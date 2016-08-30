#### Test 83243049e1001da_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
08-30 12:37:32.706  1681  1696 I art     : Explicit concurrent mark sweep GC freed 11699(563KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 8MB/13MB, paused 1.037ms total 44.864ms
--------- beginning of system
08-30 12:37:32.716  1016  1332 I ActivityManager: Killing 6188:com.google.android.music:main/u0a108 (adj 15): empty #21
08-30 12:37:32.726  1016  1487 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:37:32.726  1016  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:32.726  1016  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
08-30 12:37:32.726  1016  1487 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-30 12:37:32.736  6496  6557 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 415 ms] updated apps [took 415 ms] 
08-30 12:37:32.736  1016  1028 I ActivityManager: Killing 6389:com.sec.android.app.videoplayer/u0a45 (adj 15): empty #21
08-30 12:37:32.746  6529  6529 D ComposerPerformance: 1472553452758 ms / [DONE] Composer constructor
08-30 12:37:32.756  6529  6529 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
08-30 12:37:32.756  6529  6529 I Mms/ReservationManager: ReservationManager()
08-30 12:37:32.756  6529  6529 I Mms/ReservationManager: resetAfterConnected()
08-30 12:37:32.756  6529  6739 D Mms/Conversation: [start]    init() consume time = 96.101354
08-30 12:37:32.766  1460  1484 D TP/MmsSmsProvider: query,matched:7, calling pid = 6529
08-30 12:37:32.766  1460  1484 D TP/MmsSmsProvider: match 7:Elapsed time : 1.544 ms
08-30 12:37:32.766  1460  2494 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-30 12:37:32.766  1460  2494 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-30 12:37:32.766  1460  2494 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
08-30 12:37:32.766  1460  2494 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
08-30 12:37:32.776  1460  2494 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-30 12:37:32.776  1460  2494 D TP/MmsSmsProvider: need read changed broadcast:false
08-30 12:37:32.776  6529  6739 D Mms/Conversation: [end]    init consume time = 21.411042
08-30 12:37:32.786  6529  6739 D Mms/MessagingNotification: [start]    init() consume time = 4.185677
08-30 12:37:32.786  6529  6529 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
08-30 12:37:32.786  6529  6529 D Mms/MmsApp: [end]    onCreate() consume time = 4.455417
08-30 12:37:32.786  6529  6739 D Mms/MessagingNotification: [end]    init consume time = 2.436406
,08-30 12:37:32.796  6529  6529 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
08-30 12:37:32.796  6529  6529 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
08-30 12:37:32.796  6529  6529 D Mms/MethodReflector: getSubId is called
08-30 12:37:32.796  6529  6529 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-30 12:37:32.796  6529  6529 D Mms/MethodReflector: getTelephonyProperty is called
08-30 12:37:32.796  6529  6529 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-30 12:37:32.796  6529  6529 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-30 12:37:32.796  6529  6529 D Mms/DownloadManager: auto download without roaming -> true
08-30 12:37:32.796  6529  6529 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-30 12:37:32.796  6529  6529 D Mms/DownloadManager: mAutoDownload ------> true
08-30 12:37:32.796  1460  1638 D TP/MmsSmsProvider: query,matched:0, calling pid = 6529
08-30 12:37:32.796  1460  1638 V TP/MmsSmsProvider: getSimpleConversations entered.
08-30 12:37:32.796  1460  1638 D TP/MmsSmsProvider: match 0:Elapsed time : 2.006 ms
08-30 12:37:32.806  6529  6743 D Mms/Synchronizer: [start]    doSync consume time = 13.593177
08-30 12:37:32.806  1460  2494 D TP/MmsSmsProvider: update, matched:300, calling pid = 6529
08-30 12:37:32.806  1460  2494 V TP/MmsSmsProvider: syncDBData start
08-30 12:37:32.816  1460  2494 V TP/MmsSmsProvider: syncDBData sms end
08-30 12:37:32.816  6529  6742 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 11.950885
08-30 12:37:32.816  1016  1770 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
08-30 12:37:32.816  6529  6529 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
08-30 12:37:32.816  1460  1484 D TP/MmsSmsProvider: query,matched:400, calling pid = 6529
08-30 12:37:32.816  1016  1770 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:32.816  1016  1770 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:32.826  1460  2494 V TP/MmsSmsProvider: syncDBData mms end
08-30 12:37:32.826  1460  2494 V TP/MmsSmsProvider: syncDBData end
08-30 12:37:32.826  1016  1770 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:32.826  1016  1770 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:32.836  6529  6673 D Mms/ArtClassLoader: init [DONE] art
08-30 12:37:32.836  6744  6744 I libpersona: KNOX_SDCARD checking this for 10068
08-30 12:37:32.836  6744  6744 E Zygote  : MountEmulatedStorage()
08-30 12:37:32.836  6744  6744 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:32.836  6744  6744 E Zygote  : v2
08-30 12:37:32.836  6744  6744 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 12:37:32.846  6744  6744 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 12:37:32.846  6744  6744 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-30 12:37:32.856  1016  1770 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6744 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-30 12:37:32.856  1016  1333 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-30 12:37:32.856  1016  1333 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
08-30 12:37:32.856  1016  1333 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:37:32.856  1016  1333 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 12:37:32.856  1016  1333 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
08-30 12:37:32.856  1016  1749 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
08-30 12:37:32.866  1016  1749 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:32.866  1016  1749 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:32.866  1016  1749 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:32.866  1016  1749 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:32.876  6529  6756 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
08-30 12:37:32.876  6529  6756 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
08-30 12:37:32.886  6744  6744 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:32.886  6744  6744 D ActivityThread: Added TimaKeyStore provider
08-30 12:37:32.896   293   293 E SMD     : DCD OFF
08-30 12:37:32.896  1016  1213 E EdmStorageProvider: Admin not in database, something went wrong
08-30 12:37:32.896  6762  6762 E Zygote  : MountEmulatedStorage()
08-30 12:37:32.896  6762  6762 I libpersona: KNOX_SDCARD checking this for 10042
08-30 12:37:32.896  6762  6762 E Zygote  : v2
08-30 12:37:32.896  6762  6762 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:32.896  1016  1749 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6762 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
08-30 12:37:32.896  6762  6762 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 12:37:32.896  6762  6762 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 12:37:32.896  6762  6762 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
08-30 12:37:32.896  6529  6743 D Mms/Synchronizer: [end]    doSync consume time = 86.919115
08-30 12:37:32.906  6529  6742 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 3.509479
08-30 12:37:32.906  1016  4749 I ActivityManager: Killing 6370:com.android.defcontainer/u0a3 (adj 15): empty #21
08-30 12:37:32.906  1016  4749 I ActivityManager: Killing 6286:com.android.calendar/u0a131 (adj 15): empty #22
08-30 12:37:32.926  6762  6762 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:32.926  6762  6762 D ActivityThread: Added TimaKeyStore provider
08-30 12:37:32.956  6762  6762 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 12:37:32.956  6762  6762 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-30 12:37:32.956  6762  6762 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-30 12:37:32.976  6744  6744 D BadgeProvider: onCreate
08-30 12:37:32.976  6744  6744 D BadgeProvider: DatabaseHelper
08-30 12:37:32.996  6529  6739 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
08-30 12:37:33.016  1460  1480 D TP/SmsProvider: query,matched:26, calling pid = 6529
08-30 12:37:33.016  1460  1480 D TP/SmsProvider: match 26:Elapsed time : 1.747 ms
08-30 12:37:33.046  1460  2494 D TP/MmsSmsProvider: query,matched:6, calling pid = 6529
08-30 12:37:33.046  1460  2494 D TP/MmsSmsProvider: match 6:Elapsed time : 1.057 ms
08-30 12:37:33.066  6762  6762 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-30 12:37:33.066  1016  1056 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
08-30 12:37:33.066  1016  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-30 12:37:33.076  1016  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:33.076  1016  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:33.076  1016  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:33.076  1016  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:33.086  6754  6754 D AndroidRuntime: 
08-30 12:37:33.086  6754  6754 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 12:37:33.086  6754  6754 D AndroidRuntime: CheckJNI is OFF
08-30 12:37:33.086  6754  6754 D AndroidRuntime: readGMSProperty: start
08-30 12:37:33.086  6754  6754 D AndroidRuntime: readGMSProperty: already setted!!
08-30 12:37:33.086  6754  6754 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 12:37:33.086  6754  6754 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 12:37:33.086  6754  6754 D AndroidRuntime: readGMSProperty: end
08-30 12:37:33.086  6754  6754 D AndroidRuntime: addProductProperty: start
08-30 12:37:33.086  1016  1056 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6777 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-30 12:37:33.086  1016  1770 I ActivityManager: Killing 6142:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
08-30 12:37:33.096  6777  6777 E Zygote  : MountEmulatedStorage()
08-30 12:37:33.096  6777  6777 E Zygote  : v2
08-30 12:37:33.096  6777  6777 I libpersona: KNOX_SDCARD checking this for 10003
08-30 12:37:33.096  6777  6777 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:33.096  6777  6777 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 12:37:33.106  6777  6777 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 12:37:33.106  1016  1253 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
08-30 12:37:33.106  6777  6777 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 12:37:33.136  1016  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:33.136  1016  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:33.136  1016  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:33.136  1016  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:33.146  6793  6793 E Zygote  : MountEmulatedStorage()
08-30 12:37:33.146  6793  6793 E Zygote  : v2
08-30 12:37:33.146  6793  6793 I libpersona: KNOX_SDCARD checking this for 10023
08-30 12:37:33.146  6793  6793 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:33.146  6793  6793 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 12:37:33.156  1016  1253 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6793 uid=10023 gids={50023, 9997} abi=armeabi-v7a
08-30 12:37:33.156  6777  6777 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:33.156  6777  6777 D ActivityThread: Added TimaKeyStore provider
08-30 12:37:33.156  1016  1029 I art     : Explicit concurrent mark sweep GC freed 148318(8MB) AllocSpace objects, 5(1928KB) LOS objects, 33% free, 23MB/34MB, paused 2.887ms total 201.242ms
08-30 12:37:33.156  6793  6793 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 12:37:33.156  6793  6793 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 12:37:33.196  6793  6793 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:33.196  6793  6793 D ActivityThread: Added TimaKeyStore provider
08-30 12:37:33.206  1016  1486 I ActivityManager: Killing 6430:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
08-30 12:37:33.216   288   288 E installd: system dir 0 : /system/app/
08-30 12:37:33.216   288   288 E installd: system dir 1 : /system/priv-app/
08-30 12:37:33.216   288   288 E installd: system dir 2 : /vendor/app/
08-30 12:37:33.216   288   288 E installd: system dir 3 : /oem/app/
08-30 12:37:33.216  1016  1029 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-30 12:37:33.256  6754  6754 E AffinityControl: AffinityControl: registerfunction enter
08-30 12:37:33.286  6793  6793 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
08-30 12:37:33.286  6754  6754 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 12:37:33.296  6529  6739 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
08-30 12:37:33.306  1016  1028 E PersonaManagerService: inState():  stateMachine is null !!
08-30 12:37:33.306  1016  1056 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-30 12:37:33.316  1016  1028 I PersonaManagerService: PersonaId don't exist
08-30 12:37:33.316  1016  1028 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-30 12:37:33.316  1016  1028 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-30 12:37:33.326  6793  6793 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
08-30 12:37:33.326  6793  6793 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-30 12:37:33.326  6793  6793 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
08-30 12:37:33.336  6793  6793 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
08-30 12:37:33.336  6793  6793 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
08-30 12:37:33.336  1016  1028 W ActivityManager: mDVFSHelper.acquire()
08-30 12:37:33.336  6793  6793 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
08-30 12:37:33.346  6793  6793 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
08-30 12:37:33.346  6793  6793 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
08-30 12:37:33.346  1016  1028 D FocusedStackFrame: Set to : 0
08-30 12:37:33.346  6793  6793 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
08-30 12:37:33.346  6793  6793 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
08-30 12:37:33.346  6793  6793 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
08-30 12:37:33.346  6793  6793 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
08-30 12:37:33.346  6793  6793 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
08-30 12:37:33.366  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:33.366  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:33.366  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:33.366  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:33.366  1016  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-30 12:37:33.366  1016  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-30 12:37:33.386  1862  6576 W art     : Verification of void com.google.android.gms.games.broker.GameAgent.addGameBadgeOps(com.google.android.gms.common.internal.ClientContext, com.google.android.gms.games.server.api.MarketInstance, java.lang.String, java.util.ArrayList, int) took 133.184ms
08-30 12:37:33.386  6820  6820 E Zygote  : MountEmulatedStorage()
08-30 12:37:33.386  6820  6820 E Zygote  : v2
08-30 12:37:33.386  6820  6820 I libpersona: KNOX_SDCARD checking this for 10170
08-30 12:37:33.386  6820  6820 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:33.386  6820  6820 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 12:37:33.386  1016  1028 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6820 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 12:37:33.386  1016  1028 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-30 12:37:33.386  1016  1028 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-30 12:37:33.386  1016  1028 D InputDispatcher: Focused application set to: xxxx
08-30 12:37:33.386  1016  1028 D InputDispatcher: Focus left window: 1488
08-30 12:37:33.386  6820  6820 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 12:37:33.386  6820  6820 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-30 12:37:33.396  6754  6754 D AndroidRuntime: Shutting down VM
08-30 12:37:33.396  1016  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-30 12:37:33.396  1016  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-30 12:37:33.396   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-30 12:37:33.416  6820  6820 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:33.416  6820  6820 D ActivityThread: Added TimaKeyStore provider
08-30 12:37:33.416  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 12:37:33.416  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 12:37:33.426  1016  1254 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-30 12:37:33.426  1016  1016 V ActivityManager: Display changed displayId=0
08-30 12:37:33.426  1016  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-30 12:37:33.446  1016  1254 D PersonaManager: isKioskContainerExistOnDevice
08-30 12:37:33.466  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-30 12:37:33.486   257   455 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
08-30 12:37:33.486   257   455 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-30 12:37:33.496  1488  1488 V ActivityThread: updateVisibility : ActivityRecord{20fd7beb token=android.os.BinderProxy@3535df41 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-30 12:37:33.496  1488  1488 D Launcher: onTrimMemory. Level: 20
08-30 12:37:33.506  6637  6692 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-30 12:37:33.506  6637  6692 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 12:37:33.506  6637  6692 I GAv4    :   adb logcat -s GAv4
08-30 12:37:33.536  6637  6692 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-30 12:37:33.546  1016  1253 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-30 12:37:33.576  6637  6692 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
08-30 12:37:33.576  6820  6820 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-30 12:37:33.596  6754  6754 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-30 12:37:33.606  6637  6692 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
08-30 12:37:33.606  6820  6820 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 5744-5747)
08-30 12:37:33.606  6820  6820 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-30 12:37:33.636  6820  6820 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {119e9ec9}
,08-30 12:37:33.636  6637  6837 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
08-30 12:37:33.636  6820  6820 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-30 12:37:33.646  6820  6820 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 12:37:33.696  6820  6820 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-30 12:37:33.696  6820  6820 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 12:37:33.706  6820  6820 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-30 12:37:33.726  6820  6820 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 12:37:33.726  6820  6820 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 12:37:33.726  6820  6820 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 12:37:33.726  6820  6820 I Adreno-EGL: Local Branch: 
08-30 12:37:33.726  6820  6820 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 12:37:33.726  6820  6820 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 12:37:33.726  6820  6820 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 12:37:33.756  1016  1333 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-30 12:37:33.756  1016  1333 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4187, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-30 12:37:33.756  1016  1333 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-30 12:37:33.756  1016  1333 D BatteryService: stay LED for charging
,08-30 12:37:33.756  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 12:37:33.766  1016  1016 I MotionRecognitionService: Plugged
,08-30 12:37:33.766  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 12:37:33.766  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-30 12:37:33.766  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 12:37:33.766  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-30 12:37:33.766  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-30 12:37:33.776  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-30 12:37:33.776  3197  3328 D HeadsetStateMachine: Disconnected process message: 10
,08-30 12:37:33.796  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-30 12:37:33.796  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-30 12:37:33.796  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-30 12:37:33.806  6820  6820 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 12:37:33.816  6820  6820 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-30 12:37:33.816  6820  6820 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-30 12:37:33.836  1862  4312 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
,08-30 12:37:33.836  6820  6820 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-30 12:37:33.836  6820  6820 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-30 12:37:33.856  1016  3705 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
,08-30 12:37:33.856  1016  3705 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:33.856  1016  3705 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:33.856  1016  3705 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:33.856  1016  3705 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:33.866  6862  6862 E Zygote  : MountEmulatedStorage()
08-30 12:37:33.866  6862  6862 E Zygote  : v2
08-30 12:37:33.866  6862  6862 I libpersona: KNOX_SDCARD checking this for 1000
08-30 12:37:33.866  6862  6862 I libpersona: KNOX_SDCARD not a persona
,08-30 12:37:33.866  6862  6862 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-30 12:37:33.866  1016  3705 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=6862 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-30 12:37:33.876  6862  6862 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 12:37:33.876  6862  6862 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 12:37:33.896  6862  6862 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 12:37:33.896  6862  6862 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:33.906  1862  4312 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-30 12:37:33.926  6862  6862 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
,08-30 12:37:33.926  6862  6862 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,08-30 12:37:33.926  1016  4757 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller,
08-30 12:37:33.926  1016  4757 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
,08-30 12:37:33.926  1016  4757 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:37:33.926  1016  4757 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 12:37:33.926  1016  4757 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,08-30 12:37:33.936  1016  1029 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-30 12:37:33.946  1016  1332 I ActivityManager: Killing 6446:com.sec.spp.push/u0a32 (adj 15): empty #21
,08-30 12:37:33.946  6862  6862 I FilterInstaller: FilterPackageService : ACTION_CHANGED
,08-30 12:37:33.956  1016  1042 W ActivityManager: Activity pause timeout for ActivityRecord{ee678ef u0 com.test.thalitest/.MainActivity t163}
,08-30 12:37:33.966  1016  1016 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
08-30 12:37:33.966  1016  1016 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,08-30 12:37:33.966  6862  6881 E FilterInstaller: installFilters
,08-30 12:37:33.966  1016  1392 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 12:37:33.966  6637  6860 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 12:37:33.966  6637  6860 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 12:37:33.976  1016  1392 D AlarmManagerService: Setting time of day to sec=1472553454
,08-30 12:37:33.976  1016  1392 D AlarmManagerService: Trying to open a file
,08-30 12:37:33.976  6862  6881 E FilterInstaller: There is no requred permission
08-30 12:37:33.976  1016  1392 D AlarmManagerService: File Open Success
08-30 12:37:33.976  1016  1392 D AlarmManagerService: File Close Success
08-30 12:37:33.976  1016  1392 I AlarmManagerService: DRM_TIME_PATH CHMOD 666 for resetState done 
08-30 12:37:34.088  1016  1094 V AlarmManager: waitForAlarm result :65536
08-30 12:37:34.088  1016  1392 W AlarmManagerService: Unable to set rtc to 1472553454: Invalid argument
,08-30 12:37:34.088  1016  1016 I BackgroundCompactionService: onStart. jobID=801
,08-30 12:37:34.088  1016  1016 I BackgroundCompactionService: onStart done. jobID=801
,08-30 12:37:34.088  1016  6882 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
,08-30 12:37:34.088  1016  6882 I BackgroundCompactionService: compact_memory command done
,08-30 12:37:34.097  1016  1094 V AlarmManager: No more alarm at this time.nowELAPSED=96135 batch.start=109417
,08-30 12:37:34.117  1016  1042 W ActivityManager: Failed to update preferences for: com.sec.spp.push
,08-30 12:37:34.127  6820  6820 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 12:37:34.137  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
,08-30 12:37:34.137  1174  1174 D KeyguardUpdateMonitor: handleTimeUpdate
,08-30 12:37:34.157  1174  1174 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-30 12:37:34.167  1174  1174 D SecKeyguardClockView: HomeTimezone(): 1
,08-30 12:37:34.177  1862  4312 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
,08-30 12:37:34.177  6820  6820 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 12:37:34.177  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-30 12:37:34.177  1174  1174 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_SET
,08-30 12:37:34.187  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-30 12:37:34.187  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-30 12:37:34.187  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,08-30 12:37:34.187  6637  6860 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...,
,08-30 12:37:34.197  1016  1016 D OTPFW   : OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1472553454200,
08-30 12:37:34.197  1016  1332 I ActivityManager: Killing 5030:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
,08-30 12:37:34.197  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-30 12:37:34.197  1016  1749 D SettingsProvider: name = lockscreen_zoom_panning_effect,
08-30 12:37:34.197  1016  1749 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 12:37:34.197  1016  1749 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 12:37:34.197  1016  1749 D SettingsProvider: selectionArgs: false
08-30 12:37:34.197  1016  1749 D SettingsProvider: selectionArgs: 10049
,08-30 12:37:34.197  1016  1749 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 12:37:34.197  1016  1749 D SettingsProvider: ret = -1
,08-30 12:37:34.207  1016  1016 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,08-30 12:37:34.207  1016  1016 I DowntimeConditions: android.intent.action.TIME_SET ignored because schedule turned off.
08-30 12:37:34.207  1016  1016 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 12:37:34.207  6820  6820 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-30 12:37:34.207  6820  6820 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-30 12:37:34.217  1174  1174 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
,08-30 12:37:34.217  6820  6820 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-30 12:37:34.227  1174  1174 D KeyguardEffectViewController: isPreloadedWallpaper=true
08-30 12:37:34.227  1174  1174 I GeometricMosaic_Keyguard: update
,08-30 12:37:34.227  1016  1016 I DrmEventService:  no response from SecureClock 
,08-30 12:37:34.227  1016  1016 I splitIntent: intent=android.intent.action.TIME_SET will be not split. because same process=com.google.android.gms is in other queue. index=4
08-30 12:37:34.227  1016  1016 I splitIntent: base  index=4, name=com.google.android.gms com.google.android.gms.checkin.CheckinService$Receiver
08-30 12:37:34.227  1016  1016 I splitIntent: other index=7, name=com.google.android.gms com.google.android.gms.reminders.notification.NotificationReceiver
08-30 12:37:34.227  1016  1016 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.TIME_SET !! do not split it!!
,08-30 12:37:34.227  1174  1174 D KeyguardEffectViewUtil: getCurrentWallpaper() mWallpaperPath :null
,08-30 12:37:34.237  1016  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-30 12:37:34.237  6820  6820 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 12:37:34.237  6820  6820 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 12:37:34.247  1016  1487 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:34.247  1016  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:34.247  1016  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:34.247  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-30 12:37:34.247  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:34.247  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:34.247  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:34.247  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:34.267  1016  1016 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6888 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 12:37:34.267  6888  6888 E Zygote  : MountEmulatedStorage()
08-30 12:37:34.267  6888  6888 I libpersona: KNOX_SDCARD checking this for 10008
08-30 12:37:34.267  6888  6888 E Zygote  : v2
08-30 12:37:34.267  6888  6888 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:34.277  6888  6888 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 12:37:34.277  6637  6860 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@338a73b4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-30 12:37:34.277  6637  6860 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-30 12:37:34.277  6888  6888 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 12:37:34.277  6637  6860 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-30 12:37:34.277  6888  6888 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-30 12:37:34.287  1016  1042 W ProcessCpuTracker: Skipping unknown process pid 6884
,08-30 12:37:34.297  6820  6897 D OpenGLRenderer: Render dirty regions requested: true,
,08-30 12:37:34.307  1016  1749 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-30 12:37:34.307  1016  1749 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-30 12:37:34.307  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
08-30 12:37:34.307  1016  1749 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-30 12:37:34.307  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-30 12:37:34.307  6820  6853 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-30 12:37:34.317  6820  6820 V ActivityThread: updateVisibility : ActivityRecord{149f35a9 token=android.os.BinderProxy@28105ee2 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-30 12:37:34.317  6888  6888 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 12:37:34.317  6888  6888 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:34.327  6820  6820 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-30 12:37:34.327  6820  6820 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-30 12:37:34.347   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-30 12:37:34.357  1174  1174 I KeyguardEffectViewUtil: set current wallpaper info
,08-30 12:37:34.367  1016  1333 D InputDispatcher: Focus entered window: 6820
08-30 12:37:34.367  1016  1028 D SettingsProvider: name = keyguard_current_wallpaper_type
08-30 12:37:34.367  1016  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 12:37:34.367  1016  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 12:37:34.367  1016  1028 D SettingsProvider: selectionArgs: false
08-30 12:37:34.367  1016  1028 D SettingsProvider: selectionArgs: 10049
,08-30 12:37:34.367  1016  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 12:37:34.367  1016  1028 D SettingsProvider: ret = -1
,08-30 12:37:34.367  1016  4757 D SettingsProvider: name = keyguard_current_wallpaper_file_path
,08-30 12:37:34.367  1016  4757 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 12:37:34.367  1016  4757 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 12:37:34.367  1016  4757 D SettingsProvider: selectionArgs: false
08-30 12:37:34.367  1016  4757 D SettingsProvider: selectionArgs: 10049
,08-30 12:37:34.367  1016  4757 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 12:37:34.367  1016  4757 D SettingsProvider: ret = -1
,08-30 12:37:34.367  1016  1254 D SettingsProvider: name = keyguard_current_wallpaper_res_id
08-30 12:37:34.367  1016  1254 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 12:37:34.367  1016  1254 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 12:37:34.367  1016  1254 D SettingsProvider: selectionArgs: false
08-30 12:37:34.367  1016  1254 D SettingsProvider: selectionArgs: 10049
08-30 12:37:34.367  1016  1254 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 12:37:34.367  1016  1254 D SettingsProvider: ret = -1
,08-30 12:37:34.367  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-30 12:37:34.377  6820  6820 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-30 12:37:34.377  6820  6897 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 12:37:34.377  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 12:37:34.377  1016  1749 I ActivityManager: Killing 6476:com.samsung.helphub/1000 (adj 15): empty #21
,08-30 12:37:34.387  6820  6897 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-30 12:37:34.387  6820  6897 D OpenGLRenderer: Enabling debug mode 0
,08-30 12:37:34.417  1016  1770 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-30 12:37:34.417  6888  6888 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-30 12:37:34.427  1016  6909 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 12:37:34.437  1016  1047 I ActivityManager: Displayed Component not be shown by security: +884ms (total +978ms)
08-30 12:37:34.437  1016  1047 W ActivityManager: mDVFSHelper.release()
08-30 12:37:34.437  1016  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{ee678ef u0 com.test.thalitest/.MainActivity t163} time:96479
,08-30 12:37:34.447  1174  1639 D TEST    : run!!!
,08-30 12:37:34.457  1174  1174 D PanelView: There is/are notification(s) 
,08-30 12:37:34.457   257  1415 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-30 12:37:34.457  6820  6820 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-30 12:37:34.457  6820  6820 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@28105ee2 time:96495
,08-30 12:37:34.457  1174  1639 I GeometricMosaic_Renderer: setBackgroundBitmap
08-30 12:37:34.457   257   451 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-30 12:37:34.507  1871  1871 I SamsungIME: getCurrentCandidateView
,08-30 12:37:34.537  6888  6888 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,08-30 12:37:34.557  1016  4749 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 12:37:34.557  1016  4749 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,08-30 12:37:34.557  1016  4749 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:37:34.557  1016  4749 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 12:37:34.557  1016  4749 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:34.587  1016  1213 I ActivityManager: Killing 6461:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,08-30 12:37:34.597  1016  1253 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 12:37:34.597  1016  1253 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,08-30 12:37:34.597  1016  1253 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:34.597  1016  1253 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:34.597  1016  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:37:34.607  6820  6820 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6820
,08-30 12:37:34.617  2794  2794 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Tue Aug 30 12:37:34 GMT+02:00 2016
,08-30 12:37:34.617  1016  4757 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-30 12:37:34.617  1016  4757 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-30 12:37:34.617  1016  4757 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:34.617  1016  4757 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 12:37:34.617  1016  4757 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-30 12:37:34.627  2794  2794 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-30 12:37:34.627  1016  1333 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-30 12:37:34.627  1016  1333 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:34.627  1016  1333 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:34.627  1016  1333 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:34.627  1016  1333 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:34.637  2794  2794 I KLMS-2.5.123: : KLMSIntentService(): onCreate(),
,08-30 12:37:34.637  2794  2794 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-30 12:37:34.647  6916  6916 E Zygote  : MountEmulatedStorage()
08-30 12:37:34.647  6916  6916 E Zygote  : v2
08-30 12:37:34.647  6916  6916 I libpersona: KNOX_SDCARD checking this for 10036
08-30 12:37:34.647  6916  6916 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:34.647  6916  6916 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 12:37:34.647  1016  1333 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=6916 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 12:37:34.647  6916  6916 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 12:37:34.647  6916  6916 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-30 12:37:34.647  2794  2794 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-30 12:37:34.667   318   318 I art     : Explicit concurrent mark sweep GC freed 8674(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 663us total 21.161ms
,08-30 12:37:34.667  1871  1871 D SamsungIME: Dismiss ExpandCandiate
,08-30 12:37:34.677  2794  6915 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,08-30 12:37:34.677  2794  6915 I KLMS-2.5.123: : KLMSIntentService(): TIME_CHANGED
,08-30 12:37:34.677  2794  6915 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().START : Tue Aug 30 12:37:34 GMT+02:00 2016
,08-30 12:37:34.687   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 669us total 17.084ms
,08-30 12:37:34.687  2794  6915 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().END
,08-30 12:37:34.687  6916  6916 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 12:37:34.687  6916  6916 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:34.687  2794  2794 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-30 12:37:34.697   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 16.517ms
,08-30 12:37:34.737  6916  6916 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@358dae91
,08-30 12:37:34.747  6916  6916 I SA      : [SSP] onCreated
,08-30 12:37:34.757  6916  6916 I SA      : [TPM] There is no property file
,08-30 12:37:34.757  6916  6916 I SA      : [SCU] isHaveSA() - false
,08-30 12:37:34.767  6916  6916 I SA      : [TPM] getModelProperty : null
,08-30 12:37:34.767  6916  6916 I SA      : [TPM] getCSCProperty : null
,08-30 12:37:34.767  6916  6916 I SA      : [DM] FLOATING AMOLED FEATURE: true
,08-30 12:37:34.767  6916  6916 I SA      : [DM] PRODUCT AMOLED FEATURE: false
,08-30 12:37:34.767  6916  6916 I SA      : [DM] TFT FEATURE: false
,08-30 12:37:34.777  6916  6916 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,08-30 12:37:34.777  6916  6916 I SA      : [DM] init START
,08-30 12:37:34.787  6916  6916 I SA      : [DM] This device is not a Vodafone
,08-30 12:37:34.787  6916  6916 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-30 12:37:34.787  6916  6916 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-30 12:37:34.787  6916  6916 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-30 12:37:34.787  6916  6916 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-30 12:37:34.787  6916  6916 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-30 12:37:34.787  6916  6916 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-30 12:37:34.787  6916  6916 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-30 12:37:34.797  6916  6916 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 12:37:34.797  6916  6916 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-30 12:37:34.797  6916  6916 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-30 12:37:34.797  6916  6916 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-30 12:37:34.797  6916  6916 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-30 12:37:34.797  6820  6820 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 12:37:34.807  6916  6916 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-30 12:37:34.807  6916  6916 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-30 12:37:34.807  6916  6916 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-30 12:37:34.807  6916  6916 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-30 12:37:34.807  6916  6916 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,08-30 12:37:34.807  6916  6916 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-30 12:37:34.807  6916  6916 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-30 12:37:34.807  6916  6916 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-30 12:37:34.807  6916  6916 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-30 12:37:34.817  6916  6916 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-30 12:37:34.817  6916  6916 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-30 12:37:34.817  6916  6916 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-30 12:37:34.817  6916  6916 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-30 12:37:34.817  6916  6916 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-30 12:37:34.817  6916  6916 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,08-30 12:37:34.817  6916  6916 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-30 12:37:34.817  6916  6916 I SA      : [SCU] isHaveSA() - false
,08-30 12:37:34.817  6916  6916 I SA      : support phone number id : false
08-30 12:37:34.817  6916  6916 I SA      : [DM] Supports Ref Jpn : true
,08-30 12:37:34.817  6916  6916 I SA      : [DM] init END
,08-30 12:37:34.857  1016  1487 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,08-30 12:37:34.857  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:34.857  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:34.857  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:34.857  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:34.867  6938  6938 E Zygote  : MountEmulatedStorage(),
,08-30 12:37:34.867  6938  6938 E Zygote  : v2
08-30 12:37:34.867  6938  6938 I libpersona: KNOX_SDCARD checking this for 10058
08-30 12:37:34.867  6938  6938 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:34.867  6938  6938 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 12:37:34.877  1016  1487 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6938 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 12:37:34.877  1016  1487 I ActivityManager: Killing 5449:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
08-30 12:37:34.877  6938  6938 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 12:37:34.877  6938  6938 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 12:37:34.887  1871  1871 I SamsungIME: getDebugLevel  : 0x4f4c
08-30 12:37:34.897  6529  6529 I Mms/MmsApp:  start initViewCache mms
,08-30 12:37:34.897  6529  6529 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1887.465312
08-30 12:37:34.897  6529  6529 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-30 12:37:34.917  6938  6938 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 12:37:34.917  6938  6938 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:34.987  6820  6911 D jxcore_app_log: JniHelper::setJavaVM(0xb7b682b0), pthread_self() = -1206959768
,08-30 12:37:34.997  1871  1871 I SamsungIME: getDebugLevel  : 0x4f4c
,08-30 12:37:34.997  6820  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 12:37:34.997  6820  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 12:37:34.997  6820  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 12:37:34.997  6820  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 12:37:34.997  6820  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 12:37:34.997  6820  6911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53e3cc7 added. We now have 1 listener(s)
,08-30 12:37:34.997  6938  6938 I ExternalOEMControlProvider: onCreate
,08-30 12:37:35.007  1871  1871 I SamsungIME: KeybaordView init() : load resources
,08-30 12:37:35.007  6820  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,08-30 12:37:35.007  6820  6911 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-30 12:37:35.007  6820  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 12:37:35.007  6820  6911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 12:37:35.017  6820  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 12:37:35.017  6820  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 12:37:35.017  6820  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 12:37:35.017  6820  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-30 12:37:35.017  6820  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 12:37:35.017  6820  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 12:37:35.017  6820  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 12:37:35.017  6820  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 12:37:35.017  6820  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 12:37:35.017  6820  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 12:37:35.017  6820  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 12:37:35.017  6820  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 12:37:35.017  6820  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 12:37:35.017  6820  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 12:37:35.017  6820  6911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd24492 added. We now have 1 listener(s)
,08-30 12:37:35.017  6820  6911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 12:37:35.027  1016  1486 I ActivityManager: Killing 6076:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-30 12:37:35.027  1664  1664 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,08-30 12:37:35.027  1664  1664 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-30 12:37:35.027  6820  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 12:37:35.027  6820  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 12:37:35.027  6820  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 12:37:35.027  6820  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 12:37:35.027  6820  6911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 12:37:35.037  1016  1213 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,08-30 12:37:35.037  1016  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:35.037  1016  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:35.037  1016  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:35.037  1016  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:35.057  1016  1213 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6956 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 12:37:35.057  6820  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:37:35.057  6956  6956 E Zygote  : MountEmulatedStorage()
08-30 12:37:35.057  6956  6956 I libpersona: KNOX_SDCARD checking this for 10081
08-30 12:37:35.057  6956  6956 E Zygote  : v2
08-30 12:37:35.057  6956  6956 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:35.057  6820  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
08-30 12:37:35.057  6938  6954 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
08-30 12:37:35.067  6956  6956 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 12:37:35.067  6956  6956 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 12:37:35.067  6956  6956 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 12:37:35.067  6820  6911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-30 12:37:35.077  6820  6911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:37:35.077  6820  6911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:37:35.077  6820  6911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:37:35.077  6820  6911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:37:35.077  6820  6911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:37:35.077  6820  6911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:37:35.077  6820  6911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:37:35.077  6820  6911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 12:37:35.077  6820  6911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 12:37:35.077  6820  6911 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:37:35.077  6820  6911 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 12:37:35.077  6820  6820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:37:35.077  6820  6820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:37:35.077  1871  1871 I SamsungIME: getCurrentKeyboard
08-30 12:37:35.077  1871  1871 I SamsungIME: getTextKeyboard
08-30 12:37:35.087  6529  6529 D AbsListView: Get MotionRecognitionManager
08-30 12:37:35.087  1016  1481 D MotionRecognitionService:  ssp status : false
08-30 12:37:35.097  6529  6529 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 199.751198
08-30 12:37:35.107  6956  6956 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:35.107  6956  6956 D ActivityThread: Added TimaKeyStore provider
08-30 12:37:35.117  6820  6820 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-30 12:37:35.117  1871  1871 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
08-30 12:37:35.127  6956  6956 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-30 12:37:35.127  6956  6956 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-30 12:37:35.127  6956  6956 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:37:35.147  6956  6956 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 12:37:35.147  6956  6956 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
08-30 12:37:35.207  6529  6529 D Mms/BubbleViewCache: fillCache bubble = 1
08-30 12:37:35.237  1016  1749 D SettingsProvider: name = next_alarm_formatted
08-30 12:37:35.237  1016  1749 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 12:37:35.237  1016  1749 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 12:37:35.237  1016  1749 D SettingsProvider: selectionArgs: false
08-30 12:37:35.237  1016  1749 D SettingsProvider: selectionArgs: 10081
08-30 12:37:35.247  1016  1749 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 12:37:35.247  1016  1749 D SettingsProvider: ret = -1
08-30 12:37:35.277   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb863b7c8
08-30 12:37:35.277   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-30 12:37:35.277   272   272 I rmt_storage: wakelock acquired: 1, error no: 42
08-30 12:37:35.277   272   299 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1201424248)
08-30 12:37:35.317   272   299 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-30 12:37:35.317   272   299 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-30 12:37:35.317   272   299 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1201424248) wakelock released: 1, error no: 0
08-30 12:37:35.317   272   299 I rmt_storage: 
08-30 12:37:35.327   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb863b7c8
08-30 12:37:35.347  6956  6956 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 100.535ms
08-30 12:37:35.447  1016  3705 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
08-30 12:37:35.447  1016  3705 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:35.447  1016  3705 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:35.447  1016  3705 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:35.447  1016  3705 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:35.467  6974  6974 E Zygote  : MountEmulatedStorage()
08-30 12:37:35.467  6974  6974 E Zygote  : v2
08-30 12:37:35.467  6974  6974 I libpersona: KNOX_SDCARD checking this for 10090
08-30 12:37:35.467  6974  6974 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:35.467  6974  6974 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 12:37:35.467  1016  3705 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6974 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
08-30 12:37:35.467  6508  6550 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
08-30 12:37:35.467  1016  3705 I ActivityManager: Killing 6496:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
08-30 12:37:35.467  6974  6974 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 12:37:35.467  6974  6974 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 12:37:35.487  6508  6550 I AcmsKeyStoreHelper: Key Store exist
08-30 12:37:35.487  6508  6550 I AcmsKeyStoreHelper: Hence loading the keystore file
08-30 12:37:35.487  6974  6974 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:35.497  6974  6974 D ActivityThread: Added TimaKeyStore provider
08-30 12:37:35.517  6974  6974 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
08-30 12:37:35.517  6974  6974 D elm:15121: ELMEngine.ELMEngine( context ).
08-30 12:37:35.517  6974  6974 D elm:15121: MDMBridge.setEnterpriseBridge()
08-30 12:37:35.517  1016  3705 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-30 12:37:35.517  1016  3705 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
08-30 12:37:35.527  1016  3705 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:37:35.527  1016  3705 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 12:37:35.527  1016  3705 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
08-30 12:37:35.527  6974  6974 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
08-30 12:37:35.527  1016  1487 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
08-30 12:37:35.527  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:35.537  6974  6974 D elm:15121: ElmAgentService : onCreate()
08-30 12:37:35.537  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:35.537  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:35.537  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:35.537  6974  6989 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
08-30 12:37:35.537  6508  6550 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
08-30 12:37:35.537  6508  6550 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-30 12:37:35.537  6508  6550 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-30 12:37:35.537  6508  6550 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-30 12:37:35.537  6508  6550 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-30 12:37:35.537  6508  6550 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
08-30 12:37:35.547  6508  6550 D AcmsCore: This is NOT a valid MirrorLink app
08-30 12:37:35.547  6508  6550 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-30 12:37:35.547  6508  6550 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-30 12:37:35.547  6508  6550 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-30 12:37:35.547  6508  6550 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
08-30 12:37:35.557  6974  6989 D elm:15121: ELMAgentService.listeningToTimeDateChanges( context, intent ).
08-30 12:37:35.557  6974  6974 D elm:15121: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
08-30 12:37:35.557  6974  6974 D elm:15121: ModuleBase.ModifySetAlarm()
08-30 12:37:35.557  6974  6974 D elm:15121: MDMBridge.getInstance()
08-30 12:37:35.557  6974  6974 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
08-30 12:37:35.557  6992  6992 E Zygote  : MountEmulatedStorage()
08-30 12:37:35.557  6992  6992 E Zygote  : v2
08-30 12:37:35.557  6992  6992 I libpersona: KNOX_SDCARD checking this for 10130
08-30 12:37:35.567  6992  6992 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:35.567  1016  1487 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6992 uid=10130 gids={50130, 9997} abi=armeabi-v7a
08-30 12:37:35.567  6992  6992 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 12:37:35.567  6974  6974 D elm:15121: ElmAgentService : onDestroy().
08-30 12:37:35.567  6992  6992 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 12:37:35.567  1016  3705 I ActivityManager: Killing 6560:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
08-30 12:37:35.567  6992  6992 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
08-30 12:37:35.577  6508  6508 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-30 12:37:35.577  6508  6508 D AcmsService: Enter onDestroy
08-30 12:37:35.577  6508  6508 I AcmsService: cleanUp(): inside service clean up
08-30 12:37:35.577  6508  6508 D AcmsCore: AcmsCore: inside DeInit
08-30 12:37:35.577  6508  6508 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
08-30 12:37:35.577  6508  6508 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
08-30 12:37:35.577  6508  6508 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-30 12:37:35.577  6508  6508 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-30 12:37:35.577  6508  6508 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
08-30 12:37:35.577  6508  6508 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-30 12:37:35.577  6508  6508 D AcmsService: killing acms process
08-30 12:37:35.577  6508  6508 I Process : Sending signal. PID: 6508 SIG: 9
08-30 12:37:35.597  6992  6992 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:35.597  6992  6992 D ActivityThread: Added TimaKeyStore provider
08-30 12:37:35.607  6992  6992 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 12:37:35.607  6992  6992 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
08-30 12:37:35.627  1016  1253 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
08-30 12:37:35.627  1016  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:35.627  1016  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:35.627  1016  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:35.627  1016  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:35.647  7007  7007 E Zygote  : MountEmulatedStorage()
08-30 12:37:35.647  7007  7007 E Zygote  : v2
08-30 12:37:35.647  7007  7007 I libpersona: KNOX_SDCARD checking this for 10131
08-30 12:37:35.647  7007  7007 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:35.647  7007  7007 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 12:37:35.647  7007  7007 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 12:37:35.647  1016  1253 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7007 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
08-30 12:37:35.647  7007  7007 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 12:37:35.647  1016  1253 I ActivityManager: Killing 6579:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
08-30 12:37:35.667  7007  7007 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:37:35.667  7007  7007 D ActivityThread: Added TimaKeyStore provider
08-30 12:37:35.687  1016  1333 I ActivityManager: Process ACMS.Process (pid 6508)(adj 0) has died(25,786)
08-30 12:37:35.687  7007  7007 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-30 12:37:35.687  7007  7007 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:37:35.687  7007  7007 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 12:37:35.717  1016  1254 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
08-30 12:37:35.717  1016  1254 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
08-30 12:37:35.727  1016  1254 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:37:35.727  1016  1254 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 12:37:35.727  1016  1254 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
08-30 12:37:35.737  1742  1753 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-30 12:37:35.747  1016  1487 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-30 12:37:35.747  1016  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-30 12:37:35.747  1016  1487 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:37:35.747  1016  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 12:37:35.747  1016  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-30 12:37:35.747  1016  1770 D ActivityManager: getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,08-30 12:37:35.757  1016  1770 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:35.757  1016  1770 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:35.757  1016  1770 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:35.757  1016  1770 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:35.767  7027  7027 E Zygote  : MountEmulatedStorage(),
08-30 12:37:35.767  7027  7027 E Zygote  : v2
08-30 12:37:35.767  7027  7027 I libpersona: KNOX_SDCARD checking this for 10037
08-30 12:37:35.767  7027  7027 I libpersona: KNOX_SDCARD not a persona,
08-30 12:37:35.767  7027  7027 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 12:37:35.767  7027  7027 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-30 12:37:35.767  7027  7027 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-30 12:37:35.767  1016  1770 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7027 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 12:37:35.767  1016  4748 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
08-30 12:37:35.767  1016  4748 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:35.767  1016  4748 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:35.767  1016  4748 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:35.767  1016  4748 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:35.787  7036  7036 E Zygote  : MountEmulatedStorage()
,08-30 12:37:35.787  7036  7036 E Zygote  : v2
08-30 12:37:35.787  7036  7036 I libpersona: KNOX_SDCARD checking this for 1000,
08-30 12:37:35.787  7036  7036 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 12:37:35.787  7036  7036 I libpersona: KNOX_SDCARD not a persona
,08-30 12:37:35.787  7036  7036 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 12:37:35.787  7036  7036 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 12:37:35.797  7027  7027 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 12:37:35.797  7027  7027 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:35.797  1016  4748 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.DateTimeChangedReceiver: pid=7036 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-30 12:37:35.817  7036  7036 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 12:37:35.817  7036  7036 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:35.827  7027  7027 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,08-30 12:37:35.847  7036  7036 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 12:37:35.847  7036  7036 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 12:37:35.847  7036  7036 D SecurityLogAgent: StateMachine : Current State = 1
,08-30 12:37:35.857  1016  1332 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,08-30 12:37:35.857  1016  1332 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:35.857  1016  1332 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:35.857  1016  1332 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:35.857  1016  1332 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:35.857  7027  7027 I CalendarProvider2: CalendarProvider2.onCreate() called
,08-30 12:37:35.867  7059  7059 E Zygote  : MountEmulatedStorage(),
08-30 12:37:35.867  7059  7059 E Zygote  : v2
08-30 12:37:35.867  7059  7059 I libpersona: KNOX_SDCARD checking this for 10153
08-30 12:37:35.867  7059  7059 I libpersona: KNOX_SDCARD not a persona
08-30 12:37:35.867  7059  7059 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 12:37:35.867  1016  1332 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=7059 uid=10153 gids={50153, 9997} abi=armeabi-v7a
08-30 12:37:35.867  7059  7059 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 12:37:35.867  1016  1332 I ActivityManager: Killing 6616:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,08-30 12:37:35.877  7059  7059 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 12:37:35.887  7059  7059 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 12:37:35.897  7059  7059 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:35.917  7059  7059 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-30 12:37:35.917  6820  6965 W jxcore-log: Initializing JXcore engine
08-30 12:37:35.917  6820  6965 W jxcore-log: JXcore engine is ready
,08-30 12:37:35.937  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,08-30 12:37:35.937  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:35.937  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:35.937  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:35.937  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:35.947  7077  7077 E Zygote  : MountEmulatedStorage(),
08-30 12:37:35.947  7077  7077 E Zygote  : v2
08-30 12:37:35.947  7077  7077 I libpersona: KNOX_SDCARD checking this for 1000
08-30 12:37:35.947  7077  7077 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 12:37:35.947  7077  7077 I libpersona: KNOX_SDCARD not a persona
,08-30 12:37:35.947  1016  1029 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7077 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-30 12:37:35.957  1016  1029 I ActivityManager: Killing 6637:com.google.android.apps.docs/u0a87 (adj 15): empty #21
08-30 12:37:35.957  7077  7077 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 12:37:35.957  7077  7077 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 12:37:35.967  1016  3705 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
08-30 12:37:35.967  1016  3705 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,08-30 12:37:35.977  1950  1950 E audit   : type=1400 msg=audit(1472553455.977:205): avc:  denied  { ioctl } for  pid=6965 comm="Thread-1280" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 12:37:35.977  1950  1950 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-30 12:37:35.977  1950  1950 E audit   : type=1300 msg=audit(1472553455.977:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9d2088f8 items=0 ppid=318 ppcomm=main pid=6965 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1280" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-30 12:37:35.977  1950  1950 E audit   : type=1320 msg=audit(1472553455.977:205): 
,08-30 12:37:35.977  1016  3705 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:37:35.977  1016  3705 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 12:37:35.977  1016  3705 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-30 12:37:35.977  7077  7077 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 12:37:35.987  7077  7077 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:35.987  6820  6965 W jxcore-log: Starting JXcore engine
08-30 12:37:35.997   293   293 E SMD     : DCD OFF
08-30 12:37:36.017  7077  7077 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1472553456025
08-30 12:37:36.017  7077  7077 D         : TimeServiceNative: User Time to be set is 1472553456026
08-30 12:37:36.017  7077  7077 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
08-30 12:37:36.017  7077  7077 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-30 12:37:36.017  7077  7077 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1472553456026
08-30 12:37:36.017   333   427 D QC-time-services: Daemon: Connection accepted:time_genoff
08-30 12:37:36.017  7077  7077 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-30 12:37:36.017   333  7095 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1472553456026
08-30 12:37:36.017   333  7095 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1472553456026, operation = 0
08-30 12:37:36.017   333  7095 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS1/25/71 4:20:24
08-30 12:37:36.017   333  7095 D QC-time-services: Daemon:Value read from RTC seconds = 36303624000
08-30 12:37:36.017   333  7095 D QC-time-services: Daemon:new time 1472553456026 
08-30 12:37:36.017   333  7095 D QC-time-services: Daemon: delta 1436249832026 genoff 1436249832026 
08-30 12:37:36.017   333  7095 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249832026 to memory
08-30 12:37:36.017   333  7095 D QC-time-services: Daemon:Opening File: /data/time/ats_2
08-30 12:37:36.017   333  7095 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-30 12:37:36.047   333  7095 D QC-time-services: Updating the TOD offset
08-30 12:37:36.047   333  7095 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249832026 to memory
08-30 12:37:36.047   333  7095 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-30 12:37:36.047   333  7095 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-30 12:37:36.047   333  7095 E QC-time-services: Daemon:Update to modem bit set
08-30 12:37:36.047   333  7095 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
08-30 12:37:36.047   333  7095 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120285032026
08-30 12:37:36.047  7077  7077 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
08-30 12:37:36.047   333   421 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
08-30 12:37:36.047   333   427 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
08-30 12:37:36.047  1016  1749 I ActivityManager: Killing 6600:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,08-30 12:37:36.057  1742  1742 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,08-30 12:37:36.057  1742  1742 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
08-30 12:37:36.057  1742  1742 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-30 12:37:36.107  6820  6965 W jxcore-log: Platform android
08-30 12:37:36.107  6820  6965 W jxcore-log: 
08-30 12:37:36.107  6820  6965 W jxcore-log: Process ARCH arm
08-30 12:37:36.107  6820  6965 W jxcore-log: 
,08-30 12:37:36.157  1016  1770 I art     : Explicit concurrent mark sweep GC freed 20344(1124KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 22MB/34MB, paused 2.524ms total 146.309ms
,08-30 12:37:36.167  1742  1742 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-30 12:37:36.167  1742  1742 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-30 12:37:36.177  1742  1742 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,08-30 12:37:36.177  1742  1742 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-30 12:37:36.177  1742  1742 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,08-30 12:37:36.177  1742  1742 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,08-30 12:37:36.177  1742  1742 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-30 12:37:36.177  1742  1742 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,08-30 12:37:36.177  1742  1742 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-30 12:37:36.177  1742  1742 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,08-30 12:37:36.187  1742  1742 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,08-30 12:37:36.187  1742  1742 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
08-30 12:37:36.187  1742  1742 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,08-30 12:37:36.187  1742  1742 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-30 12:37:36.187  1742  1742 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,08-30 12:37:36.197  1016  1487 I ActivityManager: Killing 6655:com.sec.pcw.device/1000 (adj 15): empty #21
,08-30 12:37:36.197  1742  1742 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,08-30 12:37:36.197  1742  1742 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,08-30 12:37:36.307  1016  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 12:37:36.327  6820  6965 I jxcore-log: JXcore Cordova bridge is ready!
08-30 12:37:36.327  6820  6965 I jxcore-log: 
,08-30 12:37:36.327  6820  6965 W jxcore-log: JXcore engine is started
,08-30 12:37:36.327  6820  6911 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 12:37:36.327  6820  6820 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 12:37:36.977  7027  7027 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,08-30 12:37:36.987  1016  1042 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:36.987  1016  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 12:37:36.987  1016  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,08-30 12:37:36.987  1016  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,08-30 12:37:36.987  1016  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:36.987  1016  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 12:37:36.987  1016  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-30 12:37:36.987  1016  1253 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:36.987  1016  1253 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 12:37:36.987  1016  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,08-30 12:37:36.997  1016  1332 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-30 12:37:36.997  1016  1332 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-30 12:37:36.997  1016  1332 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:36.997  1016  1332 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 12:37:36.997  1016  1332 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-30 12:37:37.007  1016  1749 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:37.007  1016  1749 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 12:37:37.007  1016  1749 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,08-30 12:37:37.007  1016  1029 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-30 12:37:37.007  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-30 12:37:37.007  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:37.007  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 12:37:37.007  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-30 12:37:37.017  1016  1486 I ActivityManager: Killing 6675:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,08-30 12:37:37.527  1681  1681 I ConfigService: onDestroy
,08-30 12:37:38.997   293   293 E SMD     : DCD OFF
,08-30 12:37:41.307  1016  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 12:37:41.327  1016  3345 D SSRM:n  : SIOP:: AP = 410
,08-30 12:37:41.997   293   293 E SMD     : DCD OFF
,08-30 12:37:43.457  1016  1056 D PackageManager: [MSG] MCS_UNBIND
,08-30 12:37:43.467  1016  1056 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-30 12:37:43.467  1016  1481 I ActivityManager: Killing 6021:com.android.vending/u0a26 (adj 15): empty #21
,08-30 12:37:43.907  1016  4749 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 12:37:43.907  1016  4749 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4246, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-30 12:37:43.907  1016  4749 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-30 12:37:43.907  1016  4749 D BatteryService: stay LED for charging
08-30 12:37:43.907  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 12:37:43.907  1016  1016 I MotionRecognitionService: Plugged
,08-30 12:37:43.907  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 12:37:43.917  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-30 12:37:43.917  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 12:37:43.917  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-30 12:37:43.917  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-30 12:37:43.927  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-30 12:37:43.937  3197  3328 D HeadsetStateMachine: Disconnected process message: 10,
,08-30 12:37:43.947  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
08-30 12:37:43.947  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-30 12:37:43.947  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-30 12:37:44.997   293   293 E SMD     : DCD OFF
,08-30 12:37:46.327  1016  1317 E Watchdog: !@Sync 3
,08-30 12:37:47.007   331   331 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-30 12:37:47.007   331   331 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-30 12:37:47.377  1016  1094 V AlarmManager: waitForAlarm result :4
08-30 12:37:47.377  1016  1094 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,08-30 12:37:47.387  1016  1094 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:47.387  1016  1094 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:37:47.387  1016  1094 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:47.387  1016  1094 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:37:47.397  1016  1094 I ActivityManager: Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7103 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 12:37:47.397  7103  7103 E Zygote  : MountEmulatedStorage()
08-30 12:37:47.397  7103  7103 E Zygote  : v2
08-30 12:37:47.397  7103  7103 I libpersona: KNOX_SDCARD checking this for 10026
08-30 12:37:47.397  7103  7103 I libpersona: KNOX_SDCARD not a persona
,08-30 12:37:47.407  7103  7103 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-30 12:37:47.407  7103  7103 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 12:37:47.407  7103  7103 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 12:37:47.427  7103  7103 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 12:37:47.427  7103  7103 D ActivityThread: Added TimaKeyStore provider
,08-30 12:37:47.507  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 12:37:47.517  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 12:37:47.547  7103  7103 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-30 12:37:47.557  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 12:37:47.637  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 12:37:47.637  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 12:37:47.647  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 12:37:47.647  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 12:37:47.657  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 12:37:47.657  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 12:37:47.657  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 12:37:47.657  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 12:37:47.657  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 12:37:47.657  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 12:37:47.667  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 12:37:47.667  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 12:37:47.667  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 12:37:47.667  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 12:37:47.667  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 12:37:47.667  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 12:37:47.677  7103  7103 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-30 12:37:47.687  7103  7103 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 12:37:47.687  7103  7103 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-30 12:37:47.707  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 12:37:47.717  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 12:37:47.717  7103  7103 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-30 12:37:47.757  7103  7103 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-30 12:37:47.757  1016  4749 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
08-30 12:37:47.757  1016  4749 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,08-30 12:37:47.757  1016  4749 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:37:47.757  1016  4749 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 12:37:47.757  1016  4749 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,08-30 12:37:47.757  7103  7139 D Ads     : Skipping gmscore version check
,08-30 12:37:47.767  1016  1332 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 12:37:47.767  1016  1332 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:37:47.767  1016  1332 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:37:47.767  1016  1332 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,08-30 12:37:47.797  7103  7103 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-30 12:37:47.797  7103  7103 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-30 12:37:47.987  7103  7136 D Finsky  : [1339] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,08-30 12:37:47.987  7103  7103 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-30 12:37:47.987  1016  1254 I ActivityManager: Killing 6712:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-30 12:37:47.997   293   293 E SMD     : DCD OFF
,08-30 12:37:50.997   293   293 E SMD     : DCD OFF,
,08-30 12:37:51.307  1016  1049 I PowerManagerService: [PWL] Off : 50s ago
,08-30 12:37:51.357  1016  3345 D SSRM:n  : SIOP:: AP = 400,
,08-30 12:37:52.007   331   331 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 12:37:53.007   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 12:37:53.947  1016  1253 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 12:37:53.957  1016  1253 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4251, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-30 12:37:53.957  1016  1253 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-30 12:37:53.957  1016  1253 D BatteryService: stay LED for charging
,08-30 12:37:53.957  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 12:37:53.957  1016  1016 I MotionRecognitionService: Plugged
,08-30 12:37:53.957  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 12:37:53.957  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-30 12:37:53.957  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate,
,08-30 12:37:53.957  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-30 12:37:53.957  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-30 12:37:53.967  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-30 12:37:53.967  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-30 12:37:53.967  3197  3328 D HeadsetStateMachine: Disconnected process message: 10
,08-30 12:37:53.977  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-30 12:37:53.977  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-30 12:37:54.007   293   293 E SMD     : DCD OFF
,08-30 12:37:54.017   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 12:37:54.317  6820  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 12:37:54.317  6820  6965 I jxcore-log: 
,08-30 12:37:54.317  6820  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 12:37:54.317  6820  6965 I jxcore-log: 
,08-30 12:37:54.327  6820  6965 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:37:54.327  6820  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:37:54.327  6820  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:37:54.327  6820  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:37:54.327  6820  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:37:54.327  6820  6965 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 12:37:54.327  6820  6965 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 12:37:54.327  6820  6965 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 12:37:54.327  6820  6965 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 12:37:54.327  6820  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 12:37:54.327  6820  6965 I jxcore-log: 
,08-30 12:37:54.337  6820  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 12:37:54.337  6820  6965 I jxcore-log: 
,08-30 12:37:54.787  6820  6965 I jxcore-log: Running unit tests,
08-30 12:37:54.787  6820  6965 I jxcore-log: 
08-30 12:37:54.787  6820  6965 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-30 12:37:54.787  6820  6965 I jxcore-log: Failed to execute UT.
08-30 12:37:54.787  6820  6965 I jxcore-log: ,
,08-30 12:37:54.787  6820  6965 I jxcore-log: Unit Test app is loaded,
08-30 12:37:54.787  6820  6965 I jxcore-log: 
,08-30 12:37:54.797  6820  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
08-30 12:37:54.797  6820  6965 I jxcore-log: 
,08-30 12:37:54.797  6820  6965 I jxcore-log: My device name is: samsung-SM-A300FU
08-30 12:37:54.797  6820  6965 I jxcore-log: 
,08-30 12:37:54.797  6820  6965 I jxcore-log: WARN testUtils: myNameCallback not set!
08-30 12:37:54.797  6820  6965 I jxcore-log: 
,08-30 12:37:54.807  6820  6820 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 12:37:55.017   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 12:37:56.017   331   331 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 12:37:56.107  5898  5898 D FactoryTest: Not factory mode
,08-30 12:37:56.107  5898  5898 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-30 12:37:56.107  5898  5898 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-30 12:37:56.107  5898  5898 D MTPRx   : still no open session command from host, so toast
,08-30 12:37:56.107  5898  5898 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 ,
08-30 12:37:56.107  5898  5898 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-30 12:37:56.107  5898  5898 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:118149
,08-30 12:37:56.117  1016  1213 E PersonaManagerService: inState():  stateMachine is null !!
08-30 12:37:56.117  1016  1213 I PersonaManagerService: PersonaId don't exist
08-30 12:37:56.117  1016  1213 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-30 12:37:56.117  1016  1213 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-30 12:37:56.117  1016  1213 W ActivityManager: userId = 0, bbcId = -10000,
08-30 12:37:56.117  1016  1213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 12:37:56.117  1016  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-30 12:37:56.127  1016  1213 W ActivityManager: mDVFSHelper.acquire(),
,08-30 12:37:56.137  1016  1213 D PersonaManager: isKioskContainerExistOnDevice
,08-30 12:37:56.147  1016  1213 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-30 12:37:56.147  1016  1213 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-30 12:37:56.147  1016  1213 D InputDispatcher: Focused application set to: xxxx
08-30 12:37:56.147  1016  1213 D InputDispatcher: Focus left window: 6820
,08-30 12:37:56.157  5898  5898 E MTPRx   : started activity for popup
,08-30 12:37:56.157  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 12:37:56.157  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 12:37:56.187  5898  5898 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-30 12:37:56.187  5898  5898 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-30 12:37:56.187  5898  5898 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-30 12:37:56.187  5898  5898 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 12:37:56.187  5898  5898 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 12:37:56.187  5898  5898 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 12:37:56.207  5898  5898 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-30 12:37:56.207  1016  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-30 12:37:56.207  1016  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-30 12:37:56.207  1016  1029 D InputDispatcher: Focused application set to: xxxx
,08-30 12:37:56.207  1016  1029 D InputDispatcher: Focus entered window: 6820
,08-30 12:37:56.217  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-30 12:37:56.217  1016  1253 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-30 12:37:56.217  1016  1253 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@6fa34b5 attribute=null, token = android.os.BinderProxy@132fd21d
,08-30 12:37:56.217  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 12:37:56.257  5898  5898 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-30 12:37:56.267  5898  5898 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-30 12:37:56.267  5898  5898 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-30 12:37:56.287  6820  6820 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-30 12:37:56.287  6820  6820 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-30 12:37:56.287  6820  6820 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-30 12:37:56.287  6820  6820 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-30 12:37:56.287  1016  1749 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-30 12:37:56.287  1016  1749 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-30 12:37:56.287  1016  1749 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-30 12:37:56.287  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-30 12:37:56.287  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
,08-30 12:37:56.307  6820  6820 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 12:37:56.307  6820  6820 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-30 12:37:56.307  6820  6820 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1509827e Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2e8f5112, 16908290=android.view.AbsSavedState$1@2e8f5112}, android:focusedViewId=100}]}]
08-30 12:37:56.307  6820  6820 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-30 12:37:56.307  6820  6820 V ActivityThread: updateVisibility : ActivityRecord{149f35a9 token=android.os.BinderProxy@28105ee2 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-30 12:37:56.307  6820  6820 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 12:37:56.307  6820  6820 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-30 12:37:56.307  6820  6820 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@28105ee2 time:118347
,08-30 12:37:56.317  1016  4749 D PersonaManager: isKioskContainerExistOnDevice
,08-30 12:37:57.007   293   293 E SMD     : DCD OFF
,08-30 12:37:57.017   331   331 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-30 12:37:58.057  6820  6965 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 12:37:58.057  6820  6965 I jxcore-log: 
,08-30 12:37:58.627  6820  6965 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 12:37:58.627  6820  6965 I jxcore-log: 
,08-30 12:37:58.657  6820  6965 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js,
08-30 12:37:58.657  6820  6965 I jxcore-log: 
,08-30 12:37:59.127  1016  1042 W ActivityManager: mDVFSHelper.release()
,08-30 12:37:59.997  1016  1094 V AlarmManager: waitForAlarm result :8
,08-30 12:38:00.007   293   293 E SMD     : DCD OFF
,08-30 12:38:00.427  6820  6965 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 12:38:00.427  6820  6965 I jxcore-log: 
,08-30 12:38:00.717  6820  6965 I jxcore-log: ERROR runTests: 
08-30 12:38:00.717  6820  6965 I jxcore-log: 
,08-30 12:38:00.717  6820  6965 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 12:38:00.717  6820  6965 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-30 12:38:00.717  6820  6965 I jxcore-log: WARN testUtils: logCallback not set!
08-30 12:38:00.717  6820  6965 I jxcore-log: 
,08-30 12:38:00.727  6820  6965 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',,
08-30 12:38:00.727  6820  6965 I jxcore-log:     _functionName: 'loadFile',
08-30 12:38:00.727  6820  6965 I jxcore-log:     _lineNumber: '26',
08-30 12:38:00.727  6820  6965 I jxcore-log:     _columnNumber: '11',
08-30 12:38:00.727  6820  6965 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 12:38:00.727  6820  6965 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 12:38:00.727  6820  6965 I jxcore-log:     _functionName: '',
08-30 12:38:00.727  6820  6965 I jxcore-log:     _lineNumber: '38',
08-30 12:38:00.727  6820  6965 I jxcore-log:     _columnNumber: '7',
,08-30 12:38:00.727  6820  6965 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 12:38:00.727  6820  6965 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 12:38:00.727  6820  6965 I jxcore-log:     _functionName: '',
08-30 12:38:00.727  6820  6965 I jxcore-log:     _lineNumber: '35',
08-30 12:38:00.727  6820  6965 I jxcore-log:     _columnNumber: '3',
08-30 12:38:00.727  6820  6965 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 12:38:00.727  6820  6965 I jxcore-log:   { _fileName: 'module.js',
08-30 12:38:00.727  6820  6965 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 12:38:00.727  6820  6965 I jxcore-log:     _lineNumber: '621',
08-30 12:38:00.727  6820  6965 I jxcore-log:     _columnNumber: '8',
,08-30 12:38:00.727  6820  6965 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 12:38:00.727  6820  6965 I jxcore-log:   { _fileName: 'module.js',
08-30 12:38:00.727  6820  6965 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 12:38:00.727  6820  6965 I jxcore-log:     _lineNumber: '651',
08-30 12:38:00.727  6820  6965 I jxcore-log:     _columnNumber: '1',
08-30 12:38:00.727  6820  6965 I jxcore-log:    
08-30 12:38:00.727  6820  6965 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 12:38:00.727  6820  6965 I jxcore-log: 
08-30 12:38:00.727  6820  6965 E jxcore-log: Error: ,
08-30 12:38:00.727  6820  6965 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 12:38:00.727  6820  6965 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-30 12:38:00.727  6820  6965 E jxcore-log: 
,08-30 12:38:01.017  7149  7149 D AndroidRuntime: ,
08-30 12:38:01.017  7149  7149 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-30 12:38:01.027  7149  7149 D AndroidRuntime: CheckJNI is OFF,
08-30 12:38:01.027  7149  7149 D AndroidRuntime: readGMSProperty: start,
08-30 12:38:01.027  7149  7149 D AndroidRuntime: readGMSProperty: already setted!!
08-30 12:38:01.027  7149  7149 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 12:38:01.027  7149  7149 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 12:38:01.027  7149  7149 D AndroidRuntime: readGMSProperty: end
08-30 12:38:01.027  7149  7149 D AndroidRuntime: addProductProperty: start
,08-30 12:38:01.167  7149  7149 E AffinityControl: AffinityControl: registerfunction enter
,08-30 12:38:01.197  7149  7149 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 12:38:01.207  1016  1486 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-30 12:38:01.207  1016  1486 D PackageManager: START PACKAGE DELETE: observer{951752379}
08-30 12:38:01.207  1016  1486 D PackageManager: pkg{<packageName>}
08-30 12:38:01.207  1016  1486 D PackageManager: user{0}
08-30 12:38:01.207  1016  1486 D PackageManager: caller{2000}
08-30 12:38:01.207  1016  1486 D PackageManager: flags{2}
,08-30 12:38:01.207  1016  1486 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-30 12:38:01.207  1016  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-30 12:38:01.207  1016  1486 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-30 12:38:01.207  1016  1486 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-30 12:38:01.207  1016  1486 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-30 12:38:01.207  1016  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-30 12:38:01.207  1016  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-30 12:38:01.207  1016  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
08-30 12:38:01.207  1016  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-30 12:38:01.217  1016  1056 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,08-30 12:38:01.217  1016  1042 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
08-30 12:38:01.217  1016  1042 I ActivityManager: Killing 6820:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-30 12:38:01.217  1016  1042 I ActivityManager:   Force finishing activity ActivityRecord{ee678ef u0 com.test.thalitest/.MainActivity t163}
,08-30 12:38:01.227  1016  1042 D InputDispatcher: Focus left window: 6820,
,08-30 12:38:01.227   257   455 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,08-30 12:38:01.227   257   451 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,08-30 12:38:01.237  1016  1042 D InputDispatcher: Focused application released
,08-30 12:38:01.237  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 12:38:01.237  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101,
,08-30 12:38:01.307  1016  3362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 12:38:01.377  1016  1056 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,08-30 12:38:01.387  1016  3345 D SSRM:n  : SIOP:: AP = 390
,08-30 12:38:01.397  1016  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-30 12:38:01.427  2810  2810 I art     : Explicit concurrent mark sweep GC freed 24451(1324KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 791us total 32.143ms
,08-30 12:38:01.427  6165  6165 I art     : Explicit concurrent mark sweep GC freed 13068(719KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 4MB/6MB, paused 645us total 36.381ms
,08-30 12:38:01.447  1016  1098 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 12:38:01.457  1626  1902 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.,
,08-30 12:38:01.467  1871  1871 E SamsungIME: mOCRHelper is null
,08-30 12:38:01.477  1016  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
08-30 12:38:01.477  1016  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-30 12:38:01.477  1016  1041 W TextServicesManagerService: no available spell checker services found
,08-30 12:38:01.477  2794  2794 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 30 12:38:01 GMT+02:00 2016
,08-30 12:38:01.487  1447  1447 D PersonaManager: isKioskContainerExistOnDevice
,08-30 12:38:01.497  1016  1123 V NetworkStats: removeUidsLocked() for UIDs [10170]
08-30 12:38:01.497  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 12:38:01.497  1016  1123 V NetworkStats: performPollLocked(flags=0x3)
,08-30 12:38:01.497  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-30 12:38:01.497  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 12:38:01.507  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 12:38:01.507  1016  1123 V NetworkStats: performPollLocked() took 6ms
08-30 12:38:01.507  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 12:38:01.507  1016  1213 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-30 12:38:01.507  1016  1213 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-30 12:38:01.507  1016  1213 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:38:01.507  1016  1213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 12:38:01.507  1016  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-30 12:38:01.517  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 12:38:01.517  1447  1447 D RegisteredServicesCache: empty dynamic service
,08-30 12:38:01.517  2794  2794 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-30 12:38:01.517  1016  1028 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=42
08-30 12:38:01.517  1016  1028 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-30 12:38:01.537  6974  6974 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-30 12:38:01.537  1016  1486 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-30 12:38:01.537  1016  1486 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-30 12:38:01.537  1016  1486 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:38:01.537  1016  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 12:38:01.537  1016  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-30 12:38:01.547  2794  2794 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-30 12:38:01.547  6974  6974 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-30 12:38:01.547  2794  2794 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-30 12:38:01.547  6974  6974 D elm:15121: ElmAgentService : onCreate()
,08-30 12:38:01.557  1447  1447 D RegisteredComponentCache: Collect Tech packages for Knox
,08-30 12:38:01.557  1447  1447 D PersonaManager: isKioskContainerExistOnDevice
,08-30 12:38:01.557  6974  7161 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-30 12:38:01.567  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 12:38:01.567  6974  7161 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-30 12:38:01.567  6974  7161 D elm:15121: MDMBridge.getInstance()
08-30 12:38:01.567  6974  7161 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-30 12:38:01.567  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 12:38:01.567  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 12:38:01.577  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-30 12:38:01.577  2794  2794 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-30 12:38:01.577  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:01.577  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:01.577  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:01.577  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:38:01.587  7162  7162 E Zygote  : MountEmulatedStorage(),
,08-30 12:38:01.587  7162  7162 E Zygote  : v2
,08-30 12:38:01.597  7162  7162 I libpersona: KNOX_SDCARD checking this for 10032
08-30 12:38:01.597  7162  7162 I libpersona: KNOX_SDCARD not a persona,
08-30 12:38:01.597  7162  7162 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 12:38:01.597  7162  7162 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 12:38:01.607  6974  7161 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-30 12:38:01.607  2794  7160 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-30 12:38:01.607  7162  7162 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-30 12:38:01.607  1016  1042 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=7162 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 12:38:01.617  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,08-30 12:38:01.627  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:01.627  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:38:01.627  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:01.627  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:38:01.637   318   318 I art     : Explicit concurrent mark sweep GC freed 8685(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 774us total 31.781ms
,08-30 12:38:01.647  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 12:38:01.647  7162  7162 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:38:01.647  1016  1016 I art     : Explicit concurrent mark sweep GC freed 33561(2MB) AllocSpace objects, 20(320KB) LOS objects, 33% free, 23MB/34MB, paused 16.859ms total 254.283ms
08-30 12:38:01.647  7162  7162 D ActivityThread: Added TimaKeyStore provider
,08-30 12:38:01.647  1016  1056 I art     : WaitForGcToComplete blocked for 162.795ms for cause Explicit
,08-30 12:38:01.647  2794  7160 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-30 12:38:01.657   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 569us total 17.581ms
,08-30 12:38:01.677   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 16.396ms
,08-30 12:38:01.677  1016  4749 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-30 12:38:01.677  1016  4749 D SecContentProvider2: mCursor = null
,08-30 12:38:01.677  2794  7160 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,08-30 12:38:01.687  2794  7160 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
08-30 12:38:01.687  7177  7177 E Zygote  : MountEmulatedStorage()
08-30 12:38:01.687  7177  7177 E Zygote  : v2
08-30 12:38:01.687  7177  7177 I libpersona: KNOX_SDCARD checking this for 10052
08-30 12:38:01.687  7177  7177 I libpersona: KNOX_SDCARD not a persona
,08-30 12:38:01.687  7177  7177 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 12:38:01.687  7177  7177 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 12:38:01.687  7177  7177 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 12:38:01.707  1016  1042 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7177 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,08-30 12:38:01.707  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,08-30 12:38:01.717  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:01.717  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:38:01.717  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:01.717  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:38:01.737  7192  7192 E Zygote  : MountEmulatedStorage(),
08-30 12:38:01.747  7192  7192 E Zygote  : v2
08-30 12:38:01.747  7192  7192 I libpersona: KNOX_SDCARD checking this for 10098
08-30 12:38:01.747  7177  7177 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:38:01.747  7192  7192 I libpersona: KNOX_SDCARD not a persona
08-30 12:38:01.747  7192  7192 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 12:38:01.747  1016  1042 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7192 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-30 12:38:01.747  7177  7177 D ActivityThread: Added TimaKeyStore provider
08-30 12:38:01.747  7192  7192 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 12:38:01.747  7192  7192 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 12:38:01.777  6974  6974 D elm:15121: ElmAgentService : onDestroy().
,08-30 12:38:01.777  7192  7192 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 12:38:01.787  7192  7192 D ActivityThread: Added TimaKeyStore provider
,08-30 12:38:01.797  2794  7160 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-30 12:38:01.797  1016  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-30 12:38:01.817  2794  7160 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-30 12:38:01.817  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 12:38:01.817  2794  7160 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-30 12:38:01.817  1016  1749 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,08-30 12:38:01.817  1016  1749 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:01.817  1016  1749 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:01.817  1016  1749 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:01.817  1016  1749 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:38:01.827  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 12:38:01.827  1016  1016 D RCPManagerService: PackageReceiver onReceive()
,08-30 12:38:01.827  1016  1016 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-30 12:38:01.837  1016  1016 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,08-30 12:38:01.837  1016  1016 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-30 12:38:01.837  1016  1016 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-30 12:38:01.837  7162  7207 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-30 12:38:01.837  7208  7208 I libpersona: KNOX_SDCARD checking this for 1000
08-30 12:38:01.837  7162  7207 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
08-30 12:38:01.837  7208  7208 I libpersona: KNOX_SDCARD not a persona
08-30 12:38:01.837  7208  7208 E Zygote  : MountEmulatedStorage()
,08-30 12:38:01.837  7208  7208 E Zygote  : v2
08-30 12:38:01.847  7208  7208 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 12:38:01.847  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 12:38:01.847  7208  7208 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 12:38:01.847  1016  1016 I OTPFW   : ProvisionData::getAllEntries Enter
,08-30 12:38:01.847  7208  7208 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 12:38:01.847  1016  1016 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-30 12:38:01.847  1016  1749 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7208 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-30 12:38:01.857  1016  1749 I ActivityManager: Killing 6744:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-30 12:38:01.867  2794  2794 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-30 12:38:01.867  1016  1749 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-30 12:38:01.867  7208  7208 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 12:38:01.867  7208  7208 D ActivityThread: Added TimaKeyStore provider
,08-30 12:38:01.877  1016  1749 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:38:01.877  1016  1749 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:01.877  1016  1749 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:01.877  1016  1749 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:38:01.887  7162  7207 D SPPClientService: PushLog.txt file is not deleted.
08-30 12:38:01.887  7162  7207 D SPPClientService: PushLog.txt file is not deleted.
08-30 12:38:01.887  7162  7207 D SPPClientService: ============PushLog. stop!
,08-30 12:38:01.887  7224  7224 E Zygote  : MountEmulatedStorage()
08-30 12:38:01.887  1016  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-30 12:38:01.887  7224  7224 E Zygote  : v2
08-30 12:38:01.887  1016  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:38:01.887  1016  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 12:38:01.887  7224  7224 I libpersona: KNOX_SDCARD checking this for 10032
08-30 12:38:01.887  7224  7224 I libpersona: KNOX_SDCARD not a persona
,08-30 12:38:01.887  7224  7224 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 12:38:01.887  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 12:38:01.887  7224  7224 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 12:38:01.887  1016  1749 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7224 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 12:38:01.897  1016  1749 I ActivityManager: Killing 6762:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,08-30 12:38:01.907  7224  7224 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-30 12:38:01.917  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 12:38:01.937  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 12:38:01.937  7224  7224 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 12:38:01.937  7224  7224 D ActivityThread: Added TimaKeyStore provider
,08-30 12:38:01.937  1016  1016 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-30 12:38:01.937  1016  1016 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-30 12:38:01.937  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-30 12:38:01.937  1016  1016 V EnterpriseBillingPolicy: uID is 10170
08-30 12:38:01.937  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
08-30 12:38:01.937  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-30 12:38:01.937  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-30 12:38:01.937  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-30 12:38:01.937  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-30 12:38:01.937  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-30 12:38:01.937  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-30 12:38:01.947  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 12:38:01.947  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-30 12:38:01.947  1016  1016 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-30 12:38:01.947  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,08-30 12:38:01.947  1016  1213 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-30 12:38:01.947  1016  1213 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
08-30 12:38:01.947  1016  1016 V EnterpriseBillingPolicy: uID is 10170
08-30 12:38:01.947  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
08-30 12:38:01.947  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-30 12:38:01.947  1016  3345 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-30 12:38:01.947  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-30 12:38:01.947  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-30 12:38:01.947  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-30 12:38:01.947  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-30 12:38:01.947  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-30 12:38:01.947  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,08-30 12:38:01.947  1016  1213 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:38:01.947  1016  1213 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 12:38:01.947  1016  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-30 12:38:01.957  1016  4748 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,08-30 12:38:01.957  1016  4748 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-30 12:38:01.957  1016  4748 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:38:01.957  1016  4748 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:38:01.957  1016  4748 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-30 12:38:01.967  1016  1016 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,08-30 12:38:01.967  1016  1160 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,08-30 12:38:01.977  1016  1749 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-30 12:38:01.977  1016  1749 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:38:01.977  1016  1749 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:01.977  1016  1749 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:38:01.977  1016  1749 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:38:01.997  7241  7241 E Zygote  : MountEmulatedStorage()
08-30 12:38:01.997  7241  7241 E Zygote  : v2
08-30 12:38:01.997  7241  7241 I libpersona: KNOX_SDCARD checking this for 10055
08-30 12:38:01.997  7241  7241 I libpersona: KNOX_SDCARD not a persona
,08-30 12:38:01.997  7241  7241 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 12:38:01.997  7241  7241 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 12:38:01.997  7241  7241 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 12:38:01.997  1016  1056 I art     : Explicit concurrent mark sweep GC freed 11201(608KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 4.979ms total 350.587ms
,08-30 12:38:02.007  1016  1749 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7241 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-30 12:38:02.017   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 12:38:02.017  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 12:38:02.027  1681  1681 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
08-30 12:38:02.027  1681  1681 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-30 12:38:02.037  7241  7241 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 12:38:02.037  7241  7241 D ActivityThread: Added TimaKeyStore provider
,08-30 12:38:02.047  7224  7256 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-30 12:38:02.047  7224  7256 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-30 12:38:02.067  1016  1254 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,08-30 12:38:02.067  1016  1254 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:02.067  1016  1254 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:02.067  1016  1254 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:02.067  1016  1254 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:38:02.077  7224  7256 D SPPClientService: PushLog.txt file is not deleted.
08-30 12:38:02.077  7224  7256 D SPPClientService: PushLog.txt file is not deleted.
08-30 12:38:02.077  7224  7256 D SPPClientService: ============PushLog. stop!
,08-30 12:38:02.077  7258  7258 E Zygote  : MountEmulatedStorage()
08-30 12:38:02.077  7258  7258 E Zygote  : v2
08-30 12:38:02.077  7258  7258 I libpersona: KNOX_SDCARD checking this for 1000
08-30 12:38:02.077  7258  7258 I libpersona: KNOX_SDCARD not a persona
,08-30 12:38:02.077  7258  7258 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 12:38:02.087  7258  7258 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 12:38:02.087  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 12:38:02.087  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-30 12:38:02.087  7258  7258 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 12:38:02.087  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 12:38:02.087  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-30 12:38:02.097  1016  1254 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7258 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-30 12:38:02.097  1016  4757 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-30 12:38:02.097  1016  4757 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,08-30 12:38:02.097  1016  4757 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:38:02.097  1016  4757 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:38:02.097  1016  4757 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-30 12:38:02.097  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 12:38:02.107  1016  1213 I ActivityManager: Killing 6793:com.wsomacp/u0a23 (adj 15): empty #21
,08-30 12:38:02.107  7241  7241 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-30 12:38:02.107  1862  7273 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-30 12:38:02.117  1862  7273 D AccountUtils: Clearing selected account for com.test.thalitest
,08-30 12:38:02.117  7258  7258 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 12:38:02.117  7258  7258 D ActivityThread: Added TimaKeyStore provider
,08-30 12:38:02.117  1016  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-30 12:38:02.117  1016  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-30 12:38:02.127  1016  1486 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
08-30 12:38:02.127  1016  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,08-30 12:38:02.127  1016  1486 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:38:02.127  1016  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 12:38:02.127  1016  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,08-30 12:38:02.137  1016  1481 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 12:38:02.147  1016  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:38:02.147  1016  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 12:38:02.147  1016  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:38:02.157  1016  1056 D PackageManager: delete codoeFile: 
,08-30 12:38:02.167  1016  1056 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
08-30 12:38:02.167  1016  1056 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,08-30 12:38:02.167  1016  1056 D PackageManager: result of delete: 1{951752379}
,08-30 12:38:02.167  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,08-30 12:38:02.167  7241  7241 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-30 12:38:02.167  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:02.167  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:02.167  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:02.167  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:02.167  7241  7241 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-30 12:38:02.167  7241  7241 D UserAnalysis: Create SecureDbHelper
08-30 12:38:02.167  7149  7149 D AndroidRuntime: Shutting down VM
,08-30 12:38:02.177  7258  7258 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,08-30 12:38:02.187  1016  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-30 12:38:02.187  1016  1056 D PackageManager: userId{-1}
08-30 12:38:02.187  1016  1056 D PackageManager: andCode{true}
,08-30 12:38:02.187  7280  7280 E Zygote  : MountEmulatedStorage(),
08-30 12:38:02.187  7280  7280 E Zygote  : v2
,08-30 12:38:02.187  7280  7280 I libpersona: KNOX_SDCARD checking this for 10039
08-30 12:38:02.187  7280  7280 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 12:38:02.187  7280  7280 I libpersona: KNOX_SDCARD not a persona
,08-30 12:38:02.187  7280  7280 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 12:38:02.197  7280  7280 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 12:38:02.197  1016  1029 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7280 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-30 12:38:02.197  7241  7241 D IntelligenceServiceApplication: onCreate()
,08-30 12:38:02.197  7241  7241 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,08-30 12:38:02.207  1016  1333 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:38:02.207  1016  1333 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
08-30 12:38:02.207  1016  1333 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 12:38:02.207  1016  1333 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
08-30 12:38:02.207  1016  1333 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
08-30 12:38:02.207  1016  1486 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 12:38:02.207  7241  7241 D IntelligenceServiceApplication: no applications having user consent for prediction
08-30 12:38:02.207  1016  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
08-30 12:38:02.217  1016  1486 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:38:02.217  1016  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:38:02.217  1016  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:38:02.217  1016  4757 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 12:38:02.217  1016  4757 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:38:02.217  1016  4757 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:38:02.217  1016  4757 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:38:02.217  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-30 12:38:02.217  7241  7241 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-30 12:38:02.217  1016  1213 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,08-30 12:38:02.217  1016  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:02.217  1016  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:02.217  1016  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:02.217  1016  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:38:02.227  1016  1253 D LocationManagerService: getProviders()=[passive, gps]
,08-30 12:38:02.227  7280  7280 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 12:38:02.227  1862  7273 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
08-30 12:38:02.227  7280  7280 D ActivityThread: Added TimaKeyStore provider
,08-30 12:38:02.237  7241  7241 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-30 12:38:02.237  7301  7301 E Zygote  : MountEmulatedStorage(),
08-30 12:38:02.237  1016  1213 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7301 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-30 12:38:02.237  7301  7301 E Zygote  : v2
08-30 12:38:02.237  7301  7301 I libpersona: KNOX_SDCARD checking this for 1000
08-30 12:38:02.237  7301  7301 I libpersona: KNOX_SDCARD not a persona
,08-30 12:38:02.247  7301  7301 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-30 12:38:02.247  1016  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-30 12:38:02.247  7301  7301 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 12:38:02.247  7301  7301 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 12:38:02.257  1016  1028 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,08-30 12:38:02.257  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:02.257  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:02.257  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:02.257  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:38:02.277  7316  7316 E Zygote  : MountEmulatedStorage()
,08-30 12:38:02.277  7316  7316 E Zygote  : v2
08-30 12:38:02.277  7316  7316 I libpersona: KNOX_SDCARD checking this for 10014
08-30 12:38:02.277  7316  7316 I libpersona: KNOX_SDCARD not a persona
,08-30 12:38:02.277  7316  7316 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-30 12:38:02.277  7316  7316 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 12:38:02.277  7316  7316 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 12:38:02.277  1016  1028 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7316 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
,08-30 12:38:02.287  7301  7301 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-30 12:38:02.287  7301  7301 D ActivityThread: Added TimaKeyStore provider
,08-30 12:38:02.287  1016  1332 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-30 12:38:02.287  1016  1332 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
08-30 12:38:02.287  7280  7280 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-30 12:38:02.287  7280  7280 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
08-30 12:38:02.287  7280  7280 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-30 12:38:02.297  7280  7280 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,08-30 12:38:02.297  7280  7280 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 12:38:02.297  7280  7280 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-30 12:38:02.297  7280  7280 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-30 12:38:02.297  1016  1332 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:38:02.297  1016  1332 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 12:38:02.307  1016  1332 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:38:02.317  1862  1862 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-30 12:38:02.317  1862  1862 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-30 12:38:02.317  7241  7241 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,08-30 12:38:02.317  7241  7241 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,08-30 12:38:02.317  1862  7314 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
08-30 12:38:02.317  1862  7314 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,08-30 12:38:02.317  7241  7241 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
,08-30 12:38:02.317  7241  7241 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-30 12:38:02.317  7241  7241 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,08-30 12:38:02.317  7241  7241 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-30 12:38:02.317  7241  7241 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,08-30 12:38:02.317  7241  7241 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
,08-30 12:38:02.327  7241  7241 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
,08-30 12:38:02.327  1862  7314 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
08-30 12:38:02.327  1862  7314 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,08-30 12:38:02.327  7241  7241 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
,08-30 12:38:02.327  7241  7241 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-30 12:38:02.327  7241  7241 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,08-30 12:38:02.327  7241  7241 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-30 12:38:02.327  7316  7316 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 12:38:02.327  7241  7241 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-30 12:38:02.327  7241  7241 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
08-30 12:38:02.327  7241  7241 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
08-30 12:38:02.337  1016  4748 I ActivityManager: Killing 6862:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
08-30 12:38:02.337  7316  7316 D ActivityThread: Added TimaKeyStore provider
,08-30 12:38:02.337  7241  7241 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
,08-30 12:38:02.337  1016  1770 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 12:38:02.337  7241  7241 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,08-30 12:38:02.337  7241  7241 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,08-30 12:38:02.337  7241  7241 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-30 12:38:02.337  7241  7241 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,08-30 12:38:02.337  7241  7241 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
08-30 12:38:02.337  7241  7241 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
,08-30 12:38:02.337  7241  7241 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
08-30 12:38:02.337  1016  1770 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:38:02.337  1016  1770 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:38:02.337  1016  1770 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:38:02.357  1016  1333 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 12:38:02.357  7241  7241 D BluetoothAdapter: cancelDiscovery
,08-30 12:38:02.357  1862  7314 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
08-30 12:38:02.357  1862  7314 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,08-30 12:38:02.357  1862  7314 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,08-30 12:38:02.367  1016  1333 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:38:02.367  1016  1333 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 12:38:02.367  1016  1333 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 12:38:02.367  1016  1332 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-30 12:38:02.377  1016  1332 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:38:02.377  1016  1332 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:38:02.377  1016  1332 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:38:02.377  1016  1332 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:38:02.377  7149  7149 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-30 12:38:02.377  7301  7335 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED,
08-30 12:38:02.377  7301  7335 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
08-30 12:38:02.387  1862  7314 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1,
08-30 12:38:02.387  1862  7314 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
08-30 12:38:02.387  6165  6165 I art     : Explicit concurrent mark sweep GC freed 918(41KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 4MB/6MB, paused 735us total 65.624ms
08-30 12:38:02.387  1862  7314 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,08-30 12:38:02.387  1862  7314 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
08-30 12:38:02.387  1862  7314 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,08-30 12:38:02.387  1862  7314 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,08-30 12:38:02.397  6165  7297 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,08-30 12:38:02.397  7336  7336 E Zygote  : MountEmulatedStorage()
08-30 12:38:02.397  7336  7336 I libpersona: KNOX_SDCARD checking this for 1000
08-30 12:38:02.397  7336  7336 E Zygote  : v2
08-30 12:38:02.397  7336  7336 I libpersona: KNOX_SDCARD not a persona
,08-30 12:38:02.397  7336  7336 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 12:38:02.397  7336  7336 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 12:38:02.397  7336  7336 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 12:38:02.407  1016  1332 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7336 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-30 12:38:02.407  1016  1481 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 12:38:02.407  1016  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,08-30 12:38:02.407  1016  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-30 12:38:02.417  1016  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 12:38:02.417  1016  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-30 12:38:02.417  1016  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:02.417  1016  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:02.417  1016  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:02.417  1016  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:38:02.427  7351  7351 E Zygote  : MountEmulatedStorage(),
08-30 12:38:02.427  7351  7351 E Zygote  : v2
08-30 12:38:02.427  7351  7351 I libpersona: KNOX_SDCARD checking this for 10011
08-30 12:38:02.427  7351  7351 I libpersona: KNOX_SDCARD not a persona
,08-30 12:38:02.437  1016  1481 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=7351 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
08-30 12:38:02.437  7336  7336 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 12:38:02.437  7336  7336 D ActivityThread: Added TimaKeyStore provider
,08-30 12:38:02.437  7351  7351 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 12:38:02.437  7351  7351 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 12:38:02.437  1016  4757 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
08-30 12:38:02.447  1016  4757 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,08-30 12:38:02.447  7177  7239 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-30 12:38:02.447  1016  4757 W ActivityManager: userId = 0, bbcId = -10000
08-30 12:38:02.447  1016  4757 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 12:38:02.447  1016  4757 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,08-30 12:38:02.447  7351  7351 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 12:38:02.457   318   318 I art     : Explicit concurrent mark sweep GC freed 8739(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 612us total 25.225ms,
08-30 12:38:02.457  1016  4749 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
08-30 12:38:02.457  1016  4749 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:38:02.467  1016  4749 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:02.467  1016  4749 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:02.467  1016  4749 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:38:02.467  7301  7301 D AcmsService: Enter Oncreate
,08-30 12:38:02.467  7301  7301 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-30 12:38:02.467  7301  7301 D AcmsService: creating AcmsCore
08-30 12:38:02.467  7301  7301 D AcmsCore: AcmsCore.getAcmsCore() - Enter
08-30 12:38:02.467  7301  7301 D AcmsCore: AcmsCore
,08-30 12:38:02.477   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 18.626ms
,08-30 12:38:02.487  7301  7301 D AcmsCore: init
08-30 12:38:02.487  7301  7301 D AcmsCore: Looper handler is not null
08-30 12:38:02.487  7301  7301 D AcmsCore: Post to AcmsCoreHandler
08-30 12:38:02.487  7301  7301 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-30 12:38:02.487  7301  7301 D AcmsServiceMonitor: Incrementing - Counter value: 1
08-30 12:38:02.487  7301  7301 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
08-30 12:38:02.487  7301  7301 D AcmsService: onStartCommand
08-30 12:38:02.487  7301  7301 D AcmsService: Action: android.intent.action.PACKAGE_REMOVED
08-30 12:38:02.487  7301  7301 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
08-30 12:38:02.487  7301  7301 D AcmsServiceMonitor: Incrementing - Counter value: 2
08-30 12:38:02.487  7301  7301 D AcmsService: Incremented Counter Value : onStartCommand
,08-30 12:38:02.487  7351  7351 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:38:02.487  7351  7351 D ActivityThread: Added TimaKeyStore provider
08-30 12:38:02.487  7301  7366 D AcmsCertificateMngr: AcmsCertificateMngr
,08-30 12:38:02.487  7301  7366 D AcmsRevocationMngr: AcmsRevocationMngr
,08-30 12:38:02.497   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 597us total 16.791ms
,08-30 12:38:02.517  7370  7370 E Zygote  : MountEmulatedStorage(),
08-30 12:38:02.517  7370  7370 E Zygote  : v2
,08-30 12:38:02.517  7370  7370 I libpersona: KNOX_SDCARD checking this for 10117
08-30 12:38:02.517  7370  7370 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 12:38:02.517  7370  7370 I libpersona: KNOX_SDCARD not a persona
,08-30 12:38:02.517  7370  7370 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 12:38:02.517  1016  4749 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7370 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-30 12:38:02.527  7370  7370 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-30 12:38:02.527  1016  1487 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.sm, calleePkgName: com.sec.android.provider.badge
08-30 12:38:02.527  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:02.527  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:02.527  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:02.527  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:38:02.537  7370  7370 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:38:02.537  7370  7370 D ActivityThread: Added TimaKeyStore provider
,08-30 12:38:02.547  7385  7385 E Zygote  : MountEmulatedStorage()
08-30 12:38:02.547  7385  7385 E Zygote  : v2
08-30 12:38:02.547  7385  7385 I libpersona: KNOX_SDCARD checking this for 10068
08-30 12:38:02.547  7385  7385 I libpersona: KNOX_SDCARD not a persona
,08-30 12:38:02.547  1016  1487 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7385 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-30 12:38:02.547  7385  7385 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 12:38:02.557  1016  1254 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
08-30 12:38:02.557  7385  7385 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 12:38:02.557  7301  7301 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
08-30 12:38:02.557  7385  7385 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-30 12:38:02.567  1862  1862 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-30 12:38:02.567  1862  1862 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-30 12:38:02.577  3197  3207 D BluetoothAdapterProperties: mDiscovering is false
08-30 12:38:02.577  3197  3207 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
08-30 12:38:02.577  7241  7241 D BluetoothAdapter: cancelDiscovery = true
08-30 12:38:02.577  7241  7241 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,08-30 12:38:02.577  1016  3705 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
08-30 12:38:02.587  1016  3705 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:02.587  1016  3705 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:02.587  1016  3705 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 12:38:02.587  1016  3705 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 12:38:02.587  7301  7301 W FileUtils: Failed to chmod(/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,08-30 12:38:02.597  7385  7385 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 12:38:02.597  7385  7385 D ActivityThread: Added TimaKeyStore provider
,08-30 12:38:02.597  7351  7351 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 12:38:02.597  7351  7351 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 12:38:02.607  7370  7370 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 12:38:02.607  7404  7404 E Zygote  : MountEmulatedStorage(),
08-30 12:38:02.607  7404  7404 E Zygote  : v2
08-30 12:38:02.607  7404  7404 I libpersona: KNOX_SDCARD checking this for 1000
08-30 12:38:02.607  7404  7404 I libpersona: KNOX_SDCARD not a persona
08-30 12:38:02.607  1016  3705 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7404 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-30 12:38:02.617  1016  3705 I ActivityManager: Killing 6888:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-30 12:38:02.617  1016  1253 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-30 12:38:02.617  7241  7241 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-30 12:38:02.617  7404  7404 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 12:38:02.627  7404  7404 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 12:38:02.627  7404  7404 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 12:38:02.627  1016  1213 I ActivityManager: Killing 6916:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-30 12:38:02.637  7241  7241 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-30 12:38:02.647  7241  7241 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/dump.db" with flag (131138) and mode_t (0) due to error (30)
,08-30 12:38:02.647  7241  7241 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/dump.db'.
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:106)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 12:38:02.647  7241  7241 E UserAnalysis: It failed to get the database for dump_log
08-30 12:38:02.647  7241  7241 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/dump.db" with flag (131138) and mode_t (0) due to error (30)
,08-30 12:38:02.647  7404  7404 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 12:38:02.647  7404  7404 D ActivityThread: Added TimaKeyStore provider
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/dump.db'.
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:106)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 12:38:02.647  7241  7241 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 12:38:02.647  7241  7241 E UserAnalysis: It failed to get the database for dump_log
08-30 12:38:02.657  7301  7301 D AcmsService: Inside handle Intent
08-30 12:38:02.657  7301  7301 D AcmsService: App removed - package name: com.test.thalitest
08-30 12:38:02.657  7301  7301 D AcmsCore: Post to AcmsCoreHandler
08-30 12:38:02.657  7301  7301 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-30 12:38:02.657  7301  7301 D AcmsServiceMonitor: Incrementing - Counter value: 3
08-30 12:38:02.657  7301  7301 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>5
08-30 12:38:02.657  7301  7301 D AcmsService: Decremented Counter Value : handleStartIntent
08-30 12:38:02.657  7301  7301 D AcmsServiceMonitor: Decrementing - Counter value: 2
08-30 12:38:02.667  7177  7239 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-30 12:38:02.667  7177  7239 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-30 12:38:02.667  1016  4757 I ActivityManager: Killing 6529:com.android.mms/u0a41 (adj 15): empty #21

```
