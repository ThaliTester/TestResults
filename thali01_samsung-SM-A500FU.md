#### Test 54970261c23922d_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
E/SPPClientService( 5139): ============PushLog. commonIsShipBuild. stop!
D/CscParser( 5015): getInstance fileName =/system/csc/customer.xml
E/SPPClientService( 5139): [PushClientApplication] Push log off : This is Ship build version
D/Mms/MmsConfig( 5015):  enable multiwindow = true
--------- beginning of system
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/PhotosPlugin( 5082): Loading PhotosPlugin
E/Zygote  ( 5166): MountEmulatedStorage()
E/Zygote  ( 5166): v2
D/SPPClientService( 5139): PushLog.txt file is not deleted.
I/SELinux ( 5166): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/SPPClientService( 5139): PushLog.txt file is not deleted.
D/SPPClientService( 5139): ============PushLog. stop!
I/libpersona( 5166): KNOX_SDCARD checking this for 10038
I/libpersona( 5166): KNOX_SDCARD not a persona
E/Mms/MessageUtils( 5015): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 5015): updateCountryIso : update country iso info 
I/SELinux ( 5166): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5166): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5166 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 4574:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1014): Killing 4054:com.android.calendar/u0a135 (adj 15): empty #31
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
D/Mms/MmsConfig( 5015): [end]    init() consume time = 113.863125
D/Mms/Contact( 5015): [start]    init() consume time = 1.187084
D/TimaKeyStoreProvider( 5166): TimaSignature is unavailable
D/ActivityThread( 5166): Added TimaKeyStore provider
D/PackageBroadcastService( 1970): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1970): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1970): Loading module APK com.google.android.play.games
D/TP/MmsSmsProvider( 1441): query,matched:13, calling pid = 5015
D/TP/MmsSmsProvider( 1441): match 13:Elapsed time : 5.342 ms
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/Mms/Contact( 5015): [end]    init consume time = 26.850469
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
W/ResourcesManager( 5166): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5166): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/Mms/DraftCache( 5015): [start]    rebuildCache consume time = 13.738437
D/TP/MmsSmsProvider( 1441): query,matched:12, calling pid = 5015
D/Mms/MethodReflector( 5015): getSubId is called
D/Mms/TelephonyUtils( 5015): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5015): getTelephonyProperty is called
D/Mms/DownloadManager( 5015): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5015): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5015): auto download without roaming -> true
D/Mms/DownloadManager( 5015): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 5015): getSubId is called
D/TP/MmsSmsProvider( 1441): match 12:Elapsed time : 4.213 ms
D/Mms/MethodReflector( 5015): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5015): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5015): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5015): getTelephonyProperty is called
D/Mms/DownloadManager( 5015): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5015): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5015): auto download without roaming -> true
D/Mms/DownloadManager( 5015): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5015): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5015): mAutoDownload ------> true
D/Mms/DraftCache( 5015): [end]    rebuildCache consume time = 19.673958
D/ComposerPerformance( 5015): 1451923417339 ms / [DONE] Composer constructor
E/CII     ( 5015): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 5015): ReservationManager()
I/Mms/ReservationManager( 5015): resetAfterConnected()
D/TP/MmsSmsProvider( 1441): query,matched:7, calling pid = 5015
D/TP/MmsSmsProvider( 1441): match 7:Elapsed time : 1.735 ms
W/libprocessgroup( 1014): failed to open /acct/uid_10134/pid_4574/cgroup.procs: No such file or directory
D/Mms/Conversation( 5015): [start]    init() consume time = 43.409271
W/libprocessgroup( 1014): failed to open /acct/uid_10135/pid_4054/cgroup.procs: No such file or directory
D/TP/MmsSmsProvider( 1441): deleteConversation threadId: 9223372036854775807
I/Mms/ReservationManager( 5015): getReservedSendMessageCount(): retMessageCount=0
D/TP/MmsSmsProvider( 1441): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1441): updateThread(), thread_id = 9223372036854775807
D/Mms/MmsApp( 5015): [end]    onCreate() consume time = 6.546979
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
V/TP/MmsSmsDatabaseHelper( 1441): sUpgradeVersion = 0, db.getVersion() = 81
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TP/MmsSmsProvider( 1441): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1441): need read changed broadcast:false
D/Mms/Conversation( 5015): [end]    init consume time = 7.613698
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/MessagingNotification( 5015): [start]    init() consume time = 3.93724
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/MessagingNotification( 5015): [end]    init consume time = 10.212552
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/SpamFilter( 5015): [start]    SpamFilter fill() begin consume time = 5.822292
D/TP/MmsSmsProvider( 1441): query,matched:0, calling pid = 5015
V/TP/MmsSmsProvider( 1441): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1441): match 0:Elapsed time : 1.407 ms
D/Mms/Synchronizer( 5015): [start]    doSync consume time = 4.991093
D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
D/TP/MmsSmsProvider( 1441): query,matched:400, calling pid = 5015
D/TP/MmsSmsProvider( 1441): update, matched:300, calling pid = 5015
V/TP/MmsSmsProvider( 1441): syncDBData start
V/TP/MmsSmsProvider( 1441): syncDBData sms end
V/TP/MmsSmsProvider( 1441): syncDBData mms end
V/TP/MmsSmsProvider( 1441): syncDBData end
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5192): MountEmulatedStorage()
D/Mms/ArtClassLoader( 5015): init [DONE] art
E/Zygote  ( 5192): v2
I/libpersona( 5192): KNOX_SDCARD checking this for 10072
I/libpersona( 5192): KNOX_SDCARD not a persona
I/SELinux ( 5192): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5192): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5192 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/Mms/Synchronizer( 5015): [end]    doSync consume time = 28.924636
D/Mms/SpamFilter( 5015): [end]    SpamFilter fill() finished consume time = 1.223541
E/SELinux ( 5192): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/Mms/DownloadManager( 5015): Service state changed: Bundle[mParcelledData.dataSize=744]
D/TimaKeyStoreProvider( 5192): TimaSignature is unavailable
D/Mms/DownloadManager( 5015): roaming ------> false, mSimSlot = 0
D/ActivityThread( 5192): Added TimaKeyStore provider
D/Mms/MethodReflector( 5015): getSubId is called
D/Mms/TelephonyUtils( 5015): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5015): getTelephonyProperty is called
D/Mms/DownloadManager( 5015): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5015): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5015): auto download without roaming -> true
D/Mms/DownloadManager( 5015): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5015): mAutoDownload ------> true
D/BadgeProvider( 5192): onCreate
D/BadgeProvider( 5192): DatabaseHelper
D/Mms/FreeMessageStatusReceiver( 5015): onReceive, action : android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1014): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5208): MountEmulatedStorage()
I/libpersona( 5208): KNOX_SDCARD checking this for 10047
E/Zygote  ( 5208): v2
I/libpersona( 5208): KNOX_SDCARD not a persona
I/SELinux ( 5208): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5208 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
I/SELinux ( 5208): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/Mms/MessagingNotification( 5015): checkBadgeCount unreadCount=0 badgeCount=0
E/SELinux ( 5208): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
D/TP/SmsProvider( 1441): query,matched:26, calling pid = 5015
D/TP/SmsProvider( 1441): match 26:Elapsed time : 1.296 ms
D/TP/MmsSmsProvider( 1441): query,matched:6, calling pid = 5015
D/Mms/FreeMessageReceiverService( 5015): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5015): onHandleIntent: ACTION_PACKAGE_ADDED
D/TP/MmsSmsProvider( 1441): match 6:Elapsed time : 1.305 ms
I/art     (  314): Explicit concurrent mark sweep GC freed 8718(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 654us total 22.046ms
D/TimaKeyStoreProvider( 5208): TimaSignature is unavailable
I/ActivityManager( 1014): Killing 3875:com.android.providers.calendar/u0a42 (adj 15): empty #31
D/ActivityThread( 5208): Added TimaKeyStore provider
I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 628us total 16.887ms
D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 5208): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5208): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5208): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 629us total 25.326ms
E/Zygote  ( 5224): MountEmulatedStorage()
E/Zygote  ( 5224): v2
I/libpersona( 5224): KNOX_SDCARD checking this for 10025
I/libpersona( 5224): KNOX_SDCARD not a persona
I/SELinux ( 5224): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5224 uid=10025 gids={50025, 9997} abi=armeabi-v7a
I/SELinux ( 5224): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5224): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5224): TimaSignature is unavailable
D/ActivityThread( 5224): Added TimaKeyStore provider
I/ActivityManager( 1014): Killing 4384:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
W/libprocessgroup( 1014): failed to open /acct/uid_10042/pid_3875/cgroup.procs: No such file or directory
W/ResourcesManager( 5224): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/MyFiles ( 5208): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
I/OMACP   ( 5224): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
E/installd(  283): system dir 0 : /system/app/
E/installd(  283): system dir 1 : /system/priv-app/
E/installd(  283): system dir 2 : /vendor/app/
E/installd(  283): system dir 3 : /oem/app/
I/TactileAssist( 1014): enable value -1
I/TactileAssist( 1014): internal enable value -1
I/TactileAssist( 1014): intensity value -1
I/TactileAssist( 1014): saveAppList value true
I/TactileAssist( 1014): List of disabled apps :
D/Mms/Omacp( 5015): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/PackageManager( 1014): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
I/OMACP   ( 5224): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 5224): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 5224): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 5224): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
E/Zygote  ( 5242): MountEmulatedStorage()
E/Zygote  ( 5242): v2
I/OMACP   ( 5224): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/libpersona( 5242): KNOX_SDCARD checking this for 10053
I/OMACP   ( 5224): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/libpersona( 5242): KNOX_SDCARD not a persona
I/SELinux ( 5242): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/OMACP   ( 5224): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/SELinux ( 5242): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5242 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
I/OMACP   ( 5224): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
E/SELinux ( 5242): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1014): failed to open /acct/uid_10150/pid_4384/cgroup.procs: No such file or directory
I/OMACP   ( 5224): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 5224): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
D/TimaKeyStoreProvider( 5242): TimaSignature is unavailable
I/OMACP   ( 5224): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 5224): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
D/ActivityThread( 5242): Added TimaKeyStore provider
I/OMACP   ( 5224): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
W/ResourcesManager( 5242): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/Compatibility( 5242): onReceive() it will make start service
D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
D/Compatibility( 5242): onHandleIntent()
D/Compatibility( 5242): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10175, android.intent.extra.user_handle=0}]
D/ActivityManager( 1014): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/Compatibility( 5242): found: 2
I/UpdateIcingCorporaServi( 4695): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/SL_DEBUG( 5166): isLoggable:: isProductShip = 1
D/Compatibility( 5242): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
I/SL_DEBUG( 5166): isLoggable:: SL_DEBUG_EXIST = false
D/Compatibility( 5242): skipping ResolveInfo{3a5ed637 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5242): considering ResolveInfo{253027a4 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5242): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5242): enabling receiver ResolveInfo{e6d090d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5242): enabling receiver ResolveInfo{2a3d00c2 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5242): enabling receiver ResolveInfo{2a409ed3 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5242): enabling receiver ResolveInfo{181a1a10 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5242): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ChimeraCfgMgr( 1970): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1970): Module APK com.google.android.play.games already loaded
D/ActivityThread( 5166): Loading provider com.samsung.android.sdk.samsunglink.provider.SLinkMedia: com.mfluent.asp.datamodel.ASPMediaStoreProvider
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 1970): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/AsyncTaskServiceImpl( 1970): Submit a task: k
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 1970): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 1970): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/k       ( 1970): Processing package: com.test.thalitest
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/BaseAppContext( 1970): Using Auth Proxy for data requests.
W/BaseAppContext( 1970): Using Auth Proxy for data requests.
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/GassUtils( 1970): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
D/k       ( 1970): Found info for package com.test.thalitest in db.
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ContextImpl( 5166): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5166): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/BaseAppContext( 1970): Using Auth Proxy for data requests.
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
I/PeopleDatabaseHelper( 1970): cleanUpNonGplusAccounts done.
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
I/UpdateIcingCorporaServi( 4695): UpdateCorporaTask done [took 338 ms] updated apps [took 338 ms] 
W/BaseAppContext( 1970): Using Auth Proxy for data requests.
W/BaseAppContext( 1970): Using Auth Proxy for data requests.
I/ActivityManager( 1014): Killing 4299:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
W/BaseAppContext( 1970): Using Auth Proxy for data requests.
W/BaseAppContext( 1970): Using Auth Proxy for data requests.
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5285): MountEmulatedStorage()
E/Zygote  ( 5285): v2
I/libpersona( 5285): KNOX_SDCARD checking this for 10041
I/libpersona( 5285): KNOX_SDCARD not a persona
I/SELinux ( 5285): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5285): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5285): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=5285 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/TimaKeyStoreProvider( 5285): TimaSignature is unavailable
D/ActivityThread( 5285): Added TimaKeyStore provider
W/libprocessgroup( 1014): failed to open /acct/uid_10040/pid_4299/cgroup.procs: No such file or directory
I/SA      ( 5285): [SSP] onCreated
I/ActivityManager( 1014): Killing 4445:com.google.android.gm/u0a101 (adj 15): empty #31
I/SA      ( 5285): [TPM] There is no property file
I/SA      ( 5285): [SCU] isHaveSA() - false
I/SA      ( 5285): [TPM] getModelProperty : null
I/SA      ( 5285): [TPM] getCSCProperty : null
I/SA      ( 5285): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 5285): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 5285): [DM] TFT FEATURE: false
I/SA      ( 5285): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 5285): [DM] init START
I/SA      ( 5285): [DM] This device is not a Vodafone
W/ResourceType( 5285): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 5285): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 5285): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 5285): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 5285): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 5285): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 5285): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 5285): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 5285): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 5285): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 5285): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 5285): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 5285): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 5285): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 5285): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 5285): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 5285): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 5285): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 5285): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 5285): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 5285): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 5285): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 5285): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 5285): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 5285): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 5285): [SCU] isHaveSA() - false
I/SA      ( 5285): support phone number id : false
I/SA      ( 5285): [DM] Supports Ref Jpn : true
I/SA      ( 5285): [DM] init END
I/SA      ( 5285): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 5285): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10175 extra.user_handle.:0 ]
D/AndroidRuntime( 5277): 
D/AndroidRuntime( 5277): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5277): CheckJNI is OFF
D/AndroidRuntime( 5277): readGMSProperty: start
D/AndroidRuntime( 5277): readGMSProperty: already setted!!
D/AndroidRuntime( 5277): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5277): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5277): readGMSProperty: end
D/AndroidRuntime( 5277): addProductProperty: start
W/GAV2    ( 5082): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/art     ( 1014): Explicit concurrent mark sweep GC freed 223212(14MB) AllocSpace objects, 4(4MB) LOS objects, 33% free, 27MB/40MB, paused 2.544ms total 176.982ms
I/ActivityManager( 1014): Killing 4203:com.google.android.music:main/u0a111 (adj 15): empty #31
W/libprocessgroup( 1014): failed to open /acct/uid_10101/pid_4445/cgroup.procs: No such file or directory
E/SQLiteLog( 5082): (283) recovered 24 frames from WAL file /data/data/com.google.android.apps.docs/databases/DocList.db-wal
E/AffinityControl( 5277): AffinityControl: registerfunction enter
D/AndroidRuntime( 5277): Calling main entry com.android.commands.am.Am
W/libprocessgroup( 1014): failed to open /acct/uid_10111/pid_4203/cgroup.procs: No such file or directory
E/PersonaManagerService( 1014): inState():  stateMachine is null !!
I/PersonaManagerService( 1014): PersonaId don't exist
I/ActivityManager( 1014): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1014): mDVFSHelper.acquire()
I/SurfaceFlinger(  257): id=9 createSurf (16x16),-1 flag=20004, EimLayer(Di
I/SurfaceFlinger(  257): id=10 createSurf (16x16),-1 flag=20004, EimLayer(An
D/FocusedStackFrame( 1014): Set to : 0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1014): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1014): *FMB* installDecor flags : 25362712
E/Zygote  ( 5321): MountEmulatedStorage()
I/libpersona( 5321): KNOX_SDCARD checking this for 10175
E/Zygote  ( 5321): v2
I/libpersona( 5321): KNOX_SDCARD not a persona
D/PhoneWindow( 1014): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1014): *FMB* isFloatingMenuEnabled return false
I/SELinux ( 5321): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SurfaceFlinger(  257): id=11 createSurf (720x1280),1 flag=404, uhalitest
I/ActivityManager( 1014): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5321 uid=10175 gids={50175, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5321): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
E/SELinux ( 5321): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/InputDispatcher( 1014): Focused application set to: xxxx
D/InputDispatcher( 1014): Focus left window: 1466
D/AndroidRuntime( 5277): Shutting down VM
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 5321): TimaSignature is unavailable
D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/ActivityThread( 5321): Added TimaKeyStore provider
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
E/Zygote  ( 5341): MountEmulatedStorage()
E/Zygote  ( 5341): v2
I/libpersona( 5341): KNOX_SDCARD checking this for 10100
I/libpersona( 5341): KNOX_SDCARD not a persona
I/SELinux ( 5341): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5341): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=5341 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
E/SELinux ( 5341): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Killing 3677:com.google.android.talk/u0a104 (adj 15): empty #31
D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
V/WindowManager( 1014): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1014): Display changed displayId=0
W/GAV2    ( 5082): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/TimaKeyStoreProvider( 5341): TimaSignature is unavailable
D/ActivityThread( 5341): Added TimaKeyStore provider
D/PersonaManager( 1014): isKioskContainerExistOnDevice
D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WindowOrientationListener( 1014):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/PackageIntentReceiver( 5341): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5341): Not GearManger package! 
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
W/AccountFeatureHelper( 5082): Write apps_features disabled false
I/SurfaceFlinger(  257): id=6 Removed Mauncher (5/9)
I/SurfaceFlinger(  257): id=6 Removed Mauncher (-2/9)
V/ActivityThread( 1466): updateVisibility : ActivityRecord{34dfd515 token=android.os.BinderProxy@36198fb9 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1466): onTrimMemory. Level: 20
E/Zygote  ( 5361): MountEmulatedStorage()
E/Zygote  ( 5361): v2
I/libpersona( 5361): KNOX_SDCARD checking this for 1000
I/libpersona( 5361): KNOX_SDCARD not a persona
I/SELinux ( 5361): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5361): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=5361 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 5361): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5361): TimaSignature is unavailable
D/ActivityThread( 5361): Added TimaKeyStore provider
W/art     ( 5277): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/WebViewFactory( 5321): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5376): MountEmulatedStorage()
I/ActivityManager( 1014): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5376 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 5376): v2
I/ActivityManager( 1014): Killing 4756:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
I/libpersona( 5376): KNOX_SDCARD checking this for 1000
I/libpersona( 5376): KNOX_SDCARD not a persona
I/SELinux ( 5376): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5376): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5376): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5376): TimaSignature is unavailable
,I/LibraryLoader( 5321): Time to load native libraries: 2 ms (timestamps 5475-5477)
I/LibraryLoader( 5321): Expected native library version number "",actual native library version number ""
D/ActivityThread( 5376): Added TimaKeyStore provider
,W/libprocessgroup( 1014): failed to open /acct/uid_10104/pid_3677/cgroup.procs: No such file or directory
,V/WebViewChromiumFactoryProvider( 5321): Binding Chromium to main looper Looper (main, tid 1) {e6d090d}
,I/LibraryLoader( 5321): Expected native library version number "",actual native library version number ""
,I/chromium( 5321): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/AcmsPackageEventListener( 5376): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 5376): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,W/libprocessgroup( 1014): failed to open /acct/uid_10069/pid_4756/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,I/BrowserStartupController( 5321): Initializing chromium process, singleProcess=true
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink,
W/art     ( 5321): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5321): ApplicationContext is null in ApplicationStatus
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/AcmsService( 5376): Enter Oncreate
,D/AcmsServiceMonitor( 5376): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 5376): creating AcmsCore
,D/AcmsCore( 5376): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 5376): AcmsCore
,W/chromium( 5321): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,D/AcmsCore( 5376): init
,D/AcmsCore( 5376): Looper handler is not null
D/AcmsCore( 5376): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5376): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5376): Incrementing - Counter value: 1
D/AcmsCore( 5376): Incremented Counter Value: postToAcmsCoreHandler =>1
,W/GAV2    ( 5082): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/AcmsService( 5376): onStartCommand
,D/AcmsService( 5376): Action: android.intent.action.PACKAGE_ADDED
,D/AcmsServiceMonitor( 5376): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 5376): Incrementing - Counter value: 2
,D/AcmsService( 5376): Incremented Counter Value : onStartCommand
,W/chromium( 5321): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 5321): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,I/chromium( 5321): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,D/AcmsCertificateMngr( 5376): AcmsCertificateMngr
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
I/Adreno-EGL( 5321): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5321): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5321): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5321): Local Branch: 
I/Adreno-EGL( 5321): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5321): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5321):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/ActivityThread( 5376): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsRevocationMngr( 5376): AcmsRevocationMngr
,I/splitIntent( 1014): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1014): Killing 4788:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,D/AcmsService( 5376): Inside handle Intent
D/AcmsService( 5376): App added - package name: com.test.thalitest
D/AcmsCore( 5376): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5376): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5376): Incrementing - Counter value: 3
D/AcmsCore( 5376): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 5376): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 5376): Decrementing - Counter value: 2
,D/BluetoothAdapter( 5321): 140404494: getState() :  mService = null. Returning STATE_OFF
,I/Icing   ( 1970): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_4788/cgroup.procs: No such file or directory
,I/Icing   ( 1970): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
,I/Icing   ( 1970): Indexing 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD from com.google.android.googlequicksearchbox
,W/chromium( 5321): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,D/ChimeraCfgMgr( 1970): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1970): Module APK com.google.android.play.games already loaded
,W/ActivityManager( 1014): Activity pause timeout for ActivityRecord{3164e89c u0 com.test.thalitest/.MainActivity t2}
,W/art     ( 5321): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5321): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 5321): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 5321): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 5321): CordovaWebView is running on device made by: samsung
,W/art     ( 5321): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5321): Attempt to remove local handle scope entry from IRT, ignoring
,I/Mms/MmsApp( 5015):  start initViewCache mms
D/Mms/ComposeMessageFragment( 5015): [start]    fillCache consume time = 1937.702708
D/Mms/ComposeMessageFragment( 5015): fillCache, easy = false
,I/Icing   ( 1970): Indexing done 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD
,D/OpenGLRenderer( 5321): Render dirty regions requested: true
,D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/ActivityThread( 5321): updateVisibility : ActivityRecord{19b8afbe token=android.os.BinderProxy@4302740 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 5321): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5321): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1014): Focus entered window: 5321
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 5321): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5321): Initialized EGL, version 1.4
,D/AbsListView( 5015): Get MotionRecognitionManager
,D/OpenGLRenderer( 5321): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5321): Enabling debug mode 0
,D/MotionRecognitionService( 1014):  ssp status : false
,D/Mms/ComposeMessageFragment( 5015): [end]    fillCache consume time = 95.298021
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4341, temperature: 237, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SamsungIME( 1823): getCurrentCandidateView
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/IInputConnectionWrapper( 5321): showStatusIcon on inactive InputConnection
,I/Timeline( 5321): Timeline: Activity_idle id: android.os.BinderProxy@4302740 time:76065
,I/ActivityManager( 1014): Displayed Component not be shown by security: +781ms (total +890ms)
,W/ActivityManager( 1014): mDVFSHelper.release()
,I/Timeline( 1014): Timeline: Activity_windows_visible id: ActivityRecord{3164e89c u0 com.test.thalitest/.MainActivity t2} time:76070
,I/SurfaceFlinger(  257): id=11 Removed uhalitest (7/9)
,I/SurfaceFlinger(  257): id=11 Removed uhalitest (-2/9)
,D/Mms/BubbleViewCache( 5015): fillCache bubble = 1
,W/BindingManager( 5321): Cannot call determinedVisibility() - never saw a connection for the pid: 5321
,D/SamsungIME( 1823): Dismiss ExpandCandiate
,D/JsMessageQueue( 5321): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1823): getDebugLevel  : 0x4f4c
,I/ActivityManager( 1014): Killing 4906:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,I/SamsungIME( 1823): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1823): KeybaordView init() : load resources
,I/SamsungIME( 1823): getCurrentKeyboard
I/SamsungIME( 1823): getTextKeyboard
,D/jxcore_app_log( 5321): JniHelper::setJavaVM(0xb7ee3450), pthread_self() = -1203549384
,D/JX-Cordova( 5321): jxcore cordova android initializing
,D/SamsungIME( 1823): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/libprocessgroup( 1014): failed to open /acct/uid_10142/pid_4906/cgroup.procs: No such file or directory
,E/SMD     (  287): DCD OFF
,D/SamsungIME( 1823): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/jxcore-log( 5321): Initializing JXcore engine
W/jxcore-log( 5321): JXcore engine is ready
,W/jxcore-log( 5321): Starting JXcore engine
,E/audit   ( 1893): type=1400 msg=audit(1451923421.234:203): avc:  denied  { ioctl } for  pid=5321 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1893):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1893): type=1300 msg=audit(1451923421.234:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=bef72d58 items=0 ppid=314 ppcomm=main pid=5321 auid=4294967295 uid=10175 gid=10175 euid=10175 suid=10175 fsuid=10175 egid=10175 sgid=10175 fsgid=10175 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1893): type=1320 msg=audit(1451923421.234:203): 
,D/AcmsKeyStoreHelper( 5376):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 5376): Key Store exist
I/AcmsKeyStoreHelper( 5376): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 5376):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 5376): getKeyStoreForApplication success 
D/AcmsCore( 5376): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5376): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5376): Decrementing - Counter value: 1
D/AcmsCore( 5376): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 5376): This is NOT a valid MirrorLink app
D/AcmsCore( 5376): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5376): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5376): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5376): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 5376): getSvcCounter - Counter value: 0
,D/AcmsService( 5376): Enter onDestroy
I/AcmsService( 5376): cleanUp(): inside service clean up
D/AcmsCore( 5376): AcmsCore: inside DeInit
,D/AcmsCore( 5376): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5376): AcmsCertificateMngr: inside cleanup
,D/AcmsRevocationMngr( 5376): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5376): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5376): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 5376): getSvcCounter - Counter value: 0
D/AcmsService( 5376): killing acms process
I/Process ( 5376): Sending signal. PID: 5376 SIG: 9
,W/jxcore-log( 5321): Platform android
W/jxcore-log( 5321): 
,W/jxcore-log( 5321): Process ARCH arm
W/jxcore-log( 5321): 
,I/ActivityManager( 1014): Process ACMS.Process (pid 5376)(adj 0) has died(50,1175)
,E/Watchdog( 1014): !@Sync 2
,V/AlarmManager( 1014): waitForAlarm result :8
,V/AlarmManager( 1014): No more alarm at this time.nowELAPSED=78344 batch.start=82766
,I/jxcore-log( 5321): JXcore Cordova bridge is ready!
I/jxcore-log( 5321): 
W/jxcore-log( 5321): JXcore engine is started
,I/chromium( 5321): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,I/jxcore-log( 5321): Toggling radios to true
I/jxcore-log( 5321): 
,D/BluetoothAdapter( 5321): enable()
,W/ActivityManager( 1014): Permission Denial: getCurrentUser() from pid=5321, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 1014): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 1014): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5321, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 1014): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24778)
W/BluetoothManagerService( 1014): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
W/BluetoothManagerService( 1014): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
W/BluetoothManagerService( 1014): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/BluetoothManagerService( 1014): 	at android.os.Binder.execTransact(Binder.java:461)
,E/DevicePolicyManagerService( 1014): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 1014): getAllowBluetoothMode - value retunrs : 2
,D/SettingsProvider( 1014): name = bluetooth_on
,E/DevicePolicyManagerService( 1014): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService( 1014): getAllowBluetoothMode - value retunrs : 2
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1014): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5438 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,E/Zygote  ( 5438): MountEmulatedStorage()
I/libpersona( 5438): KNOX_SDCARD checking this for 1002
E/Zygote  ( 5438): v2
I/libpersona( 5438): KNOX_SDCARD not a persona
,I/SELinux ( 5438): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5438): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/SecContentProvider( 1014): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1014): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1014): mCursor = null
,D/WifiService( 1014): setWifiEnabled: true pid=5321, uid=10175
W/ActivityManager( 1014): Permission Denial: getCurrentUser() from pid=5321, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1014): Failed getting userId using ActivityManagerNative
W/WifiService( 1014): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5321, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1014): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24778)
W/WifiService( 1014): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1014): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1014): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1014): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1014): name = wifi_on
,E/SELinux ( 5438): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/WifiHW  ( 1014): ##################### set firmware type 0 #####################
,I/WifiService( 1014): disconnect: pid=5321, uid=10175
,I/jxcore-log( 5321): Radios toggled
I/jxcore-log( 5321): 
,D/TimaKeyStoreProvider( 5438): TimaSignature is unavailable
,D/ActivityThread( 5438): Added TimaKeyStore provider
,W/ResourcesManager( 5438): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.,
W/ResourcesManager( 5438): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/BluetoothA2dpSinkServiceJni( 5438): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig( 5438): Adding GattService
,D/BtSettings.ProfileConfig( 5438): Adding HeadsetService
,D/BtSettings.ProfileConfig( 5438): Adding A2dpService
,D/BtSettings.ProfileConfig( 5438): Adding HidService
,D/BtSettings.ProfileConfig( 5438): Adding HealthService
,D/BtSettings.ProfileConfig( 5438): Adding PanService
,D/BtSettings.ProfileConfig( 5438): Adding BluetoothMapService
,D/BtSettings.ProfileConfig( 5438): Adding SapService
,D/BtSettings.ProfileConfig( 5438): Adding HeadsetClientService
,D/BtSettings.ProfileConfig( 5438): Adding A2dpSinkService
,D/BtSettings.ProfileConfig( 5438): Adding SapClientService
,D/BtSettings.ProfileConfig( 5438): Adding HidDevService
,I/BtSettings.ProfileConfig( 5438): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider( 1014): name = bt_svcst_com.android.bluetooth.gatt.GattService
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1002
,D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/SettingsProvider( 1014): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService,
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1002
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1014): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1002
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1014): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1002
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/SettingsProvider( 1014): name = bt_svcst_com.android.bluetooth.hdp.HealthService
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1002
,D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1014): ret = -1
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/SettingsProvider( 1014): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1002
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1014): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1002
,D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1014): name = bt_svcst_com.broadcom.bt.service.sap.SapService
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1002
,D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1014): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1002
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/SettingsProvider( 1014): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
,D/SettingsProvider( 1014): selectionArgs: 1002
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1014): ret = -1
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1014): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1002
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1014): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1002
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/BluetoothAdapterState( 5438): make
,I/bluedroid( 5438): init
,I/BluetoothAdapterState( 5438): Entering OffState
,I/bte_conf( 5438): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 5438): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 5438): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 5438): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
E/bt-btif ( 5438): btif_fetch_local_ble_random_bdaddr
,I/bluedroid( 5438): get_profile_interface socket
I/bluedroid( 5438): get_profile_interface map_client
,D/BluetoothAdapterService( 5438): checkAddrForIOP: Loading from conf
,I/GKI_LINUX( 5438): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 5438): Address is:7C:F9:0E:37:96:AB
,E/BluetoothServiceJni( 5438): populateRssiValuesNative
I/bluedroid( 5438): getModelRssiValues
E/BluetoothServiceJni( 5438): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 5438): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/BluetoothAdapterProperties( 5438): Name is: A5-1
,D/SettingsProvider( 1014): name = bluetooth_name
,D/BluetoothA2dp( 5438): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1014): bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/bluedroid( 5438): config_hci_snoop_log
,D/BluetoothManagerService( 1014): Broadcasting onBluetoothServiceUp() to 9 receivers.
,D/BluetoothManagerService( 1014): Ble is always on enable gatt
,I/BluetoothManagerService( 1014): enableGattForLeMode, doBind called
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,E/DevicePolicyManagerService( 1014): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService( 1014): getAllowBluetoothMode - value retunrs : 2
,I/BtGatt.JNI( 5438): classInitNative(L900): classInitNative: Success!
,D/SecContentProvider( 1014): uri = 3 selection = isBluetoothEnabled
,D/BluetoothAdapterState( 5438): CURRENT_STATE=OFF, MSG = USER_TURN_ON
D/BluetoothAdapterProperties( 5438): Setting state to 11
I/BluetoothAdapterState( 5438): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 5438): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5438): updateAdapterState state is 11
,D/BluetoothManagerService( 1014): Broadcasting onBluetoothServiceUp() to 0 receivers.
D/BluetoothAdapterService( 5438): Autoconnection is available 
D/BluetoothAdapterService( 5438): updateAdapterState prevState = 10newState = 11
,W/InputMethodManagerService( 1014): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1014): [BT Setting State] State =11
,D/BluetoothSecureManager( 5438): getInstant: null
,D/BluetoothSecureManager( 5438): calling getMethod for getService
D/BluetoothSecureManager( 5438): calling getService
D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1177): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1177):  getBluetoothState : 11
D/BluetoothSecureManager( 5438): getService return binder: android.os.BinderProxy@262449e6
,D/BluetoothSecureManagerService( 1014): isSecureModeEnabled
,D/BluetoothSecureManagerService( 1014): getSecureModeSetting, name: secure_mode_enable
,D/BtConfig.SecureMode( 5438): isSecureModeOn:false
D/BtSettings.ProfileConfig( 5438): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 5438): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5438): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 5438): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5438): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,I/SamsungIME( 1823): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 1177): onStateChanged: Bluetooth
,W/BluetoothAdapterService( 5438): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5438): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5438): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 5438): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,D/StatusBarManagerService( 1014): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1014): setIconVisibility slot=bluetooth visible=false
,W/BluetoothAdapterService( 5438): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5438): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 5438): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5438): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5438): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/PhoneStatusBar( 1177): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
D/BtSettings.ProfileConfig( 5438): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5438): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5438): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 5438): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 5438): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 5438): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5438): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 5438): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5438): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 5438): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,D/BluetoothNotiBroadcastReceiver( 1279): onReceive
,D/BluetoothBondStateMachine( 5438): make
,V/BluetoothStatusReceiver( 1177): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothStatusReceiver( 1177): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/BluetoothAdapterService( 5438): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/BtSettings.ProfileConfig( 5438): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
I/BluetoothBondStateMachine( 5438): StableState(): Entering Off State
W/BluetoothAdapterService( 5438): Not skipping com.android.bluetooth.gatt.GattService
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5476): MountEmulatedStorage()
,E/Zygote  ( 5476): v2
I/libpersona( 5476): KNOX_SDCARD checking this for 10003
I/libpersona( 5476): KNOX_SDCARD not a persona
,I/SELinux ( 5476): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=5476 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
I/SELinux ( 5476): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/BluetoothAdapterService( 5438): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5438): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 5438): Not skipping com.android.bluetooth.hfp.HeadsetService
E/SELinux ( 5476): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/BtGatt.DebugUtils( 5438): handleDebugAction() action=null
D/BtGatt.GattService( 5438): Received start request. Starting profile...
D/BtGatt.GattService( 5438): start()
D/BtGatt.GattService( 5438): start()
I/bluedroid( 5438): get_profile_interface gatt
,D/BluetoothAdapterService( 5438): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@181a1a10
D/BtGatt.AdvertiseManager( 5438): advertise manager created
,D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5438): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5438): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 5438): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5438): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5438): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 5438): Not skipping com.android.bluetooth.hid.HidService
D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5438): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5438): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 5438): Not skipping com.android.bluetooth.hdp.HealthService
D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5438): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 5438): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 5438): Not skipping com.android.bluetooth.pan.PanService
,D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BtGatt.GattService( 5438): mStartError = false
D/BluetoothAdapterService( 5438): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@181a1a10
W/BluetoothAdapterService( 5438): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5438): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 5438): Not skipping com.android.bluetooth.map.BluetoothMapService
,D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 5438): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5438): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5438): Not skipping com.broadcom.bt.service.sap.SapService
D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/TimaKeyStoreProvider( 5476): TimaSignature is unavailable
,D/Tethering( 1014): interfaceAdded wlan0
D/ActivityThread( 5476): Added TimaKeyStore provider
,W/BluetoothAdapterService( 5438): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
D/BtSettings.ProfileConfig( 5438): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5438): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5438): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5438): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5438): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5438): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5438): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5438): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5438): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 5438): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
W/BluetoothAdapterService( 5438): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/Tethering( 1014): interfaceStatusChanged wlan0, false
I/BluetoothAdapterState( 5438): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/WifiHW  (  277): wifi_change_fw_path(): fwpath = sta
D/SoftapController(  277): Softap fwReload - Ok
,D/HeadsetService( 5438): Received start request. Starting profile...
D/HeadsetService( 5438): start()
,I/BluetoothHeadsetServiceJni( 5438): classInitNative: succeeds
,E/Tethering( 1014): No numeric data
D/CommandListener(  277): Setting iface cfg
D/CommandListener(  277): Trying to bring down wlan0
,D/HeadsetStateMachine( 5438): make
D/Tethering( 1014): sendTetherStateChangedBroadcast 1, 0, 0,
D/Tethering( 1014): clearTetheredNotification()
,D/CommandListener(  277): Clearing all IP addresses on wlan0,
D/Tethering( 1014): InitialState.processMessage what=4
D/Tethering( 1014): interfaceAdded p2p0
D/NtpTrustedTime( 1014): forceRefresh() from cache miss
D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
E/HeadsetStateMachine( 5438): # of Max HF connection is 2
D/HotspotTile( 1177): updateTetherState():false, false
,E/Tethering( 1014): No numeric data
D/Tethering( 1014): p2p0 is not a tetherable iface, ignoring
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
D/Tethering( 1014): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1014): clearTetheredNotification()
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,E/WifiHW  ( 1014): supplicant_name : p2p_supplicant
V/NetworkStats( 1014): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1014): forceRefresh Fail.
D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---
D/Tethering( 1014): interfaceLinkStateChanged p2p0, false
I/Nat464Xlat( 1014): interfaceLinkStateChanged p2p0, false
D/Tethering( 1014): interfaceStatusChanged p2p0, false
,V/NetworkStats( 1014): performPollLocked() took 5ms
,D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1177): updateTetherState():false, false
,D/ActivityManager( 1014): bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,D/NtpTrustedTime( 1014): forceRefresh() from cache miss
,D/NtpTrustedTime( 1014): forceRefresh() from cache miss
D/NtpTrustedTime( 1014): forceRefresh Fail.
D/NtpTrustedTime( 1014): forceRefresh Fail.
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
V/NetworkStats( 1014): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---
,D/ActivityManager( 1014): bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,I/bluedroid( 5438): get_profile_interface handsfree
V/NetworkStats( 1014): performPollLocked() took 4ms
,D/NtpTrustedTime( 1014): forceRefresh() from cache miss
,D/NtpTrustedTime( 1014): forceRefresh Fail.
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,D/UserAnalysis.PlaceProvider( 5476): PlaceProvider onCreate()
I/DualScoManager( 5438): Instantiating Dual Sco Manager
I/DualScoManager( 5438): Set HeadsetServiceHelper
D/BluetoothAtMessage( 5438): createCMTIContentObservers
,D/SettingsProvider( 1014): name = bluetooth_hfp_allowed_bvra
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1002
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
D/HeadsetStateMachine( 5438): Enter Disconnected: -2
D/HeadsetService( 5438): mStartError = false
D/BluetoothAdapterService( 5438): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@181a1a10
I/wpa_supplicant( 5497): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 5497): Successfully initialized wpa_supplicant
I/SecureStorage( 5497): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,D/BluetoothA2dp( 2699): Proxy object connected
,D/BluetoothA2dp( 1014): Proxy object connected,
,D/A2dpService( 5438): Received start request. Starting profile...
,D/A2dpService( 5438): start()
D/HeadsetStateMachine( 5438): Clear mHeadsetBrsf
D/HeadsetStateMachine( 5438): map size, before remove : 0
D/HeadsetStateMachine( 5438): map size, after remove: 0
D/UserAnalysis.SecureDbManager( 5476): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 5476): SecurePlaceDbHelper() 
D/UserAnalysis( 5476): Create SecureDbHelper
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/BluetoothAvrcpServiceJni( 5438): classInitNative: succeeds
D/IntelligenceServiceApplication( 5476): onCreate()
I/bluedroid( 5438): get_profile_interface avrcp
,D/WifiMonitor( 1014): startMonitoring(wlan0) with mConnected = false
I/SecureStorage( 5497): [INFO]: SPID(0x00000000)This device supports Secure Storage
E/RemoteController( 5438): Cannot set synchronization mode on an unregistered RemoteController
,D/IntelligenceServiceApplication( 5476): no applications having user consent for prediction
,I/SecureStorage(  386): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5497
I/SecureStorage(  386): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
I/SecureStorage( 5497): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 5497): ssSupport state is = 1
I/wpa_supplicant( 5497): >>>>> GET KEY, IV <<<<<
I/SecureStorage( 5497): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  386): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5497
I/SecureStorage(  386): [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1177): Wifi onReceive(2)
D/HotspotTile( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 1177): onStateChanged: Wi-Fi
D/HotspotTile( 1177): onReceive : 2, 0
,I/ActivityManager( 1014): Killing 4889:com.google.android.gms:car/u0a12 (adj 15): empty #31
D/WifiCredService( 1279): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,V/PlaceDetection v1.0.19 ( 5476): [PlaceDetection::stopService] Service stopped.
,I/Avrcp   ( 5438):  Updating now playing list upon AVRCP Start
,D/BluetoothMediaBrowser( 5438):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,I/BluetoothA2dpServiceJni( 5438): classInitNative: succeeds
D/A2dpStateMachine( 5438): make
,I/bluedroid( 5438): get_profile_interface a2dp
,I/GKI_LINUX( 5438): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 5438): warning : media task started media_task_refcnt 1 
,D/A2dpService( 5438): mStartError = false
D/BluetoothAdapterService( 5438): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@181a1a10
,I/BluetoothHidServiceJni( 5438): classInitNative: succeeds
,D/A2dpStateMachine( 5438): Enter Disconnected: -2
,D/HidService( 5438): Received start request. Starting profile...
D/HidService( 5438): start()
I/bluedroid( 5438): get_profile_interface hidhost
D/HidService( 5438): setHidService(): set to: null
D/HidService( 5438): mStartError = false
D/BluetoothAdapterService( 5438): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@181a1a10
I/BluetoothHealthServiceJni( 5438): classInitNative: succeeds
,D/HealthService( 5438): Received start request. Starting profile...
D/HealthService( 5438): start()
,I/bluedroid( 5438): get_profile_interface health
D/HealthService( 5438): mStartError = false
D/BluetoothAdapterService( 5438): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@181a1a10
,E/BluetoothAdapterService(404363792)( 5438): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,D/BluetoothMediaBrowser( 5438): no now playing list
D/BluetoothMediaBrowser( 5438):  getNowPlayingId now playing id : -1
,I/BluetoothPanServiceJni( 5438): classInitNative(L105): succeeds
,V/PlaceDetection v1.0.19 ( 5476): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/PanService( 5438): Received start request. Starting profile...
,D/PanService( 5438): start()
D/BluetoothPanServiceJni( 5438): initializeNative(L110): pan
I/bluedroid( 5438): get_profile_interface pan
D/PanService( 5438): mStartError = false
D/BluetoothAdapterService( 5438): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@181a1a10
,D/BluetoothPan( 1014): BluetoothPAN Proxy object connected
,D/BluetoothMapService( 5438): Received start request. Starting profile...
,D/BluetoothMapService( 5438): start()
,D/BluetoothMapService( 5438): mStartError = false
,D/BluetoothAdapterService( 5438): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@181a1a10
,I/BluetoothSAPServiceJni( 5438): classInitNative(L204): succeeds
,D/SapService( 5438): Received start request. Starting profile...
D/SapService( 5438): start()
D/BluetoothSAPServiceJni( 5438): initializeNative(L209): sap
I/bluedroid( 5438): get_profile_interface sap
D/SapService( 5438): mStartError = false
D/BluetoothAdapterService( 5438): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@181a1a10
,D/HeadsetStateMachine( 5438): Try to query the phonestate on bind
,I/Telecom ( 1418): BluetoothPhoneService: queryPhoneState
,I/Telecom ( 1418): BluetoothPhoneService: handleMessage(7) / param 0
,I/Telecom ( 1418): BluetoothPhoneService: updateHeadsetWithCallState
,I/Telecom ( 1418): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,I/Telecom ( 1418): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,I/Telecom ( 1418): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothHeadset( 1418): Proxy not attached to service
,I/Telecom ( 1418): BluetoothPhoneService: Result of Message : true
,D/HeadsetStateMachine( 5438): Proxy object connected
,D/HeadsetPhoneState( 5438): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetPhoneState( 5438): sendDeviceDataStateChanged
D/HeadsetStateMachine( 5438): Disconnected process message: 11
,D/HeadsetPhoneState( 5438): Signal level : previous=0 curr=0
,E/BluetoothAdapterService(404363792)( 5438): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,V/HeadsetService( 5438): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5438): Disconnected process message: 18
,D/BluetoothA2dp( 5438): Proxy object connected
D/BluetoothAdapterService( 5438): Bluetooth A2dp source service connected
E/BluetoothAdapterService(404363792)( 5438): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
E/BluetoothAdapterService(404363792)( 5438): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
E/BluetoothAdapterService(404363792)( 5438): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
D/HeadsetStateMachine( 5438): Disconnected process message: 10
D/HeadsetPhoneState( 5438): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 5438): Disconnected process message: 11
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5506): MountEmulatedStorage()
,E/Zygote  ( 5506): v2,
I/libpersona( 5506): KNOX_SDCARD checking this for 10107
I/libpersona( 5506): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=5506 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 5506): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
E/BluetoothAdapterService(404363792)( 5438): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,I/SELinux ( 5506): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.bluetooth, calleePkgName: com.android.email,
,E/SELinux ( 5506): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5515): MountEmulatedStorage(),
,E/Zygote  ( 5515): v2
I/libpersona( 5515): KNOX_SDCARD checking this for 10145
I/libpersona( 5515): KNOX_SDCARD not a persona
,I/SELinux ( 5515): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5515): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 5515): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=5515 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5506): TimaSignature is unavailable
D/ActivityThread( 5506): Added TimaKeyStore provider
,I/SecureStorage( 5497): [INFO]: SPID(0x00000002)Processing data has been completed
,I/SecureStorage(  386): [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,D/TimaKeyStoreProvider( 5515): TimaSignature is unavailable
,I/art     (  314): Explicit concurrent mark sweep GC freed 8716(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.761ms total 43.369ms
,D/ActivityThread( 5515): Added TimaKeyStore provider
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 644us total 19.522ms,
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 19.384ms,
,W/libprocessgroup( 1014): failed to open /acct/uid_10012/pid_4889/cgroup.procs: No such file or directory
,E/SMD     (  287): DCD OFF
,W/ResourcesManager( 5515): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5515): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5515): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5515): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5515): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/wpa_supplicant( 5497): Ctrl_iface: loading cred from phone
I/SecureStorage( 5497): [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,I/SecureStorage( 5497): [INFO]: SPID(0x00000002)This device supports Secure Storage
,I/SecureStorage(  386): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 5497
I/SecureStorage(  386): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
I/SecureStorage( 5497): [INFO]: SPID(0x00000002)SS Daemon is running
I/wpa_supplicant( 5497): ssSupport state is = 1
,I/wpa_supplicant( 5497): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
E/wpa_supplicant( 5497): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5497): SIM READ ERROR
I/wpa_supplicant( 5497): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5497): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5497): SIM READ ERROR,
I/wpa_supplicant( 5497): Blacklist: Clear (all) 
I/wpa_supplicant( 5497): wpa_default_ap_write_once
I/wpa_supplicant( 5497): There is no /data/misc/wifi/default_ap.check. Start copy default ap
I/wpa_supplicant( 5497): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5497): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant( 5497): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5497): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
I/wpa_supplicant( 5497): rfkill: Cannot open RFKILL control device
D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceStatusChanged wlan0, false
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/wpa_supplicant( 5497): wlan0: Setting scan request: 0 sec 100000 usec
,D/BadgeProvider( 5192): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,E/BluetoothAdapterService(404363792)( 5438): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,E/BluetoothAdapterService(404363792)( 5438): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,I/ActivityManager( 1014): Killing 4680:com.samsung.aasaservice/1000 (adj 15): empty #31
,D/BluetoothAdapterState( 5438): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 5438): enable
,I/bt_hci_bdroid( 5438): init
,I/GKI_LINUX( 5438): gki_task_entry task_id=0 [BTU] starting
,I/bt_vendor( 5438): bt-vendor : init
I/bt_vendor( 5438): bt-vendor : get_bt_soc_type
E/bt_vendor( 5438): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 5438): init: Local BD Address : ab:96:37:0e:f9:7c
D/bt_userial_mct( 5438): userial_init
,I/bt_vendor( 5438): bt-vendor : BT_VND_OP_POWER_CTRL: Off
,I/bt_vendor( 5438): Starting hciattach daemon
I/bt_vendor( 5438): try to set false
,I/bt_vendor( 5438): bt-vendor : BT_VND_OP_POWER_CTRL: On
,I/bt_vendor( 5438): Starting hciattach daemon
I/bt_vendor( 5438): try to set true
,D/BadgeProvider( 5192): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5192): sendNotify, [notify] : null
D/BadgeProvider( 5192): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5192): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5192): update, [UpdateCount] : 1
,D/Launcher.Model( 1466): reloadBadges entered.
,I/qcom-bluetooth( 5551): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId,
,I/qcom-bluetooth( 5558): /system/etc/init.qcom.bt.sh: Transport : smd ,
,I/qcom-bluetooth( 5559): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,I/wpa_supplicant( 5497): wlan0: State: DISCONNECTED -> DISCONNECTED,
I/SecureStorage( 5497): [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,I/qcom-bluetooth( 5562): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/SecureStorage( 5497): [INFO]: SPID(0x00000002)This device supports Secure Storage
,I/SecureStorage(  386): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 5497
I/SecureStorage(  386): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
I/SecureStorage( 5497): [INFO]: SPID(0x00000002)SS Daemon is running
I/wpa_supplicant( 5497): ssSupport state is = 1
,I/wpa_supplicant( 5497): Ctrl_iface: loading cred from phone
I/SecureStorage( 5497): [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,I/qcom-bluetooth( 5563): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,I/SecureStorage( 5497): [INFO]: SPID(0x00000002)This device supports Secure Storage,
I/SecureStorage(  386): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 5497
I/SecureStorage(  386): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,I/SecureStorage( 5497): [INFO]: SPID(0x00000002)SS Daemon is running
,I/wpa_supplicant( 5497): ssSupport state is = 1
I/wpa_supplicant( 5497): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5497): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5497): SIM READ ERROR
I/wpa_supplicant( 5497): wpa_default_ap_write_once
I/wpa_supplicant( 5497): There is no /data/misc/wifi/default_ap.check. Start copy default ap
I/wpa_supplicant( 5497): rfkill: Cannot open RFKILL control device
,I/Nat464Xlat( 1014): interfaceLinkStateChanged p2p0, false,
D/Tethering( 1014): interfaceLinkStateChanged p2p0, false
D/Tethering( 1014): interfaceStatusChanged p2p0, false
,I/Nat464Xlat( 1014): interfaceLinkStateChanged p2p0, false,
D/Tethering( 1014): interfaceLinkStateChanged p2p0, false
D/Tethering( 1014): interfaceStatusChanged p2p0, false
,I/qcom-bluetooth( 5565): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,I/qcom-bluetooth( 5566): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_4680/cgroup.procs: No such file or directory
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 26242(1389KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.777ms total 168.303ms
,I/wpa_supplicant( 5497): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant( 5497): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/wpa_supplicant( 5497): p2p0: State: INACTIVE -> DISCONNECTED
I/wpa_supplicant( 5497): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant( 5497): Skip scan - bUseNetwork false
,E/WifiStateMachine( 1014): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative-wlan0( 1014): callSECApiBoolean - ID [21]
,I/wpa_supplicant( 5497): HOTSPOT20_ENABLE called
I/wpa_supplicant( 5497): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5497): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5497): SIM READ ERROR
I/wpa_supplicant( 5497): Blacklist: Clear (all) 
,I/wpa_supplicant( 5497): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 5497): Skip scan - bUseNetwork false
,D/WifiNative-wlan0( 1014): callSECApiInt - ID [210]
,D/WifiConfigStore( 1014): Loading config and enabling all networks 
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1177): Wifi onReceive(3)
,D/STATUSBAR-QSTileView( 1177): onStateChanged: Wi-Fi
,D/HotspotTile( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1177): onReceive : 3, 0
,D/WifiCredService( 1279): Action received :android.net.wifi.WIFI_STATE_CHANGED
,E/WifiConfigStore( 1014): Not a HS20
,E/WifiConfigStore( 1014): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-wlan0( 1014): callSECApiInt - ID [65]
,D/WifiNative-wlan0( 1014): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 5497): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 5497): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 5497): reset timer : RESET_TIMER 0
I/wpa_supplicant( 5497): P2P: Current p2p state = IDLE
I/wpa_supplicant( 5497): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 5497): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 5497): First Scan Start
I/wpa_supplicant( 5497): Scan requested (ret=0) - scan timeout 30 seconds
,D/WifiNative-wlan0( 1014): Setting external_sim to 1
,D/WifiStateMachine( 1014): Setting OUI to DA-A1-19
,I/WifiNative-HAL( 1014): startHal
E/wifi    ( 1014): getStaticLongField sWifiHalHandle 0x9ca5e88c
I/WifiNative-HAL( 1014): Could not start hal
,E/WifiNative-wlan0( 1014): do suspend true
,D/WifiP2pService( 1014): P2pDisabledState{ what=131203 }
,D/CommandListener(  277): Setting iface cfg
D/CommandListener(  277): Trying to bring up p2p0
,D/WifiMonitor( 1014): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 1014): P2pEnablingState
D/WifiP2pService( 1014): P2pEnablingState{ what=147457 }
D/WifiP2pService( 1014): P2p socket connection successful
D/WifiP2pService( 1014): P2pEnabledState
,E/WifiStateMachine( 1014): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,E/WifiStateMachine( 1014): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,D/WifiNative-wlan0( 1014): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1014): invaild command id : 215
,D/WifiScanningService( 1014): SCAN_AVAILABLE : 3
,D/WifiScanningService( 1014): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1014): startHal
E/wifi    ( 1014): getStaticLongField sWifiHalHandle 0x9dd0c9bc
I/WifiNative-HAL( 1014): Could not start hal
E/WifiScanningService( 1014): could not start HAL
,D/RttService( 1014): SCAN_AVAILABLE : 3
D/RttService( 1014): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1014): sending p2p connection changed broadcast: IDLE
,E/WifiStateMachine( 1014): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/WifiDisplayController( 1014): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,D/WifiDisplayController( 1014): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1014): disconnect
,D/WifiDisplayController( 1014): updateConnection
D/WifiDisplayController( 1014): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/wpa_supplicant( 5497): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
I/wpa_supplicant( 5497): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,I/wpa_supplicant( 5497): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN,
,D/AllShareCastTile( 1177): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED,
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
,D/AllShareCastTile( 1177): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
,D/WifiP2pService( 1014): create mNetworkAgent
,I/qcom-bluetooth( 5580): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab 
,D/ConnectivityService( 1014): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} },
,D/WifiNative-p2p0( 1014): p2pGetDeviceAddress,
D/Tethering( 1014): interfaceLinkStateChanged p2p0, false
I/Nat464Xlat( 1014): interfaceLinkStateChanged p2p0, false
D/Tethering( 1014): interfaceStatusChanged p2p0, false
D/ConnectivityService( 1014): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService( 1014): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1014): updateNetworkInfo()
E/CSLegacyTypeTracker( 1014): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
D/WifiNative-p2p0( 1014): p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,I/qcom-bluetooth( 5581): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
D/WifiDisplayController( 1014): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StrictMode( 5506): StrictMode policy violation; ~duration=522 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5506): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5506): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 5506): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 5506): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 5506): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77),
D/StrictMode( 5506): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 5506): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 5506): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
D/StrictMode( 5506): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060),
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5506): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5506): ,	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5506): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5506): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5506): 	at android.os.Handler.dispatchMessage(Handler.java:102),
D/StrictMode( 5506): 	at android.os.Looper.loop(Looper.java:145),
D/StrictMode( 5506): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5506): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5506): 	at java.lang.reflect.Method.invoke(Method.java:372)
,D/StrictMode( 5506): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5506): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 5506): StrictMode policy violation; ~duration=515 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5506): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5506): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 5506): 	,at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 5506): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 5506): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 5506): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 5506): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5506): 	,at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5506): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5506): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5506): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5506): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5506): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5506): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5506): ,	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5506): ,	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5506): 	,at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5506): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5506): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/WifiP2pService( 1014): DeviceAddress: 7e:96:ac
,D/StrictMode( 5506): StrictMode policy violation; ~duration=451 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5506): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5506): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 5506): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 5506): 	at java.io.File.exists(File.java:363)
D/StrictMode( 5506): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366),
D/StrictMode( 5506): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 5506): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
D/StrictMode( 5506): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 5506): 	,at com.google.b.a.ca.a(PG:125)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
,D/StrictMode( 5506): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5506): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5506): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5506): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5506): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5506): 	at android.os.Looper.loop(Looper.java:145),
D/StrictMode( 5506): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5506): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5506): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5506): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5506): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/StrictMode( 5506): StrictMode policy violation; ~duration=450 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5506): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5506): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 5506): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 5506): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 5506): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 5506): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 5506): 	,at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 5506): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5506): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5506): ,	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5506): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5506): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5506): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5506): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5506): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5506): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5506): 	,at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5506): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5506): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/WifiDisplayController( 1014): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
D/WifiDisplayController( 1014):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1014):  primary type: 10-0050F204-5
D/WifiDisplayController( 1014):  secondary type: null
D/WifiDisplayController( 1014):  wps: 0
D/WifiDisplayController( 1014):  grpcapab: 0,
D/WifiDisplayController( 1014):  devcapab: 0
D/WifiDisplayController( 1014):  status: 3
D/WifiDisplayController( 1014):  wfdInfo: null
D/WifiDisplayController( 1014):  groupownerAddress: null
D/WifiDisplayController( 1014):  GOdeviceName: null
D/WifiDisplayController( 1014):  interfaceAddress: 
D/WifiDisplayController( 1014):  SConnectInfo : null
D/StrictMode( 5506): StrictMode policy violation; ~duration=448 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5506): ,	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5506): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 5506): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 5506): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 5506): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 5506): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 5506): 	,at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 5506): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5506): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020),
D/StrictMode( 5506): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5506): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5506): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5506): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5506): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5506): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5506): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5506): ,	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5506): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5506): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 5506): StrictMode policy violation; ~duration=446 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5506): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5506): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 5506): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 5506): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 5506): 	,at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 5506): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 5506): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 5506): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 5506): 	at com.google.v.a.a.eq.<init>(PG:23)
D/StrictMode( 5506): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 5506): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 5506): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 5506): 	at com.google.r.e.b(PG:170)
D/StrictMode( 5506): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
,D/StrictMode( 5506): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 5506): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5506): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5506): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5506): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5506): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5506): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5506): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5506): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5506): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5506): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5506): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5506): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 5506): StrictMode policy violation; ~duration=444 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5506): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5506): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 5506): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 5506): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 5506): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 5506): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 5506): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 5506): 	at com.google.r.k.b(PG:14147)
D/StrictMode( 5506): 	at com.google.r.k.c(PG:583)
D/StrictMode( 5506): 	at com.google.v.a.a.eq.<init>(PG:40)
D/StrictMode( 5506): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 5506): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 5506): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 5506): 	at com.google.r.e.b(PG:170)
D/StrictMode( 5506): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 5506): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5506): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5506): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5506): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5506): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5506): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5506): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5506): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5506): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5506): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5506): 	at com.android.internal.os.ZygoteInit$Met,hodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5506): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/WifiP2pService( 1014): sending p2p persistent groups changed broadcast
D/StrictMode( 5506): StrictMode policy violation; ~duration=408 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5506): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5506): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 5506): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 5506): 	at java.io.File.exists(File.java:363)
D/StrictMode( 5506): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 5506): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 5506): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
D/StrictMode( 5506): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
D/StrictMode( 5506): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5506): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5506): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5506): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5506): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5506): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5506): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5506): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5506): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5506): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5506): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5506): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/ActivityManager( 1014): Killing 4315:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
D/StrictMode( 5506): StrictMode policy violation; ~duration=408 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5506): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5506): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 5506): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 5506): 	at java.io.File.exists(File.java:363)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
D/StrictMode( 5506): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 5506): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 5506): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 5506): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 5506): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 5506): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 5506): 	at android.os.Handler.dispatchMessage(Handler.ja,va:102)
D/StrictMode( 5506): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 5506): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 5506): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5506): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5506): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 5506): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/WifiP2pService( 1014): InactiveState
D/WifiP2pService( 1014): InactiveState{ what=143376 }
D/WifiP2pService( 1014): P2pEnabledState{ what=143376 }
I/wpa_supplicant( 5497): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
D/AuthorizationBluetoothService( 1776): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/WifiP2pService( 1014): InactiveState{ what=143376 }
D/WifiP2pService( 1014): P2pEnabledState{ what=143376 }
E/ConnectivityService( 1014): updateNetworkInfo()
D/ActivityManager( 1014): bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Hs20UtilService( 3328): Starting #2
I/Hs20UtilService( 3328): Message received 5011
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/bt_vendor( 5438): bluetooth satus is on
D/bt_userial_mct( 5438): userial_open(port:0)
I/bt_vendor( 5438): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/bt_vendor( 5438): Done intiailizing UART
I/bt_vendor( 5438): Done intiailizing UART
,I/bt_userial_mct( 5438): CMD=65, EVT=65, ACL_Out=66, ACL_In=66
,I/bt_vendor( 5438): Bluetooth Firmware and transport layer are initialized
D/bt_userial_mct( 5438): Entering userial_read_thread()
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,I/ActivityManager( 1014): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=5586 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 5586): MountEmulatedStorage()
E/Zygote  ( 5586): v2
I/libpersona( 5586): KNOX_SDCARD checking this for 1000
I/libpersona( 5586): KNOX_SDCARD not a persona
,I/        ( 5438): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 5438): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 5438): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 5438): BTE_InitTraceLevels -- TRC_AVDT
,I/SELinux ( 5586): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/        ( 5438): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 5438): BTE_InitTraceLevels -- TRC_A2D
I/        ( 5438): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 5438): BTE_InitTraceLevels -- TRC_BTM
,I/        ( 5438): BTE_InitTraceLevels -- TRC_GAP
I/        ( 5438): BTE_InitTraceLevels -- TRC_PAN
I/        ( 5438): BTE_InitTraceLevels -- TRC_SAP
I/        ( 5438): BTE_InitTraceLevels -- TRC_SDP
I/        ( 5438): BTE_InitTraceLevels -- TRC_GATT
I/        ( 5438): BTE_InitTraceLevels -- TRC_SMP
I/        ( 5438): BTE_InitTraceLevels -- TRC_BTAPP
,I/        ( 5438): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 5438): BTE_InitTraceLevels -- TRC_PROTOCOL
,I/SELinux ( 5586): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5586): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5586): TimaSignature is unavailable
,D/ActivityThread( 5586): Added TimaKeyStore provider
,W/libprocessgroup( 1014): failed to open /acct/uid_10044/pid_4315/cgroup.procs: No such file or directory
,D/SecurityLogAgent( 5586): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 5586): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5586): StateMachine : Current State = 1
,W/bt-l2cap( 5438): l2c_link_processs_ble_num_bufs 16
,D/SecurityLogAgent( 5586): StateMachine : Changed Current State = 1
,E/bt-btm  ( 5438): BTM_SecRegister:p_cb_info->p_le_callback == 0xa40106e9 
E/bt-btm  ( 5438): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40106e9 
,D/BluetoothAdapterProperties( 5438): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,E/bt-btif ( 5438): BTM_SEC_REG[3  : sec
,E/bt-btif ( 5438): btif_storage_get_adapter_property service_mask:0x2120048
,I/ActivityManager( 1014): Killing 4591:com.samsung.android.sm/1000 (adj 15): empty #31
D/BluetoothAdapterProperties( 5438): Address is:7C:F9:0E:37:96:AB
E/BluetoothServiceJni( 5438): populateRssiValuesNative
I/bluedroid( 5438): getModelRssiValues
E/BluetoothServiceJni( 5438): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 5438): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/BluetoothAdapterProperties( 5438): Name is: A5-1
,D/SettingsProvider( 1014): name = bluetooth_name
,D/BluetoothUtils( 5438): getBtEnabledContainers(): btContainers = []
,D/BluetoothAdapterProperties( 5438): Scan Mode:20
,D/BluetoothAdapterProperties( 5438): Discoverable Timeout:120
,D/BluetoothAdapterProperties( 5438): LE Address is:FC:F3:1C:6E:2D:57
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,E/bt_mct  ( 5438): hci lib postload completed
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,E/bt-btif ( 5438): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 5438): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,E/bt-btif ( 5438): btif_sock_init: !radio_req && !rfc_init
E/bt-btif ( 5438): btif_sock_init: !vhci_init
D/IOP_DB_BT( 5438): db_open: file /etc/bluetooth/iop_bt.db
,D/IOP_DB_BT( 5438): db_open: db_open : handle 3027693584l, read 13894 bytes onto local cache
D/IOP_DB_BT( 5438): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,D/IOP_DB_BT( 5438): db_query: result 1
I/        ( 5438): iop_db_open: iop_db_open status 0
,D/bte_conf( 5438): Device ID record 1 : primary
D/bte_conf( 5438):   vendorId            = 0075
D/bte_conf( 5438):   vendorIdSource      = 0001
D/bte_conf( 5438):   product             = 0100
D/bte_conf( 5438):   version             = 0200
D/bte_conf( 5438):   clientExecutableURL = 
D/bte_conf( 5438):   serviceDescription  = 
D/bte_conf( 5438):   documentationURL    = 
D/bte_conf( 5438): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 5438): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,I/Hs20UtilService( 3328): Starting #3
,D/BluetoothAdapterState( 5438): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,D/BluetoothAdapterProperties( 5438): ScanMode =  20
,D/BluetoothAdapterProperties( 5438): State =  11
,D/SecContentProvider( 1014): uri = 3 selection = isDiscoverableEnabled
,D/BluetoothAdapterProperties( 5438): Setting state to 12
I/BluetoothAdapterState( 5438): Bluetooth adapter state changed: 11-> 12
,D/BluetoothUtils( 5438): getBtEnabledContainers(): btContainers = []
D/BluetoothAdapterProperties( 5438): Scan Mode:21
D/BluetoothAdapterProperties( 5438): Discoverable Timeout:120
,I/Hs20UtilService( 3328): Message received 5011
,D/SettingsProvider( 1014): name = bluetooth_a2dp_sink_mode
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1002
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,E/WifiStateMachine( 1014): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1014): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1014): invaild command id : 215
D/SecurityLogAgent( 5586): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5586): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5586): StateMachine : Current State = 1
D/SecurityLogAgent( 5586): StateMachine : Changed Current State = 1
,W/com.google.a.a.b.d.a( 5506): Application name is not set. Call Builder#setApplicationName.
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService( 5438): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5438): updateAdapterState state is 12
,D/NearbySettings( 1279): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/NearbySettings( 1279): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothA2dp( 2699): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 2699): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 2699): onBluetoothStateChange: Bluetooth is on
,I/NearbySettings( 1279): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/BluetoothAdapterService( 5438): Autoconnection is available 
D/BluetoothAdapterService( 5438): updateAdapterState prevState = 11newState = 12
,D/BluetoothAdapterService( 5438): starting service from this receiver
I/NearbySettings( 1279): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1279): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,I/NearbySettings( 1279): MountReceiver.onReceive - Set preference state off
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,V/NearbySettings( 1279): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothAdapterState( 5438): Entering On State from state = 11
D/BluetoothAdapter( 5321): onBluetoothStateChange: up=true
D/BluetoothAdapter( 5321): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1441): onBluetoothStateChange: up=true
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,D/BluetoothAdapter( 1441): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1014): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1014): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 5438): onBluetoothStateChange: up=true
D/BluetoothAdapter( 5438): onBluetoothStateChange: Bluetooth is on
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/BluetoothAdapter( 1418): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1418): onBluetoothStateChange: Bluetooth is on
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/BluetoothAdapter( 1426): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1426): onBluetoothStateChange: Bluetooth is on
,D/BluetoothA2dp( 1014): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1776): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1776): onBluetoothStateChange: Bluetooth is on
,E/Zygote  ( 5607): MountEmulatedStorage(),
I/libpersona( 5607): KNOX_SDCARD checking this for 10068
E/Zygote  ( 5607): v2
I/libpersona( 5607): KNOX_SDCARD not a persona
I/SELinux ( 5607): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=5607 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5607): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/BluetoothA2dp( 5438): onBluetoothStateChange: up=true
I/BluetoothPbapService( 5438): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
E/SELinux ( 5607): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/BluetoothAdapter( 1177): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1177): onBluetoothStateChange: Bluetooth is on
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_4591/cgroup.procs: No such file or directory
,W/InputMethodManagerService( 1014): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 1014): [BT Setting State] State =12
,I/InputMethodManagerService( 1014): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/BluetoothTile( 1177):  onBluetoothStateChange:
,D/BluetoothHeadset( 1418): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3beba321, true
,D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1177): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1177):  getBluetoothState : 12
,D/BluetoothHeadset( 1418): registerMessageListener
,I/SamsungIME( 1823): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 5607): TimaSignature is unavailable
,D/ActivityThread( 5607): Added TimaKeyStore provider
,D/HeadsetService( 5438): registerMessageListener
,D/HeadsetService( 5438): registerMessageListener
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,D/HeadsetStateMachine( 5438): Disconnected process message: 70
D/HeadsetStateMachine( 5438): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3bb41bcc
,I/Telecom ( 1418): BluetoothPhoneService: handleMessage(7) / param null
,I/Telecom ( 1418): BluetoothPhoneService: updateHeadsetWithCallState
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,I/BluetoothPbapService( 5438): Handler(): got msg=1
,I/Telecom ( 1418): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
I/Telecom ( 1418): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
I/Telecom ( 1418): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/SecContentProvider( 1014): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/HeadsetStateMachine( 5438): Disconnected process message: 9
,D/HeadsetStateMachine( 5438): mNumActive: 0 mNumHeld: 0 mCallState: 6
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,D/StatusBarManagerService( 1014): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1014): setIconVisibility slot=bluetooth visible=true
D/PhoneStatusBar( 1177): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/audio_hw_primary(  282): adev_set_parameters: enter: A2dpSuspended=false
V/voice   (  282): voice_set_parameters: enter: A2dpSuspended=false
,V/voice   (  282): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  282): platform_set_parameters: enter: A2dpSuspended=false
,V/msm8974_platform(  282): platform_set_parameters: exit with code(-2)
V/BluetoothPbapService( 5438): PBAP Service initSocket try: 0
,D/audio_hw_hfp(  282): audio_extn_hfp_set_parameters: enter
,D/BluetoothSocket( 5438): bindListen(): myUserId = 0
V/audio_hw_primary(  282): adev_set_parameters: exit
W/BluetoothAdapter( 5438): getBluetoothService() called with no BluetoothManagerCallback
,E/HeadsetStateMachine( 5438): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/BluetoothSocket( 5438): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket( 5438): bindListen(), new LocalSocket 
D/BluetoothSocket( 5438): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5438): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@188c352a
D/BluetoothSocket( 5438): channel: 19
D/BluetoothPbapService( 5438): PBAP Socket is BluetoothServerSocket
,D/BluetoothMapMasInstance( 5438): set MAP SDP message type : 1
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,W/ResourcesManager( 5607): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/BluetoothSocket( 5438): bindListen(): myUserId = 0
,W/BluetoothAdapter( 5438): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5438): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
D/BluetoothSocket( 5438): bindListen(), new LocalSocket 
D/BluetoothSocket( 5438): bindListen(), new LocalSocket.getInputStream() 
,D/BluetoothSocket( 5438): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@34619f1b
D/BluetoothSocket( 5438): channel: 5
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,D/FileShare-Client( 5607): ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Client( 5607): ClientBroadcastReceiver.onReceive - disconnected
,D/FileShare-Client( 5607): Outbound.stopDelayTimer - 
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5627): MountEmulatedStorage(),
,E/Zygote  ( 5627): v2
I/libpersona( 5627): KNOX_SDCARD checking this for 10069
I/libpersona( 5627): KNOX_SDCARD not a persona
,I/SELinux ( 5627): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5627 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 5627): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5627): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 5627): TimaSignature is unavailable
,D/ActivityThread( 5627): Added TimaKeyStore provider
,I/art     ( 1776): Explicit concurrent mark sweep GC freed 34979(2MB) AllocSpace objects, 20(320KB) LOS objects, 40% free, 12MB/20MB, paused 1.234ms total 62.792ms
,D/FileShare-Server( 5627): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager( 1014): Killing 5000:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,I/ActivityManager( 1014): Killing 3571:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/ActivityManager( 1014): startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,D/LocalBluetoothProfileManager( 1279): Adding local A2DP profile
,D/BluetoothA2dp( 1279): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1014): bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/LocalBluetoothProfileManager( 1279): Adding local HEADSET profile
,E/BluetoothHeadset( 1279): BTStateChangeCB is registed
,D/BluetoothHeadset( 1279): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1014): bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 1279): BluetoothHeadset service is binded
,D/BluetoothMap( 1279): Create BluetoothMap proxy object
,D/ActivityManager( 1014): bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1014): bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,W/ContextImpl( 1279): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/ActivityManager( 1014): bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/Bluetoothsap( 1279): bindService called to Bluetooth SAP Service
,D/ActivityManager( 1014): bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1014): bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/LocalBluetoothProfileManager( 1279): PANU : true
W/LocalBluetoothProfileManager( 1279): Warning: SAP profile was previously added.
D/LocalBluetoothProfileManager( 1279): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 1279): finishStartingService: stopping service
,W/libprocessgroup( 1014): failed to open /acct/uid_10152/pid_5000/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3571/cgroup.procs: No such file or directory
,D/BluetoothNotiBroadcastReceiver( 1279): onReceive
D/BluetoothA2dp( 1279): Proxy object connected
D/A2dpProfile( 1279): Bluetooth service connected
,V/BluetoothStatusReceiver( 1177): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothStatusReceiver( 1177): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
D/HeadsetProfile( 1279): Bluetooth service connected,
,D/BluetoothMap( 1279): Proxy object connected
D/MapProfile( 1279): Bluetooth service connected
,D/BluetoothMap( 1279): getConnectedDevices()
,D/BluetoothPbap( 1279): Proxy object connected
D/PbapServerProfile( 1279): Bluetooth service connected
D/Bluetoothsap( 1279): BluetoothSAP Proxy object connected
,D/SapProfile( 1279): Bluetooth service connected
D/Bluetoothsap( 1279): getConnectedDevices()
,D/BluetoothInputDevice( 1279): Proxy object connected
,D/HidProfile( 1279): Bluetooth service connected
,D/BluetoothAdapterService( 5438): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@181a1a10
,D/BtConfig.SecureMode( 5438): isSecureModeOn:false
,D/ActivityManager( 1014): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/BluetoothPan( 1279): BluetoothPAN Proxy object connected
,D/PanProfile( 1279): Bluetooth service connected
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/AuthorizationBluetoothService( 1776): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/SecContentProvider( 1014): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/BluetoothSocket( 5438): bindListen(): myUserId = 0
,W/BluetoothAdapter( 5438): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5438): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
D/BluetoothSocket( 5438): bindListen(), new LocalSocket 
D/BluetoothSocket( 5438): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5438): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e590acd
,D/BluetoothSocket( 5438): channel: 12
I/BtOppRfcommListener( 5438): Accept thread started.
,I/wpa_supplicant( 5497): nl80211: Received scan results (8 BSSes)
I/wpa_supplicant( 5497): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 5497): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 5497): Trying to associate with  'G700'
I/wpa_supplicant( 5497): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 5497): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
D/WifiMonitor( 1014): didn't find BSSID Trying to associate with SSID 'NG700'
I/WifiNative-HAL( 1014): startHal
E/wifi    ( 1014): getStaticLongField sWifiHalHandle 0x9ca5e8ac
I/WifiNative-HAL( 1014): Could not start hal
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
,E/wpa_supplicant( 5497): Cmd 35605 not handled
I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 5497): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 5497): wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
I/wpa_supplicant( 5497): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 5497): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 5497): Associated with C0.AA.48
I/wpa_supplicant( 5497): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 5497): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 5497): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceStatusChanged wlan0, false
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
,I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, true
D/Tethering( 1014): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1014): interfaceStatusChanged wlan0, true
,E/Tethering( 1014): No numeric data
D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
D/Tethering( 1014): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1014): clearTetheredNotification()
,I/wpa_supplicant( 5497): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 5497): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 5497): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 5497): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 5497): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 5497): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 5497): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 5497): Blacklist: Clear (temp) 
I/wpa_supplicant( 5497): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/NtpTrustedTime( 1014): forceRefresh() from cache miss,
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, true
D/Tethering( 1014): interfaceLinkStateChanged wlan0, true
D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/Tethering( 1014): interfaceStatusChanged wlan0, true
,D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1177): updateTetherState():false, false
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
,D/NtpTrustedTime( 1014): forceRefresh Fail.
V/NetworkStats( 1014): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---
,V/NetworkStats( 1014): performPollLocked() took 3ms
,D/NtpTrustedTime( 1014): forceRefresh() from cache miss
,D/NtpTrustedTime( 1014): forceRefresh Fail.
,D/WifiNative-wlan0( 1014): callSECApiVoid - ID [50]
,E/WifiConfigStore( 1014): setLastSelectedConfiguration -1
,D/ConnectivityService( 1014): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1014): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1014): updateNetworkInfo()
,D/ConnectivityService( 1014): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiConfigStore( 1014): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,E/WifiConfigStore( 1014): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Hs20UtilService( 3328): Starting #4
,D/NearbySettings( 1279): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1279): DMSUtil.isNetworkConnected - flag-null, state-null
I/Hs20UtilService( 3328): Message received 5007
,I/NearbySettings( 1279): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1279): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1279): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1279): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1279): MountReceiver.mPrefHandler - 7002
,D/CommandListener(  277): Setting iface cfg
,E/WifiStateMachine( 1014): Start Dhcp Watchdog 1
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1014): mCursor = null
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiNative-wlan0( 1014): do suspend false
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
,D/WifiP2pService( 1014): InactiveState{ what=143375 }
D/SecContentProvider2( 1014): mCursor = null
,D/WifiP2pService( 1014): P2pEnabledState{ what=143375 }
,E/dhcpcd  ( 5655): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 5655): version 5.5.6 starting,
,E/dhcpcd  ( 5655): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 5655): wlan0: sending IPv6 Router Solicitation,
E/dhcpcd  ( 5655): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 5655): if(wlan0) info get Success. (MAC : C0.AA.48),
I/dhcpcd  ( 5655): bssid match
,I/dhcpcd  ( 5655): wlan0: rebinding lease of 192.168.1.129
,I/dhcpcd  ( 5655): wlan0: acknowledged 192.168.1.129 from 192.168.1.1
,I/dhcpcd  ( 5655): wlan0: leased 192.168.1.129 for 86400 seconds
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,E/WifiNative-wlan0( 1014): do suspend true
,D/WifiP2pService( 1014): InactiveState{ what=143375 },
D/WifiP2pService( 1014): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 1014): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiStateMachine( 1014): VerifyingLinkState enter
,D/WifiNative-wlan0( 1014): callSECApiInt - ID [210]
,E/ConnectivityService( 1014): updateNetworkInfo()
,D/ConnectivityService( 1014): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1014): Adding iface wlan0 to network 502
,D/WifiWatchdogStateMachine( 1014): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1014): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 1014): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1014): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1014): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,E/WifiStateMachine( 1014): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/NearbySettings( 1279): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 3328): Starting #5,
,I/Hs20UtilService( 3328): Message received 5007
,I/NearbySettings( 1279): MountReceiver.onReceive - Keep current state
D/ConnectivityService( 1014): Adding Route [fe80::/64 -> :: wlan0] to network 502
,D/ConnectivityService( 1014): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,D/ConnectivityService( 1014): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 502
,E/ConnectivityService( 1014): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1014): Setting Dns servers for network 502 to [/192.168.1.1]
D/ConnectivityService( 1014): LTETest block dns file not exists
,D/ConnectivityService( 1014): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,E/ConnectivityService( 1014): updateNetworkInfo()
,E/ConnectivityService( 1014): updateNetworkInfo()
,D/ConnectivityService( 1014): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1014): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1014): rematching NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiTrafficPoller( 1014): evaluateTrafficStatsPolling
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,D/ConnectivityService( 1014):    accepting network in place of null
,D/ConnectivityService( 1014): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
D/WIFI_P2P( 1014): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/TelephonyNetworkFactory( 1441): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/TelephonyNetworkFactory( 1441): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
E/CSLegacyTypeTracker( 1014): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1014): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1014): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,E/WifiStateMachine( 1014): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/WifiStateMachine( 1014): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WIFI    ( 1014): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
I/System.out( 1014): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1014): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1014): (HTTPLog)-Static: isShipBuild true
I/System.out( 1014): (HTTPLog)-Thread-175-661087429: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1014): (HTTPLog)-Static: isSBSettingEnabled false
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3328): Starting #6
,D/ConnectivityService( 1014): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 1000
,D/EntConnectivity( 1014): Not allowed due to - mEnabled false - primarySimSlot false
D/ConnectivityService( 1014): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524290
,I/Hs20UtilService( 3328): Message received 5007
,I/WifiTrafficPoller( 1014): evaluateTrafficStatsPolling
,I/WifiTrafficPoller( 1014): mBoosterFLAG : 0
I/WifiTrafficPoller( 1014): current booster mode : FullMode
,D/WifiNative-wlan0( 1014): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Tethering( 1014): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,V/NetworkStats( 1014): updateIfacesLocked()
D/Tethering( 1014): MasterInitialState.processMessage what=3
V/NetworkStats( 1014): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---
D/NtpTrustedTime( 1014): forceRefresh() from cache miss
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 1000
,V/NetworkStats( 1014): performPollLocked() took 8ms
,D/NearbySettings( 1279): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1279): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1279): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1279): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1279): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1279): MountReceiver.onReceive - Keep current state
,D/StatusBar.NetworkController( 1177): EthernetConnected: false
,D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
,E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3328): Starting #7
,I/Hs20UtilService( 3328): Message received 5007
,D/NearbySettings( 1279): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1279): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1014): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1014): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 15 selection = getToastShowPackageNameState
D/SecContentProvider2( 1014): mCursor = null
,I/System.out( 1014): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 1014): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014
,D/SRIB_DCS( 1177): log_dcs ThreadedRenderer::initialize entered! 
,E/SMD     (  287): DCD OFF
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 04 Jan 2016 16:03:53 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1451923426200], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1451923426173]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Validated
,D/ConnectivityService( 1014): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1014): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1014): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService( 1014): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1014): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1177): EthernetConnected: false
,D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/AlarmManager( 1014): waitForAlarm result :4
,D/NtpTrustedTime( 1014): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1451923433132 mCachedNtpElapsedRealtime : 82807 mCachedNtpCertainty : 12
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
V/NetworkStats( 1014): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/PowerManagerService( 1014): [PWL] Off : 30s ago
,I/PowerManagerService( 1014): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1014): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1014): [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=5438, ws=null) (elapsedTime=2459)
I/PowerManagerService( 1014): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=2175)
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
I/PowerManagerService( 1014): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=2172)
,D/SSRM:n  ( 1014): SIOP:: AP = 310
,D/ConnectivityService( 1014): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/AlarmManagerService( 1014): Setting time of day to sec=1451923433
,D/AlarmManagerService( 1014): Trying to open a file
,D/AlarmManagerService( 1014): File Open Success
,D/AlarmManagerService( 1014): File Close Success
,I/AlarmManagerService( 1014): DRM_TIME_PATH CHMOD 666 for resetState done 
,V/AlarmManager( 1014): waitForAlarm result :65536
W/AlarmManagerService( 1014): Unable to set rtc to 1451923433: Invalid argument
I/DBG_DM  ( 2909): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 2909): [com.wssyncmldm.llllIIIllIlIIIIllllI(230/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
,I/DBG_DM  ( 2909): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,I/PCWCLIENTTRACE_PushUtil( 5067): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5067): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5067): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5067): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/OTPFW   ( 1014): OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1451923433427
,D/WifiStateMachine( 1014): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_SET
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
I/DowntimeConditions( 1014): android.intent.action.TIME_SET ignored because schedule turned off.
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SettingsProvider( 1014): name = lockscreen_zoom_panning_effect
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10054
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,I/DBG_DM  ( 2909): [IlIlllIlllllIlIllllI(403/llIIllllIIlllIIIIlll)] Check completed.
,W/Settings( 1014): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DBG_DM  ( 2909): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/splitIntent( 1014): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=10, mSplitNum[1]=17, mSplitNum[2]=26, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=34
,I/splitIntent( 1014): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,D/KeyguardEffectViewUtil( 1177): isStrongPowerSavingMode() :false
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/KeyguardEffectViewController( 1177): isPreloadedWallpaper=true,
I/GeometricMosaic_Keyguard( 1177): update
D/KeyguardEffectViewUtil( 1177): getCurrentWallpaper() mWallpaperPath :null,
,E/Zygote  ( 5697): MountEmulatedStorage()
,I/libpersona( 5697): KNOX_SDCARD checking this for 10111
E/Zygote  ( 5697): v2
I/libpersona( 5697): KNOX_SDCARD not a persona
,I/SELinux ( 5697): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5697 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5697): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,E/SELinux ( 5697): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/accuweather( 1719): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,V/AlarmManager( 1014): waitForAlarm result :12
,V/AlarmManager( 1014): No more alarm at this time.nowELAPSED=83177 batch.start=89684
,I/KLMS-2.5.183: ( 3358): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 04 17:03:53 GMT+01:00 2016
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/DBG_DM  ( 2909): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,D/TimaKeyStoreProvider( 5697): TimaSignature is unavailable
,W/SEC_DRM_PLUGIN_Playready(  281): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1451923426 after conversion: 1451923426
W/SEC_DRM_PLUGIN_Playready(  281): PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1451923433 after conversion: 1451923433
,D/ActivityThread( 5697): Added TimaKeyStore provider
,D/SecurityLogAgent( 5586): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 5586): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5586): StateMachine : Current State = 1
,D/SecurityLogAgent( 5586): StateMachine : Changed Current State = 1
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/KeyguardEffectViewUtil( 1177): set current wallpaper info
,I/KLMS-2.5.183: ( 3358): KLMSAbstractReciever(): onReceive().END.
,I/DBG_DM  ( 2909): [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
E/Zygote  ( 5712): MountEmulatedStorage()
E/Zygote  ( 5712): v2
I/libpersona( 5712): KNOX_SDCARD checking this for 10159
I/libpersona( 5712): KNOX_SDCARD not a persona
I/SELinux ( 5712): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/daemonapp( 1310): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 16,
D/SettingsProvider( 1014): name = keyguard_current_wallpaper_type
I/ActivityManager( 1014): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=5712 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10054
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,I/SELinux ( 5712): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5712): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/SettingsProvider( 1014): name = keyguard_current_wallpaper_file_path
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10054
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,D/SettingsProvider( 1014): name = keyguard_current_wallpaper_res_id
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10054
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/accuweather( 1719): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1719): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1719): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1,
,I/KLMS-2.5.183: ( 3358): KLMSIntentService(): onCreate(),
D/accuweather( 1719): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/TimaKeyStoreProvider( 5712): TimaSignature is unavailable,
D/ActivityThread( 5712): Added TimaKeyStore provider
,I/ActivityManager( 1014): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=5728 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a,
,E/Zygote  ( 5728): MountEmulatedStorage()
E/Zygote  ( 5728): v2
I/libpersona( 5728): KNOX_SDCARD checking this for 10034,
I/libpersona( 5728): KNOX_SDCARD not a persona
,I/SELinux ( 5728): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5728): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5728): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.phenotype.service.sync.PhenotypeConfigurator; callingUser = 0; userId(target) = 0
,I/KLMS-2.5.183: ( 3358): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 2909): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/TEST    ( 1177): run!!!
D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
D/TimaKeyStoreProvider( 5728): TimaSignature is unavailable
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
D/ActivityThread( 5728): Added TimaKeyStore provider
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
D/accuweather( 1719): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
D/accuweather( 1719): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.youtube
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.youtube
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/KLMS-2.5.183: ( 3358): KLMSUtility(): isTestMode(): product_ship: true | testApk: false,
,E/Zygote  ( 5748): MountEmulatedStorage()
,E/Zygote  ( 5748): v2
I/libpersona( 5748): KNOX_SDCARD checking this for 10166
I/libpersona( 5748): KNOX_SDCARD not a persona
,I/SELinux ( 5748): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/DBG_DM  ( 2909): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/SELinux ( 5748): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService: pid=5748 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 5748): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
I/GeometricMosaic_Renderer( 1177): setBackgroundBitmap
I/DBG_DM  ( 2909): [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
I/DBG_DM  ( 2909): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,I/KLMS-2.5.183: ( 3358): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/KLMS-2.5.183: ( 3358): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,E/Zygote  ( 5762): MountEmulatedStorage()
E/Zygote  ( 5762): v2
,I/ActivityManager( 1014): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5762 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_DM  ( 2909): [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE,
,I/libpersona( 5762): KNOX_SDCARD checking this for 10081
I/libpersona( 5762): KNOX_SDCARD not a persona
,I/SELinux ( 5762): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5762): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/DBG_DM  ( 2909): [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
E/SELinux ( 5762): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 2909): [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,D/TimaKeyStoreProvider( 5748): TimaSignature is unavailable
I/DBG_DM  ( 2909): [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,I/KLMS-2.5.183: ( 3358): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,D/ActivityThread( 5748): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3358): StateImplV2(): networkChangeListener().START
,I/DBG_DM  ( 2909): [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 2909): [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/GoogleURLConnFactory( 1776): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/art     ( 4826): Suspending all threads took: 37.019ms
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/KLMS-2.5.183: ( 3358): NetworkChangeOperations(): uploadRequestLog().START 
,D/TimaKeyStoreProvider( 5762): TimaSignature is unavailable
,D/ActivityThread( 5762): Added TimaKeyStore provider
,I/DBG_DM  ( 2909): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncService; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 2909): [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:308289685
,I/DBG_DM  ( 2909): [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,I/KLMS-2.5.183: ( 3358): NetworkChangeOperations(): uploadRequestLog().END ,
,I/KLMS-2.5.183: ( 3358): StateImplV2(): networkChangeListener().END
,W/ResourcesManager( 5748): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5748): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/DBG_DM  ( 2909): [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,I/DBG_DM  ( 2909): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,I/KLMS-2.5.183: ( 3358): KLMSIntentService(): onDestroy()
,I/DBG_DM  ( 2909): [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,I/DBG_DM  ( 2909): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 678432842
,I/DBG_DM  ( 2909): [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,I/DBG_DM  ( 2909): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity,
,I/DBG_DM  ( 2909): [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] ,
,D/WaitQueueForNetworkActivate( 5116): notifyNetworkActivated
,I/DBG_DM  ( 2909): [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,I/DBG_DM  ( 2909): [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
,E/DBG_DM  ( 2909): [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,I/DBG_DM  ( 2909): [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,E/DBG_DM  ( 2909): [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@69ad693
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 2909): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,V/JNIHelp ( 5748): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.metadata.ContactMetadataSyncService; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 2909): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,I/DBG_DM  ( 2909): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(649/IIIIllIlIIlIIIIlllIl)] nWidgetStatus : 2
,W/ContextImpl( 2909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.wssyncmldm.ui.llllIIIllIlIIIIllllI.IIIIllIlIIlIIIIlllIl:652 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:172 llllIIIllIllIlllIIlI.llIIIIlllllIIllIIllI:732 
,I/MusicStore( 5697): Database version: 108,
,D/SettingsProvider( 1014): name = SOFTWARE_UPDATE_NOTIFICATION_STATUS
,W/ContextImpl( 5116): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/ActivityThread( 5748): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5748): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@582fe8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5748): Installed default security provider GmsCore_OpenSSL
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/DBG_DM  ( 2909): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/DBG_DM  ( 2909): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/DBG_POLICYDM( 5101): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5101): [com.policydm.XDMApplication(469/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5101): [com.policydm.XDMApplication(471/isNetworkChanged)] network changed.... 
,E/SPPClientService( 5139): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,E/DBG_POLICYDM( 5101): [com.policydm.XDMBroadcastReceiver(240/xdmNotInitSetResume)] DM Not Init
,I/DBG_POLICYDM( 5101): [com.policydm.XDMApplication(286/xdmInitializing)] ----------- XEVENT_DM_INIT WIFI ok
,I/SA      ( 5285): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ],
I/SA      ( 5285): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 5285): [OR] == ACTION_CONNECTIVITY_CHANGE ==,
,I/SA      ( 5285): [SLFUCHKMGR] constructor called
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 59931(3MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 4.670ms total 252.298ms
,I/DBG_POLICYDM( 5101): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.sec.android.gallery3d, action: android.content.SyncAdapter
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0
,D/ApplicationPolicy( 1014): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager( 1014): showStatusBarByNotification() mOpenByNotification=false
,I/DBG_POLICYDM( 5101): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_DM  ( 2909): [com.wssyncmldm.ui.XUIFotaPostponeActivity(337/llIIIIlllllIIllIIllI)] 
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 5101): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
I/DBG_DM  ( 2909): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_POLICYDM( 5101): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,E/Zygote  ( 5810): MountEmulatedStorage()
E/Zygote  ( 5810): v2
I/libpersona( 5810): KNOX_SDCARD checking this for 10044
I/libpersona( 5810): KNOX_SDCARD not a persona
,I/SELinux ( 5810): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5810): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5810): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 5101): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,I/SA      ( 5285): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 5285): [OR] == isSIMCardReady false ==
I/ActivityManager( 1014): Start proc com.sec.android.gallery3d for service com.sec.android.gallery3d/.remote.picasa.PicasaService: pid=5810 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,W/NotificationService( 1014): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/ResourcesManager( 1177): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/SecContentProvider2( 1014): uri = 15 selection = getToastGravityEnabledState,
D/SecContentProvider2( 1014): mCursor = null
D/TimaKeyStoreProvider( 5810): TimaSignature is unavailable
,D/ActivityThread( 5810): Added TimaKeyStore provider
,I/SA      ( 5285): [SCU] == networkStateCheck == true,
I/SA      ( 5285): [DM] getCountryCodeFromCSC : PL,
I/SA      ( 5285): isChinaCountryCode : false
I/SA      ( 5285): [SCU] is ChinestModel Data Restricted   : false,
I/SA      ( 5285): [OR] == networkStateCheck true ==
,I/DBG_DM  ( 2909): [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 2909): [com.wssyncmldm.ui.XUIFotaPostponeActivity(386/llIIIIlllllIIllIIllI)] No idle Postpone
,I/DBG_DM  ( 2909): [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,I/SA      ( 5285): [OR] GetMyCountryZoneTask
,I/SA      ( 5285): [OR] onReceive END
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5829): MountEmulatedStorage(),
I/ActivityManager( 1014): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5829 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,E/Zygote  ( 5829): v2
I/libpersona( 5829): KNOX_SDCARD checking this for 10104,
I/libpersona( 5829): KNOX_SDCARD not a persona
,D/PackageManager( 1014): [MSG] MCS_UNBIND,
,I/SELinux ( 5829): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 5829): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5829): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,V/DownloadManager( 1224): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 5285): [SRS] prepareGetMyCountryZone
,D/SecContentProvider2( 1014): uri = 15 selection = getToastGravity
D/SecContentProvider2( 1014): mCursor = null
,D/KnoxNotification( 1177): ----- inflateViews : modified publicViewLocal -----
,I/dex2oat ( 5828): ----------------------------------------------------
I/dex2oat ( 5828): <SS>: S T A R T I N G . . .
I/dex2oat ( 5828): <SS>: Zip is absent. Canceled.
I/dex2oat ( 5828): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-78145250.jar --oat-fd=33 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads-78145250.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/SecContentProvider2( 1014): uri = 15 selection = getToastGravityXOffset
D/SecContentProvider2( 1014): mCursor = null
,W/System.err( 5748): YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/KnoxNotification( 1177): ----- inflateViews : modified KnoxViewLocal -----
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,D/PersonaManager( 1177): PersonaID is invalid or persona doesn't exists. : 0
,D/TimaKeyStoreProvider( 5829): TimaSignature is unavailable
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,I/PhoneStatusBar( 1177): Icon Only
,I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/ActivityThread( 5829): Added TimaKeyStore provider
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ResourcesManager( 5810): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5810): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5810): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5810): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5810): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 5810): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5810): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5810): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/SecContentProvider2( 1014): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1014): mCursor = null
,D/GpsLocationProvider( 1014): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,I/System.out( 5748): YouTube MDX: MDX video stage moved to NEW
,I/System.out( 5748): YouTube MDX: MDX video player state moved to UNSTARTED
,I/System.out( 5748): YouTube MDX: MDX ad player state moved to UNSTARTED
,D/SecContentProvider2( 1014): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1014): mCursor = null
I/SA      ( 5285): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,I/SA      ( 5285): [SSP] query invoked
,W/ResourcesManager( 5697): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5697): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 5101): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,W/ResourcesManager( 5829): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/SecContentProvider2( 1014): uri = 15 selection = getToastEnabledState
D/SecContentProvider2( 1014): mCursor = null
,I/DBG_POLICYDM( 5101): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,I/DBG_POLICYDM( 5101): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 5101): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] ,
,I/SA      ( 5285): [TPMU] GetMccFromDB : null
,D/SecContentProvider2( 1014): uri = 15 selection = getToastShowPackageNameState,
D/SecContentProvider2( 1014): mCursor = null
I/SA      ( 5285): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5285): [TPM] isNoProxy(default) : true
,I/DBG_POLICYDM( 5101): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,I/DBG_POLICYDM( 5101): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 5101): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2015/12/30/15:02:29
,I/dex2oat ( 5828): dex2oat took 236.523ms (threads: 4)
,E/ActivityThread( 1970): Failed to find provider info for com.android.contacts.metadata
,D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 5101): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/01/04/17:03:54
,I/DBG_POLICYDM( 5101): [com.policydm.polling.XPollingAgent(323/xpollingDefaultPollingTime)] 
,I/DBG_POLICYDM( 5101): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5101): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,I/DBG_POLICYDM( 5101): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 5101): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 5101): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 5101): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 5101): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 5101): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 5101): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,E/File    ( 5285): fail readDirectory() errno=2
,I/DBG_POLICYDM( 5101): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5101): [com.policydm.polling.XPollingAgent(347/xpollingDefaultPollingTime)] Next Polling Time:2016/01/05/18:46:18
,D/hcjo    ( 5116): AutoUpdateManager:IDLE:execute
,D/NearbySource( 5810): Nearby Source Create!
,D/NearbyContext( 5810): Nearby Context Create!
,E/GpsLocationProvider( 1014): No APN found to select.
,I/DBG_POLICYDM( 5101): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,V/JNIHelp ( 5697): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/InitializeManagerStateMachine( 5116): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5116): exit::IDLE
,D/InitializeManagerStateMachine( 5116): entry::NETWORK_CHECK
,I/CheckinService( 1970): Checkin interval check for package: unspecified last checkin: 1451089911968 min interval config: 0 actual interval: 833523082
,D/InitializeManagerStateMachine( 5116): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 5116): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5116): entry::CHECK_COUNTRY_INFO
,I/DBG_POLICYDM( 5101): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,D/InitializeManagerStateMachine( 5116): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
D/InitializeManagerStateMachine( 5116): exit::CHECK_COUNTRY_INFO
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
D/InitializeManagerStateMachine( 5116): entry::SUCCESS
D/hcjo    ( 5116): AutoUpdateManager:INITCHECK:onInitializeSuccess
I/DBG_POLICYDM( 5101): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5101): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5101): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,D/hcjo    ( 5116): AutoUpdateTriggerManager:REQUEST2:requestInterval
,W/ContextImpl( 5810): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 5810): Samsung link source created
,I/DBG_POLICYDM( 5101): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5101): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5101): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
I/DBG_POLICYDM( 5101): [com.policydm.restclient.XRCProcess(921/xspdHandler)] XEVENT_RC_GET_VERSION
,I/DBG_POLICYDM( 5101): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/SyncManager( 1014): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 23371, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager( 1014): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 116696, reason: UserStart
,I/DBG_POLICYDM( 5101): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,I/Volley  ( 5116): RestApi Request Add : 2307
,E/File    ( 5116): fail readDirectory() errno=2
,W/ActivityThread( 5697): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5697): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16a81864: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5697): Installed default security provider GmsCore_OpenSSL
,I/DBG_POLICYDM( 5101): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,D/AndroidMusic( 5697): GMSCore installation verified
,W/art     ( 5101): Suspending all threads took: 5.263ms
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5748): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/CheckinService( 1970): Checking schedule, now: 1451923435250 next: 1451629174536
I/CheckinService( 1970): active receiver: enabled
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ContactProvider( 5810): getAllContactInfoList Start
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/CheckinService( 1970): Preparing to send checkin request
I/EventLogService( 1970): Accumulating logs since 1451922840266
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/iu.SyncManager( 1970): SYNC; picasa accounts
,I/DBG_POLICYDM( 5101): [com.policydm.db.XDBSpdAdp(158/xdbSetSpdState)] nRestClientMode = 6
,D/ConnectivityService( 1014): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1014): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,E/DBG_POLICYDM( 5101): [com.policydm.restclient.XRCProcess(212/RestClientProcess)] SPD SERVICE Start!!
,W/ContextImpl( 5101): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.policydm.restclient.XRCProcess.RestClientProcess:213 com.policydm.restclient.XRCProcess.access$100:77 com.policydm.restclient.XRCProcess$RestClientThread.run:134 
,D/ConnectivityService( 1014): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524295
,D/ActivityManager( 1014): startService callerProcessName:com.policydm, calleePkgName: com.policydm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.policydm/com.policydm.XDMService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.policydm, destAppInfo.processName = com.policydm
,D/SecContentProvider2( 1014): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1014): mCursor = null
,I/DBG_POLICYDM( 5101): [com.policydm.restclient.XRCProcess(622/execute)] 
I/DBG_POLICYDM( 5101): [com.policydm.XDMService(60/onCreate)] 
,I/ConfigStore( 5697): Config Database version: 1
,D/NetworkLogImpl( 1970): Loaded NetworkSpeedPredictor
,W/ActivityThread( 5101): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/iu.Environment( 1970): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/DBG_POLICYDM( 5101): [com.policydm.XDMService(82/onStartCommand)] 
,I/System.out( 5101): Thread-868(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5101): Thread-868(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5101): Thread-868(ApacheHTTPLog):isShipBuild true
I/System.out( 5101): Thread-868(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5101): Thread-868(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 1000
,D/ContactProvider( 5810): getAllContactInfoList End
,I/syncContacts( 5810): thread: 988, sync time = 231
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.gmsproc.GcmIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,E/Auth.Api.Credentials( 1970): [CredentialSyncAdapter] Unknown sync event.
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/iu.UploadsManager( 1970): num queued entries: 0
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,I/iu.UploadsManager( 1970): num updated entries: 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/EnterpriseController(  277): uids 10012
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncService; callingUser = 0; userId(target) = 0
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/DBG_POLICYDM( 5101): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/art     ( 1633): Explicit concurrent mark sweep GC freed 1903(70KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 742us total 44.773ms
,I/iu.SyncManager( 1970): NEXT; no task
,I/System.out( 5101): Thread-868 calls detatch()
,I/DBG_POLICYDM( 5101): [com.policydm.restclient.XRCProcess(328/RestClientProcess)] HTTP status is 200
,I/DBG_POLICYDM( 5101): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,I/Babel   ( 5829): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5829): MmsConfig.loadMmsSettings
I/Babel   ( 5829): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/Babel   ( 5829): MmsConfig.loadFromDatabase
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/Babel   ( 5829): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 5829): MmsConfig.loadFromResources
,E/Babel   ( 5829): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5829): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/DBG_POLICYDM( 5101): [com.policydm.polling.XPollingAgent(204/xpollingNextPollingTime)] Next Polling Time:2016/01/11/11:32:45
,I/DBG_POLICYDM( 5101): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,I/AudioService( 1014): getStreamVolume 3 index 0
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,I/GCM     ( 1776): GCM config loaded
W/ContextImpl( 5697): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 5829): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5697): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/DBG_POLICYDM( 5101): [com.policydm.polling.XPollingAgent(165/xpollingSaveXMLData)] Next StatusReport Time:2016/01/07/20:18:23
,E/DBG_POLICYDM( 5101): [com.policydm.restclient.XRCProcess(388/RestClientProcess)] bPolicyUpdate is false
,I/DBG_POLICYDM( 5101): [com.policydm.restclient.XRCProcess(948/callRestClientFinish)] 
,E/DBG_POLICYDM( 5101): [com.policydm.XDMBroadcastReceiver(540/xdmSetCheckedIntent)] b_AlreadyReceivedIntent : false
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,I/DBG_POLICYDM( 5101): [com.policydm.db.XDBSpdAdp(158/xdbSetSpdState)] nRestClientMode = 0
,I/DBG_POLICYDM( 5101): [com.policydm.ui.XUIAdapter(33/xuiAdpGetUiMode)] nDmUiMode : 0
,E/DBG_POLICYDM( 5101): [com.policydm.restclient.XRCProcess(983/callRestClientFinish)] SPD SERVICE Stop!!
,W/ContextImpl( 5101): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.policydm.restclient.XRCProcess.callRestClientFinish:984 com.policydm.restclient.XRCProcess.RestClientProcess:504 com.policydm.restclient.XRCProcess.access$100:77 
,W/ContextImpl( 5697): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5748): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.policydm/com.policydm.XDMService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.policydm, destAppInfo.processName = com.policydm
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/DBG_POLICYDM( 5101): [com.policydm.XDMService(43/onDestroy)] 
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5748): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5748): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/Babel_StickerModule( 5829): App launched.
,I/Babel_StickerModule( 5829): Sticker update initiated. last:1451273703524 empty:false
,I/AudioService( 1014): getStreamVolume 3 index 0
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
I/MediaRouter( 5697): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
I/System.out( 1776): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1776): (HTTPLog)-Static: isShipBuild true
I/System.out( 1776): (HTTPLog)-Thread-150-479068589: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012,
,D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/SMD     (  287): DCD OFF
,I/ActivityManager( 1014): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5937 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 5937): MountEmulatedStorage()
E/Zygote  ( 5937): v2
I/libpersona( 5937): KNOX_SDCARD checking this for 10113
I/libpersona( 5937): KNOX_SDCARD not a persona
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1776): (HTTPLog)-Static: isShipBuild true
I/System.out( 1776): (HTTPLog)-Thread-251-633838818: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,I/art     (  314): Explicit concurrent mark sweep GC freed 8697(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 660us total 27.066ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 599us total 16.659ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 630us total 17.637ms
,I/SELinux ( 5937): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5937): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5937): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
I/System.out( 1776): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
I/qtaguid ( 1776): Tagging socket 78 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1776, getuid(): 10012
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,V/MusicLeanback( 5697): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/TimaKeyStoreProvider( 5937): TimaSignature is unavailable
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  282): getCameraInfo: X
,I/qtaguid ( 1776): Tagging socket 82 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1776, getuid(): 10012
,D/ActivityThread( 5937): Added TimaKeyStore provider
,I/System.out( 1776): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1776): Tagging socket 76 with tag 1000120300000000{268440067,0} for uid -1, pid: 1776, getuid(): 10012
,I/NetworkMonitor( 5697): type=WIFI subType= reason=null isConnected=true
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  282): getCameraInfo: X
I/dhcpcd  ( 5655): wlan0: sending IPv6 Router Solicitation
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/ActivityManager( 1014): Killing 4714:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,D/AndroidHttpClient( 5748): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A500FU Build/LRX22G)
D/AndroidHttpClient( 5748): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,I/System.out( 5748): Thread-1035(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5748): Thread-1035(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5748): Thread-1035(ApacheHTTPLog):isShipBuild true
I/System.out( 5748): Thread-1035(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5748): Thread-1035(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController(  277): uids 10166
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10166
,W/VideoCapabilities( 5829): Unrecognized profile 2130706433 for video/avc
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 34366(1723KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 2.773ms total 174.386ms
,W/AudioCapabilities( 5829): Unsupported mime audio/evrc
,W/AudioCapabilities( 5829): Unsupported mime audio/qcelp
,W/libprocessgroup( 1014): failed to open /acct/uid_10015/pid_4714/cgroup.procs: No such file or directory
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,V/HeadsetService( 5438): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5438): Disconnected process message: 10
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/AudioCapabilities( 5829): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 5829): Unsupported mime audio/mpeg-L2
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/AudioCapabilities( 5829): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5829): Unsupported mime audio/x-ima
,W/AudioCapabilities( 5829): Unsupported mime audio/qcelp
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/SurfaceFlinger(  257): id=13 Removed Uoast (8/9)
,D/PowerManagerService( 1014): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1014) eventTime = 86227
,D/PowerManagerService( 1014): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014 (0x0)
,D/PowerManagerService( 1014): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1014, ws=WorkSource{10054}) (elapsedTime=3541)
,W/AudioCapabilities( 5829): Unsupported mime audio/evrc
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/art     ( 5829): Suspending all threads took: 6.382ms
,I/qtaguid ( 1776): Tagging socket 85 with tag 1000120300000000{268440067,0} for uid -1, pid: 1776, getuid(): 10012
,D/OpenGLRenderer( 2909): Render dirty regions requested: true
,I/NetworkMonitor( 5697): type=WIFI subType= reason=null isConnected=true
,I/System.out( 5748): Thread-1019(ApacheHTTPLog):isSBSettingEnabled false
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,I/System.out( 5748): Thread-1019(ApacheHTTPLog):isShipBuild true
I/System.out( 5748): Thread-1019(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 5748): Thread-1019(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/SurfaceFlinger(  257): id=14 createSurf (1x1),1 flag=4, Uoast
,D/EnterpriseController(  277): uids 10166
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10166
,I/System.out( 5748): Thread-1035 calls detatch()
,I/System.out( 5748): Thread-1021(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5748): Thread-1021(ApacheHTTPLog):isShipBuild true
I/System.out( 5748): Thread-1021(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5748): Thread-1021(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10166
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10166
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/PowerManagerService( 1014): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014
,D/SRIB_DCS( 2909): log_dcs ThreadedRenderer::initialize entered! 
,I/System.out( 5748): Thread-1018(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5748): Thread-1018(ApacheHTTPLog):isShipBuild true
,I/Adreno-EGL( 2909): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2909): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2909): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2909): Local Branch: 
I/Adreno-EGL( 2909): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2909): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2909):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
I/System.out( 5748): Thread-1018(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 5748): Thread-1018(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/OpenGLRenderer( 2909): Initialized EGL, version 1.4
,I/qtaguid ( 5748): Tagging socket 53 with tag ff44265f00000000{4282656351,0} for uid -1, pid: 5748, getuid(): 10166
,E/Zygote  ( 5972): MountEmulatedStorage(),
I/ActivityManager( 1014): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=5972 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 5972): v2
I/libpersona( 5972): KNOX_SDCARD checking this for 10002,
I/qtaguid ( 5748): Tagging socket 49 with tag ff44265f00000000{4282656351,0} for uid -1, pid: 5748, getuid(): 10166
I/libpersona( 5972): KNOX_SDCARD not a persona
,I/SELinux ( 5972): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5972): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5972): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/qtaguid ( 5748): Tagging socket 58 with tag ff44265f00000000{4282656351,0} for uid -1, pid: 5748, getuid(): 10166
,D/OpenGLRenderer( 2909): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096,
D/OpenGLRenderer( 2909): Enabling debug mode 0
,I/CheckinRequestBuilder( 1970): Checkin reason type: 12 attempt count: 1
,I/System.out( 5748): Thread-1020(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5748): Thread-1020(ApacheHTTPLog):isShipBuild true
I/System.out( 5748): Thread-1020(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5748): Thread-1020(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5748): Tagging socket 56 with tag ff44265f00000000{4282656351,0} for uid -1, pid: 5748, getuid(): 10166
D/btif_config_util( 5438): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/VideoCapabilities( 5829): Unsupported mime video/wvc1
,E/ActivityThread( 1970): Failed to find provider info for com.google.android.wearable.settings,
,D/TimaKeyStoreProvider( 5972): TimaSignature is unavailable
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,D/ActivityThread( 5972): Added TimaKeyStore provider
,W/ContextImpl( 5937): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,W/VideoCapabilities( 5829): Unsupported mime video/x-ms-wmv
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
W/VideoCapabilities( 5829): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ConnectivityManager( 1970): CallingUid : 10012, CallingPid : 1970
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/VideoCapabilities( 5829): Unsupported mime video/wvc1
,W/VideoCapabilities( 5829): Unsupported mime video/x-ms-wmv
,W/ContextImpl( 5937): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/ResourcesManager( 5697): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5697): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 5697): Using the GMSCore's GoogleHttpClient
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,D/ConnectivityService( 1014): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService( 1014): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,D/ConnectivityService( 1014): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1014): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 1970): CM callback handler got msg 524290
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,D/InitializeManagerStateMachine( 5116): exit::SUCCESS
D/InitializeManagerStateMachine( 5116): entry::IDLE
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.sync.FitnessSyncAdapterService; callingUser = 0; userId(target) = 0
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5937): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/System.out( 5116): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5116): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5116): (HTTPLog)-Static: isShipBuild true
,I/System.out( 5116): (HTTPLog)-Thread-872-558593195: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5116): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10010
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10010
,W/VideoCapabilities( 5829): Unsupported mime video/x-ms-wmv7
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5937): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.sec.android.gallery3d, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0
,W/VideoCapabilities( 5829): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 5829): Unsupported mime video/mp43
,W/VideoCapabilities( 5829): Unsupported mime video/sorenson
,W/art     ( 5285): Suspending all threads took: 6.920ms
,W/VideoCapabilities( 5829): Unsupported mime video/mp4v-esdp
,I/System.out( 5116): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 5116): Tagging socket 26 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 5116, getuid(): 10010
,W/art     ( 5748): Suspending all threads took: 16.586ms
,I/ActivityManager( 1014): Killing 5037:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,I/qtaguid ( 5748): Untagging socket 58
,I/System.out( 5748): Thread-1018 calls detatch()
,I/qtaguid ( 5748): Untagging socket 56
,I/System.out( 5748): Thread-1020 calls detatch()
,I/System.out( 5748): Thread-1020(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5748): Thread-1020(ApacheHTTPLog):isShipBuild true
I/System.out( 5748): Thread-1020(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5748): Thread-1020(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5748): Tagging socket 56 with tag ff44265f00000000{4282656351,0} for uid -1, pid: 5748, getuid(): 10166
,I/System.out( 5748): Thread-1018(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5748): Thread-1018(ApacheHTTPLog):isShipBuild true
I/System.out( 5748): Thread-1018(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5748): Thread-1018(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5748): Tagging socket 58 with tag ff44265f00000000{4282656351,0} for uid -1, pid: 5748, getuid(): 10166
I/qtaguid ( 5748): Tagging socket 66 with tag ff44265f00000000{4282656351,0} for uid -1, pid: 5748, getuid(): 10166
,D/PicasaService( 5810): start picasa sync
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,D/PicasaService( 5810): end picasa sync
,I/qtaguid ( 5748): Tagging socket 68 with tag ff44265f00000000{4282656351,0} for uid -1, pid: 5748, getuid(): 10166
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/qtaguid ( 5748): Untagging socket 58,
I/System.out( 5748): Thread-1018 calls detatch()
,E/Zygote  ( 6027): MountEmulatedStorage(),
I/qtaguid ( 5748): Untagging socket 56
I/System.out( 5748): Thread-1020 calls detatch(),
E/Zygote  ( 6027): v2
I/libpersona( 6027): KNOX_SDCARD checking this for 1000
,I/libpersona( 6027): KNOX_SDCARD not a persona,
,I/System.out( 5748): Thread-1018(ApacheHTTPLog):isSBSettingEnabled false,
I/System.out( 5748): Thread-1018(ApacheHTTPLog):isShipBuild true
I/System.out( 5748): Thread-1018(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5748): Thread-1018(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false,
I/qtaguid ( 5748): Tagging socket 56 with tag ff44265f00000000{4282656351,0} for uid -1, pid: 5748, getuid(): 10166
,I/ActivityManager( 1014): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6027 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 6027): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6027): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6027): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/qtaguid ( 5116): Untagging socket 26
,I/VideoCapabilities( 5829): Unsupported profile 4 for video/mp4v-es
,D/hcjo    ( 5116): AutoUpdateTriggerManager:REQUEST2:setInterval:345600000
,D/TimaKeyStoreProvider( 6027): TimaSignature is unavailable
,D/ActivityThread( 6027): Added TimaKeyStore provider
,W/PhenotypeConfigurator( 1776): Server returned 404
,D/ActivityManager( 1014): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,D/hcjo    ( 5116): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,D/hcjo    ( 5116): AutoUpdateManager:UPD_CHECK_TIMING:onUpdateTime
D/hcjo    ( 5116): SelfUpdateManager:IDLE:execute
,I/qtaguid ( 5748): Untagging socket 56
,I/System.out( 5748): Thread-1018 calls detatch()
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/hcjo    ( 5116): SelfUpdateManager:CONDITION_CHECK:onUpdateCondition
,I/System.out( 5748): Thread-1025(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5748): Thread-1025(ApacheHTTPLog):isShipBuild true
I/System.out( 5748): Thread-1025(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5748): Thread-1025(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10166
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10166
,I/ActivityManager( 1014): Killing 5052:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,I/qtaguid ( 5748): Tagging socket 42 with tag 0{0,0} for uid -1, pid: 5748, getuid(): 10166
,I/qtaguid ( 5748): Untagging socket 49,
I/System.out( 5748): Thread-1021 calls detatch()
,I/qtaguid ( 5748): Untagging socket 53
I/System.out( 5748): Thread-1019 calls detatch()
,I/DIAGMON_AGENT( 6027): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,I/Volley  ( 5116): RestApi Request Add : 2346
,I/WebViewFactory( 5937): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,I/System.out( 5116): (HTTPLog)-Static: isSBSettingEnabled false
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gm, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.provider.MailSyncAdapterService; callingUser = 0; userId(target) = 0
,I/LibraryLoader( 5937): Time to load native libraries: 2 ms (timestamps 7197-7199)
,I/LibraryLoader( 5937): Expected native library version number "",actual native library version number ""
,I/System.out( 5116): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 5116): Tagging socket 28 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 5116, getuid(): 10010
,V/WebViewChromiumFactoryProvider( 5937): Binding Chromium to main looper Looper (main, tid 1) {b43cda}
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/LibraryLoader( 5937): Expected native library version number "",actual native library version number ""
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/chromium( 5937): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5937): Initializing chromium process, singleProcess=true,
,W/art     ( 5937): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5937): ApplicationContext is null in ApplicationStatus,
,E/Zygote  ( 6047): MountEmulatedStorage(),
I/ActivityManager( 1014): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=6047 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6047): v2
I/libpersona( 6047): KNOX_SDCARD checking this for 10101,
I/libpersona( 6047): KNOX_SDCARD not a persona
,I/SELinux ( 6047): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6047): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6047): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5037/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1014): failed to open /acct/uid_10156/pid_5052/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 5829): Creating RTCS
,D/TimaKeyStoreProvider( 6047): TimaSignature is unavailable
,D/ActivityThread( 6047): Added TimaKeyStore provider
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.games.chimera.GamesSyncServiceMainProxy; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1970): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1970): Module APK com.google.android.play.games already loaded
,W/chromium( 5937): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 5937): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
I/chromium( 5937): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,I/GamesSyncServiceMain( 1970): Found unexpected GCM tag when scheduling; aborting
,W/GamesSyncServiceMain( 1970): Failed to execute periodic sync, missing client context - aborting
,I/Adreno-EGL( 5937): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5937): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5937): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5937): Local Branch: 
I/Adreno-EGL( 5937): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5937): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5937):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/DIAGMON_AGENT( 6027): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6027): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6027): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6027): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6027): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 6027): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,W/DefaultRequestDirector( 5748): Authentication error: Unable to respond to any of these challenges: {bearer=WWW-Authenticate: Bearer realm="https://accounts.google.com/"}
,I/qtaguid ( 5748): Untagging socket 42
,I/System.out( 5748): Thread-1025 calls detatch()
,E/Volley  ( 5748): [1025] abz.a: Unexpected response code 401 for https://www.googleapis.com/youtubei/v1/account/get_setting_categories?key=AIzaSyA8eiZmM1FaDVjRy-df2KTyQ_vz_yYM39w
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/AudioManagerAndroid( 5937): Requires BLUETOOTH permission
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/NSApplication( 5937): Starting up...
,I/System.out( 5748): Thread-1025(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5748): Thread-1025(ApacheHTTPLog):isShipBuild true
I/System.out( 5748): Thread-1025(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5748): Thread-1025(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5748): Tagging socket 42 with tag 0{0,0} for uid -1, pid: 5748, getuid(): 10166
I/qtaguid ( 5748): Tagging socket 55 with tag 0{0,0} for uid -1, pid: 5748, getuid(): 10166
,W/ResourcesManager( 5829): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5829): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/DefaultRequestDirector( 5748): Authentication error: Unable to respond to any of these challenges: {bearer=WWW-Authenticate: Bearer realm="https://accounts.google.com/"}
,I/qtaguid ( 5748): Untagging socket 42
,I/System.out( 5748): Thread-1025 calls detatch()
E/Volley  ( 5748): [1025] abz.a: Unexpected response code 401 for https://www.googleapis.com/youtubei/v1/account/get_setting_categories?key=AIzaSyA8eiZmM1FaDVjRy-df2KTyQ_vz_yYM39w
,E/YouTube ( 5748): apps.youtube.app.task.YouTubeNetworkTaskService.a:124 Failed to fetch settings
E/YouTube ( 5748): gss: java.util.concurrent.ExecutionException: aaw
E/YouTube ( 5748): 	at gsl.a(SourceFile:102)
E/YouTube ( 5748): 	at gsm.b(SourceFile:158)
E/YouTube ( 5748): 	at com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService.a(SourceFile:4046)
E/YouTube ( 5748): 	at com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService.a(SourceFile:54)
E/YouTube ( 5748): 	at dyr.run(Unknown Source)
E/YouTube ( 5748): Caused by: java.util.concurrent.ExecutionException: aaw
E/YouTube ( 5748): 	at acv.a(SourceFile:117)
E/YouTube ( 5748): 	at acv.get(SourceFile:88)
E/YouTube ( 5748): 	at hoz.get(SourceFile:69)
E/YouTube ( 5748): 	at gsl.a(SourceFile:98)
E/YouTube ( 5748): 	... 4 more
E/YouTube ( 5748): Caused by: aaw
E/YouTube ( 5748): 	at abz.a(SourceFile:159)
E/YouTube ( 5748): 	at hoh.a(SourceFile:72)
E/YouTube ( 5748): 	at abf.run(SourceFile:112)
,I/ActivityManager( 1014): Killing 4772:com.sec.knox.bridge/1000 (adj 15): empty #31
,I/Gmail   ( 6047): getAccountsCursor
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/JNIHelp ( 5829): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/GAV2    ( 6047): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_4772/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityThread( 5829): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/ActivityManager( 1014): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/System  ( 5829): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1d538d4c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5829): Installed default security provider GmsCore_OpenSSL
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1014): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=6105 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,E/Zygote  ( 6105): MountEmulatedStorage(),
,E/Zygote  ( 6105): v2,
I/libpersona( 6105): KNOX_SDCARD checking this for 10009
I/libpersona( 6105): KNOX_SDCARD not a persona
,I/SELinux ( 6105): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6105): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6105): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 5829): Destroying RTCS
,I/VacuumService( 1776): Vacuum at: now=1451923438257 tag=VacuumService
,W/Gmail   ( 6047): Sync started for account: account:61035162
,I/qtaguid ( 5116): Untagging socket -1
,I/qtaguid ( 5116): Failed write_ctrl(u -1) res=-1 errno=9
,I/qtaguid ( 5116): Untagging socket -1 failed errno=-9
,W/NetworkManagementSocketTagger( 5116): untagSocket(-1) failed with errno -9
E/Gmail   ( 6047): Error finding the version of the Email provider.....
E/Gmail   ( 6047): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6047): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 6047): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 6047): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 6047): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6047): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6047): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 6047): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6047): We do not support migrating this version of the Email provider.
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6128): MountEmulatedStorage()
E/Zygote  ( 6128): v2
I/libpersona( 6128): KNOX_SDCARD checking this for 10125
I/libpersona( 6128): KNOX_SDCARD not a persona
,I/SELinux ( 6128): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6128): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/TimaKeyStoreProvider( 6105): TimaSignature is unavailable
E/SELinux ( 6128): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityThread( 6105): Added TimaKeyStore provider
I/ActivityManager( 1014): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6128 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,D/Finsky  ( 4826): [830] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/hcjo    ( 5116): SelfUpdateManager:REQUEST_UPD_CHECK:onUpdateCheckSuccessAndNoNeedUpdate
,D/hcjo    ( 5116): AutoUpdateManager:CHECK_SELF_UPD:onSelfUpdateResult:T
D/hcjo    ( 5116): SellerAppAutoUpdate:clearFlag
,D/Finsky  ( 4826): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5101): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,D/TimaKeyStoreProvider( 6128): TimaSignature is unavailable
,D/ActivityThread( 6128): Added TimaKeyStore provider
,I/DBG_POLICYDM( 5101): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/ActivityManager( 1014): Killing 4738:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,D/SellerAppAutoUpdateManagerStateMachine( 5116): execute::IDLE:EXECUTE
,D/SellerAppAutoUpdateManagerStateMachine( 5116): exit::IDLE
D/SellerAppAutoUpdateManagerStateMachine( 5116): entry::TOKENCHECK
,I/DBG_POLICYDM( 5101): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts,
,I/DBG_POLICYDM( 5101): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5101): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/Gmail   ( 6047): getAccountsCursor
,D/SellerAppAutoUpdateManagerStateMachine( 5116): execute::TOKENCHECK:TOKEN_RECEIVED
D/SellerAppAutoUpdateManagerStateMachine( 5116): exit::TOKENCHECK
D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/SellerAppAutoUpdateManagerStateMachine( 5116): entry::FAILED
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/hcjo    ( 5116): AutoUpdateManager:SELLER_UPD:onSellerAutoUpdateFailed
D/SellerAppAutoUpdateManagerStateMachine( 5116): exit::FAILED
D/SellerAppAutoUpdateManagerStateMachine( 5116): entry::IDLE
,I/DBG_POLICYDM( 5101): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5101): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/Gmail   ( 6047): Observing account changes for notifications
,I/DBG_POLICYDM( 5101): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
E/SQLiteLog( 6047): (283) recovered 77 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5067): mConnectivityHandler : connected
,I/SA      ( 5285): [RC New] Execute method=[GET] start
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1014): Killing 5015:com.android.mms/u0a46 (adj 15): empty #31
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.cache.DataUpdateListenerCacheService; callingUser = 0; userId(target) = 0
,E/DBG_POLICYDM( 5101): [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,W/ResourcesManager( 6128): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6128): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6128): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/libprocessgroup( 1014): failed to open /acct/uid_10032/pid_4738/cgroup.procs: No such file or directory
,W/PCWCLIENTTRACE_AccountUtil( 5067): [hasSamungAccount] - No Samsung Account
,I/art     ( 1633): Explicit concurrent mark sweep GC freed 3018(119KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.054ms total 46.569ms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/CountryDetector( 1014): No listener is left
,I/SA      ( 5285): [RC New] Security=[true]
,I/System.out( 5285): Thread-905(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5285): Thread-905(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5285): Thread-905(ApacheHTTPLog):isShipBuild true
I/System.out( 5285): Thread-905(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5285): Thread-905(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10041
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10041
,D/QuickConnect( 6128): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5101): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/QuickConnect( 6128): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6128): PeriphStartReceiver.onReceive - no need to start
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1014): failed to open /acct/uid_10046/pid_5015/cgroup.procs: No such file or directory
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5067): [GetString-S]
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 25384(1202KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 3.135ms total 183.581ms
,I/ActivityManager( 1014): Killing 5208:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,E/File    ( 6047): fail readDirectory() errno=2
,I/ReactiveServiceManager( 5067): Supported : 1
,D/QSEECOMAPI: ( 1014): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1014): App is not loaded in QSEE
,I/Gmail   ( 6047): notifyAccountChanged
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1776): Tagging socket 78 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1776, getuid(): 10012
,I/Gmail   ( 6047): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6047): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/QSEECOMAPI: ( 1014): Loaded image: APP id = 10
,D/QSEECOMAPI: ( 1014): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1014): QSEECom_shutdown_app, app_id = 10
I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,E/terrier ( 1014): handleString: Failed to handle string(-4)
E/terrier ( 1014): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 5067): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5067): [GetString-E]
D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/PCWCLIENTTRACE_PushUtil( 5067): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5067): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5067): getPushTypeList : [SPP, GCM],
E/PCWCLIENTTRACE_PCWHandler( 5067): [ensureRegistration] - No Samsung account
I/System.out( 1776): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1776): Tagging socket 94 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1776, getuid(): 10012
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1776): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1776): Tagging socket 97 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1776, getuid(): 10012
,I/Gmail   ( 6047): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6047): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6047): notifyAccountChanged
,I/qtaguid ( 1776): Tagging socket 99 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1776, getuid(): 10012
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/qtaguid ( 1776): Tagging socket 103 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1776, getuid(): 10012
,W/DriveInitializer( 1970): Awaiting to be initialized
,I/ActivityManager( 1014): Killing 5242:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,I/ActivityManager( 1014): Killing 5224:com.wsomacp/u0a25 (adj 15): empty #32
,W/libprocessgroup( 1014): failed to open /acct/uid_10047/pid_5208/cgroup.procs: No such file or directory
,I/FOTA_Client( 6105): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/FOTA_Client( 6105): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,W/DriveInitializer( 1970): Background init thread started
,I/ActivityManager( 1014): Killing 4695:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,I/FOTA_Client( 6105): [IlIlIIllllIllIIIIIll(86/llllIIIllIlIIIIllllI)] Polling time is not vaild
,I/FOTA_Client( 6105): [com.sec.android.fotaclient.FotaUpdaterReceiver(101/onReceive)] Polling time is already passed. Start device init Immediately
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,I/ActivityManager( 1014): Waited long enough for: ServiceRecord{b2e8329 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,I/System.out( 1776): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1776): Tagging socket 90 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1776, getuid(): 10012
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 1970): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,D/ActivityManager( 1014): startService callerProcessName:com.sec.android.fotaclient, calleePkgName: com.sec.android.fotaclient
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.fotaclient/com.sec.android.fotaclient.FotaUpdateIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.fotaclient, destAppInfo.processName = com.sec.android.fotaclient
,W/FOTA_Client( 6105): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/splitIntent( 1014): Queue : background intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart  false.
,I/qtaguid ( 1776): Tagging socket 93 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1776, getuid(): 10012
,I/FOTA_Client( 6105): [com.sec.android.fotaclient.FotaUpdateIntentService(30/onHandleIntent)] Update State: Start update request
,I/splitIntent( 1014): Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=13, mSplitNum[2]=18, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=24
,I/splitIntent( 1014): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,I/FOTA_Client( 6105): [IIIlIIIIIIlIlllllllI(45/llIIIIlllllIIllIIllI)] Update State: Check condition to decide update type
,I/FOTA_Client( 6105): [lIllIIIllIIllIIlIllI(143/llIIIIlllllIIllIIllI)] Update State: Checking polling to server
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/FOTA_Client( 6105): [lIllIllllIIIlllIlllI(88/llllIIIllIlIIIIllllI)] WiFi Network is connected
,W/libprocessgroup( 1014): failed to open /acct/uid_10025/pid_5224/cgroup.procs: No such file or directory
,E/Zygote  ( 6168): MountEmulatedStorage(),
I/libpersona( 6168): KNOX_SDCARD checking this for 10062
E/Zygote  ( 6168): v2
I/libpersona( 6168): KNOX_SDCARD not a persona
,I/SELinux ( 6168): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6168): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6168): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1014): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6168 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/FOTA_Client( 6105): [lIIllIIIIIlllIIlllIl(28/llIIIIlllllIIllIIllI)] Request Network Connection,
,I/FOTA_Client( 6105): [lIllIllllIIIlllIlllI(88/llllIIIllIlIIIIllllI)] WiFi Network is connected
,E/Zygote  ( 6182): MountEmulatedStorage()
E/Zygote  ( 6182): v2
I/libpersona( 6182): KNOX_SDCARD checking this for 10135
I/libpersona( 6182): KNOX_SDCARD not a persona
I/SELinux ( 6182): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6182 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 6182): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6182): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/daemonapp( 1310): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1310): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1310): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
I/FOTA_Client( 6105): [com.sec.android.fota.osp.time.llIIIIlllllIIllIIllI(87/llIIIIlllllIIllIIllI)] Server time was not matched, Server time is too old
,E/SMD     (  287): DCD OFF
,D/TimaKeyStoreProvider( 6168): TimaSignature is unavailable
I/FOTA_Client( 6105): [com.sec.android.fota.osp.time.llIIIIlllllIIllIIllI(111/llllIIIllIlIIIIllllI)] Request ServerTime
,D/ActivityThread( 6168): Added TimaKeyStore provider
,I/FOTA_Client( 6105): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,D/TimaKeyStoreProvider( 6182): TimaSignature is unavailable
,D/ActivityThread( 6182): Added TimaKeyStore provider
,I/FOTA_Client( 6105): [com.sec.android.fota.osp.http.RestClient(264/llIIIIlllllIIllIIllI)] =====================================================================
,D/daemonapp( 1310): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1310): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1310): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 1310): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1310): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1310): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1310): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1310): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1310): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/FOTA_Client( 6105): [com.sec.android.fota.osp.http.RestClient(276/llIIIIlllllIIllIIllI)] =====================================================================
,I/KLMS-2.5.183: ( 3358): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Mon Jan 04 17:03:59 GMT+01:00 2016
,I/System.out( 6105): Thread-1017(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 6105): Thread-1017(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6105): Thread-1017(ApacheHTTPLog):isShipBuild true
I/System.out( 6105): Thread-1017(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6105): Thread-1017(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10009
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10009
,D/daemonapp( 1310): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1310): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1310): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1310): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,D/daemonapp( 1310): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,W/ResourcesManager( 6182): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,I/KLMS-2.5.183: ( 3358): KLMSAbstractReciever(): onReceive().END.
,I/SA      ( 5285): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,W/ResourcesManager( 6182): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6182): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/DriveInitializer( 1970): Background init thread ended
,I/ExternalOEMControlProvider( 6168): onCreate
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.PeopleSyncService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1014): failed to open /acct/uid_10053/pid_5242/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10057/pid_4695/cgroup.procs: No such file or directory
,I/KLMS-2.5.183: ( 3358): KLMSIntentService(): onCreate()
,E/daemonapp( 1310): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,I/KLMS-2.5.183: ( 3358): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/Gmail   ( 6047): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 13779, normalSync: true
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3358): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3358): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,I/System.out( 6105): IntentService[Service[FotaUpdateIntentService]] calls detatch()
,I/KLMS-2.5.183: ( 3358): KLMSIntentService(): TIME_CHANGED
,E/Zygote  ( 6215): MountEmulatedStorage()
E/Zygote  ( 6215): v2
I/libpersona( 6215): KNOX_SDCARD checking this for 1000
I/libpersona( 6215): KNOX_SDCARD not a persona
I/SELinux ( 6215): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6215): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6215): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.contextagent.ContextAgentReceiver: pid=6215 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/KLMS-2.5.183: ( 3358): StateImplV2(): dateTimeChanged().START : Mon Jan 04 17:03:59 GMT+01:00 2016
,D/comdaemonstockapp( 1310): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 1310): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/daemonapp( 1310): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,I/FOTA_Client( 6105): [com.sec.android.fota.osp.time.llIIIIlllllIIllIIllI(139/llllIIIllIlIIIIllllI)] Receive result: success in ServerTime
,I/FOTA_Client( 6105): [com.sec.android.fota.osp.http.RestClient(264/llIIIIlllllIIllIIllI)] =====================================================================
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3358): StateImplV2(): dateTimeChanged().END
,D/TimaKeyStoreProvider( 6215): TimaSignature is unavailable
,D/ActivityThread( 6215): Added TimaKeyStore provider
,E/Zygote  ( 6230): MountEmulatedStorage()
I/ActivityManager( 1014): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=6230 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
E/Zygote  ( 6230): v2
I/libpersona( 6230): KNOX_SDCARD checking this for 10046
I/libpersona( 6230): KNOX_SDCARD not a persona
,I/SELinux ( 6230): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ Time Manager ( 6168): Time Difference not stored. TIME_DIFFERENCE
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,I/SELinux ( 6230): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6230): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 6230): TimaSignature is unavailable
,D/ActivityThread( 6230): Added TimaKeyStore provider
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/KLMS-2.5.183: ( 3358): KLMSIntentService(): onDestroy()
,I/art     ( 1970): Explicit concurrent mark sweep GC freed 13630(1133KB) AllocSpace objects, 32(512KB) LOS objects, 39% free, 14MB/23MB, paused 1.621ms total 108.252ms
,W/ResourcesManager( 6215): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/FOTA_Client( 6105): [com.sec.android.fota.osp.http.RestClient(276/llIIIIlllllIIllIIllI)] =====================================================================
,I/System.out( 6105): Thread-1017(ApacheHTTPLog):isSBSettingEnabled false
W/ResourcesManager( 6230): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,I/System.out( 6105): Thread-1017(ApacheHTTPLog):isShipBuild true
W/ResourcesManager( 6230): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6230): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6230): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6230): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/System.out( 6105): Thread-1017(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,W/ResourcesManager( 6230): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/System.out( 6105): Thread-1017(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10009
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10009
,I/CheckinService( 1970): Checkin interval check for package: unspecified last checkin: 1451089911968 min interval config: 0 actual interval: 833527460
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6250): MountEmulatedStorage()
E/Zygote  ( 6250): v2
I/libpersona( 6250): KNOX_SDCARD checking this for 10042
I/libpersona( 6250): KNOX_SDCARD not a persona
,I/SELinux ( 6250): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6250): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6250): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1014): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6250 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityManager( 1014): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/art     ( 5829): Attempt to remove local handle scope entry from IRT, ignoring
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/Mms/MmsApp( 6230): [start]    onCreate() consume time = 0.0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/SecurityLogAgent( 5586): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5586): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5586): StateMachine : Current State = 1
,D/TimaKeyStoreProvider( 6250): TimaSignature is unavailable
,D/ActivityThread( 6250): Added TimaKeyStore provider
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,I/dex2oat ( 6249): ----------------------------------------------------
I/dex2oat ( 6249): <SS>: S T A R T I N G . . .
I/dex2oat ( 6249): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 6249): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/cache/ads-78145250.jar --oat-fd=114 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/cache/ads-78145250.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/accuweather( 1719): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 1719): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6274): MountEmulatedStorage()
E/Zygote  ( 6274): v2
I/libpersona( 6274): KNOX_SDCARD checking this for 10157
I/libpersona( 6274): KNOX_SDCARD not a persona
,I/SELinux ( 6274): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6274): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6274): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=6274 uid=10157 gids={50157, 9997} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 5166:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,I/SA      ( 5285): [RC New] [v2liruge] api execute + 1085
I/SA      ( 5285): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5285): AsyncTask #1 calls detatch()
,I/art     (  314): Explicit concurrent mark sweep GC freed 8712(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 661us total 24.030ms
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6274): TimaSignature is unavailable
,D/ActivityThread( 6274): Added TimaKeyStore provider
,I/SA      ( 5285): [ODM] saveOpenData( GEO_IP, PL )
,W/ResourcesManager( 6250): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 618us total 18.267ms
,I/SA      ( 5285): [OCP] update openData : PL
,I/System.out( 6105): IntentService[Service[FotaUpdateIntentService]] calls detatch()
,I/FOTA_Client( 6105): [IIllIIIIlIlIlIlIllII(102/llIIIIlllllIIllIIllI)] result is success
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 618us total 19.361ms,
,I/SA      ( 5285): [TPMU] getNetworkMcc : ,
,I/SA      ( 5285): [SCU] saveMccToPreferece Start
,I/SA      ( 5285): [SCU] RegionMCC : 260
I/SA      ( 5285): [SSP] query invoked
,I/ActivityManager( 1014): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6292 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6292): MountEmulatedStorage()
E/Zygote  ( 6292): v2
I/libpersona( 6292): KNOX_SDCARD checking this for 10085
I/libpersona( 6292): KNOX_SDCARD not a persona
I/SELinux ( 6292): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6292): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6292): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/PeopleSync( 1970): onPerformSync() [5005f081]
,D/SettingsProvider( 1014): name = FOTA_CLIENT_HEARTBEAT_PERIOD
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1014): selectionArgs: false
,D/SettingsProvider( 1014): selectionArgs: 10009
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1014): ret = -1
,I/CalendarProvider2( 6250): CalendarProvider2.onCreate() called
,D/SettingsProvider( 1014): name = FOTA_CLIENT_HEARTBEAT_ADD
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10009
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=10009
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/dex2oat ( 6249): dex2oat took 211.296ms (threads: 4)
,I/FOTA_Client( 6105): [llIllIIlIIIIIIIllllI(191/IllIlIIIIlIIlIIIllIl)] Request NetActionGetPolling
,D/TimaKeyStoreProvider( 6292): TimaSignature is unavailable
I/FOTA_Client( 6105): [lIllIIIllIIllIIlIllI(146/llIIIIlllllIIllIIllI)] Receive result: success in NetActionGetPolling
,D/ActivityThread( 6292): Added TimaKeyStore provider
,W/ResourcesManager( 6274): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/FOTA_Client( 6105): [IIllIIIIlIlIlIlIllII(193/IIIIllIlIIlIIIIlllIl)] Find Firmware version in Version List
,I/FOTA_Client( 6105): [IIIlIIllllllIllIlIII(177/llIIIIlllllIIllIIllI)] Update State: success to check polling
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ProcessCpuTracker( 1014): Skipping unknown process pid 6249
,W/ResourcesManager( 6292): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6292): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6292): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6292): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6292): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6292): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,W/libprocessgroup( 1014): failed to open /acct/uid_10038/pid_5166/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6310): MountEmulatedStorage()
I/libpersona( 6310): KNOX_SDCARD checking this for 1000
,E/Zygote  ( 6310): v2
,I/libpersona( 6310): KNOX_SDCARD not a persona
I/SELinux ( 6310): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6310): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6310): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6310 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 5082:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,I/FOTA_Client( 6105): [IlIlIIllllIllIIIIIll(37/llIIIIlllllIIllIIllI)] Calculate next polling time
,D/SettingsProvider( 1014): name = FOTA_CLIENT_POLLING_TIME
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10009
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=10009
,I/FOTA_Client( 6105): [llIllIIIIlllIIlIIllI(238/llIIIIlllllIIllIIllI)] Update State: Initialize polling update
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/FOTA_Client( 6105): [llIllIIlIIIIIIIllllI(248/IlIlIlIlIlIIlllllIlI)] request Polling
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 6310): TimaSignature is unavailable
,D/ActivityThread( 6310): Added TimaKeyStore provider
,I/FOTA_Client( 6105): [com.sec.android.fotaclient.FotaUpdateIntentService(36/onHandleIntent)] Update State: Finish update request
,I/SA      ( 5285): [TPMU] GetMccFromDB : null
I/SA      ( 5285): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5285): [SCU] saveMccToPreferece End
,I/SA      ( 5285): [RC New] executeRequest [v2liruge] end. 1482
I/SA      ( 5285): [RC New] Execute end
,I/ActivityManager( 1014): Killing 5341:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,I/Gmail   ( 6047): getAccountsCursor
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimeService( 6310): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1451923439978
D/        ( 6310): TimeServiceNative: User Time to be set is 1451923439978
D/QC-time-services( 6310): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6310): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6310): Lib:time_genoff_operation: pargs->ts_val = 1451923439978
,D/QC-time-services( 6310): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  324): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  324): Daemon:Received base = 2, unit = 1, operation = 0,value = 1451923439978
D/QC-time-services(  324): Daemon:genoff_opr: Base = 2, val = 1451923439978, operation = 0
,D/QC-time-services(  324): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS6/5/70 14:10:28
D/QC-time-services(  324): Daemon:Value read from RTC seconds = 16035028000
D/QC-time-services(  324): Daemon:new time 1451923439978 
D/QC-time-services(  324): Daemon: delta 1435888411978 genoff 1435888411978 
D/QC-time-services(  324): Daemon:genoff_persistent_update: Writing genoff = 1435888411978 to memory
D/QC-time-services(  324): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  324): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/Zygote  ( 6327): MountEmulatedStorage(),
I/libpersona( 6327): KNOX_SDCARD checking this for 10012
E/Zygote  ( 6327): v2
,I/libpersona( 6327): KNOX_SDCARD not a persona
I/SA      ( 5285): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5285): [OR] GetMyCountryZoneTask Success
I/SELinux ( 6327): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6327): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6327): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6327 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
,V/AlarmManager( 1014): waitForAlarm result :8
,D/QC-time-services(  324): Updating the TOD offset
D/QC-time-services(  324): Daemon:genoff_persistent_update: Writing genoff = 1435888411978 to memory
D/QC-time-services(  324): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  324): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/SettingsProvider( 1014): name = next_alarm_formatted
,D/TimaKeyStoreProvider( 6327): TimaSignature is unavailable,
E/QC-time-services(  324): Daemon:Update to modem bit set,
D/QC-time-services(  324): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  324): Daemon: Base = 2, Value being sent to MODEM = 1119923611978,
D/ActivityThread( 6327): Added TimaKeyStore provider
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed,
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10085
E/QC-time-services(  324): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40,
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
E/QC-time-services(  324): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services( 6310): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,W/art     ( 6230): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 472.206ms
,I/ActivityManager( 1014): Killing 5361:com.samsung.helphub/1000 (adj 15): empty #31
,W/ResourcesManager( 6327): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6327): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager( 1014): Killing 5192:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,I/Gmail   ( 6047): getAccountsCursor
,I/MultiDex( 6327): VM with version 2.1.0 has multidex support
,I/MultiDex( 6327): install
,I/MultiDex( 6327): VM has multidex support, MultiDex support library is disabled.
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/SurfaceFlinger(  257): id=14 Removed Uoast (8/9)
,W/libprocessgroup( 1014): failed to open /acct/uid_10100/pid_5341/cgroup.procs: No such file or directory
,D/PowerManagerService( 1014): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1014) eventTime = 89813
,D/PowerManagerService( 1014): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014 (0x0)
,D/PowerManagerService( 1014): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1014, ws=WorkSource{1000}) (elapsedTime=3392)
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/EnterpriseController(  277): uids 10104
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10104
,W/libprocessgroup( 1014): failed to open /acct/uid_10091/pid_5082/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10072/pid_5192/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5361/cgroup.procs: No such file or directory
,I/dhcpcd  ( 5655): wlan0: sending IPv6 Router Solicitation
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,V/JNIHelp ( 6327): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityThread( 6327): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6327): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@17f02e15: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6327): Installed default security provider GmsCore_OpenSSL
,W/art     ( 6230): Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 238.989ms
,D/Mms/ArtClassLoader( 6230): init before art
,D/Mms/TelephonyPermission( 6230): start operation mode monitor
,W/ResourcesManager( 6230): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 6327): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6327): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/Mms/TelephonyPermission( 6230): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 6230): isDefault true
,D/Mms/MmsApp( 6230): onCreate() com.android.mms
,W/art     ( 6292): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 361.342ms
,D/NativeLibraryUtils( 6327): Install completed successfully. count=14 extracted=0
,W/art     ( 6230): Verification of com.android.mms.prioritysender.PrioritySenderListAdapter com.android.mms.ui.ConversationListFragment.access$3200(com.android.mms.ui.ConversationListFragment) took 101.898ms
,W/ResourcesManager( 6047): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6047): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 24192(1184KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 3.780ms total 157.571ms
,D/Mms/MmsApp( 6230): [start]    initCountryIso consume time = 1072.111301
,D/CountryDetector( 1014): The first listener is added
,D/Mms/MmsApp( 6230): [end]    initCountryIso consume time = 38.193855
D/Mms/MmsConfig( 6230): [start]    MmsConfig.init() consume time = 0.121666
,D/WVCdm   (  282): Instantiating CDM.
,D/Mms/MmsConfig( 6230): before partial update
,I/WVCdm   (  282): CdmEngine::OpenSession
,I/WVCdm   (  282): Level3 Library Sep 25 2014 17:10:03
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
W/WVCdm   (  282): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
I/ActivityManager( 1014): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6358 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
E/Zygote  ( 6358): MountEmulatedStorage()
E/Zygote  ( 6358): v2
I/libpersona( 6358): KNOX_SDCARD checking this for 10094
I/libpersona( 6358): KNOX_SDCARD not a persona
I/SELinux ( 6358): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6358): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/DrmWidevineDash(  282): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
D/DrmWidevineDash(  282): Service_Initialize: starts!
D/QSEECOMAPI: (  282): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  282): App is not loaded in QSEE
E/QSEECOMAPI: (  282): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  282): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  282): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  282): App is not loaded in QSEE
E/QSEECOMAPI: (  282): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  282): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  282): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  282): App is not loaded in QSEE
I/ActivityManager( 1014): Killing 5607:com.samsung.android.app.FileShareClient/u0a68 (adj 15): empty #31
E/SELinux ( 6358): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/QSEECOMAPI: (  282): Loaded image: APP id = 11
D/DrmWidevineDash(  282): Service_Initialize: ends! returns 0
D/QSAPPSVER(  282): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  282): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  282): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb16d0000
E/DrmWidevineDash(  282): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb16d0000
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/TimaKeyStoreProvider( 6358): TimaSignature is unavailable
D/DrmLibTime(  422): got the req here! ret=0
D/DrmLibTime(  422): command id, time_cmd_id = 770
D/DrmLibTime(  422): time_getutcsec starts!
D/DrmLibTime(  422): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  422): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  422): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  422): QSEE Time Listener: Checking if ATS_MODEM is set or not.
D/QC-time-services(  422): Lib:time_genoff_operation: pargs->base = 13
D/QC-time-services(  422): Lib:time_genoff_operation: pargs->operation = 2
D/QC-time-services(  422): Lib:time_genoff_operation: pargs->ts_val = 0
D/QC-time-services(  422): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  324): Daemon: Connection accepted:time_genoff
D/QC-time-services(  324): Daemon:Received base = 13, unit = 1, operation = 2,value = 0
D/QC-time-services(  324): Daemon:genoff_opr: Base = 13, val = 0, operation = 2
D/QC-time-services(  324): offset is: 0 for base: 0
E/QC-time-services(  422): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  422): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  422): QSEE Time Listener: Retrieved Android system time: 1451923440
D/DrmLibTime(  422): time_getutcsec returns 0, sec = 1451923440; nsec = 0
D/DrmLibTime(  422): time_getutcsec finished! 
D/DrmLibTime(  422): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  422): before calling ioctl to read the next time_cmd
E/QC-time-services(  324): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/ActivityThread( 6358): Added TimaKeyStore provider
,D/DrmWidevineDash(  282): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  282): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  282): hlos api version =  9
D/DrmWidevineDash(  282): tz api version =  9
D/DrmWidevineDash(  282): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  282): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/Mms/MmsConfig( 6230): Load Resize quality : 80
,W/libprocessgroup( 1014): failed to open /acct/uid_10068/pid_5607/cgroup.procs: No such file or directory
,I/GoogleURLConnFactory( 6327): Using platform SSLCertificateSocketFactory
,D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  282): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  282): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  282): OEMCrypto_OpenSession: starts! SID=0xbeb971b0
D/DrmWidevineDash(  282): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  282): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  282): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  282): OEMCrypto_GetRandom: starts! randomData=0xb85b4f98, dataLength=8
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  282): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  282): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb85dca30, wrapped_rsa_key_length=1280
,D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/elm:15183( 6358): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  282): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  282): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  282): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,D/elm:15183( 6358): ELMEngine.ELMEngine( context ).
,I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  282): OEMCrypto_GetDeviceID: starts! deviceID=0xb85b4360, idLength=0xb1264730
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/EasySignUpManager_1.0.1( 6230): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 6230): isAuth is false
,D/Mms/MmsConfig( 6230): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/elm:15183( 6358): MDMBridge.setEnterpriseBridge()
,D/TP/MmsSmsProvider( 1441): query,matched:2117, calling pid = 6230
,D/TP/MmsSmsProvider( 1441): match 2117:Elapsed time : 1.125 ms
,I/ActivityManager( 1014): Killing 5627:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  282): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  282): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  282): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  282): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  282): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  282): OEMCrypto_GetHDCPCapability: starts!, current = 0xb1264746, maximum = 0xb1264747
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  282): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  282): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  282): hlos api version =  9
D/DrmWidevineDash(  282): tz api version =  9
D/DrmWidevineDash(  282): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  282): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xb12647b4
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  282): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  282): PrepareKeyRequest: nonce=3841671227
D/DrmWidevineDash(  282): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb85dc678
D/DrmWidevineDash(  282): message_length=1599, signature=0xb85dccc0, signature_length=0xb1264714
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/System.out( 6327): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,D/EasySignUpManager_1.0.1( 6230): isAuth is false
D/EasySignUpManager_1.0.1( 6230): getServiceStatus : serviceId (1) is OFF
,I/System.out( 6327): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 6327): (HTTPLog)-Static: isShipBuild true
I/System.out( 6327): (HTTPLog)-Thread-1060-885145474: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 6327): (HTTPLog)-Static: isSBSettingEnabled false
E/CscParser( 6230): mps_code.dat does not exist
E/CscParser( 6230): customer_path =/system/csc/customer.xml
E/CscParser( 6230): fileName + /system/csc/customer.xml
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,W/art     ( 6230): Verification of boolean com.android.mms.ui.ConversationListFragment.onOptionsItemSelected(android.view.MenuItem) took 141.744ms
,I/System.out( 6327): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 6327): Tagging socket 30 with tag 1000180300000000{268441603,0} for uid 10012, pid: 6327, getuid(): 10012
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/art     ( 6047): Suspending all threads took: 9.144ms
,D/elm:15183( 6358): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,E/CscParser( 6230): mps_code.dat does not exist
,E/CscParser( 6230): customer_path =/system/csc/customer.xml
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/CscParser( 6230): fileName + /system/csc/customer.xml,
I/ActivityManager( 1014): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6379 uid=10134 gids={50134, 9997} abi=armeabi-v7a
,E/Zygote  ( 6379): MountEmulatedStorage(),
I/PeopleSync( 1970): Setting subscription: result=true [5005f081]
I/PeopleSync( 1970): Starting sync, feed=null [5005f081]
,E/Zygote  ( 6379): v2
I/libpersona( 6379): KNOX_SDCARD checking this for 10134
I/libpersona( 6379): KNOX_SDCARD not a persona,
,I/qtaguid ( 6327): Tagging socket 34 with tag 1000180300000000{268441603,0} for uid 10012, pid: 6327, getuid(): 10012
,I/SELinux ( 6379): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6379): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6379): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/elm:15183( 6358): ElmAgentService : onCreate()
,D/elm:15183( 6358): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/TimaKeyStoreProvider( 6379): TimaSignature is unavailable
,D/ActivityThread( 6379): Added TimaKeyStore provider
,W/ResourcesManager( 6379): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6379): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/elm:15183( 6358): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:15183( 6358): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:15183( 6358): ModuleBase.ModifySetAlarm()
D/elm:15183( 6358): MDMBridge.getInstance()
D/elm:15183( 6358): MDMBridge.getAllLicenseInfoFromSDK()
D/CscParser( 6230): getInstance fileName =/system/csc/customer.xml
,D/elm:15183( 6358): ElmAgentService : onDestroy().
,I/ActivityManager( 1014): Killing 5476:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,D/Mms/MmsConfig( 6230):  enable multiwindow = true
,I/ActivityManager( 1014): Killing 5506:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  282): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  282): CdmEngine::CloseSession
,D/DrmWidevineDash(  282): OEMCrypto_CloseSession: starts! SID=1
,D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  282): OEMCrypto_CloseSession: ends! returns 0
W/libprocessgroup( 1014): failed to open /acct/uid_10069/pid_5627/cgroup.procs: No such file or directory
,I/WVCdm   (  282): L3 Terminate.
D/DrmWidevineDash(  282): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  282): Service_Uninitialize: starts!
D/QSEECOMAPI: (  282): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  282): QSEECom_shutdown_app, app_id = 11
D/DrmWidevineDash(  282): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  282): OEMCrypto_Terminate: ends! returns 0
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 5829): Creating RTCS
,E/Mms/MessageUtils( 6230): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 6230): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 6230): [end]    init() consume time = 409.680365
,D/Mms/Contact( 6230): [start]    init() consume time = 1.82401
,V/JNIHelp ( 6047): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     ( 5829): Note: end time exceeds epoch: 
,D/TP/MmsSmsProvider( 1441): query,matched:13, calling pid = 6230
,D/TP/MmsSmsProvider( 1441): match 13:Elapsed time : 0.961 ms
,D/Mms/Contact( 6230): [end]    init consume time = 18.023698
,I/Babel   ( 5829): Account registration complete:Redacted-21
,D/Mms/DraftCache( 6230): [start]    rebuildCache consume time = 13.143438
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/libprocessgroup( 1014): failed to open /acct/uid_10003/pid_5476/cgroup.procs: No such file or directory
,I/qtaguid ( 6327): Untagging socket 30,
,D/TP/MmsSmsProvider( 1441): query,matched:12, calling pid = 6230
,D/TP/MmsSmsProvider( 1441): match 12:Elapsed time : 1.699 ms
,I/Babel   ( 5829): ProcessRegisterDeviceResponse
,I/Babel   ( 5829): Perform warm sync in case there are messages missed before the device is registered for account Redacted-21
,W/libprocessgroup( 1014): failed to open /acct/uid_10107/pid_5506/cgroup.procs: No such file or directory
,D/Mms/MethodReflector( 6230): getSubId is called
,D/Mms/TelephonyUtils( 6230): getLongSubId from simSlot 0, return Value = -1
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/MethodReflector( 6230): getTelephonyProperty is called
,D/Mms/DraftCache( 6230): [end]    rebuildCache consume time = 62.594322
,D/Mms/DownloadManager( 6230): roaming -> false (slotId = 0)
,D/Mms/DownloadManager( 6230): [NotificationTransaction] getAutoDownloadState simSlot : 0
,D/Mms/DownloadManager( 6230): auto download without roaming -> true
,D/Mms/DownloadManager( 6230): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,D/Mms/MethodReflector( 6230): getSubId is called
,D/Mms/MethodReflector( 6230): getDefaultSmsSubId is called
,E/Mms/TelephonyUtils( 6230): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 6230): getLongSubId from simSlot 1, return Value = -1000
,D/Mms/MethodReflector( 6230): getTelephonyProperty is called
,D/Mms/DownloadManager( 6230): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 6230): [NotificationTransaction] getAutoDownloadState simSlot : 1
,D/Mms/DownloadManager( 6230): auto download without roaming -> true
D/Mms/DownloadManager( 6230): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
,D/Mms/DownloadManager( 6230): auto download during roaming secondary -> false
D/Mms/DownloadManager( 6230): mAutoDownload ------> true
,I/chromium( 5321): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/AlarmManager( 1014): waitForAlarm result :4
,V/AlarmManager( 1014): ___SyncScheduler (v3) ACTIVATED___
,D/ComposerPerformance( 6230): 1451923441199 ms / [DONE] Composer constructor
,E/CII     ( 6230): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 6230): ReservationManager()
I/Mms/ReservationManager( 6230): resetAfterConnected()
,D/TP/MmsSmsProvider( 1441): query,matched:7, calling pid = 6230
,D/TP/MmsSmsProvider( 1441): match 7:Elapsed time : 2.153 ms
,I/CalendarProvider2( 6250): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,V/AlarmManagerEXT( 1014): <AppSync3 Whitelist>
,V/AlarmManagerEXT( 1014): (AppSync) ### 0 added ###
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/Mms/Conversation( 6230): [start]    init() consume time = 110.89875
,I/ActivityManager( 1014): Killing 5067:com.sec.pcw.device/1000 (adj 15): empty #31
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/TP/MmsSmsProvider( 1441): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1441): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1441): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1441): sUpgradeVersion = 0, db.getVersion() = 81
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/TP/MmsSmsProvider( 1441): delete threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1441): need read changed broadcast:false
,D/Mms/Conversation( 6230): [end]    init consume time = 30.503698
,D/Mms/MessagingNotification( 6230): [start]    init() consume time = 9.569584
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/Mms/MessagingNotification( 6230): [end]    init consume time = 19.710156
,D/Mms/SpamFilter( 6230): [start]    SpamFilter fill() begin consume time = 4.393333
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/Mms/ReservationManager( 6230): getReservedSendMessageCount(): retMessageCount=0
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/Mms/MmsApp( 6230): [end]    onCreate() consume time = 8.139479
,W/ActivityThread( 6047): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6047): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@33b164eb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6047): Installed default security provider GmsCore_OpenSSL
D/TP/MmsSmsProvider( 1441): query,matched:0, calling pid = 6230
,V/TP/MmsSmsProvider( 1441): getSimpleConversations entered.
,D/Mms/ArtClassLoader( 6230): init [DONE] art
,D/Mms/Synchronizer( 6230): [start]    doSync consume time = 7.183386
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5067/cgroup.procs: No such file or directory
D/TP/MmsSmsProvider( 1441): match 0:Elapsed time : 3.339 ms
,D/TP/MmsSmsProvider( 1441): query,matched:400, calling pid = 6230
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TP/MmsSmsProvider( 1441): update, matched:300, calling pid = 6230
,V/TP/MmsSmsProvider( 1441): syncDBData start
,V/TP/MmsSmsProvider( 1441): syncDBData sms end
V/TP/MmsSmsProvider( 1441): syncDBData mms end
,V/TP/MmsSmsProvider( 1441): syncDBData end
,D/Mms/SpamFilter( 6230): [end]    SpamFilter fill() finished consume time = 20.68526
,W/BaseAppContext( 1970): Using Auth Proxy for data requests.
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,D/Mms/Synchronizer( 6230): [end]    doSync consume time = 7.880573
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1014): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6412 uid=10072 gids={50072, 9997} abi=armeabi-v7a
E/Zygote  ( 6412): MountEmulatedStorage()
E/Zygote  ( 6412): v2
I/libpersona( 6412): KNOX_SDCARD checking this for 10072
I/libpersona( 6412): KNOX_SDCARD not a persona
,I/SELinux ( 6412): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6412): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/Mms/DownloadManager( 6230): Service state changed: Bundle[mParcelledData.dataSize=744]
D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/Mms/DownloadManager( 6230): roaming ------> false, mSimSlot = 0
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SELinux ( 6412): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/Mms/MethodReflector( 6230): getSubId is called
I/splitIntent( 1014): Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
D/Mms/TelephonyUtils( 6230): getLongSubId from simSlot 0, return Value = -1
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,D/Mms/MethodReflector( 6230): getTelephonyProperty is called
D/Mms/DownloadManager( 6230): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 6230): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 6230): auto download without roaming -> true
D/Mms/DownloadManager( 6230): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,D/Mms/DownloadManager( 6230): mAutoDownload ------> true
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/TimaKeyStoreProvider( 6412): TimaSignature is unavailable
,D/ActivityThread( 6412): Added TimaKeyStore provider
,W/BaseAppContext( 1970): Using Auth Proxy for data requests.
,I/ActivityManager( 1014): Killing 4826:com.android.vending/u0a28 (adj 15): empty #31
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 5829): Note: end time exceeds epoch: 
,I/ActivityManager( 1014): Killing 5712:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1776): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
W/BaseAppContext( 1970): Using Auth Proxy for data requests.
D/BadgeProvider( 6412): onCreate
D/BadgeProvider( 6412): DatabaseHelper
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.fotaclient, destAppInfo.processName = com.wssyncmldm
,I/PeopleSync( 1970): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,I/DBG_DM  ( 2909): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,D/Mms/MessagingNotification( 6230): checkBadgeCount unreadCount=0 badgeCount=0
,I/DBG_DM  ( 2909): [llIIIllllIIIlIIIlIIl(1846/llIlIIIIlIIIIIlIlIII)] flag is : false
,D/TP/SmsProvider( 1441): query,matched:26, calling pid = 6230
,D/TP/SmsProvider( 1441): match 26:Elapsed time : 1.385 ms
,D/TP/MmsSmsProvider( 1441): query,matched:6, calling pid = 6230
,D/TP/MmsSmsProvider( 1441): match 6:Elapsed time : 0.814 ms
,W/libprocessgroup( 1014): failed to open /acct/uid_10159/pid_5712/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10028/pid_4826/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/art     ( 1633): Explicit concurrent mark sweep GC freed 2788(109KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 755us total 36.867ms
,E/Zygote  ( 6430): MountEmulatedStorage()
,E/Zygote  ( 6430): v2
I/libpersona( 6430): KNOX_SDCARD checking this for 10025
I/libpersona( 6430): KNOX_SDCARD not a persona
,I/SELinux ( 6430): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6430): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6430): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6430 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,I/DBG_DM  ( 2909): [com.wssyncmldm.DMSecBroadcastReceiver(192/onReceive)] sec.fota.polling.intent.RECEIVE
,I/DBG_DM  ( 2909): [com.wssyncmldm.DMSecBroadcastReceiver(543/llIIIIlllllIIllIIllI)] nMode : 0
,D/AndroidHttpClient( 6047): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Android-GmailProvider/52000999 (sw360dp; 320dpi) (a5ulte LRX22G); gzip
,D/AndroidHttpClient( 6047): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = POST
,I/DBG_DM  ( 2909): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/System.out( 6047): Thread-1024(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6047): Thread-1024(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6047): Thread-1024(ApacheHTTPLog):isShipBuild true
I/System.out( 6047): Thread-1024(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6047): Thread-1024(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10101
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10101
,I/qtaguid ( 6047): Tagging socket 59 with tag 1010000000000000{269484032,0} for uid -1, pid: 6047, getuid(): 10101
,I/DBG_DM  ( 2909): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 8
,D/TimaKeyStoreProvider( 6430): TimaSignature is unavailable
,D/ActivityThread( 6430): Added TimaKeyStore provider
,I/ActivityManager( 1014): Killing 5728:com.sec.android.soagent/u0a34 (adj 15): empty #31
,I/DBG_DM  ( 2909): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 2909): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(226/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 2909): [com.wssyncmldm.db.file.XDB(3800/IllIIlllIllIIIIIllII)] Wifi_Only_flag : true
,W/ResourcesManager( 6430): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/qtaguid ( 6047): Tagging socket 63 with tag 1010000000000000{269484032,0} for uid -1, pid: 6047, getuid(): 10101
,I/DBG_DM  ( 2909): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 2909): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(251/llIIIIlllllIIllIIllI)] bWifiOnly flag : true
,I/DBG_DM  ( 2909): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 2909): [llIIIllllIIIlIIIlIIl(1846/llIlIIIIlIIIIIlIlIII)] flag is : false
,I/DBG_DM  ( 2909): [IIllIIIIlIlIlIlIllII(1756/lllllIIlIIIlIlIIIllI)] bUpdateProcessing : false
,I/DBG_DM  ( 2909): [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 2909): [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,I/splitIntent( 1014): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1014): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1014): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1014): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/libprocessgroup( 1014): failed to open /acct/uid_10034/pid_5728/cgroup.procs: No such file or directory
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 2909): [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:308289685
,I/DBG_DM  ( 2909): [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/WearableService( 1776): callingUid 10012, callindPid: 1776
,I/OMACP   ( 6430): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,I/DBG_DM  ( 2909): [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 2909): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,D/LocationInitializer( 1970): Restart initialization of location
,D/Mms/Omacp( 6230): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1776): Tagging socket 78 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1776, getuid(): 10012
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Babel   ( 5829): Destroying RTCS
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1776): [217] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1776): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,I/DBG_DM  ( 2909): [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/DBG_DM  ( 2909): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 678432842
,I/DBG_DM  ( 2909): [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/OMACP   ( 6430): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 6430): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 6430): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,I/OMACP   ( 6430): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/OMACP   ( 6430): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 6430): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 6430): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 6430): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 6430): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 6430): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 6430): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 6430): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 6430): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
I/DBG_DM  ( 2909): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 2909): [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 2909): [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false,
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 2909): [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
I/DBG_DM  ( 2909): [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
,E/DBG_DM  ( 2909): [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/DBG_DM  ( 2909): [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@69ad693
,I/DBG_DM  ( 2909): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/GCoreFlp( 1776): No location to return for getLastLocation()
,W/FusedLocationProvider( 1776): location=null
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 2909): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/DBG_DM  ( 2909): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/DBG_DM  ( 2909): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0,
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START,
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main,
,D/ApplicationPolicy( 1014): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,I/GAV4    ( 5937): Thread[GAThread,5,main]: No campaign data found.
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
I/DBG_DM  ( 2909): [com.wssyncmldm.ui.XUIFotaPostponeActivity(337/llIIIIlllllIIllIIllI)] 
,W/NotificationService( 1014): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
,I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,I/DBG_DM  ( 2909): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/DBG_DM  ( 2909): [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 8
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/DBG_DM  ( 2909): [com.wssyncmldm.ui.XUIFotaPostponeActivity(386/llIIIIlllllIIllIIllI)] No idle Postpone
,I/DBG_DM  ( 2909): [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,D/SecContentProvider2( 1014): uri = 15 selection = getToastEnabledState
D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 15 selection = getToastShowPackageNameState
D/SecContentProvider2( 1014): mCursor = null
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false,
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,E/SMD     (  287): DCD OFF
,I/SurfaceFlinger(  257): id=15 createSurf (1x1),1 flag=4, Uoast
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,D/PowerManagerService( 1014): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/SRIB_DCS( 2909): log_dcs ThreadedRenderer::initialize entered! 
,I/Babel   ( 5829): Creating RTCS
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1014): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1014): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 5829): Destroying RTCS,
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.appcert.AppCertService; callingUser = 0; userId(target) = 0
,E/GmsUtils( 5697): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 5697): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/MusicLeanback( 5697): Conditions not met for autocaching.
,I/MusicLeanback( 5697): Stop autocaching.
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1970): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1970): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1970): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1970): (HTTPLog)-Thread-219-1055997238: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1970): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/dex2oat ( 6469): ----------------------------------------------------
I/dex2oat ( 6469): <SS>: S T A R T I N G . . .
I/dex2oat ( 6469): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 6469): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/System.out( 1970): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1970): Tagging socket 114 with tag 1000150000000000{268440832,0} for uid 10012, pid: 1970, getuid(): 10012
,I/qtaguid ( 1970): Tagging socket 117 with tag 1000150000000000{268440832,0} for uid 10012, pid: 1970, getuid(): 10012
,I/dex2oat ( 6469): dex2oat took 53.050ms (threads: 4)
,I/Adreno-EGL( 6327): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6327): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6327): Build Date: 04/06/15 Mon,
I/Adreno-EGL( 6327): Local Branch: 
I/Adreno-EGL( 6327): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6327): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6327):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/System.out( 1970): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1970): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1970): Tagging socket 118 with tag 1000010400000000{268435716,0} for uid -1, pid: 1970, getuid(): 10012
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 5829): Creating RTCS
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Babel   ( 5829): Destroying RTCS
,I/qtaguid ( 1970): Untagging socket 114
,I/Adreno-EGL( 6327): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6327): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6327): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6327): Local Branch: 
I/Adreno-EGL( 6327): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6327): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6327):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/qtaguid ( 1970): Untagging socket 118
,I/Adreno-EGL( 6327): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6327): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6327): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6327): Local Branch: 
I/Adreno-EGL( 6327): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6327): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6327):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.appcert.AppCertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1970): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1970): Tagging socket 114 with tag 1000190000000000{268441856,0} for uid 10012, pid: 1970, getuid(): 10012
,I/qtaguid ( 6047): Untagging socket 59
,I/System.out( 6047): SyncAdapterThread-1 calls detatch()
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WVMDrmPlugIn(  281): WVMDrmPlugin::onInitialize : 1006
,D/WVMDrmPlugIn(  281): WVMDrmPlugin::onSetOnInfoListener : add 1006
,D/WVMDrmPlugIn(  281): WVMDrmPlugin::onGetSupportInfo : 0
,I/WVCdm   (  282): CdmEngine::OpenSession
,I/WVCdm   (  282): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  282): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  282): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
,D/DrmWidevineDash(  282): Service_Initialize: starts!
D/QSEECOMAPI: (  282): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  282): App is not loaded in QSEE
,E/QSEECOMAPI: (  282): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  282): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  282): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  282): App is not loaded in QSEE
E/QSEECOMAPI: (  282): Error::Cannot open the file /system/etc/firmware/widevine.mdt
,E/QSEECOMAPI: (  282): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  282): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  282): App is not loaded in QSEE
,I/qtaguid ( 1970): Untagging socket 114
,D/QSEECOMAPI: (  282): Loaded image: APP id = 12
,D/DrmWidevineDash(  282): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  282): qsapps_get_capabilities: Capability from secure side: 0x0
D/QSAPPSVER(  282): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  282): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb16d0000
E/DrmWidevineDash(  282): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb16d0000
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  422): got the req here! ret=0
D/DrmLibTime(  422): command id, time_cmd_id = 770
D/DrmLibTime(  422): time_getutcsec starts!
D/DrmLibTime(  422): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  422): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  422): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  422): QSEE Time Listener: Checking if ATS_MODEM is set or not.
D/QC-time-services(  422): Lib:time_genoff_operation: pargs->base = 13
D/QC-time-services(  422): Lib:time_genoff_operation: pargs->operation = 2
D/QC-time-services(  422): Lib:time_genoff_operation: pargs->ts_val = 0
D/QC-time-services(  422): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  324): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  324): Daemon:Received base = 13, unit = 1, operation = 2,value = 0
D/QC-time-services(  324): Daemon:genoff_opr: Base = 13, val = 0, operation = 2
D/QC-time-services(  324): offset is: 0 for base: 0,
E/QC-time-services(  422): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  422): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  422): QSEE Time Listener: Retrieved Android system time: 1451923442
D/DrmLibTime(  422): time_getutcsec returns 0, sec = 1451923442; nsec = 0
,D/DrmLibTime(  422): time_getutcsec finished! 
D/DrmLibTime(  422): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  422): before calling ioctl to read the next time_cmd
,D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,E/QC-time-services(  324): Daemon: Time-services: Waiting to acceptconnection
,D/DrmWidevineDash(  282): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  282): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  282): hlos api version =  9
D/DrmWidevineDash(  282): tz api version =  9
D/DrmWidevineDash(  282): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  282): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  282): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  282): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  282): OEMCrypto_OpenSession: starts! SID=0xbeb971b0
D/DrmWidevineDash(  282): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  282): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  282): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  282): OEMCrypto_GetRandom: starts! randomData=0xb85dc240, dataLength=8
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  282): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  282): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb85b81a0, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  282): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  282): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  282): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  282): OEMCrypto_GetDeviceID: starts! deviceID=0xb85b43a0, idLength=0xb18f2730
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/Babel   ( 5829): Creating RTCS
,D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  282): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  282): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  282): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  282): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  282): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  282): OEMCrypto_GetHDCPCapability: starts!, current = 0xb18f2746, maximum = 0xb18f2747
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  282): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  282): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  282): hlos api version =  9
D/DrmWidevineDash(  282): tz api version =  9
D/DrmWidevineDash(  282): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  282): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xb18f27b4
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  282): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  282): PrepareKeyRequest: nonce=1886307543
D/DrmWidevineDash(  282): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb85bca20
D/DrmWidevineDash(  282): message_length=1634, signature=0xb85b7b00, signature_length=0xb18f2714
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Babel   ( 5829): Destroying RTCS
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.appcert.AppCertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1970): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1970): Tagging socket 114 with tag 1000150000000000{268440832,0} for uid 10012, pid: 1970, getuid(): 10012
,D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  282): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  282): CdmEngine::CloseSession
D/DrmWidevineDash(  282): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  282): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  282): L3 Terminate.
D/DrmWidevineDash(  282): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  282): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  282): Service_Uninitialize: starts!
D/QSEECOMAPI: (  282): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  282): QSEECom_shutdown_app, app_id = 12
,D/DrmWidevineDash(  282): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  282): OEMCrypto_Terminate: ends! returns 0
,I/qtaguid ( 1970): Untagging socket 114
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.android.mail.widget.BaseGmailWidgetProviderService; callingUser = 0; userId(target) = 0
,E/Volley  ( 1970): [220] BasicNetwork.performRequest: Unexpected response code 410 for https://www.googleapis.com/plus/v2whitelisted/people/me/people/all?prettyPrint=false&fields=items(etag,id,names,nicknames,images,urls,sortKeys,taglines,emails,phoneNumbers,addresses,metadata,memberships,legacyFields/mobileOwnerId),nextPageToken,nextSyncToken&customResponseMaskingType=menagerie&includeAffinity=gplusAutocomplete&includeAffinity=chatAutocomplete&includeAffinity=emailAutocomplete&includeOthers=true&maxResults=100&orderBy=modified&syncToken=CKPFnqOeKhIBMRjeEioECAEQAQ
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/PeopleSync( 1970): Sync Token out of date, syncing all people/gaia-map
,I/art     ( 6047): Explicit concurrent mark sweep GC freed 5068(203KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 10MB/13MB, paused 967us total 34.268ms
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.appcert.AppCertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 6047): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 13916, normalSync: true
,I/Gmail   ( 6047): lowestBackward conversation id 0,
,I/System.out( 1970): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1970): Tagging socket 114 with tag 1000150000000000{268440832,0} for uid 10012, pid: 1970, getuid(): 10012
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,F/Babel   ( 5829): wtf
F/Babel   ( 5829): Invalid server experiment type 3 for BabelExperiment{id='dd8c17d9', experimentType=0, defaultBoolean=null, defaultLong=null}
,F/Babel   ( 5829): Invalid server experiment type 3 for BabelExperiment{id='dd8c17d9', experimentType=0, defaultBoolean=null, defaultLong=null}
F/Babel   ( 5829): java.lang.Exception
F/Babel   ( 5829): 	at cvu.h(SourceFile:274)
F/Babel   ( 5829): 	at bri.<init>(SourceFile:95)
F/Babel   ( 5829): 	at bwx.<init>(SourceFile:1866)
F/Babel   ( 5829): 	at bwx.parseFrom(SourceFile:2021)
F/Babel   ( 5829): 	at java.lang.reflect.Method.invoke(Native Method)
F/Babel   ( 5829): 	at java.lang.reflect.Method.invoke(Method.java:372)
F/Babel   ( 5829): 	at bzp.a(SourceFile:372)
F/Babel   ( 5829): 	at bzp.a(SourceFile:117)
F/Babel   ( 5829): 	at bui.a(SourceFile:626)
F/Babel   ( 5829): 	at bui.a(SourceFile:491)
F/Babel   ( 5829): 	at bfq.a(SourceFile:39)
F/Babel   ( 5829): 	at bfr.run(SourceFile:88)
,F/Babel   ( 5829): wtf
F/Babel   ( 5829): Invalid server experiment type 3 for BabelExperiment{id='6412be77', experimentType=0, defaultBoolean=null, defaultLong=null}
,F/Babel   ( 5829): Invalid server experiment type 3 for BabelExperiment{id='6412be77', experimentType=0, defaultBoolean=null, defaultLong=null}
F/Babel   ( 5829): java.lang.Exception
F/Babel   ( 5829): 	at cvu.h(SourceFile:274)
F/Babel   ( 5829): 	at bri.<init>(SourceFile:95)
F/Babel   ( 5829): 	at bwx.<init>(SourceFile:1866)
F/Babel   ( 5829): 	at bwx.parseFrom(SourceFile:2021)
F/Babel   ( 5829): 	at java.lang.reflect.Method.invoke(Native Method)
F/Babel   ( 5829): 	at java.lang.reflect.Method.invoke(Method.java:372)
F/Babel   ( 5829): 	at bzp.a(SourceFile:372)
F/Babel   ( 5829): 	at bzp.a(SourceFile:117)
F/Babel   ( 5829): 	at bui.a(SourceFile:626)
F/Babel   ( 5829): 	at bui.a(SourceFile:491)
F/Babel   ( 5829): 	at bfq.a(SourceFile:39)
F/Babel   ( 5829): 	at bfr.run(SourceFile:88)
,I/qtaguid ( 1970): Untagging socket 114
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 5829): Creating RTCS
,I/art     ( 5829): Note: end time exceeds epoch: 
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 6047): Thread[GAThread,5,main]: No campaign data found.
,D/SSRM:n  ( 1014): SIOP:: AP = 340
,I/Babel   ( 5829): Account selfinfo retrieved: Redacted-21
I/Babel   ( 5829): Retrieved account setting:Redacted-21
,I/Babel   ( 5829): Account sign in complete with state 102account: Redacted-21
,I/PeopleSync( 1970): Sync finished, successful=true, took 1730ms
,I/PeopleContactsSync( 1970): CP2 sync start [5005f081]
,I/PeopleContactsSync( 1970): CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/PeopleContactsSync( 1970): Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 31037(1707KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 3.238ms total 162.363ms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 6047): notifyAccountChanged
,I/Gmail   ( 6047): getAccountsCursor
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/Gmail   ( 6047): notifyAccountChanged
,I/ActivityManager( 1014): Killing 5762:com.android.chrome/u0a81 (adj 15): empty #31
,W/Gmail   ( 6047): Sync complete for account: account:61035162
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Mms/MmsApp( 6230):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 6230): [start]    fillCache consume time = 1965.518333
D/Mms/ComposeMessageFragment( 6230): fillCache, easy = false
,I/Gmail   ( 6047): getAccountsCursor
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PeopleContactsSync( 1970): CP2 cleanup done, kept= duration=109 ms
,I/PeopleContactsSync( 1970): ===CP2 sync finished, success=true, time=129,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
,I/PeopleSync( 1970): ***Sync finished***, duration: 3610 [5005f081]
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1970): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1970): Module APK com.google.android.play.games already loaded
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
,D/AbsListView( 6230): Get MotionRecognitionManager
,I/art     ( 1970): Explicit concurrent mark sweep GC freed 39708(2MB) AllocSpace objects, 22(784KB) LOS objects, 40% free, 14MB/24MB, paused 1.819ms total 95.653ms
,D/MotionRecognitionService( 1014):  ssp status : false
,W/libprocessgroup( 1014): failed to open /acct/uid_10081/pid_5762/cgroup.procs: No such file or directory
,W/PlaySystemBroadcastReceiver( 1970): Processed handlePeopleChanged at 93070
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/Mms/ComposeMessageFragment( 6230): [end]    fillCache consume time = 111.240677
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/SQLiteConnectionPool( 1970): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/ChimeraCfgMgr( 1970): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1970): Module APK com.google.android.play.games already loaded
,W/DataBroker( 1970): No player ID found and calling context is not the dest app
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.syncadapters.calendar, action: android.content.SyncAdapter
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.syncadapters.calendar/com.google.android.syncadapters.calendar.CalendarSyncAdapterService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6503): MountEmulatedStorage(),
I/libpersona( 6503): KNOX_SDCARD checking this for 10102
E/Zygote  ( 6503): v2
I/libpersona( 6503): KNOX_SDCARD not a persona
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
I/ActivityManager( 1014): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=6503 uid=10102 gids={50102, 9997, 3003} abi=armeabi-v7a
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.PeopleRequestProcessor; callingUser = 0; userId(target) = 0
,I/SELinux ( 6503): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6503): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6503): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Killing 4967:com.android.defcontainer/u0a4 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6503): TimaSignature is unavailable
,D/ActivityThread( 6503): Added TimaKeyStore provider
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/BubbleViewCache( 6230): fillCache bubble = 1
,W/libprocessgroup( 1014): failed to open /acct/uid_10004/pid_4967/cgroup.procs: No such file or directory
,I/Babel   ( 5829): Destroying RTCS
,E/SQLiteLog( 1970): (284) automatic index on invitations(external_inviter_id)
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.EsSyncAdapterService; callingUser = 0; userId(target) = 0
,W/AbstractGoogleClient( 6503): Application name is not set. Call Builder#setApplicationName.
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.syncadapters.calendar, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.syncadapters.calendar, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1776): Tagging socket 94 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1776, getuid(): 10012
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1776): Tagging socket 97 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1776, getuid(): 10012
,I/CheckinRequestBuilder( 1970): Classify the device as Phone.
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Icing   ( 1970): Indexing CCCF2610294B0D8C53498F9681259C2D89058ED7 from com.google.android.gm
,I/System.out( 1970): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1970): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1970): Tagging socket 103 with tag 1000040800000000{268436488,0} for uid -1, pid: 1970, getuid(): 10012
,I/Gmail   ( 6047): Backfilling search sequence table
,I/qtaguid ( 1970): Tagging socket 123 with tag 1000040800000000{268436488,0} for uid -1, pid: 1970, getuid(): 10012
,I/Icing   ( 1970): Indexing done CCCF2610294B0D8C53498F9681259C2D89058ED7
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/dhcpcd  ( 5655): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 5655): wlan0: no IPv6 Routers available
,I/CheckinTask( 1970): Sending checkin request (10896 bytes)
,W/art     ( 4805): Attempt to remove local handle scope entry from IRT, ignoring
,I/System.out( 6503): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 6503): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6503): (HTTPLog)-Static: isShipBuild true
I/System.out( 6503): (HTTPLog)-Thread-1091-611380069: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6503): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10102
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10102
,I/System.out( 6503): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 6503): Tagging socket 28 with tag 1100000000000000{285212672,0} for uid -1, pid: 6503, getuid(): 10102
,D/EnterpriseController(  277): uids 10120
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10120
,I/qtaguid ( 6503): Untagging socket 28
,D/CalendarSyncAdapter( 6503): Found 0 events marked dirty & lastSynced
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.subscribedfeeds.SyncService; callingUser = 0; userId(target) = 0
,I/qtaguid ( 1970): Untagging socket 103
,I/CheckinRequestBuilder( 1970): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1970): Failed to find provider info for com.google.android.wearable.settings
,I/GoogleURLConnFactory( 1970): Using platform SSLCertificateSocketFactory
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 1970): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1970): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1970): Tagging socket 124 with tag 1000210100000000{268443905,0} for uid -1, pid: 1970, getuid(): 10012
,I/qtaguid ( 1970): Tagging socket 128 with tag 1000210100000000{268443905,0} for uid -1, pid: 1970, getuid(): 10012
,I/art     ( 1633): Explicit concurrent mark sweep GC freed 3117(128KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 840us total 24.131ms
,I/CheckinRequestBuilder( 1970): Classify the device as Phone.
,I/CheckinTask( 1970): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1970): Checking schedule, now: 1451923444835 next: 1452462707815
,I/CheckinService( 1970): active receiver: disabled
,D/CheckinService( 1970): Recording last checkin time for package unspecified as 1451923444850
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.process.gapps
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1776): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5116): execute::IDLE:EXECUTE
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PreloadUpdateManagerStateMachine( 5116): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5116): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5116): AutoUpdateTriggerManager:REQUEST2:requestInterval
,D/hcjo    ( 5116): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,D/hcjo    ( 5116): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,D/PreloadUpdateManagerStateMachine( 5116): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5116): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 5116): entry::REQ_UPDATE_CHECK
,E/SMD     (  287): DCD OFF
,I/Volley  ( 5116): RestApi Request Add : 2315
,I/System.out( 5116): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 5116): Tagging socket -1 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 5116, getuid(): 10010
,I/qtaguid ( 5116): Failed write_ctrl(t -1 8764893202948816896 -1) res=-1 errno=9
,I/qtaguid ( 5116): Tagging socket -1 with tag 79a327ee00000000(2040735726) for uid -1 failed errno=-9
I/NetworkManagementSocketTagger( 5116): tagSocketFd(-1, 2040735726, -1) failed with errno-9
,I/qtaguid ( 5116): Tagging socket 31 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 5116, getuid(): 10010
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.ReportingSyncService; callingUser = 0; userId(target) = 0
,I/GCoreUlr( 1776): Uploading GCM registration ID for account#2#
,W/BaseAppContext( 1776): Using Auth Proxy for data requests.
,I/qtaguid ( 5116): Untagging socket -1
,I/qtaguid ( 5116): Failed write_ctrl(u -1) res=-1 errno=9
I/qtaguid ( 5116): Untagging socket -1 failed errno=-9
W/NetworkManagementSocketTagger( 5116): untagSocket(-1) failed with errno -9
,E/BaseAppContext( 1776): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,D/PreloadUpdateManagerStateMachine( 5116): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
D/PreloadUpdateManagerStateMachine( 5116): exit::REQ_UPDATE_CHECK
D/PreloadUpdateManagerStateMachine( 5116): entry::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 5116): exit::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 5116): entry::FINISH
,D/PreloadUpdateManagerStateMachine( 5116): exit::FINISH
D/PreloadUpdateManagerStateMachine( 5116): entry::IDLE
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1776): Tagging socket 90 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1776, getuid(): 10012
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.appcert.AppCertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1776): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1776): Tagging socket 86 with tag 1000060200000000{268436994,0} for uid 10012, pid: 1776, getuid(): 10012
,I/qtaguid ( 1776): Tagging socket 89 with tag 1000060200000000{268436994,0} for uid 10012, pid: 1776, getuid(): 10012
,I/SurfaceFlinger(  257): id=15 Removed Uoast (8/9)
D/PowerManagerService( 1014): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1014) eventTime = 95199
I/SurfaceFlinger(  257): id=15 Removed Uoast (-2/9)
D/PowerManagerService( 1014): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014 (0x0)
D/PowerManagerService( 1014): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1014, ws=WorkSource{1000}) (elapsedTime=3476)
,I/qtaguid ( 1970): Untagging socket 124
,I/qtaguid ( 1776): Untagging socket 86
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncService; callingUser = 0; userId(target) = 0
,I/GCoreUlr( 1776): GCM ID uploaded for account#2#
,I/ActivityManager( 1014): Killing 5748:com.google.android.youtube/u0a166 (adj 15): empty #31
,I/GCoreUlr( 1776): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1776): DispatchingService.onCreate()
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/GCoreUlr( 1776): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1776): Unbound from all location providers
,I/GCoreUlr( 1776): Place inference reporting - stopped
,I/GCoreUlr( 1776): DispatchingService.onDestroy()
I/GCoreUlr( 1776): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1776): Unbound from all location providers
,I/GCoreUlr( 1776): Place inference reporting - stopped
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.apps.docs, action: android.content.SyncAdapter
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1014): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=6560 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
E/Zygote  ( 6560): MountEmulatedStorage(),
E/Zygote  ( 6560): v2
I/libpersona( 6560): KNOX_SDCARD checking this for 10091
I/libpersona( 6560): KNOX_SDCARD not a persona
,I/SELinux ( 6560): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.apps.magazines, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.service.SyncAdapterService; callingUser = 0; userId(target) = 0
,I/SELinux ( 6560): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6560): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1014): failed to open /acct/uid_10166/pid_5748/cgroup.procs: No such file or directory,
,I/SyncAdapterService( 5937): Ignoring sync request for non-current account
,D/TimaKeyStoreProvider( 6560): TimaSignature is unavailable
,D/ActivityThread( 6560): Added TimaKeyStore provider
,E/PhotosPlugin( 6560): Loading PhotosPlugin
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.syncadapters.contacts, action: android.content.SyncAdapter
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterService; callingUser = 0; userId(target) = 0
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 42584(1867KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 2.672ms total 150.080ms
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AndroidHttpClient( 1633): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Android-GData-Contacts/1.3 (a5ulte LRX22G); gzip
,D/AndroidHttpClient( 1633): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/System.out( 1633): Thread-142(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 1633): Thread-142(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 1633): Thread-142(ApacheHTTPLog):isShipBuild true
I/System.out( 1633): Thread-142(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 1633): Thread-142(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/qtaguid ( 1633): Tagging socket 36 with tag 1244000400000000{306446340,0} for uid -1, pid: 1633, getuid(): 10012
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/HeadsetService( 5438): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5438): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/qtaguid ( 1633): Tagging socket 41 with tag 1244000400000000{306446340,0} for uid -1, pid: 1633, getuid(): 10012
,W/GAV2    ( 6560): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
,W/GAV2    ( 6560): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/qtaguid ( 1633): Untagging socket 36
,I/System.out( 1633): GDataFeedFetcher calls detatch()
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/Mms/Contact( 6230): performUpdate:widgetCount=0
D/Mms/Contact( 6230): sContactsObserver.onChange(),selfUpdate=false
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Mms/ContactsCache( 6230): [start]    invalidate() consume time = 3428.111457
D/Mms/ContactsCache( 6230): [end]    invalidate() consume time = 0.168593
,D/AndroidHttpClient( 1633): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Android-GData-Contacts/1.3 (a5ulte LRX22G); gzip
,D/AndroidHttpClient( 1633): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,I/System.out( 1633): Thread-144(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 1633): Thread-144(ApacheHTTPLog):isShipBuild true
I/System.out( 1633): Thread-144(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 1633): Thread-144(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/qtaguid ( 1633): Tagging socket 36 with tag 1144000400000000{289669124,0} for uid -1, pid: 1633, getuid(): 10012
,D/ContactProvider( 5810): getAllContactInfoList Start
,W/AccountFeatureHelper( 6560): Write apps_features disabled false
,D/ContactProvider( 5810): getAllContactInfoList End
,I/syncContacts( 5810): thread: 994, onChange
,W/Flag    ( 6560): Duration spec must be at least 2 characters long
,I/System.out( 6560): Thread-1120(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6560): Thread-1120(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 6560): Thread-1120(ApacheHTTPLog):isShipBuild true
I/System.out( 6560): Thread-1120(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 6560): Thread-1120(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10091
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10091
,I/qtaguid ( 1633): Untagging socket 36
,I/System.out( 1633): GDataFeedFetcher calls detatch()
,D/Mms/Contact( 6230): sContactsObserver.onChange(),selfUpdate=false
,D/Mms/ContactsCache( 6230): [start]    invalidate() consume time = 149.792032
,D/Mms/ContactsCache( 6230): [end]    invalidate() consume time = 0.827135
,D/ContactProvider( 5810): getAllContactInfoList Start
,E/SQLiteLog( 1684): (284) automatic index on sqlite_sq_B8585E30(STAT_DATA_ID)
,E/SQLiteLog( 1684): (284) automatic index on sqlite_sq_B8581250(STAT_DATA_ID)
,D/ContactProvider( 5810): getAllContactInfoList End
,I/syncContacts( 5810): thread: 995, onChange
,E/SQLiteLog( 1684): (284) automatic index on sqlite_sq_B858A978(STAT_DATA_ID)
,E/SQLiteLog( 1684): (284) automatic index on sqlite_sq_B836A908(STAT_DATA_ID)
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.CredentialStateSyncService; callingUser = 0; userId(target) = 0
,I/System.out( 6560): BaseSyncManager calls detatch()
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1776): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1776): Tagging socket 55 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1776, getuid(): 10012
,I/qtaguid ( 1776): Tagging socket 83 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1776, getuid(): 10012
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1776): Tagging socket 78 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1776, getuid(): 10012
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.plus.service.OfflineActionSyncAdapterService; callingUser = 0; userId(target) = 0
,W/BaseAppContext( 1970): Using Auth Proxy for data requests.
,W/BaseAppContext( 1970): Using Auth Proxy for data requests.
,W/BaseAppContext( 1970): Using Auth Proxy for data requests.
,W/BaseAppContext( 1970): Using Auth Proxy for data requests.
,W/BaseAppContext( 1970): Using Auth Proxy for data requests.
,W/BaseAppContext( 1970): Using Auth Proxy for data requests.
,W/BaseAppContext( 1970): Using Auth Proxy for data requests.
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.music, action: android.content.SyncAdapter,
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.sync.SyncAdapterService; callingUser = 0; userId(target) = 0
,I/System.out( 6560): Thread-1120(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 6560): Thread-1120(ApacheHTTPLog):isShipBuild true
I/System.out( 6560): Thread-1120(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 6560): Thread-1120(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10091
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10091
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 5697): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5697): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 5697): Using the GMSCore's GoogleHttpClient
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5697): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5697): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5697): (HTTPLog)-Static: isShipBuild true
I/System.out( 5697): (HTTPLog)-Thread-981-22706756: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5697): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10111
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10111
,I/System.out( 5697): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,E/SMD     (  287): DCD OFF,
,I/System.out( 6560): BaseSyncManager calls detatch()
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5697): (HTTPLog)-Static: isSBSettingEnabled false
,I/ActivityManager( 1014): Killing 5972:com.sec.android.cloudagent/u0a2 (adj 15): empty #31
,W/GAV2    ( 6560): BaseSyncManager-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,W/MusicApiClient( 5697): No content in 'data' field in GET sync response for Track
,I/MusicSyncAdapter( 5697): Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
I/MusicSyncAdapter( 5697): Periodic update
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6635): MountEmulatedStorage()
,E/Zygote  ( 6635): v2
I/libpersona( 6635): KNOX_SDCARD checking this for 10028
I/libpersona( 6635): KNOX_SDCARD not a persona
,I/SELinux ( 6635): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.ConsumptionAppDataChangedReceiver: pid=6635 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6635): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6635): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6635): TimaSignature is unavailable
,D/ActivityThread( 6635): Added TimaKeyStore provider
,I/ActivityManager( 1014): Killing 6027:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1014): failed to open /acct/uid_10002/pid_5972/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.libraries.social.autobackup.AutoBackupSyncService; callingUser = 0; userId(target) = 0
,D/Finsky  ( 6635): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_6027/cgroup.procs: No such file or directory
,I/art     ( 1633): Explicit concurrent mark sweep GC freed 19740(956KB) AllocSpace objects, 3(71KB) LOS objects, 25% free, 7MB/10MB, paused 774us total 37.724ms
,E/Auth.Api.Credentials( 1970): [CredentialSyncAdapter] Unknown sync event.
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.photos.service.GooglePhotoDownsyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.sync.RemindersSyncService; callingUser = 0; userId(target) = 0
,D/Finsky  ( 6635): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 6635): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6635): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.syncadapters.calendar, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.syncadapters.calendar/com.google.android.syncadapters.calendar.CalendarSyncAdapterService; callingUser = 0; userId(target) = 0
,I/System.out( 6635): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 6635): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6635): (HTTPLog)-Static: isShipBuild true
,I/System.out( 6635): (HTTPLog)-Thread-1119-884925123: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6635): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10028
,I/System.out( 6635): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 29990(1347KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 2.608ms total 143.316ms
,I/RemindersSync( 1970): Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=328:priority=5:group=main]
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.store.KeepOnUpdater$SyncListener; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/Finsky  ( 6635): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Ads     ( 6635): Skipping gmscore version check
,D/Finsky  ( 6635): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 6635): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ContextImpl( 5697): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/ActivityManager( 1014): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,E/File    ( 5697): fail readDirectory() errno=2
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,D/Mms/Contact( 6230): performUpdate:widgetCount=0
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ContextImpl( 5697): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/Finsky  ( 6635): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.keepon.KeeponSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 5697): Conditions not met for autocaching.
I/MusicLeanback( 5697): Stop autocaching.
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1776): callingUid 10012, callindPid: 1776
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5697): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,E/GmsUtils( 5697): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 5697): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.syncadapters.calendar, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.syncadapters.calendar, destAppInfo.processName = com.google.android.gms
,I/System.out( 6503): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 6503): Tagging socket 28 with tag 1000000400000000{268435460,0} for uid -1, pid: 6503, getuid(): 10102
,I/qtaguid ( 6503): Tagging socket 32 with tag 1000000400000000{268435460,0} for uid -1, pid: 6503, getuid(): 10102
,V/CalendarSyncAdapter( 6503): Saving inProgress state: {calendarId=thalitester@gmail.com, maxAttendees=50, maxResults=200, timeMax=2017-01-24T00:00:00.000Z, updatedMin=2015-11-18T16:31:02.459Z}
,I/qtaguid ( 6503): Untagging socket 28
,D/CalendarSyncAdapter( 6503): Found 0 events marked dirty & lastSynced
,I/ActivityManager( 1014): Killing 5139:com.sec.spp.push/u0a35 (adj 15): empty #31
,I/ActivityManager( 1014): Killing 5810:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,W/libprocessgroup( 1014): failed to open /acct/uid_10035/pid_5139/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10044/pid_5810/cgroup.procs: No such file or directory
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/Finsky  ( 6635): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 6635): Thread-1108(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6635): Thread-1108(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6635): Thread-1108(ApacheHTTPLog):isShipBuild true
I/System.out( 6635): Thread-1108(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6635): Thread-1108(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10028
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10028
,I/qtaguid ( 6635): Tagging socket 47 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 6635, getuid(): 10028
,I/qtaguid ( 6635): Tagging socket 51 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 6635, getuid(): 10028
,I/qtaguid ( 6635): Untagging socket 47
I/System.out( 6635): Thread-1108 calls detatch()
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 6635): Thread-1107(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 6635): Thread-1107(ApacheHTTPLog):isShipBuild true
,I/System.out( 6635): Thread-1107(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6635): Thread-1107(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 6635): Untagging socket 47
,I/qtaguid ( 6635): Failed write_ctrl(u 47) res=-1 errno=22
I/qtaguid ( 6635): Untagging socket 47 failed errno=-22
W/NetworkManagementSocketTagger( 6635): untagSocket(47) failed with errno -22
I/System.out( 6635): Thread-1107 calls detatch()
,D/Finsky  ( 6635): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6700): MountEmulatedStorage()
E/Zygote  ( 6700): v2
I/libpersona( 6700): KNOX_SDCARD checking this for 10012
I/libpersona( 6700): KNOX_SDCARD not a persona
,I/SELinux ( 6700): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6700 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
I/SELinux ( 6700): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6700): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  314): Explicit concurrent mark sweep GC freed 8685(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 917us total 26.840ms
,D/TimaKeyStoreProvider( 6700): TimaSignature is unavailable
D/ActivityThread( 6700): Added TimaKeyStore provider
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 603us total 17.539ms
,I/System.out( 6635): Thread-1108(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 6635): Thread-1108(ApacheHTTPLog):isShipBuild true
,I/System.out( 6635): Thread-1108(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6635): Thread-1108(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/ResourcesManager( 6700): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6700): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 717us total 18.174ms
,I/MultiDex( 6700): VM with version 2.1.0 has multidex support
,I/MultiDex( 6700): install
I/MultiDex( 6700): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6700): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/qtaguid ( 6635): Untagging socket 47
,I/qtaguid ( 6635): Failed write_ctrl(u 47) res=-1 errno=22
,I/qtaguid ( 6635): Untagging socket 47 failed errno=-22
W/NetworkManagementSocketTagger( 6635): untagSocket(47) failed with errno -22
I/System.out( 6635): Thread-1108 calls detatch()
,W/ActivityThread( 6700): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6700): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@17f02e15: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6700): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1014): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1014): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1014): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1014): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 6700): Reading stored module config
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1776): [235] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1970): Restart initialization of location
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1776): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 6700): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/NativeLibraryUtils( 6700): Install completed successfully. count=14 extracted=0
,W/GCoreFlp( 1776): No location to return for getLastLocation(),
W/FusedLocationProvider( 1776): location=null
,D/CAR.SERVICE( 6700): Connecting to CarCallService...
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.CarCallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 6700): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6700): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 6700): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6700): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6700): Creating a new PhoneAdapter instance
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6700): setListener: com.google.android.gms.car.dn@582fe8
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found,
,D/CAR.TEL.PhoneAdapter( 6700): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6700): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 6700): Package validated; name: com.android.vending
,V/Finsky  ( 6635): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 6635): Thread-1107(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 6635): Thread-1107(ApacheHTTPLog):isShipBuild true
,I/System.out( 6635): Thread-1107(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 6635): Thread-1107(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/SMD     (  287): DCD OFF
,I/qtaguid ( 6635): Untagging socket 47
,I/qtaguid ( 6635): Failed write_ctrl(u 47) res=-1 errno=22
I/qtaguid ( 6635): Untagging socket 47 failed errno=-22
W/NetworkManagementSocketTagger( 6635): untagSocket(47) failed with errno -22
I/System.out( 6635): Thread-1107 calls detatch()
,D/Finsky  ( 6635): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.google.android.googlequicksearchbox to true
,D/Finsky  ( 6635): [1] MultiWayUpdateController.collateResponses: Change auto-acquire tags for com.google.android.googlequicksearchbox from  to d_AAAAAAADF8w=
,W/ResourcesManager( 6635): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6635): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6635): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ActivityManager( 1014): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 6635): [1] DailyHygiene.access$600: Logging device features
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/DeviceConnectionService( 1776): client connected with version: 8296000
,D/Finsky  ( 6635): [1] VerifyInstalledPackagesReceiver.onReceive: Verify installed apps requested
,D/ActivityManager( 1014): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.vending.verifier.PackageVerificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
D/Finsky  ( 6635): [1131] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6635): [1] VerifyInstalledPackagesTask.onPreExecute: Verifying installed apps
,D/Finsky  ( 6635): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 6635): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/System.out( 6635): (HTTPLog)-Static: isSBSettingEnabled false
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WVMDrmPlugIn(  281): WVMDrmPlugin::onTerminate : 1006
,I/PowerManagerService( 1014): [PWL] Off : 50s ago,
,D/SSRM:n  ( 1014): SIOP:: AP = 310,
,E/SMD     (  287): DCD OFF
,D/PackageManager( 1014): [MSG] SEND_PENDING_BROADCAST
,I/InputReader( 1014): Reconfiguring input devices.  changes=0x00000010
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
,I/PageBuddyNotiSvc( 3999): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6740): MountEmulatedStorage()
E/Zygote  ( 6740): v2
I/libpersona( 6740): KNOX_SDCARD checking this for 1000
I/libpersona( 6740): KNOX_SDCARD not a persona
,I/SELinux ( 6740): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6740): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6740): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=6740 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/RegisteredComponentCache( 1426): Collect Tech packages for Knox
,D/PersonaManager( 1426): isKioskContainerExistOnDevice
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PersonaManager( 1426): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1426): empty dynamic service
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 6740): TimaSignature is unavailable
,D/ActivityThread( 6740): Added TimaKeyStore provider
,D/SecContentProvider2( 1014): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1014): mCursor = null
,D/AASAservice-UpdateReceiver( 6740): AASAUpdateReceiver: android.intent.action.PACKAGE_CHANGED, package = com.google.android.gms, uid = -1
,I/splitIntent( 1014): intent=android.intent.action.PACKAGE_CHANGED will be not split. because same process=com.google.android.googlequicksearchbox:search is in other queue. index=1,
I/splitIntent( 1014): base  index=1, name=com.google.android.googlequicksearchbox com.google.android.search.core.GooglePlayServicesHelper$GmsPackageWatcher
I/splitIntent( 1014): other index=7, name=com.google.android.googlequicksearchbox com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
I/splitIntent( 1014): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_CHANGED !! do not split it!!
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6756): MountEmulatedStorage()
I/ActivityManager( 1014): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GooglePlayServicesHelper$GmsPackageWatcher: pid=6756 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
E/Zygote  ( 6756): v2
I/libpersona( 6756): KNOX_SDCARD checking this for 10057
I/SELinux ( 6756): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 6756): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Killing 5101:com.policydm/1000 (adj 15): empty #31
,I/SELinux ( 6756): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 6756): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6756): TimaSignature is unavailable
,D/ActivityThread( 6756): Added TimaKeyStore provider
,W/ResourceType( 1014): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1014): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1014): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1014): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/IntentResolver( 1014): resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService( 1014): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService( 1014): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService( 1014): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.backup.TRANSPORT_HOST
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.backup.BackupTransportService; callingUser = 0; userId(target) = 0
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/BackupManagerService( 1014): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
V/BackupManagerService( 1014): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3562bd5d
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2,
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5101/cgroup.procs: No such file or directory
D/LocationProviderProxy( 1014): applying state to connected service
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6775): MountEmulatedStorage(),
,E/Zygote  ( 6775): v2
I/libpersona( 6775): KNOX_SDCARD checking this for 10015
I/libpersona( 6775): KNOX_SDCARD not a persona
,I/SELinux ( 6775): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/LocationManagerService( 1014): getProviders()=[passive],
,I/ActivityManager( 1014): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6775 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 6775): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6775): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6775): TimaSignature is unavailable
,D/ActivityThread( 6775): Added TimaKeyStore provider
,I/ActivityManager( 1014): Killing 6128:com.samsung.android.sconnect/u0a125 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 5829): Creating RTCS
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6796): MountEmulatedStorage()
I/libpersona( 6796): KNOX_SDCARD checking this for 10032
E/Zygote  ( 6796): v2
I/libpersona( 6796): KNOX_SDCARD not a persona
,I/SELinux ( 6796): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6796 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 6796): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6796): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Babel   ( 5829): Destroying RTCS
,I/ActivityManager( 1014): Killing 6168:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,I/ActivityManager( 1014): Killing 5515:com.android.email/u0a145 (adj 15): empty #32
,D/TimaKeyStoreProvider( 6796): TimaSignature is unavailable
,D/ActivityThread( 6796): Added TimaKeyStore provider
,I/ActivityManager( 1014): Killing 6105:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,I/FeatureConfig( 6796): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6813): MountEmulatedStorage(),
E/Zygote  ( 6813): v2
I/libpersona( 6813): KNOX_SDCARD checking this for 10044
,I/libpersona( 6813): KNOX_SDCARD not a persona
I/SELinux ( 6813): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6813 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6796): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
I/SELinux ( 6813): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,W/ResourcesManager( 6796): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.,
W/ResourcesManager( 6796): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/SELinux ( 6813): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 6796): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6796): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6813): TimaSignature is unavailable
,D/ActivityThread( 6813): Added TimaKeyStore provider,
,W/ResourcesManager( 6796): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 36276(1965KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/41MB, paused 2.757ms total 159.972ms
,W/ResourcesManager( 6796): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 6813): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6813): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6813): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 6813): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6813): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6813): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6813): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6813): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6796): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6796): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6796): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6796): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6796): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 6796): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6796): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6796): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6796): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1014): failed to open /acct/uid_10125/pid_6128/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10062/pid_6168/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10145/pid_5515/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10009/pid_6105/cgroup.procs: No such file or directory
,W/ResourcesManager( 6796): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6796): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6796): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/CAR.SERVICE( 6700): mConnectedToCar = false, abort
,E/ActivityThread( 6700): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@60056d0 that was originally bound here
E/ActivityThread( 6700): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@60056d0 that was originally bound here
E/ActivityThread( 6700): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6700): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6700): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6700): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6700): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6700): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6700): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6700): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6700): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6700): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6700): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6700): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6700): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6700): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3280)
E/ActivityThread( 6700): 	at android.app.ActivityThread.access$1900(ActivityThread.java:181)
E/ActivityThread( 6700): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1565)
E/ActivityThread( 6700): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6700): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6700): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6700): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6700): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6700): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6700): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ResourcesManager( 6796): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/ActivityThread( 6700): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@21e4850b that was originally bound here
E/ActivityThread( 6700): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@21e4850b that was originally bound here
E/ActivityThread( 6700): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6700): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6700): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6700): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6700): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6700): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6700): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6700): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6700): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6700): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6700): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6700): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6700): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3312)
E/ActivityThread( 6700): 	at android.app.ActivityThread.access$2000(ActivityThread.java:181)
E/ActivityThread( 6700): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1570)
E/ActivityThread( 6700): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6700): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6700): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6700): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6700): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6700): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6700): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 1014): Unbind failed: could not find connection for android.os.BinderProxy@140003c9
,W/ResourcesManager( 6796): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 6796): system/finder_cp/cpdata.xml file not found
,D/NearbySource( 6813): Nearby Source Create!
,D/NearbyContext( 6813): Nearby Context Create!
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6813): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 6813): Samsung link source created
,D/ContactProvider( 6813): getAllContactInfoList Start
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/PackagesMonitor( 6813): PackagesMonitor onReceive :com.google.android.gms
,D/ContactProvider( 6813): getAllContactInfoList End
,I/syncContacts( 6813): thread: 1133, sync time = 37
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/UpdateIcingCorporaServi( 6756): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,E/Zygote  ( 6834): MountEmulatedStorage(),
,E/Zygote  ( 6834): v2,
,I/ActivityManager( 1014): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6834 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/libpersona( 6834): KNOX_SDCARD checking this for 10069,
I/libpersona( 6834): KNOX_SDCARD not a persona
,I/SELinux ( 6834): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6834): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6834): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,D/TimaKeyStoreProvider( 6834): TimaSignature is unavailable
,D/ActivityThread( 6834): Added TimaKeyStore provider
,D/FileShare-Server( 6834): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6849): MountEmulatedStorage(),
E/Zygote  ( 6849): v2
I/libpersona( 6849): KNOX_SDCARD checking this for 1000
I/libpersona( 6849): KNOX_SDCARD not a persona,
,I/ActivityManager( 1014): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6849 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 5285:com.osp.app.signin/u0a41 (adj 15): empty #31
,I/SELinux ( 6849): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6849): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6849): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/UpdateIcingCorporaServi( 6756): UpdateCorporaTask done [took 107 ms] updated apps [took 107 ms] 
,I/ActivityManager( 1014): Killing 6230:com.android.mms/u0a46 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6849): TimaSignature is unavailable
,D/ActivityThread( 6849): Added TimaKeyStore provider
,W/ResourcesManager( 6849): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6864): MountEmulatedStorage(),
,E/Zygote  ( 6864): v2
,I/libpersona( 6864): KNOX_SDCARD checking this for 1000,
I/libpersona( 6864): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=6864 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 5586:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
I/SELinux ( 6864): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6864): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/CountryDetector( 1014): No listener is left
E/SELinux ( 6864): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6864): TimaSignature is unavailable
,D/ActivityThread( 6864): Added TimaKeyStore provider
,D/KnoxSetupWizardDbHelper( 6864): dbMigrationFlag : false
,D/ShortcutReceiver( 6864):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus,
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,I/ActivityManager( 1014): Killing 6274:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1014): failed to open /acct/uid_10046/pid_6230/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10041/pid_5285/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5586/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 1970): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PackageBroadcastService( 1970): Null package name or gms related package.  Ignoreing.
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Icing   ( 1970): updateResources: need to parse f{com.google.android.gms}
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1014): failed to open /acct/uid_10157/pid_6274/cgroup.procs: No such file or directory
,I/art     ( 1970): Explicit concurrent mark sweep GC freed 44985(2MB) AllocSpace objects, 39(886KB) LOS objects, 24% free, 15MB/20MB, paused 1.517ms total 82.551ms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,I/Icing   ( 1970): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
,I/Icing   ( 1970): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/FactoryTest( 4609): Not factory mode
,D/FactoryTest( 4609): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 4609): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 4609): still no open session command from host, so toast
,W/ContextImpl( 4609): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4609): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 4609): Timeline: Activity_launch_request id:com.android.settings time:107650,
,E/PersonaManagerService( 1014): inState():  stateMachine is null !!,
,I/PersonaManagerService( 1014): PersonaId don't exist
,I/ActivityManager( 1014): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings,
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1014): mDVFSHelper.acquire(),
,I/UsageStatsService( 1014): User[0] Flushing usage stats to disk
,D/PersonaManager( 1014): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1014): Focused application set to: xxxx
,D/InputDispatcher( 1014): Focus left window: 5321
,E/MTPRx   ( 4609): started activity for popup
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 4609): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 4609): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 4609): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4609): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4609): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4609): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/UsageStatsDatabase( 1014): Moving file /data/system/usagestats/0/daily/1451865600000 to /data/system/usagestats/0/daily/1451865606823
,I/UsageStatsDatabase( 1014): Moving file /data/system/usagestats/0/weekly/1449705603694 to /data/system/usagestats/0/weekly/1449705610517
,I/UsageStatsDatabase( 1014): Moving file /data/system/usagestats/0/weekly/1450310403694 to /data/system/usagestats/0/weekly/1450310410517
I/UsageStatsDatabase( 1014): Moving file /data/system/usagestats/0/weekly/1450915203694 to /data/system/usagestats/0/weekly/1450915210517
,I/UsageStatsDatabase( 1014): Moving file /data/system/usagestats/0/weekly/1451520000000 to /data/system/usagestats/0/weekly/1451520006823
I/UsageStatsDatabase( 1014): Moving file /data/system/usagestats/0/monthly/1439783474031 to /data/system/usagestats/0/monthly/1439783480854
,I/UsageStatsDatabase( 1014): Moving file /data/system/usagestats/0/monthly/1441152039459 to /data/system/usagestats/0/monthly/1441152046282
I/UsageStatsDatabase( 1014): Moving file /data/system/usagestats/0/monthly/1443744039459 to /data/system/usagestats/0/monthly/1443744046282
,I/UsageStatsDatabase( 1014): Moving file /data/system/usagestats/0/monthly/1446336014145 to /data/system/usagestats/0/monthly/1446336020968
I/UsageStatsDatabase( 1014): Moving file /data/system/usagestats/0/monthly/1448928006083 to /data/system/usagestats/0/monthly/1448928012906
I/UsageStatsDatabase( 1014): Moving file /data/system/usagestats/0/monthly/1451520000000 to /data/system/usagestats/0/monthly/1451520006823
,I/UsageStatsDatabase( 1014): Moving file /data/system/usagestats/0/yearly/1435031474031 to /data/system/usagestats/0/yearly/1435031480854
I/UsageStatsDatabase( 1014): Moving file /data/system/usagestats/0/yearly/1450656003694 to /data/system/usagestats/0/yearly/1450656010517
,I/UsageStatsService( 1014): User[0] Rollover scheduled @ 2016-01-05 01:00:00(1451952000000)
,E/SettingsReceiverActivity( 4609): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings,
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/InputDispatcher( 1014): Focused application set to: xxxx,
D/InputDispatcher( 1014): Focus entered window: 5321
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
W/InputMethodManagerService( 1014): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@9971aa9 attribute=null, token = android.os.BinderProxy@2cf18a32
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/SettingsReceiverActivity( 4609): dev.kiessupport is : TRUE
,D/PhoneWindow( 4609): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 4609): *FMB* installDecor flags : 8388610
,D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
,D/PersonaManager( 1014): isKioskContainerExistOnDevice,
,V/ActivityThread( 5321): updateVisibility : ActivityRecord{19b8afbe token=android.os.BinderProxy@4302740 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true,
,I/Timeline( 5321): Timeline: Activity_idle id: android.os.BinderProxy@4302740 time:107829
,E/Watchdog( 1014): !@Sync 3
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF
,W/ActivityManager( 1014): mDVFSHelper.release()
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,V/AlarmManager( 1014): waitForAlarm result :4
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/Finsky  ( 6635): [1121] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6635): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.PeopleRequestProcessor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 270
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 239, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged,
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 5438): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5438): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/IcingInternalCorpora( 1970): getNumBytesRead when not calculated.
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1014): [PWL] Off : 75s ago
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5438): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5438): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 4
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/AlarmManager( 1014): waitForAlarm result :4,
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter,
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.metadata.ContactMetadataSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.games.chimera.GamesSyncServiceNotificationProxy; callingUser = 0; userId(target) = 0
,D/ChimeraCfgMgr( 1970): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1970): Module APK com.google.android.play.games already loaded
,E/ActivityThread( 1970): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager( 1014): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 116696, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager( 1014): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 208582, reason: UserStart
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.apps.docs, action: android.content.SyncAdapter
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SecContentProvider2( 1014): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1014): mCursor = null
,V/AccountUtils( 1970): 0 accounts found with uca feature
I/GamesSyncAdapter( 1970): Starting sync for 3a3529a
,I/GamesSyncAdapter( 1970): Sync duration for 3a3529a: 13
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1970): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1970): Module APK com.google.android.play.games already loaded
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1970): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1970): Module APK com.google.android.play.games already loaded
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for fully charged,
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false,
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5438): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5438): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :8,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1014): [PWL] Off : 105s ago
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,I/ClearcutLoggerApiImpl( 1776): disconnect managed GoogleApiClient,
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 5
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,V/AlarmManager( 1014): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 237, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5438): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5438): Disconnected process message: 10,
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 140s ago
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1014): waitForAlarm result :4
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1014): !@Sync 6
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/ClearcutLoggerApiImpl( 1970): disconnect managed GoogleApiClient
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 236, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1014): Plugged
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1014): mGripSensorEnabled= false,
,V/HeadsetService( 5438): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5438): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/Watchdog( 1014): !@Sync 7,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1014): [PWL] Off : 180s ago,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1014): !@Sync 8
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/AlarmManager( 1014): waitForAlarm result :8
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 225s ago
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1014): !@Sync 9
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,E/SMD     (  287): DCD OFF
,D/TimaService( 1014): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1014): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1014): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1014): initializing...
,I/TLC_TIMA_PKM_initialize( 1014): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1014): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1014): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1014): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1014): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1014): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1014): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1014): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1014): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1014): Loaded image: APP id = 13
,I/TZ: qc_tlc_communication( 1014): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1014): Trustlet response is completed
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1014): !@Sync 10
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 275s ago
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 235, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,I/MotionRecognitionService( 1014): Plugged
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/HeadsetService( 5438): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5438): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/AlarmManager( 1014): waitForAlarm result :8
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1014): !@Sync 11
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 12
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1014): [PWL] Off : 330s ago,
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 13,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 14,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1014): [PWL] Off : 390s ago,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null,
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1776): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1776): Tagging socket 84 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1776, getuid(): 10012
,I/qtaguid ( 1776): Tagging socket 91 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1776, getuid(): 10012
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1970): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1970): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeConfigurator( 1776): Scheduling Phenotype for one-off execution 2758 seconds from now (1451923796122)
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1776): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  287): DCD OFF
,I/PhenotypeFlagCommitter( 1776): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1776): Using platform SSLCertificateSocketFactory
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,D/LocationManagerService( 1014): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/art     ( 1776): Explicit concurrent mark sweep GC freed 73327(4MB) AllocSpace objects, 48(2MB) LOS objects, 39% free, 13MB/22MB, paused 1.369ms total 74.243ms
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1776): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1776): Tagging socket 78 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1776, getuid(): 10012
,I/qtaguid ( 1776): Tagging socket 83 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1776, getuid(): 10012
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1776): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1776): Tagging socket 88 with tag 1000120100000000{268440065,0} for uid -1, pid: 1776, getuid(): 10012
,I/qtaguid ( 1776): Tagging socket 95 with tag 1000120100000000{268440065,0} for uid -1, pid: 1776, getuid(): 10012
,D/LocationManagerService( 1014): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1776): Tagging socket 88 with tag 1000120100000000{268440065,0} for uid -1, pid: 1776, getuid(): 10012
,D/LocationManagerService( 1014): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1776): Tagging socket 88 with tag 1000120100000000{268440065,0} for uid -1, pid: 1776, getuid(): 10012
,D/LocationManagerService( 1014): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1776): Tagging socket 88 with tag 1000120100000000{268440065,0} for uid -1, pid: 1776, getuid(): 10012
,D/LocationManagerService( 1014): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1776): Tagging socket 88 with tag 1000120100000000{268440065,0} for uid -1, pid: 1776, getuid(): 10012
,D/LocationManagerService( 1014): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1776): Tagging socket 88 with tag 1000120100000000{268440065,0} for uid -1, pid: 1776, getuid(): 10012
,D/LocationManagerService( 1014): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1776): Tagging socket 88 with tag 1000120100000000{268440065,0} for uid -1, pid: 1776, getuid(): 10012
,D/LocationManagerService( 1014): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1776): Tagging socket 88 with tag 1000120100000000{268440065,0} for uid -1, pid: 1776, getuid(): 10012
,D/LocationManagerService( 1014): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1776): Tagging socket 88 with tag 1000120100000000{268440065,0} for uid -1, pid: 1776, getuid(): 10012
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1014): waitForAlarm result :8
V/AlarmManager( 1014): No more alarm at this time.nowELAPSED=449683 batch.start=811047
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1,
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 15
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/bootchecker(  319): bootchecker wake up!!,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 16
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1014): [PWL] Off : 455s ago
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,V/AlarmManager( 1014): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 17
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 18
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 234, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5438): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5438): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1014): [PWL] Off : 525s ago,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF,
,I/Atfwd_Daemon(  322): Stop the daemon....,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 19
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF,
,D/TimaService( 1014): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1014): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1014): TimaServiceHandler.handleMessage what =1
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 20
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 21
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1014): [PWL] Off : 600s ago,
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 22,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 23
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1014): [PWL] Off : 680s ago
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 24,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 233, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5438): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5438): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 25,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 26
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1014): waitForAlarm result :8
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1014): [PWL] Off : 765s ago,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 27
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 28
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 29,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1014): [PWL] Off : 855s ago,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,D/TimaService( 1014): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1014): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1014): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 30,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,E/SMD     (  287): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 31
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 32
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,V/AlarmManager( 1014): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCM     ( 1970): Message from null null
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/GCM     ( 1970): Dropping message from null
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1014): waitForAlarm result :8,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1014): [PWL] Off : 951s ago
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 33,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 34,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 232, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5438): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5438): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 35,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 36
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1014): [PWL] Off : 1051s ago,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 37,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 38,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 39
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1014): [PWL] Off : 1156s ago,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/TimaService( 1014): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1014): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1014): TimaServiceHandler.handleMessage what =1
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,I/UsageStatsService( 1014): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1014): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1014): Updating Usage Statistics in DB @ 1451924566189
,I/ApplicationPolicy( 1014): updateDataUsageMap
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1014): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1014): ::isTableExists: Table exists 
,I/ApplicationUsage( 1014): Done Updating Usage Statistics in DB @ 1451924566961
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 40
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 41
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 42
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 43
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 1266s ago
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 44
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 45
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 46
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5438): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5438): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 47
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1014): [PWL] Off : 1381s ago,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 232, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1014): stay LED for fully charged,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5438): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5438): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 48
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false,
,V/HeadsetService( 5438): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5438): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 49,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/TimaService( 1014): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1014): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1014): TimaServiceHandler.handleMessage what =1
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5438): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5438): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 50,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5438): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5438): Disconnected process message: 10
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 51
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 1501s ago,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 240
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 240
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 52
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 240
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 240,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 240,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1014): !@Sync 53
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 240,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 240
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 240
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1014): !@Sync 54
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 240
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 240
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5438): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5438): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 240,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1404): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1404): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/HeadsetService( 5438): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5438): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1014): !@Sync 55
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 240
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1014): [PWL] Off : 1626s ago
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 240
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 56
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 240
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 240
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 240,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 57
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 240,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 240
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 240,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 58
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 240,
,E/SMD     (  287): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 240,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 240
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1014): !@Sync 59
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 240,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 240
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,I/PowerManagerService( 1014): [PWL] Off : 1756s ago
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/TimaService( 1014): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1014): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1014): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1014): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1014): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 1014): SIOP:: AP = 240
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 60
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 240,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 240
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 240,
,V/AlarmManager( 1014): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,I/ActivityManager( 1014): Killing 6292:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,I/ActivityManager( 1014): Killing 1719:com.sec.android.widgetapp.ap.hero.accuweather/u0a66 (adj 15): SPC_empty #32
,I/ActivityManager( 1014): Killing 1310:com.sec.android.daemonapp/u0a162 (adj 15): SPC_empty #33
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
I/ActivityManager( 1014): Killing 2699:com.samsung.android.providers.context/u0a3 (adj 15): SPC_empty #34
,I/ActivityManager( 1014): Killing 1279:com.android.settings/1000 (adj 15): SPC_empty #35
,I/ActivityManager( 1014): Killing 3999:com.sec.android.pagebuddynotisvc/u0a116 (adj 15): SPC_empty #36
,E/lowmemorykiller(  254): Error writing /proc/2575/oom_score_adj; errno=22
I/ActivityManager( 1014): Killing 2575:com.sec.phone/1001 (adj 15): SPC_empty #37
E/lowmemorykiller(  254): Error writing /proc/3704/oom_score_adj; errno=22
I/ActivityManager( 1014): Killing 3704:com.sec.bcservice/1000 (adj 15): SPC_empty #38
,I/ProcessStatsService( 1014): Prepared write state in 24ms
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,V/NetworkStats( 1014): performPollLocked(flags=0x3)
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,E/lowmemorykiller(  254): Error writing /proc/1310/oom_score_adj; errno=22
W/ActivityManager( 1014): ProcessRecord{22222e7f 1310:com.sec.android.daemonapp/u0a162} is already killed
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---
,V/NetworkStats( 1014): performPollLocked() took 14ms
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,I/BatteryStatsDumper( 1014): In refreshStats isReason Screen ON/OFF: false
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated,
,D/GpsStatusListenerHelper( 1014): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@27f2ae4c
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
,W/ActivityManager( 1014): Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 1000ms
,W/ActivityManager( 1014): Scheduling restart of crashed service com.samsung.android.providers.context/.ContextService in 3631442ms
,W/ActivityManager( 1014): Scheduling restart of crashed service com.sec.android.widgetapp.ap.hero.accuweather/.WeatherClockScreenService in 10993ms
,W/ActivityManager( 1014): Scheduling restart of crashed service com.android.settings/.wifi.WifiCredService in 20987ms
,W/ActivityManager( 1014): Scheduling restart of crashed service com.sec.phone/.SecPhoneService in 30984ms
,W/ActivityManager( 1014): Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 40981ms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/BatteryStatsDumper( 1014): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1014): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1014): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1014): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1014): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1014): Previous Battery Level: 100 Current Level: 100 Delta: 0
,W/ActivityManager( 1014): Scheduling restart of crashed service com.sec.bcservice/.BroadcastService in 50968ms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.analytics.CoreAnalyticsIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.download.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 1970): Aggregate from 1451923436044 (log), 1451922840266 (data)
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1776): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1776): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/art     ( 1014): Background sticky concurrent mark sweep GC freed 51540(6MB) AllocSpace objects, 353(5MB) LOS objects, 29% free, 29MB/41MB, paused 2.863ms total 100.546ms
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,I/System.out( 1776): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1776): Tagging socket 55 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1776, getuid(): 10012
,I/qtaguid ( 1776): Tagging socket 78 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1776, getuid(): 10012
,I/BatteryStatsDumper( 1014): Writing to database completed
,I/ProcessStatsService( 1014): Pruning old procstats: /data/system/procstats/state-2016-01-03-13-23-59.bin
,W/libprocessgroup( 1014): failed to open /acct/uid_10116/pid_3999/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10003/pid_2699/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10066/pid_1719/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_1279/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_1001/pid_2575/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10162/pid_1310/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10085/pid_6292/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3704/cgroup.procs: No such file or directory
,E/SMD     (  287): DCD OFF
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7634): MountEmulatedStorage()
,E/Zygote  ( 7634): v2
I/libpersona( 7634): KNOX_SDCARD checking this for 10116
I/libpersona( 7634): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.sec.android.pagebuddynotisvc for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc: pid=7634 uid=10116 gids={50116, 9997} abi=armeabi-v7a
,I/SELinux ( 7634): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 7634): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 7634): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7634): TimaSignature is unavailable
,D/ActivityThread( 7634): Added TimaKeyStore provider
,I/PageBuddyNotiSvc( 7634): onCreate mCpBitFlag=0
,E/Watchdog( 1014): !@Sync 61
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7654): MountEmulatedStorage(),
E/Zygote  ( 7654): v2
I/libpersona( 7654): KNOX_SDCARD checking this for 10066
,I/libpersona( 7654): KNOX_SDCARD not a persona
,I/SELinux ( 7654): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.android.widgetapp.ap.hero.accuweather for service com.sec.android.widgetapp.ap.hero.accuweather/.WeatherClockScreenService: pid=7654 uid=10066 gids={50066, 9997, 3003, 1028} abi=armeabi-v7a
I/SELinux ( 7654): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 7654): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7654): TimaSignature is unavailable
,D/ActivityThread( 7654): Added TimaKeyStore provider
,W/ResourcesManager( 7654): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7654): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7654): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/comsamsunglog( 7654): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7654): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 1505121795603] [ 1 ] 
D/comsamsunglog( 7654): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port WQHD
,D/comsamsunglog( 7654): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7654): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7654): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 1505121795603] [ 1 ] 
D/comsamsunglog( 7654): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port WQHD
D/comsamsunglog( 7654): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider( 1014): name = aw_daemon_service_key_agree_popup_check
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10066
,D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.daemonapp
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7672): MountEmulatedStorage()
,I/libpersona( 7672): KNOX_SDCARD checking this for 10162
E/Zygote  ( 7672): v2
I/libpersona( 7672): KNOX_SDCARD not a persona
I/SELinux ( 7672): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 7672): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.sec.android.daemonapp for content provider com.sec.android.daemonapp/.ap.common.WeatherContentProvider: pid=7672 uid=10162 gids={50162, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux ( 7672): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/art     (  314): Explicit concurrent mark sweep GC freed 8719(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 734us total 23.868ms
,D/TimaKeyStoreProvider( 7672): TimaSignature is unavailable
,D/ActivityThread( 7672): Added TimaKeyStore provider
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 613us total 17.105ms
,W/ResourcesManager( 7672): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 603us total 16.640ms
,D/comsamsungapp( 7672): [MSC_Daemon]>>> CCP:226 [0:0] CmaWeather Provider Created
,D/comsamsungapp( 7672): [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,D/comsamsungapp( 7672): [MSC_Daemon]>>> WNCP:216 [0:0] WeatherNewsJP Provider Created
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.sec.android.daemonapp
D/comsamsungapp( 7672): [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,D/comsamsungapp( 7672): [MSC_Daemon]>>> KWCP:221 [0:0] KWeather Provider Created,
D/comsamsungapp( 7672): [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,D/comsamsungapp( 7672): [MSC_Daemon]>>> WCP:1122 [0:0] Provider Created,
,D/comsamsungapp( 7672): [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67,
,D/comsamsungapp( 7672): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,D/comsamsungapp( 7672): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/comsamsungapp( 7672): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/comsamsungapp( 7672): [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,D/comsamsungapp( 7672): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/comsamsungapp( 7672): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/comsamsungapp( 7672): [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
,D/comsamsungapp( 7672): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,D/comsamsungapp( 7672): [MSC_Daemon]>>> WCS:65 [0:0] selLocation : null
,D/comsamsungapp( 7672): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/comsamsungapp( 7672): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/comsamsungapp( 7672): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,D/comsamsungapp( 7672): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,D/comsamsungapp( 7672): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,D/comsamsungapp( 7672): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 7672): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 7672): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 7672): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 7672): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 7672): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 7672): [MSC_Daemon]>>> WDSM:456 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 7672): [MSC_Daemon]>>> WU:1381 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 7672): [MSC_Daemon]>>> WU:1401 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 7672): [MSC_Daemon]>>> WDSM:460 [0:0] checkDay:true, UtilgetIsDay():false
D/daemonapp( 7672): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 7672): [MSC_Daemon]>>> WDSM:464 [0:0] selLocation : null
,D/daemonapp( 7672): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 7672): [MSC_Daemon]>>> WDSM:490 [0:0] today==null
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.sec.android.daemonapp
,D/daemonapp( 7672): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 7672): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 7672): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 7672): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 7672): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 7672): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 7672): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 7672): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 7672): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 7672): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 7672): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 7672): [MSC_Daemon]>>> WDSM:456 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 7672): [MSC_Daemon]>>> WU:1381 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 7672): [MSC_Daemon]>>> WU:1401 [0:0] cDayONight() ::: sunset is null 
D/daemonapp( 7672): [MSC_Daemon]>>> WDSM:460 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 7672): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 7672): [MSC_Daemon]>>> WDSM:464 [0:0] selLocation : null
,D/daemonapp( 7672): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 7672): [MSC_Daemon]>>> WDSM:490 [0:0] today==null
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.sec.android.daemonapp
,D/daemonapp( 7672): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 7672): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 7672): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 7672): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 7672): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 7672): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 7672): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 7672): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 7672): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 7672): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 7672): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 7672): [MSC_Daemon]>>> WDSM:456 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 7672): [MSC_Daemon]>>> WU:1381 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 7672): [MSC_Daemon]>>> WU:1401 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 7672): [MSC_Daemon]>>> WDSM:460 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 7672): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 7672): [MSC_Daemon]>>> WDSM:464 [0:0] selLocation : null
,D/daemonapp( 7672): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 7672): [MSC_Daemon]>>> WDSM:490 [0:0] today==null
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.sec.android.daemonapp
,D/daemonapp( 7672): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 7672): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 7672): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 7672): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 7672): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 7672): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 7672): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 7672): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 7672): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 7672): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 7672): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 7672): [MSC_Daemon]>>> WDSM:456 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 7672): [MSC_Daemon]>>> WU:1381 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 7672): [MSC_Daemon]>>> WU:1401 [0:0] cDayONight() ::: sunset is null 
D/daemonapp( 7672): [MSC_Daemon]>>> WDSM:460 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 7672): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 7672): [MSC_Daemon]>>> WDSM:464 [0:0] selLocation : null
,D/daemonapp( 7672): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 7672): [MSC_Daemon]>>> WDSM:490 [0:0] today==null
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7692): MountEmulatedStorage(),
E/Zygote  ( 7692): v2
I/libpersona( 7692): KNOX_SDCARD checking this for 1000
I/libpersona( 7692): KNOX_SDCARD not a persona
,I/SELinux ( 7692): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1014): Start proc com.android.settings for service com.android.settings/.wifi.WifiCredService: pid=7692 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 7692): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 7692): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 7692): TimaSignature is unavailable
,D/ActivityThread( 7692): Added TimaKeyStore provider
,W/ResourcesManager( 7692): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 7692): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7692): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7692): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7692): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7692): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/MySettingsProvider( 7692): DatabaseHelper(Context context):DATABASE_VERSION=1
,E/SQLiteLog( 7692): (283) recovered 10 frames from WAL file /data/data/com.android.settings/databases/mysettings.db-wal
,D/MySettingsProvider( 7692): onCreate():(mDB == null)? false:true  =true
,I/WifiCredService( 7692): onCreate
,D/WifiCredService( 7692): Action received :android.net.wifi.WIFI_STATE_CHANGED
,E/WifiStateMachine( 1014): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,D/WifiNative-wlan0( 1014): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1014): invaild command id : 215
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 250
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1014): !@Sync 62
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,TIME-OUT KILL (timeout was 1800000ms),V/AlarmManager( 1014): waitForAlarm result :4
I/ActivityManager( 1014): Killing 3328:com.samsung.hs20settings/1000 (adj 15): SPC_empty #31
W/ActivityManager( 1014): Scheduling restart of crashed service com.samsung.hs20settings/.WifiHs20UtilityService in 1000ms
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3328/cgroup.procs: No such file or directory
E/SMD     (  287): DCD OFF
D/SSRM:n  ( 1014): SIOP:: AP = 250
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7717): MountEmulatedStorage()
E/Zygote  ( 7717): v2
I/libpersona( 7717): KNOX_SDCARD checking this for 1000
I/libpersona( 7717): KNOX_SDCARD not a persona
I/SELinux ( 7717): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.hs20settings for service com.samsung.hs20settings/.WifiHs20UtilityService: pid=7717 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 7717): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7717): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7717): TimaSignature is unavailable
D/ActivityThread( 7717): Added TimaKeyStore provider
I/Hs20UtilService( 7717): onCreate
I/Hs20UtilService( 7717): Starting #8
D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
D/AndroidRuntime( 7736): 
D/AndroidRuntime( 7736): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7736): CheckJNI is OFF
D/AndroidRuntime( 7736): readGMSProperty: start
D/AndroidRuntime( 7736): readGMSProperty: already setted!!
D/AndroidRuntime( 7736): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 7736): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 7736): readGMSProperty: end
D/AndroidRuntime( 7736): addProductProperty: start
E/AffinityControl( 7736): AffinityControl: registerfunction enter
D/AndroidRuntime( 7736): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1014): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1014): START PACKAGE DELETE: observer{120969713}
D/PackageManager( 1014): pkg{<packageName>}
D/PackageManager( 1014): user{0}
D/PackageManager( 1014): caller{2000}
D/PackageManager( 1014): flags{3}
D/PersonaManagerService( 1014): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1014): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1014): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1014): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1014): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager( 1014): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1014): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/PackageManager( 1014): !@killApplicatoin: 10175, uninstall pkg
D/ApplicationPolicy( 1014): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1014): getApplicationUninstallationEnabled :  enabled true
I/ActivityManager( 1014): Force stopping com.test.thalitest appid=10175 user=-1: uninstall pkg
I/ActivityManager( 1014): Killing 5321:com.test.thalitest/u0a175 (adj 0): stop com.test.thalitest cause uninstall pkg
I/ActivityManager( 1014):   Force finishing activity ActivityRecord{3164e89c u0 com.test.thalitest/.MainActivity t2}
D/InputDispatcher( 1014): Focus left window: 5321
I/SurfaceFlinger(  257): id=12 Removed NainActivit (6/8)
I/SurfaceFlinger(  257): id=12 Removed NainActivit (-2/8)
D/InputDispatcher( 1014): Focused application released
D/FocusedStackFrame( 1014): Set to : 0
D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
W/ActivityManager( 1014): mDVFSHelper.acquire()
W/PackageSettings( 1014): Skipping PackageSetting{2f9f69e com.example.hello/10177} due to missing metadata
V/WindowManager( 1014): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
I/ActivityManager( 1014): Force stopping com.test.thalitest appid=10175 user=0: pkg removed
W/ActivityManager( 1014): CustomStartingWindow se packge removed so remove capture also
D/Launcher( 1466): onRestart, Launcher: 527353660
I/art     ( 3625): Explicit concurrent mark sweep GC freed 3027(186KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 6MB/11MB, paused 740us total 40.417ms
I/InputReader( 1014): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1823): mOCRHelper is null
W/GeofencerStateMachine( 1776): Ignoring removeGeofence because network location is disabled.
D/Launcher( 1466): onStart, Launcher: 527353660
D/Launcher.HomeView( 1466): onStart
D/Launcher( 1466): onResume, Launcher: 527353660
D/RegisteredComponentCache( 1426): Collect Tech packages for Knox
D/SettingsProvider( 1014): name = kids_home_mode
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10007
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
D/Launcher.HomeView( 1466): onResume
D/PersonaManager( 1426): isKioskContainerExistOnDevice
D/Launcher( 1466): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
I/KLMS-2.5.183: ( 3358): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 04 17:33:58 GMT+01:00 2016
D/ActivityManager( 1014): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
D/MenuAppsGridFragment( 1466): onResume
I/KLMS-2.5.183: ( 3358): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1014): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
I/splitIntent( 1014): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/WallpaperManager( 1466): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
D/WallpaperManager( 1466): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
D/WallpaperManager( 1466): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
D/elm:15183( 6358): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/PackagesMonitor( 6813): PackagesMonitor onReceive :com.test.thalitest
I/art     ( 1970): Explicit concurrent mark sweep GC freed 23826(1369KB) AllocSpace objects, 12(432KB) LOS objects, 25% free, 15MB/20MB, paused 1.850ms total 153.858ms
E/Zygote  ( 7753): MountEmulatedStorage()
E/Zygote  ( 7753): v2
I/libpersona( 7753): KNOX_SDCARD checking this for 10149
I/libpersona( 7753): KNOX_SDCARD not a persona
I/SELinux ( 7753): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 7753): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1014): handle home activity for 0
I/ActivityManager( 1014): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7753 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/WallpaperManagerService( 1014): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1014): post home show event for user 0
D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
D/Launcher.HomeView( 1466): onPause
E/SELinux ( 7753): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Launcher( 1466): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3358): KLMSIntentService(): onCreate()
I/KLMS-2.5.183: ( 3358): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
E/Zygote  ( 7768): MountEmulatedStorage()
E/Zygote  ( 7768): v2
I/libpersona( 7768): KNOX_SDCARD checking this for 10046
I/libpersona( 7768): KNOX_SDCARD not a persona
I/SELinux ( 7768): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=7768 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
I/SELinux ( 7768): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7768): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/art     ( 1014): Explicit concurrent mark sweep GC freed 53119(3MB) AllocSpace objects, 23(585KB) LOS objects, 33% free, 27MB/41MB, paused 6.825ms total 256.589ms
D/TimaKeyStoreProvider( 7753): TimaSignature is unavailable
I/art     ( 1014): WaitForGcToComplete blocked for 244.534ms for cause Explicit
D/ActivityThread( 7753): Added TimaKeyStore provider
I/KLMS-2.5.183: ( 3358): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/ActivityManager( 1014): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
I/SurfaceFlinger(  257): id=16 createSurf (720x1280),1 flag=4, Mauncher
I/KLMS-2.5.183: ( 3358): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/KLMS-2.5.183: ( 3358): KLMSIntentService(): PACKAGE_REMOVED
D/SecContentProvider2( 1014): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1014): mCursor = null
D/InputDispatcher( 1014): Focus entered window: 1466
D/elm:15183( 6358): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
I/KLMS-2.5.183: ( 3358): KLMSIntentService(): listeningToPackageRemoved().START
D/elm:15183( 6358): ElmAgentService : onCreate()
D/elm:15183( 6358): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 6358): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6358): MDMBridge.getInstance()
D/elm:15183( 6358): MDMBridge.getAllLicenseInfoFromSDK()
D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 1466): log_dcs ThreadedRenderer::initialize entered! 
D/TimaKeyStoreProvider( 7768): TimaSignature is unavailable
D/ActivityThread( 7768): Added TimaKeyStore provider
I/art     ( 6215): Explicit concurrent mark sweep GC freed 394(33KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 3.288ms total 64.909ms
I/KLMS-2.5.183: ( 3358): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
V/ActivityThread( 1466): updateVisibility : ActivityRecord{34dfd515 token=android.os.BinderProxy@36198fb9 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1466): onStop
D/elm:15183( 6358): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15183( 6358): ElmAgentService : onDestroy().
D/AASAservice-UpdateReceiver( 6740): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
D/PersonaManager( 1426): isKioskContainerExistOnDevice
W/System.err( 6740): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 6740): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
W/System.err( 6740): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 6740): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 6740): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 6740): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 6740): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6740): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6740): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 6740): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6740): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6740): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6740): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/ResourcesManager( 7768): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7768): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7768): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7768): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7768): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7768): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/SQLiteLog( 6215): (284) automatic index on crash_info_summary(package_name_touched)
D/RegisteredServicesCache( 1426): empty dynamic service
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1014): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7788 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 7788): MountEmulatedStorage()
E/Zygote  ( 7788): v2
I/libpersona( 7788): KNOX_SDCARD checking this for 1000
I/libpersona( 7788): KNOX_SDCARD not a persona
I/SELinux ( 7788): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 7788): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
E/SELinux ( 7788): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Mms/MmsApp( 7768): [start]    onCreate() consume time = 0.0
W/InputMethodManagerService( 1014): Got RemoteException sending setActive(false) notification to pid 5321 uid 10175
W/ActivityManager( 1014): mDVFSHelper.release()
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/KLMS-2.5.183: ( 3358): KLMSIntentService(): listeningToPackageRemoved().END
D/ThemeInfoUtil( 7753): getCurrentFestivalName is [null]
D/ThemeInfoUtil( 7753): isCurrentFestival = false
D/BadgeProvider( 6412): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 6412): sendNotify, [notify] : null
D/BadgeProvider( 6412): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 6412): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 6412): update, [UpdateCount] : 1
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 7788): TimaSignature is unavailable
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 7788): Added TimaKeyStore provider
E/Zygote  ( 7805): MountEmulatedStorage()
I/ActivityManager( 1014): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7805 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 6310:com.qualcomm.timeservice/1000 (adj 15): empty #31
E/Zygote  ( 7805): v2
I/libpersona( 7805): KNOX_SDCARD checking this for 10152
I/libpersona( 7805): KNOX_SDCARD not a persona
I/SELinux ( 7805): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 7805): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7805): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/RCPManagerService( 1014): PackageReceiver onReceive()
I/HarmonyEASService( 1014): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1014): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1014): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1014): OtpDbHelper::getInstance New instance created
D/OTPFW   ( 1014): DBIntegrity::getInstance - New instance created
D/SamsungIME( 1823): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
D/OTPFW   ( 1014): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10175 container id = 0
I/KLMS-2.5.183: ( 3358): KLMSIntentService(): onDestroy()
I/OTPFW   ( 1014): ProvisionData::getAllEntries Enter
E/OTPFW   ( 1014): ProvisionData::getAllEntries Table is empty
I/Timeline( 1014): Timeline: Activity_windows_visible id: ActivityRecord{20e7636f u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:1888125
D/TimaKeyStoreProvider( 7805): TimaSignature is unavailable
D/ActivityThread( 7805): Added TimaKeyStore provider
D/BackupManagerService( 1014): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1014): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1014): uID is 10175
V/EnterpriseBillingPolicy( 1014): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - end - null
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1014): uID is 10175
V/EnterpriseBillingPolicy( 1014): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - end - null
D/WallpaperManagerService( 1014):  force update = false; persona id = 0; current user =0; current persona = 0
D/WindowOrientationListener( 1014):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
D/KnoxTimeoutHandler( 1014): handleHomeShow for 0 and current 0
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
V/AlarmManagerEXT( 1014): com.test.thalitest(10175) is removed.
D/SSRM:aZ ( 1014): MSG_TYPE_APP_REMOVED::
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/EnterpriseDeviceManagerService( 1014): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1014): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1014): no available spell checker services found
E/Zygote  ( 7820): MountEmulatedStorage()
E/Zygote  ( 7820): v2
I/libpersona( 7820): KNOX_SDCARD checking this for 1000
I/libpersona( 7820): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7820 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 7820): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
I/SELinux ( 7820): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7820): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/PersonaManager( 1014): isKioskContainerExistOnDevice
D/TimaKeyStoreProvider( 7820): TimaSignature is unavailable
D/ActivityThread( 7820): Added TimaKeyStore provider
D/TaskPersister( 1014): removeObsoleteFile: deleting file=2_task.xml
W/art     ( 7768): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 170.888ms
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SQLiteLog( 7805): (284) automatic index on shooting_modes(title_id)
W/ContextImpl( 7788): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
I/PCWCLIENTTRACE_LOG( 7820): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 7820): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7820): new DMDBOpenHelper instance
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/RCPManager( 6849):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1014):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1014): queryAllProviders():  providerCallBack is not register for 0
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/PCWCLIENTTRACE_PushUtil( 7820): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7820): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7820): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7820): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7837): MountEmulatedStorage()
I/libpersona( 7837): KNOX_SDCARD checking this for 10156
E/Zygote  ( 7837): v2
I/libpersona( 7837): KNOX_SDCARD not a persona
I/SELinux ( 7837): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7837 uid=10156 gids={50156, 9997} abi=armeabi-v7a
I/SELinux ( 7837): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7837): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     ( 1014): Explicit concurrent mark sweep GC freed 19335(1130KB) AllocSpace objects, 5(86KB) LOS objects, 33% free, 27MB/41MB, paused 5.068ms total 454.910ms
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/Mms/TelephonyPermission( 7768): start operation mode monitor
E/Zygote  ( 7852): MountEmulatedStorage()
I/libpersona( 7852): KNOX_SDCARD checking this for 10100
E/Zygote  ( 7852): v2
I/libpersona( 7852): KNOX_SDCARD not a persona
I/SELinux ( 7852): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7852 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 7852): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/Mms/ArtClassLoader( 7768): init before art
E/SELinux ( 7852): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Killing 6412:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
D/TimaKeyStoreProvider( 7837): TimaSignature is unavailable

```
