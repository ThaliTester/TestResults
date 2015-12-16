#### Test 506502789b39735_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
I/SELinux ( 5929): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/DBG_POLICYDM( 5826): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2015/12/16/21:58:38
E/SPPClientService( 5901): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5901): [PushClientApplication] Push log off : This is Ship build version
E/SELinux ( 5929): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 5826): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
I/DBG_POLICYDM( 5826): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
I/DBG_POLICYDM( 5826): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
--------- beginning of system
I/ActivityManager( 1015): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5929 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/DBG_POLICYDM( 5826): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
I/DBG_POLICYDM( 5826): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2015/12/16/02:33:37
D/SPPClientService( 5901): PushLog.txt file is not deleted.
D/SPPClientService( 5901): PushLog.txt file is not deleted.
D/SPPClientService( 5901): ============PushLog. stop!
I/DBG_POLICYDM( 5826): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
I/DBG_POLICYDM( 5826): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
D/TimaKeyStoreProvider( 5929): TimaSignature is unavailable
D/ActivityThread( 5929): Added TimaKeyStore provider
I/DBG_POLICYDM( 5826): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
D/TP/MmsSmsProvider( 1454): query,matched:13, calling pid = 5776
D/TP/MmsSmsProvider( 1454): match 13:Elapsed time : 0.854 ms
D/Mms/Contact( 5776): [end]    init consume time = 45.034271
W/ResourcesManager( 5929): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5929): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/Mms/DraftCache( 5776): [start]    rebuildCache consume time = 13.479895
I/DBG_POLICYDM( 5826): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
D/TP/MmsSmsProvider( 1454): query,matched:12, calling pid = 5776
D/TP/MmsSmsProvider( 1454): match 12:Elapsed time : 2.933 ms
D/Mms/MethodReflector( 5776): getSubId is called
D/Mms/TelephonyUtils( 5776): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5776): getTelephonyProperty is called
D/Mms/DownloadManager( 5776): roaming -> false (slotId = 0)
D/Mms/DraftCache( 5776): [end]    rebuildCache consume time = 34.669375
D/Mms/DownloadManager( 5776): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5776): auto download without roaming -> true
D/Mms/DownloadManager( 5776): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 5776): getSubId is called
D/Mms/MethodReflector( 5776): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5776): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5776): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5776): getTelephonyProperty is called
D/Mms/DownloadManager( 5776): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5776): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5776): auto download without roaming -> true
D/Mms/DownloadManager( 5776): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5776): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5776): mAutoDownload ------> true
E/PhotosPlugin( 5881): Loading PhotosPlugin
D/Mms/ArtClassLoader( 5776): init [DONE] art
D/ComposerPerformance( 5776): 1450229617880 ms / [DONE] Composer constructor
E/CII     ( 5776): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 5776): ReservationManager()
I/Mms/ReservationManager( 5776): resetAfterConnected()
D/TP/MmsSmsProvider( 1454): query,matched:7, calling pid = 5776
D/TP/MmsSmsProvider( 1454): match 7:Elapsed time : 1.695 ms
D/Mms/Conversation( 5776): [start]    init() consume time = 81.465625
I/Mms/ReservationManager( 5776): getReservedSendMessageCount(): retMessageCount=0
D/TP/MmsSmsProvider( 1454): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1454): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1454): updateThread(), thread_id = 9223372036854775807
D/Mms/MmsApp( 5776): [end]    onCreate() consume time = 5.122136
V/TP/MmsSmsDatabaseHelper( 1454): sUpgradeVersion = 0, db.getVersion() = 81
D/TP/MmsSmsProvider( 1454): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1454): need read changed broadcast:false
D/Mms/Conversation( 5776): [end]    init consume time = 8.608698
D/Mms/MessagingNotification( 5776): [start]    init() consume time = 8.175833
D/Mms/DownloadManager( 5776): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 5776): roaming ------> false, mSimSlot = 0
D/Mms/MethodReflector( 5776): getSubId is called
D/Mms/TelephonyUtils( 5776): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5776): getTelephonyProperty is called
D/Mms/DownloadManager( 5776): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5776): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5776): auto download without roaming -> true
D/Mms/DownloadManager( 5776): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5776): mAutoDownload ------> true
D/Mms/MessagingNotification( 5776): [end]    init consume time = 7.183438
D/Mms/FreeMessageStatusReceiver( 5776): onReceive, action : android.intent.action.PACKAGE_ADDED
D/Mms/Synchronizer( 5776): [start]    doSync consume time = 4.302083
D/TP/MmsSmsProvider( 1454): query,matched:0, calling pid = 5776
V/TP/MmsSmsProvider( 1454): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1454): match 0:Elapsed time : 1.114 ms
D/ActivityManager( 1015): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
D/Mms/SpamFilter( 5776): [start]    SpamFilter fill() begin consume time = 3.822864
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/TP/MmsSmsProvider( 1454): update, matched:300, calling pid = 5776
V/TP/MmsSmsProvider( 1454): syncDBData start
V/TP/MmsSmsProvider( 1454): syncDBData sms end
V/TP/MmsSmsProvider( 1454): syncDBData mms end
V/TP/MmsSmsProvider( 1454): syncDBData end
D/Mms/Synchronizer( 5776): [end]    doSync consume time = 8.522969
I/DBG_POLICYDM( 5826): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/TP/MmsSmsProvider( 1454): query,matched:400, calling pid = 5776
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5955): MountEmulatedStorage()
I/libpersona( 5955): KNOX_SDCARD checking this for 10047
E/Zygote  ( 5955): v2
I/libpersona( 5955): KNOX_SDCARD not a persona
I/SELinux ( 5955): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5955 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
I/SELinux ( 5955): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SELinux ( 5955): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
D/Mms/FreeMessageReceiverService( 5776): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5776): onHandleIntent: ACTION_PACKAGE_ADDED
D/Mms/SpamFilter( 5776): [end]    SpamFilter fill() finished consume time = 53.404844
D/ChimeraCfgMgr( 2000): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2000): Module APK com.google.android.play.games already loaded
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
D/TimaKeyStoreProvider( 5955): TimaSignature is unavailable
D/ActivityThread( 5955): Added TimaKeyStore provider
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/ChimeraCfgMgr( 2000): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/DBG_POLICYDM( 5826): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
E/Zygote  ( 5974): MountEmulatedStorage()
E/Zygote  ( 5974): v2
I/libpersona( 5974): KNOX_SDCARD checking this for 10072
I/libpersona( 5974): KNOX_SDCARD not a persona
I/SELinux ( 5974): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5974): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5974): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5974 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/AsyncTaskServiceImpl( 2000): Submit a task: k
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 5826): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1015): Killing 5310:com.sec.android.diagmonagent/1000 (adj 15): empty #31
D/ChimeraCfgMgr( 2000): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/TimaKeyStoreProvider( 5974): TimaSignature is unavailable
D/ActivityThread( 5974): Added TimaKeyStore provider
I/ActivityManager( 1015): Killing 5325:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/k       ( 2000): Processing package: com.test.thalitest
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 5955): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5955): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5955): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/BadgeProvider( 5974): onCreate
D/ChimeraCfgMgr( 2000): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/BadgeProvider( 5974): DatabaseHelper
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/MessagingNotification( 5776): checkBadgeCount unreadCount=0 badgeCount=0
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TP/SmsProvider( 1454): query,matched:26, calling pid = 5776
D/TP/SmsProvider( 1454): match 26:Elapsed time : 1.104 ms
D/TP/MmsSmsProvider( 1454): query,matched:6, calling pid = 5776
D/TP/MmsSmsProvider( 1454): match 6:Elapsed time : 0.775 ms
W/libprocessgroup( 1015): failed to open /acct/uid_10142/pid_5325/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5310/cgroup.procs: No such file or directory
D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/GassUtils( 2000): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
D/k       ( 2000): Found info for package com.test.thalitest in db.
E/Zygote  ( 5995): MountEmulatedStorage()
E/Zygote  ( 5995): v2
I/libpersona( 5995): KNOX_SDCARD checking this for 10025
I/libpersona( 5995): KNOX_SDCARD not a persona
I/SELinux ( 5995): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5995): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5995 uid=10025 gids={50025, 9997} abi=armeabi-v7a
E/SELinux ( 5995): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/TimaKeyStoreProvider( 5995): TimaSignature is unavailable
D/ActivityThread( 5995): Added TimaKeyStore provider
V/GLSActivity( 1838): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager( 1015): Killing 5342:com.android.providers.calendar/u0a42 (adj 15): empty #31
W/ResourcesManager( 5995): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/MyFiles ( 5955): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
W/BaseAppContext( 2000): Using Auth Proxy for data requests.
W/BaseAppContext( 2000): Using Auth Proxy for data requests.
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/TactileAssist( 1015): enable value -1
I/TactileAssist( 1015): internal enable value -1
I/TactileAssist( 1015): intensity value -1
I/TactileAssist( 1015): saveAppList value true
I/System.out( 5530): Thread-959(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5530): Thread-959(ApacheHTTPLog):isShipBuild true
I/System.out( 5530): Thread-959(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5530): Thread-959(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
E/installd(  282): system dir 0 : /system/app/
E/installd(  282): system dir 1 : /system/priv-app/
E/installd(  282): system dir 2 : /vendor/app/
E/installd(  282): system dir 3 : /oem/app/
I/TactileAssist( 1015): List of disabled apps :
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/OMACP   ( 5995): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
I/ServiceManager(  314): Waiting for service AtCmdFwd...
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
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/Mms/Omacp( 5776): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
E/Zygote  ( 6018): MountEmulatedStorage()
E/Zygote  ( 6018): v2
I/libpersona( 6018): KNOX_SDCARD checking this for 10053
I/libpersona( 6018): KNOX_SDCARD not a persona
I/SELinux ( 6018): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/PackageManager( 1015): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
I/SELinux ( 6018): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6018): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=6018 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
W/libprocessgroup( 1015): failed to open /acct/uid_10042/pid_5342/cgroup.procs: No such file or directory
I/OMACP   ( 5995): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 5995): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
W/BaseAppContext( 2000): Using Auth Proxy for data requests.
I/OMACP   ( 5995): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 5995): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 5995): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 5995): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 5995): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 5995): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
D/TimaKeyStoreProvider( 6018): TimaSignature is unavailable
D/ActivityThread( 6018): Added TimaKeyStore provider
W/BaseAppContext( 2000): Using Auth Proxy for data requests.
I/OMACP   ( 5995): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 5995): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
W/BaseAppContext( 2000): Using Auth Proxy for data requests.
W/BaseAppContext( 2000): Using Auth Proxy for data requests.
I/OMACP   ( 5995): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 5995): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 5995): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
I/PeopleDatabaseHelper( 2000): cleanUpNonGplusAccounts done.
W/ResourcesManager( 6018): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/BaseAppContext( 2000): Using Auth Proxy for data requests.
D/Compatibility( 6018): onReceive() it will make start service
D/ActivityManager( 1015): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
D/ActivityManager( 1015): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/Compatibility( 6018): onHandleIntent()
D/Compatibility( 6018): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10175, android.intent.extra.user_handle=0}]
D/Compatibility( 6018): found: 2
I/UpdateIcingCorporaServi( 5397): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/DBG_POLICYDM( 5826): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
D/Compatibility( 6018): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6018): skipping ResolveInfo{1cdaf1ab com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 6018): considering ResolveInfo{141d3008 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 6018): default: com.sec.android.app.soundalive.SAControlPanelActivity
I/SL_DEBUG( 5929): isLoggable:: isProductShip = 1
D/Compatibility( 6018): enabling receiver ResolveInfo{234013a1 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/SL_DEBUG( 5929): isLoggable:: SL_DEBUG_EXIST = false
I/DBG_POLICYDM( 5826): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
D/Compatibility( 6018): enabling receiver ResolveInfo{17c999c6 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 6018): enabling receiver ResolveInfo{2d4fd87 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 6018): enabling receiver ResolveInfo{375944b4 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 6018): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
I/UpdateIcingCorporaServi( 5397): UpdateCorporaTask done [took 84 ms] updated apps [took 84 ms] 
I/ActivityManager( 1015): Killing 5242:com.google.android.talk/u0a104 (adj 15): empty #31
D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityThread( 5929): Loading provider com.samsung.android.sdk.samsunglink.provider.SLinkMedia: com.mfluent.asp.datamodel.ASPMediaStoreProvider
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5929): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/libprocessgroup( 1015): failed to open /acct/uid_10104/pid_5242/cgroup.procs: No such file or directory
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5929): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
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
E/Zygote  ( 6048): MountEmulatedStorage()
E/Zygote  ( 6048): v2
I/libpersona( 6048): KNOX_SDCARD checking this for 10041
I/libpersona( 6048): KNOX_SDCARD not a persona
I/SELinux ( 6048): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6048): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6048): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=6048 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  304): Explicit concurrent mark sweep GC freed 8712(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 642us total 21.371ms
D/TimaKeyStoreProvider( 6048): TimaSignature is unavailable
D/ActivityThread( 6048): Added TimaKeyStore provider
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 621us total 17.130ms
I/qtaguid ( 5530): Untagging socket 44
I/qtaguid ( 5530): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5530): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5530): untagSocket(44) failed with errno -22
I/System.out( 5530): Thread-959 calls detatch()
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 16.745ms
I/SA      ( 6048): [SSP] onCreated
W/art     ( 5881): Suspending all threads took: 11.564ms
I/SA      ( 6048): [TPM] There is no property file
I/SA      ( 6048): [SCU] isHaveSA() - false
I/SA      ( 6048): [TPM] getModelProperty : null
I/SA      ( 6048): [TPM] getCSCProperty : null
I/SA      ( 6048): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 6048): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 6048): [DM] TFT FEATURE: false
I/SA      ( 6048): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 6048): [DM] init START
I/ActivityManager( 1015): Killing 5461:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
I/SA      ( 6048): [DM] This device is not a Vodafone
W/ResourceType( 6048): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 6048): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 6048): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 6048): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 6048): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 6048): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 6048): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 6048): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 6048): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 6048): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 6048): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 6048): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 6048): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 6048): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 6048): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 6048): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 6048): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 6048): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 6048): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 6048): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 6048): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 6048): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 6048): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 6048): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 6048): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 6048): [SCU] isHaveSA() - false
I/SA      ( 6048): support phone number id : false
I/SA      ( 6048): [DM] Supports Ref Jpn : true
I/SA      ( 6048): [DM] init END
I/SA      ( 6048): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 6048): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10175 extra.user_handle.:0 ]
I/ActivityManager( 1015): Killing 5492:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
D/AndroidRuntime( 6042): 
D/AndroidRuntime( 6042): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6042): CheckJNI is OFF
D/AndroidRuntime( 6042): readGMSProperty: start
D/AndroidRuntime( 6042): readGMSProperty: already setted!!
D/AndroidRuntime( 6042): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6042): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6042): readGMSProperty: end
D/AndroidRuntime( 6042): addProductProperty: start
W/GAV2    ( 5881): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/libprocessgroup( 1015): failed to open /acct/uid_10069/pid_5461/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5492/cgroup.procs: No such file or directory
I/wpa_supplicant( 2077): nl80211: Received scan results (5 BSSes)
D/WifiP2pService( 1015): InactiveState{ what=147461 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147461 }
D/WifiP2pService( 1015): DefaultState{ what=147461 }
D/ChimeraCfgMgr( 2000): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2000): Module APK com.google.android.play.games already loaded
W/ResourcesManager( 5530): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5530): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/Icing   ( 2000): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
E/SMD     (  287): DCD OFF
I/ServiceManager(  314): Waiting for service AtCmdFwd...
D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
E/AffinityControl( 6042): AffinityControl: registerfunction enter
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6089): MountEmulatedStorage()
E/Zygote  ( 6089): v2
I/libpersona( 6089): KNOX_SDCARD checking this for 10100
I/ActivityManager( 1015): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6089 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/libpersona( 6089): KNOX_SDCARD not a persona
W/GAV2    ( 5881): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/AndroidRuntime( 6042): Calling main entry com.android.commands.am.Am
I/SELinux ( 6089): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6089): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6089): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/PersonaManagerService( 1015): inState():  stateMachine is null !!
I/PersonaManagerService( 1015): PersonaId don't exist
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/TimaKeyStoreProvider( 6089): TimaSignature is unavailable
D/ActivityThread( 6089): Added TimaKeyStore provider
W/ActivityManager( 1015): mDVFSHelper.acquire()
I/art     ( 1015): Explicit concurrent mark sweep GC freed 227271(15MB) AllocSpace objects, 6(4MB) LOS objects, 33% free, 27MB/41MB, paused 3.051ms total 199.631ms
D/PhoneWindow( 1015): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1015): *FMB* installDecor flags : 25362712
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6112): MountEmulatedStorage()
E/Zygote  ( 6112): v2
I/libpersona( 6112): KNOX_SDCARD checking this for 10175
I/libpersona( 6112): KNOX_SDCARD not a persona
I/SELinux ( 6112): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6112 uid=10175 gids={50175, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1015): Focused application set to: xxxx
D/InputDispatcher( 1015): Focus left window: 3136
I/SELinux ( 6112): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6112): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 6042): Shutting down VM
I/Icing   ( 2000): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=404, uhalitest
D/TimaKeyStoreProvider( 6112): TimaSignature is unavailable
D/ActivityThread( 6112): Added TimaKeyStore provider
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/PackageIntentReceiver( 6089): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 6089): Not GearManger package! 
D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
V/ActivityManager( 1015): Display changed displayId=0
D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1015): isKioskContainerExistOnDevice
V/ActivityThread( 3136): updateVisibility : ActivityRecord{2d47d978 token=android.os.BinderProxy@94fd12f {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6130): MountEmulatedStorage()
E/Zygote  ( 6130): v2
I/libpersona( 6130): KNOX_SDCARD checking this for 1000
I/libpersona( 6130): KNOX_SDCARD not a persona
I/SELinux ( 6130): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6130 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 5509:com.google.android.apps.plus/u0a120 (adj 15): empty #31
I/SELinux ( 6130): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
E/SELinux ( 6130): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/GLSActivity( 1838): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/SurfaceFlinger(  257): id=10 Removed YUIInstallC (5/9)
I/SurfaceFlinger(  257): id=10 Removed YUIInstallC (-2/9)
W/AccountFeatureHelper( 5881): Write apps_features disabled false
D/TimaKeyStoreProvider( 6130): TimaSignature is unavailable
D/ActivityThread( 6130): Added TimaKeyStore provider
W/GAV2    ( 5881): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager( 1015): Killing 5153:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 5530): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/WebViewFactory( 6112): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
E/Zygote  ( 6147): MountEmulatedStorage()
E/Zygote  ( 6147): v2
I/libpersona( 6147): KNOX_SDCARD checking this for 1000
I/libpersona( 6147): KNOX_SDCARD not a persona
I/SELinux ( 6147): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6147 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 5001:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
I/SELinux ( 6147): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6147): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/art     ( 6042): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/Finsky  ( 5530): [1] WearSupportService.startHygiene: disabled
D/Finsky  ( 5530): [1] DailyHygiene.access$600: Logging device features
I/LibraryLoader( 6112): Time to load native libraries: 2 ms (timestamps 2922-2924)
I/LibraryLoader( 6112): Expected native library version number "",actual native library version number ""
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,V/AlarmManager( 1015): waitForAlarm result :4
,D/TimaKeyStoreProvider( 6147): TimaSignature is unavailable
,D/ActivityThread( 6147): Added TimaKeyStore provider
,V/WebViewChromiumFactoryProvider( 6112): Binding Chromium to main looper Looper (main, tid 1) {234013a1}
,I/LibraryLoader( 6112): Expected native library version number "",actual native library version number ""
,I/chromium( 6112): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/ActivityManager( 1015): Killing 4853:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 4487:com.google.android.music:main/u0a111 (adj 15): empty #32
,D/DeviceConnectionService( 1838): client connected with version: 8296000
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/BrowserStartupController( 6112): Initializing chromium process, singleProcess=true
W/art     ( 6112): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6112): ApplicationContext is null in ApplicationStatus
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/chromium( 6112): [WARNING:resource_bundle.cc(286)] locale_file_path.empty(),
I/chromium( 6112): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379,
I/chromium( 6112): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,I/Adreno-EGL( 6112): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6112): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6112): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6112): Local Branch: 
I/Adreno-EGL( 6112): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6112): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6112):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/AcmsPackageEventListener( 6147): Received: android.intent.action.PACKAGE_ADDED
,I/ActivityManager( 1015): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6170 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 4310:com.android.calendar/u0a135 (adj 15): empty #31,
,E/Zygote  ( 6170): MountEmulatedStorage()
I/libpersona( 6170): KNOX_SDCARD checking this for 10120
E/Zygote  ( 6170): v2
I/libpersona( 6170): KNOX_SDCARD not a persona
,I/SELinux ( 6170): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6170): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ContextImpl( 6147): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
E/SELinux ( 6170): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/AcmsService( 6147): Enter Oncreate
,D/AcmsServiceMonitor( 6147): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 6147): creating AcmsCore
,D/AcmsCore( 6147): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6147): AcmsCore
,D/AcmsCore( 6147): init
D/AcmsCore( 6147): Looper handler is not null
D/AcmsCore( 6147): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6147): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6147): Incrementing - Counter value: 1
D/AcmsCore( 6147): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 6147): onStartCommand
D/AcmsService( 6147): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 6147): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6147): Incrementing - Counter value: 2
D/AcmsService( 6147): Incremented Counter Value : onStartCommand
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,W/libprocessgroup( 1015): failed to open /acct/uid_10150/pid_5153/cgroup.procs: No such file or directory
,D/ActivityThread( 6147): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,W/libprocessgroup( 1015): failed to open /acct/uid_10120/pid_5509/cgroup.procs: No such file or directory
,D/AcmsCertificateMngr( 6147): AcmsCertificateMngr
,D/TimaKeyStoreProvider( 6170): TimaSignature is unavailable
D/ActivityThread( 6170): Added TimaKeyStore provider
,D/AcmsRevocationMngr( 6147): AcmsRevocationMngr
,W/ResourcesManager( 6170): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup( 1015): failed to open /acct/uid_10040/pid_5001/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10111/pid_4487/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10134/pid_4853/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10135/pid_4310/cgroup.procs: No such file or directory
,D/AcmsService( 6147): Inside handle Intent
D/AcmsService( 6147): App added - package name: com.test.thalitest
D/AcmsCore( 6147): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6147): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6147): Incrementing - Counter value: 3
D/AcmsCore( 6147): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 6147): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 6147): Decrementing - Counter value: 2
,I/Mms/MmsApp( 5776):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5776): [start]    fillCache consume time = 1907.975364
D/Mms/ComposeMessageFragment( 5776): fillCache, easy = false
,W/chromium( 6112): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,D/AbsListView( 5776): Get MotionRecognitionManager
,D/MotionRecognitionService( 1015):  ssp status : false
,D/Mms/ComposeMessageFragment( 5776): [end]    fillCache consume time = 95.356562
,W/art     ( 6112): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6112): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6112): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6112): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6112): CordovaWebView is running on device made by: samsung
,W/ActivityManager( 1015): Activity pause timeout for ActivityRecord{23ac294b u0 com.test.thalitest/.MainActivity t3}
,W/art     ( 6112): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6112): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6112): Render dirty regions requested: true
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
,D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
,V/ActivityThread( 6112): updateVisibility : ActivityRecord{8b3234d token=android.os.BinderProxy@125677 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6112): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 6112): *FMB* isFloatingMenuEnabled return false
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,I/SurfaceFlinger(  257): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1015): Focus entered window: 6112
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/SRIB_DCS( 6112): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6112): Initialized EGL, version 1.4
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,D/OpenGLRenderer( 6112): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6112): Enabling debug mode 0
,D/Mms/BubbleViewCache( 5776): fillCache bubble = 1
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
,I/ActivityManager( 1015): Displayed Component not be shown by security: +675ms (total +768ms)
,W/ActivityManager( 1015): mDVFSHelper.release()
,W/IInputConnectionWrapper( 6112): showStatusIcon on inactive InputConnection
I/Timeline( 6112): Timeline: Activity_idle id: android.os.BinderProxy@125677 time:83439
,I/Timeline( 1015): Timeline: Activity_windows_visible id: ActivityRecord{23ac294b u0 com.test.thalitest/.MainActivity t3} time:83440
,I/SurfaceFlinger(  257): id=13 Removed uhalitest (7/9)
,I/SamsungIME( 1800): getCurrentCandidateView
,I/SurfaceFlinger(  257): id=13 Removed uhalitest (-2/9)
,I/splitIntent( 1015): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/ActivityManager( 1015): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 5530): [980] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1838): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BindingManager( 6112): Cannot call determinedVisibility() - never saw a connection for the pid: 6112
,D/SamsungIME( 1800): Dismiss ExpandCandiate
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,I/System.out( 5530): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 5530): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5530): (HTTPLog)-Static: isShipBuild true
I/System.out( 5530): (HTTPLog)-Thread-969-128038935: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5530): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  275): uids 10028
D/EnterpriseController(  275): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  275): getNetworkForDns: using netid 502 for uid 10028
,I/System.out( 5530): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/JsMessageQueue( 6112): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1800): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1800): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1800): KeybaordView init() : load resources
,D/jxcore_app_log( 6112): JniHelper::setJavaVM(0xb8c13450), pthread_self() = -1189732784
,D/JX-Cordova( 6112): jxcore cordova android initializing
,I/ActivityManager( 1015): Killing 5169:com.google.android.gm/u0a101 (adj 15): empty #31
,I/SamsungIME( 1800): getCurrentKeyboard
I/SamsungIME( 1800): getTextKeyboard
,D/SamsungIME( 1800): [SwiftkeyWrapper] currentLangauge : 1701729619
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardViewMediator( 1177): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 1177): doKeyguard: not showing because lockscreen is off
V/KeyguardEffectViewController( 1177): *** Keyguard wallpaper service already unbounded
,W/libprocessgroup( 1015): failed to open /acct/uid_10101/pid_5169/cgroup.procs: No such file or directory
,I/art     ( 6112): Background partial concurrent mark sweep GC freed 5733(478KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 11MB/19MB, paused 8.213ms total 40.471ms
,I/DBG_POLICYDM( 5826): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5826): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5826): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5826): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5826): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5826): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5826): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/SamsungIME( 1800): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/PowerManagerService( 1015): [PWL] Off : 5s ago,
,D/CAR.SERVICE( 5693): mConnectedToCar = false, abort
,E/ActivityThread( 5693): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@25bcc574 that was originally bound here
E/ActivityThread( 5693): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@25bcc574 that was originally bound here
E/ActivityThread( 5693): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 5693): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 5693): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 5693): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 5693): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5693): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5693): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5693): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5693): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5693): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5693): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5693): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5693): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5693): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3280)
E/ActivityThread( 5693): 	at android.app.ActivityThread.access$1900(ActivityThread.java:181)
E/ActivityThread( 5693): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1565)
E/ActivityThread( 5693): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5693): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 5693): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 5693): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5693): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5693): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 5693): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityThread( 5693): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@c65da3f that was originally bound here
E/ActivityThread( 5693): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@c65da3f that was originally bound here
E/ActivityThread( 5693): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 5693): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 5693): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 5693): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 5693): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 5693): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5693): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5693): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5693): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5693): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5693): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5693): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5693): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3312)
E/ActivityThread( 5693): 	at android.app.ActivityThread.access$2000(ActivityThread.java:181)
E/ActivityThread( 5693): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1570)
E/ActivityThread( 5693): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5693): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 5693): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 5693): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5693): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5693): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 5693): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 1015): Unbind failed: could not find connection for android.os.BinderProxy@1dfea382
,W/jxcore-log( 6112): Initializing JXcore engine
W/jxcore-log( 6112): JXcore engine is ready
,W/jxcore-log( 6112): Starting JXcore engine
,E/audit   ( 1923): type=1400 msg=audit(1450229622.040:205): avc:  denied  { ioctl } for  pid=6112 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1923):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1923): type=1300 msg=audit(1450229622.040:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=bed82d58 items=0 ppid=304 ppcomm=main pid=6112 auid=4294967295 uid=10175 gid=10175 euid=10175 suid=10175 fsuid=10175 egid=10175 sgid=10175 fsgid=10175 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1923): type=1320 msg=audit(1450229622.040:205): 
,W/jxcore-log( 6112): Platform android
W/jxcore-log( 6112): 
W/jxcore-log( 6112): Process ARCH arm
W/jxcore-log( 6112): 
,E/SMD     (  287): DCD OFF
,D/AcmsKeyStoreHelper( 6147):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 6147): Key Store exist
I/AcmsKeyStoreHelper( 6147): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 6147):  getKeyStoreForApplication Exit
,I/AcmsCertificateMngr( 6147): getKeyStoreForApplication success 
D/AcmsCore( 6147): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
,D/AcmsServiceMonitor( 6147): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6147): Decrementing - Counter value: 1
D/AcmsCore( 6147): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 6147): This is NOT a valid MirrorLink app
D/AcmsCore( 6147): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 6147): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6147): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 6147): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 6147): getSvcCounter - Counter value: 0
D/AcmsService( 6147): Enter onDestroy
I/AcmsService( 6147): cleanUp(): inside service clean up
D/AcmsCore( 6147): AcmsCore: inside DeInit
D/AcmsCore( 6147): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 6147): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 6147): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 6147): KeyStoreHelper: inside cleanup
,D/AcmsAppEntryInterface( 6147): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 6147): getSvcCounter - Counter value: 0
D/AcmsService( 6147): killing acms process
I/Process ( 6147): Sending signal. PID: 6147 SIG: 9
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,I/ActivityManager( 1015): Process ACMS.Process (pid 6147)(adj 0) has died(54,1154)
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 6112): JXcore Cordova bridge is ready!
I/jxcore-log( 6112): 
,W/jxcore-log( 6112): JXcore engine is started
I/Choreographer( 6112): Skipped 141 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6112): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,I/jxcore-log( 6112): Toggling radios to true
I/jxcore-log( 6112): 
,D/BluetoothAdapter( 6112): enable()
,D/BluetoothAdapter( 6112): enable(): BT is already enabled..!
,D/SecContentProvider( 1015): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1015): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1015): mCursor = null
,D/WifiService( 1015): setWifiEnabled: true pid=6112, uid=10175
,W/ActivityManager( 1015): Permission Denial: getCurrentUser() from pid=6112, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1015): Failed getting userId using ActivityManagerNative
W/WifiService( 1015): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6112, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1015): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24778)
W/WifiService( 1015): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1015): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1015): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1015): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1015): name = wifi_on
,I/WifiService( 1015): disconnect: pid=6112, uid=10175
,I/jxcore-log( 6112): Radios toggled
I/jxcore-log( 6112): 
I/wpa_supplicant( 2077): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 6112): Got Device Bluetooth address: 7C:F9:0E:37:96:AB
I/jxcore-log( 6112): 
,I/jxcore-log( 6112): Perf Test app loaded loaded
I/jxcore-log( 6112): 
,I/jxcore-log( 6112): check test folder
I/jxcore-log( 6112): 
,I/jxcore-log( 6112): found test : ./testFindPeers.js
I/jxcore-log( 6112): 
,I/wpa_supplicant( 2077): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 2077): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 2077): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 2077): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 2077): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/wpa_supplicant( 2077): Cmd 35605 not handled
E/WifiStateMachine( 1015): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 2077): reset timer : RESET_TIMER 0
I/wpa_supplicant( 2077): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2077): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2077): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 2077): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 2077): First Scan Start
D/Tethering( 1015): InitialState.processMessage what=4
I/wpa_supplicant( 2077): Scan requested (ret=0) - scan timeout 30 seconds
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,E/WifiConfigStore( 1015): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/Tethering( 1015): No numeric data
,D/Tethering( 1015): sendTetherStateChangedBroadcast 0, 0, 0,
D/Tethering( 1015): clearTetheredNotification()
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1015): interfaceStatusChanged wlan0, false
V/NetworkStats( 1015): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1177): updateTetherState():false, false
,E/WifiNative-wlan0( 1015): do suspend true
,D/WifiP2pService( 1015): InactiveState{ what=143375 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
,D/CommandListener(  275): Clearing all IP addresses on wlan0
,V/NetworkStats( 1015): performPollLocked() took 10ms
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,V/NativeCrypto( 1838): Read error: ssl=0xb913c328: I/O error during system call, Connection timed out
,V/NativeCrypto( 1838): SSL shutdown failed: ssl=0xb913c328: I/O error during system call, Broken pipe
,E/ConnectivityService( 1015): updateNetworkInfo()
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1015): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): DefaultState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Forcing reevaluation
I/jxcore-log( 6112): found test : ./testSendData.js
I/jxcore-log( 6112): 
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,E/WifiStateMachine( 1015): Start Disconnecting Watchdog 1
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14952 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
I/wpa_supplicant( 2077): wlan0: Setting scan request: 0 sec 0 usec
I/System.out( 1015): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1015): Tagging socket 358 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1015, getuid(): 1000
I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
,I/qtaguid ( 1015): Untagging socket 358
,I/System.out( 1015): (HTTPLog)-Static: isSBSettingEnabled false
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
E/WifiNative-wlan0( 1015): do suspend true
,D/WifiP2pService( 1015): InactiveState{ what=143375 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=143375 },
,I/Hs20UtilService( 3606): Starting #8
,I/Hs20UtilService( 3606): Message received 5007
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NearbySettings( 1367): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1367): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1367): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1367): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1367): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1367): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1367): MountReceiver.mPrefHandler - 7002
,D/EnterpriseController(  275): uids 1000
D/EnterpriseController(  275): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  275): getNetworkForDns: using netid 0 for uid 1000
D/CommandListener(  275): Clearing all IP addresses on wlan0
,D/ConnectivityService( 1015): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityService( 1015): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Validated
D/ConnectivityService( 1015): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524292
D/WIFI_P2P( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1015): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/TelephonyNetworkFactory( 1454): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1015): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/TelephonyNetworkFactory( 1454): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 2000): CM callback handler got msg 524292
,D/EntConnectivity( 1015): Not allowed due to - mEnabled false - primarySimSlot false
,D/Tethering( 1015): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1015): MasterInitialState.processMessage what=3
,D/EntConnectivity( 1015): Not allowed due to - mEnabled false - primarySimSlot false
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): updateIfacesLocked()
D/ConnectivityService( 1015): nai.networkMonitor.doQuit()
V/NetworkStats( 1015): performPollLocked(flags=0x1)
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): doQuit - quitNow()
D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
E/ConnectivityService( 1015): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,V/NetworkStats( 1015): performPollLocked() took 4ms
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1177): EthernetConnected: false
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
D/WifiNetworkAgent( 1015): NetworkAgent: NetworkAgent channel lost
,I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WIFI    ( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6237): MountEmulatedStorage(),
E/Zygote  ( 6237): v2
I/libpersona( 6237): KNOX_SDCARD checking this for 10104
I/libpersona( 6237): KNOX_SDCARD not a persona
,I/SELinux ( 6237): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1015): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6237 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 6237): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6237): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/Choreographer( 6112): Skipped 106 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6112): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/TimaKeyStoreProvider( 6237): TimaSignature is unavailable
,D/ActivityThread( 6237): Added TimaKeyStore provider
,W/ResourcesManager( 6237): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PhoneApp( 1454): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1454): FileWriteThread : threadType = 3
,D/PhoneApp( 1454): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1454): FileWriteThread : threadType = 3
,D/PhoneApp( 1454): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1454): FileWriteThread : threadType = 3
,D/PhoneApp( 1454): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1454): FileWriteThread : threadType = 3
,D/PhoneApp( 1454): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1454): FileWriteThread : threadType = 3
,D/PhoneApp( 1454): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1454): FileWriteThread : threadType = 3
,D/PhoneApp( 1454): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1454): FileWriteThread : threadType = 3
,D/PhoneApp( 1454): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1454): FileWriteThread : threadType = 3
,D/PhoneApp( 1454): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1454): FileWriteThread : threadType = 3
,D/PhoneApp( 1454): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1454): FileWriteThread : threadType = 3
,D/PhoneApp( 1454): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1454): FileWriteThread : threadType = 3
,D/PhoneApp( 1454): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1454): FileWriteThread : threadType = 3
,D/PhoneApp( 1454): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1454): FileWriteThread : threadType = 3,
D/PhoneApp( 1454): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1454): FileWriteThread : threadType = 3
,D/PhoneApp( 1454): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1454): FileWriteThread : threadType = 3
,I/Babel   ( 6237): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6237): MmsConfig.loadMmsSettings
I/Babel   ( 6237): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 6237): MmsConfig.loadFromDatabase
,E/Babel   ( 6237): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 6237): MmsConfig.loadFromResources
,E/Babel   ( 6237): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6237): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 6237): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_StickerModule( 6237): App launched.
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,W/QCamera2Factory(  281): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  281): getCameraInfo: X
,D/NearbySettings( 1367): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 3606): Starting #9
V/NearbySettings( 1367): DMSUtil.isNetworkConnected - flag-null, state-null
I/Hs20UtilService( 3606): Message received 5007
,I/NearbySettings( 1367): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,W/QCamera2Factory(  281): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  281): getCameraInfo: X
,I/NearbySettings( 1367): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1367): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1367): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1367): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/VideoCapabilities( 6237): Unrecognized profile 2130706433 for video/avc
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6237): Unsupported mime audio/evrc
,W/AudioCapabilities( 6237): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6237): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6237): Unsupported mime audio/mpeg-L2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6237): Unsupported mime audio/x-ms-wma
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6237): Unsupported mime audio/x-ima
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6237): Unsupported mime audio/qcelp
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6237): Unsupported mime audio/evrc
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
,W/VideoCapabilities( 6237): Unsupported mime video/wvc1
,W/VideoCapabilities( 6237): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6237): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6237): Unsupported mime video/wvc1
,W/VideoCapabilities( 6237): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6237): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6237): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6237): Unsupported mime video/mp43
,W/VideoCapabilities( 6237): Unsupported mime video/sorenson
,W/VideoCapabilities( 6237): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6237): Unsupported profile 4 for video/mp4v-es
,D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 1015): updateDataUsageMap
,D/GpsLocationProvider( 1015): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3136): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/DBG_DM  ( 3136): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,I/PCWCLIENTTRACE_PushUtil( 5793): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5793): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5793): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5793): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1015): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
I/splitIntent( 1015): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5793): noConnectivity : true
,E/Zygote  ( 6280): MountEmulatedStorage(),
E/Zygote  ( 6280): v2
I/libpersona( 6280): KNOX_SDCARD checking this for 10111
,I/libpersona( 6280): KNOX_SDCARD not a persona
,I/SELinux ( 6280): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6280 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6280): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6280): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6295): MountEmulatedStorage(),
I/libpersona( 6295): KNOX_SDCARD checking this for 10009
E/Zygote  ( 6295): v2
I/libpersona( 6295): KNOX_SDCARD not a persona
I/SELinux ( 6295): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6295): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1015): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6295 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6295): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,D/TimaKeyStoreProvider( 6280): TimaSignature is unavailable,
D/ActivityThread( 6280): Added TimaKeyStore provider,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/accuweather( 1725): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6303): MountEmulatedStorage()
,E/Zygote  ( 6303): v2
I/libpersona( 6303): KNOX_SDCARD checking this for 10145
I/libpersona( 6303): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6303 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 6303): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6303): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6303): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/accuweather( 1725): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1725): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1725): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1725): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1725): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1725): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/TimaKeyStoreProvider( 6295): TimaSignature is unavailable
,D/ActivityThread( 6295): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 6303): TimaSignature is unavailable
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,D/ActivityThread( 6303): Added TimaKeyStore provider
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/SMD     (  287): DCD OFF
,I/libpersona( 6325): KNOX_SDCARD checking this for 10081
E/Zygote  ( 6325): MountEmulatedStorage()
I/libpersona( 6325): KNOX_SDCARD not a persona
E/Zygote  ( 6325): v2
I/SELinux ( 6325): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6325): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6325): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6325 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/TimaKeyStoreProvider( 6325): TimaSignature is unavailable
D/ActivityThread( 6325): Added TimaKeyStore provider
,W/ResourcesManager( 6303): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6303): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6303): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6303): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6303): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 1015): Killing 5021:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,I/MusicStore( 6280): Database version: 108
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/wpa_supplicant( 2077): nl80211: Received scan results (6 BSSes)
,I/wpa_supplicant( 2077): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 2077): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 2077): Trying to associate with  'G700'
I/wpa_supplicant( 2077): Re-associate with C0.AA.48
I/wpa_supplicant( 2077): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 2077): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,D/WifiMonitor( 1015): didn't find BSSID Trying to associate with SSID 'NG700'
,W/libprocessgroup( 1015): failed to open /acct/uid_10044/pid_5021/cgroup.procs: No such file or directory
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,I/ActivityManager( 1015): Killing 5381:com.samsung.aasaservice/1000 (adj 15): empty #31
,I/KLMS-2.5.183: ( 3660): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 16 02:33:45 GMT+01:00 2015
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3660): KLMSAbstractReciever(): onReceive().END.
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3660): KLMSIntentService(): onCreate()
,E/Zygote  ( 6353): MountEmulatedStorage()
E/Zygote  ( 6353): v2
I/libpersona( 6353): KNOX_SDCARD checking this for 10113
I/libpersona( 6353): KNOX_SDCARD not a persona
,I/SELinux ( 6353): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6353): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6353): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1015): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6353 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager( 1015): Killing 5754:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3660): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/art     (  304): Explicit concurrent mark sweep GC freed 8740(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 24.052ms
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 6353): TimaSignature is unavailable
D/ActivityThread( 6353): Added TimaKeyStore provider
,E/wpa_supplicant( 2077): Cmd 35605 not handled
I/wpa_supplicant( 2077): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 2077): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 2077): Associated with C0.AA.48
I/wpa_supplicant( 2077): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 2077): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 2077): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 604us total 16.827ms
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1015): interfaceStatusChanged wlan0, false
,I/KLMS-2.5.183: ( 3660): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/wpa_supplicant( 2077): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 2077): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,I/wpa_supplicant( 2077): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 2077): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 2077): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2077): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2077): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 2077): Blacklist: Clear (temp) 
I/wpa_supplicant( 2077): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, true
D/Tethering( 1015): interfaceLinkStateChanged wlan0, true
D/Tethering( 1015): interfaceStatusChanged wlan0, true
E/Tethering( 1015): No numeric data
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, true
D/Tethering( 1015): interfaceLinkStateChanged wlan0, true
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 624us total 18.367ms
,D/Tethering( 1015): interfaceStatusChanged wlan0, true
,I/KLMS-2.5.183: ( 3660): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3660): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.183: ( 3660): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3660): StateImplV2(): networkChangeListener().END
,E/Zygote  ( 6370): MountEmulatedStorage()
E/Zygote  ( 6370): v2
I/libpersona( 6370): KNOX_SDCARD checking this for 10034
I/libpersona( 6370): KNOX_SDCARD not a persona
,I/SELinux ( 6370): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6370): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6370): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6370 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5381/cgroup.procs: No such file or directory
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,D/Tethering( 1015): sendTetherStateChangedBroadcast 1, 0, 0
,D/Tethering( 1015): clearTetheredNotification()
,W/libprocessgroup( 1015): failed to open /acct/uid_10152/pid_5754/cgroup.procs: No such file or directory
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
D/WifiNative-wlan0( 1015): callSECApiVoid - ID [50]
,I/KLMS-2.5.183: ( 3660): KLMSIntentService(): onDestroy()
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
,D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/HotspotTile( 1177): updateTetherState():false, false
V/NetworkStats( 1015): performPollLocked() took 3ms
,E/WifiConfigStore( 1015): setLastSelectedConfiguration -1
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/TimaKeyStoreProvider( 6370): TimaSignature is unavailable
,D/ActivityThread( 6370): Added TimaKeyStore provider
,D/ConnectivityService( 1015): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1015): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService( 1015): updateNetworkInfo()
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiConfigStore( 1015): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiConfigStore( 1015): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  275): Setting iface cfg
,E/WifiStateMachine( 1015): Start Dhcp Watchdog 2
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1015): mCursor = null
,E/WifiNative-wlan0( 1015): do suspend false
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,D/WifiP2pService( 1015): InactiveState{ what=143375 }
D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
,W/ResourcesManager( 6280): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6280): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/BadgeProvider( 5974): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 1476): reloadBadges entered.
D/BadgeProvider( 5974): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5974): sendNotify, [notify] : null
D/BadgeProvider( 5974): update, [uri] : content://com.sec.badge/apps/1
I/SO_AGENT( 6370): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
D/BadgeProvider( 5974): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5974): update, [UpdateCount] : 1
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,I/DBG_POLICYDM( 5826): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,V/JNIHelp ( 6280): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/SPPClientService( 5901): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/DBG_POLICYDM( 5826): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 5826): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5826): [com.policydm.XDMApplication(477/isNetworkChanged)] network not changed.... 
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/ActivityManager( 1015): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
I/SA      ( 6048): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 6048): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 6048): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6048): [SLFUCHKMGR] constructor called
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push,
,I/SA      ( 6048): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6048): [OR] == isSIMCardReady false ==
,I/SA      ( 6048): [SCU] == networkStateCheck == false
,I/SA      ( 6048): [OR] onReceive END
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,V/DownloadManager( 1228): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,E/SPPClientService( 5901): [[SystemStateMonitorService]] No Active Internet
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6395): MountEmulatedStorage()
E/Zygote  ( 6395): v2
I/libpersona( 6395): KNOX_SDCARD checking this for 1000
I/libpersona( 6395): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6395 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 6395): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6395): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6395): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityThread( 6280): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6280): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@160624c8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6280): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6280): GMSCore installation verified
,D/TimaKeyStoreProvider( 6395): TimaSignature is unavailable
,D/ActivityThread( 6395): Added TimaKeyStore provider
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 56362(2MB) AllocSpace objects, 3(96KB) LOS objects, 33% free, 27MB/41MB, paused 2.783ms total 168.740ms
,E/dhcpcd  ( 6411): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6411): version 5.5.6 starting
,E/dhcpcd  ( 6411): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/ActivityManager( 1015): Killing 5420:com.google.android.partnersetup/u0a15 (adj 15): empty #31,
,I/ConfigStore( 6280): Config Database version: 1
,V/AlarmManager( 1015): waitForAlarm result :8
,I/dhcpcd  ( 6411): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6411): wlan0: sendmsg: Cannot assign requested address
,I/dhcpcd  ( 6411): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 6411): bssid match
I/dhcpcd  ( 6411): wlan0: rebinding lease of 192.168.1.129
,D/SecurityLogAgent( 6395): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6395): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6395): StateMachine : Current State = 1
,D/SecurityLogAgent( 6395): StateMachine : Changed Current State = 1
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6421): MountEmulatedStorage(),
E/Zygote  ( 6421): v2
I/SELinux ( 6421): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 6421): KNOX_SDCARD checking this for 10159
I/libpersona( 6421): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6421 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 5809:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,I/SELinux ( 6421): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6421): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6421): TimaSignature is unavailable
,D/ActivityThread( 6421): Added TimaKeyStore provider
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6353): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6353): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6280): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6280): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6280): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/libprocessgroup( 1015): failed to open /acct/uid_10015/pid_5420/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10156/pid_5809/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6353): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6353): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/iu.Environment( 2000): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/iu.UploadsManager( 2000): num queued entries: 0
,I/iu.UploadsManager( 2000): num updated entries: 0,
I/ActivityManager( 1015): Killing 5746:com.samsung.android.sm/1000 (adj 15): empty #31
I/iu.SyncManager( 2000): NEXT; no task
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,I/AudioService( 1015): getStreamVolume 3 index 0
,I/MediaRouter( 6280): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6280): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SSRM:n  ( 1015): SIOP:: AP = 340
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5746/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6459): MountEmulatedStorage()
E/Zygote  ( 6459): v2
I/libpersona( 6459): KNOX_SDCARD checking this for 10002
I/libpersona( 6459): KNOX_SDCARD not a persona
,I/SELinux ( 6459): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1015): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6459 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6459): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6459): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6459): TimaSignature is unavailable
,D/ActivityThread( 6459): Added TimaKeyStore provider
,W/ResourcesManager( 6280): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6280): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/WebViewFactory( 6353): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,I/GHttpClientFactory( 6280): Using the GMSCore's GoogleHttpClient
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/LibraryLoader( 6353): Time to load native libraries: 2 ms (timestamps 9503-9505)
,I/LibraryLoader( 6353): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6353): Binding Chromium to main looper Looper (main, tid 1) {d224399}
,I/LibraryLoader( 6353): Expected native library version number "",actual native library version number ""
I/chromium( 6353): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6353): Initializing chromium process, singleProcess=true
,W/art     ( 6353): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6353): ApplicationContext is null in ApplicationStatus
,I/ActivityManager( 1015): Killing 5443:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/chromium( 6353): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 6353): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
I/chromium( 6353): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,E/Zygote  ( 6484): MountEmulatedStorage(),
E/Zygote  ( 6484): v2
I/libpersona( 6484): KNOX_SDCARD checking this for 1000
I/libpersona( 6484): KNOX_SDCARD not a persona
,I/SELinux ( 6484): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6484 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/Adreno-EGL( 6353): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6353): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6353): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6353): Local Branch: 
I/Adreno-EGL( 6353): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6353): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6353):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/SELinux ( 6484): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6484): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6484): TimaSignature is unavailable
,D/ActivityThread( 6484): Added TimaKeyStore provider
,W/AudioManagerAndroid( 6353): Requires BLUETOOTH permission
,I/DIAGMON_AGENT( 6484): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,I/NSApplication( 6353): Starting up...
,I/ActivityManager( 1015): Killing 5842:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 5138:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #32
,W/libprocessgroup( 1015): failed to open /acct/uid_10032/pid_5443/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5842/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5138/cgroup.procs: No such file or directory
,E/Zygote  ( 6513): MountEmulatedStorage()
,E/Zygote  ( 6513): v2
I/libpersona( 6513): KNOX_SDCARD checking this for 10125
I/libpersona( 6513): KNOX_SDCARD not a persona
,I/dhcpcd  ( 6411): wlan0: acknowledged 192.168.1.129 from 192.168.1.1
,I/SELinux ( 6513): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6513): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6513 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux ( 6513): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 5476:com.sec.knox.bridge/1000 (adj 15): empty #31
,I/DIAGMON_AGENT( 6484): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0,
,I/DIAGMON_AGENT( 6484): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6484): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,D/TimaKeyStoreProvider( 6513): TimaSignature is unavailable
,D/ActivityThread( 6513): Added TimaKeyStore provider
,I/DIAGMON_AGENT( 6484): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6484): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6484): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,I/ActivityManager( 1015): Killing 5776:com.android.mms/u0a46 (adj 15): empty #31
,I/dhcpcd  ( 6411): wlan0: leased 192.168.1.129 for 86400 seconds
,W/ResourcesManager( 6513): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6513): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6513): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6513): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE,
I/QuickConnect( 6513): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6513): PeriphStartReceiver.onReceive - no need to start,
I/splitIntent( 1015): Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1015): Killing 5955:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31,
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3606): Starting #10,
,I/Hs20UtilService( 3606): Message received 5007
,D/NearbySettings( 1367): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1367): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1367): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/CountryDetector( 1015): No listener is left
,I/NearbySettings( 1367): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1367): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1367): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1367): MountReceiver.mPrefHandler - 7002
,W/libprocessgroup( 1015): failed to open /acct/uid_10046/pid_5776/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5476/cgroup.procs: No such file or directory,
W/libprocessgroup( 1015): failed to open /acct/uid_10047/pid_5955/cgroup.procs: No such file or directory
,E/WifiNative-wlan0( 1015): do suspend true
,D/WifiP2pService( 1015): InactiveState{ what=143375 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiStateMachine( 1015): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,E/WifiStateMachine( 1015): VerifyingLinkState enter
,D/WifiNative-wlan0( 1015): callSECApiInt - ID [210]
,E/ConnectivityService( 1015): updateNetworkInfo()
,D/ConnectivityService( 1015): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1015): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 1015): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
D/ConnectivityService( 1015): Adding Route [fe80::/64 -> :: wlan0] to network 503
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
D/ConnectivityService( 1015): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,I/Hs20UtilService( 3606): Starting #11
E/WifiStateMachine( 1015): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/ConnectivityService( 1015): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1015): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1015): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 1015): LTETest block dns file not exists
,I/Hs20UtilService( 3606): Message received 5007
,D/ConnectivityService( 1015): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 1015): updateNetworkInfo()
,D/NearbySettings( 1367): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,E/ConnectivityService( 1015): updateNetworkInfo()
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1015): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1015): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,D/ConnectivityService( 1015):    accepting network in place of null
,D/WIFI_P2P( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1454): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1454): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/NearbySettings( 1367): MountReceiver.onReceive - Keep current state
I/System.out( 1015): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  275): uids 1000
D/EnterpriseController(  275): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  275): getNetworkForDns: using netid 503 for uid 1000
E/CSLegacyTypeTracker( 1015): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1015): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1015): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/WIFI    ( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1015): mBoosterFLAG : 0
I/WifiTrafficPoller( 1015): current booster mode : FullMode
,D/ConnectivityService( 1015): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/WifiNative-wlan0( 1015): callSECApiVoid - ID [212]
,D/EntConnectivity( 1015): Not allowed due to - mEnabled false - primarySimSlot false
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 2000): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Tethering( 1015): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1015): MasterInitialState.processMessage what=3
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit,
V/NetworkStats( 1015): updateIfacesLocked()
D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
V/NetworkStats( 1015): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,V/NetworkStats( 1015): performPollLocked() took 5ms
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3606): Starting #12
,I/Hs20UtilService( 3606): Message received 5007
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NearbySettings( 1367): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController( 1177): EthernetConnected: false
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
V/NearbySettings( 1367): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1367): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1367): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1367): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1367): MountReceiver.onReceive - Keep current state
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3606): Starting #13,
,I/Hs20UtilService( 3606): Message received 5007
,D/NearbySettings( 1367): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1367): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1015): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1015): mCursor = null
,I/System.out( 1015): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1015): mCursor = null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Dec 2015 01:33:47 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450229627128], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450229627110]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Don't send network conditions - lacking user consent.,
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Validated
,D/ConnectivityService( 1015): Validated NetworkAgentInfo [WIFI () - 503],
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524290
D/ConnectivityService( 1015): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 2000): CM callback handler got msg 524290
D/ConnectivityService( 1015): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1015): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/SurfaceFlinger(  257): id=15 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 1015): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,D/SRIB_DCS( 1177): log_dcs ThreadedRenderer::initialize entered! 
,D/StatusBar.NetworkController( 1177): EthernetConnected: false
,D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
,E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1015): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3136): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/NetworkMonitor( 6280): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil( 5793): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5793): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5793): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5793): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1015): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,I/splitIntent( 1015): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,D/accuweather( 1725): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,V/MusicLeanback( 6280): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
I/FOTA_Client( 6295): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 6395): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6395): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6395): StateMachine : Current State = 1
,D/SecurityLogAgent( 6395): StateMachine : Changed Current State = 1
,D/accuweather( 1725): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
,D/accuweather( 1725): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1725): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1725): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/FOTA_Client( 6295): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 6295): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,D/accuweather( 1725): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
W/FOTA_Client( 6295): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/DIAGMON_AGENT( 6484): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1725): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/DIAGMON_AGENT( 6484): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6484): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 6484): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/WaitQueueForNetworkActivate( 5861): notifyNetworkActivated
I/KLMS-2.5.183: ( 3660): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 16 02:33:47 GMT+01:00 2015
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3660): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.183: ( 3660): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3660): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3660): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3660): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3660): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.183: ( 3660): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3660): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.183: ( 3660): NetworkChangeOperations(): uploadRequestLog().START 
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.183: ( 3660): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.183: ( 3660): StateImplV2(): networkChangeListener().END
,W/ContextImpl( 5861): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/KLMS-2.5.183: ( 3660): KLMSIntentService(): onDestroy()
,D/QuickConnect( 6513): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6513): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6513): PeriphStartReceiver.onReceive - no need to start
,E/SPPClientService( 5901): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/DBG_POLICYDM( 5826): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5826): [com.policydm.XDMApplication(469/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5826): [com.policydm.XDMApplication(471/isNetworkChanged)] network changed.... 
,I/SA      ( 6048): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 6048): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6048): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6048): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6048): [OR] == isSIMCardReady false ==
,I/SA      ( 6048): [SCU] == networkStateCheck == true
,I/SA      ( 6048): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6048): isChinaCountryCode : false
I/SA      ( 6048): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6048): [OR] == networkStateCheck true ==
,I/SA      ( 6048): [OR] GetMyCountryZoneTask
I/SA      ( 6048): [OR] onReceive END
,V/DownloadManager( 1228): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/ActivityManager( 1015): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/SA      ( 6048): [SRS] prepareGetMyCountryZone
,I/DBG_POLICYDM( 5826): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5826): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5826): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5826): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5826): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/SA      ( 6048): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/DBG_POLICYDM( 5826): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
I/SA      ( 6048): [SSP] query invoked
,I/DBG_POLICYDM( 5826): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5826): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
D/SecContentProvider2( 1015): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1015): mCursor = null
,I/SA      ( 6048): [TPMU] GetMccFromDB : null
I/SA      ( 6048): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6048): [TPM] isNoProxy(default) : true
,E/DBG_POLICYDM( 5826): [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,E/File    ( 6048): fail readDirectory() errno=2
,I/DBG_POLICYDM( 5826): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/ActivityManager( 1015): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5861): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5861): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5861): exit::IDLE
D/InitializeManagerStateMachine( 5861): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5861): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5861): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5861): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5861): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5861): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5861): entry::SUCCESS
D/hcjo    ( 5861): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5861): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5861): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,I/iu.Environment( 2000): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/InitializeManagerStateMachine( 5861): exit::SUCCESS
D/InitializeManagerStateMachine( 5861): entry::IDLE
,I/iu.UploadsManager( 2000): num queued entries: 0
,I/iu.UploadsManager( 2000): num updated entries: 0
,I/iu.SyncManager( 2000): NEXT; no task
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1015): Queue : backgroundsplit_2 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/EnterpriseController(  275): uids 10012
D/EnterpriseController(  275): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  275): getNetworkForDns: using netid 503 for uid 10012
,D/ConnectivityService( 1015): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/art     ( 1838): Explicit concurrent mark sweep GC freed 36233(2MB) AllocSpace objects, 15(240KB) LOS objects, 40% free, 12MB/21MB, paused 1.159ms total 64.788ms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,I/SA      ( 6048): [RC New] Execute method=[GET] start
,I/SA      ( 6048): [RC New] Security=[true]
,I/System.out( 6048): Thread-1055(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6048): Thread-1055(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 6048): Thread-1055(ApacheHTTPLog):isShipBuild true
I/System.out( 6048): Thread-1055(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6048): Thread-1055(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController(  275): uids 10041
D/EnterpriseController(  275): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  275): getNetworkForDns: using netid 503 for uid 10041
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PackageManager( 1015): [MSG] MCS_UNBIND
,I/ActivityManager( 1015): Killing 5995:com.wsomacp/u0a25 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10025/pid_5995/cgroup.procs: No such file or directory
,I/SA      ( 6048): [RC New] [v2liruge] api execute + 607
,I/SA      ( 6048): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6048): AsyncTask #1 calls detatch()
,I/SA      ( 6048): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6048): [OCP] update openData : PL
,I/SA      ( 6048): [TPMU] getNetworkMcc : 
,I/SA      ( 6048): [SCU] saveMccToPreferece Start
,I/SA      ( 6048): [SCU] RegionMCC : 260
,I/SA      ( 6048): [SSP] query invoked
,I/SA      ( 6048): [TPMU] GetMccFromDB : null
,I/SA      ( 6048): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6048): [SCU] saveMccToPreferece End
,I/SA      ( 6048): [RC New] executeRequest [v2liruge] end. 681
I/SA      ( 6048): [RC New] Execute end
,I/SA      ( 6048): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6048): [OR] GetMyCountryZoneTask Success
V/AlarmManager( 1015): waitForAlarm result :8
,D/ConnectivityService( 1015): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1015): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 2000): CM callback handler got msg 524295
,D/ConnectivityService( 1015): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 2000): CM callback handler got msg 524295
,I/jxcore-log( 6112): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6112): 
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,I/dhcpcd  ( 6411): wlan0: sending IPv6 Router Solicitation
,I/SurfaceFlinger(  257): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger(  257): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 1015): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1015) eventTime = 93871
,D/PowerManagerService( 1015): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015 (0x0)
,D/PowerManagerService( 1015): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1015, ws=WorkSource{10054}) (elapsedTime=3501)
,D/ActivityManager( 1015): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/GAV4    ( 6353): Thread[GAThread,5,main]: No campaign data found.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1838): callingUid 10012, callindPid: 1838
,I/PowerManagerService( 1015): [PWL] Off : 15s ago
,I/PowerManagerService( 1015): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService( 1015): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 1015): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.music/.leanback.AutoCacheSchedulingService' (uid=10111, pid=6280, ws=null) (elapsedTime=108)
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/SMD     (  287): DCD OFF
,E/GmsUtils( 6280): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 6280): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,I/MusicLeanback( 6280): Conditions not met for autocaching.
,I/MusicLeanback( 6280): Stop autocaching.
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: android, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,I/BackgroundCompactionService( 1015): onStart. jobID=801
,I/BackgroundCompactionService( 1015): onStart done. jobID=801
,I/BackgroundCompactionService( 1015): Execute BGCompaction (type1). (0 times)
,I/BackgroundCompactionService( 1015): compact_memory command done
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{26e8e602 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/Finsky  ( 5530): [971] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5530): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5793): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5793): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5793): [GetString-S]
,I/ReactiveServiceManager( 5793): Supported : 1
,D/QSEECOMAPI: ( 1015): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1015): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1015): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1015): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1015): QSEECom_shutdown_app, app_id = 11
,E/terrier ( 1015): handleString: Failed to handle string(-4)
,E/terrier ( 1015): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5793): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5793): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5793): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5793): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5793): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5793): [ensureRegistration] - No Samsung account
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1015): stay LED for fully charged
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/dhcpcd  ( 6411): wlan0: sending IPv6 Router Solicitation
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 320
,E/SMD     (  287): DCD OFF
,D/ActivityManager( 1015): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5861): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5861): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5861): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5861): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 5861): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5861): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5861): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5861): entry::IDLE
,I/dhcpcd  ( 6411): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6411): wlan0: no IPv6 Routers available
,V/AlarmManager( 1015): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{1be8376 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 3
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,V/AlarmManager( 1015): waitForAlarm result :4
,V/AlarmManager( 1015): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1015): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1015): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/SSRM:n  ( 1015): SIOP:: AP = 300
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/PowerManagerService( 1015): [PWL] Off : 30s ago
,I/PowerManagerService( 1015): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1015): [PWL]     mWakeLockSummary : 0x1
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1838): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1838): Vacuum at: now=1450229649755 tag=VacuumService
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 49320(2MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 27MB/41MB, paused 2.511ms total 157.343ms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/PhenotypeConfigurator( 1838): Scheduling Phenotype for one-off execution 3605 seconds from now (1450229650351)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1838): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeFlagCommitter( 1838): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1838): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 1015): getLastLocation: Request[POWER_NONE passive fastest=0 num=1],
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1838): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1838): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1838): (HTTPLog)-Static: isShipBuild true
I/System.out( 1838): (HTTPLog)-Thread-269-50950590: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1838): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  275): uids 10012
D/EnterpriseController(  275): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  275): getNetworkForDns: using netid 503 for uid 10012
,I/System.out( 1838): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1838): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1838, getuid(): 10012
,I/qtaguid ( 1838): Tagging socket 87 with tag 1000120100000000{268440065,0} for uid -1, pid: 1838, getuid(): 10012
,D/LocationManagerService( 1015): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1838): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1838): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1838, getuid(): 10012
,D/LocationManagerService( 1015): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1838): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1838): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1838, getuid(): 10012
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
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/FactoryTest( 5361): Not factory mode
,D/FactoryTest( 5361): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5361): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5361): still no open session command from host, so toast
,W/ContextImpl( 5361): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 5361): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
I/Timeline( 5361): Timeline: Activity_launch_request id:com.android.settings time:114432
,E/PersonaManagerService( 1015): inState():  stateMachine is null !!
I/PersonaManagerService( 1015): PersonaId don't exist
,I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings,
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1015): mDVFSHelper.acquire()
,D/PersonaManager( 1015): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1015): Focused application set to: xxxx
,D/InputDispatcher( 1015): Focus left window: 6112
,E/MTPRx   ( 5361): started activity for popup
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 5361): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 5361): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5361): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5361): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5361): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5361): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5361): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1015): Focused application set to: xxxx
,D/InputDispatcher( 1015): Focus entered window: 6112
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1015): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1a49aa0c attribute=null, token = android.os.BinderProxy@9be92a3
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SettingsReceiverActivity( 5361): dev.kiessupport is : TRUE
,D/PhoneWindow( 5361): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5361): *FMB* installDecor flags : 8388610
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
,V/ActivityThread( 6112): updateVisibility : ActivityRecord{8b3234d token=android.os.BinderProxy@125677 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/Timeline( 6112): Timeline: Activity_idle id: android.os.BinderProxy@125677 time:114624
,D/PersonaManager( 1015): isKioskContainerExistOnDevice
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/ActivityManager( 1015): mDVFSHelper.release()
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  ( 1015): SIOP:: AP = 300
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
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
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
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
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
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
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,I/PowerManagerService( 1015): [PWL] Off : 50s ago
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 1015): !@Sync 4
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,E/SMD     (  287): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,I/PowerManagerService( 1015): [PWL] Off : 75s ago
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 270
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,V/AlarmManager( 1015): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1015): !@Sync 5
,I/ClearcutLoggerApiImpl( 1838): disconnect managed GoogleApiClient
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1015): [PWL] Off : 105s ago
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1015): !@Sync 6
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,E/SMD     (  287): DCD OFF
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 140s ago
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/Watchdog( 1015): !@Sync 7
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1015): !@Sync 8
,I/PowerManagerService( 1015): [PWL] Off : 180s ago
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1015): !@Sync 9
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 225s ago
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1015): initializing...,
I/TLC_TIMA_PKM_initialize( 1015): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1015): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1015): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1015): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1015): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1015): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1015): max_message_size = 524416 = 0x80080,
D/QSEECOMAPI: ( 1015): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1015): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1015): Loaded image: APP id = 12
,I/TZ: qc_tlc_communication( 1015): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded,
,I/TLC_TIMA_PKM_initialize( 1015): Trustlet response is completed
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1015): !@Sync 10
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/jxcore-log( 6112): Connected to the server!
I/jxcore-log( 6112): 
,I/chromium( 6112): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1015): !@Sync 11
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2
,I/PowerManagerService( 1015): [PWL] Off : 275s ago
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 12
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8
,V/AlarmManager( 1015): No more alarm at this time.nowELAPSED=403226 batch.start=797913
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 13
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/PowerManagerService( 1015): [PWL] Off : 330s ago
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 14
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,V/AlarmManager( 1015): waitForAlarm result :8
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 15
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,I/PowerManagerService( 1015): [PWL] Off : 390s ago,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/bootchecker(  311): bootchecker wake up!!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 16
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 17
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,I/PowerManagerService( 1015): [PWL] Off : 455s ago,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 18,
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/Atfwd_Daemon(  314): Stop the daemon....
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 19
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged,
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 525s ago
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 20,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 21
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 22
,I/PowerManagerService( 1015): [PWL] Off : 600s ago
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 23,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 24
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 680s ago
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 25,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 2000): Aggregate from 1450228123768 (log), 1450228123768 (data)
,E/Watchdog( 1015): !@Sync 26
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6918): MountEmulatedStorage()
E/Zygote  ( 6918): v2
I/libpersona( 6918): KNOX_SDCARD checking this for 1000
I/libpersona( 6918): KNOX_SDCARD not a persona
,I/SELinux ( 6918): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=6918 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 6918): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6918): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6918): TimaSignature is unavailable
,D/ActivityThread( 6918): Added TimaKeyStore provider
,W/ResourcesManager( 6918): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager( 1015): Killing 6018:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10053/pid_6018/cgroup.procs: No such file or directory
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged,
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 1015): waitForAlarm result :8,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 27
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 1015): [PWL] Off : 765s ago
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 28
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 29
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,E/SMD     (  287): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1015): !@Sync 30
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,I/PowerManagerService( 1015): [PWL] Off : 855s ago
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 31
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 32
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 1015): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 33
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 950s ago,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 34,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 35
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 36
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 37,
,I/PowerManagerService( 1015): [PWL] Off : 1050s ago,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 38,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 39
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1015): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1015): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1015): Updating Usage Statistics in DB @ 1450230752606
,I/ApplicationPolicy( 1015): updateDataUsageMap,
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1015): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1015): ::isTableExists: Table exists 
,I/ApplicationUsage( 1015): Done Updating Usage Statistics in DB @ 1450230752969
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 40
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,I/PowerManagerService( 1015): [PWL] Off : 1155s ago
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 41
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged,
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 42
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 43,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 44,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 1266s ago
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 45
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 46,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 47
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 48
,I/PowerManagerService( 1015): [PWL] Off : 1381s ago
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 49
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 50
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1015): !@Sync 51
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1015): !@Sync 52
,I/PowerManagerService( 1015): [PWL] Off : 1501s ago
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1015): stay LED for fully charged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1015): !@Sync 53
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1015): !@Sync 54
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 55
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1015): Plugged
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 56
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/PowerManagerService( 1015): [PWL] Off : 1626s ago
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 57
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 58
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 59
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 60
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/PowerManagerService( 1015): [PWL] Off : 1756s ago
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 61,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1015): !@Sync 62
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
I/ActivityManager( 1015): Killing 6089:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 5881:com.google.android.apps.docs/u0a91 (adj 15): empty #32
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ActivityManager( 1015): Killing 5929:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #33
,I/ActivityManager( 1015): Killing 5397:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #34
,I/ActivityManager( 1015): Killing 4254:com.sec.android.pagebuddynotisvc/u0a116 (adj 15): SPC_empty #35
,I/ActivityManager( 1015): Killing 2666:com.sec.phone/1001 (adj 15): SPC_empty #36
,I/ActivityManager( 1015): Killing 3965:com.sec.bcservice/1000 (adj 15): SPC_empty #37
,I/ProcessStatsService( 1015): Prepared write state in 9ms
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): performPollLocked(flags=0x3)
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,V/NetworkStats( 1015): performPollLocked() took 7ms
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,I/BatteryStatsDumper( 1015): In refreshStats isReason Screen ON/OFF: false
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
,W/ContextImpl( 6918): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.sm.base.a.a:307 com.samsung.android.sm.contextagent.ContextAgentReceiver.onReceive:124 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1015): ProcessRecord{2b8dff17 2666:com.sec.phone/1001} is already killed
E/lowmemorykiller(  254): Error opening /proc/2666/oom_score_adj; errno=2
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1015): Exception when unbinding service com.sec.phone/.SecPhoneService
W/ActivityManager( 1015): android.os.DeadObjectException
W/ActivityManager( 1015): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager( 1015): 	at android.os.BinderProxy.transact(Binder.java:511)
W/ActivityManager( 1015): 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:1029)
W/ActivityManager( 1015): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1997)
W/ActivityManager( 1015): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2381)
W/ActivityManager( 1015): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:18687)
W/ActivityManager( 1015): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:6654)
W/ActivityManager( 1015): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:6867)
W/ActivityManager( 1015): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1629)
W/ActivityManager( 1015): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:566)
,W/ActivityManager( 1015): ProcessRecord{2b8dff17 2666:com.sec.phone/1001} is already killed
,W/ActivityManager( 1015): Scheduling restart of crashed service com.sec.bcservice/.BroadcastService in 1000ms
,I/BatteryStatsDumper( 1015): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1015): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1015): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1015): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1015): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1015): Previous Battery Level: 100 Current Level: 100 Delta: 0
,W/ActivityManager( 1015): Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10993ms
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.analytics.CoreAnalyticsIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1838): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1838): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
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
,I/BatteryStatsDumper( 1015): Writing to database completed
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ProcessStatsService( 1015): Pruning old procstats: /data/system/procstats/state-2015-12-15-15-43-28.bin
,W/libprocessgroup( 1015): failed to open /acct/uid_10057/pid_5397/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10038/pid_5929/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10091/pid_5881/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3965/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_1001/pid_2666/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10100/pid_6089/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10116/pid_4254/cgroup.procs: No such file or directory
,E/SMD     (  287): DCD OFF
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7378): MountEmulatedStorage(),
E/Zygote  ( 7378): v2
I/libpersona( 7378): KNOX_SDCARD checking this for 1000
I/libpersona( 7378): KNOX_SDCARD not a persona
,I/SELinux ( 7378): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1015): Start proc com.sec.bcservice for service com.sec.bcservice/.BroadcastService: pid=7378 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 7378): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 7378): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7378): TimaSignature is unavailable
,D/ActivityThread( 7378): Added TimaKeyStore provider
,W/ResourcesManager( 7378): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/F_PHONE ( 7378): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 7378): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,D/ActivityManager( 1015): bindService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.phone, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7393): MountEmulatedStorage(),
E/Zygote  ( 7393): v2
I/libpersona( 7393): KNOX_SDCARD checking this for 1001
,I/SELinux ( 7393): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 7393): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.sec.phone for service com.sec.phone/.SecPhoneService: pid=7393 uid=1001 gids={41001, 9997, 1007, 1028, 1015, 3002, 3001, 3003, 1035, 1023, 3006} abi=armeabi-v7a
,I/SELinux ( 7393): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 7393): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7393): TimaSignature is unavailable
,D/ActivityThread( 7393): Added TimaKeyStore provider
,W/ResourcesManager( 7393): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/F_PHONE ( 7378): [[com.sec.bcservice]] onServiceConnected()
,I/F_PHONE ( 7378): default registerAction()
I/F_PHONE ( 7378): [[com.sec.bcservice]] sendPendingMessage()
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ActivityManager( 1015): Killing 5693:com.google.android.gms:car/u0a12 (adj 15): empty for 1800s
,I/ActivityManager( 1015): Killing 6130:com.samsung.helphub/1000 (adj 15): empty for 1801s
,W/libprocessgroup( 1015): failed to open /acct/uid_10012/pid_5693/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_6130/cgroup.procs: No such file or directory
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7414): MountEmulatedStorage()
,E/Zygote  ( 7414): v2
I/libpersona( 7414): KNOX_SDCARD checking this for 10116
I/libpersona( 7414): KNOX_SDCARD not a persona
,I/SELinux ( 7414): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.sec.android.pagebuddynotisvc for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc: pid=7414 uid=10116 gids={50116, 9997} abi=armeabi-v7a,
I/SELinux ( 7414): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 7414): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7414): TimaSignature is unavailable
,D/ActivityThread( 7414): Added TimaKeyStore provider
,I/ActivityManager( 1015): Killing 5974:com.sec.android.provider.badge/u0a72 (adj 15): empty for 1801s
,I/PageBuddyNotiSvc( 7414): onCreate mCpBitFlag=0
,W/libprocessgroup( 1015): failed to open /acct/uid_10072/pid_5974/cgroup.procs: No such file or directory
,V/AlarmManager( 1015): waitForAlarm result :4
,I/ActivityManager( 1015): Killing 5826:com.policydm/1000 (adj 15): empty for 1800s
,I/ActivityManager( 1015): Killing 6513:com.samsung.android.sconnect/u0a125 (adj 15): empty for 1800s
,I/ActivityManager( 1015): Killing 6170:com.google.android.apps.plus/u0a120 (adj 15): empty for 1800s
I/ActivityManager( 1015): Killing 6370:com.sec.android.soagent/u0a34 (adj 15): empty for 1800s
I/ActivityManager( 1015): Killing 6353:com.google.android.apps.magazines/u0a113 (adj 15): empty for 1800s
,I/ActivityManager( 1015): Killing 6325:com.android.chrome/u0a81 (adj 15): empty for 1800s
I/ActivityManager( 1015): Killing 6484:com.sec.android.diagmonagent/1000 (adj 15): empty for 1800s
I/ActivityManager( 1015): Killing 6421:com.samsung.android.service.travel/u0a159 (adj 15): empty for 1800s
I/ActivityManager( 1015): Killing 6459:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1800s
I/ActivityManager( 1015): Killing 6395:com.samsung.android.securitylogagent/1000 (adj 15): empty for 1800s
I/ActivityManager( 1015): Killing 6303:com.android.email/u0a145 (adj 15): empty for 1800s
,I/ActivityManager( 1015): Killing 5793:com.sec.pcw.device/1000 (adj 15): empty for 1800s
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5826/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_6395/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10113/pid_6353/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_6484/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10002/pid_6459/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10125/pid_6513/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10159/pid_6421/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10120/pid_6170/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5793/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10081/pid_6325/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10034/pid_6370/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10145/pid_6303/cgroup.procs: No such file or directory
,E/SMD     (  287): DCD OFF,
,TIME-OUT KILL (timeout was 1800000ms),D/SSRM:n  ( 1015): SIOP:: AP = 260
D/AndroidRuntime( 7433): 
D/AndroidRuntime( 7433): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7433): CheckJNI is OFF
D/AndroidRuntime( 7433): readGMSProperty: start
D/AndroidRuntime( 7433): readGMSProperty: already setted!!
D/AndroidRuntime( 7433): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 7433): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 7433): readGMSProperty: end
D/AndroidRuntime( 7433): addProductProperty: start
E/AffinityControl( 7433): AffinityControl: registerfunction enter
D/AndroidRuntime( 7433): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1015): START PACKAGE DELETE: observer{842941132}
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
D/ApplicationPolicy( 1015): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1015): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1015): !@killApplicatoin: 10175, uninstall pkg
I/ActivityManager( 1015): Force stopping com.test.thalitest appid=10175 user=-1: uninstall pkg
I/ActivityManager( 1015): Killing 6112:com.test.thalitest/u0a175 (adj 0): stop com.test.thalitest cause uninstall pkg
W/PackageSettings( 1015): Skipping PackageSetting{15d085a9 com.example.hello/10177} due to missing metadata
I/ActivityManager( 1015):   Force finishing activity ActivityRecord{23ac294b u0 com.test.thalitest/.MainActivity t3}
W/ActivityManager( 1015): mDVFSHelper.acquire()
I/WindowState( 1015): WIN DEATH: Window{3e449a0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  257): id=14 Removed NainActivit (6/8)
I/SurfaceFlinger(  257): id=14 Removed NainActivit (-2/8)
D/InputDispatcher( 1015): Focus left window: 6112
I/SurfaceFlinger(  257): id=14 Removed NainActivit (-2/8)
D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
I/ActivityManager( 1015): Force stopping com.test.thalitest appid=10175 user=0: pkg removed
I/ActivityManager( 1015):   Force finishing activity ActivityRecord{23ac294b u0 com.test.thalitest/.MainActivity t3 f}
W/ActivityManager( 1015): Duplicate finish request for ActivityRecord{23ac294b u0 com.test.thalitest/.MainActivity t3 f}
W/ActivityManager( 1015): CustomStartingWindow se packge removed so remove capture also
I/DBG_DM  ( 3136): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
D/InputDispatcher( 1015): Focused application released
I/DBG_DM  ( 3136): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 8
I/DBG_DM  ( 3136): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
I/art     ( 5622): Explicit concurrent mark sweep GC freed 2390(140KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 767us total 37.626ms
I/DBG_DM  ( 3136): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
I/DBG_DM  ( 3136): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 8
E/SamsungIME( 1800): mOCRHelper is null
W/GeofencerStateMachine( 1838): Ignoring removeGeofence because network location is disabled.
I/DBG_DM  ( 3136): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
I/DBG_DM  ( 3136): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
I/DBG_DM  ( 3136): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
I/art     ( 2000): Explicit concurrent mark sweep GC freed 10546(612KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 14MB/18MB, paused 1.243ms total 84.791ms
D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
D/RegisteredComponentCache( 1441): Collect Tech packages for Knox
D/PersonaManager( 1441): isKioskContainerExistOnDevice
I/DBG_DM  ( 3136): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
I/KLMS-2.5.183: ( 3660): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 16 03:03:51 GMT+01:00 2015
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
W/SQLiteConnectionPool( 2000): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/KLMS-2.5.183: ( 3660): KLMSAbstractReciever(): onReceive().END.
D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
I/splitIntent( 1015): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
I/splitIntent( 1015): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 3136): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 8
I/ActivityManager( 1015): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7446 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
I/DBG_DM  ( 3136): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
E/Zygote  ( 7446): MountEmulatedStorage()
E/Zygote  ( 7446): v2
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/libpersona( 7446): KNOX_SDCARD checking this for 10094
I/libpersona( 7446): KNOX_SDCARD not a persona
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/SELinux ( 7446): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/DBG_DM  ( 3136): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
I/DBG_DM  ( 3136): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
I/SELinux ( 7446): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/DBG_DM  ( 3136): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
I/DBG_DM  ( 3136): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
E/SELinux ( 7446): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.183: ( 3660): KLMSIntentService(): onCreate()
I/KLMS-2.5.183: ( 3660): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.5.183: ( 3660): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/art     (  304): Explicit concurrent mark sweep GC freed 8747(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 701us total 35.616ms
I/KLMS-2.5.183: ( 3660): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
D/TimaKeyStoreProvider( 7446): TimaSignature is unavailable
I/KLMS-2.5.183: ( 3660): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.183: ( 3660): KLMSIntentService(): listeningToPackageRemoved().START
D/ActivityThread( 7446): Added TimaKeyStore provider
I/KLMS-2.5.183: ( 3660): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 610us total 17.173ms
D/EnterpriseDeviceManagerService( 1015): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1015): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1015): no available spell checker services found
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 16.727ms
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/RCPManagerService( 1015): PackageReceiver onReceive()
I/HarmonyEASService( 1015): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1015): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1015): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1015): OtpDbHelper::getInstance New instance created
E/Zygote  ( 7461): MountEmulatedStorage()
I/libpersona( 7461): KNOX_SDCARD checking this for 10044
E/Zygote  ( 7461): v2
I/libpersona( 7461): KNOX_SDCARD not a persona
D/OTPFW   ( 1015): DBIntegrity::getInstance - New instance created
I/SELinux ( 7461): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7461 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux ( 7461): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7461): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/OTPFW   ( 1015): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10175 container id = 0
I/OTPFW   ( 1015): ProvisionData::getAllEntries Enter
E/OTPFW   ( 1015): ProvisionData::getAllEntries Table is empty
D/BackupManagerService( 1015): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1015): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1015): uID is 10175
V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
E/Zygote  ( 7474): MountEmulatedStorage()
I/libpersona( 7474): KNOX_SDCARD checking this for 10149
E/Zygote  ( 7474): v2
I/libpersona( 7474): KNOX_SDCARD not a persona
I/SELinux ( 7474): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7474 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/AlarmManagerEXT( 1015): com.test.thalitest(10175) is removed.
V/EnterpriseBillingPolicy( 1015): uID is 10175
D/SSRM:aZ ( 1015): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
I/DBG_DM  ( 3136): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
I/SELinux ( 7474): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
E/SELinux ( 7474): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7461): TimaSignature is unavailable
D/PersonaManager( 1441): isKioskContainerExistOnDevice
D/ActivityThread( 7461): Added TimaKeyStore provider
W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/RegisteredServicesCache( 1441): empty dynamic service
I/SurfaceFlinger(  257): id=16 createSurf (720x1280),1 flag=404, YUIInstallC
D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/KLMS-2.5.183: ( 3660): KLMSIntentService(): listeningToPackageRemoved().END
D/InputDispatcher( 1015): Focus entered window: 3136
D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 3136): log_dcs ThreadedRenderer::initialize entered! 
V/ActivityThread( 3136): updateVisibility : ActivityRecord{2d47d978 token=android.os.BinderProxy@94fd12f {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/TaskPersister( 1015): removeObsoleteFile: deleting file=3_task.xml
D/TaskPersister( 1015): removeObsoleteFile: deleting file=2_task.xml
D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService( 1015): Got RemoteException sending setActive(false) notification to pid 6112 uid 10175
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
E/SMD     (  287): DCD OFF
D/TimaKeyStoreProvider( 7474): TimaSignature is unavailable
I/KLMS-2.5.183: ( 3660): KLMSIntentService(): onDestroy()
D/ActivityThread( 7474): Added TimaKeyStore provider
D/elm:15183( 7446): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15183( 7446): ELMEngine.ELMEngine( context ).
D/elm:15183( 7446): MDMBridge.setEnterpriseBridge()
W/ResourcesManager( 7461): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/SamsungIME( 1800): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
D/ActivityManager( 1015): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
I/Timeline( 3136): Timeline: Activity_idle id: android.os.BinderProxy@94fd12f time:1895353
D/elm:15183( 7446): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
W/ResourcesManager( 7461): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7461): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7461): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7461): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7461): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7461): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7461): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/elm:15183( 7446): ElmAgentService : onCreate()
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/elm:15183( 7446): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 7446): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 7446): MDMBridge.getInstance()
D/elm:15183( 7446): MDMBridge.getAllLicenseInfoFromSDK()
E/SQLiteLog( 6918): (10) POSIX Error : 11 SQLite Error : 3850
D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
E/SQLiteLog( 6918): (284) automatic index on crash_info_summary(package_name_touched)
D/elm:15183( 7446): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 7496): MountEmulatedStorage()
E/Zygote  ( 7496): v2
I/ActivityManager( 1015): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=7496 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/libpersona( 7496): KNOX_SDCARD checking this for 1000
I/libpersona( 7496): KNOX_SDCARD not a persona
I/SELinux ( 7496): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/elm:15183( 7446): ElmAgentService : onDestroy().
D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
I/SELinux ( 7496): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7496): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.samsung.android.sm, calleePkgName: com.sec.android.provider.badge
D/PersonaManager( 1177): isKioskContainerExistOnDevice
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
I/art     ( 6918): Explicit concurrent mark sweep GC freed 844(62KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 798us total 98.849ms
E/Zygote  ( 7506): MountEmulatedStorage()
I/libpersona( 7506): KNOX_SDCARD checking this for 10072
E/Zygote  ( 7506): v2
I/libpersona( 7506): KNOX_SDCARD not a persona
I/SELinux ( 7506): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 7506): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7506): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7506 uid=10072 gids={50072, 9997} abi=armeabi-v7a
I/Timeline( 1015): Timeline: Activity_windows_visible id: ActivityRecord{b8f88d9 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t2} time:1895420
W/ActivityManager( 1015): mDVFSHelper.release()
D/TimaKeyStoreProvider( 7506): TimaSignature is unavailable
D/TimaKeyStoreProvider( 7496): TimaSignature is unavailable
D/ActivityThread( 7506): Added TimaKeyStore provider
D/ActivityThread( 7496): Added TimaKeyStore provider
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
W/ResourceType( 1015): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Zygote  ( 7529): MountEmulatedStorage()
I/libpersona( 7529): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7529): v2
I/libpersona( 7529): KNOX_SDCARD not a persona
I/SELinux ( 7529): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 7529): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7529): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7529 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 6295:com.sec.android.fotaclient/u0a9 (adj 15): empty for 1804s
D/BadgeProvider( 7506): onCreate
I/ActivityManager( 1015): Killing 6048:com.osp.app.signin/u0a41 (adj 15): empty for 1804s
D/BadgeProvider( 7506): DatabaseHelper
W/ResourcesManager( 1015): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ThemeInfoUtil( 7474): getCurrentFestivalName is [null]
D/TimaKeyStoreProvider( 7529): TimaSignature is unavailable
D/ThemeInfoUtil( 7474): isCurrentFestival = false
D/ActivityThread( 7529): Added TimaKeyStore provider
D/AASAservice-UpdateReceiver( 7496): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
W/System.err( 7496): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 7496): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
W/System.err( 7496): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 7496): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 7496): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 7496): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 7496): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7496): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7496): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 7496): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7496): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7496): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7496): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7545): MountEmulatedStorage()
I/libpersona( 7545): KNOX_SDCARD checking this for 10152
E/Zygote  ( 7545): v2
I/libpersona( 7545): KNOX_SDCARD not a persona
I/SELinux ( 7545): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 7545): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/BadgeProvider( 7506): sendNotify entered. [uri] : content://com.sec.badge/apps
I/ActivityManager( 1015): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7545 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
D/BadgeProvider( 7506): sendNotify, [notify] : null
I/ActivityManager( 1015): Killing 6237:com.google.android.talk/u0a104 (adj 15): empty for 1804s
D/BadgeProvider( 7506): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 7506): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7506): update, [UpdateCount] : 1
E/SELinux ( 7545): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 5668:com.android.defcontainer/u0a4 (adj 15): empty for 1803s
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 7545): TimaSignature is unavailable
D/ActivityThread( 7545): Added TimaKeyStore provider
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager( 1015): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7560 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 7560): MountEmulatedStorage()
E/Zygote  ( 7560): v2
I/libpersona( 7560): KNOX_SDCARD checking this for 1000
I/libpersona( 7560): KNOX_SDCARD not a persona
I/SELinux ( 7560): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 7560): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7560): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/PersonaManager( 1015): isKioskContainerExistOnDevice
D/TimaKeyStoreProvider( 7560): TimaSignature is unavailable
D/ActivityThread( 7560): Added TimaKeyStore provider
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PCWCLIENTTRACE_LOG( 7560): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 7560): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7560): new DMDBOpenHelper instance
W/ContextImpl( 7529): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
E/SQLiteLog( 7545): (284) automatic index on shooting_modes(title_id)
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Zygote  ( 7577): MountEmulatedStorage()
E/Zygote  ( 7577): v2
I/libpersona( 7577): KNOX_SDCARD checking this for 1000
I/libpersona( 7577): KNOX_SDCARD not a persona
I/SELinux ( 7577): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 7577): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7577): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7577 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
D/UsbSettingsManager( 1015): clearDefaults: com.test.thalitest
D/NearbySource( 7461): Nearby Source Create!
D/NearbyContext( 7461): Nearby Context Create!

```
