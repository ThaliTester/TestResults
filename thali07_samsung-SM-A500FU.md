#### Test 549702617e2936d_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
D/ComposerPerformance( 5750): 1452525631293 ms / [DONE] Composer constructor
E/CII     ( 5750): CommonIMSInterface: VoLTE CSC feature disabled.
I/DBG_POLICYDM( 5816): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/DBG_POLICYDM( 5816): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
I/DBG_POLICYDM( 5816): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
I/DBG_POLICYDM( 5816): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
I/Mms/ReservationManager( 5750): ReservationManager()
I/Mms/ReservationManager( 5750): resetAfterConnected()
I/DBG_POLICYDM( 5816): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
I/DBG_POLICYDM( 5816): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
D/TP/MmsSmsProvider( 1479): query,matched:7, calling pid = 5750
I/DBG_POLICYDM( 5816): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
D/TP/MmsSmsProvider( 1479): match 7:Elapsed time : 1.239 ms
I/DBG_POLICYDM( 5816): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
D/Mms/Conversation( 5750): [start]    init() consume time = 26.542448
D/TP/MmsSmsProvider( 1479): deleteConversation threadId: 9223372036854775807
I/DBG_POLICYDM( 5816): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
D/TP/MmsSmsProvider( 1479): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
I/TapandpayWidget:TapandpayAppWidgetProvider( 5889): onReceive()
V/TP/MmsSmsDatabaseHelper( 1479): updateThread(), thread_id = 9223372036854775807
D/TapandpayWidget:TapandpayAppWidgetProvider( 5889): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
V/TP/MmsSmsDatabaseHelper( 1479): sUpgradeVersion = 0, db.getVersion() = 81
D/TP/MmsSmsProvider( 1479): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1479): need read changed broadcast:false
D/Mms/Conversation( 5750): [end]    init consume time = 12.36651
D/Mms/MessagingNotification( 5750): [start]    init() consume time = 1.185938
I/Mms/ReservationManager( 5750): getReservedSendMessageCount(): retMessageCount=0
D/Mms/MessagingNotification( 5750): [end]    init consume time = 1.813437
I/TapandpayWidget:Utils( 5889): Clear T&P info.
D/TP/MmsSmsProvider( 1479): query,matched:0, calling pid = 5750
V/TP/MmsSmsProvider( 1479): getSimpleConversations entered.
D/Mms/MmsApp( 5750): [end]    onCreate() consume time = 3.354011
D/TP/MmsSmsProvider( 1479): match 0:Elapsed time : 1.306 ms
--------- beginning of system
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/Mms/Synchronizer( 5750): [start]    doSync consume time = 9.2
I/DBG_POLICYDM( 5816): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
E/Zygote  ( 5922): MountEmulatedStorage()
E/Zygote  ( 5922): v2
I/libpersona( 5922): KNOX_SDCARD checking this for 10072
I/libpersona( 5922): KNOX_SDCARD not a persona
I/SELinux ( 5922): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 5922): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5922): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5922 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/Mms/SpamFilter( 5750): [start]    SpamFilter fill() begin consume time = 20.077135
D/Mms/DownloadManager( 5750): Service state changed: Bundle[mParcelledData.dataSize=744]
D/TP/MmsSmsProvider( 1479): update, matched:300, calling pid = 5750
V/TP/MmsSmsProvider( 1479): syncDBData start
V/TP/MmsSmsProvider( 1479): syncDBData sms end
V/TP/MmsSmsProvider( 1479): syncDBData mms end
V/TP/MmsSmsProvider( 1479): syncDBData end
D/Mms/DownloadManager( 5750): roaming ------> false, mSimSlot = 0
D/Mms/MethodReflector( 5750): getSubId is called
D/Mms/TelephonyUtils( 5750): getLongSubId from simSlot 0, return Value = -1
D/Mms/Synchronizer( 5750): [end]    doSync consume time = 11.255417
D/TimaKeyStoreProvider( 5922): TimaSignature is unavailable
D/TP/MmsSmsProvider( 1479): query,matched:400, calling pid = 5750
D/Mms/MethodReflector( 5750): getTelephonyProperty is called
D/Mms/DownloadManager( 5750): roaming -> false (slotId = 0)
D/ActivityThread( 5922): Added TimaKeyStore provider
D/Mms/DownloadManager( 5750): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5750): auto download without roaming -> true
D/Mms/DownloadManager( 5750): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5750): mAutoDownload ------> true
D/Mms/SpamFilter( 5750): [end]    SpamFilter fill() finished consume time = 18.772604
D/Mms/ArtClassLoader( 5750): init [DONE] art
D/BadgeProvider( 5922): onCreate
D/BadgeProvider( 5922): DatabaseHelper
D/TapandpayWidget:TapandpayAppWidgetProvider( 5889): Widget is not attached.
D/Mms/MessagingNotification( 5750): checkBadgeCount unreadCount=0 badgeCount=0
D/TP/SmsProvider( 1479): query,matched:26, calling pid = 5750
D/TP/SmsProvider( 1479): match 26:Elapsed time : 0.914 ms
I/ActivityManager( 1017): Killing 5284:com.sec.spp.push:RemoteDlcProcess/u0a35 (adj 15): empty #31
D/TP/MmsSmsProvider( 1479): query,matched:6, calling pid = 5750
D/TP/MmsSmsProvider( 1479): match 6:Elapsed time : 1.504 ms
D/Mms/FreeMessageStatusReceiver( 5750): onReceive, action : android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
I/DBG_POLICYDM( 5816): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/PackageBroadcastService( 1867): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5941): MountEmulatedStorage()
E/Zygote  ( 5941): v2
I/libpersona( 5941): KNOX_SDCARD checking this for 10047
I/libpersona( 5941): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5941 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
I/SELinux ( 5941): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SELinux ( 5941): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5941): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 5816): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
D/TimaKeyStoreProvider( 5941): TimaSignature is unavailable
D/ActivityThread( 5941): Added TimaKeyStore provider
E/Zygote  ( 5958): MountEmulatedStorage()
E/Zygote  ( 5958): v2
I/libpersona( 5958): KNOX_SDCARD checking this for 10025
I/libpersona( 5958): KNOX_SDCARD not a persona
I/SELinux ( 5958): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5958 uid=10025 gids={50025, 9997} abi=armeabi-v7a
I/SELinux ( 5958): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5958): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ChimeraCfgMgr( 1867): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1867): Loading module APK com.google.android.play.games
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 5958): TimaSignature is unavailable
D/ActivityThread( 5958): Added TimaKeyStore provider
I/DBG_POLICYDM( 5816): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
I/ActivityManager( 1017): Killing 5165:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SMD     (  287): DCD OFF
W/ResourcesManager( 5958): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/Mms/FreeMessageReceiverService( 5750): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5750): onHandleIntent: ACTION_PACKAGE_ADDED
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1017): Killing 3863:com.google.android.talk/u0a104 (adj 15): empty #31
I/ActivityManager( 1017): Killing 3837:com.android.providers.calendar/u0a42 (adj 15): empty #32
I/SL_DEBUG( 5872): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5872): isLoggable:: SL_DEBUG_EXIST = false
W/ResourcesManager( 5941): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5941): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5941): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/ServiceManager(  317): Waiting for service AtCmdFwd...
I/OMACP   ( 5958): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
W/libprocessgroup( 1017): failed to open /acct/uid_10035/pid_5284/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5165/cgroup.procs: No such file or directory
D/Mms/Omacp( 5750): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
I/OMACP   ( 5958): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 5958): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 5958): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/DBG_POLICYDM( 5816): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
I/OMACP   ( 5958): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 5958): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 5958): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 5958): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
W/libprocessgroup( 1017): failed to open /acct/uid_10042/pid_3837/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10104/pid_3863/cgroup.procs: No such file or directory
I/OMACP   ( 5958): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 5958): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 5958): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 5958): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 5958): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 5958): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
D/MyFiles ( 5941): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
I/ActivityManager( 1017): Killing 5438:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
E/installd(  283): system dir 0 : /system/app/
E/installd(  283): system dir 1 : /system/priv-app/
E/installd(  283): system dir 2 : /vendor/app/
E/installd(  283): system dir 3 : /oem/app/
I/TactileAssist( 1017): enable value -1
I/TactileAssist( 1017): internal enable value -1
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/TactileAssist( 1017): intensity value -1
I/TactileAssist( 1017): saveAppList value true
I/DBG_POLICYDM( 5816): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/TactileAssist( 1017): List of disabled apps :
I/ConfigFetchService( 1867): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1867): launchTask
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 5816): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
E/Zygote  ( 5983): MountEmulatedStorage()
E/Zygote  ( 5983): v2
I/libpersona( 5983): KNOX_SDCARD checking this for 10053
I/libpersona( 5983): KNOX_SDCARD not a persona
I/SELinux ( 5983): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/PackageManager( 1017): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
I/SELinux ( 5983): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5983): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5983 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/ConfigFetchTask( 1867): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1VnUzRysUPPPXWr8cOc5NUCJSTyHRVAzQWaeay-hXKPCQT0Lf7czAHvE7FOxCJOKw39misaRLyRB8uwXJFzlhPrEMcaLIGfzDi1ApbyP6dPdetfR4jFw4cNOYOCLW-5FJ8ree0j3AHkxZucLwTDuEWCuUHXbT2iXx1xPF7250Jh9YbpMZ-kN87Pr7cLXomlU4oGYQ5h8HwQ3WO6MtTx-l5YdbBPjZwfuyOQ6Nq1B6xeqaMz_XM
I/PeopleContactsSync( 1867): CP2 sync disabled
D/ChimeraCfgMgr( 1867): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1867): Module APK com.google.android.play.games already loaded
D/TimaKeyStoreProvider( 5983): TimaSignature is unavailable
D/ActivityThread( 5983): Added TimaKeyStore provider
W/libprocessgroup( 1017): failed to open /acct/uid_10069/pid_5438/cgroup.procs: No such file or directory
W/ResourcesManager( 5983): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/GAv4    ( 5766): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5766):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5766):   adb logcat -s GAv4
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5872): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
D/ChimeraCfgMgr( 1867): Loading module com.google.android.gms.vision from APK com.google.android.gms
I/GoogleURLConnFactory( 1867): Using platform SSLCertificateSocketFactory
D/Vision  ( 1867): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Vision  ( 1867): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1867): No vision deps
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/GAv4    ( 5766): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 5766): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 5766): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
D/Compatibility( 5983): onReceive() it will make start service
W/AnalyticsTrackerProxyImpl( 5766): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5983): onHandleIntent()
D/Compatibility( 5983): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10175, android.intent.extra.user_handle=0}]
D/Compatibility( 5983): found: 2
E/Zygote  ( 6007): MountEmulatedStorage()
E/Zygote  ( 6007): v2
I/libpersona( 6007): KNOX_SDCARD checking this for 1000
I/libpersona( 6007): KNOX_SDCARD not a persona
I/SELinux ( 6007): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6007 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6007): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6007): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6007): TimaSignature is unavailable
D/ActivityThread( 6007): Added TimaKeyStore provider
D/Compatibility( 5983): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5983): skipping ResolveInfo{18a13fcc com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5983): considering ResolveInfo{1e08215 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5983): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5983): enabling receiver ResolveInfo{2577f92a com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5983): enabling receiver ResolveInfo{227c131b com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5983): enabling receiver ResolveInfo{1e888cb8 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5983): enabling receiver ResolveInfo{29542a91 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5983): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
W/ContextImpl( 6007): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/System.out( 1867): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1867): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1867): (HTTPLog)-Static: isShipBuild true
I/System.out( 1867): (HTTPLog)-Thread-264-683838228: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1867): (HTTPLog)-Static: isSBSettingEnabled false
E/Zygote  ( 6027): MountEmulatedStorage()
E/Zygote  ( 6027): v2
I/libpersona( 6027): KNOX_SDCARD checking this for 1000
I/libpersona( 6027): KNOX_SDCARD not a persona
I/SELinux ( 6027): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6027): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=6027 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 6027): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/art     ( 5766): Suspending all threads took: 9.445ms
D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5872): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/TimaKeyStoreProvider( 6027): TimaSignature is unavailable
D/ActivityThread( 6027): Added TimaKeyStore provider
I/ActivityManager( 1017): Killing 5453:com.sec.knox.bridge/1000 (adj 15): empty #31
V/AlarmManager( 1017): waitForAlarm result :4
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ResourcesManager( 6027): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
I/System.out( 1867): KnoxVpnUidStorageknoxVpnSupported API value returned is false
W/BaseAppContext( 1867): Using Auth Proxy for data requests.
W/BaseAppContext( 1867): Using Auth Proxy for data requests.
I/qtaguid ( 1867): Tagging socket 93 with tag 40b00000000{1035,0} for uid -1, pid: 1867, getuid(): 10012
W/BaseAppContext( 1867): Using Auth Proxy for data requests.
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5453/cgroup.procs: No such file or directory
W/BaseAppContext( 1867): Using Auth Proxy for data requests.
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6049): MountEmulatedStorage()
E/Zygote  ( 6049): v2
I/libpersona( 6049): KNOX_SDCARD checking this for 1000
I/libpersona( 6049): KNOX_SDCARD not a persona
I/SELinux ( 6049): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6049 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 5469:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
I/qtaguid ( 1867): Tagging socket 108 with tag 40b00000000{1035,0} for uid -1, pid: 1867, getuid(): 10012
I/SELinux ( 6049): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6049): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 1684): Explicit concurrent mark sweep GC freed 18161(1058KB) AllocSpace objects, 3(108KB) LOS objects, 39% free, 10MB/17MB, paused 1.061ms total 46.549ms
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6068): MountEmulatedStorage()
E/Zygote  ( 6068): v2
I/libpersona( 6068): KNOX_SDCARD checking this for 10041
I/libpersona( 6068): KNOX_SDCARD not a persona
I/SELinux ( 6068): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6068): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=6068 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6068): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6049): TimaSignature is unavailable
D/ActivityThread( 6049): Added TimaKeyStore provider
W/BaseAppContext( 1867): Using Auth Proxy for data requests.
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ResourcesManager( 6049): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ContextImpl( 5766): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.docs/cache
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5469/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 6068): TimaSignature is unavailable
D/ActivityThread( 6068): Added TimaKeyStore provider
I/qtaguid ( 1867): Untagging socket 93
I/ConfigFetchService( 1867): fetch service done; releasing wakelock
I/ConfigFetchService( 1867): stopping self
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
I/ActivityManager( 1017): Killing 5369:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
I/ActivityManager( 1017): Killing 4944:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
W/ResourcesManager( 5766): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
I/SA      ( 6068): [SSP] onCreated
W/ResourcesManager( 5766): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/JavaBinder( 1017): !!! FAILED BINDER TRANSACTION !!!
W/BroadcastQueue( 1017): Exception when sending broadcast to ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver}
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
E/Zygote  ( 6089): MountEmulatedStorage()
E/Zygote  ( 6089): v2
I/libpersona( 6089): KNOX_SDCARD checking this for 10057
I/libpersona( 6089): KNOX_SDCARD not a persona
I/SELinux ( 6089): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6089 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
I/SELinux ( 6089): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/AndroidRuntime( 6083): 
D/AndroidRuntime( 6083): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
E/SELinux ( 6089): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 4978:com.google.android.gms:car/u0a12 (adj 15): empty #31
D/AndroidRuntime( 6083): CheckJNI is OFF
D/AndroidRuntime( 6083): readGMSProperty: start
D/AndroidRuntime( 6083): readGMSProperty: already setted!!
D/AndroidRuntime( 6083): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6083): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6083): readGMSProperty: end
D/AndroidRuntime( 6083): addProductProperty: start
D/TimaKeyStoreProvider( 6089): TimaSignature is unavailable
D/ActivityThread( 6089): Added TimaKeyStore provider
I/art     ( 1017): Explicit concurrent mark sweep GC freed 221654(14MB) AllocSpace objects, 4(4MB) LOS objects, 33% free, 27MB/41MB, paused 3.643ms total 230.405ms
I/SA      ( 6068): [TPM] There is no property file
W/BaseAppContext( 1867): Using Auth Proxy for data requests.
I/SA      ( 6068): [SCU] isHaveSA() - false
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
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_4944/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10057/pid_5369/cgroup.procs: No such file or directory
W/ResourceType( 6068): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 6068): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 5
W/ResourceType( 6068): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 6068): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ActivityManager( 1017): Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
W/libprocessgroup( 1017): failed to open /acct/uid_10012/pid_4978/cgroup.procs: No such file or directory
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
I/SA      ( 6068): [SCU] isHaveSA() - false
I/SA      ( 6068): support phone number id : false
I/SA      ( 6068): [DM] Supports Ref Jpn : true
I/SA      ( 6068): [DM] init END
I/SA      ( 6068): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
I/SA      ( 6068): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10175 extra.user_handle.:0 ]
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
I/ActivityManager( 1017): Killing 5588:com.sec.android.diagmonagent/1000 (adj 15): empty #31
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
E/AffinityControl( 6083): AffinityControl: registerfunction enter
V/JNIHelp ( 5766): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6116): MountEmulatedStorage()
I/libpersona( 6116): KNOX_SDCARD checking this for 10010
E/Zygote  ( 6116): v2
I/libpersona( 6116): KNOX_SDCARD not a persona
I/SELinux ( 6116): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6116): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6116): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=6116 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/AndroidRuntime( 6083): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/PowerManagerService( 1017): [PWL] Off : 5s ago
I/PowerManagerService( 1017): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1017): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1017): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1867, ws=null) (elapsedTime=47562)
I/PowerManagerService( 1017): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1017, ws=WorkSource{10054}) (elapsedTime=609)
D/TimaKeyStoreProvider( 6116): TimaSignature is unavailable
D/ActivityThread( 6116): Added TimaKeyStore provider
W/ActivityManager( 1017): mDVFSHelper.acquire()
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1017): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1017): *FMB* installDecor flags : 25362712
E/Zygote  ( 6134): MountEmulatedStorage()
I/libpersona( 6134): KNOX_SDCARD checking this for 10175
E/Zygote  ( 6134): v2
I/libpersona( 6134): KNOX_SDCARD not a persona
I/SELinux ( 6134): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
I/ActivityManager( 1017): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6134 uid=10175 gids={50175, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1017): Focused application set to: xxxx
D/InputDispatcher( 1017): Focus left window: 3002
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  256): id=13 createSurf (1x1),1 flag=404, uhalitest
D/AndroidRuntime( 6083): Shutting down VM
I/SELinux ( 6134): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6134): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5588/cgroup.procs: No such file or directory
I/art     (  304): Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 686us total 24.786ms
D/TimaKeyStoreProvider( 6134): TimaSignature is unavailable
D/ActivityThread( 6134): Added TimaKeyStore provider
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
V/ActivityManager( 1017): Display changed displayId=0
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 993us total 21.965ms
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 608us total 17.431ms
W/art     ( 5766): Suspending all threads took: 19.782ms
D/PersonaManager( 1017): isKioskContainerExistOnDevice
I/SurfaceFlinger(  256): id=11 Removed YUIInstallC (5/9)
V/ActivityThread( 3002): updateVisibility : ActivityRecord{1bc5228 token=android.os.BinderProxy@2d75d5f9 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/splitIntent( 1017): Queue : backgroundsplit_2 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
I/ActivityManager( 1017): Killing 5610:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
W/ActivityThread( 5766): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5766): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1aed3cc6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5766): Installed default security provider GmsCore_OpenSSL
D/KeyguardViewMediator( 1179): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
D/KeyguardViewMediator( 1179): doKeyguard: not showing because lockscreen is off
V/KeyguardEffectViewController( 1179): *** Keyguard wallpaper service already unbounded
W/art     ( 6083): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/WebViewFactory( 6134): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,D/LocationManagerService( 1017): getProviders()=[passive]
,I/LibraryLoader( 6134): Time to load native libraries: 2 ms (timestamps 3768-3770)
I/LibraryLoader( 6134): Expected native library version number "",actual native library version number ""
,W/libprocessgroup( 1017): failed to open /acct/uid_10142/pid_5610/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AcmsKeyStoreHelper( 5829):  getKeyStoreForApplication Enter
,V/WebViewChromiumFactoryProvider( 6134): Binding Chromium to main looper Looper (main, tid 1) {1e888cb8}
,I/LibraryLoader( 6134): Expected native library version number "",actual native library version number ""
I/chromium( 6134): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/AcmsKeyStoreHelper( 5829): Key Store exist
I/AcmsKeyStoreHelper( 5829): Hence loading the keystore file
,I/BrowserStartupController( 6134): Initializing chromium process, singleProcess=true
,W/art     ( 6134): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6134): ApplicationContext is null in ApplicationStatus
,I/UpdateIcingCorporaServi( 6089): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/chromium( 6134): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6134): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6134): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6134): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6134): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6134): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6134): Local Branch: 
I/Adreno-EGL( 6134): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6134): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6134):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/AcmsKeyStoreHelper( 5829):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 5829): getKeyStoreForApplication success 
D/AcmsCore( 5829): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5829): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5829): Decrementing - Counter value: 1
D/AcmsCore( 5829): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 5829): This is NOT a valid MirrorLink app
D/AcmsCore( 5829): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5829): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5829): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5829): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 5829): getSvcCounter - Counter value: 0
,D/AcmsService( 5829): Enter onDestroy
I/AcmsService( 5829): cleanUp(): inside service clean up
,D/AcmsCore( 5829): AcmsCore: inside DeInit
D/AcmsCore( 5829): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 5829): AcmsCertificateMngr: inside cleanup
,D/AcmsRevocationMngr( 5829): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5829): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 5829): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 5829): getSvcCounter - Counter value: 0
,D/AcmsService( 5829): killing acms process
I/Process ( 5829): Sending signal. PID: 5829 SIG: 9
,D/ChimeraCfgMgr( 1867): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1867): Module APK com.google.android.play.games already loaded
I/art     ( 1867): Background sticky concurrent mark sweep GC freed 14233(1063KB) AllocSpace objects, 13(736KB) LOS objects, 13% free, 13MB/15MB, paused 5.462ms total 56.215ms
,I/Mms/MmsApp( 5750):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5750): [start]    fillCache consume time = 1942.482864
D/Mms/ComposeMessageFragment( 5750): fillCache, easy = false
,I/UpdateIcingCorporaServi( 6089): UpdateCorporaTask done [took 143 ms] updated apps [took 143 ms] 
,I/ActivityManager( 1017): Process ACMS.Process (pid 5829)(adj 0) has died(46,1080)
,I/ActivityManager( 1017): Killing 5180:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,D/AbsListView( 5750): Get MotionRecognitionManager
,D/MotionRecognitionService( 1017):  ssp status : false
,D/Mms/ComposeMessageFragment( 5750): [end]    fillCache consume time = 77.074843
,W/ActivityManager( 1017): Activity pause timeout for ActivityRecord{1e13be33 u0 com.test.thalitest/.MainActivity t229}
,D/Mms/BubbleViewCache( 5750): fillCache bubble = 1
,W/art     ( 6134): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6134): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6134): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6134): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6134): CordovaWebView is running on device made by: samsung
W/libprocessgroup( 1017): failed to open /acct/uid_10150/pid_5180/cgroup.procs: No such file or directory
,W/art     ( 6134): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6134): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6134): Render dirty regions requested: true
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
,D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,W/chromium( 6134): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 6134): updateVisibility : ActivityRecord{1f93153d token=android.os.BinderProxy@cf71ae7 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true,
D/PhoneWindow( 6134): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6134): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  256): id=14 createSurf (1x1),1 flag=404, NainActivit,
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/InputDispatcher( 1017): Focus entered window: 6134
,E/Zygote  ( 6189): MountEmulatedStorage()
E/Zygote  ( 6189): v2
I/libpersona( 6189): KNOX_SDCARD checking this for 10012
I/libpersona( 6189): KNOX_SDCARD not a persona
,I/SELinux ( 6189): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/SRIB_DCS( 6134): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6134): Initialized EGL, version 1.4
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1017): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=6189 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 6189): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6189): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/OpenGLRenderer( 6134): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6134): Enabling debug mode 0
,D/TimaKeyStoreProvider( 6189): TimaSignature is unavailable
,D/ActivityThread( 6189): Added TimaKeyStore provider
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/PanelView( 1179): There is/are notification(s) 
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SamsungIME( 1773): getCurrentCandidateView
,I/ActivityManager( 1017): Displayed Component not be shown by security: +812ms (total +916ms)
,I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{1e13be33 u0 com.test.thalitest/.MainActivity t229} time:84390
W/ActivityManager( 1017): mDVFSHelper.release()
,W/ResourcesManager( 6189): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/IInputConnectionWrapper( 6134): showStatusIcon on inactive InputConnection
,I/Timeline( 6134): Timeline: Activity_idle id: android.os.BinderProxy@cf71ae7 time:84397
,W/ResourcesManager( 6189): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/SurfaceFlinger(  256): id=13 Removed uhalitest (7/9)
,I/SurfaceFlinger(  256): id=13 Removed uhalitest (-2/9)
,I/MultiDex( 6189): VM with version 2.1.0 has multidex support
I/MultiDex( 6189): install
I/MultiDex( 6189): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6189): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/BindingManager( 6134): Cannot call determinedVisibility() - never saw a connection for the pid: 6134
,W/ActivityThread( 6189): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/SamsungIME( 1773): Dismiss ExpandCandiate
W/System  ( 6189): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1187d2db: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6189): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1684): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/splitIntent( 1017): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1017): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1017): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SamsungIME( 1773): getDebugLevel  : 0x4f4c
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1684): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/ActivityManager( 1017): Killing 5087:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1867): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SamsungIME( 1773): getDebugLevel  : 0x4f4c
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SamsungIME( 1773): KeybaordView init() : load resources
,D/WearableService( 4436): callingUid 10012, callindPid: 4436
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1696): [186] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SamsungIME( 1773): getCurrentKeyboard
I/SamsungIME( 1773): getTextKeyboard
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,D/SamsungIME( 1773): [SwiftkeyWrapper] currentLangauge : 1701729619
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1867): Restart initialization of location
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1017): failed to open /acct/uid_10040/pid_5087/cgroup.procs: No such file or directory
,D/JsMessageQueue( 6134): Set native->JS mode to OnlineEventsBridgeMode
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/jxcore_app_log( 6134): JniHelper::setJavaVM(0xb7e33450), pthread_self() = -1204235576
,D/JX-Cordova( 6134): jxcore cordova android initializing
,I/DBG_POLICYDM( 5816): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,E/SMD     (  287): DCD OFF
,I/DBG_POLICYDM( 5816): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5816): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5816): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5816): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5816): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
I/DBG_POLICYDM( 5816): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
I/DBG_POLICYDM( 5816): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4166, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2648): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,W/jxcore-log( 6134): Initializing JXcore engine
W/jxcore-log( 6134): JXcore engine is ready
,W/jxcore-log( 6134): Starting JXcore engine
,E/audit   ( 1863): type=1400 msg=audit(1452525635.337:205): avc:  denied  { ioctl } for  pid=6134 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1863):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1863): type=1300 msg=audit(1452525635.337:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=bea91d58 items=0 ppid=304 ppcomm=main pid=6134 auid=4294967295 uid=10175 gid=10175 euid=10175 suid=10175 fsuid=10175 egid=10175 sgid=10175 fsgid=10175 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1863): type=1320 msg=audit(1452525635.337:205): 
,W/jxcore-log( 6134): Platform android
W/jxcore-log( 6134): 
W/jxcore-log( 6134): Process ARCH arm
W/jxcore-log( 6134): 
,I/jxcore-log( 6134): JXcore Cordova bridge is ready!
I/jxcore-log( 6134): 
,W/jxcore-log( 6134): JXcore engine is started
I/Choreographer( 6134): Skipped 129 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6134): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6134): Toggling radios to true
I/jxcore-log( 6134): 
,D/BluetoothAdapter( 6134): enable()
,D/BluetoothAdapter( 6134): enable(): BT is already enabled..!
,D/SecContentProvider( 1017): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1017): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1017): mCursor = null
,D/WifiService( 1017): setWifiEnabled: true pid=6134, uid=10175
W/ActivityManager( 1017): Permission Denial: getCurrentUser() from pid=6134, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1017): Failed getting userId using ActivityManagerNative
W/WifiService( 1017): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6134, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1017): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1017): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1017): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1017): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1017): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1017): name = wifi_on
,I/WifiService( 1017): disconnect: pid=6134, uid=10175
,I/wpa_supplicant( 2081): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 6134): Radios toggled
I/jxcore-log( 6134): 
I/jxcore-log( 6134): My device name is: samsung-SM-A500FU
I/jxcore-log( 6134): 
,I/wpa_supplicant( 2081): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 2081): wlan0: State: COMPLETED -> DISCONNECTED
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 2081): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 2081): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1017): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 2081): wlan0: State: DISCONNECTED -> DISCONNECTED
E/wpa_supplicant( 2081): Cmd 35605 not handled
D/Tethering( 1017): InitialState.processMessage what=4
,E/WifiStateMachine( 1017): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 2081): reset timer : RESET_TIMER 0
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
,I/wpa_supplicant( 2081): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2081): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2081): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 2081): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 2081): First Scan Start
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 2081): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/Tethering( 1017): No numeric data
D/Tethering( 1017): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1017): clearTetheredNotification()
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
V/NetworkStats( 1017): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,D/Tethering( 1017): interfaceStatusChanged wlan0, false
,D/HotspotTile( 1179): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1179): updateTetherState():false, false
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked() took 6ms
E/WifiNative-wlan0( 1017): do suspend true
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
D/CommandListener(  277): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1684): Read error: ssl=0xb83bf230: I/O error during system call, Connection timed out
,V/NativeCrypto( 1684): SSL shutdown failed: ssl=0xb83bf230: I/O error during system call, Broken pipe
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
E/WifiStateMachine( 1017): Start Disconnecting Watchdog 1
,D/ConnectivityService( 1017): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
I/wpa_supplicant( 2081): wlan0: Setting scan request: 0 sec 0 usec
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): DefaultState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1017): Tagging socket 357 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1017, getuid(): 1000,
I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14949 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6950 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/qtaguid ( 1017): Untagging socket 357
,I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
,E/WifiNative-wlan0( 1017): do suspend true
,D/WifiP2pService( 1017): InactiveState{ what=143375 },
,D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3585): Starting #8,
I/Hs20UtilService( 3585): Message received 5007
D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NearbySettings( 1323): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1323): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1323): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1323): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1323): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1323): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1323): MountReceiver.mPrefHandler - 7002
,D/CommandListener(  277): Clearing all IP addresses on wlan0
D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/ConnectivityService( 1017): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityService( 1017): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1017): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker( 1017): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,fe80::7ef9:eff:fe51:1823/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 1017): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Validated
,D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
D/ConnectivityManager.CallbackHandler( 1179): CM callback handler got msg 524292
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyNetworkFactory( 1479): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1479): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService( 1017): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): doQuit - quitNow()
,D/Tethering( 1017): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1017): MasterInitialState.processMessage what=3
,D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
,V/NetworkStats( 1017): updateIfacesLocked()
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked() took 3ms
D/WifiNetworkAgent( 1017): NetworkAgent: NetworkAgent channel lost
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1179): EthernetConnected: false
D/StatusBar.NetworkController( 1179): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1179): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1179): updateDataNetType()
D/StatusBar.NetworkController( 1179): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1179): updateLTEICONDataNetType:0
,D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 1179): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6224): MountEmulatedStorage(),
E/Zygote  ( 6224): v2
,I/libpersona( 6224): KNOX_SDCARD checking this for 10104
,I/libpersona( 6224): KNOX_SDCARD not a persona
,I/SELinux ( 6224): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6224 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
I/SELinux ( 6224): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6224): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6224): TimaSignature is unavailable
,D/ActivityThread( 6224): Added TimaKeyStore provider
,W/ResourcesManager( 6224): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PhoneApp( 1479): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1479): FileWriteThread : threadType = 3
,D/PhoneApp( 1479): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1479): FileWriteThread : threadType = 3
,D/PhoneApp( 1479): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1479): FileWriteThread : threadType = 3
,D/PhoneApp( 1479): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1479): FileWriteThread : threadType = 3
,D/PhoneApp( 1479): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1479): FileWriteThread : threadType = 3
,D/PhoneApp( 1479): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1479): FileWriteThread : threadType = 3
,D/PhoneApp( 1479): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1479): FileWriteThread : threadType = 3
,D/PhoneApp( 1479): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1479): FileWriteThread : threadType = 3
,D/PhoneApp( 1479): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1479): FileWriteThread : threadType = 3
,D/PhoneApp( 1479): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1479): FileWriteThread : threadType = 3
,D/PhoneApp( 1479): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1479): FileWriteThread : threadType = 3
,D/PhoneApp( 1479): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1479): FileWriteThread : threadType = 3
,D/PhoneApp( 1479): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1479): FileWriteThread : threadType = 3
,D/PhoneApp( 1479): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1479): FileWriteThread : threadType = 3
,D/PhoneApp( 1479): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1479): FileWriteThread : threadType = 3
,I/Babel_SMS( 6224): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6224): MmsConfig.loadMmsSettings
I/Babel_SMS( 6224): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel_SMS( 6224): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6224): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6224): MmsConfig.loadFromResources
,E/Babel_SMS( 6224): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6224): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  282): getCameraInfo: X
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  282): getCameraInfo: X
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 6224): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6224): startup - clean
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,I/Babel   ( 6224): deleted: false for 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,W/VideoCapabilities( 6224): Unrecognized profile 2130706433 for video/avc
,D/NearbySettings( 1323): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/Hs20UtilService( 3585): Starting #9
,I/Hs20UtilService( 3585): Message received 5007
,W/AudioCapabilities( 6224): Unsupported mime audio/evrc
,V/NearbySettings( 1323): DMSUtil.isNetworkConnected - flag-null, state-null
W/AudioCapabilities( 6224): Unsupported mime audio/qcelp
,I/NearbySettings( 1323): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1323): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1323): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1323): MountReceiver.onReceive - Set preference state off
,W/AudioCapabilities( 6224): Unsupported mime audio/mpeg-L1
,V/NearbySettings( 1323): MountReceiver.mPrefHandler - 7002
,W/AudioCapabilities( 6224): Unsupported mime audio/mpeg-L2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/AudioCapabilities( 6224): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6224): Unsupported mime audio/x-ima
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/AudioCapabilities( 6224): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6224): Unsupported mime audio/evrc
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
I/DBG_DM  ( 3002): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/DBG_DM  ( 3002): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ApplicationPolicy( 1017): updateDataUsageMap
,W/VideoCapabilities( 6224): Unsupported mime video/wvc1
,W/VideoCapabilities( 6224): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6224): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6224): Unsupported mime video/wvc1
,W/VideoCapabilities( 6224): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6224): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6224): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6224): Unsupported mime video/mp43
,W/VideoCapabilities( 6224): Unsupported mime video/sorenson
,W/VideoCapabilities( 6224): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6224): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6224): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6224): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6224): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6224): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager( 1017): Killing 4997:com.google.android.music:main/u0a111 (adj 15): empty #31
,I/vclib   ( 6224): onServiceConnected
,W/Babel   ( 6224): Attempted to change video mute state without an active call.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1017): failed to open /acct/uid_10111/pid_4997/cgroup.procs: No such file or directory
,V/AlarmManager( 1017): waitForAlarm result :4
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/wpa_supplicant( 2081): nl80211: Received scan results (7 BSSes)
,I/wpa_supplicant( 2081): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 2081): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 2081): Trying to associate with  'G700'
I/wpa_supplicant( 2081): Re-associate with C0.AA.48
I/wpa_supplicant( 2081): wlan0: State: SCANNING -> ASSOCIATING
D/WifiMonitor( 1017): didn't find BSSID Trying to associate with SSID 'NG700'
I/wpa_supplicant( 2081): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/PCWCLIENTTRACE_PushUtil( 5797): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5797): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5797): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5797): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1017): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=22
I/splitIntent( 1017): base  index=22, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1017): other index=24, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5797): noConnectivity : true
,E/Zygote  ( 6268): MountEmulatedStorage()
,E/Zygote  ( 6268): v2
,I/libpersona( 6268): KNOX_SDCARD checking this for 10111
I/libpersona( 6268): KNOX_SDCARD not a persona
,I/SELinux ( 6268): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6268 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6268): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6268): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,I/ConfigService( 1684): onDestroy
,D/TimaKeyStoreProvider( 6268): TimaSignature is unavailable
,D/ActivityThread( 6268): Added TimaKeyStore provider
,E/wpa_supplicant( 2081): Cmd 35605 not handled
,I/wpa_supplicant( 2081): wlan0: State: ASSOCIATING -> ASSOCIATED
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 2081): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 2081): Associated with C0.AA.48
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 2081): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 2081): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 2081): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1017): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 2081): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 2081): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 2081): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
,I/wpa_supplicant( 2081): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
D/SecContentProvider2( 1017): mCursor = null
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, true
D/Tethering( 1017): interfaceLinkStateChanged wlan0, true
D/Tethering( 1017): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 2081): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2081): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2081): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 2081): Blacklist: Clear (temp) 
I/wpa_supplicant( 2081): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, true
D/Tethering( 1017): interfaceLinkStateChanged wlan0, true
D/Tethering( 1017): interfaceStatusChanged wlan0, true
,E/Tethering( 1017): No numeric data
,D/WifiNative-wlan0( 1017): callSECApiVoid - ID [50]
,D/Tethering( 1017): sendTetherStateChangedBroadcast 1, 0, 0
,D/Tethering( 1017): clearTetheredNotification()
E/WifiConfigStore( 1017): setLastSelectedConfiguration -1
,V/NetworkStats( 1017): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
,D/HotspotTile( 1179): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/HotspotTile( 1179): updateTetherState():false, false
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,V/NetworkStats( 1017): performPollLocked() took 7ms
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/ConnectivityService( 1017): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1017): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1017): updateNetworkInfo()
,D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/MusicStore( 6268): Database version: 120
,D/CommandListener(  277): Setting iface cfg
,E/WifiStateMachine( 1017): Start Dhcp Watchdog 2
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1017): mCursor = null
,E/WifiNative-wlan0( 1017): do suspend false
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6268): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/SMD     (  287): DCD OFF
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6268): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6268): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ResourcesManager( 6268): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6268): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/SQLiteLog( 1684): (10) POSIX Error : 11 SQLite Error : 3850
,V/JNIHelp ( 6268): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/SSRM:n  ( 1017): SIOP:: AP = 360
,W/ActivityThread( 6268): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6268): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@b1b5dee: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6268): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6268): GMSCore installation verified
,E/dhcpcd  ( 6291): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 6291): version 5.5.6 starting
,I/ConfigStore( 6268): Config Database version: 1
,E/dhcpcd  ( 6291): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6291): wlan0: sending IPv6 Router Solicitation,
E/dhcpcd  ( 6291): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6291): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 6291): bssid match
I/dhcpcd  ( 6291): wlan0: rebinding lease of 192.168.1.137
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1017): getStreamVolume 3 index 0
,I/MediaRouter( 6268): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6268): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6302): MountEmulatedStorage(),
E/Zygote  ( 6302): v2
I/libpersona( 6302): KNOX_SDCARD checking this for 10002
I/libpersona( 6302): KNOX_SDCARD not a persona
,I/SELinux ( 6302): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/SELinux ( 6302): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6302 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 6302): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GHttpClientFactory( 6268): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 6302): TimaSignature is unavailable
D/ActivityThread( 6302): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 6268): Using platform SSLCertificateSocketFactory
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1017): Killing 5322:com.google.android.gm/u0a101 (adj 15): empty #31
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6321 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 6321): MountEmulatedStorage()
I/libpersona( 6321): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6321): v2
I/libpersona( 6321): KNOX_SDCARD not a persona
I/SELinux ( 6321): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 6321): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6321): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,W/libprocessgroup( 1017): failed to open /acct/uid_10101/pid_5322/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6321): TimaSignature is unavailable
,D/ActivityThread( 6321): Added TimaKeyStore provider
,I/DIAGMON_AGENT( 6321): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 6321): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6321): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6321): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6321): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6321): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6321): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6336): MountEmulatedStorage()
E/Zygote  ( 6336): v2
I/libpersona( 6336): KNOX_SDCARD checking this for 10009
I/libpersona( 6336): KNOX_SDCARD not a persona
,I/SELinux ( 6336): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6336 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6336): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1017): Killing 5107:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
E/SELinux ( 6336): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6336): TimaSignature is unavailable
,D/ActivityThread( 6336): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 4169:com.sec.spp.push/u0a35 (adj 15): empty #31
,I/KLMS-2.5.183: ( 3621): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 11 16:20:38 GMT+01:00 2016
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3621): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.183: ( 3621): KLMSIntentService(): onCreate()
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3621): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3621): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3621): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,W/libprocessgroup( 1017): failed to open /acct/uid_10044/pid_5107/cgroup.procs: No such file or directory
,I/KLMS-2.5.183: ( 3621): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.183: ( 3621): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3621): StateImplV2(): networkChangeListener().END
,E/Zygote  ( 6352): MountEmulatedStorage()
,E/Zygote  ( 6352): v2
I/libpersona( 6352): KNOX_SDCARD checking this for 10034
I/libpersona( 6352): KNOX_SDCARD not a persona
,I/SELinux ( 6352): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1017): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6352 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6352): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/KLMS-2.5.183: ( 3621): KLMSIntentService(): onDestroy()
,E/SELinux ( 6352): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6352): TimaSignature is unavailable
,D/ActivityThread( 6352): Added TimaKeyStore provider
,W/libprocessgroup( 1017): failed to open /acct/uid_10035/pid_4169/cgroup.procs: No such file or directory
,I/SO_AGENT( 6352): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,I/DBG_POLICYDM( 5816): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 6068): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,I/SA      ( 6068): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 6068): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6068): [SLFUCHKMGR] constructor called
,I/DBG_POLICYDM( 5816): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 5816): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 5816): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5816): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,I/SA      ( 6068): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6068): [OR] == isSIMCardReady false ==
,I/SA      ( 6068): [SCU] == networkStateCheck == false
,I/SA      ( 6068): [OR] onReceive END
,I/ActivityManager( 1017): Killing 5304:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
,V/DownloadManager( 1225): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1571): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 1291): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1571): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1571): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1571): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1571): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1571): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1571): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!,
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6369 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,E/Zygote  ( 6369): MountEmulatedStorage()
E/Zygote  ( 6369): v2
I/libpersona( 6369): KNOX_SDCARD checking this for 10125
I/libpersona( 6369): KNOX_SDCARD not a persona
,I/SELinux ( 6369): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6369): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6369): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6369): TimaSignature is unavailable
,D/ActivityThread( 6369): Added TimaKeyStore provider
,W/ResourcesManager( 6369): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6369): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6369): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6369): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6369): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6369): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1017): failed to open /acct/uid_10035/pid_5304/cgroup.procs: No such file or directory
,E/Zygote  ( 6384): MountEmulatedStorage(),
E/Zygote  ( 6384): v2
I/libpersona( 6384): KNOX_SDCARD checking this for 10145
I/libpersona( 6384): KNOX_SDCARD not a persona,
I/SELinux ( 6384): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6384): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/ActivityManager( 1017): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6384 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
E/SELinux ( 6384): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 5735:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6384): TimaSignature is unavailable
,D/ActivityThread( 6384): Added TimaKeyStore provider
,W/ResourcesManager( 6384): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6384): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6384): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6384): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6384): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,W/libprocessgroup( 1017): failed to open /acct/uid_10100/pid_5735/cgroup.procs: No such file or directory
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,V/AlarmManager( 1017): waitForAlarm result :4
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/BadgeProvider( 5922): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/Launcher.Model( 1499): reloadBadges entered.
,D/BadgeProvider( 5922): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5922): sendNotify, [notify] : null
D/BadgeProvider( 5922): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5922): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5922): update, [UpdateCount] : 1
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6407): MountEmulatedStorage()
,E/Zygote  ( 6407): v2
I/libpersona( 6407): KNOX_SDCARD checking this for 1000
I/libpersona( 6407): KNOX_SDCARD not a persona
,I/SELinux ( 6407): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6407): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6407 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 6407): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6407): TimaSignature is unavailable
,D/ActivityThread( 6407): Added TimaKeyStore provider
,D/SecurityLogAgent( 6407): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6407): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6407): StateMachine : Current State = 1
,D/SecurityLogAgent( 6407): StateMachine : Changed Current State = 1
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6423): MountEmulatedStorage()
I/libpersona( 6423): KNOX_SDCARD checking this for 10159
E/Zygote  ( 6423): v2
I/libpersona( 6423): KNOX_SDCARD not a persona
I/SELinux ( 6423): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 6423): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6423): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6423 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 5403:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 5766:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,I/art     (  304): Explicit concurrent mark sweep GC freed 8725(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 701us total 26.867ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 621us total 16.930ms
,I/ActivityManager( 1017): Killing 5782:com.samsung.helphub/1000 (adj 15): empty #31
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 58779(3MB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 27MB/41MB, paused 3.058ms total 199.207ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 690us total 17.626ms
,D/TimaKeyStoreProvider( 6423): TimaSignature is unavailable
,D/ActivityThread( 6423): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 5417:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,I/ActivityManager( 1017): Killing 5854:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/dhcpcd  ( 6291): wlan0: acknowledged 192.168.1.137 from 192.168.1.1
,W/libprocessgroup( 1017): failed to open /acct/uid_10032/pid_5417/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5782/cgroup.procs: No such file or directory
,I/iu.Environment( 1867): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1867): num queued entries: 0
,I/iu.UploadsManager( 1867): num updated entries: 0
,I/iu.SyncManager( 1867): NEXT; no task
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1867): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6441 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6441): MountEmulatedStorage()
E/Zygote  ( 6441): v2
I/libpersona( 6441): KNOX_SDCARD checking this for 10035
I/libpersona( 6441): KNOX_SDCARD not a persona
,I/SELinux ( 6441): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,I/dhcpcd  ( 6291): wlan0: leased 192.168.1.137 for 86400 seconds,
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk,
I/SELinux ( 6441): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 6441): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/Babel   ( 6224): connection state changed from UNKNOWN to DISCONNECTED
,D/TimaKeyStoreProvider( 6441): TimaSignature is unavailable,
D/ActivityThread( 6441): Added TimaKeyStore provider
,W/libprocessgroup( 1017): failed to open /acct/uid_10015/pid_5403/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10091/pid_5766/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10152/pid_5854/cgroup.procs: No such file or directory
,E/SPPClientService( 6441): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE,
E/SPPClientService( 6441): [SystemStateMoniter] Current Time : 89935
,E/SPPClientService( 6441): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6441): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 6441): [SystemStateMoniter] No Connect : true,
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/SPPClientService( 6441): PushLog.txt file is not deleted.
D/SPPClientService( 6441): PushLog.txt file is not deleted.
D/SPPClientService( 6441): ============PushLog. stop!
,E/Zygote  ( 6472): MountEmulatedStorage(),
I/ActivityManager( 1017): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6472 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 5889:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
E/Zygote  ( 6472): v2
I/libpersona( 6472): KNOX_SDCARD checking this for 10113
I/libpersona( 6472): KNOX_SDCARD not a persona
,I/SELinux ( 6472): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
I/SELinux ( 6472): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6472): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/SPPClientService( 6441): [[SystemStateMonitorService]] No Active Internet,
,D/TimaKeyStoreProvider( 6472): TimaSignature is unavailable
,D/ActivityThread( 6472): Added TimaKeyStore provider
,W/libprocessgroup( 1017): failed to open /acct/uid_10156/pid_5889/cgroup.procs: No such file or directory
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6472): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,I/GAv4    ( 6472): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6472):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6472):   adb logcat -s GAv4
,W/ContextImpl( 6472): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/GAv4    ( 6472): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/ContextImpl( 6472): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6472): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6472): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6472): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/WifiNative-wlan0( 1017): do suspend true
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 1017): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1017): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiNative-wlan0( 1017): callSECApiInt - ID [210]
,E/ConnectivityService( 1017): updateNetworkInfo()
,D/ConnectivityService( 1017): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
D/ConnectivityService( 1017): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 1017): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1017): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 1017): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,E/WifiStateMachine( 1017): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/ConnectivityService( 1017): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1017): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1017): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 1017): LTETest block dns file not exists
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine( 1017): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,D/ConnectivityService( 1017): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1017): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): rematching NetworkAgentInfo [WIFI () - 503]
,E/ConnectivityService( 1017): updateNetworkInfo()
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1017):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
E/WifiStateMachine( 1017): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController(  277): uids 1000
,D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 1000
I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1017): mBoosterFLAG : 0
I/WifiTrafficPoller( 1017): current booster mode : FullMode
D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/TelephonyNetworkFactory( 1479): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/WifiNative-wlan0( 1017): callSECApiVoid - ID [212]
,D/TelephonyNetworkFactory( 1479): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 1017): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1017): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1017): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 1017): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/Tethering( 1017): MasterInitialState.processMessage what=3
,D/ConnectivityService( 1017): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,V/NetworkStats( 1017): updateIfacesLocked()
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,V/NetworkStats( 1017): performPollLocked() took 3ms
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/ConnectivityManager.CallbackHandler( 1179): CM callback handler got msg 524290
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1179): EthernetConnected: false
,D/StatusBar.NetworkController( 1179): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1179): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 1179): updateDataNetType()
D/StatusBar.NetworkController( 1179): NoService, mRoamingIconId = 0
,E/StatusBar.NetworkController( 1179): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1179): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/System.out( 1017): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 11 Jan 2016 15:20:39 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452525639740], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452525639720]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Validated
,D/ConnectivityService( 1017): Validated NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1017): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1017): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1017): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1179): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1179): EthernetConnected: false
,D/StatusBar.NetworkController( 1179): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 1179): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1179): updateDataNetType()
,D/StatusBar.NetworkController( 1179): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1179): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1179): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/WebViewFactory( 6472): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,D/ConnectivityService( 1017): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,fe80::7ef9:eff:fe51:1823/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1017): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1017): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1179): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1179): CM callback handler got msg 524295
,I/LibraryLoader( 6472): Time to load native libraries: 2 ms (timestamps 443-445)
,I/LibraryLoader( 6472): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6472): Binding Chromium to main looper Looper (main, tid 1) {3fd410b6}
,I/LibraryLoader( 6472): Expected native library version number "",actual native library version number ""
,I/chromium( 6472): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6472): Initializing chromium process, singleProcess=true
,W/art     ( 6472): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6472): ApplicationContext is null in ApplicationStatus
,W/chromium( 6472): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6472): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6472): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6472): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6472): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6472): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6472): Local Branch: 
I/Adreno-EGL( 6472): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6472): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6472):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/AudioManagerAndroid( 6472): Requires BLUETOOTH permission
,I/NSApplication( 6472): Starting up...
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6542): MountEmulatedStorage(),
,E/Zygote  ( 6542): v2,
,I/ActivityManager( 1017): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6542 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/libpersona( 6542): KNOX_SDCARD checking this for 10081
I/libpersona( 6542): KNOX_SDCARD not a persona
,I/SELinux ( 6542): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Killing 5485:com.android.vending/u0a28 (adj 15): empty #31
,I/SELinux ( 6542): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6542): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6542): TimaSignature is unavailable
,D/ActivityThread( 6542): Added TimaKeyStore provider
,W/libprocessgroup( 1017): failed to open /acct/uid_10028/pid_5485/cgroup.procs: No such file or directory
,D/WaitQueueForNetworkActivate( 6116): notifyNetworkActivated
,W/ContextImpl( 6116): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3002): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/NetworkMonitor( 6268): type=WIFI subType= reason=null isConnected=true
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6564): MountEmulatedStorage()
E/Zygote  ( 6564): v2
I/libpersona( 6564): KNOX_SDCARD checking this for 10075
I/libpersona( 6564): KNOX_SDCARD not a persona
,I/SELinux ( 6564): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6564): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6564): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6564 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/TimaKeyStoreProvider( 6564): TimaSignature is unavailable
,D/ActivityThread( 6564): Added TimaKeyStore provider
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 6116): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6116): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6116): exit::IDLE
D/InitializeManagerStateMachine( 6116): entry::NETWORK_CHECK
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10012
,D/InitializeManagerStateMachine( 6116): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6116): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6116): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6116): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6116): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6116): entry::SUCCESS
D/hcjo    ( 6116): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6116): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6116): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
D/InitializeManagerStateMachine( 6116): exit::SUCCESS
D/InitializeManagerStateMachine( 6116): entry::IDLE
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3585): Starting #10
,I/Hs20UtilService( 3585): Message received 5007
,D/NearbySettings( 1323): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1323): DMSUtil.isNetworkConnected - flag-null, state-null
,I/ActivityManager( 1017): Killing 5750:com.android.mms/u0a46 (adj 15): empty #31
,I/NearbySettings( 1323): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1323): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1323): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1323): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3585): Starting #11
,I/Hs20UtilService( 3585): Message received 5007
,D/NearbySettings( 1323): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1323): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3585): Starting #12
,I/Hs20UtilService( 3585): Message received 5007
,D/NearbySettings( 1323): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1323): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1323): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1323): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1323): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1323): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3585): Starting #13
,I/Hs20UtilService( 3585): Message received 5007
,D/NearbySettings( 1323): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1323): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1017): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityXOffset
D/SecContentProvider2( 1017): mCursor = null
D/CountryDetector( 1017): No listener is left
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastShowPackageNameState
D/SecContentProvider2( 1017): mCursor = null
,I/PCWCLIENTTRACE_PushUtil( 5797): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5797): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5797): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5797): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1017): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=22
,I/splitIntent( 1017): base  index=22, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
,I/splitIntent( 1017): other index=24, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,V/MusicLeanback( 6268): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SurfaceFlinger(  256): id=15 createSurf (1x1),1 flag=4, Uoast
,W/libprocessgroup( 1017): failed to open /acct/uid_10046/pid_5750/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6321): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6321): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6321): ./extraInfo: "NG700"
I/DIAGMON_AGENT( 6321): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService( 1017): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
,D/SRIB_DCS( 1179): log_dcs ThreadedRenderer::initialize entered! 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1684): Connected
,I/DBG_POLICYDM( 5816): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5816): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5816): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5816): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5816): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5816): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,D/GCM     ( 1684): Message class com.google.f.a.a.p
,I/FOTA_Client( 6336): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/GAV2    ( 6564): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/SMD     (  287): DCD OFF
,W/FOTA_Client( 6336): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/BooksApp( 6564): Created application version: 3.6.9 (30609)
,I/KLMS-2.5.183: ( 3621): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 11 16:20:40 GMT+01:00 2016
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3621): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.183: ( 3621): KLMSIntentService(): onCreate()
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.183: ( 3621): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3621): KLMSUtility(): isTestMode(): product_ship: true | testApk: false,
,I/KLMS-2.5.183: ( 3621): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/ConnectivityService( 1017): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/DBG_POLICYDM( 5816): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.5.183: ( 3621): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.183: ( 3621): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/SA      ( 6068): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,I/SA      ( 6068): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6068): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 5816): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/KLMS-2.5.183: ( 3621): StateImplV2(): networkChangeListener().START
,I/SA      ( 6068): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 6068): [OR] == isSIMCardReady false ==
,I/KLMS-2.5.183: ( 3621): NetworkChangeOperations(): uploadRequestLog().START 
,I/SA      ( 6068): [SCU] == networkStateCheck == true
I/SA      ( 6068): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6068): isChinaCountryCode : false
I/SA      ( 6068): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6068): [OR] == networkStateCheck true ==
,I/SA      ( 6068): [OR] GetMyCountryZoneTask
I/SA      ( 6068): [OR] onReceive END
,I/DBG_POLICYDM( 5816): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5816): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,V/DownloadManager( 1225): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.5.183: ( 3621): NetworkChangeOperations(): uploadRequestLog().END 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,I/KLMS-2.5.183: ( 3621): StateImplV2(): networkChangeListener().END
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/SA      ( 6068): [SRS] prepareGetMyCountryZone
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/KLMS-2.5.183: ( 3621): KLMSIntentService(): onDestroy()
,I/DBG_POLICYDM( 5816): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,D/accuweather( 1571): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SA      ( 6068): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6068): [SSP] query invoked
,D/daemonapp( 1291): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,I/SA      ( 6068): [TPMU] GetMccFromDB : null
I/SA      ( 6068): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6068): [TPM] isNoProxy(default) : true
,D/SecContentProvider2( 1017): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1017): mCursor = null
,D/accuweather( 1571): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1571): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/accuweather( 1571): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1571): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5816): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5816): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,E/File    ( 6068): fail readDirectory() errno=2
,I/DBG_POLICYDM( 5816): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,D/accuweather( 1571): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5816): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,D/accuweather( 1571): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/DBG_POLICYDM( 5816): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5816): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,D/QuickConnect( 6369): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6369): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6369): PeriphStartReceiver.onReceive - no need to start
I/DBG_POLICYDM( 5816): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5816): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/DBG_POLICYDM( 5816): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/DBG_POLICYDM( 5816): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,D/SecurityLogAgent( 6407): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6407): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6407): StateMachine : Current State = 1
,D/SecurityLogAgent( 6407): StateMachine : Changed Current State = 1
,I/BooksSync( 6564): Starting books sync for 61035162, extras: ade
,I/DBG_POLICYDM( 5816): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5816): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ConnectivityService( 1017): reportBadNetwork(NetworkAgentInfo [WIFI () - 503]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): DefaultState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1017): Tagging socket 357 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1017, getuid(): 1000
,I/qtaguid ( 1017): Untagging socket 357
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 11 Jan 2016 15:20:40 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452525640837], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452525640820]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Validated
,D/ConnectivityService( 1017): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1017): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1017): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1017): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1179): CM callback handler got msg 524290
,I/iu.Environment( 1867): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1867): num queued entries: 0
,I/iu.UploadsManager( 1867): num updated entries: 0
,I/iu.SyncManager( 1867): NEXT; no task
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1867): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1867): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,E/SPPClientService( 6441): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6441): [SystemStateMoniter] Current Time : 91585
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SPPClientService( 6441): [SystemStateMoniter] No Connect : false
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/System.out( 6224): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 6224): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6224): (HTTPLog)-Static: isShipBuild true
I/System.out( 6224): (HTTPLog)-Thread-1073-1063746147: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6224): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController(  277): uids 10104
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10104
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 6224): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,E/SQLiteLog( 6564): (284) automatic index on view_volumes(volume_id)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 6116): AutoUpdateManager:IDLE:execute
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/InitializeManagerStateMachine( 6116): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6116): exit::IDLE
D/InitializeManagerStateMachine( 6116): entry::NETWORK_CHECK
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,D/InitializeManagerStateMachine( 6116): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6116): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6116): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6116): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6116): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6116): entry::SUCCESS
D/hcjo    ( 6116): AutoUpdateManager:INITCHECK:onInitializeSuccess
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/hcjo    ( 6116): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6116): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/InitializeManagerStateMachine( 6116): exit::SUCCESS
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
,D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
W/Kids    ( 1867): [AccountUtils] Account not ready
W/Kids    ( 1867): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1867): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1867): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1867): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1867): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1867): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1867): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1867): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1867): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1867): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1867): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1867): 	at java.lang.Thread.run(Thread.java:818)
D/InitializeManagerStateMachine( 6116): entry::IDLE
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,I/Babel   ( 6224): connection state changed from DISCONNECTED to CONNECTED
,I/BooksConfig( 6564): GmsCore Version = 7.8.99 (2134222-436)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6564): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6564): Soft error
E/BooksSync( 6564): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6564): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6564): Sync error
E/BooksSync( 6564): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6564): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6564): Finished books sync
,D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 63555, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/SA      ( 6068): [RC New] Execute method=[GET] start
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,I/SA      ( 6068): [RC New] Security=[true]
,I/System.out( 6068): Thread-1040(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6068): Thread-1040(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6068): Thread-1040(ApacheHTTPLog):isShipBuild true
I/System.out( 6068): Thread-1040(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6068): Thread-1040(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10041
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10041
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 43470(2MB) AllocSpace objects, 6(136KB) LOS objects, 33% free, 27MB/41MB, paused 2.623ms total 144.696ms
,I/ActivityManager( 1017): Killing 5941:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,W/libprocessgroup( 1017): failed to open /acct/uid_10047/pid_5941/cgroup.procs: No such file or directory
,D/PackageManager( 1017): [MSG] MCS_UNBIND
,I/ActivityManager( 1017): Killing 5958:com.wsomacp/u0a25 (adj 15): empty #31
,I/SA      ( 6068): [RC New] [v2liruge] api execute + 603
,I/SA      ( 6068): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 6068): AsyncTask #1 calls detatch()
,I/SA      ( 6068): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6068): [OCP] update openData : PL
,W/libprocessgroup( 1017): failed to open /acct/uid_10025/pid_5958/cgroup.procs: No such file or directory
,I/SA      ( 6068): [TPMU] getNetworkMcc : 
,I/SA      ( 6068): [SCU] saveMccToPreferece Start
,I/SA      ( 6068): [SCU] RegionMCC : 260
I/SA      ( 6068): [SSP] query invoked
,I/SA      ( 6068): [TPMU] GetMccFromDB : null
,I/SA      ( 6068): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6068): [SCU] saveMccToPreferece End
,I/SA      ( 6068): [RC New] executeRequest [v2liruge] end. 660
I/SA      ( 6068): [RC New] Execute end
I/SA      ( 6068): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6068): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  ( 6291): wlan0: sending IPv6 Router Solicitation
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/PowerManagerService( 1017): [PWL] Off : 15s ago
I/PowerManagerService( 1017): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1017): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1017): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1867, ws=null) (elapsedTime=57565)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/MusicLeanback( 6268): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6268): Stop autocaching.
,D/WearableService( 4436): callingUid 10012, callindPid: 4436
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/GmsUtils( 6268): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6268): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/SMD     (  287): DCD OFF,
,I/SurfaceFlinger(  256): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger(  256): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 1017): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1017) eventTime = 94583
,D/PowerManagerService( 1017): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017 (0x0)
D/PowerManagerService( 1017): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1017, ws=WorkSource{10054}) (elapsedTime=3467)
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4186, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2648): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5797): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5797): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5797): [GetString-S]
,I/ReactiveServiceManager( 5797): Supported : 1
,D/QSEECOMAPI: ( 1017): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1017): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1017): Loaded image: APP id = 12
,D/QSEECOMAPI: ( 1017): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1017): QSEECom_shutdown_app, app_id = 12
,E/terrier ( 1017): handleString: Failed to handle string(-4)
,E/terrier ( 1017): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5797): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5797): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5797): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5797): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5797): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5797): [ensureRegistration] - No Samsung account
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 6564): Thread[GAThread,5,main]: No campaign data found.
,I/dhcpcd  ( 6291): wlan0: sending IPv6 Router Solicitation
,I/ActivityManager( 1017): Waited long enough for: ServiceRecord{ead1e48 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,V/AlarmManager( 1017): waitForAlarm result :4
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10012
,D/GCM     ( 1684): Connected,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/GCM     ( 1684): Message class com.google.f.a.a.p
,E/SMD     (  287): DCD OFF
,I/jxcore-log( 6134): Test app app.js loaded
I/jxcore-log( 6134): 
,I/Choreographer( 6134): Skipped 648 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6134): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/SSRM:n  ( 1017): SIOP:: AP = 360
,E/SMD     (  287): DCD OFF
,I/dhcpcd  ( 6291): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6291): wlan0: no IPv6 Routers available
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6116): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6116): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6116): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6116): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 6116): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6116): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6116): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 6116): entry::IDLE
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.android.vending
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6638): MountEmulatedStorage()
,E/Zygote  ( 6638): v2,
I/libpersona( 6638): KNOX_SDCARD checking this for 10028
I/libpersona( 6638): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentFiltersService: pid=6638 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6638): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6638): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6638): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6638): TimaSignature is unavailable
,D/ActivityThread( 6638): Added TimaKeyStore provider
,D/Finsky  ( 6638): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6638): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/Settings( 6638): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6638): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6116): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 6116): exit::IDLE
D/PreloadUpdateManagerStateMachine( 6116): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6116): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6116): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6116): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 6116): entry::IDLE
,D/Finsky  ( 6638): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6638): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 6638): [1127] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,D/Finsky  ( 6638): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6638): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6638): [1127] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,I/ActivityManager( 1017): Killing 5983:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,I/art     ( 1684): Explicit concurrent mark sweep GC freed 16464(893KB) AllocSpace objects, 6(216KB) LOS objects, 40% free, 10MB/17MB, paused 1.172ms total 45.589ms
,V/Finsky  ( 6638): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,W/libprocessgroup( 1017): failed to open /acct/uid_10053/pid_5983/cgroup.procs: No such file or directory
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6638): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6638): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6638): [1] 5.onFinished: Scheduling replication attempt 2.
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
,D/Finsky  ( 6638): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6638): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6638): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6638): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6638): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6638): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6638): [1] DailyHygiene.reschedule: Scheduling new run in 849 minutes (failures=5)
,D/DeviceConnectionService( 1696): client connected with version: 7571000
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4225, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2648): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1017): !@Sync 3
,I/Atfwd_Sendcmd(  317): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  317): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,V/AlarmManager( 1017): waitForAlarm result :4
,D/SSRM:n  ( 1017): SIOP:: AP = 330
,I/PowerManagerService( 1017): [PWL] Off : 30s ago
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4228, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2648): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,D/FactoryTest( 5568): Not factory mode
,D/FactoryTest( 5568): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5568): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5568): still no open session command from host, so toast
,W/ContextImpl( 5568): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 5568): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 5568): Timeline: Activity_launch_request id:com.android.settings time:117164
,E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1017): mDVFSHelper.acquire(),
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1017): Focused application set to: xxxx
,D/InputDispatcher( 1017): Focus left window: 6134
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,E/MTPRx   ( 5568): started activity for popup
,W/ResourcesManager( 5568): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 5568): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5568): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5568): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5568): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5568): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5568): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/InputDispatcher( 1017): Focused application set to: xxxx
,D/InputDispatcher( 1017): Focus entered window: 6134
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1017): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@9abe3d4 attribute=null, token = android.os.BinderProxy@68ff568
,D/SettingsReceiverActivity( 5568): dev.kiessupport is : TRUE
,D/PhoneWindow( 5568): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5568): *FMB* installDecor flags : 8388610
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,V/ActivityThread( 6134): updateVisibility : ActivityRecord{1f93153d token=android.os.BinderProxy@cf71ae7 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/Timeline( 6134): Timeline: Activity_idle id: android.os.BinderProxy@cf71ae7 time:117351
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  ( 1017): SIOP:: AP = 310
,W/ActivityManager( 1017): mDVFSHelper.release()
,V/AlarmManager( 1017): waitForAlarm result :4
,V/AlarmManager( 1017): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1017): <AppSync3 Whitelist>
,V/AlarmManagerEXT( 1017): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 28928(1551KB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 27MB/41MB, paused 2.552ms total 159.977ms
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/Finsky  ( 6638): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6638): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6638): [1] 5.onFinished: Scheduling replication attempt 3.
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4231, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2648): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:n  ( 1017): SIOP:: AP = 300
,I/PowerManagerService( 1017): [PWL] Off : 50s ago,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4232, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2648): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1017): !@Sync 4
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 300
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 3
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6638): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6638): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6638): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4233, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate,
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2648): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,I/BooksSync( 6564): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6564): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0,
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6564): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6564): Soft error
E/BooksSync( 6564): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6564): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6564): Sync error
E/BooksSync( 6564): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6564): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source),
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
I/BooksSync( 6564): Finished books sync
,D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 123650, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/PowerManagerService( 1017): [PWL] Off : 75s ago
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4235, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2648): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 4
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6638): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6638): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6638): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4236, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2648): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1017): !@Sync 5
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK,
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/PowerManagerService( 1017): [PWL] Off : 105s ago
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SMD     (  287): DCD OFF
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6638): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6638): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6638): [1] 5.onFinished: Giving up after 6 failures.
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4237, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2648): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4236, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2648): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1017): !@Sync 6
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1684): Vacuum at: now=1452525753230 tag=VacuumService
,I/GoogleURLConnFactory( 1684): Using platform SSLCertificateSocketFactory
,W/Uploader( 1684): No account for auth token provided
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1684): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1684): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1684): (HTTPLog)-Static: isShipBuild true
I/System.out( 1684): (HTTPLog)-Thread-198-655270760: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1684): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10012
,I/System.out( 1684): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1684): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1684, getuid(): 10012
,I/qtaguid ( 1684): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1684, getuid(): 10012
,W/Uploader( 1684): No account for auth token provided
,I/System.out( 1684): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1684): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1684, getuid(): 10012
,W/Uploader( 1684): No account for auth token provided
,I/System.out( 1684): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1684): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1684, getuid(): 10012
,W/Uploader( 1684): No account for auth token provided
,I/System.out( 1684): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1684): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1684, getuid(): 10012
,W/Uploader( 1684):  no longer exists, so no auth token.
,I/System.out( 1684): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1684): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1684, getuid(): 10012
,W/Uploader( 1684): No account for auth token provided
,I/System.out( 1684): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1684): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1684, getuid(): 10012
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/Uploader( 1684): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1684): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1684): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1684): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1684): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1684): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1684): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1684): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1684): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1684): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1684): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1684): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1684): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,I/System.out( 1684): (HTTPLog)-Static: isSBSettingEnabled false,
I/qtaguid ( 1684): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1684, getuid(): 10012
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true,
,E/SQLiteLog( 1684): (10) POSIX Error : 11 SQLite Error : 3850,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4237, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2648): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,I/Atfwd_Sendcmd(  317): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  317): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.apps.books/com.google.android.apps.books.service.SyncService; callingUser = 0; userId(target) = 0
,I/BooksSync( 6564): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6564): GmsCore Version = 7.8.99 (2134222-436)
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
,D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6564): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6564): Soft error
E/BooksSync( 6564): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6564): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6564): Sync error
E/BooksSync( 6564): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6564): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6564): Finished books sync
,D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 215009, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 140s ago
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/Watchdog( 1017): !@Sync 7
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4238, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2648): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:n  ( 1017): SIOP:: AP = 280
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4237, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2648): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 280
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 3
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4238, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1017): stay LED for charging
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2648): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1017): !@Sync 8
,I/PowerManagerService( 1017): [PWL] Off : 180s ago
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4235, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging,
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2648): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 4
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4238, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1017): mGripSensorEnabled= false,
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2648): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 9
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4236, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): stay LED for charging
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.,
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2648): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 225s ago
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1017): initializing...
,I/TLC_TIMA_PKM_initialize( 1017): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1017): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication( 1017): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1017): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1017): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1017): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1017): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1017): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: ( 1017): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1017): Loaded image: APP id = 13
,I/TZ: qc_tlc_communication( 1017): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded,
,I/TLC_TIMA_PKM_initialize( 1017): Trustlet response is completed
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4231, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for charging
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2648): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1017): !@Sync 10
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/Atfwd_Sendcmd(  317): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  317): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF
,I/jxcore-log( 6134): --= Surplus to requirements =--
I/jxcore-log( 6134): 
,I/jxcore-log( 6134): ****TEST TOOK:  ms ****
I/jxcore-log( 6134): 
I/jxcore-log( 6134): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6134): 
,D/AndroidRuntime( 6808): 
D/AndroidRuntime( 6808): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6808): CheckJNI is OFF
D/AndroidRuntime( 6808): readGMSProperty: start
D/AndroidRuntime( 6808): readGMSProperty: already setted!!
D/AndroidRuntime( 6808): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6808): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6808): readGMSProperty: end
D/AndroidRuntime( 6808): addProductProperty: start
,E/AffinityControl( 6808): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 6808): Calling main entry com.android.commands.pm.Pm,
,D/PackageManager( 1017): START PACKAGE DELETE: observer{414400181},
D/PackageManager( 1017): pkg{<packageName>}
D/PackageManager( 1017): user{0}
D/PackageManager( 1017): caller{2000}
D/PackageManager( 1017): flags{3}
,D/PersonaManagerService( 1017): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1017): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1017): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1017): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1017): deletePackage- pkg:com.test.thalitest, edmuserId:0,
D/PackageManagerService( 1017): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1017): !@killApplicatoin: 10175, uninstall pkg,
,I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10175 user=-1: uninstall pkg
,I/ActivityManager( 1017): Killing 6134:com.test.thalitest/u0a175 (adj 0): stop com.test.thalitest cause uninstall pkg
,W/PackageSettings( 1017): Skipping PackageSetting{43c2741 com.example.hello/10176} due to missing metadata
,I/ActivityManager( 1017):   Force finishing activity ActivityRecord{1e13be33 u0 com.test.thalitest/.MainActivity t229}
,W/ActivityManager( 1017): mDVFSHelper.acquire()
,I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10175 user=0: pkg removed
,I/ActivityManager( 1017):   Force finishing activity ActivityRecord{1e13be33 u0 com.test.thalitest/.MainActivity t229 f}
W/ActivityManager( 1017): Duplicate finish request for ActivityRecord{1e13be33 u0 com.test.thalitest/.MainActivity t229 f}
,I/WindowState( 1017): WIN DEATH: Window{1e815d81 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  256): id=14 Removed NainActivit (6/8),
,D/InputDispatcher( 1017): Focus left window: 6134
,I/SurfaceFlinger(  256): id=14 Removed NainActivit (-2/8)
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4208, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1017): stay LED for charging
,I/art     ( 5070): Explicit concurrent mark sweep GC freed 2369(132KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 792us total 36.412ms
,I/DBG_DM  ( 3002): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,D/InputDispatcher( 1017): Focused application released
,I/art     ( 6089): Explicit concurrent mark sweep GC freed 359(25KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 767us total 43.303ms
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010,
,I/DBG_DM  ( 3002): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 12
,E/SamsungIME( 1773): mOCRHelper is null
,I/DBG_DM  ( 3002): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,W/GeofencerStateMachine( 1696): Ignoring removeGeofence because network location is disabled.
,I/DBG_DM  ( 3002): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3002): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 12
,D/RegisteredComponentCache( 1461): Collect Tech packages for Knox
,D/PersonaManager( 1461): isKioskContainerExistOnDevice
,I/DBG_DM  ( 3002): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 3002): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/KLMS-2.5.183: ( 3621): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 11 16:24:36 GMT+01:00 2016
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 3002): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/DBG_DM  ( 3002): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/KLMS-2.5.183: ( 3621): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1017): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=28
,I/splitIntent( 1017): base  index=28, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
,I/splitIntent( 1017): other index=31, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3621): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3621): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3621): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/ActivityManager( 1017): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6823 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,E/Zygote  ( 6823): MountEmulatedStorage()
E/Zygote  ( 6823): v2
I/libpersona( 6823): KNOX_SDCARD checking this for 10094
I/libpersona( 6823): KNOX_SDCARD not a persona
,I/SELinux ( 6823): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/SELinux ( 6823): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/art     ( 1017): Explicit concurrent mark sweep GC freed 58211(4MB) AllocSpace objects, 89(1485KB) LOS objects, 33% free, 27MB/41MB, paused 2.901ms total 178.261ms
I/DBG_DM  ( 3002): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 12
E/SELinux ( 6823): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 1017): WaitForGcToComplete blocked for 170.361ms for cause Explicit
I/KLMS-2.5.183: ( 3621): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/DBG_DM  ( 3002): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,V/HeadsetService( 2648): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2648): Disconnected process message: 10
,I/DBG_DM  ( 3002): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3002): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3002): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 3002): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
,I/DBG_DM  ( 3002): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,I/SurfaceFlinger(  256): id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1017): Focus entered window: 3002
,D/TimaKeyStoreProvider( 6823): TimaSignature is unavailable
,D/ActivityThread( 6823): Added TimaKeyStore provider
,D/SRIB_DCS( 3002): log_dcs ThreadedRenderer::initialize entered! 
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,I/KLMS-2.5.183: ( 3621): KLMSIntentService(): PACKAGE_REMOVED
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
,I/KLMS-2.5.183: ( 3621): KLMSIntentService(): listeningToPackageRemoved().START
,D/PersonaManager( 1461): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1461): empty dynamic service
,V/ActivityThread( 3002): updateVisibility : ActivityRecord{1bc5228 token=android.os.BinderProxy@2d75d5f9 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,I/KLMS-2.5.183: ( 3621): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 1017): Got RemoteException sending setActive(false) notification to pid 6134 uid 10175
,D/SamsungIME( 1773): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,I/Timeline( 3002): Timeline: Activity_idle id: android.os.BinderProxy@2d75d5f9 time:327729
,D/elm:15183( 6823): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15183( 6823): ELMEngine.ELMEngine( context ).
,D/elm:15183( 6823): MDMBridge.setEnterpriseBridge()
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,W/ActivityManager( 1017): mDVFSHelper.release()
I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{10e14049 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t228} time:327753
,D/elm:15183( 6823): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15183( 6823): ElmAgentService : onCreate()
,D/EnterpriseDeviceManagerService( 1017): Package has changed for user 0
,D/EnterpriseDeviceManagerService( 1017): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1017): no available spell checker services found
,D/elm:15183( 6823): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15183( 6823): MainReceiver.listeningToPackageRemoved()
,D/elm:15183( 6823): MDMBridge.getInstance()
,D/elm:15183( 6823): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15183( 6823): MDMBridge.getAllLicenseInfoFromSDK()
,I/KLMS-2.5.183: ( 3621): KLMSIntentService(): listeningToPackageRemoved().END
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/KLMS-2.5.183: ( 3621): KLMSIntentService(): onDestroy()
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RCPManagerService( 1017): PackageReceiver onReceive()
I/HarmonyEASService( 1017): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/elm:15183( 6823): ElmAgentService : onDestroy().
,I/ActivityManager( 1017): Killing 6007:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,D/KnoxMUMContainerPolicy( 1017): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1017): PackageRemovalReceiver::onReceive Enter
,D/OTPFW   ( 1017): OtpDbHelper::getInstance New instance created
,D/OTPFW   ( 1017): DBIntegrity::getInstance - New instance created
,D/OTPFW   ( 1017): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10175 container id = 0
,I/OTPFW   ( 1017): ProvisionData::getAllEntries Enter
,E/OTPFW   ( 1017): ProvisionData::getAllEntries Table is empty
,D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1017): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10175
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10175
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,D/SSRM:aZ ( 1017): MSG_TYPE_APP_REMOVED::
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,D/TaskPersister( 1017): removeObsoleteFile: deleting file=229_task.xml
,D/TaskPersister( 1017): removeObsoleteFile: deleting file=228_task.xml
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,I/PCWCLIENTTRACE_PushUtil( 5797): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5797): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5797): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5797): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/PanelView( 1179): There is/are notification(s) 
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6843): MountEmulatedStorage(),
I/libpersona( 6843): KNOX_SDCARD checking this for 10032
E/Zygote  ( 6843): v2
I/libpersona( 6843): KNOX_SDCARD not a persona
,I/SELinux ( 6843): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6843): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/ActivityManager( 1017): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6843 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,E/SELinux ( 6843): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 16118(880KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 9.170ms total 269.210ms
,W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/TimaKeyStoreProvider( 6843): TimaSignature is unavailable
,D/ActivityThread( 6843): Added TimaKeyStore provider
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager( 1017): delete codoeFile: 
,D/AASAuninstall( 1017): userId = 0, info.removedAppID = -1, info.uid = 10175, packageName = com.test.thalitest
I/AASA_removePackage( 1017): UID=10175 Target=com.test.thalitest
,D/PackageManager( 1017): result of delete: 1{414400181}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/AndroidRuntime( 6808): Shutting down VM
,I/FeatureConfig( 6843): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/SA      ( 6068): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,I/SA      ( 6068): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10175 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/ActivityManager( 1017): Killing 6027:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
E/Zygote  ( 6861): MountEmulatedStorage()
I/libpersona( 6861): KNOX_SDCARD checking this for 10044
E/Zygote  ( 6861): v2
I/libpersona( 6861): KNOX_SDCARD not a persona
I/SELinux ( 6861): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6861 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 6861): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 6861): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 6843): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6843): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6843): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6843): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6843): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6843): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/UsbSettingsManager( 1017): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1017): onPackageRemoved : com.test.thalitest
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_6007/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_6027/cgroup.procs: No such file or directory
,W/ResourcesManager( 6843): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 6843): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6843): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6843): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6843): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6843): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6861): TimaSignature is unavailable
,D/ActivityThread( 6861): Added TimaKeyStore provider
,W/ResourcesManager( 6843): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6843): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6843): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6861): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6861): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6861): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 6861): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6861): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6861): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6861): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6861): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6843): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6843): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6843): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 6843): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6843): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6843): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6843): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6843): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6843): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6843): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6843): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6843): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6843): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6843): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6843): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6843): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6843): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6843): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6843): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6843): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6843): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6843): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6843): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6843): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6843): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6843): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 6843): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6843): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6843): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6843): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 6843): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6843): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 6843): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6843): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6843): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6843): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6843): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6843): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 6843): system/finder_cp/cpdata.xml file not found
,W/art     ( 6808): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/NearbySource( 6861): Nearby Source Create!
,D/NearbyContext( 6861): Nearby Context Create!
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6861): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 6861): Samsung link source created
,E/SQLiteLog( 6861): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
,D/ContactProvider( 6861): getAllContactInfoList Start
,E/SQLiteDatabase( 6861): Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
E/SQLiteDatabase( 6861): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6861): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6861): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6861): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6861): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6861): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6861): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6861): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6861): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6861): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6861): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6861): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6861): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6861): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6861): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteDatabase( 6861): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteDatabase( 6861): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteDatabase( 6861): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:211)
E/SQLiteDatabase( 6861): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:203)
E/SQLiteDatabase( 6861): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 6861): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
E/SQLiteDatabase( 6861): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 6861): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 6861): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6861): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6861): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6861): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6861): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6861): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6861): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SQLiteOpenHelper( 6861): Couldn't open local.db for writing (will try read-only):
E/SQLiteOpenHelper( 6861): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6861): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6861): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6861): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6861): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6861): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6861): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6861): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 6861): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 6861): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6861): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 6861): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6861): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6861): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6861): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteOpenHelper( 6861): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteOpenHelper( 6861): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteOpenHelper( 6861): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:211)
E/SQLiteOpenHelper( 6861): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:203)
E/SQLiteOpenHelper( 6861): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 6861): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
E/SQLiteOpenHelper( 6861): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteOpenHelper( 6861): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteOpenHelper( 6861): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6861): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6861): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 6861): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 6861): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 6861): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 6861): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/SQLiteOpenHelper( 6861): Opened local.db in read-only mode
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/PackagesMonitor( 6861): PackagesMonitor onReceive :com.test.thalitest
,D/ContactProvider( 6861): getAllContactInfoList End
,I/syncContacts( 6861): thread: 1148, sync time = 36
,E/SharedPreferencesImpl( 6861): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=6882 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,E/Zygote  ( 6882): MountEmulatedStorage()
E/Zygote  ( 6882): v2
I/libpersona( 6882): KNOX_SDCARD checking this for 10046
I/libpersona( 6882): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Killing 6049:com.sec.knox.bridge/1000 (adj 15): empty #31
,I/SELinux ( 6882): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 6882): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 6882): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL

```
