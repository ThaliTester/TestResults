#### Test 54968200254eab2_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
D/Mms/DraftCache( 5779): [start]    rebuildCache consume time = 35.984427
D/Mms/MethodReflector( 5779): getSubId is called
D/Mms/TelephonyUtils( 5779): getLongSubId from simSlot 0, return Value = -1
I/DBG_POLICYDM( 5842): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
D/Mms/MethodReflector( 5779): getTelephonyProperty is called
D/TP/MmsSmsProvider( 1467): query,matched:12, calling pid = 5779
D/Mms/DownloadManager( 5779): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5779): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5779): auto download without roaming -> true
D/Mms/DownloadManager( 5779): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 5779): getSubId is called
D/Mms/MethodReflector( 5779): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5779): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5779): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5779): getTelephonyProperty is called
D/Mms/DownloadManager( 5779): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5779): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5779): auto download without roaming -> true
D/TP/MmsSmsProvider( 1467): match 12:Elapsed time : 2.347 ms
D/Mms/DownloadManager( 5779): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5779): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5779): mAutoDownload ------> true
D/Mms/DraftCache( 5779): [end]    rebuildCache consume time = 11.464792
D/ComposerPerformance( 5779): 1451954359969 ms / [DONE] Composer constructor
E/CII     ( 5779): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 5779): ReservationManager()
I/Mms/ReservationManager( 5779): resetAfterConnected()
D/TapandpayWidget:TapandpayAppWidgetProvider( 5919): Widget is not attached.
D/TP/MmsSmsProvider( 1467): query,matched:7, calling pid = 5779
D/TP/MmsSmsProvider( 1467): match 7:Elapsed time : 2.625 ms
D/Mms/ArtClassLoader( 5779): init [DONE] art
D/Mms/Conversation( 5779): [start]    init() consume time = 26.305104
I/Mms/ReservationManager( 5779): getReservedSendMessageCount(): retMessageCount=0
D/TP/MmsSmsProvider( 1467): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1467): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1467): updateThread(), thread_id = 9223372036854775807
V/TP/MmsSmsDatabaseHelper( 1467): sUpgradeVersion = 0, db.getVersion() = 81
D/LocationProviderProxy( 1018): applying state to connected service
--------- beginning of system
W/libprocessgroup( 1018): failed to open /acct/uid_10122/pid_5268/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10134/pid_4918/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10135/pid_4807/cgroup.procs: No such file or directory
D/Mms/MmsApp( 5779): [end]    onCreate() consume time = 14.505261
D/TP/MmsSmsProvider( 1467): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1467): need read changed broadcast:false
D/Mms/Conversation( 5779): [end]    init consume time = 3.309062
D/Mms/MessagingNotification( 5779): [start]    init() consume time = 1.330521
D/Mms/MessagingNotification( 5779): [end]    init consume time = 2.57901
D/TP/MmsSmsProvider( 1467): query,matched:0, calling pid = 5779
V/TP/MmsSmsProvider( 1467): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1467): match 0:Elapsed time : 0.835 ms
W/libprocessgroup( 1018): failed to open /acct/uid_10033/pid_5295/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10035/pid_5324/cgroup.procs: No such file or directory
D/Mms/SpamFilter( 5779): [start]    SpamFilter fill() begin consume time = 11.673073
D/TP/MmsSmsProvider( 1467): query,matched:400, calling pid = 5779
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/Mms/Synchronizer( 5779): [start]    doSync consume time = 7.585521
E/Zygote  ( 5953): MountEmulatedStorage()
E/Zygote  ( 5953): v2
I/libpersona( 5953): KNOX_SDCARD checking this for 10072
I/libpersona( 5953): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5953 uid=10072 gids={50072, 9997} abi=armeabi-v7a
I/SELinux ( 5953): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/Mms/SpamFilter( 5779): [end]    SpamFilter fill() finished consume time = 17.086979
D/TP/MmsSmsProvider( 1467): update, matched:300, calling pid = 5779
V/TP/MmsSmsProvider( 1467): syncDBData start
V/TP/MmsSmsProvider( 1467): syncDBData sms end
V/TP/MmsSmsProvider( 1467): syncDBData mms end
V/TP/MmsSmsProvider( 1467): syncDBData end
I/SELinux ( 5953): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/Mms/Synchronizer( 5779): [end]    doSync consume time = 4.080209
E/SELinux ( 5953): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/Mms/DownloadManager( 5779): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 5779): roaming ------> false, mSimSlot = 0
D/Mms/MethodReflector( 5779): getSubId is called
D/Mms/TelephonyUtils( 5779): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5779): getTelephonyProperty is called
D/Mms/DownloadManager( 5779): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5779): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5779): auto download without roaming -> true
D/Mms/DownloadManager( 5779): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5779): mAutoDownload ------> true
D/Mms/FreeMessageStatusReceiver( 5779): onReceive, action : android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5967): MountEmulatedStorage()
D/Mms/FreeMessageReceiverService( 5779): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5779): onHandleIntent: ACTION_PACKAGE_ADDED
E/Zygote  ( 5967): v2
I/libpersona( 5967): KNOX_SDCARD checking this for 10047
I/libpersona( 5967): KNOX_SDCARD not a persona
I/DBG_POLICYDM( 5842): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
I/SELinux ( 5967): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5967 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
I/SELinux ( 5967): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5967): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 5953): TimaSignature is unavailable
D/ActivityThread( 5953): Added TimaKeyStore provider
D/PackageBroadcastService( 1934): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
I/ActivityManager( 1018): Killing 5200:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
I/ActivityManager( 1018): Killing 3725:com.android.providers.calendar/u0a42 (adj 15): empty #31
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
D/ChimeraCfgMgr( 1934): Loading module com.google.android.gms.games from APK com.google.android.play.games
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraModuleLdr( 1934): Loading module APK com.google.android.play.games
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 5967): TimaSignature is unavailable
I/DBG_POLICYDM( 5842): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
D/ActivityThread( 5967): Added TimaKeyStore provider
I/DBG_POLICYDM( 5842): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ResourcesManager( 5967): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5967): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5967): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/BadgeProvider( 5953): onCreate
D/BadgeProvider( 5953): DatabaseHelper
D/Mms/MessagingNotification( 5779): checkBadgeCount unreadCount=0 badgeCount=0
D/TP/SmsProvider( 1467): query,matched:26, calling pid = 5779
D/TP/SmsProvider( 1467): match 26:Elapsed time : 1.776 ms
D/TP/MmsSmsProvider( 1467): query,matched:6, calling pid = 5779
D/TP/MmsSmsProvider( 1467): match 6:Elapsed time : 1.625 ms
W/libprocessgroup( 1018): failed to open /acct/uid_10042/pid_3725/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5200/cgroup.procs: No such file or directory
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1018): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5989 uid=10025 gids={50025, 9997} abi=armeabi-v7a
E/Zygote  ( 5989): MountEmulatedStorage()
E/Zygote  ( 5989): v2
I/libpersona( 5989): KNOX_SDCARD checking this for 10025
I/libpersona( 5989): KNOX_SDCARD not a persona
I/SELinux ( 5989): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5989): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5989): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5989): TimaSignature is unavailable
D/ActivityThread( 5989): Added TimaKeyStore provider
I/ActivityManager( 1018): Killing 3945:com.google.android.talk/u0a104 (adj 15): empty #31
W/ResourcesManager( 5989): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/MyFiles ( 5967): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
I/ActivityManager( 1018): Killing 5469:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
I/TactileAssist( 1018): enable value -1
I/TactileAssist( 1018): internal enable value -1
I/TactileAssist( 1018): intensity value -1
I/TactileAssist( 1018): saveAppList value true
I/TactileAssist( 1018): List of disabled apps :
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6005): MountEmulatedStorage()
E/Zygote  ( 6005): v2
I/libpersona( 6005): KNOX_SDCARD checking this for 10053
I/libpersona( 6005): KNOX_SDCARD not a persona
I/SELinux ( 6005): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6005): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6005): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=6005 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
E/installd(  284): system dir 0 : /system/app/
E/installd(  284): system dir 1 : /system/priv-app/
E/installd(  284): system dir 2 : /vendor/app/
E/installd(  284): system dir 3 : /oem/app/
D/TimaKeyStoreProvider( 6005): TimaSignature is unavailable
D/ActivityThread( 6005): Added TimaKeyStore provider
I/OMACP   ( 5989): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
E/SMD     (  288): DCD OFF
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 6005): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/Mms/Omacp( 5779): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
I/ConfigFetchService( 1934): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ServiceManager(  315): Waiting for service AtCmdFwd...
I/ConfigFetchService( 1934): launchTask
I/OMACP   ( 5989): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 5989): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/PackageManager( 1018): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/OMACP   ( 5989): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
D/ChimeraCfgMgr( 1934): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1934): Module APK com.google.android.play.games already loaded
I/OMACP   ( 5989): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 5989): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 5989): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 5989): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 5989): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 5989): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 5989): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 5989): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/DBG_POLICYDM( 5842): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
I/OMACP   ( 5989): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 5989): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
W/libprocessgroup( 1018): failed to open /acct/uid_10069/pid_5469/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10104/pid_3945/cgroup.procs: No such file or directory
D/ChimeraCfgMgr( 1934): Loading module com.google.android.gms.vision from APK com.google.android.gms
I/PeopleContactsSync( 1934): CP2 sync disabled
D/Vision  ( 1934): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1934): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1934): No vision deps
D/Compatibility( 6005): onReceive() it will make start service
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/Compatibility( 6005): onHandleIntent()
D/Compatibility( 6005): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10175, android.intent.extra.user_handle=0}]
I/libpersona( 6030): KNOX_SDCARD checking this for 1000
D/Compatibility( 6005): found: 2
I/libpersona( 6030): KNOX_SDCARD not a persona
E/Zygote  ( 6030): MountEmulatedStorage()
E/Zygote  ( 6030): v2
I/SELinux ( 6030): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
V/AlarmManager( 1018): waitForAlarm result :4
I/SELinux ( 6030): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6030 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 6030): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
V/ConfigFetchTask( 1934): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1X3wtX3bDakR4ZE8tkvokKBccA1GCRpqINdSzLvqu5tHuIH0nyZuZRql44yQIw6gE5U9rV1tix03mze5Vlhqg1oUQOQYVMBrpeJ7OfYmTZrcTZQFmFyqRGvfQFm-bIZeQZUE3pAIarp6Vym_DyUgrZcKdsEO97Pp-8nuxZbIkFo1tvNJXwYS58HSdKt4rsY5uj-CFMQ
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 6030): TimaSignature is unavailable
D/ActivityThread( 6030): Added TimaKeyStore provider
D/Compatibility( 6005): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6005): skipping ResolveInfo{1ee6a524 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 6005): considering ResolveInfo{c5d788d com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 6005): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6005): enabling receiver ResolveInfo{8957a42 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 6005): enabling receiver ResolveInfo{3f15a53 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
I/GoogleURLConnFactory( 1934): Using platform SSLCertificateSocketFactory
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Compatibility( 6005): enabling receiver ResolveInfo{267aef90 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 6005): enabling receiver ResolveInfo{30b61089 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 6005): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
I/GAv4    ( 5797): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5797):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5797):   adb logcat -s GAv4
W/ContextImpl( 6030): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6046): MountEmulatedStorage()
I/libpersona( 6046): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6046): v2
I/libpersona( 6046): KNOX_SDCARD not a persona
I/SELinux ( 6046): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6046): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=6046 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 6046): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/GAv4    ( 5797): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/TimaKeyStoreProvider( 6046): TimaSignature is unavailable
D/ActivityThread( 6046): Added TimaKeyStore provider
I/ActivityManager( 1018): Killing 5484:com.sec.knox.bridge/1000 (adj 15): empty #31
I/DBG_POLICYDM( 5842): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
W/GAv4    ( 5797): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/ResourcesManager( 6046): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
W/AnalyticsTrackerProxyImpl( 5797): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
I/DBG_POLICYDM( 5842): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
I/System.out( 1934): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1934): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1934): (HTTPLog)-Static: isShipBuild true
I/System.out( 1934): (HTTPLog)-Thread-276-252274199: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1934): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10012
I/ActivityManager( 1018): Killing 5500:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
W/BroadcastQueue( 1018): Exception when sending broadcast to ComponentInfo{com.sec.knox.bridge/com.sec.knox.bridge.PersonaShortcutReceiver}
W/BroadcastQueue( 1018): android.os.TransactionTooLargeException
W/BroadcastQueue( 1018): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1018): 	at android.os.BinderProxy.transact(Binder.java:511)
W/BroadcastQueue( 1018): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
W/BroadcastQueue( 1018): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:309)
W/BroadcastQueue( 1018): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1236)
W/BroadcastQueue( 1018): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20387)
W/BroadcastQueue( 1018): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
W/BroadcastQueue( 1018): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3368)
W/BroadcastQueue( 1018): 	at android.os.Binder.execTransact(Binder.java:461)
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/GAv4    ( 5797): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/Zygote  ( 6070): MountEmulatedStorage()
E/Zygote  ( 6070): v2
I/libpersona( 6070): KNOX_SDCARD checking this for 1000
I/libpersona( 6070): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6070 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6070): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6070): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6070): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/BaseAppContext( 1934): Using Auth Proxy for data requests.
W/BaseAppContext( 1934): Using Auth Proxy for data requests.
W/art     ( 5797): Suspending all threads took: 5.499ms
D/TimaKeyStoreProvider( 6070): TimaSignature is unavailable
D/ActivityThread( 6070): Added TimaKeyStore provider
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5484/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5500/cgroup.procs: No such file or directory
I/System.out( 1934): KnoxVpnUidStorageknoxVpnSupported API value returned is false
W/ResourcesManager( 6070): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/BaseAppContext( 1934): Using Auth Proxy for data requests.
I/SL_DEBUG( 5881): isLoggable:: isProductShip = 1
I/qtaguid ( 1934): Tagging socket 96 with tag 40b00000000{1035,0} for uid -1, pid: 1934, getuid(): 10012
W/BaseAppContext( 1934): Using Auth Proxy for data requests.
I/SL_DEBUG( 5881): isLoggable:: SL_DEBUG_EXIST = false
I/ActivityManager( 1018): Killing 5558:com.google.android.apps.plus/u0a120 (adj 15): empty #31
W/BaseAppContext( 1934): Using Auth Proxy for data requests.
D/ActivityThread( 5881): Loading provider com.samsung.android.sdk.samsunglink.provider.SLinkMedia: com.mfluent.asp.datamodel.ASPMediaStoreProvider
W/BaseAppContext( 1934): Using Auth Proxy for data requests.
I/qtaguid ( 1934): Tagging socket 105 with tag 40b00000000{1035,0} for uid -1, pid: 1934, getuid(): 10012
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5881): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/libprocessgroup( 1018): failed to open /acct/uid_10120/pid_5558/cgroup.procs: No such file or directory
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5797): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.docs/cache
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5881): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
E/Zygote  ( 6095): MountEmulatedStorage()
E/Zygote  ( 6095): v2
I/libpersona( 6095): KNOX_SDCARD checking this for 10120
I/libpersona( 6095): KNOX_SDCARD not a persona
I/SELinux ( 6095): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6095): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6095 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 5409:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
E/SELinux ( 6095): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
D/TimaKeyStoreProvider( 6095): TimaSignature is unavailable
D/ActivityThread( 6095): Added TimaKeyStore provider
W/ResourcesManager( 6095): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5797): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5797): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6115): MountEmulatedStorage()
E/Zygote  ( 6115): v2
I/libpersona( 6115): KNOX_SDCARD checking this for 10041
I/libpersona( 6115): KNOX_SDCARD not a persona
I/SELinux ( 6115): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6115): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=6115 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6115): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6115): TimaSignature is unavailable
D/ActivityThread( 6115): Added TimaKeyStore provider
I/art     (  304): Explicit concurrent mark sweep GC freed 8717(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 23.777ms
W/libprocessgroup( 1018): failed to open /acct/uid_10057/pid_5409/cgroup.procs: No such file or directory
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 621us total 17.645ms
I/qtaguid ( 1934): Untagging socket 96
I/PowerManagerService( 1018): [PWL] Off : 5s ago
I/PowerManagerService( 1018): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1018): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1934, ws=null) (elapsedTime=47164)
I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              'Config Service fetch' (uid=10012, pid=1934, ws=WorkSource{10175 com.test.thalitest}) (elapsedTime=714)
I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1018, ws=WorkSource{10054}) (elapsedTime=618)
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 720us total 19.342ms
I/ConfigFetchService( 1934): fetch service done; releasing wakelock
I/ConfigFetchService( 1934): stopping self
I/ActivityManager( 1018): Killing 4985:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
I/SA      ( 6115): [SSP] onCreated
I/SA      ( 6115): [TPM] There is no property file
I/SA      ( 6115): [SCU] isHaveSA() - false
I/SA      ( 6115): [TPM] getModelProperty : null
I/SA      ( 6115): [TPM] getCSCProperty : null
,I/SA      ( 6115): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 6115): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 6115): [DM] TFT FEATURE: false
I/SA      ( 6115): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 6115): [DM] init START
I/art     ( 1018): Explicit concurrent mark sweep GC freed 220876(14MB) AllocSpace objects, 4(4MB) LOS objects, 33% free, 27MB/40MB, paused 3.217ms total 203.420ms
I/SA      ( 6115): [DM] This device is not a Vodafone
W/ResourceType( 6115): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 6115): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 6115): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 6115): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 6115): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 6115): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 6115): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 6115): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 6115): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 6115): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 6115): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 6115): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 6115): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 6115): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 6115): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 6115): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 6115): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 6115): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 6115): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 6115): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 6115): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 6115): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 6115): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 6115): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 6115): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 6115): [SCU] isHaveSA() - false
I/SA      ( 6115): support phone number id : false
I/SA      ( 6115): [DM] Supports Ref Jpn : true
I/SA      ( 6115): [DM] init END
I/SA      ( 6115): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
I/SA      ( 6115): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10175 extra.user_handle.:0 ]
W/art     ( 5797): Suspending all threads took: 56.616ms
I/ActivityManager( 1018): Killing 5625:com.sec.android.diagmonagent/1000 (adj 15): empty #31
V/JNIHelp ( 5797): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_4985/cgroup.procs: No such file or directory
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 5
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
W/ActivityThread( 5797): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5797): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@99c115e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5797): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5625/cgroup.procs: No such file or directory
D/AndroidRuntime( 6137): 
D/AndroidRuntime( 6137): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 6137): CheckJNI is OFF
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 6137): readGMSProperty: start
D/AndroidRuntime( 6137): readGMSProperty: already setted!!
D/AndroidRuntime( 6137): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6137): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6137): readGMSProperty: end
D/AndroidRuntime( 6137): addProductProperty: start
E/Zygote  ( 6147): MountEmulatedStorage()
E/Zygote  ( 6147): v2
I/libpersona( 6147): KNOX_SDCARD checking this for 10057
I/libpersona( 6147): KNOX_SDCARD not a persona
I/SELinux ( 6147): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6147): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6147 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
E/SELinux ( 6147): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 5045:com.google.android.gms:car/u0a12 (adj 15): empty #31
D/TimaKeyStoreProvider( 6147): TimaSignature is unavailable
D/ActivityThread( 6147): Added TimaKeyStore provider
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1018): Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
D/ChimeraCfgMgr( 1934): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1934): Module APK com.google.android.play.games already loaded
E/AffinityControl( 6137): AffinityControl: registerfunction enter
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/libprocessgroup( 1018): failed to open /acct/uid_10012/pid_5045/cgroup.procs: No such file or directory
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 6137): Calling main entry com.android.commands.am.Am
E/Zygote  ( 6175): MountEmulatedStorage()
I/libpersona( 6175): KNOX_SDCARD checking this for 10010
E/Zygote  ( 6175): v2
I/libpersona( 6175): KNOX_SDCARD not a persona
I/SELinux ( 6175): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=6175 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 6175): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
E/SELinux ( 6175): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1018): mDVFSHelper.acquire()
D/TimaKeyStoreProvider( 6175): TimaSignature is unavailable
D/ActivityThread( 6175): Added TimaKeyStore provider
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1018): *FMB* installDecor flags : 25362712
E/Zygote  ( 6193): MountEmulatedStorage()
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6193 uid=10175 gids={50175, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/libpersona( 6193): KNOX_SDCARD checking this for 10175
D/InputDispatcher( 1018): Focused application set to: xxxx
I/libpersona( 6193): KNOX_SDCARD not a persona
E/Zygote  ( 6193): v2
D/InputDispatcher( 1018): Focus left window: 3005
I/SELinux ( 6193): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/AndroidRuntime( 6137): Shutting down VM
I/SELinux ( 6193): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6193): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=404, uhalitest
D/TimaKeyStoreProvider( 6193): TimaSignature is unavailable
D/ActivityThread( 6193): Added TimaKeyStore provider
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
V/ActivityManager( 1018): Display changed displayId=0
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1018): isKioskContainerExistOnDevice
V/ActivityThread( 3005): updateVisibility : ActivityRecord{1c82e300 token=android.os.BinderProxy@2ff068f1 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/splitIntent( 1018): Queue : backgroundsplit_2 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
I/ActivityManager( 1018): Killing 5643:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
D/KeyguardViewMediator( 1179): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
D/KeyguardViewMediator( 1179): doKeyguard: not showing because lockscreen is off
V/KeyguardEffectViewController( 1179): *** Keyguard wallpaper service already unbounded
I/SurfaceFlinger(  257): id=11 Removed YUIInstallC (5/9)
I/SurfaceFlinger(  257): id=11 Removed YUIInstallC (-2/9)
D/LocationManagerService( 1018): getProviders()=[passive]
W/libprocessgroup( 1018): failed to open /acct/uid_10142/pid_5643/cgroup.procs: No such file or directory
I/WebViewFactory( 6193): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
W/art     ( 6137): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/LibraryLoader( 6193): Time to load native libraries: 3 ms (timestamps 3831-3834)
I/LibraryLoader( 6193): Expected native library version number "",actual native library version number ""
,I/UpdateIcingCorporaServi( 6147): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/Mms/MmsApp( 5779):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5779): [start]    fillCache consume time = 1951.103645
,D/Mms/ComposeMessageFragment( 5779): fillCache, easy = false
,V/WebViewChromiumFactoryProvider( 6193): Binding Chromium to main looper Looper (main, tid 1) {267aef90}
,I/LibraryLoader( 6193): Expected native library version number "",actual native library version number ""
I/chromium( 6193): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6193): Initializing chromium process, singleProcess=true
,W/art     ( 6193): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6193): ApplicationContext is null in ApplicationStatus
,W/chromium( 6193): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6193): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6193): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6193): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6193): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6193): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6193): Local Branch: 
I/Adreno-EGL( 6193): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6193): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6193):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/AbsListView( 5779): Get MotionRecognitionManager
,D/MotionRecognitionService( 1018):  ssp status : false
,D/Mms/ComposeMessageFragment( 5779): [end]    fillCache consume time = 70.090937
,I/UpdateIcingCorporaServi( 6147): UpdateCorporaTask done [took 122 ms] updated apps [took 122 ms] 
,I/ActivityManager( 1018): Killing 5219:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,D/Mms/BubbleViewCache( 5779): fillCache bubble = 1
,W/libprocessgroup( 1018): failed to open /acct/uid_10150/pid_5219/cgroup.procs: No such file or directory
,W/art     ( 6193): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6193): onDetachedFromWindow called when already detached. Ignoring,
,D/PhoneWindow( 6193): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6193): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6193): CordovaWebView is running on device made by: samsung
,W/art     ( 6193): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1018): Activity pause timeout for ActivityRecord{21701d6a u0 com.test.thalitest/.MainActivity t231}
,W/art     ( 6193): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6193): Render dirty regions requested: true
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,W/chromium( 6193): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 6193): updateVisibility : ActivityRecord{1143b0b5 token=android.os.BinderProxy@2cc7bb9f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6193): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6193): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1018): Focus entered window: 6193
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/SRIB_DCS( 6193): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6193): Initialized EGL, version 1.4
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/OpenGLRenderer( 6193): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6193): Enabling debug mode 0
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/PanelView( 1179): There is/are notification(s) 
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SamsungIME( 1785): getCurrentCandidateView,
,I/ActivityManager( 1018): Displayed Component not be shown by security: +682ms (total +765ms)
,W/ActivityManager( 1018): mDVFSHelper.release()
I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{21701d6a u0 com.test.thalitest/.MainActivity t231} time:84367
,W/IInputConnectionWrapper( 6193): showStatusIcon on inactive InputConnection
,I/Timeline( 6193): Timeline: Activity_idle id: android.os.BinderProxy@2cc7bb9f time:84369
,I/SurfaceFlinger(  257): id=13 Removed uhalitest (7/9)
,I/SurfaceFlinger(  257): id=13 Removed uhalitest (-2/9)
,D/SamsungIME( 1785): Dismiss ExpandCandiate
,I/SamsungIME( 1785): getDebugLevel  : 0x4f4c
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=6245 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,E/Zygote  ( 6245): MountEmulatedStorage()
,E/Zygote  ( 6245): v2,
I/libpersona( 6245): KNOX_SDCARD checking this for 10012,
I/SamsungIME( 1785): getDebugLevel  : 0x4f4c
I/libpersona( 6245): KNOX_SDCARD not a persona
W/BindingManager( 6193): Cannot call determinedVisibility() - never saw a connection for the pid: 6193
,I/SELinux ( 6245): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6245): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6245): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/SamsungIME( 1785): KeybaordView init() : load resources
,D/TimaKeyStoreProvider( 6245): TimaSignature is unavailable
D/ActivityThread( 6245): Added TimaKeyStore provider
,I/SamsungIME( 1785): getCurrentKeyboard
I/SamsungIME( 1785): getTextKeyboard
,W/ResourcesManager( 6245): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6245): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/SamsungIME( 1785): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/MultiDex( 6245): VM with version 2.1.0 has multidex support,
I/MultiDex( 6245): install
I/MultiDex( 6245): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6245): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6245): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6245): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1d331213: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6245): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1018): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1018): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1018): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
D/GCM     ( 1734): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/JsMessageQueue( 6193): Set native->JS mode to OnlineEventsBridgeMode
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Killing 5121:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1934): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 4449): callingUid 10012, callindPid: 4449
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1655): [178] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1934): Restart initialization of location
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_10040/pid_5121/cgroup.procs: No such file or directory
,D/jxcore_app_log( 6193): JniHelper::setJavaVM(0xb746d450), pthread_self() = -1214486288
D/JX-Cordova( 6193): jxcore cordova android initializing
,I/DBG_POLICYDM( 5842): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5842): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5842): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5842): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5842): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5842): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5842): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5842): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/AcmsKeyStoreHelper( 5860):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 5860): Key Store exist
I/AcmsKeyStoreHelper( 5860): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 5860):  getKeyStoreForApplication Exit
,I/AcmsCertificateMngr( 5860): getKeyStoreForApplication success 
D/AcmsCore( 5860): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
,D/AcmsServiceMonitor( 5860): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5860): Decrementing - Counter value: 1
D/AcmsCore( 5860): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 5860): This is NOT a valid MirrorLink app
,D/AcmsCore( 5860): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5860): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5860): Decrementing - Counter value: 0
,D/AcmsServiceMonitor( 5860): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 5860): getSvcCounter - Counter value: 0
D/AcmsService( 5860): Enter onDestroy
I/AcmsService( 5860): cleanUp(): inside service clean up
D/AcmsCore( 5860): AcmsCore: inside DeInit
D/AcmsCore( 5860): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5860): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 5860): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5860): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5860): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 5860): getSvcCounter - Counter value: 0
D/AcmsService( 5860): killing acms process
I/Process ( 5860): Sending signal. PID: 5860 SIG: 9
,E/SMD     (  288): DCD OFF
,I/ActivityManager( 1018): Process ACMS.Process (pid 5860)(adj 0) has died(58,1085)
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4216, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,W/jxcore-log( 6193): Initializing JXcore engine
W/jxcore-log( 6193): JXcore engine is ready
,W/jxcore-log( 6193): Starting JXcore engine
,E/audit   ( 1848): type=1400 msg=audit(1451954364.284:205): avc:  denied  { ioctl } for  pid=6193 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1848):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1848): type=1300 msg=audit(1451954364.284:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=bebafd58 items=0 ppid=304 ppcomm=main pid=6193 auid=4294967295 uid=10175 gid=10175 euid=10175 suid=10175 fsuid=10175 egid=10175 sgid=10175 fsgid=10175 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1848): type=1320 msg=audit(1451954364.284:205): 
,W/jxcore-log( 6193): Platform android
W/jxcore-log( 6193): 
W/jxcore-log( 6193): Process ARCH arm
W/jxcore-log( 6193): 
,I/jxcore-log( 6193): JXcore Cordova bridge is ready!
I/jxcore-log( 6193): 
,W/jxcore-log( 6193): JXcore engine is started
I/Choreographer( 6193): Skipped 130 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6193): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SSRM:n  ( 1018): SIOP:: AP = 350
,I/ConfigService( 1734): onDestroy
,E/SMD     (  288): DCD OFF
,I/jxcore-log( 6193): Toggling radios to true
I/jxcore-log( 6193): 
,D/BluetoothAdapter( 6193): enable()
,D/BluetoothAdapter( 6193): enable(): BT is already enabled..!
,D/SecContentProvider( 1018): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1018): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1018): mCursor = null
,D/WifiService( 1018): setWifiEnabled: true pid=6193, uid=10175
,W/ActivityManager( 1018): Permission Denial: getCurrentUser() from pid=6193, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1018): Failed getting userId using ActivityManagerNative
W/WifiService( 1018): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6193, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1018): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1018): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1018): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1018): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1018): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1018): name = wifi_on
,I/WifiService( 1018): disconnect: pid=6193, uid=10175
I/jxcore-log( 6193): Radios toggled
I/jxcore-log( 6193): 
I/wpa_supplicant( 2090): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 6193): Got Device Bluetooth address: 7C:F9:0E:51:18:22
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): Perf Test app loaded loaded
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): check test folder
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): found test : ./testFindPeers.js
I/jxcore-log( 6193): 
,I/wpa_supplicant( 2090): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 2090): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 2090): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 2090): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 2090): wlan0: State: DISCONNECTED -> DISCONNECTED
E/wpa_supplicant( 2090): Cmd 35605 not handled
,D/Tethering( 1018): interfaceStatusChanged wlan0, false
E/WifiStateMachine( 1018): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 2090): reset timer : RESET_TIMER 0
I/wpa_supplicant( 2090): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2090): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2090): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 2090): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 2090): First Scan Start
I/wpa_supplicant( 2090): Scan requested (ret=0) - scan timeout 30 seconds
D/Tethering( 1018): InitialState.processMessage what=4
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/Tethering( 1018): No numeric data
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,D/Tethering( 1018): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1018): clearTetheredNotification()
,E/WifiNative-wlan0( 1018): do suspend true
,V/NetworkStats( 1018): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
I/jxcore-log( 6193): found test : ./testSendData.js
I/jxcore-log( 6193): 
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
D/HotspotTile( 1179): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1179): updateTetherState():false, false
,D/CommandListener(  278): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1734): Read error: ssl=0xb79c4860: I/O error during system call, Connection timed out,
D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/NativeCrypto( 1734): SSL shutdown failed: ssl=0xb79c4860: I/O error during system call, Broken pipe
V/NetworkStats( 1018): performPollLocked() took 12ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/ConnectivityService( 1018): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
E/ConnectivityService( 1018): updateNetworkInfo()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine( 1018): Start Disconnecting Watchdog 1
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
I/wpa_supplicant( 2090): wlan0: Setting scan request: 0 sec 0 usec
I/qtaguid ( 1018): Tagging socket 385 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1018, getuid(): 1000
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14949 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6950 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,I/qtaguid ( 1018): Untagging socket 385
,I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
,D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiNative-wlan0( 1018): do suspend true
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3586): Starting #8
,I/Hs20UtilService( 3586): Message received 5007
D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NearbySettings( 1325): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1325): DMSUtil.isNetworkConnected - flag-null, state-null,
,I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1325): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1325): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1325): MountReceiver.mPrefHandler - 7002
,D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
D/CommandListener(  278): Clearing all IP addresses on wlan0
,D/WIFI_P2P( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false,
D/ConnectivityService( 1018): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/TelephonyNetworkFactory( 1467): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/ConnectivityService( 1018): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/TelephonyNetworkFactory( 1467): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1018): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/CSLegacyTypeTracker( 1018): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,fe80::7ef9:eff:fe51:1823/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} },
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Validated
D/CSLegacyTypeTracker( 1018): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 1179): CM callback handler got msg 524292
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
,D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
,D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/WifiNetworkAgent( 1018): NetworkAgent: NetworkAgent channel lost
,D/WIFI    ( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,E/Zygote  ( 6276): MountEmulatedStorage()
,E/Zygote  ( 6276): v2
I/libpersona( 6276): KNOX_SDCARD checking this for 10104
I/libpersona( 6276): KNOX_SDCARD not a persona
,I/SELinux ( 6276): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6276): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6276 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
E/SELinux ( 6276): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ConnectivityService( 1018): nai.networkMonitor.doQuit()
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): doQuit - quitNow()
D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
D/Tethering( 1018): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1018): MasterInitialState.processMessage what=3
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): updateIfacesLocked()
V/NetworkStats( 1018): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---,
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked() took 3ms
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1179): EthernetConnected: false
D/StatusBar.NetworkController( 1179): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1179): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1179): updateDataNetType()
D/StatusBar.NetworkController( 1179): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1179): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit,
V/NetworkStats( 1018): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1179): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/Choreographer( 6193): Skipped 108 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6193): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/TimaKeyStoreProvider( 6276): TimaSignature is unavailable
,D/ActivityThread( 6276): Added TimaKeyStore provider
,W/ResourcesManager( 6276): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PhoneApp( 1467): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
,D/PhoneApp( 1467): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
,D/PhoneApp( 1467): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
,D/PhoneApp( 1467): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
,D/PhoneApp( 1467): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
,D/PhoneApp( 1467): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
,D/PhoneApp( 1467): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
,D/PhoneApp( 1467): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
,D/PhoneApp( 1467): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
,D/PhoneApp( 1467): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
,D/PhoneApp( 1467): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
,D/PhoneApp( 1467): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
,D/PhoneApp( 1467): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
D/PhoneApp( 1467): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
D/PhoneApp( 1467): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1467): FileWriteThread : threadType = 3
,I/Babel_SMS( 6276): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6276): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6276): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/Babel_SMS( 6276): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6276): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6276): MmsConfig.loadFromResources
,E/Babel_SMS( 6276): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6276): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  283): getCameraInfo: X
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  283): getCameraInfo: X
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 6276): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6276): startup - clean
,I/Babel   ( 6276): deleted: false for 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3586): Starting #9
,I/Hs20UtilService( 3586): Message received 5007
,D/NearbySettings( 1325): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1325): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1325): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1325): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1325): MountReceiver.mPrefHandler - 7002
,W/VideoCapabilities( 6276): Unrecognized profile 2130706433 for video/avc
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6276): Unsupported mime audio/evrc
,W/AudioCapabilities( 6276): Unsupported mime audio/qcelp
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6276): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6276): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 6276): Unsupported mime audio/x-ms-wma
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6276): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6276): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6276): Unsupported mime audio/evrc
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6276): Unsupported mime video/wvc1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6276): Unsupported mime video/x-ms-wmv
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6276): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6276): Unsupported mime video/wvc1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6276): Unsupported mime video/x-ms-wmv
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6276): Unsupported mime video/x-ms-wmv7
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6276): Unsupported mime video/x-ms-wmv8
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6276): Unsupported mime video/mp43
,W/VideoCapabilities( 6276): Unsupported mime video/sorenson
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3005): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,W/VideoCapabilities( 6276): Unsupported mime video/mp4v-esdp
,I/DBG_DM  ( 3005): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,I/ApplicationPolicy( 1018): updateDataUsageMap
,I/PCWCLIENTTRACE_PushUtil( 5808): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5808): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5808): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5808): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1018): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=22
,I/splitIntent( 1018): base  index=22, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1018): other index=24, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
,I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,V/MusicLeanback( 5020): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5808): noConnectivity : true
,I/VideoCapabilities( 6276): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6276): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6276): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6276): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6276): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6276): onServiceConnected
,W/Babel   ( 6276): Attempted to change video mute state without an active call.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Killing 5362:com.google.android.gm/u0a101 (adj 15): empty #31
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6319): MountEmulatedStorage()
,E/Zygote  ( 6319): v2
I/libpersona( 6319): KNOX_SDCARD checking this for 10002
I/libpersona( 6319): KNOX_SDCARD not a persona
,I/SELinux ( 6319): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1018): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6319 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6319): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6319): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6319): TimaSignature is unavailable
,D/ActivityThread( 6319): Added TimaKeyStore provider
,I/wpa_supplicant( 2090): nl80211: Received scan results (10 BSSes)
I/wpa_supplicant( 2090): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 2090): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 2090): Trying to associate with  'G700'
I/wpa_supplicant( 2090): Re-associate with C0.AA.48
I/wpa_supplicant( 2090): wlan0: State: SCANNING -> ASSOCIATING
D/WifiMonitor( 1018): didn't find BSSID Trying to associate with SSID 'NG700'
I/wpa_supplicant( 2090): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,W/libprocessgroup( 1018): failed to open /acct/uid_10101/pid_5362/cgroup.procs: No such file or directory
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6336): MountEmulatedStorage()
E/Zygote  ( 6336): v2
I/libpersona( 6336): KNOX_SDCARD checking this for 1000
I/libpersona( 6336): KNOX_SDCARD not a persona
,I/SELinux ( 6336): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6336 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 6336): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6336): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6336): TimaSignature is unavailable
,D/ActivityThread( 6336): Added TimaKeyStore provider
,I/ActivityManager( 1018): Killing 5139:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,E/wpa_supplicant( 2090): Cmd 35605 not handled
,I/wpa_supplicant( 2090): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 2090): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 2090): Associated with C0.AA.48
I/wpa_supplicant( 2090): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 2090): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 2090): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, true
D/Tethering( 1018): interfaceLinkStateChanged wlan0, true
D/Tethering( 1018): interfaceStatusChanged wlan0, true
,E/Tethering( 1018): No numeric data
D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
I/wpa_supplicant( 2090): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1018): clearTetheredNotification()
I/wpa_supplicant( 2090): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 2090): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 2090): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 2090): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2090): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2090): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 2090): Blacklist: Clear (temp) 
I/wpa_supplicant( 2090): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,V/NetworkStats( 1018): performPollLocked(flags=0x1),
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, true
D/Tethering( 1018): interfaceLinkStateChanged wlan0, true
D/Tethering( 1018): interfaceStatusChanged wlan0, true
D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,D/HotspotTile( 1179): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1179): updateTetherState():false, false
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked() took 8ms
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/WifiNative-wlan0( 1018): callSECApiVoid - ID [50]
,E/WifiConfigStore( 1018): setLastSelectedConfiguration -1
,D/ConnectivityService( 1018): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1018): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/DIAGMON_AGENT( 6336): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,D/CommandListener(  278): Setting iface cfg
,E/WifiStateMachine( 1018): Start Dhcp Watchdog 2
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1018): mCursor = null
,I/ActivityManager( 1018): Killing 4151:com.sec.spp.push/u0a35 (adj 15): empty #31
,E/WifiNative-wlan0( 1018): do suspend false
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,I/DIAGMON_AGENT( 6336): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0,
,E/SQLiteLog( 1734): (10) POSIX Error : 11 SQLite Error : 3850
,I/DIAGMON_AGENT( 6336): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6336): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE,
,I/DIAGMON_AGENT( 6336): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6336): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6336): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6352 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 5344:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
E/Zygote  ( 6352): MountEmulatedStorage()
,E/Zygote  ( 6352): v2,
I/libpersona( 6352): KNOX_SDCARD checking this for 10009
I/libpersona( 6352): KNOX_SDCARD not a persona
,I/SELinux ( 6352): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6352): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6352): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1018): failed to open /acct/uid_10044/pid_5139/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10035/pid_4151/cgroup.procs: No such file or directory
,V/AlarmManager( 1018): waitForAlarm result :4
,D/TimaKeyStoreProvider( 6352): TimaSignature is unavailable
,D/ActivityThread( 6352): Added TimaKeyStore provider
,I/ActivityManager( 1018): Killing 5435:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,I/KLMS-2.5.183: ( 3622): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 05 01:39:28 GMT+01:00 2016,
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
E/dhcpcd  ( 6368): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6368): version 5.5.6 starting
,E/dhcpcd  ( 6368): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/KLMS-2.5.183: ( 3622): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.183: ( 3622): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3622): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3622): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3622): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3622): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,E/Zygote  ( 6374): MountEmulatedStorage()
,E/Zygote  ( 6374): v2
I/libpersona( 6374): KNOX_SDCARD checking this for 10034
I/libpersona( 6374): KNOX_SDCARD not a persona,
,I/SELinux ( 6374): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1018): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6374 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.5.183: ( 3622): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3622): StateImplV2(): networkChangeListener().END
,I/SELinux ( 6374): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6374): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3622): KLMSIntentService(): onDestroy()
,I/dhcpcd  ( 6368): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6368): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6368): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 6368): bssid match,
I/dhcpcd  ( 6368): wlan0: rebinding lease of 192.168.1.137
,D/TimaKeyStoreProvider( 6374): TimaSignature is unavailable
,D/ActivityThread( 6374): Added TimaKeyStore provider
,I/SO_AGENT( 6374): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,I/DBG_POLICYDM( 5842): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5842): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/SA      ( 6115): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,I/SA      ( 6115): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 6115): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6115): [SLFUCHKMGR] constructor called
,I/DBG_POLICYDM( 5842): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 5842): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5842): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,I/SA      ( 6115): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6115): [OR] == isSIMCardReady false ==
,I/SA      ( 6115): [SCU] == networkStateCheck == false
I/SA      ( 6115): [OR] onReceive END
,I/ActivityManager( 1018): Killing 5764:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,V/DownloadManager( 1229): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1562): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1562): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1562): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1562): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1562): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1562): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1562): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6393): MountEmulatedStorage(),
E/Zygote  ( 6393): v2
I/libpersona( 6393): KNOX_SDCARD checking this for 10125
I/libpersona( 6393): KNOX_SDCARD not a persona
I/SELinux ( 6393): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6393 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 6393): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6393): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6393): TimaSignature is unavailable
,D/ActivityThread( 6393): Added TimaKeyStore provider
,W/ResourcesManager( 6393): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6393): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6393): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/libprocessgroup( 1018): failed to open /acct/uid_10035/pid_5344/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10015/pid_5435/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10100/pid_5764/cgroup.procs: No such file or directory
,D/QuickConnect( 6393): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6393): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6393): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/Zygote  ( 6408): MountEmulatedStorage(),
E/Zygote  ( 6408): v2
I/libpersona( 6408): KNOX_SDCARD checking this for 10145
I/libpersona( 6408): KNOX_SDCARD not a persona,
,I/SELinux ( 6408): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6408 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 5797:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,I/SELinux ( 6408): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6408): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6408): TimaSignature is unavailable
D/ActivityThread( 6408): Added TimaKeyStore provider
,I/art     (  304): Explicit concurrent mark sweep GC freed 8701(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 698us total 32.546ms
,W/ResourcesManager( 6408): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6408): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6408): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6408): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6408): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 654us total 18.589ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 718us total 20.045ms
,W/libprocessgroup( 1018): failed to open /acct/uid_10091/pid_5797/cgroup.procs: No such file or directory
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/BadgeProvider( 5953): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/BadgeProvider( 5953): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5953): sendNotify, [notify] : null
D/BadgeProvider( 5953): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5953): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5953): update, [UpdateCount] : 1
D/Launcher.Model( 1486): reloadBadges entered.
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6431): MountEmulatedStorage()
E/Zygote  ( 6431): v2
I/libpersona( 6431): KNOX_SDCARD checking this for 1000
I/libpersona( 6431): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6431 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 6431): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6431): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6431): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6431): TimaSignature is unavailable
,D/ActivityThread( 6431): Added TimaKeyStore provider
,D/SecurityLogAgent( 6431): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6431): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6431): StateMachine : Current State = 1
,D/SecurityLogAgent( 6431): StateMachine : Changed Current State = 1
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6447): MountEmulatedStorage(),
E/Zygote  ( 6447): v2,
I/libpersona( 6447): KNOX_SDCARD checking this for 10159
I/libpersona( 6447): KNOX_SDCARD not a persona
,I/SELinux ( 6447): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6447): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/ActivityManager( 1018): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6447 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 6447): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 5444:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 59969(3MB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 27MB/40MB, paused 3.089ms total 179.103ms
,D/TimaKeyStoreProvider( 6447): TimaSignature is unavailable
,D/ActivityThread( 6447): Added TimaKeyStore provider
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,I/ActivityManager( 1018): Killing 5827:com.samsung.helphub/1000 (adj 15): empty #31
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,I/ActivityManager( 1018): Killing 5898:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/iu.Environment( 1934): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1934): num queued entries: 0
,I/iu.UploadsManager( 1934): num updated entries: 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
I/iu.SyncManager( 1934): NEXT; no task
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1934): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_10032/pid_5444/cgroup.procs: No such file or directory
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5827/cgroup.procs: No such file or directory
,E/Zygote  ( 6466): MountEmulatedStorage()
,E/Zygote  ( 6466): v2
I/libpersona( 6466): KNOX_SDCARD checking this for 10035
I/libpersona( 6466): KNOX_SDCARD not a persona
,I/SELinux ( 6466): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6466 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,W/libprocessgroup( 1018): failed to open /acct/uid_10152/pid_5898/cgroup.procs: No such file or directory
,I/SELinux ( 6466): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
E/SELinux ( 6466): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 6276): connection state changed from UNKNOWN to DISCONNECTED
,D/TimaKeyStoreProvider( 6466): TimaSignature is unavailable
,D/ActivityThread( 6466): Added TimaKeyStore provider,
,E/SPPClientService( 6466): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 6466): [PushClientApplication] Push log off : This is Ship build version
E/SPPClientService( 6466): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6466): [SystemStateMoniter] Current Time : 90975
,E/SPPClientService( 6466): [SystemStateMoniter] No Connect : true
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/SPPClientService( 6466): PushLog.txt file is not deleted.
,D/SPPClientService( 6466): PushLog.txt file is not deleted.
,D/SPPClientService( 6466): ============PushLog. stop!
,E/Zygote  ( 6483): MountEmulatedStorage(),
I/ActivityManager( 1018): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6483 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6483): v2
,I/libpersona( 6483): KNOX_SDCARD checking this for 10113
I/libpersona( 6483): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Killing 5919:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
I/SELinux ( 6483): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SELinux ( 6483): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6483): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/SPPClientService( 6466): [[SystemStateMonitorService]] No Active Internet
,D/TimaKeyStoreProvider( 6483): TimaSignature is unavailable
,D/ActivityThread( 6483): Added TimaKeyStore provider
,I/GAv4    ( 6483): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6483):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6483):   adb logcat -s GAv4
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6483): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6483): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6483): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/GAv4    ( 6483): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/ContextImpl( 6483): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup( 1018): failed to open /acct/uid_10156/pid_5919/cgroup.procs: No such file or directory
,E/SMD     (  288): DCD OFF
,W/GAv4    ( 6483): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6483): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/dhcpcd  ( 6368): wlan0: acknowledged 192.168.1.137 from 192.168.1.1
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/dhcpcd  ( 6368): wlan0: leased 192.168.1.137 for 86400 seconds
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6483): Loading com.google.android.webview version 44.0.2403.117 (code 240311700),
,I/LibraryLoader( 6483): Time to load native libraries: 18 ms (timestamps 1541-1559)
,I/LibraryLoader( 6483): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6483): Binding Chromium to main looper Looper (main, tid 1) {20ace34e},
I/LibraryLoader( 6483): Expected native library version number "",actual native library version number ""
I/chromium( 6483): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6483): Initializing chromium process, singleProcess=true,
,W/art     ( 6483): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6483): ApplicationContext is null in ApplicationStatus
,W/chromium( 6483): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6483): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6483): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6483): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6483): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6483): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6483): Local Branch: 
I/Adreno-EGL( 6483): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
,I/Adreno-EGL( 6483): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6483):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/NSApplication( 6483): Starting up...
,W/AudioManagerAndroid( 6483): Requires BLUETOOTH permission
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6561): MountEmulatedStorage()
I/libpersona( 6561): KNOX_SDCARD checking this for 10081
E/Zygote  ( 6561): v2
I/libpersona( 6561): KNOX_SDCARD not a persona
I/SELinux ( 6561): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6561 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6561): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6561): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 5516:com.android.vending/u0a28 (adj 15): empty #31
E/WifiNative-wlan0( 1018): do suspend true
,D/TimaKeyStoreProvider( 6561): TimaSignature is unavailable
,D/ActivityThread( 6561): Added TimaKeyStore provider
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 1018): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1018): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiNative-wlan0( 1018): callSECApiInt - ID [210]
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/ConnectivityService( 1018): updateNetworkInfo()
,D/ConnectivityService( 1018): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1018): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 1018): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1018): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 1018): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
D/ConnectivityService( 1018): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
E/ConnectivityService( 1018): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1018): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 1018): LTETest block dns file not exists
,D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
,W/ActivityManager( 1018): Failed to clear dns cache for: com.android.vending
,E/WifiStateMachine( 1018): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,E/ConnectivityService( 1018): updateNetworkInfo()
E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1018): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1018): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
,D/ConnectivityService( 1018):    accepting network in place of null
D/WIFI_P2P( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/TelephonyNetworkFactory( 1467): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1467): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/EnterpriseController(  278): uids 1000
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/CSLegacyTypeTracker( 1018): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 1000
D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/CSLegacyTypeTracker( 1018): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1018): mBoosterFLAG : 0
I/WifiTrafficPoller( 1018): current booster mode : FullMode
,D/WifiNative-wlan0( 1018): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WIFI    ( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/ConnectivityService( 1018): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService( 1018): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false,
,D/ConnectivityManager.CallbackHandler( 1179): CM callback handler got msg 524290
D/ConnectivityService( 1018): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,fe80::7ef9:eff:fe51:1823/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1179): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1179): CM callback handler got msg 524295
,D/Tethering( 1018): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1018): MasterInitialState.processMessage what=3
,V/NetworkStats( 1018): updateIfacesLocked()
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked() took 5ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,V/NetworkStats( 1018): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1179): EthernetConnected: false
D/StatusBar.NetworkController( 1179): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1179): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1179): updateDataNetType()
D/StatusBar.NetworkController( 1179): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1179): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1179): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false,
D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700",
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/System.out( 1018): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/WaitQueueForNetworkActivate( 6175): notifyNetworkActivated
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jan 2016 00:39:30 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1451954370062], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1451954370042]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Validated
D/ConnectivityService( 1018): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1018): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1018): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1018): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
W/libprocessgroup( 1018): failed to open /acct/uid_10028/pid_5516/cgroup.procs: No such file or directory
,D/ConnectivityManager.CallbackHandler( 1179): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1179): EthernetConnected: false
D/StatusBar.NetworkController( 1179): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1179): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1179): updateDataNetType()
D/StatusBar.NetworkController( 1179): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1179): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1179): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ContextImpl( 6175): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 6175): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6175): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6175): exit::IDLE
D/InitializeManagerStateMachine( 6175): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6175): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6175): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6175): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6175): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6175): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6175): entry::SUCCESS
D/hcjo    ( 6175): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3586): Starting #10
D/hcjo    ( 6175): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6175): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,I/Hs20UtilService( 3586): Message received 5007
,D/InitializeManagerStateMachine( 6175): exit::SUCCESS
D/InitializeManagerStateMachine( 6175): entry::IDLE
,D/NearbySettings( 1325): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1325): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1325): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1325): MountReceiver.onReceive - Keep current state
,I/ActivityManager( 1018): Killing 5779:com.android.mms/u0a46 (adj 15): empty #31
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3586): Starting #11
,D/NearbySettings( 1325): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1325): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 3586): Message received 5007
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1325): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1325): DMSUtil.isNetworkConnected - flag-null, state-null
,I/Hs20UtilService( 3586): Starting #12
,I/Hs20UtilService( 3586): Message received 5007
,I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1325): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1325): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1325): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3586): Starting #13
,I/Hs20UtilService( 3586): Message received 5007
,D/NearbySettings( 1325): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1325): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1018): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityEnabledState,
D/SecContentProvider2( 1018): mCursor = null
D/SecContentProvider2( 1018): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1018): mCursor = null
D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityXOffset
D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityYOffset
D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastEnabledState,
D/SecContentProvider2( 1018): mCursor = null
D/SecContentProvider2( 1018): uri = 15 selection = getToastShowPackageNameState
D/SecContentProvider2( 1018): mCursor = null
,D/CountryDetector( 1018): No listener is left,
,I/SurfaceFlinger(  257): id=15 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 1018): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018,
,D/SRIB_DCS( 1179): log_dcs ThreadedRenderer::initialize entered! 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6590): MountEmulatedStorage()
E/Zygote  ( 6590): v2
,I/libpersona( 6590): KNOX_SDCARD checking this for 10075
I/libpersona( 6590): KNOX_SDCARD not a persona
I/SELinux ( 6590): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6590 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6590): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6590): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1018): failed to open /acct/uid_10046/pid_5779/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6590): TimaSignature is unavailable
,D/ActivityThread( 6590): Added TimaKeyStore provider
,D/PackageManager( 1018): [MSG] MCS_UNBIND
,I/ActivityManager( 1018): Killing 5967:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3005): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/NetworkMonitor( 5020): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil( 5808): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5808): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5808): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5808): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1018): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=22
,I/splitIntent( 1018): base  index=22, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1018): other index=24, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,V/MusicLeanback( 5020): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/DIAGMON_AGENT( 6336): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 6336): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6336): ./extraInfo: "NG700"
I/DIAGMON_AGENT( 6336): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/DBG_POLICYDM( 5842): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5842): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5842): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5842): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5842): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5842): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/FOTA_Client( 6352): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 6352): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/KLMS-2.5.183: ( 3622): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 05 01:39:30 GMT+01:00 2016
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3622): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.183: ( 3622): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3622): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,I/KLMS-2.5.183: ( 3622): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.183: ( 3622): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3622): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.183: ( 3622): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1018): failed to open /acct/uid_10047/pid_5967/cgroup.procs: No such file or directory
,I/KLMS-2.5.183: ( 3622): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.183: ( 3622): NetworkChangeOperations(): uploadRequestLog().START 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/KLMS-2.5.183: ( 3622): NetworkChangeOperations(): uploadRequestLog().END 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,I/KLMS-2.5.183: ( 3622): StateImplV2(): networkChangeListener().END
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/KLMS-2.5.183: ( 3622): KLMSIntentService(): onDestroy()
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5842): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5842): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5842): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5842): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
I/SA      ( 6115): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,I/SA      ( 6115): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6115): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6115): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6115): [OR] == isSIMCardReady false ==
,I/SA      ( 6115): [SCU] == networkStateCheck == true
I/SA      ( 6115): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 6115): isChinaCountryCode : false
I/SA      ( 6115): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6115): [OR] == networkStateCheck true ==
,I/SA      ( 6115): [OR] GetMyCountryZoneTask
,I/SA      ( 6115): [OR] onReceive END
,V/DownloadManager( 1229): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
I/DBG_POLICYDM( 5842): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,I/SA      ( 6115): [SRS] prepareGetMyCountryZone
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
W/GAV2    ( 6590): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/accuweather( 1562): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SA      ( 6115): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6115): [SSP] query invoked
,I/BooksApp( 6590): Created application version: 3.6.9 (30609)
,D/daemonapp( 1290): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,I/DBG_POLICYDM( 5842): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1018): mCursor = null
,D/accuweather( 1562): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1562): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
I/DBG_POLICYDM( 5842): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
D/accuweather( 1562): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1562): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
I/DBG_POLICYDM( 5842): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5842): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
I/DBG_POLICYDM( 5842): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5842): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5842): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/accuweather( 1562): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5842): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
I/SA      ( 6115): [TPMU] GetMccFromDB : null
I/SA      ( 6115): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6115): [TPM] isNoProxy(default) : true
,D/accuweather( 1562): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/DBG_POLICYDM( 5842): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,D/QuickConnect( 6393): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6393): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6393): PeriphStartReceiver.onReceive - no need to start
,E/DBG_POLICYDM( 5842): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,E/File    ( 6115): fail readDirectory() errno=2
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 6431): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6431): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6431): StateMachine : Current State = 1
,I/DBG_POLICYDM( 5842): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
D/SecurityLogAgent( 6431): StateMachine : Changed Current State = 1
,I/DBG_POLICYDM( 5842): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10012
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/iu.Environment( 1934): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1934): num queued entries: 0
,I/iu.UploadsManager( 1934): num updated entries: 0
,I/iu.SyncManager( 1934): NEXT; no task
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/ChimeraCfgMgr( 1934): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1934): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,I/BooksSync( 6590): Starting books sync for 61035162, extras: ade
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/SPPClientService( 6466): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 6466): [SystemStateMoniter] Current Time : 92773
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SPPClientService( 6466): [SystemStateMoniter] No Connect : false
,I/System.out( 6276): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 6276): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 6276): (HTTPLog)-Static: isShipBuild true
I/System.out( 6276): (HTTPLog)-Thread-1087-611052187: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6276): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10104
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10104
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ConnectivityService( 1018): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,I/System.out( 6276): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/hcjo    ( 6175): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6175): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6175): exit::IDLE
D/InitializeManagerStateMachine( 6175): entry::NETWORK_CHECK
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/InitializeManagerStateMachine( 6175): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6175): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6175): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6175): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6175): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6175): entry::SUCCESS
D/hcjo    ( 6175): AutoUpdateManager:INITCHECK:onInitializeSuccess
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/hcjo    ( 6175): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6175): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6175): exit::SUCCESS
D/InitializeManagerStateMachine( 6175): entry::IDLE
,I/art     ( 1734): Explicit concurrent mark sweep GC freed 11279(600KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 10MB/17MB, paused 1.085ms total 64.181ms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Babel   ( 6276): connection state changed from DISCONNECTED to CONNECTED
,I/GLSUser ( 1734): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1734): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1734): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1734): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/Kids    ( 1934): [AccountUtils] Account not ready
W/Kids    ( 1934): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1934): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1934): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1934): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1934): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1934): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1934): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1934): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1934): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1934): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1934): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1934): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/GCM     ( 1734): Connected
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,I/PowerManagerService( 1018): [PWL] Off : 15s ago
I/PowerManagerService( 1018): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1018): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1934, ws=null) (elapsedTime=57164)
I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=1018, ws=WorkSource{10075}) (elapsedTime=751)
,D/GCM     ( 1734): Message class com.google.f.a.a.p
,E/SQLiteLog( 6590): (284) automatic index on view_volumes(volume_id)
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/BooksConfig( 6590): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1734): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1734): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1734): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1734): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice,
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/SA      ( 6115): [RC New] Execute method=[GET] start
,I/GLSUser ( 1734): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1734): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1734): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1734): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6590): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,I/SA      ( 6115): [RC New] Security=[true]
,I/System.out( 6115): Thread-1055(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6115): Thread-1055(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6115): Thread-1055(ApacheHTTPLog):isShipBuild true
I/System.out( 6115): Thread-1055(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6115): Thread-1055(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
E/BooksSync( 6590): Soft error
E/BooksSync( 6590): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6590): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6590): Sync error
E/BooksSync( 6590): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6590): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
D/EnterpriseController(  278): uids 10041
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10041
I/BooksSync( 6590): Finished books sync
D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 63753, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,I/ActivityManager( 1018): Killing 5989:com.wsomacp/u0a25 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10025/pid_5989/cgroup.procs: No such file or directory
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 6193): BLE supported!!
I/jxcore-log( 6193): 
,I/SA      ( 6115): [RC New] [v2liruge] api execute + 663
,I/SA      ( 6115): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 6115): AsyncTask #1 calls detatch()
,I/SA      ( 6115): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6115): [OCP] update openData : PL
,I/SA      ( 6115): [TPMU] getNetworkMcc : 
,I/SA      ( 6115): [SCU] saveMccToPreferece Start
,I/SA      ( 6115): [SCU] RegionMCC : 260
,I/SA      ( 6115): [SSP] query invoked
,I/SA      ( 6115): [TPMU] GetMccFromDB : null
,I/SA      ( 6115): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6115): [SCU] saveMccToPreferece End
,I/SA      ( 6115): [RC New] executeRequest [v2liruge] end. 729,
I/SA      ( 6115): [RC New] Execute end
I/SA      ( 6115): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6115): [OR] GetMyCountryZoneTask Success
,E/SMD     (  288): DCD OFF
,I/dhcpcd  ( 6368): wlan0: sending IPv6 Router Solicitation
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SurfaceFlinger(  257): id=15 Removed Uoast (8/9)
,D/PowerManagerService( 1018): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1018) eventTime = 95684
,D/PowerManagerService( 1018): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018 (0x0)
,D/PowerManagerService( 1018): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1018, ws=WorkSource{10054}) (elapsedTime=3493)
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4263, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{35a7c29b u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,E/SMD     (  288): DCD OFF
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5808): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5808): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5808): [GetString-S]
,I/ReactiveServiceManager( 5808): Supported : 1
,D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 12
,D/QSEECOMAPI: ( 1018): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1018): QSEECom_shutdown_app, app_id = 12
,E/terrier ( 1018): handleString: Failed to handle string(-4)
E/terrier ( 1018): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5808): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5808): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5808): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5808): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5808): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5808): [ensureRegistration] - No Samsung account
,D/SSRM:n  ( 1018): SIOP:: AP = 330
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 43747(2MB) AllocSpace objects, 6(136KB) LOS objects, 33% free, 27MB/40MB, paused 2.572ms total 153.194ms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 6590): Thread[GAThread,5,main]: No campaign data found.
,I/dhcpcd  ( 6368): wlan0: sending IPv6 Router Solicitation
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0,
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6652): MountEmulatedStorage(),
E/Zygote  ( 6652): v2
I/libpersona( 6652): KNOX_SDCARD checking this for 10028
I/libpersona( 6652): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6652 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6652): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6652): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6652): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6652): TimaSignature is unavailable
,D/ActivityThread( 6652): Added TimaKeyStore provider
,D/Finsky  ( 6652): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6175): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6175): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6175): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6175): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 6175): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6175): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6175): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 6175): entry::IDLE
,D/Finsky  ( 6652): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/Settings( 6652): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6652): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 6652): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6652): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 6652): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6652): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/dhcpcd  ( 6368): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6368): wlan0: no IPv6 Routers available
,V/Finsky  ( 6652): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1734): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1734): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1734): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1734): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.android.vending
,D/Finsky  ( 6652): [1140] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,D/Finsky  ( 6652): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6652): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6652): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager( 1018): Killing 6005:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1734): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1734): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1734): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1734): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6652): [1140] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6175): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 6175): exit::IDLE
D/PreloadUpdateManagerStateMachine( 6175): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6175): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6175): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6175): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6175): entry::IDLE
,W/libprocessgroup( 1018): failed to open /acct/uid_10053/pid_6005/cgroup.procs: No such file or directory
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/Finsky  ( 6652): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1734): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1734): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1734): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1734): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  288): DCD OFF
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6652): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1734): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1734): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1734): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1734): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1734): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1734): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1734): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1734): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6652): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1734): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1734): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1734): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1734): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6652): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6652): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6652): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6652): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,D/DeviceConnectionService( 1655): client connected with version: 7571000
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4268, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1018): stay LED for charging
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{20115fec u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,V/AlarmManager( 1018): waitForAlarm result :4
,D/SSRM:n  ( 1018): SIOP:: AP = 310
,I/PowerManagerService( 1018): [PWL] Off : 30s ago
,E/Watchdog( 1018): !@Sync 3
,I/Atfwd_Sendcmd(  315): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  315): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4272, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/FactoryTest( 5592): Not factory mode
,D/FactoryTest( 5592): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5592): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5592): still no open session command from host, so toast
W/ContextImpl( 5592): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5592): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
I/Timeline( 5592): Timeline: Activity_launch_request id:com.android.settings time:116178
,E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
,I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1018): mDVFSHelper.acquire()
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 6193
E/MTPRx   ( 5592): started activity for popup
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 5592): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5592): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5592): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5592): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5592): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5592): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SettingsReceiverActivity( 5592): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1018): Focused application set to: xxxx
,D/InputDispatcher( 1018): Focus entered window: 6193
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService( 1018): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@bbc0788 attribute=null, token = android.os.BinderProxy@8197796
,D/SettingsReceiverActivity( 5592): dev.kiessupport is : TRUE
,D/PhoneWindow( 5592): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5592): *FMB* installDecor flags : 8388610
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,V/ActivityThread( 6193): updateVisibility : ActivityRecord{1143b0b5 token=android.os.BinderProxy@2cc7bb9f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/Timeline( 6193): Timeline: Activity_idle id: android.os.BinderProxy@2cc7bb9f time:116349
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 300
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 1
,W/ActivityManager( 1018): mDVFSHelper.release()
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8,
,V/AlarmManager( 1018): waitForAlarm result :4
,V/AlarmManager( 1018): ___SyncScheduler (v3) ACTIVATED___
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK,
V/AlarmManagerEXT( 1018): <AppSync3 Whitelist>
D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
V/AlarmManagerEXT( 1018): (AppSync) ### 0 added ###,
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.sync.FitnessSyncAdapterService; callingUser = 0; userId(target) = 0
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1734): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1734): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1734): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1734): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6652): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6652): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6652): [1] 5.onFinished: Scheduling replication attempt 3.
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4275, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1018): stay LED for charging
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,I/PowerManagerService( 1018): [PWL] Off : 50s ago
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4276, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,E/Watchdog( 1018): !@Sync 4,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 3,
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1734): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1734): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1734): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1734): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6652): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6652): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6652): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4277, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :4
,I/PowerManagerService( 1018): [PWL] Off : 75s ago
,E/SMD     (  288): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4278, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 4
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 37305(2MB) AllocSpace objects, 30(480KB) LOS objects, 33% free, 27MB/41MB, paused 2.550ms total 141.890ms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1734): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1734): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1734): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1734): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6652): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6652): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6652): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4280, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 280
,E/Watchdog( 1018): !@Sync 5
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,I/BooksSync( 6590): Starting books sync for 61035162, extras: ade
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksConfig( 6590): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1734): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1734): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1734): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1734): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1734): Explicit concurrent mark sweep GC freed 29285(1720KB) AllocSpace objects, 6(216KB) LOS objects, 40% free, 10MB/17MB, paused 1.517ms total 58.730ms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1734): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1734): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1734): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1734): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6590): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6590): Soft error
E/BooksSync( 6590): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6590): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6590): Sync error
E/BooksSync( 6590): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6590): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6590): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 155511, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,I/PowerManagerService( 1018): [PWL] Off : 105s ago
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1734): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1734): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1734): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1734): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6652): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6652): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6652): [1] 5.onFinished: Giving up after 6 failures.
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4281, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/Watchdog( 1018): !@Sync 6
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1734): Vacuum at: now=1451954481877 tag=VacuumService
,I/GoogleURLConnFactory( 1734): Using platform SSLCertificateSocketFactory
,W/Uploader( 1734): No account for auth token provided
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1734): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1734): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1734): (HTTPLog)-Static: isShipBuild true
I/System.out( 1734): (HTTPLog)-Thread-207-661843767: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1734): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10012
,I/System.out( 1734): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1734): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1734, getuid(): 10012
,I/qtaguid ( 1734): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1734, getuid(): 10012
,W/Uploader( 1734): No account for auth token provided
,I/System.out( 1734): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1734): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1734, getuid(): 10012
,W/Uploader( 1734): No account for auth token provided
,I/System.out( 1734): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1734): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1734, getuid(): 10012
,W/Uploader( 1734): No account for auth token provided
,I/System.out( 1734): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1734): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1734, getuid(): 10012
,W/Uploader( 1734):  no longer exists, so no auth token.
,I/System.out( 1734): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1734): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1734, getuid(): 10012
,W/Uploader( 1734): No account for auth token provided
,I/System.out( 1734): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1734): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1734, getuid(): 10012
,E/SQLiteLog( 1734): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,I/Atfwd_Sendcmd(  315): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  315): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 140s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4282, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/Watchdog( 1018): !@Sync 7
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4280, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1018): stay LED for charging
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2642): Disconnected process message: 10,
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4282, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1018): [PWL] Off : 180s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 8
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4281, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1018): Plugged,
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1018): !@Sync 9
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4282, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 225s ago
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4281, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,I/BooksSync( 6590): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6590): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1734): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1734): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1734): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1734): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true,
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1734): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1734): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1734): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1734): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6590): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6590): Soft error
E/BooksSync( 6590): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6590): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6590): Sync error
E/BooksSync( 6590): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6590): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6590): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 307539, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1018): initializing...
,I/TLC_TIMA_PKM_initialize( 1018): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1018): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1018): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1018): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1018): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1018): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1018): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x80080,
D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 13
,I/TZ: qc_tlc_communication( 1018): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1018): Trustlet response is completed
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4278, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1018): !@Sync 10
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/Atfwd_Sendcmd(  315): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  315): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF
,I/jxcore-log( 6193): Connected to the server!
I/jxcore-log( 6193): 
,I/chromium( 6193): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4282, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged,
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 1018): waitForAlarm result :4
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 11
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 275s ago
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :8
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 12
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1734): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1734): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1734): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1734): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
,D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,W/GLSActivity( 1734): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1734): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1734): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1734): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1734): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1734): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1734): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,E/PlayEventLogger( 6652): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6652): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6652): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6652): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6652): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6652): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6652): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 6652): Ignoring header User-Agent because its value was null.
,I/System.out( 6652): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6652): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 6652): (HTTPLog)-Static: isShipBuild true
I/System.out( 6652): (HTTPLog)-Thread-1159-123650068: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6652): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10028
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10028
,I/System.out( 6652): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1018): [PWL] Off : 330s ago
,E/Watchdog( 1018): !@Sync 13
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 14
,I/Atfwd_Sendcmd(  315): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  315): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/jxcore-log( 6193): --- start :testFindPeers.js---
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): testFindPeers created [object Object]
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): serverPort is 8876
I/jxcore-log( 6193): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): start: Peer ID: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT3690
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6193): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6193): initialize: My bluetooth address is 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6193): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3690","ra":"7C:F9:0E:51:18:22"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): startListeningForIncomingConnections: Starting...
,D/BluetoothSocket( 6193): bindListen(): myUserId = 0
,W/BluetoothAdapter( 6193): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6193): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[111]}
,D/BluetoothSocket( 6193): bindListen(), new LocalSocket 
D/BluetoothSocket( 6193): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6193): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@592af50
,D/BluetoothSocket( 6193): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): start: OK
I/io.jxcore.node.ConnectionHelper( 6193): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): start: Peer ID: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT3690
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6193): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3690","ra":"7C:F9:0E:51:18:22"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6193): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): start: {"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3690","ra":"7C:F9:0E:51:18:22"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6193): start: Identity string: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3690","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 1018): InactiveState{ what=139292 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 1018): P2pEnabledState add service
E/SMD     (  288): DCD OFF
,D/WifiP2pService( 1018): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6193): start: OK
,I/jxcore-log( 6193): StartBroadcasting started ok
I/jxcore-log( 6193): 
I/chromium( 6193): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6193): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onWifiStateChanged: State changed to 2
I/io.jxcore.node.ConnectionHelper( 6193): onDiscoveryManagerStateChanged: RUNNING
,D/WifiP2pService( 1018): InactiveState{ what=139265 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6193): Local service added successfully
D/WifiStateMachine( 1018): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1018): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1018): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2090): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1018): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 44.5A.07 p2p_dev_addr=44.5A.07 pri_dev_type=10-0050F204-5  '23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1018): P2pEnabledState{ what=147477 },
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 2 device(s) discovered
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 2 device(s) discovered
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 1018): InactiveState{ what=139301 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1018): P2pEnabledState add service request
,D/WifiP2pManager( 6193): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): Service request added successfully
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 0A.75.42 p2p_dev_addr=0A.75.42 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiDisplayController( 1018): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 4 device(s) discovered
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 4 device(s) discovered
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiP2pService( 1018): InactiveState{ what=139310 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1018): P2pEnabledState discover services
,D/WifiService( 1018): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1018): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1018): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2090): USE_NETWORK : USE_NETWORK OFF
I/wpa_supplicant( 2090): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): Service discovery started successfully
,I/wpa_supplicant( 2090): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 2090): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1779","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
,I/io.jxcore.node.ConnectionHelper( 6193): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 6193): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779] is available
,I/jxcore-log( 6193): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT1779","peerAvailable":true}]
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): weAreDoneNow
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): done, now sending data to server
I/jxcore-log( 6193): 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4276, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
,I/MotionRecognitionService( 1018): Plugged,
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6753","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
,I/io.jxcore.node.ConnectionHelper( 6193): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], Bluetooth address: 08:EC:A9:50:76:27, device name: , device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 6193): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753] is available
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6172","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
,I/io.jxcore.node.ConnectionHelper( 6193): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 6193): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172] is available
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4282, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 390s ago
,E/Watchdog( 1018): !@Sync 15
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): setState: RESTARTING
,D/WifiP2pService( 1018): InactiveState{ what=139268 }
,I/wpa_supplicant( 2090): P2P-FIND-STOPPED 
,D/WifiP2pService( 1018): InactiveState{ what=147493 },
D/WifiP2pService( 1018): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1018): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): Start timer timeout, starting now...
,D/WifiP2pService( 1018): InactiveState{ what=139265 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139265 }
D/WifiService( 1018): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1018): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1018): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
,D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2090): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1018): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 2090): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 2090): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1018): InactiveState{ what=147477 },
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=147477 },
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 7 device(s) discovered,
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: true
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779],
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): restart: Restarting...
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 7 device(s) discovered
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1018): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: true
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 7 device(s) discovered
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1018): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1018): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1018): P2pEnabledState clear service request
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: true
D/WifiP2pService( 1018): InactiveState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
D/WifiP2pService( 1018): P2pEnabledState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1018): P2pEnabledState add service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/WifiP2pManager( 6193): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): Service request added successfully
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 44.5A.07 p2p_dev_addr=44.5A.07 pri_dev_type=10-0050F204-5  '23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 freq=2437,
D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 },
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 7 device(s) discovered
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1018): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: true
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiP2pService( 1018): InactiveState{ what=139310 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1018): P2pEnabledState discover services
,D/WifiService( 1018): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1018): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1018): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2090): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): Service discovery started successfully,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 2090): p2p0: P2P: Reject scan trigger since one is already pending
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/bootchecker(  312): bootchecker wake up!!
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 8 device(s) discovered
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1018): DefaultState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: true
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1018): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 8 device(s) discovered
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: true
D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT706","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
,I/io.jxcore.node.ConnectionHelper( 6193): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 6193): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706] is available
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6440","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
I/io.jxcore.node.ConnectionHelper( 6193): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 6193): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440] is available
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4271, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate,
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1018): InactiveState{ what=147477 },
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 },
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,E/SMD     (  288): DCD OFF,
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1018): InactiveState{ what=147477 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): InactiveState{ what=139283 },
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 9 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiDisplayController( 1018): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172], add/update: true
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, de,vcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): restart: Restarting...
,D/WifiP2pService( 1018): InactiveState{ what=139307 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139307 }
D/WifiP2pService( 1018): P2pEnabledState clear service request
,D/WifiP2pService( 1018): InactiveState{ what=139301 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 1018): P2pEnabledState add service request
D/WifiP2pManager( 6193): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): Service request added successfully
,E/SMD     (  288): DCD OFF
,D/WifiP2pService( 1018): InactiveState{ what=139310 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1018): P2pEnabledState discover services
,D/WifiService( 1018): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1018): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1018): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 2090): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): Service discovery started successfully
,E/Watchdog( 1018): !@Sync 16
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4275, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging,
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/WifiP2pService( 1018): InactiveState{ what=147494 },
D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2787","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
I/io.jxcore.node.ConnectionHelper( 6193): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,D/io.jxcore.node.ConnectionHelper( 6193): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787] is available
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6172","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
,I/io.jxcore.node.ConnectionHelper( 6193): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 6193): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172] already in the list, will not add again
,E/SMD     (  288): DCD OFF
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT706","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
I/io.jxcore.node.ConnectionHelper( 6193): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 6193): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT177","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1018): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
I/io.jxcore.node.ConnectionHelper( 6193): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 6193): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177] is available
,D/WifiP2pService( 1018): InactiveState{ what=147494 },
,D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6440","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440],
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
I/io.jxcore.node.ConnectionHelper( 6193): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 6193): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440] already in the list, will not add again
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
,D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.,
,D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1018): DefaultState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
,D/WifiDisplayController( 1018): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true,
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): restart: Restarting...
,D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1018): DefaultState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/WifiP2pService( 1018): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/WifiP2pService( 1018): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1018): P2pEnabledState clear service request
D/WifiP2pManager( 6193): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
D/WifiP2pService( 1018): InactiveState{ what=139301 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1018): P2pEnabledState add service request
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): Service request added successfully
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,D/WifiP2pService( 1018): InactiveState{ what=139310 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1018): P2pEnabledState discover services
,D/WifiService( 1018): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1018): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1018): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 2090): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): Service discovery started successfully,
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1018): InactiveState{ what=147477 },
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6440","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
I/io.jxcore.node.ConnectionHelper( 6193): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 6193): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440] already in the list, will not add again
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT177","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177],
I/io.jxcore.node.ConnectionHelper( 6193): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 6193): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6753","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1018): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/WifiP2pService( 1018): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
I/io.jxcore.node.ConnectionHelper( 6193): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6193): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753] already in the list, will not add again
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4281, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1018): !@Sync 17
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4280, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 455s ago
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4282, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): setState: RESTARTING
,D/WifiP2pService( 1018): InactiveState{ what=139268 }
,I/wpa_supplicant( 2090): P2P-FIND-STOPPED 
,D/WifiP2pService( 1018): InactiveState{ what=147493 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1018): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
V/AlarmManager( 1018): No more alarm at this time.nowELAPSED=541846 batch.start=557074
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): Start timer timeout, starting now...
,D/WifiP2pService( 1018): InactiveState{ what=139265 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139265 }
D/WifiService( 1018): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1018): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1018): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2090): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): setState: STARTED
D/WifiP2pService( 1018): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,E/SMD     (  288): DCD OFF
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1018): InactiveState{ what=147477 },
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 },
D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28,
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80,
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1018): DefaultState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], add/update: true,
D/WifiDisplayController( 1018): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8,
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): restart: Restarting...
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07,
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80,
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac,
D/WifiP2pService( 1018): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1018): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1018): P2pEnabledState clear service request
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true,
D/WifiP2pService( 1018): InactiveState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/WifiP2pService( 1018): P2pEnabledState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1018): P2pEnabledState add service request
D/WifiP2pManager( 6193): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): Service request added successfully
,E/SMD     (  288): DCD OFF
,D/WifiP2pService( 1018): InactiveState{ what=139310 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1018): P2pEnabledState discover services
,D/WifiService( 1018): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1018): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiStateMachine( 1018): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 2090): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 2090): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): Service discovery started successfully
,I/wpa_supplicant( 2090): p2p0: P2P: Reject scan trigger since one is already pending,
I/wpa_supplicant( 2090): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT706","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
,I/io.jxcore.node.ConnectionHelper( 6193): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
,W/io.jxcore.node.ConnectionHelper( 6193): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706] already in the list, will not add again
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4275, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1018): stay LED for charging,
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate,
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 },
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 },
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86,
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1018): Received list of peers.
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706], add/update: true,
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
,D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
,D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
I/wpa_supplicant( 2090): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1018): InactiveState{ what=147477 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706], add/update: true
D/org.thaliproject.p2p.btconnec,torlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1779","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
I/io.jxcore.node.ConnectionHelper( 6193): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 6193): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779] already in the list, will not add again,
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6590): Starting books sync for 61035162, extras: ade,
,I/BooksConfig( 6590): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1734): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1734): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1734): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1734): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
,D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1734): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1734): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1734): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1734): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 73863(7MB) AllocSpace objects, 162(2MB) LOS objects, 33% free, 27MB/41MB, paused 2.474ms total 169.818ms,
,E/BooksAccountManager( 6590): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6590): Soft error
E/BooksSync( 6590): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6590): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6590): Sync error
E/BooksSync( 6590): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6590): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6590): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 557074, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1018): InactiveState{ what=147477 },
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: true
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488,, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/WifiP2pService( 1018): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/WifiP2pService( 1018): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1018): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): restart: Restarting...
,D/WifiP2pService( 1018): InactiveState{ what=139301 },
D/WifiP2pService( 1018): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 1018): P2pEnabledState add service request
D/WifiP2pManager( 6193): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): Service request added successfully
,E/Watchdog( 1018): !@Sync 18
,I/Atfwd_Sendcmd(  315): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  315): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiP2pService( 1018): InactiveState{ what=139310 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1018): P2pEnabledState discover services
,D/WifiStateMachine( 1018): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1018): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1018): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2090): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): Service discovery started successfully
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4280, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1018): InactiveState{ what=147477 },
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiDisplayController( 1018): Received list of peers.
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceA,ddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1779","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
,I/io.jxcore.node.ConnectionHelper( 6193): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 6193): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779] already in the list, will not add again
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2787","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
I/io.jxcore.node.ConnectionHelper( 6193): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 6193): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787] already in the list, will not add again
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9197","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
I/io.jxcore.node.ConnectionHelper( 6193): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
,D/io.jxcore.node.ConnectionHelper( 6193): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197] is available
,E/SMD     (  288): DCD OFF
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 12 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,I/jxcore-log( 6193): teardown
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): testFindPeers stopped
I/jxcore-log( 6193): 
,I/io.jxcore.node.ConnectionHelper( 6193): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): shutdown
D/BluetoothSocket( 6193): close() in, this: android.bluetooth.BluetoothSocket@35fb707c, channel: 6, state: LISTENING
D/BluetoothSocket( 6193): close() this: android.bluetooth.BluetoothSocket@35fb707c, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@592af50, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@143cdd05mSocket: android.net.LocalSocket@201fd15a impl:android.net.LocalSocketImpl@24f1bf8b fd:FileDescriptor[111]
D/BluetoothSocket( 6193): Closing mSocket: android.net.LocalSocket@201fd15a impl:android.net.LocalSocketImpl@24f1bf8b fd:FileDescriptor[111]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6193): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): stop: Stopping services
D/WifiP2pService( 1018): InactiveState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6193): release: No more listeners, de-initializing...
,D/WifiP2pService( 1018): P2pEnabledState{ what=139298 }
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6193): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6193): release: No more listeners, de-initializing...
D/WifiP2pService( 1018): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): setState: NOT_STARTED
,I/jxcore-log( 6193): StopBroadcasting went ok
I/jxcore-log( 6193): 
,I/chromium( 6193): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6193): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6193): onDiscoveryManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6193): Local services cleared successfully
,D/WifiP2pService( 1018): InactiveState{ what=139268 }
,I/wpa_supplicant( 2090): P2P-FIND-STOPPED 
,D/WifiP2pService( 1018): InactiveState{ what=139307 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 1018): P2pEnabledState clear service request
I/jxcore-log( 6193): --- start :testSendData.js---
I/jxcore-log( 6193): 
D/WifiP2pService( 1018): remove channel information from framework
,I/jxcore-log( 6193): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":14}bt-address length : 0
I/jxcore-log( 6193): 
,D/WifiP2pService( 1018): InactiveState{ what=147493 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1018): discovery change broadcast false
,I/jxcore-log( 6193): daya100000
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): check server
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): serverPort is 40261
I/jxcore-log( 6193): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): start: Peer ID: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT3690
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6193): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6193): initialize: My bluetooth address is 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6193): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3690","ra":"7C:F9:0E:51:18:22"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): startListeningForIncomingConnections: Starting...
,D/BluetoothSocket( 6193): bindListen(): myUserId = 0
,W/BluetoothAdapter( 6193): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6193): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[113]}
,D/BluetoothSocket( 6193): bindListen(), new LocalSocket 
D/BluetoothSocket( 6193): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6193): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@34334481
,D/BluetoothSocket( 6193): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): start: OK
,I/io.jxcore.node.ConnectionHelper( 6193): start: Using peer discovery mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): start: Peer ID: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT3690
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6193): verifyIdentityString: Identity string created: {"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3690","ra":"7C:F9:0E:51:18:22"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6193): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): start: {"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3690","ra":"7C:F9:0E:51:18:22"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6193): start: Identity string: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3690","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 1018): InactiveState{ what=139292 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139292 }
E/SMD     (  288): DCD OFF
D/WifiP2pService( 1018): P2pEnabledState add service
D/WifiP2pService( 1018): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6193): start: OK
,I/jxcore-log( 6193): StartBroadcasting started ok
I/jxcore-log( 6193): 
D/WifiP2pService( 1018): InactiveState{ what=139265 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139265 }
D/WifiStateMachine( 1018): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1018): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1018): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2090): USE_NETWORK : USE_NETWORK OFF
,I/jxcore-log( 6193): null
I/jxcore-log( 6193): 
,D/WifiP2pService( 1018): discovery change broadcast true
,I/jxcore-log( 6193): 2016-01-05T00:47:23.609Z SendDataTCPServer.js: TCP/IP server is bound to port: 40261
I/jxcore-log( 6193): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): P2P device discovery stopped successfully
,I/chromium( 6193): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): Service requests cleared successfully
,I/io.jxcore.node.ConnectionHelper( 6193): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onWifiStateChanged: State changed to 2
I/io.jxcore.node.ConnectionHelper( 6193): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6193): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 2090): P2P-FIND-STOPPED ,
D/WifiP2pService( 1018): InactiveState{ what=139268 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): P2P device discovery stopped successfully
D/WifiP2pService( 1018): InactiveState{ what=147493 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1018): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): setState: RESTARTING
D/WifiP2pService( 1018): InactiveState{ what=139268 }
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): Start timer timeout, starting now...
,D/WifiP2pService( 1018): InactiveState{ what=139265 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139265 }
D/WifiService( 1018): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1018): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1018): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 2090): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): P2P device discovery started successfully
,D/WifiP2pService( 1018): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,E/SMD     (  288): DCD OFF
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
I/wpa_supplicant( 2090): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 44.5A.07 p2p_dev_addr=44.5A.07 pri_dev_type=10-0050F204-5  '23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 freq=2437
I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 },
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/WifiDisplayController( 1018): Received list of peers.,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1018): InactiveState{ what=139283 },
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b,
,D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 12 device(s) discovered
,D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac,
,D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1018): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 12 device(s) discovered
,D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac,
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiDisplayController( 1018): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac,
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86,
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78,
D/WifiDisplayController( 1018): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 },
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pManager( 6193): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): Service request added successfully
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1018): InactiveState{ what=139301 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1018): P2pEnabledState add service request
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 0A.75.42 p2p_dev_addr=0A.75.42 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
,D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1018): InactiveState{ what=139310 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1018): P2pEnabledState discover services
,D/WifiStateMachine( 1018): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiService( 1018): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1018): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 2090): USE_NETWORK : USE_NETWORK OFF
I/wpa_supplicant( 2090): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): Service discovery started successfully
,I/wpa_supplicant( 2090): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 2090): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1018): InactiveState{ what=147477 },
,D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 12 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1018): InactiveState{ what=147494 },
D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9383","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,I/io.jxcore.node.ConnectionHelper( 6193): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
,D/io.jxcore.node.ConnectionHelper( 6193): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383] is available
,I/jxcore-log( 6193): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"LGE-Nexus 5_PT9383","peerAvailable":true}]
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): Found peer : LGE-Nexus 5_PT9383, Available: true
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): startWithNextDevice
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): device[1]: 34:FC:EF:11:AE:67
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:31.888Z SendDataConnector.js: Start called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:31.890Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:31.891Z SendDataConnector.js: do connect now
I/jxcore-log( 6193): 
,I/io.jxcore.node.ConnectionHelper( 6193): connect: Trying to connect to peer with ID 34:FC:EF:11:AE:67
,D/io.jxcore.node.ConnectionHelper( 6193): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): connect: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): connect: Trying to start connecting to null in address 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): setInsecureRfcommSocketPort: Using port -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): onConnecting: null 34:FC:EF:11:AE:67
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): connect: Started connecting to null in address 34:FC:EF:11:AE:67
,I/io.jxcore.node.ConnectionHelper( 6193): connect: Connection process successfully started (peer ID: 34:FC:EF:11:AE:67)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): Trying to connect to peer with address 34:FC:EF:11:AE:67 (thread ID: 1090)
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState receive service response
D/BluetoothUtils( 6193): isSocketAllowedBySecurityPolicy start : device null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8357","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
D/BluetoothSocket( 6193): connect(): myUserId = 0
W/BluetoothAdapter( 6193): getBluetoothService() called with no BluetoothManagerCallback
I/io.jxcore.node.ConnectionHelper( 6193): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
D/io.jxcore.node.ConnectionHelper( 6193): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357] is available
,I/jxcore-log( 6193): peerAvailabilityChanged [{"peerIdentifier":"90:E7:C4:F6:69:77","peerName":"HTC-HTC One M8s_PT8357","peerAvailable":true}]
I/jxcore-log( 6193): 
I/jxcore-log( 6193): Found peer : HTC-HTC One M8s_PT8357, Available: true
I/jxcore-log( 6193): 
,D/BTIF_SOCK( 2642): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 6193): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[115]},
,D/IOP_DB_BT( 2642): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 2642): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2642): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 2642): db_query_add_key: key KEY_DIR_ALL, value 1
D/IOP_DB_BT( 2642): db_query_execute: result 1
,D/IOP_DB_BT( 2642): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 2642): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 2642): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 2642): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2642): db_query_execute: result 1
,W/bt-btif ( 2642): info:x10
D/        ( 2642): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 2642): aclStateChangeCallback: Device is NULL
,D/BluetoothUtils( 2642): getBtEnabledContainers(): btContainers = []
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.NAME_CHANGED
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1779","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
,I/io.jxcore.node.ConnectionHelper( 6193): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
,W/io.jxcore.node.ConnectionHelper( 6193): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779] already in the list, will not add again
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT818","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818],
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
I/io.jxcore.node.ConnectionHelper( 6193): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 6193): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818] is available
,I/jxcore-log( 6193): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT818","peerAvailable":true}]
I/jxcore-log( 6193): 
I/jxcore-log( 6193): Found peer : samsung-SM-A300FU_PT818, Available: true
I/jxcore-log( 6193): 
,W/bt-sdp  ( 2642): process_service_search_attr_rsp,
,E/SMD     (  288): DCD OFF
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.NAME_CHANGED
,D/BluetoothUtils( 2642): getBtEnabledContainers(): btContainers = []
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
,D/BluetoothUtils( 2642): getBtEnabledContainers(): btContainers = []
,I/BluetoothBondStateMachine( 2642): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
D/WifiP2pService( 1018): P2pEnabledState receive service response
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.CLASS_CHANGED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT706","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,D/SecContentProvider( 1018): uri = 4 selection = bluetoothLogForRemote
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
I/io.jxcore.node.ConnectionHelper( 6193): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 6193): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706] already in the list, will not add again
,E/bt-btif ( 2642): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2642): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 2642): isSecureModeOn:false
,D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED
,D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
,D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/BluetoothTile( 1179):  onBluetoothPairedDevicesChanged:,
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.BOND_STATE_CHANGED
I/BluetoothBondStateMachine( 2642): Entering PendingCommandState State
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothTile( 1179):  handleUpdatestate:false name:null
,D/BluetoothNotiBroadcastReceiver( 1325): onReceive
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6929): MountEmulatedStorage(),
,E/Zygote  ( 6929): v2
,I/ActivityManager( 1018): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/.GMHFPReceiver: pid=6929 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/libpersona( 6929): KNOX_SDCARD checking this for 10100
I/libpersona( 6929): KNOX_SDCARD not a persona
,I/SELinux ( 6929): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 6929): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6929): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6929): TimaSignature is unavailable
,D/ActivityThread( 6929): Added TimaKeyStore provider
,E/BluetoothHeadset( 6929): BTStateChangeCB is registed
,D/BluetoothHeadset( 6929): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 6929): BluetoothHeadset service is binded
,D/GMFPReceiver( 6929): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
D/GMFPReceiver( 6929): jangil::setProperties()
,D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4505","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
D/GMFPReceiver( 6929): jangil::printBTStatus()
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onServiceDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
I/io.jxcore.node.ConnectionHelper( 6193): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07
D/io.jxcore.node.ConnectionHelper( 6193): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4505] is available
,I/jxcore-log( 6193): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"motorola-XT1072_PT4505","peerAvailable":true}]
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): Found peer : motorola-XT1072_PT4505, Available: true
I/jxcore-log( 6193): 
,D/SettingsProvider( 1018): name = Wearable0001
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10100
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10100,
,D/GMFPReceiver( 6929): ::::::::Wearable0001::false
,D/SettingsProvider( 1018): name = Wearable0002
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10100
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/btif_config_util( 2642): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10100
,D/GMFPReceiver( 6929): ::::::::Wearable0002::false
,D/GMFPReceiver( 6929): onServiceConnected() : 1
D/GMFPReceiver( 6929): mBluetoothHeadset = true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Killing 6030:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,I/BluetoothBondStateMachine( 2642): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
,D/BluetoothAdapterProperties( 2642): Failed to remove device: 34:FC:EF:11:AE:67
,D/SecContentProvider( 1018): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2642): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 2642): isSecureModeOn:false
,D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/BluetoothTile( 1179):  onBluetoothPairedDevicesChanged:
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 1179):  handleUpdatestate:false name:null
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothNotiBroadcastReceiver( 1325): onReceive
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,D/HidService( 2642): getHidService(): returning com.android.bluetooth.hid.HidService@bf2ac50
,D/SettingsProvider( 1018): name = bluetooth_input_device_priority_34:FC:EF:11:AE:67
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/HidService( 2642): Saved priority 34:FC:EF:11:AE:67 = -1
,D/SettingsProvider( 1018): name = bluetooth_a2dp_sink_priority_34:FC:EF:11:AE:67
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = bluetooth_headset_priority_34:FC:EF:11:AE:67
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,I/BluetoothBondStateMachine( 2642): StableState(): Entering Off State
,E/BluetoothHeadset( 6929): BTStateChangeCB is registed
,D/BluetoothHeadset( 6929): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 6929): BluetoothHeadset service is binded
,D/GMFPReceiver( 6929): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 6929): jangil::setProperties()
,D/GMFPReceiver( 6929): jangil::printBTStatus()
,D/SettingsProvider( 1018): name = Wearable0001
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10100
,D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/GMFPReceiver( 6929): ::::::::Wearable0001::false
,D/SettingsProvider( 1018): name = Wearable0002
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10100
,D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/GMFPReceiver( 6929): ::::::::Wearable0002::false
D/GMFPReceiver( 6929): onServiceConnected() : 1
,D/GMFPReceiver( 6929): mBluetoothHeadset = true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,W/bt-btif ( 2642): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2642): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2642): bta_dm_pm_ssr:2, lat:1200
E/BluetoothRemoteDevices( 2642): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): onSocketConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1090)
,D/BluetoothSocket( 6193): getInputStream(): myUserId = 0
,D/BluetoothSocket( 6193): getOutputStream(): myUserId = 0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): onBytesWritten: 83 bytes successfully written (thread ID: 1091)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6193): Entering thread (ID: 1091)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): Outgoing connection initialized (*handshake* thread ID: 1091)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): Exiting thread (thread ID: 1090)
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_6030/cgroup.procs: No such file or directory
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): onBytesRead: Read 77 bytes successfully (thread ID: 1091)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): Handshake succeeded with [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): onHandshakeSucceeded: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6193): Exiting thread (ID: 1091)
,I/io.jxcore.node.ConnectionHelper( 6193): onConnected: Outgoing connection to peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,D/io.jxcore.node.ConnectionHelper( 6193): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
,W/io.jxcore.node.ConnectionHelper( 6193): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383] already in the list, will not add again
,D/BluetoothSocket( 6193): getInputStream(): myUserId = 0
,D/BluetoothSocket( 6193): getOutputStream(): myUserId = 0
,I/io.jxcore.node.ConnectionHelper( 6193): onConnected: Outgoing socket thread, for peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6193): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 6193): Entering thread (ID: 1092)
,D/io.jxcore.node.OutgoingSocketThread( 6193): Server socket local port: 33482
,I/io.jxcore.node.OutgoingSocketThread( 6193): Now accepting connections...
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/bt-btif ( 2642): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2642): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2642): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2642): bta_dm_pm_ssr:2, lat:1200
D/BluetoothSocket( 6193): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@288f5314
,E/BluetoothRemoteDevices( 2642): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): Incoming connection accepted
,D/BluetoothSocket( 6193): getInputStream(): myUserId = 0
,D/BluetoothSocket( 6193): getOutputStream(): myUserId = 0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): Incoming connection initialized (thread ID: 1093)
I/io.jxcore.node.ConnectionHelper( 6193): onListeningForIncomingConnections: Outgoing connection is using port 33482 (peer ID: 34:FC:EF:11:AE:67)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): Waiting for incoming connections...
,I/jxcore-log( 6193): 2016-01-05T00:47:33.574Z SendDataConnector.js: CLIENT connected to 33482, error: null
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:33.574Z SendDataConnector.js: CLIENT starting client ,
I/jxcore-log( 6193): 
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6193): Entering thread (ID: 1093)
,I/jxcore-log( 6193): 2016-01-05T00:47:33.582Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6193): 
,I/io.jxcore.node.OutgoingSocketThread( 6193): Incoming data from address: /127.0.0.1, port: 33482
D/io.jxcore.node.OutgoingSocketThread( 6193): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6193): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6193): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 6193): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6193): Exiting thread (ID: 1092)
,D/io.jxcore.node.StreamCopyingThread( 6193): Entering thread (ID: 1095, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6193): Entering thread (ID: 1094, name: Sender)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): onBytesRead: Read 77 bytes successfully (thread ID: 1093)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): Got valid identity from [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): onBytesWritten: 83 bytes successfully written (thread ID: 1093)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): removeThreadFromList: Removing thread with ID 1093
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): Handshake thread disposed (thread ID: 1093)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): onIncomingConnectionConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6193): Exiting thread (ID: 1093)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383],
I/io.jxcore.node.ConnectionHelper( 6193): onConnected: Incoming connection to peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
D/io.jxcore.node.ConnectionHelper( 6193): hasConnection: We have an outgoing connection with peer with ID 34:FC:EF:11:AE:67,
W/io.jxcore.node.ConnectionHelper( 6193): onConnected: Already connected with peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 6193): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383] already in the list, will not add again
,D/        ( 2642): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:29210
,D/BluetoothSocket( 6193): getInputStream(): myUserId = 0
,D/BluetoothSocket( 6193): getOutputStream(): myUserId = 0,
I/io.jxcore.node.ConnectionHelper( 6193): onConnected: Incoming socket thread, for peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], created successfully,
D/io.jxcore.node.ConnectionHelper( 6193): onConnected: The total number of connections is now 2
D/io.jxcore.node.IncomingSocketThread( 6193): Entering thread (ID: 1096)
D/EnterpriseController(  278): uids 10175
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10175
,I/io.jxcore.node.IncomingSocketThread( 6193): Local host address: localhost/127.0.0.1, port: 40261
D/io.jxcore.node.IncomingSocketThread( 6193): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6193): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6193): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6193): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6193): Exiting thread (ID: 1096)
,D/io.jxcore.node.StreamCopyingThread( 6193): Entering thread (ID: 1098, name: Receiver)
,I/jxcore-log( 6193): 2016-01-05T00:47:33.993Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6193): 
,D/io.jxcore.node.StreamCopyingThread( 6193): Entering thread (ID: 1097, name: Sender)
,I/jxcore-log( 6193): 2016-01-05T00:47:34.189Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6193): 
,D/        ( 2642): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:17330
,D/        ( 2642): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:5450
,I/jxcore-log( 6193): 2016-01-05T00:47:34.635Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:34.692Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:34.846Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:34.878Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:34.907Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:34.912Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:34.941Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:34.976Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:34.993Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:35.043Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:35.048Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:35.051Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:35.053Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:35.061Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:35.096Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:35.101Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:35.168Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:35.213Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:35.250Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:35.302Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:35.308Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:35.313Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:35.319Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:35.336Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:35.375Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:35.415Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:35.450Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:35.490Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:35.491Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): oneRoundDownNow
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:35.494Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:35.495Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6193): 
,D/io.jxcore.node.ConnectionHelper( 6193): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:AE:67
,I/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 34:FC:EF:11:AE:67
,I/io.jxcore.node.IncomingSocketThread( 6193): close
,D/io.jxcore.node.IncomingSocketThread( 6193): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6193): doStop: Thread ID: 1095
,D/io.jxcore.node.IncomingSocketThread( 6193): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6193): doStop: Thread ID: 1094
,D/io.jxcore.node.IncomingSocketThread( 6193): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6193): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6193): Either failed to read from the output stream or write to the input stream (thread ID: 1094, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 6193): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 6193): onDisconnected: Outgoing connection, peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 6193): closeLocalSocketAndStreams: Closing the local output stream...,
D/io.jxcore.node.IncomingSocketThread( 6193): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6193): closeBluetoothSocketAndStreams
D/BluetoothSocket( 6193): close() in, this: android.bluetooth.BluetoothSocket@5cea7bd, channel: 5, state: CONNECTED
D/BluetoothSocket( 6193): close() this: android.bluetooth.BluetoothSocket@5cea7bd, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@294731b2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@26209503mSocket: android.net.LocalSocket@2c988c80 impl:android.net.LocalSocketImpl@22c302b9 fd:FileDescriptor[115]
,D/BluetoothSocket( 6193): Closing mSocket: android.net.LocalSocket@2c988c80 impl:android.net.LocalSocketImpl@22c302b9 fd:FileDescriptor[115]
W/io.jxcore.node.StreamCopyingThread( 6193): Either failed to read from the output stream or write to the input stream (thread ID: 1095, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 6193): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6193): onDisconnected: Outgoing connection, peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/BluetoothSocket( 6193): close() in, this: android.bluetooth.BluetoothSocket@5cea7bd, channel: 5, state: CLOSED
D/BluetoothSocket( 6193): close() in, this: android.bluetooth.BluetoothSocket@5cea7bd, channel: 5, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 6193): disconnectOutgoingConnection: Successfully disconnected (peer ID: 34:FC:EF:11:AE:67
E/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6193): Exiting thread (ID: 1094, name: Sender)
E/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6193): Exiting thread (ID: 1095, name: Receiver)
I/jxcore-log( 6193): 2016-01-05T00:47:35.508Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6193): 
I/jxcore-log( 6193): ---- round done--------
I/jxcore-log( 6193): 
I/jxcore-log( 6193): startWithNextDevice
I/jxcore-log( 6193): 
I/jxcore-log( 6193): device[2]: 90:E7:C4:F6:69:77
I/jxcore-log( 6193): 
I/jxcore-log( 6193): 2016-01-05T00:47:35.509Z SendDataConnector.js: Start called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 6193): 
I/jxcore-log( 6193): 2016-01-05T00:47:35.510Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:35.510Z SendDataConnector.js: do connect now
I/jxcore-log( 6193): 
I/io.jxcore.node.ConnectionHelper( 6193): connect: Trying to connect to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 6193): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): connect: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): connect: Trying to start connecting to null in address 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): onConnecting: null 90:E7:C4:F6:69:77
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): connect: Started connecting to null in address 90:E7:C4:F6:69:77
,I/io.jxcore.node.ConnectionHelper( 6193): connect: Connection process successfully started (peer ID: 90:E7:C4:F6:69:77)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): Trying to connect to peer with address 90:E7:C4:F6:69:77 (thread ID: 1099)
,D/BluetoothUtils( 6193): isSocketAllowedBySecurityPolicy start : device null
D/BluetoothSocket( 6193): connect(): myUserId = 0
W/BluetoothAdapter( 6193): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 6193): 2016-01-05T00:47:35.526Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 6193): 
,D/BTIF_SOCK( 2642): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/IOP_DB_BT( 2642): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
D/IOP_DB_BT( 2642): db_query_add_key: key KEY_LMP_MFCT, value 0
,D/BluetoothSocket( 6193): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[115]}
D/IOP_DB_BT( 2642): db_query_add_key: key KEY_LMP_VER, value 0:0
D/IOP_DB_BT( 2642): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 2642): db_query_execute: result 1
,E/SMD     (  288): DCD OFF
,I/jxcore-log( 6193): 2016-01-05T00:47:35.681Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:35.806Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:35.931Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 6193): 
,D/IOP_DB_BT( 2642): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
,D/IOP_DB_BT( 2642): db_query_add_key: key KEY_LMP_MFCT, value 0
D/IOP_DB_BT( 2642): db_query_add_key: key KEY_LMP_VER, value 0:0
D/IOP_DB_BT( 2642): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2642): db_query_execute: result 1
W/bt-btif ( 2642): info:x10
,D/        ( 2642): remote version info [90:e7:c4:f6:69:77]: 0, 0, 0
,E/BluetoothRemoteDevices( 2642): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 6193): 2016-01-05T00:47:36.308Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 6193): 
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.NAME_CHANGED
,D/BluetoothUtils( 2642): getBtEnabledContainers(): btContainers = []
,I/jxcore-log( 6193): 2016-01-05T00:47:36.352Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:36.386Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:36.405Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:36.450Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 6193): 
,W/bt-sdp  ( 2642): process_service_search_attr_rsp
,I/jxcore-log( 6193): 2016-01-05T00:47:36.494Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 6193): 
,W/bt-btif ( 2642): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,I/jxcore-log( 6193): 2016-01-05T00:47:36.603Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:36.635Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:36.640Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:36.676Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:36.711Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 6193): 
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.NAME_CHANGED
,D/BluetoothUtils( 2642): getBtEnabledContainers(): btContainers = []
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.CLASS_CHANGED
,D/BluetoothUtils( 2642): getBtEnabledContainers(): btContainers = []
I/BluetoothBondStateMachine( 2642): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 1
,D/SecContentProvider( 1018): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 2642): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2642): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 10 NewState: 11
D/BtConfig.SecureMode( 2642): isSecureModeOn:false
I/BluetoothBondStateMachine( 2642): Entering PendingCommandState State
,D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/BluetoothTile( 1179):  onBluetoothPairedDevicesChanged:
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/BluetoothTile( 1179):  handleUpdatestate:false name:null
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothNotiBroadcastReceiver( 1325): onReceive
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,I/jxcore-log( 6193): 2016-01-05T00:47:36.756Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 6193): 
,E/BluetoothHeadset( 6929): BTStateChangeCB is registed
,D/BluetoothHeadset( 6929): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 6929): BluetoothHeadset service is binded
D/GMFPReceiver( 6929): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 6929): jangil::setProperties()
,D/GMFPReceiver( 6929): jangil::printBTStatus()
,D/SettingsProvider( 1018): name = Wearable0001
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10100
,D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/GMFPReceiver( 6929): ::::::::Wearable0001::false
,D/SettingsProvider( 1018): name = Wearable0002
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10100
,D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/GMFPReceiver( 6929): ::::::::Wearable0002::false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/GMFPReceiver( 6929): onServiceConnected() : 1
D/GMFPReceiver( 6929): mBluetoothHeadset = true
,I/jxcore-log( 6193): 2016-01-05T00:47:36.795Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6193): 
,W/bt-btif ( 2642): invalid rfc slot id: 5
,W/io.jxcore.node.StreamCopyingThread( 6193): Either failed to read from the output stream or write to the input stream (thread ID: 1098, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 6193): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 6193): onDisconnected: Incoming connection, peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1096
D/io.jxcore.node.IncomingSocketThread( 6193): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6193): doStop: Thread ID: 1098
D/io.jxcore.node.IncomingSocketThread( 6193): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6193): doStop: Thread ID: 1097
,D/io.jxcore.node.IncomingSocketThread( 6193): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6193): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6193): closeLocalSocketAndStreams: Closing the local output stream...
,W/io.jxcore.node.StreamCopyingThread( 6193): Either failed to read from the output stream or write to the input stream (thread ID: 1097, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6193): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6193): onDisconnected: Incoming connection, peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.IncomingSocketThread( 6193): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6193): closeBluetoothSocketAndStreams
,D/BluetoothSocket( 6193): close() in, this: android.bluetooth.BluetoothSocket@bf2b6fe, channel: 6, state: CONNECTED
,D/BluetoothSocket( 6193): close() this: android.bluetooth.BluetoothSocket@bf2b6fe, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@108d7e5f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@539f0acmSocket: android.net.LocalSocket@32081175 impl:android.net.LocalSocketImpl@383f450a fd:FileDescriptor[117]
,D/BluetoothSocket( 6193): Closing mSocket: android.net.LocalSocket@32081175 impl:android.net.LocalSocketImpl@383f450a fd:FileDescriptor[117]
D/BluetoothSocket( 6193): close() in, this: android.bluetooth.BluetoothSocket@bf2b6fe, channel: 6, state: CLOSED
D/BluetoothSocket( 6193): close() in, this: android.bluetooth.BluetoothSocket@bf2b6fe, channel: 6, state: CLOSED
,D/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6193): Exiting thread (ID: 1098, name: Receiver)
I/jxcore-log( 6193): 2016-01-05T00:47:36.866Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6193): 
D/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 6193): Exiting thread (ID: 1097, name: Sender)
,D/btif_config_util( 2642): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2642): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 0
,D/BluetoothAdapterProperties( 2642): Failed to remove device: 90:E7:C4:F6:69:77
,D/SecContentProvider( 1018): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2642): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 2642): isSecureModeOn:false
,D/HidService( 2642): getHidService(): returning com.android.bluetooth.hid.HidService@bf2ac50
,D/SettingsProvider( 1018): name = bluetooth_input_device_priority_90:E7:C4:F6:69:77
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/HidService( 2642): Saved priority 90:E7:C4:F6:69:77 = -1
,D/SettingsProvider( 1018): name = bluetooth_a2dp_sink_priority_90:E7:C4:F6:69:77
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
,D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = bluetooth_headset_priority_90:E7:C4:F6:69:77
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,I/BluetoothBondStateMachine( 2642): StableState(): Entering Off State
,D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/BluetoothTile( 1179):  onBluetoothPairedDevicesChanged:
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothTile( 1179):  handleUpdatestate:false name:null
,D/BluetoothNotiBroadcastReceiver( 1325): onReceive
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 6929): BTStateChangeCB is registed
,D/BluetoothHeadset( 6929): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3,
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
E/BluetoothHeadset( 6929): BluetoothHeadset service is binded
D/GMFPReceiver( 6929): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 6929): jangil::setProperties()
,D/GMFPReceiver( 6929): jangil::printBTStatus()
,D/SettingsProvider( 1018): name = Wearable0001
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10100
,D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/GMFPReceiver( 6929): ::::::::Wearable0001::false
,D/SettingsProvider( 1018): name = Wearable0002
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
,D/SettingsProvider( 1018): selectionArgs: 10100
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/GMFPReceiver( 6929): ::::::::Wearable0002::false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/GMFPReceiver( 6929): onServiceConnected() : 1
D/GMFPReceiver( 6929): mBluetoothHeadset = true
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,W/bt-btif ( 2642): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2642): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2642): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 2642): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): onSocketConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1099)
,D/BluetoothSocket( 6193): getInputStream(): myUserId = 0,
,D/BluetoothSocket( 6193): getOutputStream(): myUserId = 0,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): onBytesWritten: 83 bytes successfully written (thread ID: 1100)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): Outgoing connection initialized (*handshake* thread ID: 1100)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): Exiting thread (thread ID: 1099)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6193): Entering thread (ID: 1100)
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4260, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2642): Disconnected process message: 10,
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): onBytesRead: Read 81 bytes successfully (thread ID: 1100)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): Handshake succeeded with [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): onHandshakeSucceeded: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): onConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
,I/io.jxcore.node.ConnectionHelper( 6193): onConnected: Outgoing connection to peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
,D/io.jxcore.node.ConnectionHelper( 6193): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
,W/io.jxcore.node.ConnectionHelper( 6193): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357] already in the list, will not add again
,D/BluetoothSocket( 6193): getInputStream(): myUserId = 0
,D/BluetoothSocket( 6193): getOutputStream(): myUserId = 0
,I/io.jxcore.node.ConnectionHelper( 6193): onConnected: Outgoing socket thread, for peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], created successfully,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6193): onConnected: The total number of connections is now 1
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6193): Exiting thread (ID: 1100)
D/io.jxcore.node.OutgoingSocketThread( 6193): Entering thread (ID: 1101)
D/io.jxcore.node.OutgoingSocketThread( 6193): Server socket local port: 46196
I/io.jxcore.node.OutgoingSocketThread( 6193): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 6193): onListeningForIncomingConnections: Outgoing connection is using port 46196 (peer ID: 90:E7:C4:F6:69:77)
,I/jxcore-log( 6193): 2016-01-05T00:47:37.560Z SendDataConnector.js: CLIENT connected to 46196, error: null
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:37.560Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6193): 
,I/io.jxcore.node.OutgoingSocketThread( 6193): Incoming data from address: /127.0.0.1, port: 46196
D/io.jxcore.node.OutgoingSocketThread( 6193): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6193): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6193): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 6193): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6193): Exiting thread (ID: 1101)
,I/jxcore-log( 6193): 2016-01-05T00:47:37.565Z SendDataConnector.js: CLIENT now sending 100000 bytes of data,
I/jxcore-log( 6193): 
D/io.jxcore.node.StreamCopyingThread( 6193): Entering thread (ID: 1103, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6193): Entering thread (ID: 1102, name: Sender)
,D/        ( 2642): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 6193): 2016-01-05T00:47:38.148Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6193): 
,D/        ( 2642): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:17776
,I/jxcore-log( 6193): 2016-01-05T00:47:38.238Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:38.307Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6193): 
,D/        ( 2642): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:5896
,I/jxcore-log( 6193): 2016-01-05T00:47:38.388Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6193): 
,D/        ( 2642): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 6193): 2016-01-05T00:47:38.393Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:38.488Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:38.541Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:38.596Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6193): 
,E/SMD     (  288): DCD OFF
,I/jxcore-log( 6193): 2016-01-05T00:47:38.636Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:38.691Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:38.692Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): oneRoundDownNow
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:38.694Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:38.695Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6193): 
,D/io.jxcore.node.ConnectionHelper( 6193): disconnectOutgoingConnection: Trying to close connection to peer with ID 90:E7:C4:F6:69:77
,I/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 90:E7:C4:F6:69:77
,I/io.jxcore.node.OutgoingSocketThread( 6193): close
D/io.jxcore.node.OutgoingSocketThread( 6193): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 6193): doStop: Thread ID: 1103
D/io.jxcore.node.OutgoingSocketThread( 6193): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 6193): doStop: Thread ID: 1102
D/io.jxcore.node.OutgoingSocketThread( 6193): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.OutgoingSocketThread( 6193): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6193): Either failed to read from the output stream or write to the input stream (thread ID: 1102, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 6193): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 6193): onDisconnected: Outgoing connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 6193): closeLocalSocketAndStreams: Closing the local output stream...,
D/io.jxcore.node.OutgoingSocketThread( 6193): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 6193): closeBluetoothSocketAndStreams
,D/BluetoothSocket( 6193): close() in, this: android.bluetooth.BluetoothSocket@29b5a17b, channel: 6, state: CONNECTED
D/BluetoothSocket( 6193): close() this: android.bluetooth.BluetoothSocket@29b5a17b, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@39ab6b98, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@18554ff1mSocket: android.net.LocalSocket@2014a7d6 impl:android.net.LocalSocketImpl@1972da57 fd:FileDescriptor[115]
,D/BluetoothSocket( 6193): Closing mSocket: android.net.LocalSocket@2014a7d6 impl:android.net.LocalSocketImpl@1972da57 fd:FileDescriptor[115]
,W/io.jxcore.node.StreamCopyingThread( 6193): Either failed to read from the output stream or write to the input stream (thread ID: 1103, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 6193): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.ConnectionHelper( 6193): onDisconnected: Outgoing connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/BluetoothSocket( 6193): close() in, this: android.bluetooth.BluetoothSocket@29b5a17b, channel: 6, state: CLOSED
,D/BluetoothSocket( 6193): close() in, this: android.bluetooth.BluetoothSocket@29b5a17b, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 6193): disconnectOutgoingConnection: Successfully disconnected (peer ID: 90:E7:C4:F6:69:77,
E/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
,D/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6193): Exiting thread (ID: 1102, name: Sender)
E/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6193): Exiting thread (ID: 1103, name: Receiver)
,W/bt-btif ( 2642): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,I/jxcore-log( 6193): 2016-01-05T00:47:38.712Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): ---- round done--------
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): startWithNextDevice
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): device[3]: 08:EC:A9:50:75:41
I/jxcore-log( 6193): 
I/jxcore-log( 6193): 2016-01-05T00:47:38.715Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 6193): 
I/jxcore-log( 6193): 2016-01-05T00:47:38.716Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:38.718Z SendDataConnector.js: do connect now
I/jxcore-log( 6193): 
,I/io.jxcore.node.ConnectionHelper( 6193): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
,D/io.jxcore.node.ConnectionHelper( 6193): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): connect: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 6193): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 1104)
,D/BluetoothUtils( 6193): isSocketAllowedBySecurityPolicy start : device null
,D/BluetoothSocket( 6193): connect(): myUserId = 0
,W/BluetoothAdapter( 6193): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2642): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/IOP_DB_BT( 2642): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:75:41
D/IOP_DB_BT( 2642): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2642): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 2642): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 2642): db_query_execute: result 1
,D/BluetoothSocket( 6193): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[115]}
,E/bt-btm  ( 2642): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2642): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 2642): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:75:41
D/IOP_DB_BT( 2642): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2642): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 2642): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2642): db_query_execute: result 1
W/bt-btif ( 2642): info:x10
,D/KeyguardViewMediator( 1179): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothUtils( 2642): getBtEnabledContainers(): btContainers = []
,D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver onReceive
D/        ( 2642): remote version info [08:ec:a9:50:75:41]: 0, 0, 0
,D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_ACL_DISCONNECTED
,E/BluetoothRemoteDevices( 2642): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 1325): ACTION_ACL_DISCONNECTED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothUtils( 2642): getBtEnabledContainers(): btContainers = []
,D/KeyguardViewMediator( 1179): isGear1: device is not B1!
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.NAME_CHANGED
,D/BluetoothAdapterService( 2642): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@984f88e
,D/BtConfig.SecureMode( 2642): isSecureModeOn:false
,D/SecContentProvider( 1018): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/bt-sdp  ( 2642): process_service_search_attr_rsp
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2642): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 6147): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6147): Bluetooth Device Name: Nexus 5
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.NAME_CHANGED
,D/BluetoothUtils( 2642): getBtEnabledContainers(): btContainers = []
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.CLASS_CHANGED
D/BluetoothUtils( 2642): getBtEnabledContainers(): btContainers = []
,I/BluetoothBondStateMachine( 2642): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
,D/SecContentProvider( 1018): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 2642): check_cod: remote_cod = 0x5a020c,
I/BluetoothBondStateMachine( 2642): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 2642): isSecureModeOn:false
I/BluetoothBondStateMachine( 2642): Entering PendingCommandState State
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
,D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/BluetoothTile( 1179):  onBluetoothPairedDevicesChanged:
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 1179):  handleUpdatestate:false name:null
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothNotiBroadcastReceiver( 1325): onReceive
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 6929): BTStateChangeCB is registed
,D/BluetoothHeadset( 6929): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 6929): BluetoothHeadset service is binded
D/GMFPReceiver( 6929): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 6929): jangil::setProperties()
,D/GMFPReceiver( 6929): jangil::printBTStatus()
,D/SettingsProvider( 1018): name = Wearable0001
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10100
,D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/GMFPReceiver( 6929): ::::::::Wearable0001::false
D/SettingsProvider( 1018): name = Wearable0002
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10100
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/GMFPReceiver( 6929): ::::::::Wearable0002::false
D/GMFPReceiver( 6929): onServiceConnected() : 1
D/GMFPReceiver( 6929): mBluetoothHeadset = true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/btif_config_util( 2642): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2642): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 2642): Failed to remove device: 08:EC:A9:50:75:41
,D/SecContentProvider( 1018): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2642): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 2642): isSecureModeOn:false
,D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/HidService( 2642): getHidService(): returning com.android.bluetooth.hid.HidService@bf2ac50
,D/BluetoothTile( 1179):  onBluetoothPairedDevicesChanged:
,D/BluetoothNotiBroadcastReceiver( 1325): onReceive
,D/SettingsProvider( 1018): name = bluetooth_input_device_priority_08:EC:A9:50:75:41
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/HidService( 2642): Saved priority 08:EC:A9:50:75:41 = -1
,D/SettingsProvider( 1018): name = bluetooth_a2dp_sink_priority_08:EC:A9:50:75:41
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/BluetoothTile( 1179):  handleUpdatestate:false name:null
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,D/SettingsProvider( 1018): name = bluetooth_headset_priority_08:EC:A9:50:75:41
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,E/BluetoothHeadset( 6929): BTStateChangeCB is registed
,I/BluetoothBondStateMachine( 2642): StableState(): Entering Off State
,D/BluetoothHeadset( 6929): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 6929): BluetoothHeadset service is binded
,D/GMFPReceiver( 6929): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 6929): jangil::setProperties()
,D/GMFPReceiver( 6929): jangil::printBTStatus()
,D/SettingsProvider( 1018): name = Wearable0001
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10100
,D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/GMFPReceiver( 6929): ::::::::Wearable0001::false
,D/SettingsProvider( 1018): name = Wearable0002
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10100
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1018): ret = -1
,D/GMFPReceiver( 6929): ::::::::Wearable0002::false
,D/GMFPReceiver( 6929): onServiceConnected() : 1
D/GMFPReceiver( 6929): mBluetoothHeadset = true
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,W/bt-btif ( 2642): new conn_srvc id:26, app_id:1
W/bt-btif ( 2642): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2642): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 2642): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): onSocketConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818],
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1104)
,D/BluetoothSocket( 6193): getInputStream(): myUserId = 0,
,D/BluetoothSocket( 6193): getOutputStream(): myUserId = 0,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): onBytesWritten: 83 bytes successfully written (thread ID: 1105)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): Outgoing connection initialized (*handshake* thread ID: 1105)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): Exiting thread (thread ID: 1104),
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6193): Entering thread (ID: 1105)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): onBytesRead: Read 82 bytes successfully (thread ID: 1105),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): onHandshakeSucceeded: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6193): Exiting thread (ID: 1105)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818],
,I/io.jxcore.node.ConnectionHelper( 6193): onConnected: Outgoing connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818],
,D/io.jxcore.node.ConnectionHelper( 6193): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 6193): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818] already in the list, will not add again,
D/BluetoothSocket( 6193): getInputStream(): myUserId = 0
D/BluetoothSocket( 6193): getOutputStream(): myUserId = 0
,I/io.jxcore.node.ConnectionHelper( 6193): onConnected: Outgoing socket thread, for peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6193): onConnected: The total number of connections is now 1
D/io.jxcore.node.OutgoingSocketThread( 6193): Entering thread (ID: 1106),
D/io.jxcore.node.OutgoingSocketThread( 6193): Server socket local port: 53869
,I/io.jxcore.node.OutgoingSocketThread( 6193): Now accepting connections...
,W/bt-btif ( 2642): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2642): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2642): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2642): bta_dm_pm_ssr:2, lat:1200
D/BluetoothSocket( 6193): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@ab7a944
,E/BluetoothRemoteDevices( 2642): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): Incoming connection accepted,
I/Atfwd_Daemon(  315): Stop the daemon....
,D/BluetoothSocket( 6193): getInputStream(): myUserId = 0
,D/BluetoothSocket( 6193): getOutputStream(): myUserId = 0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): Incoming connection initialized (thread ID: 1107)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6193): Entering thread (ID: 1107)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): onBytesRead: Read 82 bytes successfully (thread ID: 1107)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): Got valid identity from [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): onBytesWritten: 83 bytes successfully written (thread ID: 1107)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): removeThreadFromList: Removing thread with ID 1107
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): Handshake thread disposed (thread ID: 1107)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): onIncomingConnectionConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6193): Exiting thread (ID: 1107)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
I/io.jxcore.node.ConnectionHelper( 6193): onConnected: Incoming connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
D/io.jxcore.node.ConnectionHelper( 6193): hasConnection: We have an outgoing connection with peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 6193): onConnected: Already connected with peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 6193): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818] already in the list, will not add again
,D/BluetoothSocket( 6193): getInputStream(): myUserId = 0
,D/BluetoothSocket( 6193): getOutputStream(): myUserId = 0
,I/io.jxcore.node.ConnectionHelper( 6193): onConnected: Incoming socket thread, for peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], created successfully
,D/io.jxcore.node.ConnectionHelper( 6193): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 6193): Entering thread (ID: 1108)
,D/EnterpriseController(  278): uids 10175
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10175
,I/jxcore-log( 6193): 2016-01-05T00:47:41.499Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6193): 
,I/io.jxcore.node.IncomingSocketThread( 6193): Local host address: localhost/127.0.0.1, port: 40261
,D/io.jxcore.node.IncomingSocketThread( 6193): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 6193): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 6193): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 6193): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6193): Exiting thread (ID: 1108)
,D/io.jxcore.node.StreamCopyingThread( 6193): Entering thread (ID: 1109, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6193): Entering thread (ID: 1110, name: Receiver)
,E/SMD     (  288): DCD OFF
,I/io.jxcore.node.ConnectionHelper( 6193): onListeningForIncomingConnections: Outgoing connection is using port 53869 (peer ID: 08:EC:A9:50:75:41)
,I/jxcore-log( 6193): 2016-01-05T00:47:41.714Z SendDataConnector.js: CLIENT connected to 53869, error: null
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:41.715Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6193): 
,I/io.jxcore.node.IncomingSocketThread( 6193): Incoming data from address: /127.0.0.1, port: 53869
,D/io.jxcore.node.IncomingSocketThread( 6193): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 6193): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 6193): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 6193): startStreamCopyingThreads: OK
,D/io.jxcore.node.IncomingSocketThread( 6193): Exiting thread (ID: 1106)
,I/jxcore-log( 6193): 2016-01-05T00:47:41.724Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6193): 
,D/io.jxcore.node.StreamCopyingThread( 6193): Entering thread (ID: 1112, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6193): Entering thread (ID: 1111, name: Sender)
,E/bt-btm  ( 2642): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2642): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1179): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothUtils( 2642): getBtEnabledContainers(): btContainers = [],
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 1325): ACTION_ACL_DISCONNECTED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterService( 2642): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@984f88e
,D/BtConfig.SecureMode( 2642): isSecureModeOn:false
,D/SecContentProvider( 1018): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/KeyguardViewMediator( 1179): isGear1: device is not B1!
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2642): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 6147): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6147): Bluetooth Device Name: HTC One M8s,
,D/        ( 2642): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:28748
,I/jxcore-log( 6193): 2016-01-05T00:47:42.263Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data,
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.268Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data,
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.275Z SendDataTCPServer.js: TCP/IP server has received 6072 bytes of data,
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.279Z SendDataTCPServer.js: TCP/IP server has received 8096 bytes of data,
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.286Z SendDataTCPServer.js: TCP/IP server has received 10120 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.292Z SendDataTCPServer.js: TCP/IP server has received 12144 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.316Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6193): 
,D/        ( 2642): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:18628
,I/jxcore-log( 6193): 2016-01-05T00:47:42.319Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.321Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.326Z SendDataTCPServer.js: TCP/IP server has received 20240 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.334Z SendDataTCPServer.js: TCP/IP server has received 22264 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.365Z SendDataTCPServer.js: TCP/IP server has received 30360 bytes of data
I/jxcore-log( 6193): 
,D/        ( 2642): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:8508
,I/jxcore-log( 6193): 2016-01-05T00:47:42.443Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.478Z SendDataTCPServer.js: TCP/IP server has received 32384 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.516Z SendDataTCPServer.js: TCP/IP server has received 40480 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.564Z SendDataTCPServer.js: TCP/IP server has received 42504 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.596Z SendDataTCPServer.js: TCP/IP server has received 50600 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.599Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.603Z SendDataTCPServer.js: TCP/IP server has received 52624 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.635Z SendDataTCPServer.js: TCP/IP server has received 58696 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.639Z SendDataTCPServer.js: TCP/IP server has received 60720 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.644Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.717Z SendDataTCPServer.js: TCP/IP server has received 62744 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.744Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.756Z SendDataTCPServer.js: TCP/IP server has received 70840 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.761Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.766Z SendDataTCPServer.js: TCP/IP server has received 72864 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.807Z SendDataTCPServer.js: TCP/IP server has received 80960 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.811Z SendDataTCPServer.js: TCP/IP server has received 82984 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.845Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.866Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.867Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): oneRoundDownNow
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.869Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.870Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6193): 
,D/io.jxcore.node.ConnectionHelper( 6193): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
,I/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:75:41
,I/io.jxcore.node.IncomingSocketThread( 6193): close
D/io.jxcore.node.IncomingSocketThread( 6193): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 6193): doStop: Thread ID: 1112
,D/io.jxcore.node.IncomingSocketThread( 6193): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6193): doStop: Thread ID: 1111
,D/io.jxcore.node.IncomingSocketThread( 6193): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6193): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6193): Either failed to read from the output stream or write to the input stream (thread ID: 1111, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 6193): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 6193): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 6193): closeLocalSocketAndStreams: Closing the local output stream...,
,D/io.jxcore.node.IncomingSocketThread( 6193): closeLocalSocketAndStreams: Closing the localhost socket...,
I/io.jxcore.node.IncomingSocketThread( 6193): closeBluetoothSocketAndStreams
,D/BluetoothSocket( 6193): close() in, this: android.bluetooth.BluetoothSocket@345dfa2d, channel: 6, state: CONNECTED
,D/BluetoothSocket( 6193): close() this: android.bluetooth.BluetoothSocket@345dfa2d, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a0b6b62, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@160c4f3mSocket: android.net.LocalSocket@192815b0 impl:android.net.LocalSocketImpl@22cd0c29 fd:FileDescriptor[115]
,D/BluetoothSocket( 6193): Closing mSocket: android.net.LocalSocket@192815b0 impl:android.net.LocalSocketImpl@22cd0c29 fd:FileDescriptor[115]
,W/io.jxcore.node.StreamCopyingThread( 6193): Either failed to read from the output stream or write to the input stream (thread ID: 1112, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6193): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6193): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/BluetoothSocket( 6193): close() in, this: android.bluetooth.BluetoothSocket@345dfa2d, channel: 6, state: CLOSED
D/BluetoothSocket( 6193): close() in, this: android.bluetooth.BluetoothSocket@345dfa2d, channel: 6, state: CLOSED
,D/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 6193): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:75:41
E/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 6193): Exiting thread (ID: 1111, name: Sender)
E/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6193): Exiting thread (ID: 1112, name: Receiver)
,W/bt-btif ( 2642): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
I/jxcore-log( 6193): 2016-01-05T00:47:42.888Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): ---- round done--------
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): startWithNextDevice
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): device[4]: 44:80:EB:7B:5A:05
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.893Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.894Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:42.895Z SendDataConnector.js: do connect now
I/jxcore-log( 6193): 
,I/io.jxcore.node.ConnectionHelper( 6193): connect: Trying to connect to peer with ID 44:80:EB:7B:5A:05
,D/io.jxcore.node.ConnectionHelper( 6193): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): connect: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): connect: Trying to start connecting to null in address 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): setInsecureRfcommSocketPort: Using port -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): onConnecting: null 44:80:EB:7B:5A:05
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): connect: Started connecting to null in address 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 6193): connect: Connection process successfully started (peer ID: 44:80:EB:7B:5A:05)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): Trying to connect to peer with address 44:80:EB:7B:5A:05 (thread ID: 1113)
,I/jxcore-log( 6193): 2016-01-05T00:47:42.907Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6193): 
,D/BluetoothUtils( 6193): isSocketAllowedBySecurityPolicy start : device null
,D/BluetoothSocket( 6193): connect(): myUserId = 0
W/BluetoothAdapter( 6193): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2642): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/IOP_DB_BT( 2642): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 2642): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2642): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 2642): db_query_add_key: key KEY_DIR_ALL, value 1
,D/BluetoothSocket( 6193): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[115]}
,D/IOP_DB_BT( 2642): db_query_execute: result 1
,W/bt-btif ( 2642): invalid rfc slot id: 7
,W/io.jxcore.node.StreamCopyingThread( 6193): Either failed to read from the output stream or write to the input stream (thread ID: 1110, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6193): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6193): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1108
,D/io.jxcore.node.IncomingSocketThread( 6193): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6193): doStop: Thread ID: 1110
,D/io.jxcore.node.IncomingSocketThread( 6193): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6193): doStop: Thread ID: 1109
,D/io.jxcore.node.IncomingSocketThread( 6193): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6193): closeLocalSocketAndStreams: Closing the local input stream...
,D/io.jxcore.node.IncomingSocketThread( 6193): closeLocalSocketAndStreams: Closing the local output stream...
,W/io.jxcore.node.StreamCopyingThread( 6193): Either failed to read from the output stream or write to the input stream (thread ID: 1109, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6193): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 6193): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 6193): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6193): closeBluetoothSocketAndStreams
D/BluetoothSocket( 6193): close() in, this: android.bluetooth.BluetoothSocket@1bb8dbae, channel: 6, state: CONNECTED
D/BluetoothSocket( 6193): close() this: android.bluetooth.BluetoothSocket@1bb8dbae, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3738bd4f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@6f0dcdcmSocket: android.net.LocalSocket@60141e5 impl:android.net.LocalSocketImpl@cbb04ba fd:FileDescriptor[117]
D/BluetoothSocket( 6193): Closing mSocket: android.net.LocalSocket@60141e5 impl:android.net.LocalSocketImpl@cbb04ba fd:FileDescriptor[117]
D/BluetoothSocket( 6193): close() in, this: android.bluetooth.BluetoothSocket@1bb8dbae, channel: 6, state: CLOSED
D/BluetoothSocket( 6193): close() in, this: android.bluetooth.BluetoothSocket@1bb8dbae, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6193): Exiting thread (ID: 1110, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6193): Exiting thread (ID: 1109, name: Sender)
,I/jxcore-log( 6193): 2016-01-05T00:47:43.074Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6193): 
,D/IOP_DB_BT( 2642): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05,
D/IOP_DB_BT( 2642): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 2642): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 2642): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2642): db_query_execute: result 1
,W/bt-btif ( 2642): info:x10
,D/        ( 2642): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3,
E/BluetoothRemoteDevices( 2642): aclStateChangeCallback: Device is NULL
,E/SMD     (  288): DCD OFF
,D/BluetoothUtils( 2642): getBtEnabledContainers(): btContainers = []
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.NAME_CHANGED
,W/bt-sdp  ( 2642): process_service_search_attr_rsp
,D/BluetoothUtils( 2642): getBtEnabledContainers(): btContainers = []
,D/BluetoothUtils( 2642): getBtEnabledContainers(): btContainers = []
,I/BluetoothBondStateMachine( 2642): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.NAME_CHANGED
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.CLASS_CHANGED
,D/SecContentProvider( 1018): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 2642): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2642): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
D/BtConfig.SecureMode( 2642): isSecureModeOn:false
I/BluetoothBondStateMachine( 2642): Entering PendingCommandState State
,D/BluetoothTile( 1179):  onBluetoothPairedDevicesChanged:
,D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/BluetoothTile( 1179):  handleUpdatestate:false name:null
V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothNotiBroadcastReceiver( 1325): onReceive
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 6929): BTStateChangeCB is registed
,D/BluetoothHeadset( 6929): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 6929): BluetoothHeadset service is binded
,D/GMFPReceiver( 6929): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 6929): jangil::setProperties()
,D/GMFPReceiver( 6929): jangil::printBTStatus()
,D/SettingsProvider( 1018): name = Wearable0001
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10100
,D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/GMFPReceiver( 6929): ::::::::Wearable0001::false
,D/SettingsProvider( 1018): name = Wearable0002
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10100
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/GMFPReceiver( 6929): ::::::::Wearable0002::false
,D/GMFPReceiver( 6929): onServiceConnected() : 1
D/GMFPReceiver( 6929): mBluetoothHeadset = true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/btif_config_util( 2642): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2642): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 2642): Failed to remove device: 44:80:EB:7B:5A:05
,D/SecContentProvider( 1018): uri = 4 selection = bluetoothLogForRemote,
,I/BluetoothBondStateMachine( 2642): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10,
,D/BluetoothTile( 1179):  onBluetoothPairedDevicesChanged:
D/BtConfig.SecureMode( 2642): isSecureModeOn:false
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
,D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
D/HidService( 2642): getHidService(): returning com.android.bluetooth.hid.HidService@bf2ac50
V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 1179):  handleUpdatestate:false name:null
,D/SettingsProvider( 1018): name = bluetooth_input_device_priority_44:80:EB:7B:5A:05
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/HidService( 2642): Saved priority 44:80:EB:7B:5A:05 = -1
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/SettingsProvider( 1018): name = bluetooth_a2dp_sink_priority_44:80:EB:7B:5A:05
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1018): ret = -1
,D/BluetoothNotiBroadcastReceiver( 1325): onReceive
,D/SettingsProvider( 1018): name = bluetooth_headset_priority_44:80:EB:7B:5A:05
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,I/BluetoothBondStateMachine( 2642): StableState(): Entering Off State
,W/bt-btif ( 2642): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2642): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2642): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 2642): setRfcommConnected true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 6929): BTStateChangeCB is registed
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): onSocketConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1113)
,D/BluetoothHeadset( 6929): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 6929): BluetoothHeadset service is binded
D/GMFPReceiver( 6929): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 6929): jangil::setProperties()
,D/BluetoothSocket( 6193): getInputStream(): myUserId = 0
,D/GMFPReceiver( 6929): jangil::printBTStatus()
,D/BluetoothSocket( 6193): getOutputStream(): myUserId = 0
D/SettingsProvider( 1018): name = Wearable0001
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): onBytesWritten: 83 bytes successfully written (thread ID: 1114)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): Outgoing connection initialized (*handshake* thread ID: 1114)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): Exiting thread (thread ID: 1113)
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10100
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/GMFPReceiver( 6929): ::::::::Wearable0001::false
,D/SettingsProvider( 1018): name = Wearable0002
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10100
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/GMFPReceiver( 6929): ::::::::Wearable0002::false
,D/GMFPReceiver( 6929): onServiceConnected() : 1
D/GMFPReceiver( 6929): mBluetoothHeadset = true
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6193): Entering thread (ID: 1114)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): onBytesRead: Read 81 bytes successfully (thread ID: 1114)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6193): Handshake succeeded with [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): onHandshakeSucceeded: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6193): Exiting thread (ID: 1114)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
,I/io.jxcore.node.ConnectionHelper( 6193): onConnected: Outgoing connection to peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
D/io.jxcore.node.ConnectionHelper( 6193): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
,W/io.jxcore.node.ConnectionHelper( 6193): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4505] already in the list, will not add again
,D/BluetoothSocket( 6193): getInputStream(): myUserId = 0
,D/BluetoothSocket( 6193): getOutputStream(): myUserId = 0
,I/io.jxcore.node.ConnectionHelper( 6193): onConnected: Outgoing socket thread, for peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4505], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6193): onConnected: The total number of connections is now 1
D/io.jxcore.node.OutgoingSocketThread( 6193): Entering thread (ID: 1115)
,D/io.jxcore.node.OutgoingSocketThread( 6193): Server socket local port: 54825
I/io.jxcore.node.OutgoingSocketThread( 6193): Now accepting connections...
,V/AlarmManager( 1018): waitForAlarm result :4
,I/io.jxcore.node.ConnectionHelper( 6193): onListeningForIncomingConnections: Outgoing connection is using port 54825 (peer ID: 44:80:EB:7B:5A:05)
,I/jxcore-log( 6193): 2016-01-05T00:47:45.613Z SendDataConnector.js: CLIENT connected to 54825, error: null
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:45.614Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6193): 
,I/io.jxcore.node.OutgoingSocketThread( 6193): Incoming data from address: /127.0.0.1, port: 54825
D/io.jxcore.node.OutgoingSocketThread( 6193): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6193): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6193): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 6193): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6193): Exiting thread (ID: 1115)
,D/io.jxcore.node.StreamCopyingThread( 6193): Entering thread (ID: 1116, name: Sender)
,I/jxcore-log( 6193): 2016-01-05T00:47:45.621Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6193): 
,D/io.jxcore.node.StreamCopyingThread( 6193): Entering thread (ID: 1117, name: Receiver)
,D/        ( 2642): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3786
,I/jxcore-log( 6193): 2016-01-05T00:47:46.118Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6193): 
,D/        ( 2642): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18320
,I/jxcore-log( 6193): 2016-01-05T00:47:46.230Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6193): 
,E/Watchdog( 1018): !@Sync 19
,I/jxcore-log( 6193): 2016-01-05T00:47:46.316Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6193): 
,D/        ( 2642): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8420
,I/jxcore-log( 6193): 2016-01-05T00:47:46.448Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:46.520Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:46.615Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:46.707Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:46.710Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:46.855Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:46.971Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:46.972Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): oneRoundDownNow
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:46.974Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:47:46.974Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6193): 
,D/io.jxcore.node.ConnectionHelper( 6193): disconnectOutgoingConnection: Trying to close connection to peer with ID 44:80:EB:7B:5A:05
,I/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 44:80:EB:7B:5A:05
,I/io.jxcore.node.OutgoingSocketThread( 6193): close
D/io.jxcore.node.OutgoingSocketThread( 6193): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 6193): doStop: Thread ID: 1117
D/io.jxcore.node.OutgoingSocketThread( 6193): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 6193): doStop: Thread ID: 1116
D/io.jxcore.node.OutgoingSocketThread( 6193): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.OutgoingSocketThread( 6193): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6193): Either failed to read from the output stream or write to the input stream (thread ID: 1116, thread name: Sender): Socket closed,
E/io.jxcore.node.OutgoingSocketThread( 6193): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 6193): onDisconnected: Outgoing connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4505] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 6193): closeLocalSocketAndStreams: Closing the local output stream...,
,D/io.jxcore.node.OutgoingSocketThread( 6193): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6193): closeBluetoothSocketAndStreams
,D/BluetoothSocket( 6193): close() in, this: android.bluetooth.BluetoothSocket@8eddf6b, channel: 5, state: CONNECTED
D/BluetoothSocket( 6193): close() this: android.bluetooth.BluetoothSocket@8eddf6b, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3f1ceac8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@d891761mSocket: android.net.LocalSocket@3e84b286 impl:android.net.LocalSocketImpl@26890747 fd:FileDescriptor[115]
,D/BluetoothSocket( 6193): Closing mSocket: android.net.LocalSocket@3e84b286 impl:android.net.LocalSocketImpl@26890747 fd:FileDescriptor[115]
W/io.jxcore.node.StreamCopyingThread( 6193): Either failed to read from the output stream or write to the input stream (thread ID: 1117, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 6193): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6193): onDisconnected: Outgoing connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4505] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/BluetoothSocket( 6193): close() in, this: android.bluetooth.BluetoothSocket@8eddf6b, channel: 5, state: CLOSED
D/BluetoothSocket( 6193): close() in, this: android.bluetooth.BluetoothSocket@8eddf6b, channel: 5, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left,
I/io.jxcore.node.ConnectionHelper( 6193): disconnectOutgoingConnection: Successfully disconnected (peer ID: 44:80:EB:7B:5A:05,
E/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05,
D/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 6193): Exiting thread (ID: 1116, name: Sender),
E/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6193): Exiting thread (ID: 1117, name: Receiver)
W/bt-btif ( 2642): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
I/jxcore-log( 6193): 2016-01-05T00:47:46.993Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 6193): 
I/jxcore-log( 6193): ---- round done--------
I/jxcore-log( 6193): 
I/jxcore-log( 6193): startWithNextDevice
I/jxcore-log( 6193): 
,D/SSRM:n  ( 1018): SIOP:: AP = 280
,E/bt-btm  ( 2642): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2642): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1179): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothUtils( 2642): getBtEnabledContainers(): btContainers = []
,D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 1325): ACTION_ACL_DISCONNECTED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/KeyguardViewMediator( 1179): isGear1: device is not B1!
,D/BluetoothAdapterService( 2642): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@984f88e
,D/BtConfig.SecureMode( 2642): isSecureModeOn:false
D/SecContentProvider( 1018): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2642): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 6147): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6147): Bluetooth Device Name: A3-1
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4271, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,E/bt-btm  ( 2642): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2642): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1179): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothUtils( 2642): getBtEnabledContainers(): btContainers = []
,D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.ACL_DISCONNECTED,
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,E/BluetoothEventManager( 1325): ACTION_ACL_DISCONNECTED
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterService( 2642): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@984f88e
,D/BtConfig.SecureMode( 2642): isSecureModeOn:false
D/KeyguardViewMediator( 1179): isGear1: device is not B1!
,D/SecContentProvider( 1018): uri = 4 selection = isProfileAuthorizedBySecurityPolicy,
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
I/BluetoothPbapService( 2642): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 6147): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6147): Bluetooth Device Name: XT1072
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4278, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,I/PowerManagerService( 1018): [PWL] Off : 525s ago
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): setState: RESTARTING
,D/WifiP2pService( 1018): InactiveState{ what=139268 }
,I/wpa_supplicant( 2090): P2P-FIND-STOPPED 
,D/WifiP2pService( 1018): InactiveState{ what=147493 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1018): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): Start timer timeout, starting now...
,D/WifiP2pService( 1018): InactiveState{ what=139265 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139265 }
D/WifiService( 1018): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1018): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1018): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2090): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1018): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): P2P device discovery started successfully,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4273, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86,
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505], add/update: true
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac,
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1018): InactiveState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706], add/update: true
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1018): InactiveState{ what=139307 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: true
D/WifiP2pService( 1018): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
D/WifiP2pService( 1018): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1018): InactiveState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 1018): P2pEnabledState{ what=139301 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], add/update: true
D/WifiP2pService( 1018): P2pEnabledState add service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): restart: Restarting...
D/WifiP2pManager( 6193): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): Service request added successfully
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 0A.75.42 p2p_dev_addr=0A.75.42 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505], add/update: true
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,E/SMD     (  288): DCD OFF
,D/WifiP2pService( 1018): InactiveState{ what=139310 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1018): P2pEnabledState discover services
D/WifiService( 1018): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1018): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1018): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 2090): USE_NETWORK : USE_NETWORK OFF
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): Service discovery started successfully
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 0A.75.42 p2p_dev_addr=0A.75.42 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 },
D/WifiDisplayController( 1018): Received list of peers.,
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28,
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80,
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1018): InactiveState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2787","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
I/io.jxcore.node.ConnectionHelper( 6193): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 6193): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787] already in the list, will not add again
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1018): !@Sync 20,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4278, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/IOP_DB_BT( 2642): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
D/IOP_DB_BT( 2642): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2642): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 2642): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2642): db_query_execute: result 1
,D/IOP_DB_BT( 2642): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 2642): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2642): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 2642): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2642): db_query_execute: result 1
,W/bt-btif ( 2642): info:x10
D/        ( 2642): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2642): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.NAME_CHANGED
,D/BluetoothUtils( 2642): getBtEnabledContainers(): btContainers = []
,E/SMD     (  288): DCD OFF
,D/BluetoothUtils( 2642): getBtEnabledContainers(): btContainers = []
,D/BluetoothUtils( 2642): getBtEnabledContainers(): btContainers = []
,I/BluetoothBondStateMachine( 2642): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.NAME_CHANGED
,D/SecContentProvider( 1018): uri = 4 selection = bluetoothLogForRemote
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.CLASS_CHANGED
,E/bt-btif ( 2642): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2642): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
D/BtConfig.SecureMode( 2642): isSecureModeOn:false
I/BluetoothBondStateMachine( 2642): Entering PendingCommandState State
,D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/BluetoothTile( 1179):  onBluetoothPairedDevicesChanged:
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.BOND_STATE_CHANGED,
D/BluetoothTile( 1179):  handleUpdatestate:false name:null
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothNotiBroadcastReceiver( 1325): onReceive
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 6929): BTStateChangeCB is registed
,D/BluetoothHeadset( 6929): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 6929): BluetoothHeadset service is binded
D/GMFPReceiver( 6929): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 6929): jangil::setProperties()
,D/GMFPReceiver( 6929): jangil::printBTStatus()
,D/SettingsProvider( 1018): name = Wearable0001
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
,D/SettingsProvider( 1018): selectionArgs: 10100
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1018): ret = -1
,D/GMFPReceiver( 6929): ::::::::Wearable0001::false
,D/SettingsProvider( 1018): name = Wearable0002
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10100
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/GMFPReceiver( 6929): ::::::::Wearable0002::false
,D/GMFPReceiver( 6929): onServiceConnected() : 1
D/GMFPReceiver( 6929): mBluetoothHeadset = true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/btif_config_util( 2642): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2642): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 2642): Failed to remove device: 58:3F:54:73:64:C0
,D/SecContentProvider( 1018): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2642): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 2642): isSecureModeOn:false
,D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/BluetoothTile( 1179):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1179):  handleUpdatestate:false name:null
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/HidService( 2642): getHidService(): returning com.android.bluetooth.hid.HidService@bf2ac50
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/SettingsProvider( 1018): name = bluetooth_input_device_priority_58:3F:54:73:64:C0
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/BluetoothNotiBroadcastReceiver( 1325): onReceive
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
,D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/HidService( 2642): Saved priority 58:3F:54:73:64:C0 = -1
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,D/SettingsProvider( 1018): name = bluetooth_a2dp_sink_priority_58:3F:54:73:64:C0
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
,D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = bluetooth_headset_priority_58:3F:54:73:64:C0
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,I/BluetoothBondStateMachine( 2642): StableState(): Entering Off State
,E/BluetoothHeadset( 6929): BTStateChangeCB is registed
,D/BluetoothHeadset( 6929): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 6929): BluetoothHeadset service is binded
D/GMFPReceiver( 6929): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 6929): jangil::setProperties()
,D/GMFPReceiver( 6929): jangil::printBTStatus()
,D/SettingsProvider( 1018): name = Wearable0001
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10100
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/GMFPReceiver( 6929): ::::::::Wearable0001::false
D/SettingsProvider( 1018): name = Wearable0002
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10100
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/GMFPReceiver( 6929): ::::::::Wearable0002::false
D/GMFPReceiver( 6929): onServiceConnected() : 1
D/GMFPReceiver( 6929): mBluetoothHeadset = true
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,W/bt-btif ( 2642): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2642): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2642): bta_dm_pm_ssr:2, lat:1200
,D/BluetoothSocket( 6193): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@1079eb74
,E/BluetoothRemoteDevices( 2642): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): Incoming connection accepted
,D/BluetoothSocket( 6193): getInputStream(): myUserId = 0
,D/BluetoothSocket( 6193): getOutputStream(): myUserId = 0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): Incoming connection initialized (thread ID: 1118),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6193): Entering thread (ID: 1118)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): onBytesRead: Read 77 bytes successfully (thread ID: 1118)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): Got valid identity from [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): onBytesWritten: 83 bytes successfully written (thread ID: 1118)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): removeThreadFromList: Removing thread with ID 1118
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): Handshake thread disposed (thread ID: 1118)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): onIncomingConnectionConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6193): Exiting thread (ID: 1118)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
,I/io.jxcore.node.ConnectionHelper( 6193): onConnected: Incoming connection to peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/io.jxcore.node.ConnectionHelper( 6193): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
,W/io.jxcore.node.ConnectionHelper( 6193): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787] already in the list, will not add again
,D/BluetoothSocket( 6193): getInputStream(): myUserId = 0
,D/BluetoothSocket( 6193): getOutputStream(): myUserId = 0
,I/io.jxcore.node.ConnectionHelper( 6193): onConnected: Incoming socket thread, for peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], created successfully
,D/io.jxcore.node.ConnectionHelper( 6193): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 6193): Entering thread (ID: 1119)
,D/EnterpriseController(  278): uids 10175
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10175
,I/jxcore-log( 6193): 2016-01-05T00:48:18.437Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6193): 
,I/io.jxcore.node.IncomingSocketThread( 6193): Local host address: localhost/127.0.0.1, port: 40261
,D/io.jxcore.node.IncomingSocketThread( 6193): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6193): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 6193): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 6193): startStreamCopyingThreads: OK
,D/io.jxcore.node.IncomingSocketThread( 6193): Exiting thread (ID: 1119)
,D/io.jxcore.node.StreamCopyingThread( 6193): Entering thread (ID: 1121, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6193): Entering thread (ID: 1120, name: Sender)
,I/jxcore-log( 6193): 2016-01-05T00:48:19.380Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:19.388Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:19.394Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:19.401Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:19.482Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:19.519Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:19.548Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:19.585Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:19.666Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:19.676Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:19.687Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:19.692Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:19.748Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:19.754Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:19.777Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:19.783Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:19.820Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:19.856Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:19.862Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:19.908Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:19.915Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:19.921Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:19.955Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:19.982Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:19.991Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:19.997Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:20.004Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:20.035Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:20.083Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:20.123Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:20.152Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:20.181Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:20.196Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:20.218Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:20.224Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:20.310Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:20.316Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:20.356Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:20.382Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:20.422Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:20.447Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:20.461Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:20.495Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:20.517Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:48:20.524Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6193): 
,E/SMD     (  288): DCD OFF
,W/bt-btif ( 2642): invalid rfc slot id: 10
,W/io.jxcore.node.StreamCopyingThread( 6193): Either failed to read from the output stream or write to the input stream (thread ID: 1121, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6193): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6193): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1119
D/io.jxcore.node.IncomingSocketThread( 6193): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 6193): doStop: Thread ID: 1121
D/io.jxcore.node.IncomingSocketThread( 6193): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6193): doStop: Thread ID: 1120
,D/io.jxcore.node.IncomingSocketThread( 6193): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6193): closeLocalSocketAndStreams: Closing the local input stream...
,D/io.jxcore.node.IncomingSocketThread( 6193): closeLocalSocketAndStreams: Closing the local output stream...
,W/io.jxcore.node.StreamCopyingThread( 6193): Either failed to read from the output stream or write to the input stream (thread ID: 1120, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 6193): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6193): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 6193): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6193): closeBluetoothSocketAndStreams
,D/BluetoothSocket( 6193): close() in, this: android.bluetooth.BluetoothSocket@395ec89d, channel: 6, state: CONNECTED
,D/BluetoothSocket( 6193): close() this: android.bluetooth.BluetoothSocket@395ec89d, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@14e97112, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@dc4d0e3mSocket: android.net.LocalSocket@7044ae0 impl:android.net.LocalSocketImpl@14e45199 fd:FileDescriptor[114]
D/BluetoothSocket( 6193): Closing mSocket: android.net.LocalSocket@7044ae0 impl:android.net.LocalSocketImpl@14e45199 fd:FileDescriptor[114]
,D/BluetoothSocket( 6193): close() in, this: android.bluetooth.BluetoothSocket@395ec89d, channel: 6, state: CLOSED
,D/BluetoothSocket( 6193): close() in, this: android.bluetooth.BluetoothSocket@395ec89d, channel: 6, state: CLOSED
,D/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6193): Exiting thread (ID: 1121, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 6193): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6193): Exiting thread (ID: 1120, name: Sender)
,I/jxcore-log( 6193): 2016-01-05T00:48:20.907Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6193): 
,W/bt-rfcomm( 2642): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
,W/bt-rfcomm( 2642): RFCOMM_DisconnectInd LCID:0x4b
,E/SMD     (  288): DCD OFF
,E/bt-btm  ( 2642): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2642): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1179): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothUtils( 2642): getBtEnabledContainers(): btContainers = []
,D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1018): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1325): Received android.bluetooth.device.action.ACL_DISCONNECTED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,E/BluetoothEventManager( 1325): ACTION_ACL_DISCONNECTED
,D/BluetoothAdapterService( 2642): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@984f88e
,D/BtConfig.SecureMode( 2642): isSecureModeOn:false
,D/SecContentProvider( 1018): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/KeyguardViewMediator( 1179): isGear1: device is not B1!
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2642): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 6147): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6147): Bluetooth Device Name: G3-1
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): setState: RESTARTING
D/WifiP2pService( 1018): InactiveState{ what=139268 },
I/wpa_supplicant( 2090): P2P-FIND-STOPPED 
,D/WifiP2pService( 1018): InactiveState{ what=147493 },
D/WifiP2pService( 1018): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1018): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): Start timer timeout, starting now...
,D/WifiP2pService( 1018): InactiveState{ what=139265 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139265 }
D/WifiService( 1018): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1018): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1018): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 2090): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1018): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): P2P device discovery started successfully,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,E/Watchdog( 1018): !@Sync 21
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1018): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1018): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42,
D/WifiP2pService( 1018): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1018): InactiveState{ what=139301 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/WifiP2pService( 1018): P2pEnabledState{ what=139301 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/WifiP2pService( 1018): P2pEnabledState add service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): restart: Restarting...
D/WifiP2pManager( 6193): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): Service request added successfully
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiP2pService( 1018): InactiveState{ what=139310 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1018): P2pEnabledState discover services
D/WifiService( 1018): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1018): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1018): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [13]
I/wpa_supplicant( 2090): USE_NETWORK : USE_NETWORK OFF
I/wpa_supplicant( 2090): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): Service discovery started successfully
,I/wpa_supplicant( 2090): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 2090): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/SMD     (  288): DCD OFF
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4272, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6753","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
I/io.jxcore.node.ConnectionHelper( 6193): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6193): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753] already in the list, will not add again,
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2787","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
,I/io.jxcore.node.ConnectionHelper( 6193): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 6193): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787] already in the list, will not add again
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
I/wpa_supplicant( 2090): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
,D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4280, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/jxcore-log( 6193): timeout now
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): weAreDoneNow, resultArray.length: 4
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): sendReportNow
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): done, now sending data to server
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): 2016-01-05T00:49:03.615Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6193): 
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4281, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2642): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2642): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 600s ago
,E/Watchdog( 1018): !@Sync 22
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): setState: RESTARTING
D/WifiP2pService( 1018): InactiveState{ what=139268 }
,I/wpa_supplicant( 2090): P2P-FIND-STOPPED 
,D/WifiP2pService( 1018): InactiveState{ what=147493 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1018): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/jxcore-log( 6193): teardown
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): testSendData stopped
I/jxcore-log( 6193): 
,I/io.jxcore.node.ConnectionHelper( 6193): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): shutdown
D/BluetoothSocket( 6193): close() in, this: android.bluetooth.BluetoothSocket@2b698c5e, channel: 6, state: LISTENING
D/BluetoothSocket( 6193): close() this: android.bluetooth.BluetoothSocket@2b698c5e, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@34334481, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1369983fmSocket: android.net.LocalSocket@3013350c impl:android.net.LocalSocketImpl@259f6e55 fd:FileDescriptor[113]
D/BluetoothSocket( 6193): Closing mSocket: android.net.LocalSocket@3013350c impl:android.net.LocalSocketImpl@259f6e55 fd:FileDescriptor[113]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6193): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6193): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6193): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6193): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6193): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6193): release: No more listeners, de-initializing...
,D/WifiP2pService( 1018): InactiveState{ what=139298 }
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6193): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6193): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6193): setState: NOT_STARTED
,I/jxcore-log( 6193): StopBroadcasting went ok
I/jxcore-log( 6193): 
,D/WifiP2pService( 1018): P2pEnabledState{ what=139298 }
,D/WifiP2pService( 1018): P2pEnabledState clear service
,I/jxcore-log( 6193): 2016-01-05T00:49:24.687Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 6193): 
,I/io.jxcore.node.ConnectionHelper( 6193): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6193): onDiscoveryManagerStateChanged: NOT_STARTED
,I/chromium( 6193): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiP2pService( 1018): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6193): Local services cleared successfully
,I/jxcore-log( 6193): ****TEST TOOK:  ms ****
I/jxcore-log( 6193): 
,I/jxcore-log( 6193): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
I/jxcore-log( 6193): 
D/WifiP2pService( 1018): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6193): P2P device discovery stopped successfully
D/WifiP2pService( 1018): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6193): Service requests cleared successfully
D/WifiP2pService( 1018): P2pEnabledState clear service request
D/WifiP2pService( 1018): remove channel information from framework
,D/AndroidRuntime( 7032): ,
D/AndroidRuntime( 7032): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7032): CheckJNI is OFF,
D/AndroidRuntime( 7032): readGMSProperty: start
D/AndroidRuntime( 7032): readGMSProperty: already setted!!
D/AndroidRuntime( 7032): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 7032): readGMSProperty: could not set the property(default)!!,
D/AndroidRuntime( 7032): readGMSProperty: end
D/AndroidRuntime( 7032): addProductProperty: start
,E/AffinityControl( 7032): AffinityControl: registerfunction enter
,D/AndroidRuntime( 7032): Calling main entry com.android.commands.pm.Pm,
,D/PackageManager( 1018): START PACKAGE DELETE: observer{749169703},
D/PackageManager( 1018): pkg{<packageName>}
D/PackageManager( 1018): user{0}
D/PackageManager( 1018): caller{2000}
D/PackageManager( 1018): flags{3}
,D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1018): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved : true,
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:0,
D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1018): !@killApplicatoin: 10175, uninstall pkg,
,I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10175 user=-1: uninstall pkg
,I/ActivityManager( 1018): Killing 6193:com.test.thalitest/u0a175 (adj 0): stop com.test.thalitest cause uninstall pkg
,W/PackageSettings( 1018): Skipping PackageSetting{65c03d com.example.hello/10176} due to missing metadata
,I/WindowState( 1018): WIN DEATH: Window{94bcf17 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  257): id=14 Removed NainActivit (6/8)
,I/SurfaceFlinger(  257): id=14 Removed NainActivit (-2/8)
,I/ActivityManager( 1018):   Force finishing activity ActivityRecord{21701d6a u0 com.test.thalitest/.MainActivity t231}
,I/SurfaceFlinger(  257): id=14 Removed NainActivit (-2/8)
,D/InputDispatcher( 1018): Focus left window: 6193
,W/ActivityManager( 1018): mDVFSHelper.acquire(),
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,W/ActivityManager( 1018): Spurious death for ProcessRecord{13671ed4 6193:com.test.thalitest/u0a175}, curProc for 6193: null
,D/InputDispatcher( 1018): Focused application released
,I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10175 user=0: pkg removed
,W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
,I/DBG_DM  ( 3005): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,I/art     ( 6147): Explicit concurrent mark sweep GC freed 23201(1185KB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 9MB/12MB, paused 854us total 45.170ms
,I/DBG_DM  ( 3005): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 11
,I/art     ( 5104): Explicit concurrent mark sweep GC freed 2369(132KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 778us total 32.746ms
,I/DBG_DM  ( 3005): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,E/SamsungIME( 1785): mOCRHelper is null
,I/DBG_DM  ( 3005): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3005): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 11
,I/DBG_DM  ( 3005): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,W/GeofencerStateMachine( 1655): Ignoring removeGeofence because network location is disabled.
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,I/DBG_DM  ( 3005): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,D/RegisteredComponentCache( 1444): Collect Tech packages for Knox
,D/PersonaManager( 1444): isKioskContainerExistOnDevice
,I/KLMS-2.5.183: ( 3622): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 05 01:49:25 GMT+01:00 2016
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/DBG_DM  ( 3005): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3005): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/KLMS-2.5.183: ( 3622): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1018): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=28
I/splitIntent( 1018): base  index=28, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1018): other index=31, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0,
W/TextServicesManagerService( 1018): no available spell checker services found
D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3622): KLMSIntentService(): onCreate()
,E/Zygote  ( 7045): MountEmulatedStorage(),
E/Zygote  ( 7045): v2
I/libpersona( 7045): KNOX_SDCARD checking this for 10094
I/libpersona( 7045): KNOX_SDCARD not a persona
,I/SELinux ( 7045): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 7045): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7045 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 7045): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
,I/DBG_DM  ( 3005): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 11
,I/KLMS-2.5.183: ( 3622): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/DBG_DM  ( 3005): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PersonaManager( 1444): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1444): empty dynamic service
,D/TimaKeyStoreProvider( 7045): TimaSignature is unavailable
,D/ActivityThread( 7045): Added TimaKeyStore provider
,I/DBG_DM  ( 3005): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3005): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3005): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/DBG_DM  ( 3005): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 62014(7MB) AllocSpace objects, 57(912KB) LOS objects, 33% free, 27MB/41MB, paused 2.944ms total 202.538ms
,I/KLMS-2.5.183: ( 3622): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/art     ( 1018): WaitForGcToComplete blocked for 202.276ms for cause Explicit
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,I/DBG_DM  ( 3005): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,I/KLMS-2.5.183: ( 3622): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/SurfaceFlinger(  257): id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,I/KLMS-2.5.183: ( 3622): KLMSIntentService(): PACKAGE_REMOVED
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/KLMS-2.5.183: ( 3622): KLMSIntentService(): listeningToPackageRemoved().START
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/KLMS-2.5.183: ( 3622): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/InputDispatcher( 1018): Focus entered window: 3005
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 3005): log_dcs ThreadedRenderer::initialize entered! 
,V/ActivityThread( 3005): updateVisibility : ActivityRecord{1c82e300 token=android.os.BinderProxy@2ff068f1 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/elm:15183( 7045): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15183( 7045): ELMEngine.ELMEngine( context ).
,D/elm:15183( 7045): MDMBridge.setEnterpriseBridge()
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/elm:15183( 7045): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15183( 7045): ElmAgentService : onCreate()
,D/elm:15183( 7045): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 7045): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 7045): MDMBridge.getInstance()
D/elm:15183( 7045): MDMBridge.getAllLicenseInfoFromSDK()
,W/InputMethodManagerService( 1018): Got RemoteException sending setActive(false) notification to pid 6193 uid 10175
,D/elm:15183( 7045): MDMBridge.getAllLicenseInfoFromSDK()
,I/Timeline( 3005): Timeline: Activity_idle id: android.os.BinderProxy@2ff068f1 time:687466
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/KLMS-2.5.183: ( 3622): KLMSIntentService(): listeningToPackageRemoved().END
,D/SamsungIME( 1785): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,W/ActivityManager( 1018): mDVFSHelper.release()
I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{3fd9f117 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t230} time:687477
,I/KLMS-2.5.183: ( 3622): KLMSIntentService(): onDestroy()
,D/elm:15183( 7045): ElmAgentService : onDestroy().
,I/ActivityManager( 1018): Killing 6046:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 13960(663KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 4.367ms total 211.771ms
,D/RCPManagerService( 1018): PackageReceiver onReceive()
I/HarmonyEASService( 1018): onReceive : android.intent.action.PACKAGE_REMOVED for 0
W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1018): PackageRemovalReceiver::onReceive Enter
,D/OTPFW   ( 1018): OtpDbHelper::getInstance New instance created
,D/OTPFW   ( 1018): DBIntegrity::getInstance - New instance created
,D/OTPFW   ( 1018): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10175 container id = 0
,I/OTPFW   ( 1018): ProvisionData::getAllEntries Enter
,E/OTPFW   ( 1018): ProvisionData::getAllEntries Table is empty
,D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1018): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10175
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10175
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,D/TaskPersister( 1018): removeObsoleteFile: deleting file=231_task.xml
,D/TaskPersister( 1018): removeObsoleteFile: deleting file=230_task.xml
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager( 1018): delete codoeFile: ,
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,I/AASA_removePackage( 1018): UID=10175 Target=com.test.thalitest
D/AASAuninstall( 1018): userId = 0, info.removedAppID = -1, info.uid = 10175, packageName = com.test.thalitest
,D/PackageManager( 1018): result of delete: 1{749169703}
,W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PCWCLIENTTRACE_PushUtil( 5808): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5808): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5808): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5808): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/PanelView( 1179): There is/are notification(s) 
,D/AndroidRuntime( 7032): Shutting down VM
,E/Zygote  ( 7065): MountEmulatedStorage()
,E/Zygote  ( 7065): v2
I/libpersona( 7065): KNOX_SDCARD checking this for 10032
I/libpersona( 7065): KNOX_SDCARD not a persona
,I/SELinux ( 7065): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7065 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 7065): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 7065): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/TimaKeyStoreProvider( 7065): TimaSignature is unavailable
,D/ActivityThread( 7065): Added TimaKeyStore provider
D/UsbSettingsManager( 1018): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1018): onPackageRemoved : com.test.thalitest
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_6046/cgroup.procs: No such file or directory
,I/FeatureConfig( 7065): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/SA      ( 6115): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,I/SA      ( 6115): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10175 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/ActivityManager( 1018): Killing 6070:com.sec.knox.bridge/1000 (adj 15): empty #31
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,W/ResourcesManager( 7065): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7065): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7065): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 7065): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/Zygote  ( 7083): MountEmulatedStorage()
E/Zygote  ( 7083): v2
I/libpersona( 7083): KNOX_SDCARD checking this for 10044
I/libpersona( 7083): KNOX_SDCARD not a persona
I/SELinux ( 7083): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 7083): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1018): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7083 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
E/SELinux ( 7083): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
W/ResourcesManager( 7065): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 7083): TimaSignature is unavailable
,W/ResourcesManager( 7065): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ActivityThread( 7083): Added TimaKeyStore provider
,I/art     (  304): Explicit concurrent mark sweep GC freed 8683(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 26.325ms
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_6070/cgroup.procs: No such file or directory
W/ResourcesManager( 7065): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 7065): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 7065): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 637us total 17.906ms
,W/ResourcesManager( 7083): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7083): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7083): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7083): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7083): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7083): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7083): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7083): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 7065): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7065): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 673us total 17.852ms
,W/ResourcesManager( 7065): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7065): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 7065): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 7065): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/art     ( 7032): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,W/ResourcesManager( 7065): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7065): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7065): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7065): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 7065): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 7065): system/finder_cp/cpdata.xml file not found
,D/NearbySource( 7083): Nearby Source Create!
,D/NearbyContext( 7083): Nearby Context Create!
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7083): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 7083): Samsung link source created
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,E/SQLiteLog( 7083): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
,D/ContactProvider( 7083): getAllContactInfoList Start
,E/SQLiteDatabase( 7083): Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
E/SQLiteDatabase( 7083): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7083): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7083): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7083): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7083): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7083): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7083): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7083): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 7083): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 7083): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7083): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 7083): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7083): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7083): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7083): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteDatabase( 7083): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteDatabase( 7083): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteDatabase( 7083): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:211)
E/SQLiteDatabase( 7083): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:203)
E/SQLiteDatabase( 7083): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 7083): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
E/SQLiteDatabase( 7083): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 7083): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 7083): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7083): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7083): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 7083): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7083): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7083): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 7083): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SQLiteOpenHelper( 7083): Couldn't open local.db for writing (will try read-only):
E/SQLiteOpenHelper( 7083): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7083): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7083): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 7083): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 7083): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7083): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7083): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7083): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 7083): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 7083): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 7083): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 7083): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 7083): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7083): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7083): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteOpenHelper( 7083): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteOpenHelper( 7083): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteOpenHelper( 7083): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:211)
E/SQLiteOpenHelper( 7083): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:203)
E/SQLiteOpenHelper( 7083): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 7083): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
E/SQLiteOpenHelper( 7083): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteOpenHelper( 7083): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteOpenHelper( 7083): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7083): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 7083): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 7083): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 7083): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 7083): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 7083): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/SQLiteOpenHelper( 7083): Opened local.db in read-only mode
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/ContactProvider( 7083): getAllContactInfoList End
,I/syncContacts( 7083): thread: 1163, sync time = 30
,I/PackagesMonitor( 7083): PackagesMonitor onReceive :com.test.thalitest
,E/SharedPreferencesImpl( 7083): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7105): MountEmulatedStorage(),
E/Zygote  ( 7105): v2
I/libpersona( 7105): KNOX_SDCARD checking this for 10046
I/libpersona( 7105): KNOX_SDCARD not a persona
,I/SELinux ( 7105): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1018): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=7105 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 4449:com.google.android.gms.wearable/u0a12 (adj 15): empty #31
,I/SELinux ( 7105): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 7105): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL

```
