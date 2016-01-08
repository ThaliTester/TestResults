#### Test 549702610b97681_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
D/TP/MmsSmsProvider( 1457): query,matched:13, calling pid = 5718
D/TP/MmsSmsProvider( 1457): match 13:Elapsed time : 2.252 ms
I/DBG_POLICYDM( 5810): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
I/DBG_POLICYDM( 5810): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
D/Mms/Contact( 5718): [end]    init consume time = 33.769844
I/DBG_POLICYDM( 5810): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
I/DBG_POLICYDM( 5810): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
I/DBG_POLICYDM( 5810): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
I/DBG_POLICYDM( 5810): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
I/DBG_POLICYDM( 5810): [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
D/Mms/DraftCache( 5718): [start]    rebuildCache consume time = 8.451458
D/TP/MmsSmsProvider( 1457): query,matched:12, calling pid = 5718
D/TP/MmsSmsProvider( 1457): match 12:Elapsed time : 2.401 ms
--------- beginning of system
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
D/Mms/MethodReflector( 5718): getSubId is called
D/Mms/TelephonyUtils( 5718): getLongSubId from simSlot 0, return Value = -1
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/Mms/MethodReflector( 5718): getTelephonyProperty is called
D/Mms/DownloadManager( 5718): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5718): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5718): auto download without roaming -> true
D/Mms/DownloadManager( 5718): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 5718): getSubId is called
E/Zygote  ( 5867): MountEmulatedStorage()
E/Zygote  ( 5867): v2
I/SELinux ( 5867): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 5867): KNOX_SDCARD checking this for 10035
I/libpersona( 5867): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=5867 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5867): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5867): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/Mms/MethodReflector( 5718): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5718): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5718): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5718): getTelephonyProperty is called
D/Mms/DownloadManager( 5718): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5718): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5718): auto download without roaming -> true
D/Mms/DownloadManager( 5718): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DraftCache( 5718): [end]    rebuildCache consume time = 35.822083
D/Mms/DownloadManager( 5718): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5718): mAutoDownload ------> true
D/TimaKeyStoreProvider( 5867): TimaSignature is unavailable
D/ActivityThread( 5867): Added TimaKeyStore provider
I/DBG_POLICYDM( 5810): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
I/DBG_POLICYDM( 5810): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
D/ComposerPerformance( 5718): 1452294289143 ms / [DONE] Composer constructor
I/DBG_POLICYDM( 5810): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
E/CII     ( 5718): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 5718): ReservationManager()
I/Mms/ReservationManager( 5718): resetAfterConnected()
I/DBG_POLICYDM( 5810): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
D/TP/MmsSmsProvider( 1457): query,matched:7, calling pid = 5718
I/DBG_POLICYDM( 5810): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
D/TP/MmsSmsProvider( 1457): match 7:Elapsed time : 4.254 ms
I/Mms/ReservationManager( 5718): getReservedSendMessageCount(): retMessageCount=0
D/Mms/MmsApp( 5718): [end]    onCreate() consume time = 79.880313
D/Mms/Conversation( 5718): [start]    init() consume time = 1.748489
D/TP/MmsSmsProvider( 1457): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1457): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1457): updateThread(), thread_id = 9223372036854775807
V/TP/MmsSmsDatabaseHelper( 1457): sUpgradeVersion = 0, db.getVersion() = 81
D/Mms/DownloadManager( 5718): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 5718): roaming ------> false, mSimSlot = 0
D/Mms/MethodReflector( 5718): getSubId is called
D/Mms/TelephonyUtils( 5718): getLongSubId from simSlot 0, return Value = -1
E/SPPClientService( 5867): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5867): [PushClientApplication] Push log off : This is Ship build version
D/TP/MmsSmsProvider( 1457): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1457): need read changed broadcast:false
D/SPPClientService( 5867): PushLog.txt file is not deleted.
D/SPPClientService( 5867): PushLog.txt file is not deleted.
D/SPPClientService( 5867): ============PushLog. stop!
I/DBG_POLICYDM( 5810): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
D/Mms/Conversation( 5718): [end]    init consume time = 18.434375
D/Mms/MethodReflector( 5718): getTelephonyProperty is called
D/Mms/DownloadManager( 5718): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5718): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5718): auto download without roaming -> true
D/Mms/DownloadManager( 5718): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5718): mAutoDownload ------> true
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/Mms/MessagingNotification( 5718): [start]    init() consume time = 2.995677
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/PhotosPlugin( 5826): Loading PhotosPlugin
D/Mms/FreeMessageStatusReceiver( 5718): onReceive, action : android.intent.action.PACKAGE_ADDED
I/DBG_POLICYDM( 5810): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
E/Zygote  ( 5887): MountEmulatedStorage()
E/Zygote  ( 5887): v2
I/libpersona( 5887): KNOX_SDCARD checking this for 10038
I/libpersona( 5887): KNOX_SDCARD not a persona
I/SELinux ( 5887): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5887 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 5887): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5887): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/Mms/MessagingNotification( 5718): [end]    init consume time = 28.202709
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 5810): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
I/DBG_POLICYDM( 5810): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
I/DBG_POLICYDM( 5810): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
I/DBG_POLICYDM( 5810): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
I/DBG_POLICYDM( 5810): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
D/Mms/SpamFilter( 5718): [start]    SpamFilter fill() begin consume time = 19.378021
I/DBG_POLICYDM( 5810): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/DBG_POLICYDM( 5810): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
E/Zygote  ( 5903): MountEmulatedStorage()
E/Zygote  ( 5903): v2
I/libpersona( 5903): KNOX_SDCARD checking this for 10047
I/libpersona( 5903): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5903 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
I/SELinux ( 5903): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5903): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/DBG_POLICYDM( 5810): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/01/11/11:32:45
E/SELinux ( 5903): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 5810): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/01/09/00:04:49
D/TP/MmsSmsProvider( 1457): query,matched:400, calling pid = 5718
I/DBG_POLICYDM( 5810): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
D/TP/MmsSmsProvider( 1457): query,matched:0, calling pid = 5718
V/TP/MmsSmsProvider( 1457): getSimpleConversations entered.
I/DBG_POLICYDM( 5810): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
D/TP/MmsSmsProvider( 1457): match 0:Elapsed time : 1.244 ms
I/DBG_POLICYDM( 5810): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
D/TimaKeyStoreProvider( 5887): TimaSignature is unavailable
I/DBG_POLICYDM( 5810): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
D/ActivityThread( 5887): Added TimaKeyStore provider
I/DBG_POLICYDM( 5810): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
I/DBG_POLICYDM( 5810): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
D/Mms/SpamFilter( 5718): [end]    SpamFilter fill() finished consume time = 27.491927
I/DBG_POLICYDM( 5810): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
I/DBG_POLICYDM( 5810): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
D/Mms/Synchronizer( 5718): [start]    doSync consume time = 5.594427
D/Mms/FreeMessageReceiverService( 5718): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5718): onHandleIntent: ACTION_PACKAGE_ADDED
D/TP/MmsSmsProvider( 1457): update, matched:300, calling pid = 5718
V/TP/MmsSmsProvider( 1457): syncDBData start
V/TP/MmsSmsProvider( 1457): syncDBData sms end
V/TP/MmsSmsProvider( 1457): syncDBData mms end
V/TP/MmsSmsProvider( 1457): syncDBData end
D/Mms/Synchronizer( 5718): [end]    doSync consume time = 7.193073
I/ActivityManager( 1014): Killing 5223:com.google.android.talk/u0a104 (adj 15): empty #31
W/ResourcesManager( 5887): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5887): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 5903): TimaSignature is unavailable
D/ActivityThread( 5903): Added TimaKeyStore provider
D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 5810): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
W/ResourcesManager( 5903): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5903): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5903): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/Mms/ArtClassLoader( 5718): init [DONE] art
I/ActivityManager( 1014): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5920 uid=10072 gids={50072, 9997} abi=armeabi-v7a
E/Zygote  ( 5920): MountEmulatedStorage()
I/libpersona( 5920): KNOX_SDCARD checking this for 10072
E/Zygote  ( 5920): v2
I/libpersona( 5920): KNOX_SDCARD not a persona
I/SELinux ( 5920): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5920): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5920): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 5810): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
D/TimaKeyStoreProvider( 5920): TimaSignature is unavailable
D/ActivityThread( 5920): Added TimaKeyStore provider
I/ActivityManager( 1014): Killing 5346:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
D/BadgeProvider( 5920): onCreate
D/BadgeProvider( 5920): DatabaseHelper
I/wpa_supplicant( 2079): nl80211: Received scan results (6 BSSes)
D/WifiP2pService( 1014): InactiveState{ what=147461 }
D/WifiP2pService( 1014): P2pEnabledState{ what=147461 }
D/WifiP2pService( 1014): DefaultState{ what=147461 }
D/Mms/MessagingNotification( 5718): checkBadgeCount unreadCount=0 badgeCount=0
D/TP/SmsProvider( 1457): query,matched:26, calling pid = 5718
D/TP/SmsProvider( 1457): match 26:Elapsed time : 1.105 ms
D/TP/MmsSmsProvider( 1457): query,matched:6, calling pid = 5718
D/TP/MmsSmsProvider( 1457): match 6:Elapsed time : 1.598 ms
W/libprocessgroup( 1014): failed to open /acct/uid_10104/pid_5223/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10057/pid_5346/cgroup.procs: No such file or directory
D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5935): MountEmulatedStorage()
E/Zygote  ( 5935): v2
I/libpersona( 5935): KNOX_SDCARD checking this for 10025
I/libpersona( 5935): KNOX_SDCARD not a persona
I/SELinux ( 5935): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/MyFiles ( 5903): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
I/SELinux ( 5935): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5935 uid=10025 gids={50025, 9997} abi=armeabi-v7a
E/SELinux ( 5935): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
I/TactileAssist( 1014): enable value -1
I/TactileAssist( 1014): internal enable value -1
E/installd(  283): system dir 0 : /system/app/
E/installd(  283): system dir 1 : /system/priv-app/
E/installd(  283): system dir 2 : /vendor/app/
E/installd(  283): system dir 3 : /oem/app/
I/TactileAssist( 1014): intensity value -1
I/TactileAssist( 1014): saveAppList value true
I/TactileAssist( 1014): List of disabled apps :
D/TimaKeyStoreProvider( 5935): TimaSignature is unavailable
D/ActivityThread( 5935): Added TimaKeyStore provider
I/DBG_POLICYDM( 5810): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
I/ActivityManager( 1014): Killing 5407:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 5935): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/PackageManager( 1014): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
E/Zygote  ( 5951): MountEmulatedStorage()
E/Zygote  ( 5951): v2
I/libpersona( 5951): KNOX_SDCARD checking this for 10053
I/libpersona( 5951): KNOX_SDCARD not a persona
I/SELinux ( 5951): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5951 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SELinux ( 5951): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5951): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 5951): TimaSignature is unavailable
D/ActivityThread( 5951): Added TimaKeyStore provider
I/OMACP   ( 5935): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
D/ChimeraCfgMgr( 2004): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2004): Module APK com.google.android.play.games already loaded
W/ResourcesManager( 5951): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/Mms/Omacp( 5718): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
E/SMD     (  287): DCD OFF
I/OMACP   ( 5935): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 5935): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
W/libprocessgroup( 1014): failed to open /acct/uid_10069/pid_5407/cgroup.procs: No such file or directory
I/OMACP   ( 5935): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 5935): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 5935): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 5935): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 5935): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 5935): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 5935): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 5935): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 5935): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
D/Compatibility( 5951): onReceive() it will make start service
I/OMACP   ( 5935): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 5935): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5951): onHandleIntent()
D/Compatibility( 5951): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10175, android.intent.extra.user_handle=0}]
D/Compatibility( 5951): found: 2
E/Zygote  ( 5972): MountEmulatedStorage()
I/libpersona( 5972): KNOX_SDCARD checking this for 10057
E/Zygote  ( 5972): v2
I/libpersona( 5972): KNOX_SDCARD not a persona
I/SELinux ( 5972): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5972 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
I/SELinux ( 5972): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5972): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/Compatibility( 5951): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5951): skipping ResolveInfo{183595aa com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5951): considering ResolveInfo{de6b59b com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5951): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5951): enabling receiver ResolveInfo{772bd38 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5951): enabling receiver ResolveInfo{32d1d111 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5951): enabling receiver ResolveInfo{152f6276 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/ChimeraCfgMgr( 2004): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/Compatibility( 5951): enabling receiver ResolveInfo{12711077 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Compatibility( 5951): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
I/ServiceManager(  314): Waiting for service AtCmdFwd...
D/TimaKeyStoreProvider( 5972): TimaSignature is unavailable
D/ActivityThread( 5972): Added TimaKeyStore provider
D/AsyncTaskServiceImpl( 2004): Submit a task: k
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1014): Killing 5438:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 2004): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 2004): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/k       ( 2004): Processing package: com.test.thalitest
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/GassUtils( 2004): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
D/k       ( 2004): Found info for package com.test.thalitest in db.
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5438/cgroup.procs: No such file or directory
W/BaseAppContext( 2004): Using Auth Proxy for data requests.
W/BaseAppContext( 2004): Using Auth Proxy for data requests.
I/UpdateIcingCorporaServi( 5972): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/BaseAppContext( 2004): Using Auth Proxy for data requests.
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/art     ( 1788): Explicit concurrent mark sweep GC freed 34347(2MB) AllocSpace objects, 14(224KB) LOS objects, 40% free, 12MB/21MB, paused 1.264ms total 66.758ms
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 5810): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,I/DBG_POLICYDM( 5810): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
I/DBG_POLICYDM( 5810): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
W/BaseAppContext( 2004): Using Auth Proxy for data requests.
I/SL_DEBUG( 5887): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5887): isLoggable:: SL_DEBUG_EXIST = false
I/DBG_POLICYDM( 5810): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
W/BaseAppContext( 2004): Using Auth Proxy for data requests.
W/BaseAppContext( 2004): Using Auth Proxy for data requests.
I/PeopleDatabaseHelper( 2004): cleanUpNonGplusAccounts done.
W/BaseAppContext( 2004): Using Auth Proxy for data requests.
I/art     ( 1014): Explicit concurrent mark sweep GC freed 227500(15MB) AllocSpace objects, 6(4MB) LOS objects, 33% free, 27MB/41MB, paused 2.600ms total 183.027ms
I/art     ( 1014): WaitForGcToComplete blocked for 142.247ms for cause HeapTrim
D/LocationManagerService( 1014): getProviders()=[passive]
D/AndroidRuntime( 6003): 
D/AndroidRuntime( 6003): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
D/AndroidRuntime( 6003): CheckJNI is OFF
W/ContextImpl( 5887): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
D/AndroidRuntime( 6003): readGMSProperty: start
D/AndroidRuntime( 6003): readGMSProperty: already setted!!
D/AndroidRuntime( 6003): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6003): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6003): readGMSProperty: end
D/AndroidRuntime( 6003): addProductProperty: start
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5887): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6023): MountEmulatedStorage()
E/Zygote  ( 6023): v2
I/libpersona( 6023): KNOX_SDCARD checking this for 10041
I/libpersona( 6023): KNOX_SDCARD not a persona
I/SELinux ( 6023): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=6023 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6023): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6023): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/UpdateIcingCorporaServi( 5972): UpdateCorporaTask done [took 110 ms] updated apps [took 110 ms] 
I/ActivityManager( 1014): Killing 5456:com.google.android.apps.plus/u0a120 (adj 15): empty #31
D/TimaKeyStoreProvider( 6023): TimaSignature is unavailable
D/ActivityThread( 6023): Added TimaKeyStore provider
I/SA      ( 6023): [SSP] onCreated
I/SA      ( 6023): [TPM] There is no property file
I/SA      ( 6023): [SCU] isHaveSA() - false
I/SA      ( 6023): [TPM] getModelProperty : null
I/SA      ( 6023): [TPM] getCSCProperty : null
I/SA      ( 6023): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 6023): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 6023): [DM] TFT FEATURE: false
I/SA      ( 6023): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 6023): [DM] init START
I/ActivityManager( 1014): Killing 5058:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
I/SA      ( 6023): [DM] This device is not a Vodafone
W/ResourceType( 6023): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 6023): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 6023): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 6023): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 6023): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 6023): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/libprocessgroup( 1014): failed to open /acct/uid_10120/pid_5456/cgroup.procs: No such file or directory
W/ResourceType( 6023): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 6023): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 6023): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 6023): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 6023): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 6023): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 6023): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 6023): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 6023): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 6023): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 6023): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 6023): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 6023): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 6023): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 6023): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 6023): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 6023): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 6023): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 6023): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 6023): [SCU] isHaveSA() - false
I/SA      ( 6023): support phone number id : false
I/SA      ( 6023): [DM] Supports Ref Jpn : true
I/SA      ( 6023): [DM] init END
I/SA      ( 6023): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 6023): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10175 extra.user_handle.:0 ]
I/ActivityManager( 1014): Killing 4940:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
E/AffinityControl( 6003): AffinityControl: registerfunction enter
W/GAV2    ( 5826): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/AndroidRuntime( 6003): Calling main entry com.android.commands.am.Am
W/libprocessgroup( 1014): failed to open /acct/uid_10150/pid_5058/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10040/pid_4940/cgroup.procs: No such file or directory
E/PersonaManagerService( 1014): inState():  stateMachine is null !!
I/PersonaManagerService( 1014): PersonaId don't exist
I/ActivityManager( 1014): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1014): mDVFSHelper.acquire()
I/SurfaceFlinger(  257): id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
I/SurfaceFlinger(  257): id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
I/ServiceManager(  314): Waiting for service AtCmdFwd...
D/FocusedStackFrame( 1014): Set to : 0
D/PhoneWindow( 1014): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1014): *FMB* installDecor flags : 25362712
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6052): MountEmulatedStorage()
I/libpersona( 6052): KNOX_SDCARD checking this for 10175
E/Zygote  ( 6052): v2
I/libpersona( 6052): KNOX_SDCARD not a persona
I/SELinux ( 6052): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
I/ActivityManager( 1014): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6052 uid=10175 gids={50175, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/SELinux ( 6052): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6052): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/InputDispatcher( 1014): Focused application set to: xxxx
D/PhoneWindow( 1014): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1014): *FMB* isFloatingMenuEnabled return false
D/InputDispatcher( 1014): Focus left window: 1476
I/SurfaceFlinger(  257): id=12 createSurf (720x1280),1 flag=404, uhalitest
D/AndroidRuntime( 6003): Shutting down VM
D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
I/art     (  305): Explicit concurrent mark sweep GC freed 8695(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 657us total 21.417ms
D/TimaKeyStoreProvider( 6052): TimaSignature is unavailable
D/ActivityThread( 6052): Added TimaKeyStore provider
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 18.293ms
V/WindowManager( 1014): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1014): Display changed displayId=0
D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 621us total 21.719ms
D/PersonaManager( 1014): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1014):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/SurfaceFlinger(  257): id=7 Removed Mauncher (5/9)
I/SurfaceFlinger(  257): id=7 Removed Mauncher (-2/9)
V/ActivityThread( 1476): updateVisibility : ActivityRecord{314549e0 token=android.os.BinderProxy@21f9c154 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1476): onTrimMemory. Level: 20
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6072): MountEmulatedStorage()
E/Zygote  ( 6072): v2
I/libpersona( 6072): KNOX_SDCARD checking this for 10100
I/libpersona( 6072): KNOX_SDCARD not a persona
I/SELinux ( 6072): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6072): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6072 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 4434:com.google.android.music:main/u0a111 (adj 15): empty #31
E/SELinux ( 6072): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
W/GAV2    ( 5826): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/TimaKeyStoreProvider( 6072): TimaSignature is unavailable
D/ActivityThread( 6072): Added TimaKeyStore provider
I/Icing   ( 2004): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
D/PackageIntentReceiver( 6072): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 6072): Not GearManger package! 
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
W/art     ( 6003): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/WebViewFactory( 6052): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,E/Zygote  ( 6094): MountEmulatedStorage()
I/libpersona( 6094): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6094): v2
I/libpersona( 6094): KNOX_SDCARD not a persona
,I/SELinux ( 6094): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6094 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 6094): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6094): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/LibraryLoader( 6052): Time to load native libraries: 2 ms (timestamps 1096-1098)
I/LibraryLoader( 6052): Expected native library version number "",actual native library version number ""
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 6094): TimaSignature is unavailable
,D/ActivityThread( 6094): Added TimaKeyStore provider
,V/GLSActivity( 1788): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WebViewChromiumFactoryProvider( 6052): Binding Chromium to main looper Looper (main, tid 1) {772bd38}
I/LibraryLoader( 6052): Expected native library version number "",actual native library version number ""
I/chromium( 6052): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,W/AccountFeatureHelper( 5826): Write apps_features disabled false
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/BrowserStartupController( 6052): Initializing chromium process, singleProcess=true
W/art     ( 6052): Attempt to remove local handle scope entry from IRT, ignoring
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/SysUtils( 6052): ApplicationContext is null in ApplicationStatus
,I/Icing   ( 2004): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28,
,E/Zygote  ( 6113): MountEmulatedStorage()
E/Zygote  ( 6113): v2
I/libpersona( 6113): KNOX_SDCARD checking this for 1000
I/libpersona( 6113): KNOX_SDCARD not a persona
,I/SELinux ( 6113): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6113 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 4798:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31
,I/SELinux ( 6113): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6113): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/chromium( 6052): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
I/chromium( 6052): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 6052): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,I/Adreno-EGL( 6052): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6052): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6052): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6052): Local Branch: 
I/Adreno-EGL( 6052): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6052): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6052):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/ChimeraCfgMgr( 2004): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2004): Module APK com.google.android.play.games already loaded
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 6113): TimaSignature is unavailable
W/libprocessgroup( 1014): failed to open /acct/uid_10111/pid_4434/cgroup.procs: No such file or directory
D/ActivityThread( 6113): Added TimaKeyStore provider
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GAV2    ( 5826): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/Mms/MmsApp( 5718):  start initViewCache mms
D/Mms/ComposeMessageFragment( 5718): [start]    fillCache consume time = 1891.390155
D/Mms/ComposeMessageFragment( 5718): fillCache, easy = false
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/AcmsPackageEventListener( 6113): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 6113): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
W/art     ( 2004): Suspending all threads took: 46.546ms
,E/Zygote  ( 6145): MountEmulatedStorage()
,E/Zygote  ( 6145): v2
I/libpersona( 6145): KNOX_SDCARD checking this for 10120
I/libpersona( 6145): KNOX_SDCARD not a persona
I/SELinux ( 6145): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6145): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6145 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6145): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Killing 5264:com.android.calendar/u0a135 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/AcmsService( 6113): Enter Oncreate
,D/AcmsServiceMonitor( 6113): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsService( 6113): creating AcmsCore
,D/AcmsCore( 6113): AcmsCore.getAcmsCore() - Enter
,D/AcmsCore( 6113): AcmsCore
,D/TimaKeyStoreProvider( 6145): TimaSignature is unavailable
,D/ActivityThread( 6145): Added TimaKeyStore provider
,D/AcmsCore( 6113): init
D/AcmsCore( 6113): Looper handler is not null
D/AcmsCore( 6113): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6113): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6113): Incrementing - Counter value: 1
D/AcmsCore( 6113): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 6113): onStartCommand
D/AcmsService( 6113): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 6113): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6113): Incrementing - Counter value: 2
D/AcmsService( 6113): Incremented Counter Value : onStartCommand
,D/AcmsCertificateMngr( 6113): AcmsCertificateMngr
D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityThread( 6113): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,W/ResourcesManager( 6145): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AcmsRevocationMngr( 6113): AcmsRevocationMngr
,D/AcmsService( 6113): Inside handle Intent
D/AcmsService( 6113): App added - package name: com.test.thalitest
D/AcmsCore( 6113): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6113): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6113): Incrementing - Counter value: 3
D/AcmsCore( 6113): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 6113): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 6113): Decrementing - Counter value: 2
,D/AbsListView( 5718): Get MotionRecognitionManager
,D/MotionRecognitionService( 1014):  ssp status : false
,W/chromium( 6052): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,D/Mms/ComposeMessageFragment( 5718): [end]    fillCache consume time = 114.387292
,W/libprocessgroup( 1014): failed to open /acct/uid_10134/pid_4798/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10135/pid_5264/cgroup.procs: No such file or directory
,W/ActivityManager( 1014): Activity pause timeout for ActivityRecord{b49bfae u0 com.test.thalitest/.MainActivity t2}
,W/art     ( 6052): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6052): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6052): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6052): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6052): CordovaWebView is running on device made by: samsung
,W/art     ( 6052): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6052): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6052): Render dirty regions requested: true
,D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
,D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
,V/ActivityThread( 6052): updateVisibility : ActivityRecord{248edf14 token=android.os.BinderProxy@3d935526 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6052): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 6052): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/Mms/BubbleViewCache( 5718): fillCache bubble = 1
,D/InputDispatcher( 1014): Focus entered window: 6052
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/SRIB_DCS( 6052): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6052): Initialized EGL, version 1.4
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,D/OpenGLRenderer( 6052): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6052): Enabling debug mode 0
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
,I/SamsungIME( 1806): getCurrentCandidateView,
,W/IInputConnectionWrapper( 6052): showStatusIcon on inactive InputConnection
W/ActivityManager( 1014): mDVFSHelper.release(),
I/ActivityManager( 1014): Displayed Component not be shown by security: +746ms (total +850ms)
I/Timeline( 6052): Timeline: Activity_idle id: android.os.BinderProxy@3d935526 time:81665
I/Timeline( 1014): Timeline: Activity_windows_visible id: ActivityRecord{b49bfae u0 com.test.thalitest/.MainActivity t2} time:81666
,I/SurfaceFlinger(  257): id=12 Removed uhalitest (7/9),
I/SurfaceFlinger(  257): id=12 Removed uhalitest (-2/9)
,W/BindingManager( 6052): Cannot call determinedVisibility() - never saw a connection for the pid: 6052
,I/splitIntent( 1014): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1014): Killing 5110:com.google.android.gm/u0a101 (adj 15): empty #31
,D/SamsungIME( 1806): Dismiss ExpandCandiate
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/JsMessageQueue( 6052): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager( 1014): Killing 5617:com.google.android.gms:car/u0a12 (adj 15): empty #31
,W/libprocessgroup( 1014): failed to open /acct/uid_10101/pid_5110/cgroup.procs: No such file or directory
,I/SamsungIME( 1806): getDebugLevel  : 0x4f4c
,W/libprocessgroup( 1014): failed to open /acct/uid_10012/pid_5617/cgroup.procs: No such file or directory
,I/SamsungIME( 1806): getDebugLevel  : 0x4f4c
,D/jxcore_app_log( 6052): JniHelper::setJavaVM(0xb7241450), pthread_self() = -1216796952
,D/JX-Cordova( 6052): jxcore cordova android initializing
,I/SamsungIME( 1806): KeybaordView init() : load resources
,I/SamsungIME( 1806): getCurrentKeyboard
,I/SamsungIME( 1806): getTextKeyboard
,D/AcmsKeyStoreHelper( 6113):  getKeyStoreForApplication Enter
,D/SamsungIME( 1806): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/AcmsKeyStoreHelper( 6113): Key Store exist
I/AcmsKeyStoreHelper( 6113): Hence loading the keystore file
,D/AcmsKeyStoreHelper( 6113):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 6113): getKeyStoreForApplication success 
D/AcmsCore( 6113): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 6113): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6113): Decrementing - Counter value: 1
D/AcmsCore( 6113): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 6113): This is NOT a valid MirrorLink app
D/AcmsCore( 6113): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 6113): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6113): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 6113): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 6113): getSvcCounter - Counter value: 0
D/AcmsService( 6113): Enter onDestroy
I/AcmsService( 6113): cleanUp(): inside service clean up
D/AcmsCore( 6113): AcmsCore: inside DeInit
D/AcmsCore( 6113): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 6113): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 6113): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 6113): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 6113): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 6113): getSvcCounter - Counter value: 0
D/AcmsService( 6113): killing acms process
I/Process ( 6113): Sending signal. PID: 6113 SIG: 9
,V/AlarmManager( 1014): waitForAlarm result :4
,I/ActivityManager( 1014): Process ACMS.Process (pid 6113)(adj 0) has died(34,1186)
,W/ProcessCpuTracker( 1014): Skipping unknown process pid 6113
,D/KeyguardViewMediator( 1175): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 1175): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1175): *** Keyguard wallpaper service already unbounded
,D/SamsungIME( 1806): [SwiftkeyWrapper] currentLangauge : 1701729619
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 5s ago
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/DBG_POLICYDM( 5810): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5810): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5810): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5810): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5810): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5810): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5810): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,W/jxcore-log( 6052): Initializing JXcore engine
W/jxcore-log( 6052): JXcore engine is ready
,W/jxcore-log( 6052): Starting JXcore engine
,E/audit   ( 1891): type=1400 msg=audit(1452294293.320:205): avc:  denied  { ioctl } for  pid=6052 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1891):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1891): type=1300 msg=audit(1452294293.320:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=be9bfd58 items=0 ppid=305 ppcomm=main pid=6052 auid=4294967295 uid=10175 gid=10175 euid=10175 suid=10175 fsuid=10175 egid=10175 sgid=10175 fsgid=10175 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1891): type=1320 msg=audit(1452294293.320:205): 
,W/jxcore-log( 6052): Platform android
W/jxcore-log( 6052): 
W/jxcore-log( 6052): Process ARCH arm
W/jxcore-log( 6052): 
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6052): JXcore Cordova bridge is ready!
I/jxcore-log( 6052): 
,W/jxcore-log( 6052): JXcore engine is started
,I/chromium( 6052): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6052): Toggling radios to true
I/jxcore-log( 6052): 
,D/BluetoothAdapter( 6052): enable()
,D/BluetoothAdapter( 6052): enable(): BT is already enabled..!
,D/SecContentProvider( 1014): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1014): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1014): mCursor = null
,D/WifiService( 1014): setWifiEnabled: true pid=6052, uid=10175
,W/ActivityManager( 1014): Permission Denial: getCurrentUser() from pid=6052, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1014): Failed getting userId using ActivityManagerNative
W/WifiService( 1014): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6052, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1014): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24778)
W/WifiService( 1014): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1014): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1014): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1014): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1014): name = wifi_on
,I/WifiService( 1014): disconnect: pid=6052, uid=10175
,I/wpa_supplicant( 2079): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 6052): Radios toggled
I/jxcore-log( 6052): 
,I/jxcore-log( 6052): My device name is: samsung-SM-A500FU
I/jxcore-log( 6052): 
,I/wpa_supplicant( 2079): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
,I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 2079): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 2079): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 2079): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 2079): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/wpa_supplicant( 2079): Cmd 35605 not handled
,D/Tethering( 1014): InitialState.processMessage what=4
E/WifiStateMachine( 1014): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 2079): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 2079): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2079): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2079): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 2079): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 2079): First Scan Start
,I/wpa_supplicant( 2079): Scan requested (ret=0) - scan timeout 30 seconds
D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceStatusChanged wlan0, false
E/Tethering( 1014): No numeric data
,I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1014): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1014): clearTetheredNotification()
D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceStatusChanged wlan0, false
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
V/NetworkStats( 1014): performPollLocked(flags=0x1)
,I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
,E/WifiConfigStore( 1014): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---
,D/HotspotTile( 1175): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1175): updateTetherState():false, false
,E/WifiNative-wlan0( 1014): do suspend true
V/NetworkStats( 1014): performPollLocked() took 9ms
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/WifiP2pService( 1014): InactiveState{ what=143375 }
,D/WifiP2pService( 1014): P2pEnabledState{ what=143375 }
,D/CommandListener(  277): Clearing all IP addresses on wlan0
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,V/NativeCrypto( 1788): Read error: ssl=0xb77f0dd0: I/O error during system call, Connection timed out,
D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
V/NativeCrypto( 1788): SSL shutdown failed: ssl=0xb77f0dd0: I/O error during system call, Broken pipe
,E/WifiStateMachine( 1014): Start Disconnecting Watchdog 1
,E/ConnectivityService( 1014): updateNetworkInfo()
,D/ConnectivityService( 1014): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/wpa_supplicant( 2079): wlan0: Setting scan request: 0 sec 0 usec
D/ConnectivityService( 1014): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
E/ConnectivityService( 1014): updateNetworkInfo()
,D/ConnectivityService( 1014): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14952 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
I/WifiTrafficPoller( 1014): evaluateTrafficStatsPolling
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,I/System.out( 1014): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1014): Tagging socket 359 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1014, getuid(): 1000
,I/qtaguid ( 1014): Untagging socket 359
,I/System.out( 1014): (HTTPLog)-Static: isSBSettingEnabled false
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiNative-wlan0( 1014): do suspend true
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
D/WifiP2pService( 1014): InactiveState{ what=143375 }
,D/WifiP2pService( 1014): P2pEnabledState{ what=143375 }
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3525): Starting #8
I/Hs20UtilService( 3525): Message received 5007
,D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1320): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1320): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1320): MountReceiver.mPrefHandler - 7002
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/CommandListener(  277): Clearing all IP addresses on wlan0,
D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Validated,
D/ConnectivityService( 1014): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityService( 1014): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1014): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1014): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 1014): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1014): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/TelephonyNetworkFactory( 1457): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1457): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI_P2P( 1014): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/EntConnectivity( 1014): Not allowed due to - mEnabled false - primarySimSlot false
,D/Tethering( 1014): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1014): MasterInitialState.processMessage what=3
,D/ConnectivityService( 1014): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): doQuit - quitNow()
D/ConnectivityManager.CallbackHandler( 2004): CM callback handler got msg 524292
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
V/NetworkStats( 1014): updateIfacesLocked()
V/NetworkStats( 1014): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---
D/StatusBar.NetworkController( 1175): EthernetConnected: false
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): 0
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
V/NetworkStats( 1014): performPollLocked() took 3ms
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1175): updateDataNetType()
D/StatusBar.NetworkController( 1175): NoService, mRoamingIconId = 0
D/EntConnectivity( 1014): Not allowed due to - mEnabled false - primarySimSlot false
,I/WifiTrafficPoller( 1014): evaluateTrafficStatsPolling
E/StatusBar.NetworkController( 1175): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/WifiNetworkAgent( 1014): NetworkAgent: NetworkAgent channel lost
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
V/NetworkStats( 1014): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 1175): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
D/WIFI    ( 1014): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1014): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6196 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
E/Zygote  ( 6196): MountEmulatedStorage()
I/libpersona( 6196): KNOX_SDCARD checking this for 10104
E/Zygote  ( 6196): v2
I/libpersona( 6196): KNOX_SDCARD not a persona
D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
I/SELinux ( 6196): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
I/SELinux ( 6196): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6196): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6196): TimaSignature is unavailable
D/ActivityThread( 6196): Added TimaKeyStore provider
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/ResourcesManager( 6196): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,I/Babel   ( 6196): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6196): MmsConfig.loadMmsSettings
I/Babel   ( 6196): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 6196): MmsConfig.loadFromDatabase
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/Babel   ( 6196): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6196): MmsConfig.loadFromResources
,E/Babel   ( 6196): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6196): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,W/Settings( 6196): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_StickerModule( 6196): App launched.
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 3525): Starting #9
V/NearbySettings( 1320): DMSUtil.isNetworkConnected - flag-null, state-null
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  282): getCameraInfo: X
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/Hs20UtilService( 3525): Message received 5007
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1320): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1320): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  282): getCameraInfo: X
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6196): Unrecognized profile 2130706433 for video/avc
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6196): Unsupported mime audio/evrc
,W/AudioCapabilities( 6196): Unsupported mime audio/qcelp
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6196): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6196): Unsupported mime audio/mpeg-L2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ConnectivityService( 1014): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 1014): updateDataUsageMap
,I/DBG_DM  ( 3092): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/DBG_DM  ( 3092): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,W/AudioCapabilities( 6196): Unsupported mime audio/x-ms-wma
,I/PCWCLIENTTRACE_PushUtil( 5741): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5741): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5741): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5741): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1014): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,W/AudioCapabilities( 6196): Unsupported mime audio/x-ima
,I/splitIntent( 1014): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,W/AudioCapabilities( 6196): Unsupported mime audio/qcelp
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/AudioCapabilities( 6196): Unsupported mime audio/evrc
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5741): noConnectivity : true
,I/ActivityManager( 1014): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6237 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/GpsLocationProvider( 1014): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/VideoCapabilities( 6196): Unsupported mime video/wvc1
,W/VideoCapabilities( 6196): Unsupported mime video/x-ms-wmv
,E/Zygote  ( 6237): MountEmulatedStorage()
,E/Zygote  ( 6237): v2
,I/libpersona( 6237): KNOX_SDCARD checking this for 10111
I/libpersona( 6237): KNOX_SDCARD not a persona
,I/SELinux ( 6237): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,I/SELinux ( 6237): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/SELinux ( 6237): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6237): TimaSignature is unavailable,
D/ActivityThread( 6237): Added TimaKeyStore provider
,E/Zygote  ( 6247): MountEmulatedStorage(),
E/Zygote  ( 6247): v2
I/libpersona( 6247): KNOX_SDCARD checking this for 10009
I/libpersona( 6247): KNOX_SDCARD not a persona
,I/SELinux ( 6247): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6247): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6247 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 6247): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/accuweather( 1709): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/ActivityManager( 1014): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6268 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,E/Zygote  ( 6268): MountEmulatedStorage()
,E/Zygote  ( 6268): v2
,I/libpersona( 6268): KNOX_SDCARD checking this for 10145
I/libpersona( 6268): KNOX_SDCARD not a persona
,I/SELinux ( 6268): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/VideoCapabilities( 6196): Unrecognized profile/level 32768/2 for video/mp4v-es
,I/SELinux ( 6268): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6268): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/VideoCapabilities( 6196): Unsupported mime video/wvc1
,D/TimaKeyStoreProvider( 6247): TimaSignature is unavailable
,D/ActivityThread( 6247): Added TimaKeyStore provider
,W/VideoCapabilities( 6196): Unsupported mime video/x-ms-wmv
,D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/accuweather( 1709): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1709): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1709): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1709): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,W/VideoCapabilities( 6196): Unsupported mime video/x-ms-wmv7
,D/accuweather( 1709): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1709): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,W/VideoCapabilities( 6196): Unsupported mime video/x-ms-wmv8
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
W/VideoCapabilities( 6196): Unsupported mime video/mp43
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1014): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6280 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,E/Zygote  ( 6280): MountEmulatedStorage(),
,E/Zygote  ( 6280): v2,
I/libpersona( 6280): KNOX_SDCARD checking this for 10081,
I/libpersona( 6280): KNOX_SDCARD not a persona
,I/SELinux ( 6280): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6280): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6280): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6268): TimaSignature is unavailable
,D/TimaKeyStoreProvider( 6280): TimaSignature is unavailable
,D/ActivityThread( 6268): Added TimaKeyStore provider
,D/ActivityThread( 6280): Added TimaKeyStore provider
,W/VideoCapabilities( 6196): Unsupported mime video/sorenson
,W/VideoCapabilities( 6196): Unsupported mime video/mp4v-esdp
,W/ResourcesManager( 6268): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6268): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6268): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6268): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6268): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/VideoCapabilities( 6196): Unsupported profile 4 for video/mp4v-es
,I/wpa_supplicant( 2079): nl80211: Received scan results (5 BSSes)
,I/wpa_supplicant( 2079): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 2079): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 2079): Trying to associate with  'G700'
I/wpa_supplicant( 2079): Re-associate with C0.AA.48
I/wpa_supplicant( 2079): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 2079): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,D/WifiMonitor( 1014): didn't find BSSID Trying to associate with SSID 'NG700'
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
,I/ActivityManager( 1014): Killing 5659:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,I/MusicStore( 6237): Database version: 108
,E/wpa_supplicant( 2079): Cmd 35605 not handled
,I/wpa_supplicant( 2079): wlan0: State: ASSOCIATING -> ASSOCIATED
,I/wpa_supplicant( 2079): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 2079): Associated with C0.AA.48
I/wpa_supplicant( 2079): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 2079): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 2079): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1014): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, false
D/Tethering( 1014): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, true
D/Tethering( 1014): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 2079): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 2079): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, true
,I/wpa_supplicant( 2079): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 2079): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 2079): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2079): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2079): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 2079): Blacklist: Clear (temp) 
I/wpa_supplicant( 2079): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1014): interfaceLinkStateChanged wlan0, true
D/Tethering( 1014): interfaceStatusChanged wlan0, true,
I/Nat464Xlat( 1014): interfaceLinkStateChanged wlan0, true
,E/Tethering( 1014): No numeric data
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
D/Tethering( 1014): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1014): clearTetheredNotification()
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
,V/NetworkStats( 1014): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---
,D/HotspotTile( 1175): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1175): updateTetherState():false, false
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,D/WifiNative-wlan0( 1014): callSECApiVoid - ID [50]
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,V/NetworkStats( 1014): performPollLocked() took 8ms
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/ActivityManager( 1014): Killing 5326:com.samsung.aasaservice/1000 (adj 15): empty #31
,E/WifiConfigStore( 1014): setLastSelectedConfiguration -1
I/KLMS-2.5.183: ( 3550): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Sat Jan 09 00:04:55 GMT+01:00 2016
,D/ConnectivityService( 1014): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1014): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1014): updateNetworkInfo()
D/ConnectivityService( 1014): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,E/WifiConfigStore( 1014): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/KLMS-2.5.183: ( 3550): KLMSAbstractReciever(): onReceive().END.
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,E/WifiConfigStore( 1014): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/CommandListener(  277): Setting iface cfg
,E/WifiStateMachine( 1014): Start Dhcp Watchdog 2
,E/Zygote  ( 6309): MountEmulatedStorage()
E/Zygote  ( 6309): v2
I/libpersona( 6309): KNOX_SDCARD checking this for 10113
I/libpersona( 6309): KNOX_SDCARD not a persona
,I/SELinux ( 6309): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6309 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager( 1014): Killing 4958:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,I/SELinux ( 6309): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6309): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
,I/KLMS-2.5.183: ( 3550): KLMSIntentService(): onCreate()
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3550): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3550): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/Zygote  ( 6322): MountEmulatedStorage()
E/Zygote  ( 6322): v2
,I/libpersona( 6322): KNOX_SDCARD checking this for 10034
I/libpersona( 6322): KNOX_SDCARD not a persona
,I/SELinux ( 6322): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1014): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6322 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
D/TimaKeyStoreProvider( 6309): TimaSignature is unavailable
D/ActivityThread( 6309): Added TimaKeyStore provider
,I/SELinux ( 6322): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6322): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1014): mCursor = null
,I/art     (  305): Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 674us total 21.880ms
,E/WifiNative-wlan0( 1014): do suspend false
D/TimaKeyStoreProvider( 6322): TimaSignature is unavailable
,D/ActivityThread( 6322): Added TimaKeyStore provider
D/SecContentProvider2( 1014): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1014): mCursor = null
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 18.433ms
,D/WifiP2pService( 1014): InactiveState{ what=143375 }
D/WifiP2pService( 1014): P2pEnabledState{ what=143375 }
,I/KLMS-2.5.183: ( 3550): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3550): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 623us total 17.155ms
,W/libprocessgroup( 1014): failed to open /acct/uid_10142/pid_5659/cgroup.procs: No such file or directory
,I/KLMS-2.5.183: ( 3550): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3550): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.183: ( 3550): KLMSIntentService(): onDestroy()
,E/SMD     (  287): DCD OFF,
,I/SO_AGENT( 6322): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5326/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10044/pid_4958/cgroup.procs: No such file or directory
,W/ResourcesManager( 6237): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6237): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/DBG_POLICYDM( 5810): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,E/SPPClientService( 5867): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/DBG_POLICYDM( 5810): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 5810): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5810): [com.policydm.XDMApplication(477/isNetworkChanged)] network not changed.... 
,V/JNIHelp ( 6237): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6237): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6237): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3998f55b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6237): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6237): GMSCore installation verified
,E/dhcpcd  ( 6347): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6347): version 5.5.6 starting
,E/dhcpcd  ( 6347): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 56484(2MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 27MB/41MB, paused 2.832ms total 172.896ms
D/ActivityManager( 1014): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
I/SA      ( 6023): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ],
I/SA      ( 6023): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 6023): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6023): [SLFUCHKMGR] constructor called,
,I/dhcpcd  ( 6347): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6347): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6347): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 6347): bssid match
I/dhcpcd  ( 6347): wlan0: rebinding lease of 192.168.1.129
D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SA      ( 6023): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 6023): [OR] == isSIMCardReady false ==
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/SA      ( 6023): [SCU] == networkStateCheck == false
I/SA      ( 6023): [OR] onReceive END
,V/DownloadManager( 1226): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/ConfigStore( 6237): Config Database version: 1
,E/SPPClientService( 5867): [[SystemStateMonitorService]] No Active Internet
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BadgeProvider( 5920): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/dhcpcd  ( 6347): wlan0: acknowledged 192.168.1.129 from 192.168.1.1
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/BadgeProvider( 5920): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 5920): sendNotify, [notify] : null
D/BadgeProvider( 5920): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5920): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5920): update, [UpdateCount] : 1
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/Launcher.Model( 1476): reloadBadges entered.
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6237): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6237): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6237): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 6347): wlan0: leased 192.168.1.129 for 86400 seconds,
,E/Zygote  ( 6365): MountEmulatedStorage(),
E/Zygote  ( 6365): v2
I/libpersona( 6365): KNOX_SDCARD checking this for 1000,
I/libpersona( 6365): KNOX_SDCARD not a persona,
,I/SELinux ( 6365): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6365): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6365): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6365 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/ActivityManager( 1014): Killing 5704:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music,
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/TimaKeyStoreProvider( 6365): TimaSignature is unavailable,
,D/ActivityThread( 6365): Added TimaKeyStore provider
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6309): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6309): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files,
,D/SecurityLogAgent( 6365): KnoxConfiguration : Current State = 1,
,D/SecurityLogAgent( 6365): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6365): StateMachine : Current State = 1,
,D/SecurityLogAgent( 6365): StateMachine : Changed Current State = 1,
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast,
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0,
,I/ActivityManager( 1014): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6406 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager( 1014): Killing 5365:com.google.android.partnersetup/u0a15 (adj 15): empty #31
E/Zygote  ( 6406): MountEmulatedStorage(),
I/libpersona( 6406): KNOX_SDCARD checking this for 10159
E/Zygote  ( 6406): v2
I/libpersona( 6406): KNOX_SDCARD not a persona
,I/SELinux ( 6406): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6406): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6406): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6309): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6309): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files,
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null,
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/TimaKeyStoreProvider( 6406): TimaSignature is unavailable
,D/ActivityThread( 6406): Added TimaKeyStore provider
,E/WifiNative-wlan0( 1014): do suspend true
,D/WifiP2pService( 1014): InactiveState{ what=143375 }
,D/WifiP2pService( 1014): P2pEnabledState{ what=143375 }
D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiStateMachine( 1014): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,E/WifiStateMachine( 1014): VerifyingLinkState enter
,D/WifiNative-wlan0( 1014): callSECApiInt - ID [210]
,E/ConnectivityService( 1014): updateNetworkInfo()
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ConnectivityService( 1014): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
D/ConnectivityService( 1014): Adding iface wlan0 to network 503
,I/AudioService( 1014): getStreamVolume 3 index 0
,I/MediaRouter( 6237): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,W/libprocessgroup( 1014): failed to open /acct/uid_10152/pid_5704/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10015/pid_5365/cgroup.procs: No such file or directory
,D/WifiWatchdogStateMachine( 1014): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1014): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 1014): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1014): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1014): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1014): Adding Route [fe80::/64 -> :: wlan0] to network 503
,E/WifiStateMachine( 1014): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/ConnectivityService( 1014): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
V/MusicLeanback( 6237): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/ConnectivityService( 1014): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1014): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1014): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 1014): LTETest block dns file not exists
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ConnectivityService( 1014): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 1014): updateNetworkInfo()
,E/ConnectivityService( 1014): updateNetworkInfo()
D/ConnectivityService( 1014): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService( 1014): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1014): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Connected
E/WifiStateMachine( 1014): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,E/WifiStateMachine( 1014): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/System.out( 1014): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 1000
,D/ConnectivityService( 1014):    accepting network in place of null
,D/WIFI_P2P( 1014): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/WIFI    ( 1014): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1457): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1457): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/WifiTrafficPoller( 1014): evaluateTrafficStatsPolling
,E/CSLegacyTypeTracker( 1014): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1014): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 1014): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/WifiTrafficPoller( 1014): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1014): mBoosterFLAG : 0
I/WifiTrafficPoller( 1014): current booster mode : FullMode
,D/WifiNative-wlan0( 1014): callSECApiVoid - ID [212]
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1014): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 1014): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,V/NetworkStats( 1014): updateIfacesLocked()
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
V/NetworkStats( 1014): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---
,D/Tethering( 1014): MasterInitialState.processMessage what=3
,D/ConnectivityService( 1014): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524290
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
V/NetworkStats( 1014): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1175): EthernetConnected: false
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1175): updateDataNetType()
D/StatusBar.NetworkController( 1175): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1175): updateLTEICONDataNetType:0
,D/ConnectivityManager.CallbackHandler( 2004): CM callback handler got msg 524290
,V/NetworkStats( 1014): performPollLocked() took 16ms
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/WaitQueueForNetworkActivate( 5795): notifyNetworkActivated
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,D/StatusBar.NetworkController( 1175): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ContextImpl( 5795): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/System.out( 1014): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/WebViewFactory( 6309): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/NetworkMonitor( 6237): type=WIFI subType= reason=null isConnected=true
,E/Zygote  ( 6449): MountEmulatedStorage()
E/Zygote  ( 6449): v2
I/libpersona( 6449): KNOX_SDCARD checking this for 10002
I/libpersona( 6449): KNOX_SDCARD not a persona
,I/SELinux ( 6449): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6449): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6449 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 23:04:56 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452294296608], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452294296584]}
,D/ConnectivityService( 1014): Validated NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Don't send network conditions - lacking user consent.
D/ConnectivityService( 1014): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1014): Validated
D/ConnectivityService( 1014): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,E/SELinux ( 6449): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ConnectivityService( 1014): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524290
D/ConnectivityService( 1014): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 2004): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1175): EthernetConnected: false
,D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1175): updateDataNetType()
D/StatusBar.NetworkController( 1175): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1175): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1175): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
I/LibraryLoader( 6309): Time to load native libraries: 4 ms (timestamps 6729-6733)
I/LibraryLoader( 6309): Expected native library version number "",actual native library version number ""
,D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/WebViewChromiumFactoryProvider( 6309): Binding Chromium to main looper Looper (main, tid 1) {25d7810}
,D/TimaKeyStoreProvider( 6449): TimaSignature is unavailable
,D/ActivityThread( 6449): Added TimaKeyStore provider
,I/LibraryLoader( 6309): Expected native library version number "",actual native library version number ""
D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/chromium( 6309): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,W/ResourcesManager( 6237): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6237): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 6237): Using the GMSCore's GoogleHttpClient
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/BrowserStartupController( 6309): Initializing chromium process, singleProcess=true
,W/art     ( 6309): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6309): ApplicationContext is null in ApplicationStatus
,I/ActivityManager( 1014): Killing 5756:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6471): MountEmulatedStorage(),
E/Zygote  ( 6471): v2
I/libpersona( 6471): KNOX_SDCARD checking this for 1000
I/libpersona( 6471): KNOX_SDCARD not a persona
,I/SELinux ( 6471): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6471 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/SELinux ( 6471): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6471): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6471): TimaSignature is unavailable
,D/ActivityThread( 6471): Added TimaKeyStore provider
,D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/chromium( 6309): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 6309): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,I/chromium( 6309): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5795): AutoUpdateManager:IDLE:execute
,I/Adreno-EGL( 6309): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6309): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6309): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6309): Local Branch: 
I/Adreno-EGL( 6309): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6309): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6309):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/InitializeManagerStateMachine( 5795): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5795): exit::IDLE
D/InitializeManagerStateMachine( 5795): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5795): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 5795): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5795): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5795): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 5795): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5795): entry::SUCCESS
,D/hcjo    ( 5795): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/hcjo    ( 5795): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5795): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5795): exit::SUCCESS,
D/InitializeManagerStateMachine( 5795): entry::IDLE
,I/ActivityManager( 1014): Killing 5693:com.samsung.android.sm/1000 (adj 15): empty #31,
,I/DIAGMON_AGENT( 6471): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/AudioManagerAndroid( 6309): Requires BLUETOOTH permission
,I/NSApplication( 6309): Starting up...
,I/ActivityManager( 1014): Killing 5777:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,I/ActivityManager( 1014): Killing 5040:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #32
,W/libprocessgroup( 1014): failed to open /acct/uid_10156/pid_5756/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/DIAGMON_AGENT( 6471): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/DIAGMON_AGENT( 6471): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !,
D/ConnectivityService( 1014): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,E/Zygote  ( 6503): MountEmulatedStorage(),
E/Zygote  ( 6503): v2
I/libpersona( 6503): KNOX_SDCARD checking this for 10125
I/DIAGMON_AGENT( 6471): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/libpersona( 6503): KNOX_SDCARD not a persona,
I/SELinux ( 6503): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6503 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
,I/SELinux ( 6503): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1014): Killing 5478:com.android.vending/u0a28 (adj 15): empty #31
,E/SELinux ( 6503): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DIAGMON_AGENT( 6471): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6471): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6471): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5693/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5040/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5777/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6503): TimaSignature is unavailable
,D/ActivityThread( 6503): Added TimaKeyStore provider
,I/DBG_DM  ( 3092): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/ActivityManager( 1014): Killing 5389:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,I/NetworkMonitor( 6237): type=WIFI subType= reason=null isConnected=true
,W/ResourcesManager( 6503): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6503): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6503): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/SecContentProvider2( 1014): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1014): mCursor = null
,D/QuickConnect( 6503): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6503): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6503): PeriphStartReceiver.onReceive - no need to start
,I/splitIntent( 1014): Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1014): Killing 5422:com.sec.knox.bridge/1000 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3525): Starting #10
D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1320): DMSUtil.isNetworkConnected - flag-null, state-null
I/Hs20UtilService( 3525): Message received 5007
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/GpsLocationProvider( 1014): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1320): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3525): Starting #11
,I/Hs20UtilService( 3525): Message received 5007
,D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1320): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3525): Starting #12
,D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1320): DMSUtil.isNetworkConnected - flag-null, state-null
,I/Hs20UtilService( 3525): Message received 5007
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1320): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3525): Starting #13
,I/Hs20UtilService( 3525): Message received 5007
,D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1320): MountReceiver.onReceive - Keep current state
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
,D/SecContentProvider2( 1014): mCursor = null
,W/libprocessgroup( 1014): failed to open /acct/uid_10028/pid_5478/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10032/pid_5389/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_5422/cgroup.procs: No such file or directory
,I/PCWCLIENTTRACE_PushUtil( 5741): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5741): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5741): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5741): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1014): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,I/splitIntent( 1014): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,D/accuweather( 1709): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,V/MusicLeanback( 6237): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/daemonapp( 1302): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
D/accuweather( 1709): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,I/SurfaceFlinger(  257): id=14 createSurf (1x1),1 flag=4, Uoast
D/accuweather( 1709): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1709): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/FOTA_Client( 6247): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,D/accuweather( 1709): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/SecurityLogAgent( 6365): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6365): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6365): StateMachine : Current State = 1
,D/PowerManagerService( 1014): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014
,D/SecurityLogAgent( 6365): StateMachine : Changed Current State = 1
,I/FOTA_Client( 6247): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 6247): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
D/accuweather( 1709): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1709): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,W/FOTA_Client( 6247): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,D/SRIB_DCS( 1175): log_dcs ThreadedRenderer::initialize entered! 
,I/KLMS-2.5.183: ( 3550): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Sat Jan 09 00:04:57 GMT+01:00 2016
,I/DIAGMON_AGENT( 6471): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6471): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6471): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 6471): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/hcjo    ( 5795): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5795): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5795): exit::IDLE
D/InitializeManagerStateMachine( 5795): entry::NETWORK_CHECK
,I/KLMS-2.5.183: ( 3550): KLMSAbstractReciever(): onReceive().END.
,D/InitializeManagerStateMachine( 5795): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5795): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5795): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5795): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5795): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5795): entry::SUCCESS
D/hcjo    ( 5795): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5795): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5795): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/QuickConnect( 6503): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,D/InitializeManagerStateMachine( 5795): exit::SUCCESS
D/InitializeManagerStateMachine( 5795): entry::IDLE
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.183: ( 3550): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3550): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3550): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/QuickConnect( 6503): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6503): PeriphStartReceiver.onReceive - no need to start
,I/KLMS-2.5.183: ( 3550): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3550): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.183: ( 3550): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3550): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.183: ( 3550): NetworkChangeOperations(): uploadRequestLog().START 
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/AlarmManager( 1014): waitForAlarm result :8
,I/KLMS-2.5.183: ( 3550): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.183: ( 3550): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.183: ( 3550): KLMSIntentService(): onDestroy()
,E/SPPClientService( 5867): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6023): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 6023): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6023): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 5810): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5810): [com.policydm.XDMApplication(469/isNetworkChanged)] a previous network is 0, current network is 2
,I/SA      ( 6023): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6023): [OR] == isSIMCardReady false ==
,E/DBG_POLICYDM( 5810): [com.policydm.XDMApplication(471/isNetworkChanged)] network changed.... 
,I/SA      ( 6023): [SCU] == networkStateCheck == true
,I/SA      ( 6023): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 6023): isChinaCountryCode : false
,I/SA      ( 6023): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6023): [OR] == networkStateCheck true ==
,I/SA      ( 6023): [OR] GetMyCountryZoneTask
,I/SA      ( 6023): [OR] onReceive END
,I/SA      ( 6023): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 1226): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/SA      ( 6023): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6023): [SSP] query invoked
,I/DBG_POLICYDM( 5810): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5810): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5810): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/SA      ( 6023): [TPMU] GetMccFromDB : null
I/SA      ( 6023): [SCU] getMccFromPreferece mcc = 260
,D/SecContentProvider2( 1014): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1014): mCursor = null
,I/DBG_POLICYDM( 5810): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
I/SA      ( 6023): [TPM] isNoProxy(default) : true
,I/DBG_POLICYDM( 5810): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5810): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5810): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5810): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/splitIntent( 1014): Queue : background intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart  false.
,E/File    ( 6023): fail readDirectory() errno=2
,E/DBG_POLICYDM( 5810): [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,I/DBG_POLICYDM( 5810): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/ConnectivityService( 1014): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/SSRM:n  ( 1014): SIOP:: AP = 330
,I/SA      ( 6023): [RC New] Execute method=[GET] start
,I/SA      ( 6023): [RC New] Security=[true]
,I/System.out( 6023): Thread-1050(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6023): Thread-1050(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 6023): Thread-1050(ApacheHTTPLog):isShipBuild true
I/System.out( 6023): Thread-1050(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6023): Thread-1050(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): uids 10041,
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10041
,D/ConnectivityService( 1014): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1014): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524295
,D/ConnectivityService( 1014): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 2004): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 2004): CM callback handler got msg 524295
,E/SMD     (  287): DCD OFF
,I/SA      ( 6023): [RC New] [v2liruge] api execute + 684
,I/SA      ( 6023): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6023): AsyncTask #1 calls detatch()
,I/SA      ( 6023): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6023): [OCP] update openData : PL
,I/SA      ( 6023): [TPMU] getNetworkMcc : 
,I/SA      ( 6023): [SCU] saveMccToPreferece Start
,I/SA      ( 6023): [SCU] RegionMCC : 260
I/SA      ( 6023): [SSP] query invoked
,I/SA      ( 6023): [TPMU] GetMccFromDB : null
,I/SA      ( 6023): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6023): [SCU] saveMccToPreferece End
,I/SA      ( 6023): [RC New] executeRequest [v2liruge] end. 745
I/SA      ( 6023): [RC New] Execute end
,I/SA      ( 6023): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6023): [OR] GetMyCountryZoneTask Success
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,D/PackageManager( 1014): [MSG] MCS_UNBIND
,I/ActivityManager( 1014): Killing 5718:com.android.mms/u0a46 (adj 15): empty #31
,D/CountryDetector( 1014): No listener is left
,W/libprocessgroup( 1014): failed to open /acct/uid_10046/pid_5718/cgroup.procs: No such file or directory
,V/AlarmManager( 1014): waitForAlarm result :8
,I/dhcpcd  ( 6347): wlan0: sending IPv6 Router Solicitation
,V/AlarmManager( 1014): waitForAlarm result :8
,D/ActivityManager( 1014): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SurfaceFlinger(  257): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  257): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 1014): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1014) eventTime = 90848
,D/PowerManagerService( 1014): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014 (0x0)
,D/PowerManagerService( 1014): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1014, ws=WorkSource{10054}) (elapsedTime=3467)
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/GAV4    ( 6309): Thread[GAThread,5,main]: No campaign data found.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1788): callingUid 10012, callindPid: 1788
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/GmsUtils( 6237): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 6237): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,I/MusicLeanback( 6237): Conditions not met for autocaching.
,I/MusicLeanback( 6237): Stop autocaching.
,E/SMD     (  287): DCD OFF
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5741): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5741): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5741): [GetString-S]
,I/ReactiveServiceManager( 5741): Supported : 1
,D/QSEECOMAPI: ( 1014): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1014): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1014): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1014): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1014): QSEECom_shutdown_app, app_id = 11
,E/terrier ( 1014): handleString: Failed to handle string(-4)
E/terrier ( 1014): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5741): getString is null
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5741): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5741): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5741): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5741): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5741): [ensureRegistration] - No Samsung account
,I/PowerManagerService( 1014): [PWL] Off : 15s ago
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1014): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6549 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6549): MountEmulatedStorage(),
E/Zygote  ( 6549): v2
I/libpersona( 6549): KNOX_SDCARD checking this for 10028
I/libpersona( 6549): KNOX_SDCARD not a persona
,I/SELinux ( 6549): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,V/AlarmManager( 1014): ___SyncScheduler (v3) ACTIVATED___
,I/SELinux ( 6549): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
V/AlarmManagerEXT( 1014): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1014): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
E/SELinux ( 6549): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: android, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,I/BackgroundCompactionService( 1014): onStart. jobID=801
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
I/BackgroundCompactionService( 1014): onStart done. jobID=801
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
I/BackgroundCompactionService( 1014): Execute BGCompaction (type1). (0 times)
,I/BackgroundCompactionService( 1014): compact_memory command done
,D/TimaKeyStoreProvider( 6549): TimaSignature is unavailable
,D/ActivityThread( 6549): Added TimaKeyStore provider
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/Finsky  ( 6549): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6549): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6549): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6549): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 6549): Skipping gmscore version check
,D/Finsky  ( 6549): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6549): [1] Libraries$2.run: Finished loading 1 libraries.
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6549): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1014): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 6549): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager( 1014): Waited long enough for: ServiceRecord{32a19c25 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,I/dhcpcd  ( 6347): wlan0: sending IPv6 Router Solicitation
,D/Finsky  ( 6549): [1155] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6549): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager( 1014): Killing 5903:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,W/libprocessgroup( 1014): failed to open /acct/uid_10047/pid_5903/cgroup.procs: No such file or directory
,E/SMD     (  287): DCD OFF
,I/jxcore-log( 6052): Test app app.js loaded
I/jxcore-log( 6052): 
,I/chromium( 6052): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1014): Plugged
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5795): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5795): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5795): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5795): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 44231(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 2.445ms total 165.142ms
,D/hcjo    ( 5795): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5795): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5795): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5795): entry::IDLE
,D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5795): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5795): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5795): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5795): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5795): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5795): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5795): entry::IDLE
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 320
,I/dhcpcd  ( 6347): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6347): wlan0: no IPv6 Routers available
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,I/PowerManagerService( 1014): [PWL] Off : 30s ago
,E/Watchdog( 1014): !@Sync 3
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1788): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1788): Vacuum at: now=1452294321630 tag=VacuumService
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
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
,I/PhenotypeConfigurator( 1788): Scheduling Phenotype for one-off execution 12368 seconds from now (1452294322044)
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1788): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeFlagCommitter( 1788): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1788): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 1014): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1788): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1788): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1788): (HTTPLog)-Static: isShipBuild true
I/System.out( 1788): (HTTPLog)-Thread-253-709353393: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 1788): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10012
,I/System.out( 1788): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1788): Tagging socket 80 with tag 1000120100000000{268440065,0} for uid -1, pid: 1788, getuid(): 10012
,I/qtaguid ( 1788): Tagging socket 84 with tag 1000120100000000{268440065,0} for uid -1, pid: 1788, getuid(): 10012
,E/SMD     (  287): DCD OFF
,D/LocationManagerService( 1014): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1788): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1788): Tagging socket 80 with tag 1000120100000000{268440065,0} for uid -1, pid: 1788, getuid(): 10012
,D/FactoryTest( 5306): Not factory mode
,D/FactoryTest( 5306): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5306): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5306): still no open session command from host, so toast
,W/ContextImpl( 5306): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5306): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 5306): Timeline: Activity_launch_request id:com.android.settings time:112927
,E/PersonaManagerService( 1014): inState():  stateMachine is null !!
,I/PersonaManagerService( 1014): PersonaId don't exist
,I/ActivityManager( 1014): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1014): mDVFSHelper.acquire()
,D/PersonaManager( 1014): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings
D/InputDispatcher( 1014): Focused application set to: xxxx
D/InputDispatcher( 1014): Focus left window: 6052
,E/MTPRx   ( 5306): started activity for popup
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 5306): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 5306): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5306): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5306): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5306): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5306): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5306): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/InputDispatcher( 1014): Focused application set to: xxxx
,D/InputDispatcher( 1014): Focus entered window: 6052
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1014): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@2a568c67 attribute=null, token = android.os.BinderProxy@278c4e41
,D/LocationManagerService( 1014): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1788): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1788): Tagging socket 80 with tag 1000120100000000{268440065,0} for uid -1, pid: 1788, getuid(): 10012
,D/SettingsReceiverActivity( 5306): dev.kiessupport is : TRUE
,D/PhoneWindow( 5306): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5306): *FMB* installDecor flags : 8388610
,D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
,D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
,D/PersonaManager( 1014): isKioskContainerExistOnDevice
,V/ActivityThread( 6052): updateVisibility : ActivityRecord{248edf14 token=android.os.BinderProxy@3d935526 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/Timeline( 6052): Timeline: Activity_idle id: android.os.BinderProxy@3d935526 time:113108
,D/LocationManagerService( 1014): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1788): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1788): Tagging socket 80 with tag 1000120100000000{268440065,0} for uid -1, pid: 1788, getuid(): 10012
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/ActivityManager( 1014): mDVFSHelper.release()
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/SMD     (  287): DCD OFF
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
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
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
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
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/PowerManagerService( 1014): [PWL] Off : 50s ago
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/Watchdog( 1014): !@Sync 4
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,V/AlarmManager( 1014): waitForAlarm result :8,
,E/SMD     (  287): DCD OFF
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.sec.spp.push
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6635): MountEmulatedStorage(),
E/Zygote  ( 6635): v2,
I/libpersona( 6635): KNOX_SDCARD checking this for 10035
I/libpersona( 6635): KNOX_SDCARD not a persona
,I/SELinux ( 6635): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1014): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.util.DlcRegiReceiver: pid=6635 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6635): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6635): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6635): TimaSignature is unavailable
,D/ActivityThread( 6635): Added TimaKeyStore provider
,E/SPPClientService( 6635): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6635): [PushClientApplication] Push log off : This is Ship build version
,D/ActivityManager( 1014): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.dlc.sender.SenderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/SPPClientService( 6635): PushLog.txt file is not deleted.
,D/SPPClientService( 6635): PushLog.txt file is not deleted.
D/SPPClientService( 6635): ============PushLog. stop!
,D/ActivityManager( 1014): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.dlc.db.DbService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/ActivityManager( 1014): Killing 5935:com.wsomacp/u0a25 (adj 15): empty #31
,W/libprocessgroup( 1014): failed to open /acct/uid_10025/pid_5935/cgroup.procs: No such file or directory
,I/PowerManagerService( 1014): [PWL] Off : 75s ago
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,I/ClearcutLoggerApiImpl( 1788): disconnect managed GoogleApiClient
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/Watchdog( 1014): !@Sync 5
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1,
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 105s ago,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/Watchdog( 1014): !@Sync 6,
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1014): waitForAlarm result :4
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1014): SIOP:: AP = 260,
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,V/AlarmManager( 1014): waitForAlarm result :8
,E/SMD     (  287): DCD OFF
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1014): [PWL] Off : 140s ago
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/Watchdog( 1014): !@Sync 7,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged,
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 1014): [PWL] Off : 180s ago
,E/Watchdog( 1014): !@Sync 8,
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): stay LED for fully charged
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1014): !@Sync 9
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1014): Do not check CP during LCD off.,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1014): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6052): --= Surplus to requirements =--
I/jxcore-log( 6052): 
I/jxcore-log( 6052): ****TEST TOOK:  ms ****
I/jxcore-log( 6052): 
I/jxcore-log( 6052): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6052): 
,D/AndroidRuntime( 6723): 
D/AndroidRuntime( 6723): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6723): CheckJNI is OFF,
D/AndroidRuntime( 6723): readGMSProperty: start
D/AndroidRuntime( 6723): readGMSProperty: already setted!!,
D/AndroidRuntime( 6723): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6723): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6723): readGMSProperty: end
D/AndroidRuntime( 6723): addProductProperty: start
,E/AffinityControl( 6723): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6723): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1014): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
D/PackageManager( 1014): START PACKAGE DELETE: observer{981687525},
D/PackageManager( 1014): pkg{<packageName>}
D/PackageManager( 1014): user{0}
D/PackageManager( 1014): caller{2000}
D/PackageManager( 1014): flags{3}
D/PersonaManagerService( 1014): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1014): [MSG] DELETE_PACKAGE_AS_USER
,D/PersonaManagerService( 1014): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1014): !@killApplicatoin: 10175, uninstall pkg
D/PackageManager( 1014): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
I/ActivityManager( 1014): Force stopping com.test.thalitest appid=10175 user=-1: uninstall pkg
,D/PackageManager( 1014): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
I/ActivityManager( 1014): Killing 6052:com.test.thalitest/u0a175 (adj 0): stop com.test.thalitest cause uninstall pkg
D/PackageManagerService( 1014): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1014): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1014): getApplicationUninstallationEnabled,
D/ApplicationPolicy( 1014): getApplicationUninstallationEnabled :  enabled true
,W/PackageSettings( 1014): Skipping PackageSetting{bc4f4f4 com.example.hello/10177} due to missing metadata
,I/WindowState( 1014): WIN DEATH: Window{1ddb4fe6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  257): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  257): id=13 Removed NainActivit (-2/8)
D/InputDispatcher( 1014): Focus left window: 6052
I/ActivityManager( 1014):   Force finishing activity ActivityRecord{b49bfae u0 com.test.thalitest/.MainActivity t2}
,W/ActivityManager( 1014): Spurious death for ProcessRecord{2e5a83ba 6052:com.test.thalitest/u0a175}, curProc for 6052: null
I/ActivityManager( 1014): Force stopping com.test.thalitest appid=10175 user=0: pkg removed
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1014):   Force finishing activity ActivityRecord{b49bfae u0 com.test.thalitest/.MainActivity t2 f}
W/ActivityManager( 1014): Duplicate finish request for ActivityRecord{b49bfae u0 com.test.thalitest/.MainActivity t2 f}
,W/ActivityManager( 1014): CustomStartingWindow se packge removed so remove capture also
,D/InputDispatcher( 1014): Focused application released
,D/FocusedStackFrame( 1014): Set to : 0
,W/ActivityManager( 1014): mDVFSHelper.acquire()
,I/art     ( 4923): Explicit concurrent mark sweep GC freed 2522(147KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 1.219ms total 34.043ms
,V/WindowManager( 1014): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,E/SMD     (  287): DCD OFF
I/art     ( 5972): Explicit concurrent mark sweep GC freed 270(21KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/11MB, paused 717us total 39.212ms
,D/Launcher( 1476): onRestart, Launcher: 735853843
,I/InputReader( 1014): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 2004): Explicit concurrent mark sweep GC freed 7630(396KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 13MB/18MB, paused 1.279ms total 77.062ms
,W/GeofencerStateMachine( 1788): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 1806): mOCRHelper is null
,D/Launcher( 1476): onStart, Launcher: 735853843
D/Launcher.HomeView( 1476): onStart
,D/Launcher( 1476): onResume, Launcher: 735853843
,D/RegisteredComponentCache( 1439): Collect Tech packages for Knox
,D/SettingsProvider( 1014): name = kids_home_mode
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10007
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1014): ret = -1
,D/Launcher.HomeView( 1476): onResume
,D/PersonaManager( 1439): isKioskContainerExistOnDevice
,D/Launcher( 1476): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,I/KLMS-2.5.183: ( 3550): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Sat Jan 09 00:08:31 GMT+01:00 2016
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/MenuAppsGridFragment( 1476): onResume
,D/WallpaperManager( 1476): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1476): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1476): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/ActivityManager( 1014): handle home activity for 0
I/KLMS-2.5.183: ( 3550): KLMSAbstractReciever(): onReceive().END.
I/WallpaperManagerService( 1014): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1014): post home show event for user 0
D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
D/Launcher.HomeView( 1476): onPause
,D/Launcher( 1476): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
I/splitIntent( 1014): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
,I/splitIntent( 1014): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/EnterpriseDeviceManagerService( 1014): Package has changed for user 0
E/Zygote  ( 6737): MountEmulatedStorage()
E/Zygote  ( 6737): v2
I/libpersona( 6737): KNOX_SDCARD checking this for 10094
I/libpersona( 6737): KNOX_SDCARD not a persona
I/KLMS-2.5.183: ( 3550): KLMSIntentService(): onCreate()
,I/SELinux ( 6737): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/KLMS-2.5.183: ( 3550): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/SELinux ( 6737): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6737 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
D/EnterpriseDeviceManagerService( 1014): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1014): no available spell checker services found
E/SELinux ( 6737): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3550): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3550): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3550): KLMSIntentService(): PACKAGE_REMOVED
,E/Zygote  ( 6748): MountEmulatedStorage()
E/Zygote  ( 6748): v2
I/libpersona( 6748): KNOX_SDCARD checking this for 10044
I/libpersona( 6748): KNOX_SDCARD not a persona
I/SELinux ( 6748): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6748): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6748): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6748 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 6737): TimaSignature is unavailable
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
D/ActivityThread( 6737): Added TimaKeyStore provider
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 6767): MountEmulatedStorage()
E/Zygote  ( 6767): v2
I/libpersona( 6767): KNOX_SDCARD checking this for 1000
I/libpersona( 6767): KNOX_SDCARD not a persona
,I/SELinux ( 6767): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6767): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1014): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=6767 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 6767): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3550): KLMSIntentService(): listeningToPackageRemoved().START
,D/TimaKeyStoreProvider( 6748): TimaSignature is unavailable
,D/ActivityThread( 6748): Added TimaKeyStore provider
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 48255(3MB) AllocSpace objects, 88(1409KB) LOS objects, 33% free, 27MB/41MB, paused 4.935ms total 222.766ms
,I/art     ( 1014): WaitForGcToComplete blocked for 101.083ms for cause Explicit
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/SurfaceFlinger(  257): id=15 createSurf (720x1280),1 flag=4, Mauncher
D/SecContentProvider2( 1014): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1014): mCursor = null
,E/Zygote  ( 6782): MountEmulatedStorage()
E/Zygote  ( 6782): v2
I/libpersona( 6782): KNOX_SDCARD checking this for 10149
I/libpersona( 6782): KNOX_SDCARD not a persona
,I/SELinux ( 6782): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6782 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6782): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6782): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     (  305): Explicit concurrent mark sweep GC freed 8713(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 641us total 23.282ms
,D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/KLMS-2.5.183: ( 3550): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/TimaKeyStoreProvider( 6767): TimaSignature is unavailable
,D/ActivityThread( 6767): Added TimaKeyStore provider
,D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 18.118ms
D/TimaKeyStoreProvider( 6782): TimaSignature is unavailable,
D/ActivityThread( 6782): Added TimaKeyStore provider
,D/InputDispatcher( 1014): Focus entered window: 1476
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 6748): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6748): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6748): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6748): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6748): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6748): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6748): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6748): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/SRIB_DCS( 1476): log_dcs ThreadedRenderer::initialize entered! 
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 628us total 17.110ms
D/PersonaManager( 1439): isKioskContainerExistOnDevice
D/Launcher.HomeView( 1476): onStop
V/ActivityThread( 1476): updateVisibility : ActivityRecord{314549e0 token=android.os.BinderProxy@21f9c154 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1014): Got RemoteException sending setActive(false) notification to pid 6052 uid 10175
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ResourcesManager( 6767): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/SamsungIME( 1806): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/elm:15183( 6737): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15183( 6737): ELMEngine.ELMEngine( context ).
,D/elm:15183( 6737): MDMBridge.setEnterpriseBridge()
,D/ActivityManager( 1014): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,D/RegisteredServicesCache( 1439): empty dynamic service
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,I/KLMS-2.5.183: ( 3550): KLMSIntentService(): listeningToPackageRemoved().END
,D/elm:15183( 6737): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 6800): MountEmulatedStorage()
I/libpersona( 6800): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6800): v2
I/libpersona( 6800): KNOX_SDCARD not a persona
I/SELinux ( 6800): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=6800 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 6800): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6800): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/elm:15183( 6737): ElmAgentService : onCreate()
,I/KLMS-2.5.183: ( 3550): KLMSIntentService(): onDestroy()
,D/ThemeInfoUtil( 6782): getCurrentFestivalName is [null]
D/ThemeInfoUtil( 6782): isCurrentFestival = false
,D/elm:15183( 6737): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) },
D/elm:15183( 6737): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6737): MDMBridge.getInstance()
D/elm:15183( 6737): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15183( 6737): MDMBridge.getAllLicenseInfoFromSDK()
,W/ActivityManager( 1014): mDVFSHelper.release()
,I/Timeline( 1014): Timeline: Activity_windows_visible id: ActivityRecord{1461de24 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:302199
,D/TimaKeyStoreProvider( 6800): TimaSignature is unavailable
,D/ActivityThread( 6800): Added TimaKeyStore provider
,I/ActivityManager( 1014): Killing 5951:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 6820): MountEmulatedStorage()
E/Zygote  ( 6820): v2
I/libpersona( 6820): KNOX_SDCARD checking this for 10152
I/libpersona( 6820): KNOX_SDCARD not a persona
,I/SELinux ( 6820): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6820): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6820 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,E/SELinux ( 6820): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/elm:15183( 6737): ElmAgentService : onDestroy().
,D/PersonaManager( 1014): isKioskContainerExistOnDevice
,D/AASAservice-UpdateReceiver( 6800): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,E/SQLiteLog( 6767): (284) automatic index on crash_info_summary(package_name_touched)
,W/System.err( 6800): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,W/System.err( 6800): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
W/System.err( 6800): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 6800): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 6800): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 6800): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 6800): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6800): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6800): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 6800): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6800): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6800): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6800): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/TimaKeyStoreProvider( 6820): TimaSignature is unavailable
,I/ActivityManager( 1014): Killing 5972:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,D/ActivityThread( 6820): Added TimaKeyStore provider
,I/ActivityManager( 1014): Killing 5887:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,D/BadgeProvider( 5920): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5920): sendNotify, [notify] : null
D/BadgeProvider( 5920): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5920): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5920): update, [UpdateCount] : 1
,I/art     ( 6767): Explicit concurrent mark sweep GC freed 9687(457KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 769us total 73.180ms
,D/NearbySource( 6748): Nearby Source Create!
,D/NearbyContext( 6748): Nearby Context Create!
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 11162(514KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 3.102ms total 384.348ms
,E/SQLiteLog( 6820): (284) automatic index on shooting_modes(title_id)
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ResourceType( 1014): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
W/ContextImpl( 6748): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 6748): Samsung link source created
,E/Zygote  ( 6838): MountEmulatedStorage()
I/libpersona( 6838): KNOX_SDCARD checking this for 10156
E/Zygote  ( 6838): v2
I/libpersona( 6838): KNOX_SDCARD not a persona
,I/SELinux ( 6838): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=6838 uid=10156 gids={50156, 9997} abi=armeabi-v7a
,I/SELinux ( 6838): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6838): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6849): MountEmulatedStorage()
E/Zygote  ( 6849): v2
I/libpersona( 6849): KNOX_SDCARD checking this for 1000
I/libpersona( 6849): KNOX_SDCARD not a persona
,I/SELinux ( 6849): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6849): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
D/TimaKeyStoreProvider( 6838): TimaSignature is unavailable
E/SELinux ( 6849): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityThread( 6838): Added TimaKeyStore provider,
I/ActivityManager( 1014): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6849 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 5826:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,I/ActivityManager( 1014): Killing 6072:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6849): TimaSignature is unavailable
,D/ActivityThread( 6849): Added TimaKeyStore provider
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RCPManagerService( 1014): PackageReceiver onReceive()
,I/HarmonyEASService( 1014): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1014): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1014): PackageRemovalReceiver::onReceive Enter
,D/OTPFW   ( 1014): OtpDbHelper::getInstance New instance created
,D/OTPFW   ( 1014): DBIntegrity::getInstance - New instance created
,D/OTPFW   ( 1014): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10175 container id = 0
,I/OTPFW   ( 1014): ProvisionData::getAllEntries Enter
,E/OTPFW   ( 1014): ProvisionData::getAllEntries Table is empty
,D/BackupManagerService( 1014): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1014): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1014): uID is 10175
V/EnterpriseBillingPolicy( 1014): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - end - null
,I/TapandpayWidget:TapandpayAppWidgetProvider( 6838): onReceive()
,D/TapandpayWidget:TapandpayAppWidgetProvider( 6838): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/WindowOrientationListener( 1014):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1014): uID is 10175
V/EnterpriseBillingPolicy( 1014): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - end - null
,D/WallpaperManagerService( 1014):  force update = false; persona id = 0; current user =0; current persona = 0
D/SSRM:aZ ( 1014): MSG_TYPE_APP_REMOVED::
D/KnoxTimeoutHandler( 1014): handleHomeShow for 0 and current 0
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
,D/TaskPersister( 1014): removeObsoleteFile: deleting file=2_task.xml
V/AlarmManagerEXT( 1014): com.test.thalitest(10175) is removed.
D/PackageManager( 1014): delete codoeFile: 
,D/AASAuninstall( 1014): userId = 0, info.removedAppID = -1, info.uid = 10175, packageName = com.test.thalitest
,I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
,I/AASA_removePackage( 1014): UID=10175 Target=com.test.thalitest
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager( 1014): result of delete: 1{981687525}
,I/TapandpayWidget:Utils( 6838): Clear T&P info.
,I/PCWCLIENTTRACE_PushUtil( 5741): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5741): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5741): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5741): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
W/ContextImpl( 6849): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1014): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 1014): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1014): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 6870): MountEmulatedStorage()
E/Zygote  ( 6870): v2
I/libpersona( 6870): KNOX_SDCARD checking this for 10032
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/libpersona( 6870): KNOX_SDCARD not a persona
,I/SELinux ( 6870): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1014): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6870 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a,
I/SELinux ( 6870): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6870): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TapandpayWidget:TapandpayAppWidgetProvider( 6838): Widget is not attached.
D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/AndroidRuntime( 6723): Shutting down VM,
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/ContactProvider( 6748): getAllContactInfoList Start
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 6886): MountEmulatedStorage()
E/Zygote  ( 6886): v2
I/libpersona( 6886): KNOX_SDCARD checking this for 10160
I/libpersona( 6886): KNOX_SDCARD not a persona
,I/SELinux ( 6886): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/TimaKeyStoreProvider( 6870): TimaSignature is unavailable
I/SELinux ( 6886): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
D/ActivityThread( 6870): Added TimaKeyStore provider
E/SELinux ( 6886): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1014): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=6886 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/ActivityManager( 1014): Killing 6094:com.samsung.helphub/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6886): TimaSignature is unavailable
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ActivityThread( 6886): Added TimaKeyStore provider
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/Choreographer( 1476): Skipped 32 frames!  The application may be doing too much work on its main thread.
,D/Launcher.Model( 1476): reloadBadges entered.
,I/Timeline( 1476): Timeline: Activity_idle id: android.os.BinderProxy@21f9c154 time:302649
,E/Zygote  ( 6901): MountEmulatedStorage()
E/Zygote  ( 6901): v2
I/libpersona( 6901): KNOX_SDCARD checking this for 1000
I/libpersona( 6901): KNOX_SDCARD not a persona
,I/SELinux ( 6901): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6901): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6901 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
E/SELinux ( 6901): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/CrashAnrDetector( 1014): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 1014): clearDefaults: com.test.thalitest
D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/libprocessgroup( 1014): failed to open /acct/uid_10053/pid_5951/cgroup.procs: No such file or directory
,I/ActivityManager( 1014): Killing 6268:com.android.email/u0a145 (adj 15): empty #31
,W/libprocessgroup( 1014): failed to open /acct/uid_10057/pid_5972/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10038/pid_5887/cgroup.procs: No such file or directory
,W/ResourcesManager( 6886): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/libprocessgroup( 1014): failed to open /acct/uid_10091/pid_5826/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10100/pid_6072/cgroup.procs: No such file or directory
,I/PackagesMonitor( 6748): PackagesMonitor onReceive :com.test.thalitest
,D/TimaKeyStoreProvider( 6901): TimaSignature is unavailable
,D/ActivityThread( 6901): Added TimaKeyStore provider
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,D/[0]UMC:UMCContentProvider( 6886): @onCreate
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6901): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 6917): MountEmulatedStorage()
,E/Zygote  ( 6917): v2
I/libpersona( 6917): KNOX_SDCARD checking this for 10046
I/libpersona( 6917): KNOX_SDCARD not a persona
,I/SELinux ( 6917): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6917): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6917): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=6917 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 6449:com.sec.android.cloudagent/u0a2 (adj 15): empty #31
,D/ContactProvider( 6748): getAllContactInfoList End
,I/syncContacts( 6748): thread: 1153, sync time = 223
D/[0]UMC:Core( 6886): onCreate(): 
D/[0]UMC:Core( 6886): @isManagedProfileUser
D/[0]UMC:Core( 6886): userId: 0
,D/[0]UMC:Core( 6886): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 6886): userInfo.isManagedProfile() : false
,D/RCPManager( 6901):  in createShortcut() for packageName: com.test.thalitest userId0
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_6094/cgroup.procs: No such file or directory
,D/RCPManagerService( 1014):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1014): queryAllProviders():  providerCallBack is not register for 0
,I/FeatureConfig( 6870): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/TimaKeyStoreProvider( 6917): TimaSignature is unavailable
,D/ActivityThread( 6917): Added TimaKeyStore provider
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/[0]UMC:DeviceInfo( 6886): USA==US==
,E/Zygote  ( 6935): MountEmulatedStorage()
W/ResourcesManager( 6870): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
E/Zygote  ( 6935): v2
W/ResourcesManager( 6870): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/libpersona( 6935): KNOX_SDCARD checking this for 10091
I/libpersona( 6935): KNOX_SDCARD not a persona
,I/SELinux ( 6935): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1014): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6935 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6935): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,W/ResourcesManager( 6870): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6870): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
E/SELinux ( 6935): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1014): Killing 6365:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/art     ( 6723): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/TimaKeyStoreProvider( 6935): TimaSignature is unavailable
,D/ActivityThread( 6935): Added TimaKeyStore provider
,W/libprocessgroup( 1014): failed to open /acct/uid_10145/pid_6268/cgroup.procs: No such file or directory
,I/PowerManagerService( 1014): [PWL] Off : 225s ago
,W/ResourcesManager( 6917): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6917): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6917): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6917): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6917): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.,
W/ResourcesManager( 6917): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6870): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.,
W/ResourcesManager( 6870): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/ActivityManager( 1014): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6951 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 6406:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,E/Zygote  ( 6951): MountEmulatedStorage()
I/libpersona( 6951): KNOX_SDCARD checking this for 10035
E/Zygote  ( 6951): v2
I/libpersona( 6951): KNOX_SDCARD not a persona
,I/SELinux ( 6951): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6951): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6951): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 6870): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6870): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6870): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6870): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6951): TimaSignature is unavailable
,D/Mms/MmsApp( 6917): [start]    onCreate() consume time = 0.0
,D/ActivityThread( 6951): Added TimaKeyStore provider
,D/USER_AGENT( 6886): UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
,D/[0]UMC:AdminManager( 6886): init - start
,W/ResourcesManager( 6870): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6870): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/[0]UMC:AdminManager( 6886): loadAdmins
,E/SQLiteLog( 6767): (284) automatic index on crash_info_summary(package_name_touched)
,W/libprocessgroup( 1014): failed to open /acct/uid_10002/pid_6449/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_6365/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10159/pid_6406/cgroup.procs: No such file or directory
,E/SQLiteLog( 5920): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 5920): (3850) statement aborts at 28: [UPDATE apps SET badgecount=? WHERE package=? AND class=?] disk I/O error
,E/DatabaseUtils( 5920): Writing exception to parcel
E/DatabaseUtils( 5920): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DatabaseUtils( 5920): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DatabaseUtils( 5920): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/DatabaseUtils( 5920): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DatabaseUtils( 5920): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DatabaseUtils( 5920): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1714)
E/DatabaseUtils( 5920): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1660)
E/DatabaseUtils( 5920): 	at com.sec.android.provider.badge.BadgeProvider.update(BadgeProvider.java:170)
E/DatabaseUtils( 5920): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
E/DatabaseUtils( 5920): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:222)
E/DatabaseUtils( 5920): 	at android.os.Binder.execTransact(Binder.java:461)
,D/[0]UMC:AdminManager( 6886): init - end
,D/GSLBManager( 6886): migrateStoredUrlFromOldPref
,W/ResourcesManager( 6870): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6870): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
,E/SPPClientService( 6951): ============PushLog. commonIsShipBuild. stop!
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/SPPClientService( 6951): [PushClientApplication] Push log off : This is Ship build version
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/GSLBManager( 6886): migrateStoredUrlFromOldPref : Migration Not Needed
,D/[0]UMC:UMCAdmin( 6886): deactivateUMCAdminIfNotRequired : -1,
,E/[0]UMC:Utils( 6886): Admin not found in package com.samsung.knoxpb.mdm,
E/[0]UMC:Utils( 6886): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
,D/[0]UMC:UMCAdmin( 6886): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 6886): isContainer : 0
E/PhotosPlugin( 6935): Loading PhotosPlugin,
,D/EnterpriseDeviceManagerService( 1014): isManagedProfileUser(): userId = 0
,W/ResourcesManager( 6870): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6870): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/Zygote  ( 6970): MountEmulatedStorage()
E/Zygote  ( 6970): v2
I/libpersona( 6970): KNOX_SDCARD checking this for 10038
I/libpersona( 6970): KNOX_SDCARD not a persona
I/SELinux ( 6970): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6970): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/SPPClientService( 6951): PushLog.txt file is not deleted.
E/SELinux ( 6970): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/SPPClientService( 6951): PushLog.txt file is not deleted.
D/SPPClientService( 6951): ============PushLog. stop!
,I/ActivityManager( 1014): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=6970 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 6280:com.android.chrome/u0a81 (adj 15): empty #31
,E/[0]UMC:UMCAdmin( 6886): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 6886): isContainer : 0
,E/SQLiteLog( 6951): (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131138) and mode_t (0) due to error (30)

```
