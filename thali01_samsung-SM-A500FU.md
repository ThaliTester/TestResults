#### Test 564496604206eac_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
I/DBG_POLICYDM( 5840): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
D/Mms/Contact( 5756): [end]    init consume time = 31.201563
E/SPPClientService( 5884): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5884): [PushClientApplication] Push log off : This is Ship build version
I/DBG_POLICYDM( 5840): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
D/Mms/DraftCache( 5756): [start]    rebuildCache consume time = 14.920781
D/TP/MmsSmsProvider( 1455): query,matched:12, calling pid = 5756
--------- beginning of system
W/ResourcesManager( 5467): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5467): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/Mms/MethodReflector( 5756): getSubId is called
D/Mms/TelephonyUtils( 5756): getLongSubId from simSlot 0, return Value = -1
D/TP/MmsSmsProvider( 1455): match 12:Elapsed time : 1.356 ms
D/Mms/MethodReflector( 5756): getTelephonyProperty is called
D/Mms/DownloadManager( 5756): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5756): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5756): auto download without roaming -> true
D/Mms/DownloadManager( 5756): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 5756): getSubId is called
D/PowerManagerService( 1019): [s] UserActivityState : 2 -> 4
I/PowerManagerService( 1019): [PWL] On : 0 (78743 ms ago)
I/PowerManagerService( 1019): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x4
I/PowerManagerService( 1019): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI.Notification' ACQUIRE_CAUSES_WAKEUP (uid=10054, pid=1181, ws=null) (elapsedTime=12833)
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
D/Mms/MethodReflector( 5756): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5756): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5756): getLongSubId from simSlot 1, return Value = -1000
I/DBG_POLICYDM( 5840): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
D/Mms/MethodReflector( 5756): getTelephonyProperty is called
D/Mms/DownloadManager( 5756): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5756): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5756): auto download without roaming -> true
D/Mms/DownloadManager( 5756): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5756): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5756): mAutoDownload ------> true
D/SPPClientService( 5884): PushLog.txt file is not deleted.
D/SPPClientService( 5884): PushLog.txt file is not deleted.
D/SPPClientService( 5884): ============PushLog. stop!
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 5840): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
E/Zygote  ( 5909): MountEmulatedStorage()
E/Zygote  ( 5909): v2
I/DBG_POLICYDM( 5840): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
I/SELinux ( 5909): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/DBG_POLICYDM( 5840): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
I/libpersona( 5909): KNOX_SDCARD checking this for 10038
I/libpersona( 5909): KNOX_SDCARD not a persona
I/DBG_POLICYDM( 5840): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
I/SELinux ( 5909): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5909): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5909 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 5366:com.android.providers.calendar/u0a42 (adj 15): empty #31
D/ActivityManager( 1019): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
D/Mms/DraftCache( 5756): [end]    rebuildCache consume time = 54.228333
W/ActivityManager( 1019): userId = 0, bbcId = -10000
I/DBG_POLICYDM( 5840): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
D/TimaKeyStoreProvider( 5909): TimaSignature is unavailable
D/ActivityThread( 5909): Added TimaKeyStore provider
I/DBG_POLICYDM( 5840): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/02/02/14:24:23
I/DBG_POLICYDM( 5840): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/01/27/10:04:55
I/DBG_POLICYDM( 5840): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
I/DBG_POLICYDM( 5840): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
I/DBG_POLICYDM( 5840): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/DBG_POLICYDM( 5840): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
I/DBG_POLICYDM( 5840): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
I/DBG_POLICYDM( 5840): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
I/DBG_POLICYDM( 5840): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
I/DBG_POLICYDM( 5840): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
W/ResourcesManager( 5909): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/DBG_POLICYDM( 5840): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
W/ResourcesManager( 5909): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/DBG_POLICYDM( 5840): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
I/ServiceManager(  319): Waiting for service AtCmdFwd...
D/ComposerPerformance( 5756): 1453885495496 ms / [DONE] Composer constructor
E/CII     ( 5756): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 5756): ReservationManager()
I/Mms/ReservationManager( 5756): resetAfterConnected()
I/DBG_POLICYDM( 5840): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
D/TP/MmsSmsProvider( 1455): query,matched:7, calling pid = 5756
D/Mms/Conversation( 5756): [start]    init() consume time = 56.651927
D/TP/MmsSmsProvider( 1455): match 7:Elapsed time : 2.934 ms
D/TP/MmsSmsProvider( 1455): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1455): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1455): updateThread(), thread_id = 9223372036854775807
V/TP/MmsSmsDatabaseHelper( 1455): sUpgradeVersion = 0, db.getVersion() = 81
I/Mms/ReservationManager( 5756): getReservedSendMessageCount(): retMessageCount=0
D/TP/MmsSmsProvider( 1455): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1455): need read changed broadcast:false
D/Mms/Conversation( 5756): [end]    init consume time = 15.604636
D/Mms/MmsApp( 5756): [end]    onCreate() consume time = 1.514479
D/Mms/MessagingNotification( 5756): [start]    init() consume time = 4.099271
D/Mms/DownloadManager( 5756): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/MessagingNotification( 5756): [end]    init consume time = 3.958541
D/Mms/DownloadManager( 5756): roaming ------> false, mSimSlot = 0
I/DBG_POLICYDM( 5840): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
D/Mms/MethodReflector( 5756): getSubId is called
D/Mms/TelephonyUtils( 5756): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5756): getTelephonyProperty is called
D/Mms/DownloadManager( 5756): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5756): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5756): auto download without roaming -> true
D/Mms/DownloadManager( 5756): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5756): mAutoDownload ------> true
D/TP/MmsSmsProvider( 1455): query,matched:0, calling pid = 5756
V/TP/MmsSmsProvider( 1455): getSimpleConversations entered.
D/Mms/SpamFilter( 5756): [start]    SpamFilter fill() begin consume time = 13.788282
D/TP/MmsSmsProvider( 1455): match 0:Elapsed time : 1.504 ms
D/TP/MmsSmsProvider( 1455): query,matched:400, calling pid = 5756
D/ActivityManager( 1019): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/Mms/Synchronizer( 5756): [start]    doSync consume time = 15.084843
D/Mms/FreeMessageStatusReceiver( 5756): onReceive, action : android.intent.action.PACKAGE_ADDED
E/Zygote  ( 5936): MountEmulatedStorage()
E/Zygote  ( 5936): v2
I/libpersona( 5936): KNOX_SDCARD checking this for 10072
I/libpersona( 5936): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5936 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/ActivityManager( 1019): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
I/SELinux ( 5936): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5936): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5936): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
W/art     ( 2005): Verification of void com.google.android.gms.games.service.PlayGamesAsyncService.launchGameForRecording(com.google.android.gms.games.broker.GamesClientContext, com.google.android.gms.games.service.WrappedGamesCallbacks, java.lang.String, com.google.android.gms.games.video.VideoConfiguration) took 101.107ms
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5952): MountEmulatedStorage()
E/Zygote  ( 5952): v2
I/libpersona( 5952): KNOX_SDCARD checking this for 10047
I/libpersona( 5952): KNOX_SDCARD not a persona
I/SELinux ( 5952): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1019): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5952 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
D/TimaKeyStoreProvider( 5936): TimaSignature is unavailable
D/ActivityThread( 5936): Added TimaKeyStore provider
I/SELinux ( 5952): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5952): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 5840): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
D/TP/MmsSmsProvider( 1455): update, matched:300, calling pid = 5756
V/TP/MmsSmsProvider( 1455): syncDBData start
V/TP/MmsSmsProvider( 1455): syncDBData sms end
V/TP/MmsSmsProvider( 1455): syncDBData mms end
V/TP/MmsSmsProvider( 1455): syncDBData end
D/Mms/SpamFilter( 5756): [end]    SpamFilter fill() finished consume time = 62.700157
D/Mms/Synchronizer( 5756): [end]    doSync consume time = 0.636406
D/Mms/FreeMessageReceiverService( 5756): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5756): onHandleIntent: ACTION_PACKAGE_ADDED
D/TimaKeyStoreProvider( 5952): TimaSignature is unavailable
D/ActivityThread( 5952): Added TimaKeyStore provider
I/ActivityManager( 1019): Killing 5286:com.google.android.talk/u0a104 (adj 15): empty #31
D/BadgeProvider( 5936): onCreate
D/BadgeProvider( 5936): DatabaseHelper
W/ResourcesManager( 5952): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5952): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5952): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/Mms/MessagingNotification( 5756): checkBadgeCount unreadCount=0 badgeCount=0
D/TP/SmsProvider( 1455): query,matched:26, calling pid = 5756
D/TP/SmsProvider( 1455): match 26:Elapsed time : 1.841 ms
D/TP/MmsSmsProvider( 1455): query,matched:6, calling pid = 5756
D/TP/MmsSmsProvider( 1455): match 6:Elapsed time : 1.713 ms
W/libprocessgroup( 1019): failed to open /acct/uid_10042/pid_5366/cgroup.procs: No such file or directory
D/Mms/ArtClassLoader( 5756): init [DONE] art
D/ActivityManager( 1019): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5967): MountEmulatedStorage()
E/Zygote  ( 5967): v2
I/libpersona( 5967): KNOX_SDCARD checking this for 10025
I/libpersona( 5967): KNOX_SDCARD not a persona
I/SELinux ( 5967): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1019): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5967 uid=10025 gids={50025, 9997} abi=armeabi-v7a
I/SELinux ( 5967): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5967): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5967): TimaSignature is unavailable
I/DBG_POLICYDM( 5840): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
D/ActivityThread( 5967): Added TimaKeyStore provider
W/libprocessgroup( 1019): failed to open /acct/uid_10104/pid_5286/cgroup.procs: No such file or directory
I/ActivityManager( 1019): Killing 5424:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
I/DBG_POLICYDM( 5840): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
W/ResourcesManager( 5967): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1019): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1019): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 2005): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2005): Module APK com.google.android.play.games already loaded
I/OMACP   ( 5967): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
W/libprocessgroup( 1019): failed to open /acct/uid_10057/pid_5424/cgroup.procs: No such file or directory
D/Mms/Omacp( 5756): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
D/MyFiles ( 5952): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1019): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
I/TactileAssist( 1019): enable value -1
I/TactileAssist( 1019): internal enable value -1
I/TactileAssist( 1019): intensity value -1
I/TactileAssist( 1019): saveAppList value true
D/ChimeraCfgMgr( 2005): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/OMACP   ( 5967): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 5967): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 5967): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/TactileAssist( 1019): List of disabled apps :
I/OMACP   ( 5967): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 5967): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 5967): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/OMACP   ( 5967): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/OMACP   ( 5967): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 5967): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 5967): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 5967): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 5967): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
E/installd(  283): system dir 0 : /system/app/
E/installd(  283): system dir 1 : /system/priv-app/
E/installd(  283): system dir 2 : /vendor/app/
E/installd(  283): system dir 3 : /oem/app/
I/OMACP   ( 5967): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/PackageManager( 1019): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
E/Zygote  ( 5988): MountEmulatedStorage()
I/libpersona( 5988): KNOX_SDCARD checking this for 10053
E/Zygote  ( 5988): v2
I/libpersona( 5988): KNOX_SDCARD not a persona
I/SELinux ( 5988): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1019): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5988 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
D/AsyncTaskServiceImpl( 2005): Submit a task: k
I/SELinux ( 5988): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SELinux ( 5988): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1019): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 5988): TimaSignature is unavailable
D/ActivityThread( 5988): Added TimaKeyStore provider
W/art     ( 2005): Suspending all threads took: 5.253ms
W/ResourcesManager( 5988): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/Compatibility( 5988): onReceive() it will make start service
D/ActivityManager( 1019): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5988): onHandleIntent()
D/Compatibility( 5988): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10155, android.intent.extra.user_handle=0}]
D/Compatibility( 5988): found: 2
E/Zygote  ( 6010): MountEmulatedStorage()
E/Zygote  ( 6010): v2
I/libpersona( 6010): KNOX_SDCARD checking this for 10057
I/libpersona( 6010): KNOX_SDCARD not a persona
I/SELinux ( 6010): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1019): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6010 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
I/SELinux ( 6010): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6010): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/Compatibility( 5988): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/TimaKeyStoreProvider( 6010): TimaSignature is unavailable
D/Compatibility( 5988): skipping ResolveInfo{3eb8911 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5988): considering ResolveInfo{332ba76 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5988): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/ActivityThread( 6010): Added TimaKeyStore provider
D/Compatibility( 5988): enabling receiver ResolveInfo{3ead8877 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5988): enabling receiver ResolveInfo{12818ce4 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5988): enabling receiver ResolveInfo{366ea54d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5988): enabling receiver ResolveInfo{a080802 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5988): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
I/ActivityManager( 1019): Killing 5485:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
I/DBG_POLICYDM( 5840): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/DBG_POLICYDM( 5840): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
D/ChimeraCfgMgr( 2005): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1019): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 2005): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/ActivityManager( 1019): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/k       ( 2005): Processing package: com.test.thalitest
D/ActivityManager( 1019): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1019): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1019): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/ActivityManager( 1019): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SL_DEBUG( 5909): isLoggable:: isProductShip = 1
D/ActivityManager( 1019): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/libprocessgroup( 1019): failed to open /acct/uid_10069/pid_5485/cgroup.procs: No such file or directory
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SL_DEBUG( 5909): isLoggable:: SL_DEBUG_EXIST = false
D/GassUtils( 2005): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
D/k       ( 2005): Found info for package com.test.thalitest in db.
D/ActivityManager( 1019): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/IcingInternalCorpora( 2005): getNumBytesRead when not calculated.
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/UpdateIcingCorporaServi( 6010): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/BaseAppContext( 2005): Using Auth Proxy for data requests.
W/BaseAppContext( 2005): Using Auth Proxy for data requests.
D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/PeopleDatabaseHelper( 2005): cleanUpNonGplusAccounts done.
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5909): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/BaseAppContext( 2005): Using Auth Proxy for data requests.
W/BaseAppContext( 2005): Using Auth Proxy for data requests.
W/BaseAppContext( 2005): Using Auth Proxy for data requests.
W/BaseAppContext( 2005): Using Auth Proxy for data requests.
D/ActivityManager( 1019): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
W/BaseAppContext( 2005): Using Auth Proxy for data requests.
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
D/LocationManagerService( 1019): getProviders()=[passive]
W/ContextImpl( 5909): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/ActivityManager( 1019): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
E/SMD     (  287): DCD OFF
I/ServiceManager(  319): Waiting for service AtCmdFwd...
D/AndroidRuntime( 6036): 
D/AndroidRuntime( 6036): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6036): CheckJNI is OFF
D/AndroidRuntime( 6036): readGMSProperty: start
D/AndroidRuntime( 6036): readGMSProperty: already setted!!
D/AndroidRuntime( 6036): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6036): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6036): readGMSProperty: end
D/AndroidRuntime( 6036): addProductProperty: start
I/art     ( 1019): Explicit concurrent mark sweep GC freed 236727(15MB) AllocSpace objects, 4(4MB) LOS objects, 33% free, 27MB/40MB, paused 2.688ms total 197.135ms
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/UpdateIcingCorporaServi( 6010): UpdateCorporaTask done [took 126 ms] updated apps [took 126 ms] 
E/Zygote  ( 6049): MountEmulatedStorage()
E/Zygote  ( 6049): v2
I/libpersona( 6049): KNOX_SDCARD checking this for 10041
I/libpersona( 6049): KNOX_SDCARD not a persona
I/SELinux ( 6049): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1019): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=6049 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6049): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6049): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Killing 5516:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
D/TimaKeyStoreProvider( 6049): TimaSignature is unavailable
D/ActivityThread( 6049): Added TimaKeyStore provider
I/SA      ( 6049): [SSP] onCreated
I/SA      ( 6049): [TPM] There is no property file
I/SA      ( 6049): [SCU] isHaveSA() - false
I/SA      ( 6049): [TPM] getModelProperty : null
I/SA      ( 6049): [TPM] getCSCProperty : null
I/SA      ( 6049): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 6049): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 6049): [DM] TFT FEATURE: false
I/SA      ( 6049): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 6049): [DM] init START
I/SA      ( 6049): [DM] This device is not a Vodafone
W/ResourceType( 6049): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 6049): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 6049): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 6049): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 6049): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 6049): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 6049): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 6049): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 6049): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 6049): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 6049): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 6049): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 6049): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 6049): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
I/ActivityManager( 1019): Killing 5532:com.google.android.apps.plus/u0a120 (adj 15): empty #31
W/ResourceType( 6049): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 6049): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 6049): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 6049): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 6049): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 6049): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 6049): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 6049): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 6049): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 6049): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 6049): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_5516/cgroup.procs: No such file or directory
I/SA      ( 6049): [SCU] isHaveSA() - false
I/SA      ( 6049): support phone number id : false
I/SA      ( 6049): [DM] Supports Ref Jpn : true
I/SA      ( 6049): [DM] init END
I/SA      ( 6049): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 6049): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10155 extra.user_handle.:0 ]
I/ActivityManager( 1019): Killing 5156:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
W/GAV2    ( 5825): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/libprocessgroup( 1019): failed to open /acct/uid_10120/pid_5532/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10150/pid_5156/cgroup.procs: No such file or directory
E/AffinityControl( 6036): AffinityControl: registerfunction enter
D/AndroidRuntime( 6036): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1019): inState():  stateMachine is null !!
I/PersonaManagerService( 1019): PersonaId don't exist
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1019): mDVFSHelper.acquire()
D/PermissionCache(  257): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (185 us)
D/PhoneWindow( 1019): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1019): *FMB* installDecor flags : 25362712
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=404, uhalitest
I/DBG_DM  ( 3120): [com.wssyncmldm.ui.XUIInstallConfirmActivity(366/onUserLeaveHint)] 
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1019): Focused application set to: xxxx
D/InputDispatcher( 1019): Focus left window: 3120
D/AndroidRuntime( 6036): Shutting down VM
I/DBG_DM  ( 3120): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 21
D/ActivityManager( 1019): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
I/DBG_DM  ( 3120): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
I/DBG_DM  ( 3120): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
I/DBG_DM  ( 3120): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3120): [com.wssyncmldm.ui.XUIInstallConfirmActivity(371/onUserLeaveHint)] Home Key!!
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
W/GAV2    ( 5825): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/DBG_DM  ( 3120): [com.wssyncmldm.ui.XUIFotaPostponeActivity(337/llIIIIlllllIIllIIllI)] 
I/DBG_DM  ( 3120): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
I/libpersona( 6093): KNOX_SDCARD checking this for 10100
E/Zygote  ( 6093): MountEmulatedStorage()
I/libpersona( 6093): KNOX_SDCARD not a persona
E/Zygote  ( 6093): v2
I/SELinux ( 6093): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6093): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1019): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6093 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
E/SELinux ( 6093): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  307): Explicit concurrent mark sweep GC freed 8694(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 641us total 22.374ms
D/TimaKeyStoreProvider( 6093): TimaSignature is unavailable
D/ActivityThread( 6093): Added TimaKeyStore provider
I/DBG_DM  ( 3120): [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 3
D/LightsService( 1019): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1019) 
D/LightsService( 1019): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/DBG_DM  ( 3120): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
D/LightsService( 1019): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1019): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 19.064ms
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
I/DBG_DM  ( 3120): [com.wssyncmldm.db.file.XDB(3671/llIIIIlllllIIllllllI)] FUMO_Status : 220
D/WindowManager( 1019): showStatusBarByNotification() mOpenByNotification=false
W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 681us total 18.386ms
D/PackageIntentReceiver( 6093): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 6093): Not GearManger package! 
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/KnoxNotification( 1181): ----- inflateViews : modified publicViewLocal -----
I/DBG_DM  ( 3120): [com.wssyncmldm.ui.XUIFotaPostponeActivity(381/llIIIIlllllIIllIIllI)] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
I/DBG_DM  ( 3120): [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
E/Zygote  ( 6111): MountEmulatedStorage()
I/libpersona( 6111): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6111): v2
I/libpersona( 6111): KNOX_SDCARD not a persona
I/SELinux ( 6111): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6111): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1019): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6111 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 5002:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
E/SELinux ( 6111): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/KnoxNotification( 1181): ----- inflateViews : modified KnoxViewLocal -----
I/DBG_DM  ( 3120): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/PersonaManager( 1181): PersonaID is invalid or persona doesn't exists. : 0
D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
E/Zygote  ( 6126): MountEmulatedStorage()
E/Zygote  ( 6126): v2
I/libpersona( 6126): KNOX_SDCARD checking this for 10155
I/libpersona( 6126): KNOX_SDCARD not a persona
I/SELinux ( 6126): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6126): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6126 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6126): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1019): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1783): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TimaKeyStoreProvider( 6111): TimaSignature is unavailable
D/ActivityThread( 6111): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 6126): TimaSignature is unavailable
D/ActivityThread( 6126): Added TimaKeyStore provider
W/art     ( 6036): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/Icing   ( 2005): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1019): isKioskContainerExistOnDevice
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,W/AccountFeatureHelper( 5825): Write apps_features disabled false
,W/libprocessgroup( 1019): failed to open /acct/uid_10040/pid_5002/cgroup.procs: No such file or directory
,D/ActivityManager( 1019): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6143): MountEmulatedStorage(),
E/Zygote  ( 6143): v2
I/libpersona( 6143): KNOX_SDCARD checking this for 1000
I/libpersona( 6143): KNOX_SDCARD not a persona,
I/SELinux ( 6143): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6143): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1019): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6143 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 6143): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Killing 4510:com.google.android.music:main/u0a111 (adj 15): empty #31
D/ChimeraCfgMgr( 2005): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2005): Module APK com.google.android.play.games already loaded
W/GAV2    ( 5825): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager( 1019): Killing 4873:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6143): TimaSignature is unavailable
,D/ActivityThread( 6143): Added TimaKeyStore provider
,I/Icing   ( 2005): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6126): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,I/LibraryLoader( 6126): Time to load native libraries: 1 ms (timestamps 831-832)
,I/LibraryLoader( 6126): Expected native library version number "",actual native library version number ""
,D/ActivityManager( 1019): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,D/AcmsPackageEventListener( 6143): Received: android.intent.action.PACKAGE_ADDED,
I/ServiceManager(  319): Waiting for service AtCmdFwd...
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 6143): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,E/Zygote  ( 6163): MountEmulatedStorage(),
E/Zygote  ( 6163): v2
I/libpersona( 6163): KNOX_SDCARD checking this for 10120
I/libpersona( 6163): KNOX_SDCARD not a persona
,I/SELinux ( 6163): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/Mms/MmsApp( 5756):  start initViewCache mms
D/Mms/ComposeMessageFragment( 5756): [start]    fillCache consume time = 1900.934634
D/Mms/ComposeMessageFragment( 5756): fillCache, easy = false
I/SELinux ( 6163): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6163): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6163 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 5311:com.android.calendar/u0a135 (adj 15): empty #31
W/libprocessgroup( 1019): failed to open /acct/uid_10134/pid_4873/cgroup.procs: No such file or directory
,V/WebViewChromiumFactoryProvider( 6126): Binding Chromium to main looper Looper (main, tid 1) {3ead8877}
,I/LibraryLoader( 6126): Expected native library version number "",actual native library version number ""
I/chromium( 6126): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,D/ActivityManager( 1019): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/TimaKeyStoreProvider( 6163): TimaSignature is unavailable
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ActivityThread( 6163): Added TimaKeyStore provider
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/AcmsService( 6143): Enter Oncreate
,D/AcmsServiceMonitor( 6143): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsService( 6143): creating AcmsCore
,D/AcmsCore( 6143): AcmsCore.getAcmsCore() - Enter
,D/AcmsCore( 6143): AcmsCore
,D/AcmsCore( 6143): init
D/AcmsCore( 6143): Looper handler is not null
D/AcmsCore( 6143): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6143): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6143): Incrementing - Counter value: 1
D/AcmsCore( 6143): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 6143): onStartCommand
,D/AcmsService( 6143): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 6143): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6143): Incrementing - Counter value: 2
D/AcmsService( 6143): Incremented Counter Value : onStartCommand
,D/AcmsCertificateMngr( 6143): AcmsCertificateMngr
,D/AcmsRevocationMngr( 6143): AcmsRevocationMngr
,I/BrowserStartupController( 6126): Initializing chromium process, singleProcess=true
,W/art     ( 6126): Attempt to remove local handle scope entry from IRT, ignoring
,D/ActivityManager( 1019): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/ActivityThread( 6143): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,E/SysUtils( 6126): ApplicationContext is null in ApplicationStatus,
,W/libprocessgroup( 1019): failed to open /acct/uid_10111/pid_4510/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10135/pid_5311/cgroup.procs: No such file or directory
,W/chromium( 6126): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 6126): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,I/chromium( 6126): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,W/ResourcesManager( 6163): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AcmsService( 6143): Inside handle Intent
D/AcmsService( 6143): App added - package name: com.test.thalitest
D/AcmsCore( 6143): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6143): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6143): Incrementing - Counter value: 3
D/AcmsCore( 6143): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 6143): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 6143): Decrementing - Counter value: 2
,I/Adreno-EGL( 6126): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6126): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6126): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6126): Local Branch: 
I/Adreno-EGL( 6126): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6126): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6126):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/AbsListView( 5756): Get MotionRecognitionManager
,D/MotionRecognitionService( 1019):  ssp status : false
,D/Mms/ComposeMessageFragment( 5756): [end]    fillCache consume time = 143.257396
,W/chromium( 6126): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,D/Mms/BubbleViewCache( 5756): fillCache bubble = 1
,W/art     ( 6126): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6126): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6126): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6126): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6126): CordovaWebView is running on device made by: samsung
,W/art     ( 6126): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6126): Attempt to remove local handle scope entry from IRT, ignoring
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/OpenGLRenderer( 6126): Render dirty regions requested: true
,D/ActivityManager( 1019): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0,
,D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
,D/PhoneWindow( 6126): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6126): *FMB* isFloatingMenuEnabled return false
,D/ActivityManager( 1019): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/SSRM:n  ( 1019): SIOP:: AP = 340
,I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1019): Focus entered window: 6126
,D/SRIB_DCS( 6126): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 6126): Initialized EGL, version 1.4
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,D/OpenGLRenderer( 6126): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6126): Enabling debug mode 0
,I/SurfaceFlinger(  257): id=10 Removed YUIInstallC (4/9)
,I/SurfaceFlinger(  257): id=10 Removed YUIInstallC (-2/9)
,I/splitIntent( 1019): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1019): Killing 5173:com.google.android.gm/u0a101 (adj 15): empty #31
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
,I/ActivityManager( 1019): Displayed Component not be shown by security: +901ms
D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1019): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11
I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{3dc5ff0d u0 com.test.thalitest/.MainActivity t8} time:81478
,I/SamsungIME( 1878): getCurrentCandidateView
,I/Timeline( 6126): Timeline: Activity_idle id: android.os.BinderProxy@21007bbd time:81490,
,I/ActivityManager( 1019): Killing 5693:com.google.android.gms:car/u0a12 (adj 15): empty #31
,I/DBG_DM  ( 3120): [com.wssyncmldm.ui.XUIInstallConfirmActivity(508/onDestroy)] 
,W/BindingManager( 6126): Cannot call determinedVisibility() - never saw a connection for the pid: 6126
,W/libprocessgroup( 1019): failed to open /acct/uid_10101/pid_5173/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10012/pid_5693/cgroup.procs: No such file or directory
,D/SamsungIME( 1878): Dismiss ExpandCandiate
,I/SurfaceFlinger(  257): id=12 Removed uhalitest (6/8)
,I/SurfaceFlinger(  257): id=12 Removed uhalitest (-2/8)
,D/JsMessageQueue( 6126): Set native->JS mode to OnlineEventsBridgeMode
,D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11
,I/SamsungIME( 1878): getDebugLevel  : 0x4f4c
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/jxcore_app_log( 6126): JniHelper::setJavaVM(0xb7dbf450), pthread_self() = -1204729712
,I/SamsungIME( 1878): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1878): KeybaordView init() : load resources
,I/SamsungIME( 1878): getCurrentKeyboard
I/SamsungIME( 1878): getTextKeyboard
,D/SamsungIME( 1878): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/chromium( 6126): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/DBG_POLICYDM( 5840): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5840): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5840): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5840): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5840): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5840): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5840): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/SamsungIME( 1878): [SwiftkeyWrapper] currentLangauge : 1701729619
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/SensorService( 1019): [SO] 0.019 0.096 10.132
,W/jxcore-log( 6126): Initializing JXcore engine
W/jxcore-log( 6126): JXcore engine is ready
,D/AcmsKeyStoreHelper( 6143):  getKeyStoreForApplication Enter
,V/AlarmManager( 1019): waitForAlarm result :8
,V/AlarmManager( 1019): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1019): <AppSync3 Whitelist>
,V/AlarmManagerEXT( 1019): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,E/audit   ( 1876): type=1400 msg=audit(1453885500.017:205): avc:  denied  { ioctl } for  pid=6221 comm="Thread-1080" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1876):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1876): type=1300 msg=audit(1453885500.017:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9cdb48f8 items=0 ppid=307 ppcomm=main pid=6221 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1080" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1876): type=1320 msg=audit(1453885500.017:205): 
,I/AcmsKeyStoreHelper( 6143): Key Store exist
I/AcmsKeyStoreHelper( 6143): Hence loading the keystore file
,W/jxcore-log( 6126): Starting JXcore engine
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/accuweather( 1731): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,D/accuweather( 1731): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1731): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1731): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1731): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1731): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1731): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,D/accuweather( 1731): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1731): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 1731): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 10 05
,D/AcmsKeyStoreHelper( 6143):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 6143): getKeyStoreForApplication success 
D/AcmsCore( 6143): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 6143): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6143): Decrementing - Counter value: 1
D/AcmsCore( 6143): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 6143): This is NOT a valid MirrorLink app
D/AcmsCore( 6143): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 6143): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6143): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 6143): Counter value is 0: Stopping ACMS service
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/AcmsServiceMonitor( 6143): getSvcCounter - Counter value: 0
D/AcmsService( 6143): Enter onDestroy
I/AcmsService( 6143): cleanUp(): inside service clean up
D/AcmsCore( 6143): AcmsCore: inside DeInit
D/AcmsCore( 6143): AcmsCore: mLooperHandler is not null and making it null
,D/AcmsCertificateMngr( 6143): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 6143): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 6143): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 6143): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 6143): getSvcCounter - Counter value: 0
D/AcmsService( 6143): killing acms process
I/Process ( 6143): Sending signal. PID: 6143 SIG: 9
,W/jxcore-log( 6126): Platform android
W/jxcore-log( 6126): 
W/jxcore-log( 6126): Process ARCH arm
W/jxcore-log( 6126): 
,I/ActivityManager( 1019): Process ACMS.Process (pid 6143)(adj 0) has died(64,1127)
,I/PowerManagerService( 1019): [PWL] On : 0 (83742 ms ago)
,I/PowerManagerService( 1019): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x4
,I/PowerManagerService( 1019): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI.Notification' ACQUIRE_CAUSES_WAKEUP (uid=10054, pid=1181, ws=null) (elapsedTime=17833)
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6126): JXcore Cordova bridge is ready!
I/jxcore-log( 6126): 
,W/jxcore-log( 6126): JXcore engine is started
,E/jxcore  ( 6126): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6126): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6126): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/FocusedStackFrame( 1019): Set to : 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1019): Focused application set to: xxxx
,D/InputDispatcher( 1019): Focus left window: 6126
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101,
,W/PluginManager( 6126): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 32ms. Plugin should use CordovaInterface.getThreadPool().
,D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1019): mDVFSHelper.acquire()
,V/WindowOrientationListener( 1019): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,V/WindowManager( 1019): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1019): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/SensorService( 1019): [SO] activate (ident=0xb86571b0, enabled=0)
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/Launcher( 1481): onRestart, Launcher: 150118990
,D/Launcher( 1481): onStart, Launcher: 150118990
D/Launcher.HomeView( 1481): onStart
,D/Launcher( 1481): onResume, Launcher: 150118990
,D/SettingsProvider( 1019): name = kids_home_mode
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
,D/SettingsProvider( 1019): selectionArgs: 10007
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1019): ret = -1
,D/Launcher.HomeView( 1481): onResume
,D/SensorManager( 1019): unregisterListener ::   
,I/Sensors ( 1019): AccelerometerSensor(0) setDelay : 200000000(ns),
,D/SensorService( 1019): [SO] changed settle time [0]
D/SensorService( 1019): [SO] setDelay [200000000]
D/SensorService( 1019): [SO] activate (ident=0xb8633c48, enabled=1)
D/SensorService( 1019): [SO] AR_init
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/Launcher( 1481): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/MenuAppsGridFragment( 1481): onResume
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,D/SensorManager( 1019): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,D/WallpaperManager( 1481): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1481): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
I/splitIntent( 1019): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=6, mSplitNum[2]=8, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=10
I/splitIntent( 1019): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
D/WallpaperManager( 1481): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,D/GalleryCacheReady( 5017): Receive : home resume
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6228): MountEmulatedStorage()
,I/libpersona( 6228): KNOX_SDCARD checking this for 10088
E/Zygote  ( 6228): v2
I/libpersona( 6228): KNOX_SDCARD not a persona
,I/SELinux ( 6228): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1019): Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6228 uid=10088 gids={50088, 9997} abi=armeabi-v7a
,I/SELinux ( 6228): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6228): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast,
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget,
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6240): MountEmulatedStorage()
,E/Zygote  ( 6240): v2
I/libpersona( 6240): KNOX_SDCARD checking this for 10142
I/libpersona( 6240): KNOX_SDCARD not a persona
I/SELinux ( 6240): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1019): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6240 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6240): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6240): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,D/ActivityManager( 1019): handle home activity for 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
I/WallpaperManagerService( 1019): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1019): post home show event for user 0
D/WallpaperManagerService( 1019):  force update = false; persona id = 0; current user =0; current persona = 0
D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 1019): handleHomeShow for 0 and current 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/Mms/UIEventReceiver( 5756): ui event
D/TimaKeyStoreProvider( 6228): TimaSignature is unavailable
,D/ActivityThread( 6228): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,W/BroadcastQueue( 1019): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1481, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
I/SurfaceFlinger(  257): id=14 createSurf (720x1280),1 flag=4, Mauncher
,D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,D/InputDispatcher( 1019): Focus entered window: 1481
,D/Recents_RecreateReceiver( 2478): onReceive by home
,D/SRIB_DCS( 1481): log_dcs ThreadedRenderer::initialize entered! 
,D/TimaKeyStoreProvider( 6240): TimaSignature is unavailable
,D/ActivityThread( 6240): Added TimaKeyStore provider
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 6228): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/Launcher( 1481): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1181): Icon Only
W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/PanelView( 1181): There is/are notification(s) 
,W/IInputConnectionWrapper( 6126): showStatusIcon on inactive InputConnection
,D/SamsungIME( 1878): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,V/TaskCloserActivity( 6240): TaskCloserActivity enter()
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,V/TaskCloserActivity( 6240): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,E/Zygote  ( 6262): MountEmulatedStorage()
,E/Zygote  ( 6262): v2,
I/libpersona( 6262): KNOX_SDCARD checking this for 10139
I/SELinux ( 6262): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/libpersona( 6262): KNOX_SDCARD not a persona
,I/SELinux ( 6262): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6262): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6262 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 5403:com.samsung.aasaservice/1000 (adj 15): empty #31
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,I/ActivityManager( 1019): Killing 4783:com.samsung.android.sm/1000 (adj 15): empty #31
,W/OpenGLRenderer( 1481): SFEffectCache::get: create texture(0x9ff2b724): name, size, mSize = 40, 144744, 468884
,I/Timeline( 1481): Timeline: Activity_idle id: android.os.BinderProxy@1ec6d954 time:84308
,D/PersonaManager( 1019): isKioskContainerExistOnDevice
,D/TimaKeyStoreProvider( 6262): TimaSignature is unavailable
,D/ActivityThread( 6262): Added TimaKeyStore provider
,I/ActivityManager( 1019): Displayed Component not be shown by security: +236ms
,D/SensorService( 1019): [SO] Reset Rotation Old [100], Init [1]
W/ResourcesManager( 6262): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6262): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6262): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6262): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 6262): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/splitIntent( 1019): Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1019): Killing 5743:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_5403/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_4783/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10152/pid_5743/cgroup.procs: No such file or directory
,D/SensorService( 1019): [SO] currT = 84540063404, prevT = 84080054185, diff = 460009219, [0.019 0.096 10.113]
,D/SensorService( 1019): [SO] 0.019 0.096 10.113
D/SensorService( 1019): [SO] [100 -> 255]
,D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1019): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/ActivityManager( 1019): Killing 5443:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{376bddaf u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t6} time:84760
,I/SurfaceFlinger(  257): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  257): id=13 Removed NainActivit (-2/8)
,W/BindingManager( 6126): Cannot call determinedVisibility() - never saw a connection for the pid: 6126
,D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11
,W/libprocessgroup( 1019): failed to open /acct/uid_10015/pid_5443/cgroup.procs: No such file or directory
,D/ActivityManager( 1019): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,D/TaskPersister( 1019): removeObsoleteFile: deleting file=7_task_thumbnail.png
,E/SMD     (  287): DCD OFF
,D/PowerManagerService( 1019): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1181 (0x0),
I/PowerManagerService( 1019): Nap time (uid 1000)...
,D/PowerManagerService( 1019): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false),
,I/PowerManagerService( 1019): !@[ps] Screen__Off - 0 :  dream(timeout) (2)
I/PowerManagerService( 1019): Going to sleep due to screen timeout (uid 1000)...
,D/DisplayPowerController( 1019): getFinalBrightness : Summary is 1 -> 1,
V/WindowOrientationListener( 1019): WindowOrientationListener disabled,
D/DisplayPowerController( 1019): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255))),
,D/SensorService( 1019): [SO] activate (ident=0xb8633c48, enabled=0)
D/PowerManagerService( 1019): [s] DisplayPowerCallbacks : onStateChanged()
,I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/PowerManagerService( 1019): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 1019): SecHardwareInterface.setBatteryADC : false
D/PowerManagerService( 1019): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
,D/PowerManagerService( 1019): handleSandman : startDream(true),
I/SurfaceFlinger(  257): id=15 createSurf (720x1280),-1 flag=20004, DolorFade
E/PowerManagerService( 1019): handleSandman : startDreaming, but isDreaming false,
,I/PowerManagerService( 1019): Sleeping (uid 1000)...,
D/PowerManagerService( 1019): [s] UserActivityState : 4 -> 0,
,D/PowerManagerService( 1019): Excessive delay in ColorFade : createSurface: 18ms
,D/SensorManager( 1019): unregisterListener ::   
,I/Adreno-EGL( 1019): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1019): OpenGL ES Shader Compiler Version: E031.25.03.02,
I/Adreno-EGL( 1019): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1019): Local Branch: 
I/Adreno-EGL( 1019): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1019): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1019):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/KeyguardViewMediator( 1181): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1181): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1181): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 1181): notifyScreenOffLocked
,D/Launcher.HomeView( 1481): onPause
,D/Launcher( 1481): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/KeyguardViewMediator( 1181): timeout : 5000
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,V/TaskCloserActivity( 6240): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,E/SmartFaceService( 1019): onReceive: android.intent.action.SCREEN_ON
,D/KeyguardViewMediator( 1181): setting alarm to turn off keyguard, seq = 1
,D/KeyguardViewMediator( 1181): handleNotifyScreenOff
D/VolumePanel( 1181): onScreenTurnedOff()
D/VolumePanel( 1181): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,W/System.err( 1019): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,W/System.err( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1019): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1019): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1019): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1019): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1019): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1019): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SmartFaceService( 1019): fail to set sysfs 1
W/System.err( 1019): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1019): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1019): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1019): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1019): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1019): 	... 10 more
D/VolumePanel( 1181): mCoverBroadcastReceiver: Screen OFF end
,D/SecKeyguardClockSingleView( 1181): onScreenTurnedOff
,V/ActivityThread( 1481): updateVisibility : ActivityRecord{231a6955 token=android.os.BinderProxy@1ec6d954 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1481): onStop
,D/PowerManagerService( 1019): Excessive delay in ColorFade : createEglContext: 68ms
,D/InputMethodManagerService( 1019): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/MotionRecognitionService( 1019):   mReceiver.onReceive : ACTION_SCREEN_ON
,I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/NotificationService( 1019): ACTION_SCREEN_ON
D/LightsService( 1019): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1019) 
,D/LightsService( 1019): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LightsService( 1019): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1019): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,E/MotionRecognitionService( 1019):  handler : SCREEN_ON end
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=on
,V/voice   (  282): voice_set_parameters: enter: screen_state=on
V/voice   (  282): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  282): platform_set_parameters: exit with code(-2),
D/audio_hw_hfp(  282): audio_extn_hfp_set_parameters: enter
,V/audio_hw_primary(  282): adev_set_parameters: exit,
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate,
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PowerManagerService( 1019): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 31ms
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
E/WifiNative-wlan0( 1019): do suspend false
I/wpa_supplicant( 2083): reset timer : RESET_TIMER 1
I/wpa_supplicant( 2083): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2083): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2083): Scan requested (ret=0) - scan timeout 30 seconds
,D/IpRemoteDisplayController( 1019): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 1019): Bridge Server is not available
,D/GpsLocationProvider( 1019): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService( 1019): ACTION_SCREEN_ON onReceive
D/PersonaManagerServiceHandler( 1019): MSG_ACTION_SCREEN_ON called
,D/PowerManagerService( 1019): Excessive delay in ColorFade : initGLShaders: 38ms
,D/PowerManagerService( 1019): Excessive delay in ColorFade prepare: 170ms
D/DisplayPowerController( 1019): ColorFade: onAnimationStart
D/DisplayPowerController( 1019): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1019): performScreenOffTransition : no brightness animation
,D/CoverManagerWhiteLists( 1019): isAllowedToUse : SIGNATURE_MATCH
,I/NfcService( 1446): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1446): call the applyRouting
,D/accuweather( 1731): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 1731): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1731): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1731): [KK AccuPhone]>>> UIM:282 [0:0] update clock event, is not screen on!!
D/ActivityManager( 1019): startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SamsungIME( 1878): getNextShiftState() cursorCapsMode : 0
,D/LightsService( 1019): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1019) 
,D/LightsService( 1019): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1019): turn on LED for fully charged
,E/lights  ( 1019): write_int failed to open -1
D/LightsService( 1019): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1019): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,W/System.err( 1019): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,E/SmartFaceService( 1019): onReceive: android.intent.action.SCREEN_OFF
W/System.err( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1019): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1019): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95),
W/System.err( 1019): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
E/SmartFaceService( 1019): fail to set sysfs 0
W/System.err( 1019): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1019): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1019): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1019): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1019): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1019): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1019): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1019): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1019): 	... 10 more
,D/SSRM:n  ( 1019): SIOP:: AP = 350
,I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
,D/SamsungIME( 1878): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
D/MotionRecognitionService( 1019):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService( 1019):  handler : SCREEN_OFF end 
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/NotificationService( 1019): ACTION_SCREEN_OFF
D/LightsService( 1019): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1019) 
,D/LightsService( 1019): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService( 1019): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1019): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=off
,V/voice   (  282): voice_set_parameters: enter: screen_state=off
V/voice   (  282): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  282): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  282): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  282): adev_set_parameters: exit
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1323): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1323): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1323): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1323): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1453907040000
D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1453885502861
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/BackgroundCompactionService( 1019): Schedule Type1 BGCompaction
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1323): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1323): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/IpRemoteDisplayController( 1019): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 1019): Bridge Server is not available
,D/GpsLocationProvider( 1019): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1420): [EmergencyStateReceiver] binteractive [false] why[3]
,D/PersonaManagerService( 1019): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 1019): MSG_ACTION_SCREEN_OFF called
,I/BatteryStatsDumper( 1019): In refreshStats isReason Screen ON/OFF: true
,D/NetworkStatsFactory( 1019): UpdateStatsForKnox updated
,D/accuweather( 1731): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1731): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/NetworkStatsFactory( 1019): UpdateStatsForKnox updated
,D/NfcService( 1446): call the applyRouting
,D/DisplayPowerState( 1019): !@ ColorFade entry
D/DisplayPowerController( 1019): ColorFade: onAnimationEnd
,D/accuweather( 1731): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/DisplayPowerController( 1019): getFinalBrightness : Summary is 0 -> 0
D/lights  ( 1019): lcd : 0 +
D/DisplayPowerController( 1019): performScreenOffTransition : no brightness animation
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/lights  ( 1019): lcd : 0 -
,D/DisplayPowerController( 1019): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1019): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1019): [s] DisplayPowerCallbacks : onStateChanged()
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
,D/MISC PowerHAL( 1019): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/PowerManagerService( 1019): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 1019): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/accuweather( 1731): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/MISC PowerHAL( 1019): sysfs_write +: /sys/class/input/event3/device/enabled: 0
,D/accuweather( 1731): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1731): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1731): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/MISC PowerHAL( 1019): sysfs_write -: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1019): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
,D/MISC PowerHAL( 1019): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1019): Got set_interactive hint
,D/DisplayManagerService( 1019): !@display_state: ON -> OFF
,I/DisplayManagerService( 1019): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager( 1019): Display changed displayId=0
,I/BatteryStatsDumper( 1019): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1019): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1019): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1019): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1019): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1019): Previous Battery Level: 0 Current Level: 100 Delta: -100
,D/SurfaceFlinger(  257): Set power mode=0, type=0 flinger=0xb7afe690
D/qdhwcomposer(  257): hwc_setPowerMode: Setting mode 0 on display: 0
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,E/LibSecureUISvc( 1909): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/SSRM:n  ( 1019): SIOP:: AP = 350
D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/PowerManagerService( 1019): [PWL] sb release: PowerManagerService.Broadcasts
,D/StatusBar.NetworkController( 1181): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/accuweather( 1731): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1731): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1731): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1731): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1731): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 1731): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1731): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/BatteryStatsDumper( 1019): Writing to database completed
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to open fb node 2
,E/qdutils (  257): int qdutils::getHDMINode(): Failed to find HDMI node
D/qdhwcomposer(  257): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl( 1019): Excessive delay in setPowerMode(): 249ms
D/PowerManagerService( 1019): Excessive delay in !@display_state: OFF: 250ms
I/libsuspend( 1019): !@autosuspend_wakeup_count_enable
D/PowerManagerService( 1019): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 267ms
I/libsuspend( 1019): !@autosuspend_wakeup_count_enable done
I/PowerManagerService( 1019): [PWL] Off : 0s ago
,E/WifiNative-wlan0( 1019): do suspend true
,D/SSRM:a  ( 1019): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1019): SettingsAirViewInfo:: 000000000
,I/wpa_supplicant( 2083): nl80211: Received scan results (3 BSSes)
,D/WifiP2pService( 1019): InactiveState{ what=147461 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147461 }
,D/WifiP2pService( 1019): DefaultState{ what=147461 }
,E/SMD     (  287): DCD OFF
,D/PackageManager( 1019): [MSG] MCS_UNBIND
,I/ActivityManager( 1019): Killing 5141:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_5141/cgroup.procs: No such file or directory
,V/AlarmManager( 1019): waitForAlarm result :4
D/KeyguardViewMediator( 1181): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 1181): doKeyguard: not showing because lockscreen is off
V/KeyguardEffectViewController( 1181): *** Keyguard wallpaper service already unbounded
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 1019): [PWL] Off : 5s ago
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/Finsky  ( 5554): [970] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5554): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager( 1019): Waited long enough for: ServiceRecord{a990c7c u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 1019): waitForAlarm result :8
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 310
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :8
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 15s ago,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1019): SIOP:: AP = 290,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1019): !@Sync 3
,I/Atfwd_Sendcmd(  319): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  319): result : -1 	, ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,D/ActivityManager( 1019): bindService callerProcessName:android, calleePkgName: android, action: null
D/ActivityManager( 1019): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,I/BackgroundCompactionService( 1019): onStart. jobID=801
,I/BackgroundCompactionService( 1019): onStart done. jobID=801
,I/BackgroundCompactionService( 1019): Execute BGCompaction (type1). (0 times)
,I/BackgroundCompactionService( 1019): compact_memory command done
,D/ActivityManager( 1019): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  287): DCD OFF
,D/ActivityManager( 1019): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.phenotype.service.sync.PhenotypeConfigurator; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/GoogleURLConnFactory( 1783): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1783): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 60456(3MB) AllocSpace objects, 26(2MB) LOS objects, 32% free, 32MB/48MB, paused 2.484ms total 150.826ms
,I/PhenotypeConfigurator( 1783): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1783): Explicit concurrent mark sweep GC freed 43088(2MB) AllocSpace objects, 11(176KB) LOS objects, 40% free, 12MB/21MB, paused 1.193ms total 60.163ms
,D/ActivityManager( 1019): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1783): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1783): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1783): (HTTPLog)-Static: isShipBuild true
I/System.out( 1783): (HTTPLog)-Thread-253-495505075: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1783): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1783): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1783): Tagging socket 55 with tag 1000120300000000{268440067,0} for uid -1, pid: 1783, getuid(): 10012
,I/qtaguid ( 1783): Tagging socket 76 with tag 1000120300000000{268440067,0} for uid -1, pid: 1783, getuid(): 10012
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,W/PhenotypeConfigurator( 1783): Server returned 404
,D/ActivityManager( 1019): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1783): Vacuum at: now=1453885530801 tag=VacuumService
,D/FactoryTest( 5384): Not factory mode
,D/FactoryTest( 5384): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5384): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 5384): still no open session command from host, so toast
,W/ContextImpl( 5384): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5384): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 5384): Timeline: Activity_launch_request id:com.android.settings time:114179
E/PersonaManagerService( 1019): inState():  stateMachine is null !!
I/PersonaManagerService( 1019): PersonaId don't exist,
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1019): mDVFSHelper.acquire()
,D/FocusedStackFrame( 1019): Set to : 0
,V/ActivityManager( 1019): Display changed displayId=0
,D/PersonaManager( 1019): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1019): Focused application set to: xxxx
D/InputDispatcher( 1019): Focus left window: 1481
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,E/MTPRx   ( 5384): started activity for popup
,D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,W/ResourcesManager( 5384): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 5384): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5384): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5384): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5384): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5384): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5384): PREF_DONT_ASK_AGAIN : true
,D/FocusedStackFrame( 1019): Set to : 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1019): Focused application set to: xxxx
,D/InputDispatcher( 1019): Focus entered window: 1481
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1019): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@3c45981d attribute=android.view.inputmethod.EditorInfo@2168ca92, token = android.os.BinderProxy@2df4f59e
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,D/SamsungIME( 1878): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/SettingsReceiverActivity( 5384): dev.kiessupport is : TRUE
,D/PhoneWindow( 5384): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5384): *FMB* installDecor flags : 8388610
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1019): waitForAlarm result :4,
,D/ActivityManager( 1019): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,D/ActivityManager( 1019): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PowerManagerService( 1019): [PWL] Off : 30s ago
,I/PowerManagerService( 1019): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1019): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 1019): [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10012, pid=1783, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=153)
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeConfigurator( 1783): Scheduling Phenotype for one-off execution 12226 seconds from now (1453885533334)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1783): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeFlagCommitter( 1783): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1783): Using platform SSLCertificateSocketFactory
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/LocationManagerService( 1019): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1783): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
,I/System.out( 1783): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1783): Tagging socket 88 with tag 1000120100000000{268440065,0} for uid -1, pid: 1783, getuid(): 10012
,I/qtaguid ( 1783): Tagging socket 91 with tag 1000120100000000{268440065,0} for uid -1, pid: 1783, getuid(): 10012
,D/LocationManagerService( 1019): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1783): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1783): Tagging socket 88 with tag 1000120100000000{268440065,0} for uid -1, pid: 1783, getuid(): 10012
,W/ActivityManager( 1019): mDVFSHelper.release()
,D/LocationManagerService( 1019): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1783): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1783): Tagging socket 88 with tag 1000120100000000{268440065,0} for uid -1, pid: 1783, getuid(): 10012
,D/LocationManagerService( 1019): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1783): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1783): Tagging socket 88 with tag 1000120100000000{268440065,0} for uid -1, pid: 1783, getuid(): 10012
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 290,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,I/PowerManagerService( 1019): [PWL] Off : 50s ago,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1019): !@Sync 4
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1019): waitForAlarm result :8
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 75s ago,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1019): !@Sync 5
,I/ClearcutLoggerApiImpl( 1783): disconnect managed GoogleApiClient
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/BatteryService( 1019): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate,
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 105s ago
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1019): !@Sync 6,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1019): waitForAlarm result :8,
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
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
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,I/Atfwd_Sendcmd(  319): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  319): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1019): [PWL] Off : 140s ago,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/Watchdog( 1019): !@Sync 7
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 8
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1019): waitForAlarm result :8,
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 180s ago,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1019): Plugged
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1019): Plugged
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1019): !@Sync 9
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,I/MotionRecognitionService( 1019): Plugged,
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 225s ago,
,E/SMD     (  287): DCD OFF
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1019): initializing...
,I/TLC_TIMA_PKM_initialize( 1019): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1019): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1019): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1019): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1019): aligned max_sendmsg_size = 262208 = 0x40040,
I/TZ: qc_tlc_communication( 1019): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1019): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1019): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: ( 1019): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1019): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1019): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1019): Trustlet response is completed
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 10
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,I/Atfwd_Sendcmd(  319): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  319): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,E/SMD     (  287): DCD OFF
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 11,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 275s ago,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 12,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 13
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 1019): [PWL] Off : 330s ago,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/Watchdog( 1019): !@Sync 14
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/Atfwd_Sendcmd(  319): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  319): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1019): waitForAlarm result :8,
V/AlarmManager( 1019): No more alarm at this time.nowELAPSED=443346 batch.start=801448,
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/Watchdog( 1019): !@Sync 15
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 1019): [PWL] Off : 390s ago,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,E/SMD     (  287): DCD OFF
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/bootchecker(  315): bootchecker wake up!!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 16,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged,
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1019): waitForAlarm result :8,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 17
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1019): [PWL] Off : 455s ago
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/Watchdog( 1019): !@Sync 18,
,I/Atfwd_Sendcmd(  319): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  319): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,I/Atfwd_Daemon(  319): Stop the daemon....
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/Watchdog( 1019): !@Sync 19,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1019): stay LED for fully charged,
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 525s ago
,E/SMD     (  287): DCD OFF
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 20
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/Watchdog( 1019): !@Sync 21
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/Watchdog( 1019): !@Sync 22,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 600s ago,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1019): !@Sync 23
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1019): !@Sync 24
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 680s ago,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1019): !@Sync 25,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1019): Plugged
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
I/MotionRecognitionService( 1019): mGripSensorEnabled= false,
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1019): !@Sync 26,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,V/AlarmManager( 1019): waitForAlarm result :8,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1019): !@Sync 27,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1019): [PWL] Off : 765s ago
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1019): !@Sync 28,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false,
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1019): stay LED for fully charged,
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1019): !@Sync 29,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1019): !@Sync 30
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/PowerManagerService( 1019): [PWL] Off : 855s ago
I/PowerManagerService( 1019): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1019): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1019): [PWL]       PARTIAL_WAKE_LOCK              'GCM_CONN' (uid=10012, pid=1783, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=2)
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1019): Plugged
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1019): !@Sync 31
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1019): Plugged
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2619): Disconnected process message: 10
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged,
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.,
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): Plugged
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1019): !@Sync 32,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1019): !@Sync 33
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
I/MotionRecognitionService( 1019): Plugged
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 950s ago
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1019): !@Sync 34
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1019): !@Sync 35
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1019): !@Sync 36
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate,
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1019): !@Sync 37,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 1050s ago,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1019): !@Sync 38,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1019): !@Sync 39,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1019): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1019): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1019): Updating Usage Statistics in DB @ 1453886632486
,I/ApplicationPolicy( 1019): updateDataUsageMap
,I/art     ( 1019): Background sticky concurrent mark sweep GC freed 70724(8MB) AllocSpace objects, 446(6MB) LOS objects, 31% free, 33MB/48MB, paused 3.637ms total 100.892ms
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1019): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1019): ::isTableExists: Table exists 
,I/ApplicationUsage( 1019): Done Updating Usage Statistics in DB @ 1453886632854
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1019): !@Sync 40,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 1155s ago,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF,
,E/Watchdog( 1019): !@Sync 41
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1019): !@Sync 42
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6802): 
D/AndroidRuntime( 6802): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6802): CheckJNI is OFF
D/AndroidRuntime( 6802): readGMSProperty: start
D/AndroidRuntime( 6802): readGMSProperty: already setted!!
D/AndroidRuntime( 6802): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6802): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6802): readGMSProperty: end
D/AndroidRuntime( 6802): addProductProperty: start
E/AffinityControl( 6802): AffinityControl: registerfunction enter
D/AndroidRuntime( 6802): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1019): START PACKAGE DELETE: observer{807049870}
D/PackageManager( 1019): pkg{<packageName>}
D/PackageManager( 1019): user{0}
D/PackageManager( 1019): caller{2000}
D/PackageManager( 1019): flags{3}
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1019): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1019): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1019): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1019): !@killApplicatoin: 10155, uninstall pkg
D/PackageManagerService( 1019): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1019): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled :  enabled true
I/ActivityManager( 1019): Killing 6126:com.test.thalitest/u0a155 (adj 13): stop com.test.thalitest cause uninstall pkg
W/ActivityManager( 1019): Spurious death for ProcessRecord{2e3f42af 6126:com.test.thalitest/u0a155}, curProc for 6126: null
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10155 user=0: pkg removed
W/ActivityManager( 1019): CustomStartingWindow se packge removed so remove capture also
I/art     ( 3872): Explicit concurrent mark sweep GC freed 2652(162KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 6MB/11MB, paused 1.412ms total 45.263ms
I/art     ( 6010): Explicit concurrent mark sweep GC freed 275(22KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 871us total 66.852ms
I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
I/art     ( 2005): Explicit concurrent mark sweep GC freed 2178(96KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 13MB/18MB, paused 1.185ms total 120.443ms
W/GeofencerStateMachine( 1783): Ignoring removeGeofence because network location is disabled.
E/SamsungIME( 1878): mOCRHelper is null
D/RegisteredComponentCache( 1446): Collect Tech packages for Knox
D/PersonaManager( 1446): isKioskContainerExistOnDevice
I/KLMS-2.5.183: ( 3593): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Jan 27 10:25:08 GMT+01:00 2016
D/ActivityManager( 1019): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.183: ( 3593): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1019): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
I/splitIntent( 1019): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6815): MountEmulatedStorage()
E/Zygote  ( 6815): v2
I/libpersona( 6815): KNOX_SDCARD checking this for 10094
I/libpersona( 6815): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6815 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 6815): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6815): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/KLMS-2.5.183: ( 3593): KLMSIntentService(): onCreate()
E/SELinux ( 6815): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     ( 1019): Explicit concurrent mark sweep GC freed 25170(2MB) AllocSpace objects, 35(560KB) LOS objects, 32% free, 32MB/48MB, paused 2.988ms total 225.256ms
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
I/art     ( 1019): WaitForGcToComplete blocked for 160.076ms for cause Explicit
I/PackagesMonitor( 5017): PackagesMonitor onReceive :com.test.thalitest
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3593): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/TimaKeyStoreProvider( 6815): TimaSignature is unavailable
E/Zygote  ( 6830): MountEmulatedStorage()
I/libpersona( 6830): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6830): v2
I/libpersona( 6830): KNOX_SDCARD not a persona
I/SELinux ( 6830): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6830): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6830): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityThread( 6815): Added TimaKeyStore provider
I/KLMS-2.5.183: ( 3593): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.5.183: ( 3593): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.5.183: ( 3593): KLMSIntentService(): PACKAGE_REMOVED
D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1019): mCursor = null
I/ActivityManager( 1019): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=6830 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3593): KLMSIntentService(): listeningToPackageRemoved().START
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6844): MountEmulatedStorage()
E/Zygote  ( 6844): v2
I/libpersona( 6844): KNOX_SDCARD checking this for 10149
I/libpersona( 6844): KNOX_SDCARD not a persona
I/SELinux ( 6844): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/KLMS-2.5.183: ( 3593): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
I/SELinux ( 6844): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6844): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6844 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/TimaKeyStoreProvider( 6830): TimaSignature is unavailable
D/ActivityThread( 6830): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 6844): TimaSignature is unavailable
D/ActivityThread( 6844): Added TimaKeyStore provider
D/Mms/FreeMessageStatusReceiver( 5756): onReceive, action : android.intent.action.PACKAGE_REMOVED
D/ActivityManager( 1019): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
W/ResourcesManager( 6830): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/PersonaManager( 1446): isKioskContainerExistOnDevice
I/TactileAssist( 1019): enable value -1
I/TactileAssist( 1019): internal enable value -1
I/TactileAssist( 1019): intensity value -1
I/TactileAssist( 1019): saveAppList value true
D/RegisteredServicesCache( 1446): empty dynamic service
I/TactileAssist( 1019): List of disabled apps :
D/RCPManagerService( 1019): PackageReceiver onReceive()
I/HarmonyEASService( 1019): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1019): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1019): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1019): OtpDbHelper::getInstance New instance created
D/OTPFW   ( 1019): DBIntegrity::getInstance - New instance created
D/Mms/FreeMessageReceiverService( 5756): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 5756): onHandleIntent: ACTION_PACKAGE_REMOVED
D/OTPFW   ( 1019): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
I/OTPFW   ( 1019): ProvisionData::getAllEntries Enter
D/Compatibility( 5988): onReceive() it will make start service
D/ActivityManager( 1019): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
E/OTPFW   ( 1019): ProvisionData::getAllEntries Table is empty
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1019): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10155
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
D/ActivityManager( 1019): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
I/KLMS-2.5.183: ( 3593): KLMSIntentService(): listeningToPackageRemoved().END
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10155
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
D/SSRM:aZ ( 1019): MSG_TYPE_APP_REMOVED::
D/TaskPersister( 1019): removeObsoleteFile: deleting file=8_task.xml
D/TaskPersister( 1019): removeObsoleteFile: deleting file=8_task_thumbnail.png
I/KLMS-2.5.183: ( 3593): KLMSIntentService(): onDestroy()
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.test.thalitest
D/Compatibility( 5988): onHandleIntent()
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
V/AlarmManagerEXT( 1019): com.test.thalitest(10155) is removed.
D/elm:15183( 6815): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/ThemeInfoUtil( 6844): getCurrentFestivalName is [null]
D/ThemeInfoUtil( 6844): isCurrentFestival = false
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
D/Compatibility( 5988): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10155, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/elm:15183( 6815): ELMEngine.ELMEngine( context ).
D/Compatibility( 5988): found: 2
D/Compatibility( 5988): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5988): skipping ResolveInfo{d8d4949 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5988): considering ResolveInfo{8f2a24e com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5988): default: com.sec.android.app.soundalive.SAControlPanelActivity
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5988): enabling receiver ResolveInfo{13170f6f com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/elm:15183( 6815): MDMBridge.setEnterpriseBridge()
I/UpdateIcingCorporaServi( 6010): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/Compatibility( 5988): enabling receiver ResolveInfo{65f947c com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
E/Zygote  ( 6865): MountEmulatedStorage()
E/Zygote  ( 6865): v2
I/libpersona( 6865): KNOX_SDCARD checking this for 10152
I/libpersona( 6865): KNOX_SDCARD not a persona
I/SELinux ( 6865): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6865): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6865): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6865 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
D/ActivityManager( 1019): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/Compatibility( 5988): enabling receiver ResolveInfo{29d83105 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
I/art     (  307): Explicit concurrent mark sweep GC freed 8719(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 654us total 25.591ms
D/Compatibility( 5988): enabling receiver ResolveInfo{1eda955a com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/elm:15183( 6815): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
I/art     ( 1019): Explicit concurrent mark sweep GC freed 12588(779KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 32MB/48MB, paused 10.581ms total 295.366ms
D/elm:15183( 6815): ElmAgentService : onCreate()
D/Compatibility( 5988): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/elm:15183( 6815): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 6815): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6815): MDMBridge.getInstance()
D/elm:15183( 6815): MDMBridge.getAllLicenseInfoFromSDK()
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 21.516ms
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
D/TimaKeyStoreProvider( 6865): TimaSignature is unavailable
D/ActivityThread( 6865): Added TimaKeyStore provider
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/elm:15183( 6815): MDMBridge.getAllLicenseInfoFromSDK()
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 688us total 17.159ms
E/Zygote  ( 6883): MountEmulatedStorage()
I/libpersona( 6883): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6883): v2
I/libpersona( 6883): KNOX_SDCARD not a persona
I/SELinux ( 6883): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6883): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1019): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=6883 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 6883): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/elm:15183( 6815): ElmAgentService : onDestroy().
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/SQLiteLog( 6830): (284) automatic index on crash_info_summary(package_name_touched)
E/Zygote  ( 6898): MountEmulatedStorage()
E/Zygote  ( 6898): v2
I/libpersona( 6898): KNOX_SDCARD checking this for 10003
I/libpersona( 6898): KNOX_SDCARD not a persona
I/SELinux ( 6898): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6898): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6898): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6898 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
D/TimaKeyStoreProvider( 6883): TimaSignature is unavailable
D/ActivityThread( 6883): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 6898): TimaSignature is unavailable
E/SQLiteLog( 6865): (284) automatic index on shooting_modes(title_id)
D/ActivityThread( 6898): Added TimaKeyStore provider
D/ActivityManager( 1019): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
I/TapandpayWidget:TapandpayAppWidgetProvider( 5809): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 5809): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils( 5809): Clear T&P info.
D/TapandpayWidget:TapandpayAppWidgetProvider( 5809): Widget is not attached.
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/PackageManager( 1019): delete codoeFile: 
D/AASAuninstall( 1019): userId = 0, info.removedAppID = -1, info.uid = 10155, packageName = com.test.thalitest
I/AASA_removePackage( 1019): UID=10155 Target=com.test.thalitest
D/PackageManager( 1019): result of delete: 1{807049870}
D/AndroidRuntime( 6802): Shutting down VM
E/Zygote  ( 6914): MountEmulatedStorage()
E/Zygote  ( 6914): v2
I/libpersona( 6914): KNOX_SDCARD checking this for 10160
I/libpersona( 6914): KNOX_SDCARD not a persona
I/SELinux ( 6914): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1019): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=6914 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
I/SELinux ( 6914): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6914): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/AASAservice-UpdateReceiver( 6883): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
W/System.err( 6883): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 6883): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
W/System.err( 6883): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 6883): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 6883): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
I/art     ( 6830): Explicit concurrent mark sweep GC freed 8918(424KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 987us total 56.573ms
W/System.err( 6883): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 6883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6883): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 6883): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6883): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6883): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6883): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/ActivityManager( 1019): Killing 5788:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
D/UserAnalysis.PlaceProvider( 6898): PlaceProvider onCreate()
D/ActivityManager( 1019): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/BadgeProvider( 5936): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5936): sendNotify, [notify] : null
D/BadgeProvider( 5936): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5936): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5936): update, [UpdateCount] : 1
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
I/PCWCLIENTTRACE_PushUtil( 5779): SPPPushClient is installed : true
D/TimaKeyStoreProvider( 6914): TimaSignature is unavailable
D/ActivityThread( 6914): Added TimaKeyStore provider
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
I/PCWCLIENTTRACE_PushUtil( 5779): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5779): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5779): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/UserAnalysis.SecureDbManager( 6898): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 6898): SecurePlaceDbHelper() 
D/UserAnalysis( 6898): Create SecureDbHelper
E/Zygote  ( 6931): MountEmulatedStorage()
E/Zygote  ( 6931): v2
I/libpersona( 6931): KNOX_SDCARD checking this for 1000
I/libpersona( 6931): KNOX_SDCARD not a persona
I/SELinux ( 6931): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1019): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6931 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6931): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1019): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
E/SELinux ( 6931): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/IntelligenceServiceApplication( 6898): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 6898): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
D/TimaKeyStoreProvider( 6931): TimaSignature is unavailable
D/ActivityThread( 6931): Added TimaKeyStore provider
I/ActivityManager( 1019): Killing 5500:com.sec.knox.bridge/1000 (adj 15): empty #31
D/IntelligenceServiceApplication( 6898): no applications having user consent for prediction
W/ResourcesManager( 6914): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
V/PlaceDetection v1.0.19 ( 6898): [PlaceDetection::stopService] Service stopped.
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/Launcher.Model( 1481): reloadBadges entered.
D/[0]UMC:UMCContentProvider( 6914): @onCreate
V/PlaceDetection v1.0.19 ( 6898): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
E/Zygote  ( 6948): MountEmulatedStorage()
E/Zygote  ( 6948): v2
I/libpersona( 6948): KNOX_SDCARD checking this for 10035
I/libpersona( 6948): KNOX_SDCARD not a persona
I/SELinux ( 6948): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6948): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6948): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6948 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 5840:com.policydm/1000 (adj 15): empty #31
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/[0]UMC:Core( 6914): onCreate(): 
D/[0]UMC:Core( 6914): @isManagedProfileUser
D/[0]UMC:Core( 6914): userId: 0
W/art     ( 6802): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/ActivityManager( 1019): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ContextImpl( 6931): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1019): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1019): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
D/[0]UMC:Core( 6914): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 6914): userInfo.isManagedProfile() : false
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
V/PlaceDetection v1.0.19 ( 6898): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
V/PlaceDetection v1.0.19 ( 6898): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
V/PlaceDetection v1.0.19 ( 6898): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
V/PlaceDetection v1.0.19 ( 6898): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6898): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6898): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6898): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6898): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
V/PlaceDetection v1.0.19 ( 6898): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
D/ActivityManager( 1019): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
D/TimaKeyStoreProvider( 6948): TimaSignature is unavailable
V/PlaceDetection v1.0.19 ( 6898): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
V/PlaceDetection v1.0.19 ( 6898): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6898): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6898): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6898): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6898): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
V/PlaceDetection v1.0.19 ( 6898): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 6898): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
V/PlaceDetection v1.0.19 ( 6898): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
V/PlaceDetection v1.0.19 ( 6898): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
V/PlaceDetection v1.0.19 ( 6898): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0

```
