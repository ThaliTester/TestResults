#### Test 828946820542738_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
09-06 19:09:23.474  1915  6527 I qtaguid : Untagging socket 101
09-06 19:09:23.474  1915  1915 I ConfigFetchService: fetch service done; releasing wakelock
09-06 19:09:23.474  1915  1915 I ConfigFetchService: stopping self
--------- beginning of system
09-06 19:09:23.494  1003  1416 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
09-06 19:09:23.514  6494  6494 D ComposerPerformance: 1473181763520 ms / [DONE] Composer constructor
09-06 19:09:23.514  6494  6494 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
09-06 19:09:23.514  6494  6494 I Mms/ReservationManager: ReservationManager()
09-06 19:09:23.514  6494  6494 I Mms/ReservationManager: resetAfterConnected()
09-06 19:09:23.514  6494  6678 D Mms/Conversation: [start]    init() consume time = 88.351718
09-06 19:09:23.524  1483  3314 D TP/MmsSmsProvider: query,matched:7, calling pid = 6494
09-06 19:09:23.524  1483  1797 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
09-06 19:09:23.524  1483  1797 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
09-06 19:09:23.524  1483  3314 D TP/MmsSmsProvider: match 7:Elapsed time : 2.523 ms
09-06 19:09:23.524  1483  1797 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
09-06 19:09:23.534  1483  1797 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
09-06 19:09:23.534  1483  1797 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
09-06 19:09:23.534  1483  1797 D TP/MmsSmsProvider: need read changed broadcast:false
09-06 19:09:23.534  6494  6678 D Mms/Conversation: [end]    init consume time = 16.379792
09-06 19:09:23.534  6494  6494 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
09-06 19:09:23.544  6494  6494 D Mms/MmsApp: [end]    onCreate() consume time = 4.553125
09-06 19:09:23.544  6494  6642 D Mms/ArtClassLoader: init [DONE] art
09-06 19:09:23.544  6494  6678 D Mms/MessagingNotification: [start]    init() consume time = 3.803333
09-06 19:09:23.544  6494  6494 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
09-06 19:09:23.544  6494  6678 D Mms/MessagingNotification: [end]    init consume time = 2.65224
09-06 19:09:23.554  6494  6494 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
09-06 19:09:23.554  6494  6494 D Mms/MethodReflector: getSubId is called
09-06 19:09:23.554  6494  6494 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
09-06 19:09:23.554  6494  6683 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 4.909844
09-06 19:09:23.554  6494  6494 D Mms/MethodReflector: getTelephonyProperty is called
09-06 19:09:23.554  6494  6494 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-06 19:09:23.554  6494  6494 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-06 19:09:23.554  6494  6494 D Mms/DownloadManager: auto download without roaming -> true
09-06 19:09:23.554  6494  6494 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
09-06 19:09:23.554  6494  6494 D Mms/DownloadManager: mAutoDownload ------> true
09-06 19:09:23.554  1483  3314 D TP/MmsSmsProvider: query,matched:0, calling pid = 6494
09-06 19:09:23.554  1683  4412 I art     : Explicit concurrent mark sweep GC freed 13217(626KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 8MB/13MB, paused 1.216ms total 45.918ms
09-06 19:09:23.554  1483  3314 V TP/MmsSmsProvider: getSimpleConversations entered.
09-06 19:09:23.554  1483  3314 D TP/MmsSmsProvider: match 0:Elapsed time : 1.453 ms
09-06 19:09:23.554  1483  1797 D TP/MmsSmsProvider: query,matched:400, calling pid = 6494
09-06 19:09:23.564  6494  6684 D Mms/Synchronizer: [start]    doSync consume time = 10.415937
09-06 19:09:23.564  6494  6494 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
09-06 19:09:23.564  1003  1496 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
09-06 19:09:23.564  1003  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
09-06 19:09:23.574  1003  1496 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:23.574  1003  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:23.574  1003  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
09-06 19:09:23.574  1003  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
09-06 19:09:23.574  6494  6683 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 11.959375
09-06 19:09:23.574  1003  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:23.574  1003  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:23.574  1003  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:23.574  1003  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:23.574  1483  1497 D TP/MmsSmsProvider: update, matched:300, calling pid = 6494
09-06 19:09:23.574  1483  1497 V TP/MmsSmsProvider: syncDBData start
09-06 19:09:23.574  1483  1497 V TP/MmsSmsProvider: syncDBData sms end
09-06 19:09:23.574  1483  1497 V TP/MmsSmsProvider: syncDBData mms end
09-06 19:09:23.574  1483  1497 V TP/MmsSmsProvider: syncDBData end
09-06 19:09:23.584  6686  6686 E Zygote  : MountEmulatedStorage()
09-06 19:09:23.584  6686  6686 E Zygote  : v2
09-06 19:09:23.584  6686  6686 I libpersona: KNOX_SDCARD checking this for 10042
09-06 19:09:23.584  6686  6686 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:23.594  6686  6686 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:09:23.594  6494  6685 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
09-06 19:09:23.594  6494  6685 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
09-06 19:09:23.594  6686  6686 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:09:23.594  6686  6686 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
09-06 19:09:23.594  6494  6684 D Mms/Synchronizer: [end]    doSync consume time = 23.318438
09-06 19:09:23.594  1003  1030 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6686 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
09-06 19:09:23.604  1003  1512 I ActivityManager: Killing 6261:com.android.calendar/u0a131 (adj 15): empty #21
09-06 19:09:23.604  1003  1029 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
09-06 19:09:23.614  1003  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:23.614  1003  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:23.614  1003  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:23.614  1003  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:23.634  6700  6700 E Zygote  : MountEmulatedStorage()
09-06 19:09:23.634  6686  6686 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:09:23.634  1003  1029 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6700 uid=10068 gids={50068, 9997} abi=armeabi-v7a
09-06 19:09:23.634  6686  6686 D ActivityThread: Added TimaKeyStore provider
09-06 19:09:23.634  6700  6700 I libpersona: KNOX_SDCARD checking this for 10068
09-06 19:09:23.634  6700  6700 E Zygote  : v2
09-06 19:09:23.634  6700  6700 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:23.634  6700  6700 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:09:23.634  6700  6700 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:09:23.634  6700  6700 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-06 19:09:23.664  6700  6700 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:09:23.664  6700  6700 D ActivityThread: Added TimaKeyStore provider
09-06 19:09:23.664  1003  1481 I ActivityManager: Killing 6344:com.android.defcontainer/u0a3 (adj 15): empty #21
09-06 19:09:23.674  6686  6686 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-06 19:09:23.674  6686  6686 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-06 19:09:23.674  6686  6686 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-06 19:09:23.694  6700  6700 D BadgeProvider: onCreate
09-06 19:09:23.694  6700  6700 D BadgeProvider: DatabaseHelper
09-06 19:09:23.714  6494  6678 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
09-06 19:09:23.724  1483  3314 D TP/SmsProvider: query,matched:26, calling pid = 6494
09-06 19:09:23.724  1483  3314 D TP/SmsProvider: match 26:Elapsed time : 2.113 ms
09-06 19:09:23.734  1483  1500 D TP/MmsSmsProvider: query,matched:6, calling pid = 6494
09-06 19:09:23.734  1483  1500 D TP/MmsSmsProvider: match 6:Elapsed time : 1.680 ms
09-06 19:09:23.794  1915  4359 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
09-06 19:09:23.804  6517  6580 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-06 19:09:23.804  6517  6580 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-06 19:09:23.804  6517  6580 I GAv4    :   adb logcat -s GAv4
09-06 19:09:23.834  6686  6686 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
09-06 19:09:23.844  1003  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
09-06 19:09:23.844  1003  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
09-06 19:09:23.844  1003  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:23.844  1003  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:23.844  1003  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:23.844  1003  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:23.854  6718  6718 E Zygote  : MountEmulatedStorage()
09-06 19:09:23.854  6718  6718 E Zygote  : v2
09-06 19:09:23.854  6718  6718 I libpersona: KNOX_SDCARD checking this for 10003
09-06 19:09:23.854  6718  6718 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:23.854  6718  6718 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:09:23.864  6718  6718 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:09:23.864  6718  6718 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:09:23.864  1003  1058 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6718 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-06 19:09:23.884  6718  6718 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:09:23.884  6718  6718 D ActivityThread: Added TimaKeyStore provider
09-06 19:09:23.894  6517  6580 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
09-06 19:09:23.894  1003  1416 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
09-06 19:09:23.894  1915  4359 D Icing   : Loaded CLD2 Version V2.0 - 20141016
09-06 19:09:23.904  1003  1030 I ActivityManager: Killing 6112:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
09-06 19:09:23.924   284   284 E installd: system dir 0 : /system/app/
09-06 19:09:23.924   284   284 E installd: system dir 1 : /system/priv-app/
09-06 19:09:23.924   284   284 E installd: system dir 2 : /vendor/app/
09-06 19:09:23.924   284   284 E installd: system dir 3 : /oem/app/
09-06 19:09:23.954  6517  6580 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
09-06 19:09:23.954  1003  1137 I art     : Explicit concurrent mark sweep GC freed 139448(7MB) AllocSpace objects, 6(1895KB) LOS objects, 33% free, 22MB/34MB, paused 2.898ms total 196.565ms
09-06 19:09:23.954  1003  1523 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
09-06 19:09:23.964  1003  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:23.964  1003  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:23.964  1003  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:23.964  1003  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:23.984  6737  6737 E Zygote  : MountEmulatedStorage()
09-06 19:09:23.984  6737  6737 E Zygote  : v2
09-06 19:09:23.984  6737  6737 I libpersona: KNOX_SDCARD checking this for 10023
09-06 19:09:23.984  6737  6737 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:23.984  6737  6737 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:09:23.984  1003  1058 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
09-06 19:09:23.984  1003  1523 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6737 uid=10023 gids={50023, 9997} abi=armeabi-v7a
09-06 19:09:23.984  6737  6737 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:09:23.984  6737  6737 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:09:24.014  6737  6737 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:09:24.014  6737  6737 D ActivityThread: Added TimaKeyStore provider
09-06 19:09:24.014  6517  6580 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
09-06 19:09:24.024  6517  6736 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
09-06 19:09:24.034  1003  1479 I ActivityManager: Killing 6388:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
09-06 19:09:24.034  1915  4359 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
09-06 19:09:24.064  1003  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-06 19:09:24.064  1003  1481 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:24.064  1003  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:24.064  1003  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-06 19:09:24.064  6737  6737 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
09-06 19:09:24.084  6494  6678 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
09-06 19:09:24.104  6737  6737 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
09-06 19:09:24.114  6737  6737 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
09-06 19:09:24.114  6737  6737 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
09-06 19:09:24.114  6737  6737 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
09-06 19:09:24.114  6737  6737 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
09-06 19:09:24.114  6737  6737 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
09-06 19:09:24.124  1003  1481 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
09-06 19:09:24.124  6737  6737 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
09-06 19:09:24.124  1003  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:24.124  6737  6737 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
09-06 19:09:24.124  1003  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:24.124  1003  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:24.124  1003  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:24.124  6737  6737 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
09-06 19:09:24.124  6737  6737 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
09-06 19:09:24.124  6737  6737 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
09-06 19:09:24.134  6737  6737 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
09-06 19:09:24.134  6737  6737 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
09-06 19:09:24.134  1003  1481 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=6758 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-06 19:09:24.144  1003  1481 I ActivityManager: Killing 5033:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
09-06 19:09:24.144  6758  6758 E Zygote  : MountEmulatedStorage()
09-06 19:09:24.144  6758  6758 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:09:24.144  6758  6758 E Zygote  : v2
09-06 19:09:24.144  6758  6758 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:24.144  6758  6758 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:09:24.144  6758  6758 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:09:24.144  6758  6758 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:09:24.174  6758  6758 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:09:24.174  6758  6758 D ActivityThread: Added TimaKeyStore provider
09-06 19:09:24.184  6517  6756 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-06 19:09:24.184  6517  6756 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-06 19:09:24.194  6758  6758 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
09-06 19:09:24.204  6758  6758 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
09-06 19:09:24.204  1003  1416 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
09-06 19:09:24.204  1003  1416 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
09-06 19:09:24.204  1003  1416 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:24.204  1003  1416 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:24.204  1003  1416 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
09-06 19:09:24.214  1003  1029 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
09-06 19:09:24.214  6758  6758 I FilterInstaller: FilterPackageService : ACTION_CHANGED
09-06 19:09:24.224  1003  1003 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
09-06 19:09:24.224  1003  1003 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
09-06 19:09:24.224  1003  1393 D NtpTrustedTime: forceRefresh() from cache miss
09-06 19:09:24.234   278   901 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-06 19:09:24.234   278   901 D Netd    : getNetworkForDns: using netid 502 for uid 1000
09-06 19:09:24.234  6758  6774 E FilterInstaller: installFilters
09-06 19:09:24.234  6758  6774 E FilterInstaller: There is no requred permission
09-06 19:09:24.234  1003  1003 I BackgroundCompactionService: onStart. jobID=801
09-06 19:09:24.234  1003  1512 I ActivityManager: Killing 6420:com.sec.spp.push/u0a32 (adj 15): empty #21
09-06 19:09:24.234  1003  1003 I BackgroundCompactionService: onStart done. jobID=801
09-06 19:09:24.234  1003  6776 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
09-06 19:09:24.244  1003  6776 I BackgroundCompactionService: compact_memory command done
09-06 19:09:24.264  6517  6756 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
09-06 19:09:24.344  6517  6756 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-06 19:09:24.344  6517  6756 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1f93a06c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-06 19:09:24.344  6517  6756 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-06 19:09:24.394  1003  1393 D NtpTrustedTime: requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1473181764653 mCachedNtpElapsedRealtime : 93682 mCachedNtpCertainty : 6
09-06 19:09:24.394  1003  1393 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:24.394  1003  1393 D AlarmManagerService: Setting time of day to sec=1473181764
09-06 19:09:24.394  1003  1393 D AlarmManagerService: Trying to open a file
09-06 19:09:24.394  1003  1393 D AlarmManagerService: File Open Success
09-06 19:09:24.653  1003  1096 V AlarmManager: waitForAlarm result :65536
09-06 19:09:24.394  1003  1393 D AlarmManagerService: File Close Success
09-06 19:09:24.653  1003  1096 V AlarmManager: No more alarm at this time.nowELAPSED=93693 batch.start=107165
09-06 19:09:24.394  1003  1393 I AlarmManagerService: DRM_TIME_PATH CHMOD 666 for resetState done 
09-06 19:09:24.653  1003  1393 W AlarmManagerService: Unable to set rtc to 1473181764: Invalid argument
09-06 19:09:24.653  1003  1003 D OTPFW   : OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1473181764662
09-06 19:09:24.653  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
09-06 19:09:24.653  1180  1180 D KeyguardUpdateMonitor: handleTimeUpdate
09-06 19:09:24.662  1180  1180 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
09-06 19:09:24.662  1003  1003 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
09-06 19:09:24.662  1003  1003 I DowntimeConditions: android.intent.action.TIME_SET ignored because schedule turned off.
09-06 19:09:24.662  1180  1180 D SecKeyguardClockView: HomeTimezone(): 1
09-06 19:09:24.672  1003  1003 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:09:24.672  1180  1180 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
09-06 19:09:24.672  1180  1180 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_SET
09-06 19:09:24.682  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
09-06 19:09:24.682  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
09-06 19:09:24.682  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
09-06 19:09:24.682  1003  1003 I DrmEventService:  no response from SecureClock 
09-06 19:09:24.682  1180  1180 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
09-06 19:09:24.682  1003  1003 I splitIntent: intent=android.intent.action.TIME_SET will be not split. because same process=com.google.android.gms is in other queue. index=4
09-06 19:09:24.682  1003  1003 I splitIntent: base  index=4, name=com.google.android.gms com.google.android.gms.checkin.CheckinService$Receiver
09-06 19:09:24.682  1003  1003 I splitIntent: other index=7, name=com.google.android.gms com.google.android.gms.reminders.notification.NotificationReceiver
09-06 19:09:24.682  1003  1003 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.TIME_SET !! do not split it!!
09-06 19:09:24.692  1003  1003 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
09-06 19:09:24.692  1180  1180 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
09-06 19:09:24.692  1003  1003 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:24.692  1003  1003 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:24.692  1003  1003 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:24.692  1003  1003 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:24.692  1003  1030 D SettingsProvider: name = lockscreen_zoom_panning_effect
09-06 19:09:24.692  1003  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:24.692  1003  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:24.692  1003  1030 D SettingsProvider: selectionArgs: false
09-06 19:09:24.692  1003  1030 D SettingsProvider: selectionArgs: 10049
09-06 19:09:24.692  1003  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:24.692  1003  1030 D SettingsProvider: ret = -1
09-06 19:09:24.692  1180  1180 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
09-06 19:09:24.702  1180  1180 D KeyguardEffectViewController: isPreloadedWallpaper=true
09-06 19:09:24.702  1180  1180 I GeometricMosaic_Keyguard: update
09-06 19:09:24.702  1180  1180 D KeyguardEffectViewUtil: getCurrentWallpaper() mWallpaperPath :null
09-06 19:09:24.702  6780  6780 E Zygote  : MountEmulatedStorage()
09-06 19:09:24.702  6780  6780 I libpersona: KNOX_SDCARD checking this for 10008
09-06 19:09:24.702  6780  6780 E Zygote  : v2
09-06 19:09:24.702  6780  6780 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:24.712  6780  6780 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:09:24.712  1003  1003 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6780 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:09:24.712  6780  6780 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:09:24.712  6780  6780 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-06 19:09:24.722  6777  6777 D AndroidRuntime: 
09-06 19:09:24.722  6777  6777 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-06 19:09:24.722  6777  6777 D AndroidRuntime: CheckJNI is OFF
09-06 19:09:24.722  6777  6777 D AndroidRuntime: readGMSProperty: start
09-06 19:09:24.722  6777  6777 D AndroidRuntime: readGMSProperty: already setted!!
09-06 19:09:24.722  6777  6777 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-06 19:09:24.722  6777  6777 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-06 19:09:24.722  6777  6777 D AndroidRuntime: readGMSProperty: end
09-06 19:09:24.722  6777  6777 D AndroidRuntime: addProductProperty: start
09-06 19:09:24.732  6780  6780 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:09:24.732  6780  6780 D ActivityThread: Added TimaKeyStore provider
09-06 19:09:24.742  1180  1212 I art     : Background sticky concurrent mark sweep GC freed 8373(417KB) AllocSpace objects, 1(16KB) LOS objects, 0% free, 20MB/20MB, paused 5.592ms total 31.365ms
09-06 19:09:24.792  1180  1180 I KeyguardEffectViewUtil: set current wallpaper info
09-06 19:09:24.792  1003  1223 D SettingsProvider: name = keyguard_current_wallpaper_type
09-06 19:09:24.792  1003  1223 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:24.792  1003  1223 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:24.792  1003  1223 D SettingsProvider: selectionArgs: false
09-06 19:09:24.792  1003  1223 D SettingsProvider: selectionArgs: 10049
09-06 19:09:24.792  1003  1223 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:24.792  1003  1223 D SettingsProvider: ret = -1
09-06 19:09:24.792  1003  1733 D SettingsProvider: name = keyguard_current_wallpaper_file_path
09-06 19:09:24.792  1003  1733 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:24.792  1003  1733 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:24.792  1003  1733 D SettingsProvider: selectionArgs: false
09-06 19:09:24.792  1003  1733 D SettingsProvider: selectionArgs: 10049
09-06 19:09:24.792  1003  1733 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:24.792  1003  1733 D SettingsProvider: ret = -1
09-06 19:09:24.802  1003  1496 D SettingsProvider: name = keyguard_current_wallpaper_res_id
09-06 19:09:24.802  1003  1496 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:24.802  1003  1496 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:24.802  1003  1496 D SettingsProvider: selectionArgs: false
09-06 19:09:24.802  1003  1496 D SettingsProvider: selectionArgs: 10049
09-06 19:09:24.802  1003  1496 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:24.802  1003  1496 D SettingsProvider: ret = -1
09-06 19:09:24.812  6780  6780 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
09-06 19:09:24.812  6780  6780 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
09-06 19:09:24.822  1003  1733 I ActivityManager: Killing 6404:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
09-06 19:09:24.822  1003  1512 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:09:24.822  1003  1512 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
09-06 19:09:24.832  1003  1512 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:24.832  1003  1512 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:24.832  1003  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-06 19:09:24.852  1003  1029 I ActivityManager: Killing 6437:com.samsung.helphub/1000 (adj 15): empty #21
09-06 19:09:24.862  6777  6777 E AffinityControl: AffinityControl: registerfunction enter
09-06 19:09:24.872  1180  1603 D TEST    : run!!!
09-06 19:09:24.872  1003  1479 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:09:24.872  1003  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
09-06 19:09:24.872  1003  1479 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:24.872  1003  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:24.872  1003  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-06 19:09:24.882  1180  1603 I GeometricMosaic_Renderer: setBackgroundBitmap
09-06 19:09:24.892  2805  2805 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Tue Sep 06 19:09:24 GMT+02:00 2016
09-06 19:09:24.892  1003  1029 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-06 19:09:24.892  1003  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
09-06 19:09:24.892  1003  1029 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:24.892  1003  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:24.892  1003  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
09-06 19:09:24.892  6777  6777 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-06 19:09:24.892  2805  2805 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
09-06 19:09:24.902  1003  1223 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
09-06 19:09:24.902  1003  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:24.902  1003  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:24.902  1003  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:24.902  1003  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:24.902  2805  2805 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
09-06 19:09:24.902  2805  2805 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
09-06 19:09:24.912  2805  2805 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
09-06 19:09:24.912  2805  6804 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
09-06 19:09:24.912  2805  6804 I KLMS-2.5.123: : KLMSIntentService(): TIME_CHANGED
09-06 19:09:24.912  6806  6806 E Zygote  : MountEmulatedStorage()
09-06 19:09:24.912  6806  6806 E Zygote  : v2
09-06 19:09:24.912  6806  6806 I libpersona: KNOX_SDCARD checking this for 10036
09-06 19:09:24.912  6806  6806 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:24.912  6806  6806 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:09:24.912  1003  1137 E PersonaManagerService: inState():  stateMachine is null !!
09-06 19:09:24.922  2805  6804 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().START : Tue Sep 06 19:09:24 GMT+02:00 2016
09-06 19:09:24.922  6806  6806 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:09:24.922  1003  1223 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=6806 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:09:24.922  1003  1137 I PersonaManagerService: PersonaId don't exist
09-06 19:09:24.922  1003  1137 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-06 19:09:24.922  6806  6806 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-06 19:09:24.922  1003  1137 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-06 19:09:24.922  2805  6804 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().END
09-06 19:09:24.942  6806  6806 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:09:24.942  6806  6806 D ActivityThread: Added TimaKeyStore provider
09-06 19:09:24.942  1003  1137 W ActivityManager: mDVFSHelper.acquire()
09-06 19:09:24.942  1003  1137 D FocusedStackFrame: Set to : 0
09-06 19:09:24.952  1003  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:24.952  1003  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:24.952  1003  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:24.952  1003  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:24.952  1003  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-06 19:09:24.952  1003  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-06 19:09:24.962  6822  6822 E Zygote  : MountEmulatedStorage()
09-06 19:09:24.962  6822  6822 E Zygote  : v2
09-06 19:09:24.962  6822  6822 I libpersona: KNOX_SDCARD checking this for 10170
09-06 19:09:24.962  6822  6822 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:24.962  6822  6822 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:09:24.962  1003  1137 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6822 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-06 19:09:24.962  1003  1137 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-06 19:09:24.962  1003  1137 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-06 19:09:24.962  1003  1137 D InputDispatcher: Focused application set to: xxxx
09-06 19:09:24.972  1003  1137 D InputDispatcher: Focus left window: 1506
09-06 19:09:24.972  6777  6777 D AndroidRuntime: Shutting down VM
09-06 19:09:24.972  6822  6822 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:09:24.972  6822  6822 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-06 19:09:24.972  1003  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-06 19:09:24.972  1003  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-06 19:09:24.972  2805  2805 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
09-06 19:09:24.972   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
09-06 19:09:24.992  6822  6822 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:09:24.992  6822  6822 D ActivityThread: Added TimaKeyStore provider
09-06 19:09:25.002  1003  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-06 19:09:25.002  1003  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
09-06 19:09:25.012  1003  1137 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-06 19:09:25.012  1003  1003 V ActivityManager: Display changed displayId=0
09-06 19:09:25.012  1003  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-06 19:09:25.032  1003  1137 D PersonaManager: isKioskContainerExistOnDevice
09-06 19:09:25.042  1003  1003 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-06 19:09:25.052  6806  6806 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@2d262fee
09-06 19:09:25.062  6806  6806 I SA      : [SSP] onCreated
09-06 19:09:25.072   258  1098 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
09-06 19:09:25.072   258   451 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
09-06 19:09:25.072  1506  1506 V ActivityThread: updateVisibility : ActivityRecord{6cf36dc token=android.os.BinderProxy@34fb6cea {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-06 19:09:25.072  1506  1506 D Launcher: onTrimMemory. Level: 20
09-06 19:09:25.092  6806  6806 I SA      : [TPM] There is no property file
09-06 19:09:25.092  6806  6806 I SA      : [SCU] isHaveSA() - false
09-06 19:09:25.092  6806  6806 I SA      : [TPM] getModelProperty : null
09-06 19:09:25.092  6806  6806 I SA      : [TPM] getCSCProperty : null
09-06 19:09:25.092  6806  6806 I SA      : [DM] FLOATING AMOLED FEATURE: true
09-06 19:09:25.092  6806  6806 I SA      : [DM] PRODUCT AMOLED FEATURE: false
09-06 19:09:25.092  6806  6806 I SA      : [DM] TFT FEATURE: false
09-06 19:09:25.102  6806  6806 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
09-06 19:09:25.102  6806  6806 I SA      : [DM] init START
09-06 19:09:25.102  6806  6806 I SA      : [DM] This device is not a Vodafone
09-06 19:09:25.112  6806  6806 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
09-06 19:09:25.112  6806  6806 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
09-06 19:09:25.112  6806  6806 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
09-06 19:09:25.112  6806  6806 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
09-06 19:09:25.112  6806  6806 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
09-06 19:09:25.112  6806  6806 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
09-06 19:09:25.112  6806  6806 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
09-06 19:09:25.122  6806  6806 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 19:09:25.122  6806  6806 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
09-06 19:09:25.122  6806  6806 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
09-06 19:09:25.122  6806  6806 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
09-06 19:09:25.122  6806  6806 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
09-06 19:09:25.122  6806  6806 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
09-06 19:09:25.122  6806  6806 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
09-06 19:09:25.122  6806  6806 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
09-06 19:09:25.122  6806  6806 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
09-06 19:09:25.122  6806  6806 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
09-06 19:09:25.122  6806  6806 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
09-06 19:09:25.122  6806  6806 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
09-06 19:09:25.132  6806  6806 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
09-06 19:09:25.132  6806  6806 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
09-06 19:09:25.132  6806  6806 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
09-06 19:09:25.132  6806  6806 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
09-06 19:09:25.132  6806  6806 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
09-06 19:09:25.132  6806  6806 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
09-06 19:09:25.132  6806  6806 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
09-06 19:09:25.132  6806  6806 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
09-06 19:09:25.132  6806  6806 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
09-06 19:09:25.132  6806  6806 I SA      : [SCU] isHaveSA() - false
09-06 19:09:25.132  6806  6806 I SA      : support phone number id : false
09-06 19:09:25.132  6806  6806 I SA      : [DM] Supports Ref Jpn : true
09-06 19:09:25.132  6806  6806 I SA      : [DM] init END
09-06 19:09:25.152  6822  6822 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
09-06 19:09:25.172  6777  6777 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-06 19:09:25.182  1003  1479 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
09-06 19:09:25.182  1003  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:25.182  1003  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:25.182  1003  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:25.182  1003  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:25.202  6842  6842 E Zygote  : MountEmulatedStorage(),
09-06 19:09:25.202  6842  6842 E Zygote  : v2
09-06 19:09:25.202  1003  1479 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6842 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:09:25.202  6842  6842 I libpersona: KNOX_SDCARD checking this for 10058
09-06 19:09:25.202  1003  1479 I ActivityManager: Killing 5950:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
09-06 19:09:25.202  6842  6842 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:25.202  6842  6842 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:25.202  6822  6822 I cr.library_loader: Time to load native libraries: 15 ms (timestamps 4230-4245)
09-06 19:09:25.202  6822  6822 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-06 19:09:25.202  6842  6842 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:25.212  6842  6842 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:25.232  6842  6842 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:25.232  6842  6842 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:25.242  6822  6822 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {35404ec6}
,09-06 19:09:25.242  6822  6822 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-06 19:09:25.252  6822  6822 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-06 19:09:25.282  6842  6842 I ExternalOEMControlProvider: onCreate
,09-06 19:09:25.292  6822  6822 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-06 19:09:25.292  1003  1223 I ActivityManager: Killing 5453:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
09-06 19:09:25.292  6822  6822 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 19:09:25.292  6842  6859 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,09-06 19:09:25.302  1813  1813 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,09-06 19:09:25.302  1813  1813 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-06 19:09:25.302  1003  1518 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,09-06 19:09:25.302  6822  6822 E SysUtils: ApplicationContext is null in ApplicationStatus
09-06 19:09:25.302  1003  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:25.302  1003  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:25.302  1003  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:25.302  1003  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:25.332  6861  6861 E Zygote  : MountEmulatedStorage(),
09-06 19:09:25.332  6861  6861 E Zygote  : v2
09-06 19:09:25.332  6861  6861 I libpersona: KNOX_SDCARD checking this for 10081
09-06 19:09:25.332  6861  6861 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:25.332  6861  6861 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:25.332  6861  6861 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-06 19:09:25.332  1003  1518 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6861 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:09:25.332  6861  6861 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:25.352  6861  6861 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:25.352  6861  6861 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:25.372  6861  6861 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,09-06 19:09:25.372  6861  6861 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-06 19:09:25.372  6861  6861 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:09:25.372  6861  6861 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-06 19:09:25.372  6861  6861 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,09-06 19:09:25.382  6822  6822 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 19:09:25.382  6822  6822 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 19:09:25.382  6822  6822 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 19:09:25.382  6822  6822 I Adreno-EGL: Local Branch: 
09-06 19:09:25.382  6822  6822 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 19:09:25.382  6822  6822 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 19:09:25.382  6822  6822 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-06 19:09:25.422  1003  1029 D SettingsProvider: name = next_alarm_formatted
09-06 19:09:25.422  1003  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:25.422  1003  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:25.422  1003  1029 D SettingsProvider: selectionArgs: false
09-06 19:09:25.422  1003  1029 D SettingsProvider: selectionArgs: 10081
09-06 19:09:25.422  1003  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:25.422  1003  1029 D SettingsProvider: ret = -1
,09-06 19:09:25.482  6822  6822 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-06 19:09:25.502  6822  6822 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
09-06 19:09:25.502  6822  6822 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-06 19:09:25.512  6822  6822 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
09-06 19:09:25.512  6822  6822 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-06 19:09:25.532  1003  1043 W ActivityManager: Activity pause timeout for ActivityRecord{ca61c13 u0 com.test.thalitest/.MainActivity t163}
,09-06 19:09:25.532  6861  6861 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 111.120ms
,09-06 19:09:25.622  6822  6822 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 19:09:25.632  1003  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-06 19:09:25.632  6822  6822 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-06 19:09:25.632  1003  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:25.632  1003  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:25.632  1003  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:25.632  1003  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:25.642  6822  6822 D PhoneWindow: *FMB* installDecor mIsFloating : false,
09-06 19:09:25.642  6822  6822 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-06 19:09:25.642  6894  6894 E Zygote  : MountEmulatedStorage(),
09-06 19:09:25.652  6894  6894 E Zygote  : v2
09-06 19:09:25.652  6894  6894 I libpersona: KNOX_SDCARD checking this for 10090
09-06 19:09:25.652  6894  6894 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:25.652  6894  6894 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:25.652  6894  6894 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:25.652  6894  6894 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:09:25.652  6822  6822 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
09-06 19:09:25.652  1003  1030 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6894 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
09-06 19:09:25.652  1003  1030 I ActivityManager: Killing 6459:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,09-06 19:09:25.662  6822  6822 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 19:09:25.662  6822  6822 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 19:09:25.672   312   312 I art     : Explicit concurrent mark sweep GC freed 8683(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 625us total 22.665ms
,09-06 19:09:25.672  6894  6894 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:25.672  6894  6894 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:25.692   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 579us total 16.752ms
,09-06 19:09:25.702  6894  6894 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,09-06 19:09:25.702  6894  6894 D elm:15121: ELMEngine.ELMEngine( context ).
,09-06 19:09:25.702  6894  6894 D elm:15121: MDMBridge.setEnterpriseBridge()
,09-06 19:09:25.702  1003  1029 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,09-06 19:09:25.702  1003  1029 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-06 19:09:25.712  1003  1029 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:25.712  1003  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:25.712  1003  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-06 19:09:25.712   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 576us total 18.413ms
,09-06 19:09:25.712  6894  6894 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,09-06 19:09:25.712  1003  1512 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,09-06 19:09:25.712  1003  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:25.712  1003  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:25.712  6894  6894 D elm:15121: ElmAgentService : onCreate()
09-06 19:09:25.712  1003  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:25.712  1003  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:25.712  6894  6913 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,09-06 19:09:25.712  6894  6913 D elm:15121: ELMAgentService.listeningToTimeDateChanges( context, intent ).
,09-06 19:09:25.722  6894  6894 D elm:15121: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,09-06 19:09:25.722  6894  6894 D elm:15121: ModuleBase.ModifySetAlarm()
09-06 19:09:25.722  6894  6894 D elm:15121: MDMBridge.getInstance()
09-06 19:09:25.722  6894  6894 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-06 19:09:25.732  6915  6915 E Zygote  : MountEmulatedStorage()
09-06 19:09:25.732  6915  6915 I libpersona: KNOX_SDCARD checking this for 10130
09-06 19:09:25.732  6915  6915 E Zygote  : v2
09-06 19:09:25.732  6915  6915 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:25.732  6915  6915 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:25.732  1003  1512 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6915 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,09-06 19:09:25.732  6915  6915 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:25.732  6915  6915 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
,09-06 19:09:25.742  6894  6894 D elm:15121: ElmAgentService : onDestroy().,
,09-06 19:09:25.742  1003  1479 I ActivityManager: Killing 6517:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,09-06 19:09:25.752  6915  6915 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:25.752  6915  6915 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:25.762  6915  6915 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-06 19:09:25.762  6915  6915 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,09-06 19:09:25.782  1003  1029 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,09-06 19:09:25.782  1003  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:25.782  1003  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:25.782  1003  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:25.782  1003  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:25.792  6494  6494 I Mms/MmsApp:  start initViewCache mms
,09-06 19:09:25.792  6494  6494 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1944.124634
09-06 19:09:25.792  6494  6494 D Mms/ComposeMessageFragment: fillCache, easy = false
,09-06 19:09:25.792  6822  6930 D OpenGLRenderer: Render dirty regions requested: true
09-06 19:09:25.802  6931  6931 E Zygote  : MountEmulatedStorage()
09-06 19:09:25.802  6931  6931 E Zygote  : v2
09-06 19:09:25.802  6931  6931 I libpersona: KNOX_SDCARD checking this for 10131
09-06 19:09:25.802  6931  6931 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:25.802  6931  6931 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:25.802  6931  6931 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:25.802  6931  6931 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:25.812  1003  1029 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6931 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,09-06 19:09:25.812  1003  1029 I ActivityManager: Killing 6050:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,09-06 19:09:25.812  1003  1479 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-06 19:09:25.812  1003  1479 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-06 19:09:25.812  1003  1479 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-06 19:09:25.812  1003  1003 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-06 19:09:25.812  1003  1003 D PersonaManagerService: getPersonasForUser(): returning null!
,09-06 19:09:25.822  6822  6885 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,09-06 19:09:25.822  6822  6822 V ActivityThread: updateVisibility : ActivityRecord{1450df81 token=android.os.BinderProxy@3d41228b {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-06 19:09:25.822  6822  6822 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-06 19:09:25.822  6822  6822 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-06 19:09:25.832  6931  6931 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:25.832  6931  6931 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:25.842   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,09-06 19:09:25.862  1003  1029 D InputDispatcher: Focus entered window: 6822
,09-06 19:09:25.862  6931  6931 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-06 19:09:25.862  6931  6931 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:09:25.862  6931  6931 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-06 19:09:25.862  1003  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-06 19:09:25.862  6822  6822 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-06 19:09:25.862  6822  6930 I OpenGLRenderer: Initialized EGL, version 1.4
09-06 19:09:25.862  1003  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 19:09:25.872  6822  6930 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
09-06 19:09:25.872  6822  6930 D OpenGLRenderer: Enabling debug mode 0
,09-06 19:09:25.892  1003  1518 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-06 19:09:25.902   291   291 E SMD     : DCD OFF
,09-06 19:09:25.902  1180  1180 D PanelView: There is/are notification(s) 
,09-06 19:09:25.902  1003  6951 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-06 19:09:25.912  1003  1048 I ActivityManager: Displayed Component not be shown by security: +885ms (total +968ms)
09-06 19:09:25.922  1003  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{ca61c13 u0 com.test.thalitest/.MainActivity t163} time:94960
09-06 19:09:25.922  1003  1048 W ActivityManager: mDVFSHelper.release()
,09-06 19:09:25.922  1003  1481 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,09-06 19:09:25.922  1003  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,09-06 19:09:25.922  1003  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:25.922  1003  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:25.922  1003  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-06 19:09:25.922   258   440 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,09-06 19:09:25.922  6494  6494 D AbsListView: Get MotionRecognitionManager
09-06 19:09:25.922   258  1098 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,09-06 19:09:25.922  2673  2687 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,09-06 19:09:25.932  1003  1518 D MotionRecognitionService:  ssp status : false
,09-06 19:09:25.932  6494  6494 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 147.902864
,09-06 19:09:25.942  6822  6822 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,09-06 19:09:25.942  6822  6822 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3d41228b time:94982
,09-06 19:09:25.952  1003  1518 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
09-06 19:09:25.952  1003  1518 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,09-06 19:09:25.952  1003  1518 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:25.952  1003  1518 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:25.952  1003  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-06 19:09:25.952  1003  1481 D ActivityManager: getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,09-06 19:09:25.952  1003  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:25.952  1003  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:25.952  1003  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:25.952  1003  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:25.962  1995  1995 I SamsungIME: getCurrentCandidateView
,09-06 19:09:25.972  6959  6959 E Zygote  : MountEmulatedStorage(),
09-06 19:09:25.972  6959  6959 E Zygote  : v2
09-06 19:09:25.972  6959  6959 I libpersona: KNOX_SDCARD checking this for 10037
09-06 19:09:25.972  6959  6959 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:09:25.972  6959  6959 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:25.972  6959  6959 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:25.972  6959  6959 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-06 19:09:25.982  1003  1481 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6959 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:09:25.982  1003  1496 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,09-06 19:09:25.982  1003  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:25.982  1003  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:25.982  1003  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:25.982  1003  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:25.992  6971  6971 E Zygote  : MountEmulatedStorage()
09-06 19:09:25.992  6971  6971 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:09:25.992  6971  6971 E Zygote  : v2
09-06 19:09:25.992  6971  6971 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:26.002  6971  6971 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:26.002  1003  1496 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.DateTimeChangedReceiver: pid=6971 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
09-06 19:09:26.002  6971  6971 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:26.002  6971  6971 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:26.002  6959  6959 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:09:26.002  6959  6959 D ActivityThread: Added TimaKeyStore provider
09-06 19:09:26.012  6822  6822 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6822
,09-06 19:09:26.032  6971  6971 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:26.032  6971  6971 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:26.042  6959  6959 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,09-06 19:09:26.052  6494  6494 D Mms/BubbleViewCache: fillCache bubble = 1
,09-06 19:09:26.072  6959  6959 I CalendarProvider2: CalendarProvider2.onCreate() called
,09-06 19:09:26.092  6971  6971 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 19:09:26.092  6971  6971 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-06 19:09:26.092  6971  6971 D SecurityLogAgent: StateMachine : Current State = 1
,09-06 19:09:26.102  1003  1512 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,09-06 19:09:26.102  1003  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:26.102  1003  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:26.102  1003  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:26.102  1003  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:26.112  6994  6994 E Zygote  : MountEmulatedStorage()
09-06 19:09:26.112  6994  6994 E Zygote  : v2
09-06 19:09:26.112  6994  6994 I libpersona: KNOX_SDCARD checking this for 10153
09-06 19:09:26.112  6994  6994 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:26.112  6994  6994 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:26.112  1003  1512 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=6994 uid=10153 gids={50153, 9997} abi=armeabi-v7a
,09-06 19:09:26.122  6994  6994 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:09:26.122  1003  1512 I ActivityManager: Killing 6543:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,09-06 19:09:26.122  6994  6994 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:26.132  6994  6994 D TimaKeyStoreProvider: TimaSignature is unavailable,
,09-06 19:09:26.132  6994  6994 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:26.142  1995  1995 D SamsungIME: Dismiss ExpandCandiate
,09-06 19:09:26.152  6994  6994 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-06 19:09:26.162  1003  1137 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,09-06 19:09:26.162  1003  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,09-06 19:09:26.172  1003  1137 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:26.172  1003  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:26.172  1003  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,09-06 19:09:26.172  1003  1029 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,09-06 19:09:26.172  1003  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:26.172  1003  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:26.172  1003  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:26.172  1003  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:26.192  7014  7014 E Zygote  : MountEmulatedStorage()
09-06 19:09:26.192  7014  7014 E Zygote  : v2
09-06 19:09:26.192  7014  7014 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:09:26.192  7014  7014 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:26.192  7014  7014 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:26.192  7014  7014 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:09:26.192  1003  1029 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7014 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-06 19:09:26.192  1003  1029 I ActivityManager: Killing 6583:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,09-06 19:09:26.202  7014  7014 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:26.222  7014  7014 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:26.222  7014  7014 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:26.282  6822  6822 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-06 19:09:26.302  1003  1043 W ProcessCpuTracker: Skipping unknown process pid 6583
,09-06 19:09:26.302  7014  7014 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1473181766310
,09-06 19:09:26.302  7014  7014 D         : TimeServiceNative: User Time to be set is 1473181766311
09-06 19:09:26.302  7014  7014 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
,09-06 19:09:26.302  7014  7014 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
09-06 19:09:26.302  7014  7014 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1473181766311
,09-06 19:09:26.302   324   428 D QC-time-services: Daemon: Connection accepted:time_genoff
,09-06 19:09:26.302   324  7030 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1473181766311
09-06 19:09:26.302   324  7030 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1473181766311, operation = 0
,09-06 19:09:26.312   324  7030 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/4/71 10:52:9
09-06 19:09:26.312   324  7030 D QC-time-services: Daemon:Value read from RTC seconds = 36931929000
09-06 19:09:26.312   324  7030 D QC-time-services: Daemon:new time 1473181766311 
09-06 19:09:26.312   324  7030 D QC-time-services: Daemon: delta 1436249837311 genoff 1436249837311 
09-06 19:09:26.312   324  7030 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249837311 to memory
09-06 19:09:26.312   324  7030 D QC-time-services: Daemon:Opening File: /data/time/ats_2
09-06 19:09:26.312   324  7030 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,09-06 19:09:26.312  7014  7014 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,09-06 19:09:26.322   324  7030 D QC-time-services: Updating the TOD offset
09-06 19:09:26.322   324  7030 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249837311 to memory
09-06 19:09:26.322   324  7030 D QC-time-services: Daemon:Opening File: /data/time/ats_1
,09-06 19:09:26.322   324  7030 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,09-06 19:09:26.332   324  7030 E QC-time-services: Daemon:Update to modem bit set
09-06 19:09:26.332   324  7030 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
09-06 19:09:26.332   324  7030 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120285037311
,09-06 19:09:26.332  7014  7014 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,09-06 19:09:26.332   324   422 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
09-06 19:09:26.332   324   428 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,09-06 19:09:26.332  1003  1523 I ActivityManager: Killing 6565:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,09-06 19:09:26.342  2673  2673 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,09-06 19:09:26.342  2673  2673 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
09-06 19:09:26.352  2673  2673 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,09-06 19:09:26.352  1003  1223 I ActivityManager: Killing 6603:com.sec.pcw.device/1000 (adj 15): empty #21
09-06 19:09:26.352  2673  2673 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,09-06 19:09:26.352  1995  1995 I SamsungIME: getDebugLevel  : 0x4f4c
09-06 19:09:26.352  2673  2673 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,09-06 19:09:26.362  2673  2673 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,09-06 19:09:26.362  2673  2673 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
09-06 19:09:26.362  2673  2673 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,09-06 19:09:26.362  2673  2673 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
09-06 19:09:26.362  2673  2673 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
09-06 19:09:26.362  2673  2673 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,09-06 19:09:26.362  2673  2673 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,09-06 19:09:26.372  2673  2673 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,09-06 19:09:26.372  2673  2673 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,09-06 19:09:26.372  2673  2673 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
09-06 19:09:26.372  2673  2673 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,09-06 19:09:26.372  2673  2673 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,09-06 19:09:26.382  2673  2673 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,09-06 19:09:26.382  6822  6952 D jxcore_app_log: JniHelper::setJavaVM(0xb7d742b0), pthread_self() = -1204814168
,09-06 19:09:26.392  2673  2673 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,09-06 19:09:26.392  2673  2673 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,09-06 19:09:26.392  6822  6952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-06 19:09:26.392  6822  6952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-06 19:09:26.392  6822  6952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-06 19:09:26.392  6822  6952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-06 19:09:26.392  6822  6952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-06 19:09:26.392  6822  6952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bd867ac added. We now have 1 listener(s)
,09-06 19:09:26.402  6822  6952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,09-06 19:09:26.402  6822  6952 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-06 19:09:26.402  6822  6952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:09:26.402  6822  6952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:09:26.402  1995  1995 I SamsungIME: getDebugLevel  : 0x4f4c
,09-06 19:09:26.412  6822  6952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-06 19:09:26.412  6822  6952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-06 19:09:26.412  6822  6952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-06 19:09:26.412  6822  6952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
09-06 19:09:26.412  6822  6952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-06 19:09:26.412  6822  6952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-06 19:09:26.412  6822  6952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-06 19:09:26.412  6822  6952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-06 19:09:26.412  6822  6952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-06 19:09:26.412  6822  6952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-06 19:09:26.412  6822  6952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-06 19:09:26.412  6822  6952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-06 19:09:26.412  6822  6952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-06 19:09:26.412  6822  6952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-06 19:09:26.412  6822  6952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@223c47b added. We now have 1 listener(s)
,09-06 19:09:26.412  6822  6952 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:09:26.412  6822  6952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:09:26.412  6822  6952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-06 19:09:26.412  6822  6952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-06 19:09:26.412  6822  6952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-06 19:09:26.412  6822  6952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-06 19:09:26.422  6822  6952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:09:26.422  1995  1995 I SamsungIME: KeybaordView init() : load resources
,09-06 19:09:26.422  6822  6952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,09-06 19:09:26.432  6822  6952 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-06 19:09:26.432  6822  6952 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:09:26.432  6822  6952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:26.432  6822  6952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:26.432  6822  6952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:26.432  6822  6952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:26.432  6822  6952 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:26.432  6822  6952 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:26.432  6822  6952 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:09:26.432  6822  6952 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-06 19:09:26.432  6822  6952 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:09:26.432  6822  6952 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-06 19:09:26.432  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:26.442  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:26.442  1995  1995 I SamsungIME: getCurrentKeyboard
09-06 19:09:26.442  1995  1995 I SamsungIME: getTextKeyboard
,09-06 19:09:26.462  1995  1995 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-06 19:09:26.462  6822  6822 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-06 19:09:26.842  1003  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-06 19:09:26.842  1003  1496 D BatteryService: level:98, scale:100, status:2, health:2, present:true, voltage: 4177, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-06 19:09:26.842  1003  1496 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-06 19:09:26.842  1003  1496 D BatteryService: stay LED for charging
,09-06 19:09:26.842  1003  1003 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-06 19:09:26.852  1003  1003 I MotionRecognitionService: Plugged
,09-06 19:09:26.852  1003  1003 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 19:09:26.852  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-06 19:09:26.852  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-06 19:09:26.852  1436  1436 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-06 19:09:26.852  1436  1436 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 98
,09-06 19:09:26.862  3204  3204 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-06 19:09:26.862  3204  3344 D HeadsetStateMachine: Disconnected process message: 10
,09-06 19:09:26.872  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:98 status:2 health:2
,09-06 19:09:26.872  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:98 status:2 health:2
,09-06 19:09:26.872  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:98 status:2 health:2
09-06 19:09:26.872  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-06 19:09:26.872  1180  1180 D SViewCoverView: level :98 plugged : 2
,09-06 19:09:27.032  6822  7033 W jxcore-log: Initializing JXcore engine
09-06 19:09:27.032  6822  7033 W jxcore-log: JXcore engine is ready
,09-06 19:09:27.082  1990  1990 E audit   : type=1400 msg=audit(1473181767.082:205): avc:  denied  { ioctl } for  pid=7033 comm="Thread-1281" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2071 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-06 19:09:27.082  1990  1990 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:27.082  1990  1990 E audit   : type=1300 msg=audit(1473181767.082:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9d0588f8 items=0 ppid=312 ppcomm=main pid=7033 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1281" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-06 19:09:27.082  1990  1990 E audit   : type=1320 msg=audit(1473181767.082:205): 
,09-06 19:09:27.102  6822  7033 W jxcore-log: Starting JXcore engine
,09-06 19:09:27.172  6959  6959 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,09-06 19:09:27.172  1003  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:27.172  1003  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:27.172  1003  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,09-06 19:09:27.182  1003  1416 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,09-06 19:09:27.182  1003  1416 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:27.182  1003  1416 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:27.182  1003  1416 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,09-06 19:09:27.182  1003  1523 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:27.182  1003  1523 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:27.182  1003  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,09-06 19:09:27.192  1003  1137 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,09-06 19:09:27.192  1003  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,09-06 19:09:27.192  1003  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:27.192  1003  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:27.192  1003  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-06 19:09:27.202  1003  1518 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:27.202  1003  1518 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:27.202  1003  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,09-06 19:09:27.212  6822  7033 W jxcore-log: Platform android
09-06 19:09:27.212  6822  7033 W jxcore-log: 
,09-06 19:09:27.212  6822  7033 W jxcore-log: Process ARCH arm
09-06 19:09:27.212  6822  7033 W jxcore-log: 
,09-06 19:09:27.212  1003  1481 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
09-06 19:09:27.212  1003  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,09-06 19:09:27.212  1003  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:27.212  1003  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:27.212  1003  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-06 19:09:27.222  1003  1496 I ActivityManager: Killing 6610:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,09-06 19:09:27.422  6822  7033 I jxcore-log: JXcore Cordova bridge is ready!
09-06 19:09:27.422  6822  7033 I jxcore-log: 
,09-06 19:09:27.422  6822  7033 W jxcore-log: JXcore engine is started
,09-06 19:09:27.432  6822  6952 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-06 19:09:27.432  6822  6822 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-06 19:09:28.242   269   269 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb75b97c8,
09-06 19:09:28.242   269   269 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
09-06 19:09:28.242   269   269 I rmt_storage: wakelock acquired: 1, error no: 42
09-06 19:09:28.242   269   333 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1218734792),
,09-06 19:09:28.292   269   333 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
09-06 19:09:28.292   269   333 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
09-06 19:09:28.292   269   333 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1218734792) wakelock released: 1, error no: 0
09-06 19:09:28.292   269   333 I rmt_storage: 
,09-06 19:09:28.292   269   269 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb75b97c8
,09-06 19:09:28.442  1003  3371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-06 19:09:28.732  1683  1683 I ConfigService: onDestroy
,09-06 19:09:28.902   291   291 E SMD     : DCD OFF,
,09-06 19:09:31.902   291   291 E SMD     : DCD OFF
,09-06 19:09:33.252  1003  3354 D SSRM:n  : SIOP:: AP = 400,
,09-06 19:09:33.442  1003  3371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-06 19:09:34.282  1003  1058 D PackageManager: [MSG] MCS_UNBIND
,09-06 19:09:34.282  1003  1512 I ActivityManager: Killing 5998:com.android.vending/u0a26 (adj 15): empty #21
,09-06 19:09:34.902   291   291 E SMD     : DCD OFF
,09-06 19:09:34.952  1003  1058 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,09-06 19:09:36.892  1003  1523 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-06 19:09:36.892  1003  1523 D BatteryService: level:98, scale:100, status:2, health:2, present:true, voltage: 4231, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-06 19:09:36.892  1003  1523 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-06 19:09:36.892  1003  1523 D BatteryService: stay LED for charging
09-06 19:09:36.892  1003  1003 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-06 19:09:36.892  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-06 19:09:36.892  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-06 19:09:36.892  1003  1003 I MotionRecognitionService: Plugged
09-06 19:09:36.892  1003  1003 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 19:09:36.902  1436  1436 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-06 19:09:36.902  1436  1436 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 98
,09-06 19:09:36.912  3204  3204 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-06 19:09:36.912  3204  3344 D HeadsetStateMachine: Disconnected process message: 10
,09-06 19:09:36.922  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:98 status:2 health:2
,09-06 19:09:36.922  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:98 status:2 health:2
,09-06 19:09:36.922  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:98 status:2 health:2
,09-06 19:09:36.922  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-06 19:09:36.922  1180  1180 D SViewCoverView: level :98 plugged : 2
,09-06 19:09:37.902   291   291 E SMD     : DCD OFF
,09-06 19:09:38.122  1003  1096 V AlarmManager: waitForAlarm result :4,
09-06 19:09:38.122  1003  1096 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,09-06 19:09:38.132  1003  1096 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-06 19:09:38.132  1003  1096 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:38.132  1003  1096 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:38.132  1003  1096 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:38.142  7042  7042 E Zygote  : MountEmulatedStorage(),
09-06 19:09:38.142  1003  1096 I ActivityManager: Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7042 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:09:38.142  7042  7042 E Zygote  : v2
09-06 19:09:38.142  7042  7042 I libpersona: KNOX_SDCARD checking this for 10026
09-06 19:09:38.142  7042  7042 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:38.152  7042  7042 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-06 19:09:38.152  7042  7042 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 19:09:38.152  7042  7042 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:09:38.172  7042  7042 D TimaKeyStoreProvider: TimaSignature is unavailable,
,09-06 19:09:38.172  7042  7042 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:38.252  7042  7042 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-06 19:09:38.262  7042  7042 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-06 19:09:38.292  7042  7042 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-06 19:09:38.302  7042  7042 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-06 19:09:38.382  7042  7042 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-06 19:09:38.382  7042  7042 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-06 19:09:38.392  7042  7042 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-06 19:09:38.392  7042  7042 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-06 19:09:38.402  7042  7042 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-06 19:09:38.402  7042  7042 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-06 19:09:38.402  7042  7042 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-06 19:09:38.402  7042  7042 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-06 19:09:38.402  7042  7042 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-06 19:09:38.402  7042  7042 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-06 19:09:38.412  7042  7042 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-06 19:09:38.412  7042  7042 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-06 19:09:38.412  7042  7042 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-06 19:09:38.412  7042  7042 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-06 19:09:38.412  7042  7042 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-06 19:09:38.412  7042  7042 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-06 19:09:38.422  7042  7042 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,09-06 19:09:38.432  7042  7042 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-06 19:09:38.432  7042  7042 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-06 19:09:38.452  7042  7042 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-06 19:09:38.452  7042  7042 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-06 19:09:38.452  7042  7042 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,09-06 19:09:38.482  7042  7042 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-06 19:09:38.482  7042  7079 D Ads     : Skipping gmscore version check
09-06 19:09:38.482  1003  1733 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
09-06 19:09:38.482  1003  1733 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,09-06 19:09:38.482  1003  1733 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:38.482  1003  1733 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:38.482  1003  1733 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,09-06 19:09:38.492  1003  1496 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:38.502  7042  7042 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-06 19:09:38.502  1003  1496 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:38.502  1003  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:09:38.502  1003  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-06 19:09:38.512  7042  7042 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-06 19:09:38.622  1003  1523 I art     : Explicit concurrent mark sweep GC freed 25314(1478KB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 22MB/34MB, paused 2.383ms total 144.255ms
,09-06 19:09:38.832  1003  1330 E Watchdog: !@Sync 3
,09-06 19:09:38.852  7042  7076 D Finsky  : [1325] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,09-06 19:09:38.862  7042  7042 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,09-06 19:09:38.862  1003  1030 I ActivityManager: Killing 6656:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,09-06 19:09:39.872  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-06 19:09:39.872  6822  7033 I jxcore-log: 
,09-06 19:09:39.872  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-06 19:09:39.872  6822  7033 I jxcore-log: 
,09-06 19:09:39.882  6822  7033 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:09:39.882  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:39.882  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:39.882  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:39.882  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:39.882  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:39.882  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:39.882  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:09:39.882  6822  7033 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:09:39.882  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-06 19:09:39.882  6822  7033 I jxcore-log: 
,09-06 19:09:39.892  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-06 19:09:39.892  6822  7033 I jxcore-log: 
,09-06 19:09:39.902   322   322 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
09-06 19:09:39.902   322   322 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-06 19:09:40.532  6822  7033 D executeNativeTests: Running unit tests
,09-06 19:09:40.622  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:09:40.622  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38affb7c added. We now have 2 listener(s)
,09-06 19:09:40.622  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-06 19:09:40.622  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:09:40.622  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:09:40.622  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:09:40.622  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 added. We now have 2 listener(s)
09-06 19:09:40.622  6822  7033 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:09:40.622  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:09:40.632  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:09:40.632  6822  7033 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:09:40.632  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:40.632  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:40.632  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:40.632  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:40.632  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:40.632  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:40.632  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:09:40.632  6822  7033 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:09:40.632  6822  7033 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:09:40.642  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 19:09:40.642  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:40.642  6822  7033 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:09:40.642  6822  7033 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-06 19:09:40.642  6822  7033 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-06 19:09:40.642  6822  7033 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 19:09:40.642  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:09:40.642  6822  7033 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:09:40.642  6822  7033 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:09:40.642  6822  7033 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:09:40.642  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:40.642  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:09:40.642  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:40.642  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.642  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:09:40.642  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:09:40.642  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38affb7c removed from the list
09-06 19:09:40.642  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.642  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 removed from the list
,09-06 19:09:40.642  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:40.642  6822  7033 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:40.642  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:40.642  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.642  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:40.642  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:40.642  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:40.642  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.642  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
,09-06 19:09:40.642  6822  7033 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-06 19:09:40.652  6822  7033 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:40.652  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:40.652  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:40.652  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:40.652  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.652  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.652  6822  7033 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38affb7c not in the list
09-06 19:09:40.652  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.652  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:40.652  6822  7033 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:40.652  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.652  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.652  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.652  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:40.652  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:40.652  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:40.652  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.652  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
,09-06 19:09:40.652  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-06 19:09:40.652  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 19:09:40.652  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Pee,r: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 19:09:40.662  6822  7033 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:40.662  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:40.662  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:40.662  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:40.662  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.662  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.662  6822  7033 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38affb7c not in the list
09-06 19:09:40.662  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.662  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:40.662  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.662  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.662  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.662  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.662  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:40.662  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:40.662  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.662  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:40.662  6822  7033 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 19:09:40.662  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:09:40.662  6822  7033 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:09:40.662  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:40.662  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:40.662  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:40.662  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:40.662  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:40.662  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:40.662  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:09:40.662  6822  7033 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:40.662  6822  7033 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:09:40.672  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:09:40.672  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:09:40.672  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:09:40.672  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:09:40.672  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:09:40.672  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:40.672  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:40.672  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:09:40.682  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:09:40.682  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 19:09:40.692  6822  7033 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-06 19:09:40.692  6822  7033 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-06 19:09:40.692  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 19:09:40.692  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:09:40.692  6822  7033 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-06 19:09:40.702  3204  3219 D BtGatt.GattService: registerClient() - UUID=238396d8-d242-48aa-af5c-c3f7c16d0181
,09-06 19:09:40.752  3204  3282 D BtGatt.GattService: onClientRegistered() - UUID=238396d8-d242-48aa-af5c-c3f7c16d0181, clientIf=6
,09-06 19:09:40.752  6822  6836 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:09:40.752  3204  3357 D BtGatt.GattService: start scan with filters
,09-06 19:09:40.752  3204  3340 D BtGatt.ScanManager: handling starting scan
,09-06 19:09:40.752  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:09:40.752  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:09:40.752  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:09:40.752  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:09:40.762  3204  3340 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
,09-06 19:09:40.762  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:09:40.772  6822  6822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:09:40.772  3204  3282 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 19:09:40.772  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:40.772  3204  3340 D BtGatt.ScanManager: allow scan with filters
,09-06 19:09:40.772  3204  3340 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-06 19:09:40.772  3204  3340 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-06 19:09:40.772  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:09:40.782  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:09:40.782  3204  3282 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-06 19:09:40.782  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:40.782  3204  3340 D BtGatt.ScanManager: Starting BLE batch scan
,09-06 19:09:40.782  3204  3340 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:09:40.792  6822  7033 I io.jxcore.node.ConnectionHelper: start: OK
,09-06 19:09:40.792  3204  3282 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-06 19:09:40.792  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:40.792  6822  7033 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:09:40.792  6822  7033 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-06 19:09:40.792  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:40.792  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-06 19:09:40.792  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.802  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:09:40.802  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:09:40.802  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:09:40.802  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:09:40.802  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-06 19:09:40.802  3204  3282 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-06 19:09:40.802  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:40.802  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:09:40.802  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:09:40.802  3204  3217 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:09:40.802  3204  3340 D BtGatt.ScanManager: filter size is 1
,09-06 19:09:40.802  3204  3340 D BtGatt.ScanManager: delete FilterIndex - 3
,09-06 19:09:40.802  3204  3357 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:09:40.812  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-06 19:09:40.812  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:09:40.812  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:09:40.812  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:09:40.812  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:09:40.812  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:09:40.812  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:09:40.812  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:09:40.812  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:09:40.812  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:09:40.812  3204  3282 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
09-06 19:09:40.812  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:40.812  3204  3340 D BtGatt.ScanManager: stopping BLe Batch
09-06 19:09:40.812  6822  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:09:40.812  6822  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:09:40.812  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:40.812  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.812  6822  6822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:09:40.812  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:09:40.812  6822  7033 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38affb7c not in the list
,09-06 19:09:40.812  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.812  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:40.812  6822  7033 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:40.812  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:40.812  6822  7033 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 19:09:40.812  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:09:40.822  3204  3282 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-06 19:09:40.822  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:09:40.822  3204  3340 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 19:09:40.822  3204  3282 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-06 19:09:40.822  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:40.822  6822  7033 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:09:40.822  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:40.822  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:40.822  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:40.822  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:40.822  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:40.822  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:40.822  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:09:40.822  6822  7033 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:09:40.822  6822  7033 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:09:40.822  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:09:40.822  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:09:40.822  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:09:40.822  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:09:40.822  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:09:40.832  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:40.832  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:40.832  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:09:40.832  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:09:40.842  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:09:40.842  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:09:40.842  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-06 19:09:40.842  6822  7033 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:09:40.842  3204  3357 D BtGatt.GattService: registerClient() - UUID=b2ba41fa-c89f-4aed-ad37-425e61c84032
,09-06 19:09:40.882  3204  3282 D BtGatt.GattService: onClientRegistered() - UUID=b2ba41fa-c89f-4aed-ad37-425e61c84032, clientIf=6
,09-06 19:09:40.882  6822  6834 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:09:40.892  3204  3339 D BtGatt.GattService: start scan with filters
,09-06 19:09:40.892  3204  3340 D BtGatt.ScanManager: handling starting scan
,09-06 19:09:40.892  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 19:09:40.892  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:09:40.892  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:09:40.892  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:09:40.892  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:09:40.902  6822  6822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:09:40.902  3204  3282 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 19:09:40.902  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:40.902  3204  3340 D BtGatt.ScanManager: allow scan with filters
,09-06 19:09:40.902  3204  3340 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-06 19:09:40.902  3204  3340 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-06 19:09:40.902  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:09:40.902  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:09:40.902   291   291 E SMD     : DCD OFF
,09-06 19:09:40.912  3204  3282 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
09-06 19:09:40.912  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:40.912  3204  3340 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:09:40.912  3204  3340 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-06 19:09:40.912  6822  7033 I io.jxcore.node.ConnectionHelper: start: OK,
,09-06 19:09:40.912  3204  3282 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-06 19:09:40.912  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:40.922  6822  7033 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:09:40.922  6822  7033 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:09:40.922  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:40.922  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:09:40.922  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.922  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:09:40.922  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:09:40.922  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:09:40.922  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:09:40.922  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:09:40.922  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:09:40.922  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:09:40.922  3204  3217 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:09:40.922  3204  3282 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-06 19:09:40.922  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:40.932  3204  3340 D BtGatt.ScanManager: filter size is 1
09-06 19:09:40.932  3204  3340 D BtGatt.ScanManager: delete FilterIndex - 4
,09-06 19:09:40.932  3204  3339 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:09:40.932  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:09:40.932  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:09:40.932  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:09:40.932  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:09:40.932  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:09:40.932  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:09:40.932  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
09-06 19:09:40.932  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-06 19:09:40.932  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:09:40.932  3204  3282 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-06 19:09:40.932  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:40.932  3204  3340 D BtGatt.ScanManager: stopping BLe Batch
09-06 19:09:40.932  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:09:40.942  6822  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:09:40.942  6822  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:09:40.942  6822  6822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:09:40.942  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:09:40.942  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:40.942  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:09:40.942  6822  7033 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38affb7c not in the list
09-06 19:09:40.942  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:40.942  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:40.942  6822  7033 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:40.942  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:40.942  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:09:40.942  3204  3282 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-06 19:09:40.942  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:09:40.942  3204  3340 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 19:09:40.942  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:40.942  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:09:40.942  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:40.952  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:09:40.952  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
,09-06 19:09:40.952  6822  7033 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-06 19:09:40.952  3204  3282 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-06 19:09:40.952  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:40.952  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:09:40.962  6822  7033 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:09:40.962  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:40.962  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:40.962  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:40.962  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:40.962  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:40.962  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:40.962  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:09:40.962  6822  7033 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:09:40.962  6822  7033 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:09:40.962  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:09:40.962  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only,
09-06 19:09:40.962  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:09:40.962  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:09:40.962  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:09:40.972  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:40.972  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:09:40.972  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-06 19:09:40.972  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:09:40.972  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:09:40.982  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:09:40.982  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:09:40.982  6822  7033 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:09:40.982  3204  3357 D BtGatt.GattService: registerClient() - UUID=a3b918a5-7ef1-452f-a075-455ae5802922
,09-06 19:09:41.022  3204  3282 D BtGatt.GattService: onClientRegistered() - UUID=a3b918a5-7ef1-452f-a075-455ae5802922, clientIf=6
,09-06 19:09:41.022  6822  6834 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-06 19:09:41.022  3204  3217 D BtGatt.GattService: start scan with filters
,09-06 19:09:41.022  3204  3340 D BtGatt.ScanManager: handling starting scan
,09-06 19:09:41.032  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 19:09:41.032  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:09:41.032  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:09:41.032  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:09:41.032  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:09:41.032  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 19:09:41.032  6822  6822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:09:41.032  3204  3282 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 19:09:41.032  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:41.032  3204  3340 D BtGatt.ScanManager: allow scan with filters
,09-06 19:09:41.032  3204  3340 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-06 19:09:41.032  3204  3340 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-06 19:09:41.042  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:09:41.042  6822  7033 I io.jxcore.node.ConnectionHelper: start: OK
,09-06 19:09:41.042  3204  3282 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-06 19:09:41.042  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:41.042  3204  3340 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:09:41.042  3204  3340 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:09:41.042  6822  7033 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:09:41.042  6822  7033 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-06 19:09:41.042  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:41.042  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-06 19:09:41.042  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.042  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:09:41.042  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-06 19:09:41.042  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:09:41.042  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-06 19:09:41.042  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:09:41.052  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:09:41.052  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:09:41.052  3204  3357 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:09:41.052  3204  3282 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-06 19:09:41.052  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:41.052  3204  3217 D BtGatt.GattService: unregisterClient() - clientIf=6,
,09-06 19:09:41.062  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:09:41.062  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:09:41.062  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:09:41.062  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:09:41.062  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:09:41.062  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:09:41.062  3204  3282 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-06 19:09:41.062  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:09:41.062  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:09:41.062  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:09:41.062  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:09:41.062  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:09:41.062  3204  3340 D BtGatt.ScanManager: filter size is 1
,09-06 19:09:41.062  3204  3340 D BtGatt.ScanManager: delete FilterIndex - 5
,09-06 19:09:41.072  6822  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:09:41.072  6822  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:09:41.072  6822  6822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:09:41.072  6822  7033 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:41.072  6822  7033 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-06 19:09:41.072  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:41.072  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:41.072  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:41.072  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.072  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:09:41.072  6822  7033 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38affb7c not in the list
,09-06 19:09:41.072  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.072  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:41.072  6822  7033 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:41.072  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.072  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.072  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:41.072  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:41.072  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:41.072  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.072  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:41.072  6822  7033 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-06 19:09:41.072  6822  7033 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:41.072  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:41.072  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:41.072  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:41.072  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.072  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.072  6822  7033 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38affb7c not in the list
09-06 19:09:41.072  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.072  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:41.072  6822  7033 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:41.072  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.072  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.072  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.072  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.072  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:41.072  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:41.072  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.072  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:41.072  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 19:09:41.072  6822  7033 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:41.072  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:41.072  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:41.072  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:41.072 , 6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.072  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.072  6822  7033 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38affb7c not in the list
09-06 19:09:41.072  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.072  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:41.072  6822  7033 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:41.072  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.072  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.072  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.072  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.072  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:41.072  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:41.072  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.072  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:41.072  3204  3282 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-06 19:09:41.072  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:09:41.072  3204  3340 D BtGatt.ScanManager: stopping BLe Batch
09-06 19:09:41.072  6822  7033 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-06 19:09:41.072  6822  7033 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:41.072  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:41.072  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:41.072  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:41.072  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.072  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-06 19:09:41.072  6822  7033 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38affb7c not in the list
09-06 19:09:41.072  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.072  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:41.072  6822  7033 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:09:41.072  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.072  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.072  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.072  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.082  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:41.082  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:41.082  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.082  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
,09-06 19:09:41.082  6822  7033 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-06 19:09:41.082  6822  7033 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:41.082  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:41.082  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:41.082  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:41.082  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.082  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.082  6822  7033 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38affb7c not in the list
09-06 19:09:41.082  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.082  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:41.082  6822  7033 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:41.082  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.082  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.082  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.082  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:41.082  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:41.082  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-06 19:09:41.082  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.082  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
,09-06 19:09:41.082  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-06 19:09:41.082  3204  3282 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-06 19:09:41.082  6822  7033 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-06 19:09:41.082  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-06 19:09:41.082  6822  7033 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:09:41.082  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-06 19:09:41.082  6822  7033 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:09:41.082  6822  7033 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:41.082  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:09:41.082  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:41.082  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:41.082  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.082  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.082  6822  7033 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38affb7c not in the list
09-06 19:09:41.082  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.082  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:41.082  6822  7033 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:41.082  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.082  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:41.082  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.082  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.082  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:09:41.082  3204  3340 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-06 19:09:41.092  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-06 19:09:41.092  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:41.092  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.092  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:41.092  6822  7033 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:09:41.092  6822  7033 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-06 19:09:41.092  6822  7033 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:09:41.092  6822  7033 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910],
09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 19:09:41.092  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 19:09:41.092  6822  7033 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-06 19:09:41.092  6822  7033 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:09:41.092  6822  7033 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-06 19:09:41.092  6822  7033 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:09:41.092  6822  7033 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:09:41.092  6822  7033 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-06 19:09:41.092  6822  7033 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:09:41.092  6822  7033 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:09:41.092  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-06 19:09:41.092  3204  3282 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 19:09:41.092  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:09:41.092  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-06 19:09:41.092  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-06 19:09:41.092  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-06 19:09:41.092  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-06 19:09:41.092  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-06 19:09:41.092  6822  7033 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-06 19:09:41.092  6822  7033 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:09:41.092  6822  7033 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-06 19:09:41.092  6822  7033 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:41.092  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:41.092  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:41.092  6822  7085 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1345)
09-06 19:09:41.092  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:41.092  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.092  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.092  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-06 19:09:41.102  6822  7033 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38affb7c not in the list
09-06 19:09:41.102  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.102  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:41.102  6822  7033 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:41.102  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.102  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.102  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.102  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.102  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:41.102  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:41.102  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.102  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:41.102  6822  7086 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1345
09-06 19:09:41.102  6822  7033 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-06 19:09:41.102  6822  7033 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:41.102  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:41.102  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:41.102  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:41.102  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.102  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.102  6822  7033 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38affb7c not in the list
09-06 19:09:41.102  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.102  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:41.102  6822  7033 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:41.102  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.102  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.102  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.102  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.102  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:41.102  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:41.102  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.102  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
,09-06 19:09:41.102  6822  7033 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-06 19:09:41.102  6822  7033 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:41.102  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:09:41.102  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:41.102  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:41.102  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.102  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.102  6822  7033 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38affb7c not in the list
09-06 19:09:41.102  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.102  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:41.102  6822  7033 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:41.102  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.102  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:41.102  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.102  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.102  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:41.102  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:41.102  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.102  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
,09-06 19:09:41.102  6822  7033 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-06 19:09:41.102  6822  7033 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-06 19:09:41.102  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:09:41.102  6822  7033 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-06 19:09:41.102  6822  7033 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 19:09:41.102  6822  7033 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-06 19:09:41.102  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:09:41.102  6822  7033 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-06 19:09:41.102  6822  7033 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 19:09:41.102  6822  7033 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 19:09:41.102  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:09:41.102  6822  7033 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-06 19:09:41.102  6822  7033 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:41.102  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:41.102  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:41.102  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:41.102  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.102  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.102  6822  7033 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38affb7c not in the list
09-06 19:09:41.102  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.102  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:41.102  6822  7033 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:41.102  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.102  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.102  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.102  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:41.102  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:41.102  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:41.112  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.112  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:41.112  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:41.112  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.112  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.112  6822  7033 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38affb7c not in the list
09-06 19:09:41.112  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.112  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:41.112  6822  7033 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:41.112  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.112  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.112  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.112  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:41.112  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:41.112  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.112  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.112  6822  7033 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38affb7c not in the list
09-06 19:09:41.112  6822  7033 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-06 19:09:41.112  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:41.112  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:41.112  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:41.112  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.112  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.112  6822  7033 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38affb7c not in the list
09-06 19:09:41.112  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.112  6822  7085 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-06 19:09:41.112  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:41.112  6822  7033 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:41.112  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.112  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.112  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.112  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.112  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:41.112  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:41.112  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.112  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:41.112  6822  7085 D BluetoothSocket: connect(): myUserId = 0
09-06 19:09:41.112  6822  7085 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:09:41.112  6822  7033 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-06 19:09:41.112  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:09:41.112  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-06 19:09:41.112  6822  7033 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-06 19:09:41.112  6822  7033 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-06 19:09:41.112  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-06 19:09:41.112  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:09:41.112  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:41.112  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-06 19:09:41.112  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-06 19:09:41.112  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-06 19:09:41.112  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.112  6822  7033 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-06 19:09:41.112  6822  7033 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38affb7c not in the list
09-06 19:09:41.112  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.112  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:09:41.112  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:09:41.112  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:09:41.112  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.112  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.112  6822  6822 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-06 19:09:41.112  6822  6822 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-06 19:09:41.112  3204  3357 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:09:41.112  6822  7085 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
09-06 19:09:41.112  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:09:41.112  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:41.112  6822  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:09:41.112  6822  7033 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:41.112  6822  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:09:41.112  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:41.112  6822  6822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:09:41.112  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:41.112  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:41.112  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.112  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.112  6822  7033 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38affb7c not in the list
09-06 19:09:41.112  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.112  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:41.112  6822  7033 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:41.112  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.112  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.112  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.112  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.112  6822  7087 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-06 19:09:41.112  6822  7087 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-06 19:09:41.122  6822  6822 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-06 19:09:41.122  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:41.122  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:41.122  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.122  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
,09-06 19:09:41.122  6822  7033 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-06 19:09:41.122  6822  7033 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 19:09:41.122  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:09:41.122  6822  7033 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:09:41.122  6822  7033 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:41.122  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:41.122  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:41.122  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:41.122  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.122  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.122  6822  7033 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38affb7c not in the list
09-06 19:09:41.122  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.122  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:41.122  6822  7033 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:41.122  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.122  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.122  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.122  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:41.122  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:41.122  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:41.122  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.122  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
,09-06 19:09:41.122  6822  7033 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:09:41.122  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:41.122  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:41.122  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:41.122  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.122  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.122  6822  7033 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38affb7c not in the list
09-06 19:09:41.122  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:09:41.122  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:41.122  6822  7033 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:41.122  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.122  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.122  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.122  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.122  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:41.122  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:41.122  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.122  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
,09-06 19:09:41.132  6822  7033 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:41.132  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:09:41.132  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:41.132  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:09:41.132  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.132  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.132  6822  7033 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38affb7c not in the list
09-06 19:09:41.132  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.132  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:41.132  6822  7033 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:41.132  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:41.132  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.132  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:09:41.132  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:41.132  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:41.132  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:41.132  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:41.132  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f760c05 not in the list
09-06 19:09:41.132  6822  7033 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-06 19:09:41.132  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:09:41.132  6822  7033 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-06 19:09:41.132  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:09:41.132  6822  7033 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-06 19:09:41.132  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:09:41.132  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 19:09:41.132  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-06 19:09:41.132  6822  7033 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-06 19:09:41.132  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 19:09:41.132  6822  7033 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-06 19:09:41.132  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 19:09:41.132  6822  7033 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-06 19:09:41.132  6822  7033 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-06 19:09:41.132  6822  7033 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-06 19:09:41.132  6822  7033 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-06 19:09:41.132  6822  7033 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-06 19:09:41.132  6822  7033 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-06 19:09:41.132  6822  7033 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-06 19:09:41.132  6822  7033 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-06 19:09:41.132  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:09:41.132  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@485155f added. We now have 2 listener(s)
09-06 19:09:41.132  6822  7033 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:09:41.132  6822  7033 D BluetoothAdapter: enable()
,09-06 19:09:41.132  6822  7033 D BluetoothAdapter: enable(): BT is already enabled..!
,09-06 19:09:41.142  1003  1481 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-06 19:09:41.142  1003  1481 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 19:09:41.142  1003  1481 D SecContentProvider2: mCursor = null
,09-06 19:09:41.142  1003  1481 D WifiService: setWifiEnabled: true pid=6822, uid=10170
09-06 19:09:41.142  1003  1481 W ActivityManager: Permission Denial: getCurrentUser() from pid=6822, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-06 19:09:41.142  1003  1481 W WifiService: Failed getting userId using ActivityManagerNative
09-06 19:09:41.142  1003  1481 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6822, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:09:41.142  1003  1481 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 19:09:41.142  1003  1481 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-06 19:09:41.142  1003  1481 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-06 19:09:41.142  1003  1481 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-06 19:09:41.142  1003  1481 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-06 19:09:41.142  1003  1481 D SettingsProvider: name = wifi_on
,09-06 19:09:41.152  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-06 19:09:41.152  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1fa73bac added. We now have 3 listener(s)
09-06 19:09:41.152  6822  7033 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:09:41.152  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:09:41.152  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@16b0075 added. We now have 4 listener(s)
09-06 19:09:41.152  6822  7033 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:09:41.152  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:09:41.152  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@431080a added. We now have 5 listener(s)
09-06 19:09:41.152  6822  7033 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:09:41.162  1003  1512 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-06 19:09:41.162  1003  1512 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 19:09:41.162  1003  1512 D SecContentProvider2: mCursor = null
,09-06 19:09:41.162  1003  1512 D WifiService: setWifiEnabled: false pid=6822, uid=10170
,09-06 19:09:41.162  1003  1512 D SettingsProvider: name = wifi_on
,09-06 19:09:41.162  1003  1127 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-06 19:09:41.162  6822  7033 D BluetoothAdapter: disable()
,09-06 19:09:41.162  1381  1381 I wpa_supplicant: reset timer : RESET_TIMER 0
09-06 19:09:41.162  1381  1381 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-06 19:09:41.172  1381  1381 I wpa_supplicant: P2P: Current p2p state = IDLE
09-06 19:09:41.172  1381  1381 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-06 19:09:41.172  1003  1496 D SettingsProvider: name = bluetooth_on
,09-06 19:09:41.172  1003  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:09:41.182  3204  3279 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-06 19:09:41.182  3204  3279 D BluetoothAdapterProperties: Setting state to 13
,09-06 19:09:41.182  3204  3279 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 19:09:41.182  3204  3279 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:09:41.182  3204  3279 D BluetoothAdapterService: updateAdapterState state is 13
,09-06 19:09:41.182  1003  1416 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
,09-06 19:09:41.182  1003  1416 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:09:41.192  1003  1416 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.192  1003  1416 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.192  1003  1416 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:41.192  3204  3204 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
09-06 19:09:41.192  3204  3204 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@26903261, channel: 19, state: LISTENING
09-06 19:09:41.192  3204  3204 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@26903261, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@24047aae, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@32c53186mSocket: android.net.LocalSocket@6b11a47 impl:android.net.LocalSocketImpl@29540274 fd:FileDescriptor[82]
09-06 19:09:41.192  3204  3204 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@6b11a47 impl:android.net.LocalSocketImpl@29540274 fd:FileDescriptor[82]
,09-06 19:09:41.192  1003  1127 E WifiNative-wlan0: do suspend true
,09-06 19:09:41.192  3204  3279 D BluetoothAdapterService: Autoconnection is available 
09-06 19:09:41.192  3204  3279 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-06 19:09:41.192  3204  3279 D BluetoothAdapterService: terminating service from this receiver
,09-06 19:09:41.192  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:09:41.202  1003  1518 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:41.202  1003  1518 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-06 19:09:41.202  1003  1518 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.202  1003  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:09:41.202  3204  3279 D BluetoothAdapterProperties: onBluetoothDisable()
09-06 19:09:41.202  3204  3279 D BluetoothAdapterProperties: mDiscovering is false
09-06 19:09:41.202  1003  1523 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-06 19:09:41.202  3204  3279 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-06 19:09:41.202  1003  1003 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:41.202  1003  1003 I InputMethodManagerService: [BT Setting State] State =13
,09-06 19:09:41.202  4809  4809 D BluetoothPbap: Proxy object disconnected
,09-06 19:09:41.212  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:41.212  4809  4809 D PbapServerProfile: Bluetooth service disconnected
09-06 19:09:41.212  6822  7033 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:09:41.212  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:41.212  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:41.212  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:41.212  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:41.212  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:41.212  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:41.212  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:09:41.212  3204  3282 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 19:09:41.212  3204  3282 D BluetoothAdapterProperties: Scan Mode:20
,09-06 19:09:41.212  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:41.212  6822  7033 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:41.212  6822  7033 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:09:41.212  1180  1180 D BluetoothTile:  onBluetoothStateChange:
,09-06 19:09:41.212  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:41.212  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 19:09:41.212  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:41.212  1180  1180 D BluetoothTile:  getBluetoothState : 13
,09-06 19:09:41.212  1995  1995 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:09:41.222  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:41.222  1003  1496 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:09:41.222  4809  4809 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:41.222  1180  1715 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:09:41.222  1003  1223 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 19:09:41.222  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 19:09:41.232  1180  1715 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:09:41.232  1180  1715 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-06 19:09:41.232  3204  3204 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@632e012, channel: 5, state: LISTENING
,09-06 19:09:41.232  3204  3279 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,09-06 19:09:41.232  3204  3279 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
09-06 19:09:41.232  3204  3204 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@632e012, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3a97c729, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3db13e3mSocket: android.net.LocalSocket@28e8d1e0 impl:android.net.LocalSocketImpl@e53cc99 fd:FileDescriptor[80]
09-06 19:09:41.232  3204  3204 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@28e8d1e0 impl:android.net.LocalSocketImpl@e53cc99 fd:FileDescriptor[80]
,09-06 19:09:41.242  6822  7085 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@35226698, channel: -1, state: INIT
09-06 19:09:41.242  6822  7085 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@35226698, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c782ef1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2cdf9ad6mSocket: android.net.LocalSocket@13e65157 impl:android.net.LocalSocketImpl@26235444 fd:FileDescriptor[106]
09-06 19:09:41.242  6822  7085 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@13e65157 impl:android.net.LocalSocketImpl@26235444 fd:FileDescriptor[106]
09-06 19:09:41.242  6822  7085 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1345)
09-06 19:09:41.242  3204  5240 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-06 19:09:41.242  3204  3279 E bt-btif : cmd socket is not created
,09-06 19:09:41.242  3204  3204 I BtOppRfcommListener: stopping Accept Thread
09-06 19:09:41.242  3204  3283 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
09-06 19:09:41.242  3204  3204 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@395aeb5e, channel: 12, state: LISTENING
09-06 19:09:41.242  3204  3204 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@395aeb5e, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@27b391c8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@8210b3fmSocket: android.net.LocalSocket@39392c0c impl:android.net.LocalSocketImpl@260b9955 fd:FileDescriptor[87]
09-06 19:09:41.242  3204  3204 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@39392c0c impl:android.net.LocalSocketImpl@260b9955 fd:FileDescriptor[87]
,09-06 19:09:41.242  3204  3279 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-06 19:09:41.242  3204  5240 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-06 19:09:41.242  6822  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:09:41.242  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:41.242  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:41.242  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:41.242  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:41.242  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:41.242  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:41.242  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:41.242  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:09:41.242  6822  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:41.242  6822  6822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:09:41.252  3204  3204 V BluetoothOppManager: cleanUp...
,09-06 19:09:41.252  4809  4809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:09:41.252  1003  1523 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-06 19:09:41.252  1003  1523 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:09:41.252  1003  1523 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:41.252  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:41.252  1003  1523 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.252  1003  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
09-06 19:09:41.252  3204  3283 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:09:41.252  3204  3283 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:09:41.252  3204  3283 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:09:41.252  3204  3283 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:09:41.252  3204  3283 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:09:41.252  3204  3283 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-06 19:09:41.252  3204  3283 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
09-06 19:09:41.252  3204  3283 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
09-06 19:09:41.252  3204  3283 W bt-btif : invalid rfc slot id: 4
,09-06 19:09:41.252  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:41.262  1683  1683 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:09:41.262  4809  4809 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:09:41.262  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:41.272  4809  4809 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:09:41.272  1381  1381 I wpa_supplicant: nl80211: Received scan results (11 BSSes)
,09-06 19:09:41.272  1003  1126 D WifiP2pService: InactiveState{ what=147461 }
,09-06 19:09:41.272  1003  1126 D WifiP2pService: P2pEnabledState{ what=147461 }
,09-06 19:09:41.272  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:41.272  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-06 19:09:41.272  1003  1126 D WifiP2pService: DefaultState{ what=147461 }
,09-06 19:09:41.272  1003  1126 D WifiP2pService: InactiveState{ what=143375 }
,09-06 19:09:41.272  1003  1479 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
09-06 19:09:41.272  1003  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-06 19:09:41.282  1003  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:41.282  1003  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:41.282  1003  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:41.282  1003  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:41.292  1003  1479 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7092 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-06 19:09:41.292   278   905 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:09:41.292  7092  7092 E Zygote  : MountEmulatedStorage()
09-06 19:09:41.302  7092  7092 E Zygote  : v2
09-06 19:09:41.302  7092  7092 I libpersona: KNOX_SDCARD checking this for 10055
09-06 19:09:41.302  7092  7092 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:41.302  1683  2532 V NativeCrypto: Read error: ssl=0xb82a3450: I/O error during system call, Connection timed out,
09-06 19:09:41.302  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:41.302  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-06 19:09:41.302  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.302  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.302  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.302  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:41.302  1683  2532 V NativeCrypto: SSL shutdown failed: ssl=0xb82a3450: I/O error during system call, Broken pipe
,09-06 19:09:41.302  1003  1129 E ConnectivityService: updateNetworkInfo()
09-06 19:09:41.302  1003  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:09:41.312  1003  1129 E ConnectivityService: updateNetworkInfo()
09-06 19:09:41.312  1003  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,09-06 19:09:41.312  7092  7092 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:41.312  1003  1003 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-06 19:09:41.312  1003  1137 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
09-06 19:09:41.312  1003  1741 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:09:41.312  1003  1741 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:09:41.312  1003  1741 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-06 19:09:41.312  1003  1741 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:09:41.312  1003  1741 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
09-06 19:09:41.312  7092  7092 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:41.312  7092  7092 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:09:41.312  1003  1741 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 19:09:41.312  1003  1741 I qtaguid : Tagging socket 352 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1003, getuid(): 1000
,09-06 19:09:41.322  1003  1126 D WifiP2pService: InactiveState{ what=131204 }
,09-06 19:09:41.332  1003  1003 D WifiScanningService: SCAN_AVAILABLE : 1
,09-06 19:09:41.332  1003  1741 I qtaguid : Untagging socket 352
09-06 19:09:41.332  1003  1152 D WifiScanningService: DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:09:41.332  1003  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
09-06 19:09:41.332  1003  1741 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:09:41.332  1003  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-06 19:09:41.332  1003  1003 D RttService: SCAN_AVAILABLE : 1
,09-06 19:09:41.332  1003  1153 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:09:41.342  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-06 19:09:41.342  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:41.342  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:09:41.342  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:41.342  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.342  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:41.342  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:41.342  1003  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-06 19:09:41.352  1003  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:09:41.352  1003  1048 D WifiDisplayAdapter: onP2pDisconnected
,09-06 19:09:41.352  1003  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-06 19:09:41.352  1003  1127 E WifiNative-wlan0: do suspend true
09-06 19:09:41.352  1003  1126 D WifiP2pService: P2pDisablingState
09-06 19:09:41.352  1003  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
09-06 19:09:41.352  1003  1126 D WifiP2pService: p2p socket connection lost
09-06 19:09:41.352  1003  1126 D WifiP2pService: P2pDisabledState
09-06 19:09:41.352  1003  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:09:41.352  1003  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
09-06 19:09:41.352  1003  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-06 19:09:41.352  1003  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:09:41.352  1003  1048 D WifiDisplayController: disconnect
09-06 19:09:41.352  1003  1048 D WifiDisplayController: updateConnection
09-06 19:09:41.352  1003  1003 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-06 19:09:41.352  1003  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:09:41.352  1003  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 19:09:41.352  1003  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-06 19:09:41.352  1003  1048 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:09:41.352  1003  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:09:41.352  1003  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-06 19:09:41.362  7092  7092 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:41.362  1180  1180 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-06 19:09:41.362  1003  1030 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 19:09:41.362  7092  7092 D ActivityThread: Added TimaKeyStore provider
09-06 19:09:41.362  1180  1180 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-06 19:09:41.382   278   901 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
09-06 19:09:41.382   278   901 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,09-06 19:09:41.382  1003  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-06 19:09:41.382  7092  7092 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
09-06 19:09:41.382  1003  1126 D WifiP2pService: DefaultState{ what=143375 }
09-06 19:09:41.382  1003  1741 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-06 19:09:41.382  1003  1741 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-06 19:09:41.382  1003  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-06 19:09:41.382  1003  1129 V NetworkStats: updateIfacesLocked()
09-06 19:09:41.382  1003  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.382  1003  1129 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:09:41.382   278   905 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:09:41.382  1003  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:09:41.392  1003  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:09:41.392  1003  1003 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-06 19:09:41.392  1381  1381 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-06 19:09:41.392  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-06 19:09:41.392  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:41.392  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:09:41.392  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.392  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.392  1003  1129 V NetworkStats: performPollLocked() took 9ms
09-06 19:09:41.392  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.392  1003  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.392  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:41.402  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-06 19:09:41.402  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:41.412  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:09:41.412  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.412  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.412  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.412  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:41.412  1003  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:09:41.412  1003  1127 D SecContentProvider2: mCursor = null
,09-06 19:09:41.412  4809  4809 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:09:41.412  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-06 19:09:41.412  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.412  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.412  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:41.412  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:09:41.412  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:41.412  1003  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,09-06 19:09:41.422  1003  1129 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-06 19:09:41.422  1003  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-06 19:09:41.422  1003  1129 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,09-06 19:09:41.422  1003  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 19:09:41.422  1003  1741 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:09:41.422  1003  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-06 19:09:41.422  1003  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-06 19:09:41.422  1180  1681 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,09-06 19:09:41.422  1483  1483 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-06 19:09:41.422  1483  1483 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-06 19:09:41.422  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.422  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:41.422  1003  1003 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-06 19:09:41.422  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:41.422  1003  1132 D Tethering: MasterInitialState.processMessage what=3
09-06 19:09:41.422  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:09:41.422  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-06 19:09:41.422  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:09:41.422  7092  7092 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
09-06 19:09:41.422  1003  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-06 19:09:41.422  6822  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:41.422  1180  1715 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 19:09:41.422  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:41.422  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:41.422  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:41.422  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:41.422  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:41.422  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:41.422  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:41.422  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:09:41.422  7092  7092 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-06 19:09:41.422  7092  7092 D UserAnalysis: Create SecureDbHelper
,09-06 19:09:41.422  6822  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:41.422  6822  6822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:09:41.432  1003  1129 D ConnectivityService: nai.networkMonitor.doQuit()
09-06 19:09:41.432  1003  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-06 19:09:41.432  1003  1129 E ConnectivityService: updateNetworkInfo()
09-06 19:09:41.432  1003  1129 E ConnectivityService: updateNetworkInfo()
09-06 19:09:41.432  1003  1129 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-06 19:09:41.432  1180  1180 D HotspotTile: onReceive : 0, 0
,09-06 19:09:41.432  1003  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-06 19:09:41.432  1003  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.432  1003  1124 V NetworkStats: updateIfacesLocked()
09-06 19:09:41.432  1003  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:09:41.432  1003  1124 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:09:41.432  1003  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:09:41.432  1180  1180 D StatusBar.NetworkController: EthernetConnected: false
09-06 19:09:41.432  1180  1180 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-06 19:09:41.432  1180  1180 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-06 19:09:41.432  1180  1180 D StatusBar.NetworkController: updateDataNetType(),
,09-06 19:09:41.432  6822  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:41.432  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:41.432  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:41.432  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:41.432  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:41.432  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:41.432  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:41.432  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:41.432  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:09:41.442  6822  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:41.442  6822  6822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:09:41.442  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:41.442  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.442  1003  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-06 19:09:41.442  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.442  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.442  1003  1124 V NetworkStats: performPollLocked() took 9ms
09-06 19:09:41.442  1003  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:41.442  3204  3279 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-06 19:09:41.442  3204  3279 D BtConfig.SecureMode: isSecureModeOn:false
09-06 19:09:41.442  3204  3279 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-06 19:09:41.442  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
09-06 19:09:41.442  3204  3279 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
09-06 19:09:41.442  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-06 19:09:41.442  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-06 19:09:41.442  7092  7092 D IntelligenceServiceApplication: onCreate()
09-06 19:09:41.442  3204  3279 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-06 19:09:41.442  1003  1416 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:41.442  1003  1416 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-06 19:09:41.452  1003  1416 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.452  1003  1416 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.452  1003  1416 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:41.452  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-06 19:09:41.452  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-06 19:09:41.452  3204  3204 D HeadsetService: Received stop request...Stopping profile...
09-06 19:09:41.452  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.452  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
09-06 19:09:41.452  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-06 19:09:41.452  1003  1030 I ActivityManager: Killing 6686:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,09-06 19:09:41.452  1180  1180 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-06 19:09:41.452  3204  3279 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-06 19:09:41.452  1180  1180 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-06 19:09:41.452  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 23 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-06 19:09:41.452  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-06 19:09:41.452  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,09-06 19:09:41.462  7092  7092 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-06 19:09:41.462  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
09-06 19:09:41.462  1003  1518 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:41.462  1003  1518 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-06 19:09:41.462  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-06 19:09:41.462  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:41.462  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:09:41.462  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.462  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.462  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.462  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:41.462  1003  1518 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.462  1003  1518 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.462  1003  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:41.462  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-06 19:09:41.462  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-06 19:09:41.462  3204  3279 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-06 19:09:41.462  1003  1003 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-06 19:09:41.462  4809  4809 D HeadsetProfile: Bluetooth service disconnected
,09-06 19:09:41.472  1003  1733 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-06 19:09:41.472  1003  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:41.472  1003  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-06 19:09:41.472  7092  7092 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-06 19:09:41.472  1003  1479 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.472  1003  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.472  1003  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:09:41.472  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-06 19:09:41.472  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-06 19:09:41.472  3204  3279 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-06 19:09:41.472  1003  1223 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-06 19:09:41.472  1003  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:41.472  1003  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:41.472  1003  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:41.472  1003  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:41.482  7092  7092 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-06 19:09:41.492  7114  7114 E Zygote  : MountEmulatedStorage(),
09-06 19:09:41.492  7114  7114 I libpersona: KNOX_SDCARD checking this for 10105
09-06 19:09:41.492  7114  7114 E Zygote  : v2
,09-06 19:09:41.492  7114  7114 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:41.492  7114  7114 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:41.492  7114  7114 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 19:09:41.492  7114  7114 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:09:41.502  1003  1223 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7114 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-06 19:09:41.502  1003  1518 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:41.502  1003  1518 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-06 19:09:41.502  1003  1518 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:41.502  1003  1518 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.502  1003  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:09:41.502  1381  1381 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:09:41.502  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-06 19:09:41.502  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-06 19:09:41.502  3204  3279 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-06 19:09:41.512  1003  1512 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:41.512  1003  1512 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:09:41.512  1003  1512 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.512  1003  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.512  1003  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:09:41.512  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-06 19:09:41.512  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-06 19:09:41.512  3204  3279 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-06 19:09:41.512  1003  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:41.512  1003  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:09:41.512  1003  1481 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.512  1003  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.512  1003  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:41.522  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-06 19:09:41.522  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-06 19:09:41.522  3204  3279 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-06 19:09:41.522  7114  7114 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:41.522  1003  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:41.522  1003  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:09:41.522  1003  1479 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.522  1003  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.522  1003  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:41.522  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:41.522  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:09:41.522  7114  7114 D ActivityThread: Added TimaKeyStore provider
09-06 19:09:41.522  3204  3279 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:41.522  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:41.522  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-06 19:09:41.522  3204  3279 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:41.522  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 19:09:41.522  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-06 19:09:41.522  3204  3279 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-06 19:09:41.522  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-06 19:09:41.522  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-06 19:09:41.532  3204  3279 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService,
09-06 19:09:41.532  3204  3279 D BluetoothAdapterState: Stopping profile services that were post enabled
09-06 19:09:41.532  3204  3204 E BluetoothAdapterService(138181793): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-06 19:09:41.532  3204  3204 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:09:41.532  3204  3204 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-06 19:09:41.532  3204  3204 D A2dpService: Received stop request...Stopping profile...,
09-06 19:09:41.532  3204  3348 D A2dpStateMachine: Exit Disconnected: -1
,09-06 19:09:41.542  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
,09-06 19:09:41.542  1003  1003 D BluetoothA2dp: Proxy object disconnected
,09-06 19:09:41.542  1003  1003 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-06 19:09:41.542  4809  4809 D BluetoothA2dp: Proxy object disconnected
,09-06 19:09:41.542  4809  4809 D A2dpProfile: Bluetooth service disconnected
09-06 19:09:41.542  3204  3204 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 19:09:41.542  3204  3204 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 19:09:41.542  3204  3204 D HidService: Received stop request...Stopping profile...
09-06 19:09:41.542  3204  3204 D HidService: Stopping Bluetooth HidService
09-06 19:09:41.542  3204  3204 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 19:09:41.542  3204  3204 W bt-btif : cleanup: HH disabling or disabled already, status = 0
,09-06 19:09:41.542  3204  3204 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 19:09:41.542  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
,09-06 19:09:41.542  3204  3204 D HealthService: Received stop request...Stopping profile...
09-06 19:09:41.542  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
09-06 19:09:41.552  4809  4809 D BluetoothInputDevice: Proxy object disconnected
09-06 19:09:41.552  4809  4809 D HidProfile: Bluetooth service disconnected
,09-06 19:09:41.552  3204  3204 D PanService: Received stop request...Stopping profile...
,09-06 19:09:41.552  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
,09-06 19:09:41.552  1003  1003 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-06 19:09:41.552  3204  3204 D BluetoothMapService: Received stop request...Stopping profile...
,09-06 19:09:41.552  4809  4809 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 19:09:41.552  4809  4809 D PanProfile: Bluetooth service disconnected
,09-06 19:09:41.562  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
,09-06 19:09:41.562  3204  3204 D SapService: Received stop request...Stopping profile...
09-06 19:09:41.562  3204  3204 D SapService: Stopping Bluetooth SapService
09-06 19:09:41.562  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
09-06 19:09:41.562  4809  4809 D BluetoothMap: Proxy object disconnected
09-06 19:09:41.562  4809  4809 D MapProfile: Bluetooth service disconnected
,09-06 19:09:41.562  3204  3204 E BluetoothAdapterService(138181793): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-06 19:09:41.562  3204  3204 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:09:41.562  3204  3204 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-06 19:09:41.562  3204  3204 D BluetoothA2dp: Proxy object disconnected
09-06 19:09:41.562  3204  3204 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,09-06 19:09:41.562  4809  4809 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-06 19:09:41.562  4809  4809 D SapProfile: Bluetooth service disconnected
09-06 19:09:41.562  3204  3349 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-06 19:09:41.572  3204  3204 I GKI_LINUX: GKI_exit_task 2 done
09-06 19:09:41.572  3204  3204 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-06 19:09:41.572  3204  3204 E BluetoothAdapterService(138181793): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-06 19:09:41.572  3204  3204 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-06 19:09:41.572  3204  3204 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:41.572  3204  3204 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-06 19:09:41.572  3204  3204 E BluetoothAdapterService(138181793): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-06 19:09:41.572  3204  3204 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-06 19:09:41.572  3204  3204 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:41.572  3204  3204 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:41.572  3204  3204 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 19:09:41.572  3204  3204 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:09:41.572  3204  3204 E BluetoothAdapterService(138181793): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-06 19:09:41.572  3204  3204 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-06 19:09:41.572  3204  3204 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:41.572  3204  3204 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-06 19:09:41.572  3204  3204 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 19:09:41.572  3204  3204 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-06 19:09:41.572  3204  3204 E BluetoothAdapterService(138181793): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-06 19:09:41.572  3204  3204 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-06 19:09:41.572  3204  3204 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 19:09:41.572  3204  3204 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-06 19:09:41.572  3204  3204 E BluetoothAdapterService(138181793): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-06 19:09:41.572  3204  3204 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-06 19:09:41.572  3204  3204 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-06 19:09:41.572  3204  3204 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-06 19:09:41.572  3204  3279 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-06 19:09:41.572  3204  3279 D BluetoothAdapterProperties: Setting state to 10,
09-06 19:09:41.572  3204  3279 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-06 19:09:41.572  3204  3279 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:09:41.572  3204  3279 D BluetoothAdapterService: updateAdapterState state is 10
09-06 19:09:41.572  3204  3279 D BluetoothAdapterService: Autoconnection is available 
09-06 19:09:41.572  3204  3279 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-06 19:09:41.572  3204  3279 I BluetoothAdapterState: Entering OffState
09-06 19:09:41.572  1467  1493 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:41.572  1467  1493 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:09:41.572  4809  4817 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:09:41.582  6822  6953 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:41.582  6822  6953 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:41.582  6822  6953 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,09-06 19:09:41.582  6822  6953 D BluetoothLeAdvertiser: Exit stop advertising
09-06 19:09:41.582  6822  6953 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-06 19:09:41.582  6822  6953 D BluetoothLeScanner: Exiting stopAllScan
,09-06 19:09:41.582  4809  4817 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-06 19:09:41.582  1381  1381 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-06 19:09:41.582  1003  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:09:41.582  1003  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:09:41.582  1003  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:09:41.592  4809  4819 D Bluetoothsap: onBluetoothStateChange: up=false
,09-06 19:09:41.592  4809  4819 D Bluetoothsap: Unbinding service...
,09-06 19:09:41.592  4809  4817 D BluetoothMap: onBluetoothStateChange: up=false
09-06 19:09:41.592  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.592  1483  1500 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:41.592  1483  1500 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:41.592  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:09:41.592  3204  3339 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:41.592  3204  3339 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:09:41.592  1752  1951 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:41.592  1752  1951 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:09:41.592  4809  4819 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:41.592  4809  4819 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:09:41.592  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-06 19:09:41.592  4809  4817 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 19:09:41.592  1455  1466 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:41.592  1455  1466 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:09:41.592  1003  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:41.592  1003  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:09:41.592  1003  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:09:41.602  1683  4411 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:41.602  1683  4411 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:09:41.602  1180  3524 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:41.602  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:09:41.602  1180  3524 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:09:41.602  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.602  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:09:41.602  3204  3217 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:09:41.602  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.602  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:09:41.602  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.602  1003  1003 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
09-06 19:09:41.602  1003  1003 I InputMethodManagerService: [BT Setting State] State =10
09-06 19:09:41.602  1003  1003 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 19:09:41.612  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:09:41.612  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.612  1381  1381 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
,09-06 19:09:41.612  1381  1381 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-06 19:09:41.612  1381  1381 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-06 19:09:41.612  1381  1381 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-06 19:09:41.612  1381  1381 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-06 19:09:41.612  1003  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:09:41.612  1003  1045 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:09:41.612  1003  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:09:41.612  1003  1132 D Tethering: InitialState.processMessage what=4
,09-06 19:09:41.612  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:09:41.612  1003  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 19:09:41.612  1003  1045 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:09:41.612  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.612  1003  1132 E Tethering: No numeric data
,09-06 19:09:41.612  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:09:41.612  1003  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:09:41.622  6822  6822 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-06 19:09:41.622  1003  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:09:41.622  1003  1045 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:09:41.622  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-06 19:09:41.622  1003  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:09:41.622  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 19:09:41.622  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:41.622  1180  1180 D BluetoothTile:  getBluetoothState : 10
09-06 19:09:41.622  1003  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:09:41.622  1003  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:09:41.622  1003  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:09:41.622  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:09:41.622  1995  1995 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:09:41.622  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.622  4809  4809 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:41.622  1003  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:09:41.622  1003  1132 D Tethering: clearTetheredNotification()
09-06 19:09:41.622  1003  1496 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:09:41.622  1003  1030 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-06 19:09:41.632  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 19:09:41.632  1003  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.632  1003  1124 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:09:41.632  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:09:41.632  6822  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:41.632  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:41.632  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:41.632  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:41.632  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:41.632  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:41.632  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:41.632  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:41.632  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:09:41.632  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-06 19:09:41.632  1003  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:09:41.632  1003  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:09:41.632  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:09:41.632  1180  1180 D HotspotTile: updateTetherState():false, false
,09-06 19:09:41.632  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:09:41.632  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.632  1003  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.632  1003  1124 V NetworkStats: performPollLocked() took 4ms
,09-06 19:09:41.632  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:41.632  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.632  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:41.642  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:09:41.642  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.642  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:09:41.642  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.642  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
09-06 19:09:41.642  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-06 19:09:41.642  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:09:41.642  1483  1483 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.642  1483  1483 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:09:41.682   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-06 19:09:41.682   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:09:41.682  7114  7147 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-06 19:09:41.682   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-06 19:09:41.682   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:09:41.682  7114  7147 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-06 19:09:41.822  1381  1381 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:09:41.822  7114  7114 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:41.822  7114  7114 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:41.822  7114  7114 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:41.822  7114  7114 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.q.e.b(PG:170)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:41.822  7114  7114 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.q.k.d(PG:583)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.q.e.b(PG:170)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:41.822  7114  7114 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:41.822  7114  7114 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:41.822  7114  7114 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:41.822  7114  7114 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:41.832  1003  1137 I ActivityManager: Killing 6700:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
09-06 19:09:41.832  1003  1416 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:09:41.832  1003  1416 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 19:09:41.832  1003  1416 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.832  1003  1416 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.832  1003  1416 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:09:41.842  1611  1611 I Hs20UtilService: Starting #8
09-06 19:09:41.842  1611  1654 I Hs20UtilService: Message received 5007
09-06 19:09:41.842  4809  4809 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-06 19:09:41.842  4809  4809 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 19:09:41.842  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-06 19:09:41.842  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:09:41.842  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:09:41.842  4809  4809 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 19:09:41.842  4809  4849 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-06 19:09:41.852  4809  4809 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-06 19:09:41.862  4809  4809 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 19:09:41.862  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:09:41.872  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:09:41.872  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:09:41.872  4809  4809 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 19:09:41.872  4809  4849 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-06 19:09:41.872  1003  1518 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
09-06 19:09:41.872  1003  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:41.872  1003  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:41.872  1003  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:41.872  1003  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:41.882  7158  7158 E Zygote  : MountEmulatedStorage()
09-06 19:09:41.882  7158  7158 I libpersona: KNOX_SDCARD checking this for 10064
09-06 19:09:41.882  7158  7158 E Zygote  : v2
09-06 19:09:41.882  7158  7158 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:41.882  7158  7158 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:09:41.882  7158  7158 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:09:41.882  7158  7158 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:09:41.892  7114  7157 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
09-06 19:09:41.892  1003  1518 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7158 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:09:41.902  1381  1381 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
09-06 19:09:41.902  1003  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:09:41.902  1003  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:09:41.902  1003  1045 D Tethering: interfaceStatusChanged wlan0, false,
,09-06 19:09:41.922  7158  7158 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:41.922  7158  7158 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:41.922  1003  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:09:41.932  1003  1003 I ApplicationPolicy: updateDataUsageMap
,09-06 19:09:41.942  7158  7158 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-06 19:09:41.952  1003  1481 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:41.952  1003  1481 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.952  1003  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:41.952  1003  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
09-06 19:09:41.952  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:41.952  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:41.962  7158  7158 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:09:41.972  7158  7158 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-06 19:09:42.002  7158  7158 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 19:09:42.002  1003  1481 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-06 19:09:42.002  1003  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.002  1003  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.002  1003  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.002  1003  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.022  7175  7175 E Zygote  : MountEmulatedStorage()
,09-06 19:09:42.022  7175  7175 E Zygote  : v2
09-06 19:09:42.022  7175  7175 I libpersona: KNOX_SDCARD checking this for 10065
09-06 19:09:42.022  7175  7175 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:42.022  7175  7175 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:42.022  7175  7175 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 19:09:42.022  7175  7175 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:42.032  1003  1481 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7175 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-06 19:09:42.032  1003  1481 I ActivityManager: Killing 6737:com.wsomacp/u0a23 (adj 15): empty #21
,09-06 19:09:42.032  1003  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-06 19:09:42.032  1003  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-06 19:09:42.042  7175  7175 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:09:42.052  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:09:42.052  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-06 19:09:42.052  1180  1715 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 19:09:42.052  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:42.052  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:09:42.052  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:42.052  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:42.052  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:42.052  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:42.052  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:09:42.052  7175  7175 D ActivityThread: Added TimaKeyStore provider
09-06 19:09:42.052  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-06 19:09:42.052  1180  1180 D HotspotTile: onReceive : 1, 0
,09-06 19:09:42.052  4809  4809 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:09:42.062  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:42.062  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:42.062  1003  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:09:42.062  1752  2185 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:09:42.072   312   312 I art     : Explicit concurrent mark sweep GC freed 8682(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 596us total 39.208ms
,09-06 19:09:42.082  7175  7175 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:09:42.082  1003  1481 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.082  1003  1481 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
09-06 19:09:42.082  1003  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:42.082  1003  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,09-06 19:09:42.082  1003  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.082  1003  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.082  1003  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.082  1003  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.092   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 767us total 16.571ms,
,09-06 19:09:42.102   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 566us total 16.040ms
,09-06 19:09:42.122  7191  7191 E Zygote  : MountEmulatedStorage(),
09-06 19:09:42.122  7191  7191 E Zygote  : v2
,09-06 19:09:42.122  7191  7191 I libpersona: KNOX_SDCARD checking this for 10102
09-06 19:09:42.122  7191  7191 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:42.132  7191  7191 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:09:42.132  1003  1481 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7191 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-06 19:09:42.132  1003  1481 I ActivityManager: Killing 6758:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,09-06 19:09:42.132  7191  7191 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:42.132  7191  7191 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:09:42.152  7191  7191 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:42.152  7191  7191 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:42.172  7191  7191 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-06 19:09:42.372  7191  7211 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-06 19:09:42.372  7191  7211 I Babel_SMS: MmsConfig.loadMmsSettings
,09-06 19:09:42.372  7191  7211 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
09-06 19:09:42.372  7191  7211 I Babel_SMS: MmsConfig.loadFromDatabase
,09-06 19:09:42.392  7191  7211 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-06 19:09:42.392  7191  7211 I Babel_SMS: MmsConfig.loadFromResources
,09-06 19:09:42.392  7191  7211 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-06 19:09:42.392  7191  7211 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-06 19:09:42.402  1003  1733 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,09-06 19:09:42.412  1003  1733 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-06 19:09:42.412  1003  1733 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:42.412  1003  1733 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:42.412  1003  1733 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-06 19:09:42.432  7191  7191 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:09:42.432  7191  7191 I Babel_Crash: startup - clean
,09-06 19:09:42.452  1003  1223 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:09:42.452  1003  1223 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:09:42.452  1003  1223 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.452  1003  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.462  1003  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:09:42.462  1611  1611 I Hs20UtilService: Starting #9
,09-06 19:09:42.462  1611  1654 I Hs20UtilService: Message received 5007
,09-06 19:09:42.462  4809  4809 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 19:09:42.462  4809  4809 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:09:42.462  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:09:42.472  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 19:09:42.472  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:09:42.472  4809  4809 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 19:09:42.472  7191  7191 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-06 19:09:42.472  4809  4849 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:09:42.482  7191  7191 W AudioCapabilities: Unsupported mime audio/evrc
,09-06 19:09:42.482  7191  7191 W AudioCapabilities: Unsupported mime audio/qcelp
,09-06 19:09:42.482  7191  7191 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-06 19:09:42.482  7191  7191 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-06 19:09:42.492  1003  1137 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:09:42.492  1003  1137 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:09:42.492  1003  1137 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.492  1003  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.492  7191  7191 W AudioCapabilities: Unsupported mime audio/x-ms-wma
09-06 19:09:42.492  1003  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:09:42.492  1611  1611 I Hs20UtilService: Starting #10
,09-06 19:09:42.492  7191  7191 W AudioCapabilities: Unsupported mime audio/x-ima
,09-06 19:09:42.492  1611  1654 I Hs20UtilService: Message received 5011
,09-06 19:09:42.492  7191  7191 W AudioCapabilities: Unsupported mime audio/qcelp
,09-06 19:09:42.492  7191  7191 W AudioCapabilities: Unsupported mime audio/evrc
,09-06 19:09:42.502  6971  6971 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 19:09:42.502  6971  6971 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:09:42.502  6971  6971 D SecurityLogAgent: StateMachine : Current State = 1
,09-06 19:09:42.502  6971  6971 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:09:42.512  1003  1523 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:42.512  1003  1523 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.512  1003  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.512  1003  1003 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.512  1003  1003 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.512  1003  1003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.512  1003  1003 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.522  1003  1003 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.522  1003  1003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.522  1003  1003 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.522  1003  1003 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.522  1003  1003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.522  1003  1003 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.522  1003  1003 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.522  1003  1003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.522  1003  1003 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.522  1003  1003 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.522  1003  1003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.532  1003  1003 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.532  1003  1003 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.532  1003  1003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.532  1003  1003 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.532  1003  1003 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.532  1003  1003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.532  1003  1003 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.532  1003  1003 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.532  1003  1003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.542  1003  1003 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.542  1003  1003 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.542  1003  1003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.542  7191  7191 W VideoCapabilities: Unsupported mime video/wvc1
,09-06 19:09:42.542  1003  1003 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.542  1003  1003 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.542  1003  1003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.542  7191  7191 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-06 19:09:42.542  1003  1003 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:42.542  1003  1003 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:42.542  1003  1003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.552  7191  7191 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-06 19:09:42.552  1003  1003 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.552  1003  1003 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.552  1003  1003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.552  7191  7191 W VideoCapabilities: Unsupported mime video/wvc1
,09-06 19:09:42.552  1003  1003 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.552  1003  1003 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.552  1003  1003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.552  7191  7191 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-06 19:09:42.552  7191  7191 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-06 19:09:42.552  1003  1003 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.552  1003  1003 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.552  1003  1003 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:42.562  7191  7191 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-06 19:09:42.562  1003  1045 D Tethering: interfaceRemoved wlan0
,09-06 19:09:42.562  7191  7191 W VideoCapabilities: Unsupported mime video/mp43
09-06 19:09:42.562  1003  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-06 19:09:42.562  4809  4809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:09:42.562  7191  7191 W VideoCapabilities: Unsupported mime video/sorenson
,09-06 19:09:42.562  1003  1416 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-06 19:09:42.562  1003  1416 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:09:42.572  1003  1416 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.572  1003  1416 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.572  1003  1416 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:09:42.572  1683  1683 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-06 19:09:42.572  7191  7191 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-06 19:09:42.572  4809  4809 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:09:42.582  4809  4809 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:09:42.582  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:42.582  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-06 19:09:42.592  1003  1137 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
09-06 19:09:42.592  7191  7191 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-06 19:09:42.592  1003  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.592  1003  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.592  1003  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.592  1003  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.602  7216  7216 E Zygote  : MountEmulatedStorage()
09-06 19:09:42.602  7216  7216 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:09:42.602  7216  7216 E Zygote  : v2
09-06 19:09:42.602  7216  7216 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:42.602  7216  7216 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:42.612  1003  1137 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7216 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,09-06 19:09:42.612  7216  7216 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:42.612  7216  7216 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:42.632  7216  7216 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:42.642  7216  7216 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:42.642  7191  7191 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:09:42.642  7191  7191 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:09:42.642  7191  7191 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:09:42.652  7191  7191 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:09:42.652  1003  1137 I ActivityManager: Killing 6780:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,09-06 19:09:42.652  7191  7191 I vclib   : onServiceConnected
,09-06 19:09:42.662  7216  7216 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-06 19:09:42.662  7216  7216 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-06 19:09:42.662  7216  7216 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-06 19:09:42.682  7216  7216 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-06 19:09:42.682  7216  7216 I PCWCLIENTTRACE_PushUtil: sales region : global
09-06 19:09:42.682  7216  7216 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-06 19:09:42.682  7216  7216 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:09:42.682  1003  1030 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,09-06 19:09:42.682  1003  1030 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
09-06 19:09:42.682  1003  1030 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
,09-06 19:09:42.682  1003  1030 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,09-06 19:09:42.682  1003  1030 I ActivityManager: Killing 6806:com.osp.app.signin/u0a36 (adj 15): empty #21
,09-06 19:09:42.682  7216  7231 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-06 19:09:42.692  1003  1003 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-06 19:09:42.692  1003  1003 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.692  1003  1003 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.692  1003  1003 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.692  1003  1003 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.702  7233  7233 E Zygote  : MountEmulatedStorage(),
09-06 19:09:42.702  7233  7233 E Zygote  : v2
09-06 19:09:42.702  7233  7233 I libpersona: KNOX_SDCARD checking this for 10001,
,09-06 19:09:42.712  7233  7233 I libpersona: KNOX_SDCARD not a persona,
,09-06 19:09:42.712  1003  1003 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7233 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:09:42.712  7233  7233 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-06 19:09:42.712  7233  7233 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 19:09:42.712  7233  7233 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:42.722  1003  1045 D Tethering: interfaceRemoved p2p0
09-06 19:09:42.722  1003  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-06 19:09:42.732  7233  7233 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-06 19:09:42.732  7233  7233 D ActivityThread: Added TimaKeyStore provider,
,09-06 19:09:42.802  1003  1733 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-06 19:09:42.802  1003  1733 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.802  1003  1733 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.802  1003  1733 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.802  1003  1733 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.812  7251  7251 E Zygote  : MountEmulatedStorage(),
09-06 19:09:42.812  1003  1733 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7251 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-06 19:09:42.812  1003  1733 I ActivityManager: Killing 6494:com.android.mms/u0a41 (adj 15): empty #21
,09-06 19:09:42.812  7251  7251 E Zygote  : v2
09-06 19:09:42.812  7251  7251 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:09:42.812  7251  7251 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:42.812  7251  7251 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:42.822  7251  7251 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:42.822  7251  7251 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:42.832  7251  7251 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:42.842  7251  7251 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:42.872  7251  7251 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-06 19:09:42.932  1003  1523 D CountryDetector: No listener is left,
,09-06 19:09:43.002  7251  7251 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0,
,09-06 19:09:43.012  7251  7251 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !,
,09-06 19:09:43.012  7251  7251 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE,
,09-06 19:09:43.012  7251  7251 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:,
09-06 19:09:43.012  7251  7251 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
09-06 19:09:43.012  7251  7251 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-06 19:09:43.012  1003  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast,
,09-06 19:09:43.012  1003  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.012  1003  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.012  1003  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-06 19:09:43.012  1003  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.022  7268  7268 E Zygote  : MountEmulatedStorage(),
09-06 19:09:43.022  7268  7268 E Zygote  : v2
09-06 19:09:43.022  7268  7268 I libpersona: KNOX_SDCARD checking this for 10008
09-06 19:09:43.022  7268  7268 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:43.032  1003  1030 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7268 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:09:43.032  7268  7268 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:09:43.032  1003  1030 I ActivityManager: Killing 6842:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,09-06 19:09:43.032  7268  7268 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:43.032  7268  7268 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-06 19:09:43.062  7268  7268 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:43.062  7268  7268 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:43.142  1003  1512 I ActivityManager: Killing 6140:com.samsung.android.sm/1000 (adj 15): empty #21
,09-06 19:09:43.142  1003  1137 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,09-06 19:09:43.142  1003  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-06 19:09:43.142  1003  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:43.142  1003  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:43.142  1003  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-06 19:09:43.162  1915  1915 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-06 19:09:43.162  1915  2801 I iu.UploadsManager: num queued entries: 0
,09-06 19:09:43.172  1003  1523 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:09:43.172  1003  1523 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,09-06 19:09:43.172  1915  2801 I iu.UploadsManager: num updated entries: 0
,09-06 19:09:43.172  1003  1523 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:43.172  1915  2801 I iu.SyncManager: NEXT; no task
09-06 19:09:43.172  1003  1523 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:43.172  1003  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:43.182  1915  1915 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-06 19:09:43.192  1915  1915 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,09-06 19:09:43.202  2805  2805 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Sep 06 19:09:43 GMT+02:00 2016
,09-06 19:09:43.202  1003  1523 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-06 19:09:43.202  1003  1523 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-06 19:09:43.202  1003  1523 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:43.202  1003  1523 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:43.202  1003  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-06 19:09:43.212  2805  2805 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-06 19:09:43.222  1003  1518 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-06 19:09:43.222  1003  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.222  1003  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.222  1003  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.222  1003  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.242  7285  7285 E Zygote  : MountEmulatedStorage(),
09-06 19:09:43.242  7285  7285 E Zygote  : v2
09-06 19:09:43.242  7285  7285 I libpersona: KNOX_SDCARD checking this for 10031
09-06 19:09:43.242  7285  7285 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:43.242  7285  7285 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-06 19:09:43.242  2805  2805 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
09-06 19:09:43.242  1003  1518 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7285 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
09-06 19:09:43.242  2805  2805 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-06 19:09:43.252  2805  2805 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-06 19:09:43.252  7285  7285 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:43.252  2805  7284 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
09-06 19:09:43.252  7285  7285 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:43.262  2805  7284 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-06 19:09:43.262  2805  7284 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-06 19:09:43.262  2805  7284 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-06 19:09:43.272  2805  2805 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-06 19:09:43.272  1003  3354 D SSRM:n  : SIOP:: AP = 380
,09-06 19:09:43.272  7285  7285 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:43.272  7285  7285 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:43.302  7285  7285 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-06 19:09:43.312  1003  1223 I ActivityManager: Killing 6861:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,09-06 19:09:43.322  1003  1479 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-06 19:09:43.322  1003  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.332  1003  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.332  1003  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.332  1003  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.332  2743  7300 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-06 19:09:43.332  2743  7300 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-06 19:09:43.332  1003  1050 I PowerManagerService: [PWL] Off : 50s ago
,09-06 19:09:43.332  1003  1050 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-06 19:09:43.332  1003  1050 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
09-06 19:09:43.332  1003  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1003, ws=null) (elapsedTime=1909)
,09-06 19:09:43.342  2743  7300 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-06 19:09:43.342  2743  7300 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-06 19:09:43.342  2743  7300 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-06 19:09:43.342  7301  7301 E Zygote  : MountEmulatedStorage(),
,09-06 19:09:43.342  7301  7301 E Zygote  : v2
09-06 19:09:43.352  7301  7301 I libpersona: KNOX_SDCARD checking this for 10032
,09-06 19:09:43.352  7301  7301 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:43.352  7301  7301 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:09:43.352  1003  1479 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7301 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:09:43.352  7301  7301 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-06 19:09:43.352  7301  7301 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-06 19:09:43.382  7301  7301 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:43.382  7301  7301 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:43.462  7301  7316 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-06 19:09:43.462  7301  7316 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-06 19:09:43.462  7301  7301 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-06 19:09:43.472  1003  1733 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,09-06 19:09:43.472  1003  1733 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.472  1003  1733 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.472  1003  1733 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.472  1003  1733 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.472  7301  7316 D SPPClientService: PushLog.txt file is not deleted.
,09-06 19:09:43.472  7301  7316 D SPPClientService: PushLog.txt file is not deleted.
09-06 19:09:43.472  7301  7316 D SPPClientService: ============PushLog. stop!
,09-06 19:09:43.492  7318  7318 E Zygote  : MountEmulatedStorage(),
,09-06 19:09:43.492  1003  1733 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7318 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:09:43.492  1003  1733 I ActivityManager: Killing 6894:com.sec.esdk.elm/u0a90 (adj 15): empty #21,
09-06 19:09:43.502  7318  7318 E Zygote  : v2
09-06 19:09:43.502  7318  7318 I libpersona: KNOX_SDCARD checking this for 10036
09-06 19:09:43.502  7318  7318 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:43.502  1003  1518 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push,
,09-06 19:09:43.502  7318  7318 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:09:43.502  1003  1518 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
09-06 19:09:43.502  1003  1518 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:09:43.502  1003  1518 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023,
09-06 19:09:43.502  1003  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
09-06 19:09:43.502  7318  7318 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:09:43.502  7318  7318 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,09-06 19:09:43.522  7318  7318 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:43.532  7318  7318 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:43.532  7301  7324 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-06 19:09:43.572  7318  7318 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@2d262fee
,09-06 19:09:43.572  1003  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-06 19:09:43.582  7318  7318 I SA      : [SSP] onCreated
,09-06 19:09:43.592  7318  7318 I SA      : [TPM] There is no property file
,09-06 19:09:43.592  7318  7318 I SA      : [SCU] isHaveSA() - false
,09-06 19:09:43.602  7318  7318 I SA      : [TPM] getModelProperty : null
,09-06 19:09:43.602  7318  7318 I SA      : [TPM] getCSCProperty : null
,09-06 19:09:43.602  7318  7318 I SA      : [DM] FLOATING AMOLED FEATURE: true
,09-06 19:09:43.602  7318  7318 I SA      : [DM] PRODUCT AMOLED FEATURE: false
09-06 19:09:43.602  7318  7318 I SA      : [DM] TFT FEATURE: false
,09-06 19:09:43.602  7318  7318 I SA      : [DM] init START
,09-06 19:09:43.602  7318  7318 I SA      : [DM] This device is not a Vodafone
,09-06 19:09:43.612  7318  7318 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,09-06 19:09:43.612  7318  7318 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,09-06 19:09:43.612  7318  7318 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,09-06 19:09:43.612  7318  7318 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,09-06 19:09:43.612  7318  7318 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,09-06 19:09:43.612  7318  7318 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,09-06 19:09:43.612  7318  7318 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,09-06 19:09:43.622  7318  7318 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-06 19:09:43.622  7318  7318 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
09-06 19:09:43.622  7318  7318 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,09-06 19:09:43.622  7318  7318 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,09-06 19:09:43.622  7318  7318 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75),
,09-06 19:09:43.622  7318  7318 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-06 19:09:43.622  7318  7318 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
09-06 19:09:43.622  7318  7318 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,09-06 19:09:43.622  7318  7318 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
09-06 19:09:43.622  7318  7318 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,09-06 19:09:43.622  7318  7318 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,09-06 19:09:43.622  7318  7318 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,09-06 19:09:43.622  7318  7318 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-06 19:09:43.622  7318  7318 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
09-06 19:09:43.622  7318  7318 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-06 19:09:43.622  7318  7318 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75),
09-06 19:09:43.622  7318  7318 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,09-06 19:09:43.632  7318  7318 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
09-06 19:09:43.632  7318  7318 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
09-06 19:09:43.632  7318  7318 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,09-06 19:09:43.632  7318  7318 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,09-06 19:09:43.632  7318  7318 I SA      : [SCU] isHaveSA() - false
09-06 19:09:43.632  7318  7318 I SA      : support phone number id : false
09-06 19:09:43.632  7318  7318 I SA      : [DM] Supports Ref Jpn : true
,09-06 19:09:43.632  7318  7318 I SA      : [DM] init END
,09-06 19:09:43.632  7318  7318 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-06 19:09:43.632  7318  7318 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ],
09-06 19:09:43.632  7318  7318 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-06 19:09:43.642  7318  7318 I SA      : [SLFUCHKMGR] constructor called,
,09-06 19:09:43.642  7318  7318 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-06 19:09:43.642  7318  7318 I SA      : [OR] == isSIMCardReady false ==
,09-06 19:09:43.652  7318  7318 I SA      : [SCU] == networkStateCheck == false
09-06 19:09:43.652  7318  7318 I SA      : [OR] onReceive END
,09-06 19:09:43.652  1003  1029 I ActivityManager: Killing 6994:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,09-06 19:09:43.652  1231  1231 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:09:43.662  1813  1813 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-06 19:09:43.662  2673  2687 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3,
,09-06 19:09:43.672  1813  1813 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-06 19:09:43.672  1813  1813 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,09-06 19:09:43.672  1813  1813 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,09-06 19:09:43.672  1813  1813 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-06 19:09:43.672  1813  1813 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-06 19:09:43.672  1813  1813 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-06 19:09:43.672  1003  1733 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-06 19:09:43.682  1003  1733 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.682  1003  1733 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.682  1003  1733 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.682  1003  1733 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.692  1003  1733 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7340 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
09-06 19:09:43.692  7340  7340 E Zygote  : MountEmulatedStorage()
,09-06 19:09:43.692  7340  7340 E Zygote  : v2
09-06 19:09:43.692  7340  7340 I libpersona: KNOX_SDCARD checking this for 10077
09-06 19:09:43.692  7340  7340 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:43.692  7340  7340 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:43.702  7340  7340 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 19:09:43.702  7340  7340 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-06 19:09:43.712  7340  7340 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:43.712  7340  7340 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:43.882  1003  1733 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,09-06 19:09:43.882  1003  1733 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-06 19:09:43.882  1003  1733 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:43.882  1003  1733 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:43.882  1003  1733 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-06 19:09:43.882  1003  1518 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-06 19:09:43.882  1003  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.882  1003  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.882  1003  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.892  1003  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.902  7359  7359 E Zygote  : MountEmulatedStorage(),
09-06 19:09:43.902  7359  7359 I libpersona: KNOX_SDCARD checking this for 10110
09-06 19:09:43.902  7359  7359 E Zygote  : v2
09-06 19:09:43.902  7359  7359 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:43.902  7359  7359 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-06 19:09:43.902  1003  1518 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7359 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:09:43.902  7359  7359 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 19:09:43.902  7359  7359 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
09-06 19:09:43.902  1003  1481 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk,
09-06 19:09:43.902  1003  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
09-06 19:09:43.912  1003  1481 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:43.912  1003  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:43.912  1003  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-06 19:09:43.912   291   291 E SMD     : DCD OFF
09-06 19:09:43.912  7191  7358 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-06 19:09:43.912  1003  1223 I ActivityManager: Killing 6959:com.android.providers.calendar/u0a37 (adj 15): empty #21
,09-06 19:09:43.922  7359  7359 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:43.922  7359  7359 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:44.022  1003  1029 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-06 19:09:44.112   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-06 19:09:44.112   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:09:44.112  7359  7377 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-06 19:09:44.122   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-06 19:09:44.122   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:09:44.122  7359  7377 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-06 19:09:44.142   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
,09-06 19:09:44.142   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:09:44.142  7359  7378 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-06 19:09:44.152   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-06 19:09:44.152   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:09:44.152  7359  7378 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-06 19:09:44.162  7359  7359 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-06 19:09:44.162  7359  7359 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-06 19:09:44.162  7359  7359 I GAv4    :   adb logcat -s GAv4
,09-06 19:09:44.182  7359  7359 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-06 19:09:44.182  1003  1518 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-06 19:09:44.192  7359  7359 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-06 19:09:44.202  7359  7380 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-06 19:09:44.212  1003  1223 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-06 19:09:44.212  1003  1223 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 19:09:44.212  1003  1223 D SecContentProvider2: mCursor = null
,09-06 19:09:44.212  1003  1223 D WifiService: setWifiEnabled: true pid=6822, uid=10170
,09-06 19:09:44.212  1003  1223 W ActivityManager: Permission Denial: getCurrentUser() from pid=6822, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-06 19:09:44.212  1003  1223 W WifiService: Failed getting userId using ActivityManagerNative
09-06 19:09:44.212  1003  1223 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6822, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:09:44.212  1003  1223 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 19:09:44.212  1003  1223 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-06 19:09:44.212  1003  1223 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-06 19:09:44.212  1003  1223 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-06 19:09:44.212  1003  1223 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 19:09:44.212  1003  1223 D SettingsProvider: name = wifi_on
,09-06 19:09:44.222  1003  1127 E WifiHW  : ##################### set firmware type 0 #####################
,09-06 19:09:44.462  1003  1416 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:44.462  1003  1416 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:44.462  1003  1416 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:44.462  1003  1416 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-06 19:09:44.492  7359  7359 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-06 19:09:44.522  7359  7359 I cr.library_loader: Time to load native libraries: 13 ms (timestamps 3548-3561)
,09-06 19:09:44.522  7359  7359 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-06 19:09:44.522  7359  7359 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {26903261}
,09-06 19:09:44.532  7359  7359 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-06 19:09:44.532  7359  7359 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-06 19:09:44.552  7359  7359 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-06 19:09:44.562  7359  7359 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 19:09:44.562  7359  7359 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-06 19:09:44.582  7359  7359 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 19:09:44.582  7359  7359 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 19:09:44.582  7359  7359 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 19:09:44.582  7359  7359 I Adreno-EGL: Local Branch: 
09-06 19:09:44.582  7359  7359 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 19:09:44.582  7359  7359 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 19:09:44.582  7359  7359 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-06 19:09:44.582  1003  1045 D Tethering: interfaceAdded wlan0
,09-06 19:09:44.592  1003  1132 E Tethering: No numeric data,
,09-06 19:09:44.592  1003  1124 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:09:44.592  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:09:44.592  1180  1180 D HotspotTile: updateTetherState():false, false
,09-06 19:09:44.602  1003  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:44.602  1003  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:09:44.602  1003  1132 D Tethering: clearTetheredNotification()
09-06 19:09:44.602  1003  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-06 19:09:44.602  1003  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:09:44.602  1003  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:09:44.602  1003  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:09:44.602  1003  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:09:44.602  1003  1132 D Tethering: InitialState.processMessage what=4
,09-06 19:09:44.602  1003  1045 D Tethering: interfaceAdded p2p0
,09-06 19:09:44.602   278   905 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-06 19:09:44.602   278   905 D SoftapController: Softap fwReload - Ok
,09-06 19:09:44.602  1003  1132 E Tethering: No numeric data
,09-06 19:09:44.602  1003  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:09:44.602  1003  1132 D Tethering: clearTetheredNotification()
09-06 19:09:44.602  1003  1124 V NetworkStats: performPollLocked() took 9ms
,09-06 19:09:44.602  1003  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-06 19:09:44.612  1003  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:44.612  1003  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:09:44.612  1003  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:09:44.612  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-06 19:09:44.612  1180  1180 D HotspotTile: updateTetherState():false, false
09-06 19:09:44.612  1003  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:09:44.612   278   905 D CommandListener: Setting iface cfg
09-06 19:09:44.612   278   905 D CommandListener: Trying to bring down wlan0
,09-06 19:09:44.612   278   905 D CommandListener: Clearing all IP addresses on wlan0,
09-06 19:09:44.612  1003  1124 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:09:44.612  1003  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:44.612  1003  1124 D NetworkStatsFactory: UpdateStatsForKnox updated,
09-06 19:09:44.612  1003  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:09:44.622  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:44.622  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:44.622  1003  1124 V NetworkStats: performPollLocked() took 7ms
,09-06 19:09:44.622  1003  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:44.622  1003  1127 E WifiHW  : supplicant_name : p2p_supplicant
,09-06 19:09:44.622  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:44.622  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:44.672  7409  7409 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-06 19:09:44.672  7409  7409 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-06 19:09:44.672  7409  7409 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-06 19:09:44.692  7359  7417 W cr.media: Requires BLUETOOTH permission,
,09-06 19:09:44.692  7359  7359 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-06 19:09:44.692  7409  7409 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-06 19:09:44.702   403   403 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7409
09-06 19:09:44.702   403   403 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
09-06 19:09:44.702  7409  7409 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-06 19:09:44.702  7409  7409 I wpa_supplicant: ssSupport state is = 1
09-06 19:09:44.702  7409  7409 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-06 19:09:44.702  7409  7409 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,09-06 19:09:44.702   403   403 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7409
09-06 19:09:44.702   403   403 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,09-06 19:09:44.702  7359  7359 I NSApplication: Starting up...
,09-06 19:09:44.702  1003  1030 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-06 19:09:44.712  1003  1733 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-06 19:09:44.722  1003  1523 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-06 19:09:44.722  1003  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:44.722  1003  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:44.722  1003  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:44.722  1003  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:44.732  7423  7423 E Zygote  : MountEmulatedStorage()
,09-06 19:09:44.732  7423  7423 E Zygote  : v2
09-06 19:09:44.732  7423  7423 I libpersona: KNOX_SDCARD checking this for 10117
09-06 19:09:44.732  7423  7423 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:44.742  7423  7423 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:44.742  1003  1523 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7423 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-06 19:09:44.742  1003  1523 I ActivityManager: Killing 7014:com.qualcomm.timeservice/1000 (adj 15): empty #21
09-06 19:09:44.742  7423  7423 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:44.742  7423  7423 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:09:44.752  1003  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-06 19:09:44.772  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-06 19:09:44.772  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:44.772  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:09:44.772  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:44.772  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:09:44.772  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:44.772  1180  1715 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 19:09:44.772  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:44.772  1180  1180 D HotspotTile: onReceive : 2, 0
09-06 19:09:44.772  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:44.772  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:09:44.772  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-06 19:09:44.772  4809  4809 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-06 19:09:44.772  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:44.782  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:44.792   312   312 I art     : Explicit concurrent mark sweep GC freed 8695(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 758us total 48.711ms
,09-06 19:09:44.792  7423  7423 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-06 19:09:44.792  7423  7423 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:44.812   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 601us total 19.239ms,
,09-06 19:09:44.822  7423  7423 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:09:44.832   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 572us total 17.944ms
,09-06 19:09:44.902   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
,09-06 19:09:44.912   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:09:44.912  7409  7409 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,09-06 19:09:44.962  7409  7409 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-06 19:09:44.962  7409  7409 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-06 19:09:44.972  7409  7409 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-06 19:09:44.972   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7409
09-06 19:09:44.972   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,09-06 19:09:44.972  7409  7409 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-06 19:09:44.972  7409  7409 I wpa_supplicant: ssSupport state is = 1
,09-06 19:09:44.972  7409  7409 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-06 19:09:44.972  7409  7409 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:09:44.972  7409  7409 E wpa_supplicant: SIM READ ERROR
09-06 19:09:44.972  7409  7409 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-06 19:09:44.972  7409  7409 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:09:44.972  7409  7409 E wpa_supplicant: SIM READ ERROR
,09-06 19:09:44.972  7409  7409 I wpa_supplicant: Blacklist: Clear (all) 
09-06 19:09:44.972  7409  7409 I wpa_supplicant: wpa_default_ap_write_once
09-06 19:09:44.972  7409  7409 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-06 19:09:44.972  7409  7409 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:09:44.982  1003  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
09-06 19:09:44.972  7409  7409 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-06 19:09:44.972  7409  7409 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:09:44.972  7409  7409 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:09:44.972  7409  7409 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-06 19:09:44.982  1003  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:09:44.982  1003  1045 D Tethering: interfaceStatusChanged wlan0, false,
,09-06 19:09:45.042  7409  7409 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-06 19:09:45.182  1003  1518 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-06 19:09:45.182  1003  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:45.182  1003  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:45.182  1003  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:45.182  1003  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:45.192  1003  1518 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7445 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,09-06 19:09:45.202  1003  1518 I ActivityManager: Killing 6915:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21,
,09-06 19:09:45.202  7445  7445 E Zygote  : MountEmulatedStorage()
09-06 19:09:45.202  7445  7445 E Zygote  : v2
09-06 19:09:45.202  7445  7445 I libpersona: KNOX_SDCARD checking this for 10121
09-06 19:09:45.202  7445  7445 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:45.212  7445  7445 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:45.212  7445  7445 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:45.212  7445  7445 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-06 19:09:45.232  7445  7445 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:45.242  7445  7445 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:45.252  7445  7445 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:09:45.262  7445  7445 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-06 19:09:45.262  7445  7445 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 19:09:45.272  7409  7409 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-06 19:09:45.272  7409  7409 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-06 19:09:45.282  7445  7445 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE,
,09-06 19:09:45.282  7445  7445 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-06 19:09:45.282  7445  7445 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-06 19:09:45.292  7409  7409 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,09-06 19:09:45.292   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7409
09-06 19:09:45.292   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-06 19:09:45.292  7409  7409 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-06 19:09:45.292  7409  7409 I wpa_supplicant: ssSupport state is = 1
09-06 19:09:45.292  1003  1496 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,09-06 19:09:45.292  7409  7409 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-06 19:09:45.292  7409  7409 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-06 19:09:45.292  1003  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-06 19:09:45.292  1003  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:45.292  1003  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:45.292  1003  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:45.312  7464  7464 E Zygote  : MountEmulatedStorage()
,09-06 19:09:45.312  7464  7464 E Zygote  : v2,
,09-06 19:09:45.312  7464  7464 I libpersona: KNOX_SDCARD checking this for 10141
09-06 19:09:45.312  7464  7464 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 19:09:45.312  7464  7464 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:45.312  1003  1496 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7464 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
09-06 19:09:45.312  1003  1496 I ActivityManager: Killing 6931:com.android.calendar/u0a131 (adj 15): empty #21
09-06 19:09:45.312  7464  7464 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-06 19:09:45.312  7464  7464 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:45.312  7409  7409 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
09-06 19:09:45.312   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7409
09-06 19:09:45.312   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-06 19:09:45.312  7409  7409 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-06 19:09:45.312  7409  7409 I wpa_supplicant: ssSupport state is = 1
09-06 19:09:45.312  7409  7409 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:09:45.312  7409  7409 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:09:45.312  7409  7409 E wpa_supplicant: SIM READ ERROR
09-06 19:09:45.312  7409  7409 I wpa_supplicant: wpa_default_ap_write_once
09-06 19:09:45.312  7409  7409 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-06 19:09:45.322  7409  7409 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-06 19:09:45.322  1003  1045 D Tethering: interfaceLinkStateChanged p2p0, false,
09-06 19:09:45.322  1003  1045 D Tethering: interfaceStatusChanged p2p0, false
09-06 19:09:45.322  1003  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:09:45.322  1003  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:09:45.322  1003  1045 D Tethering: interfaceStatusChanged p2p0, false
09-06 19:09:45.322  1003  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 19:09:45.332  7464  7464 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:09:45.332  7464  7464 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:45.352  7464  7464 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-06 19:09:45.352  7464  7464 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:09:45.352  7464  7464 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-06 19:09:45.352  7464  7464 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-06 19:09:45.372  7409  7409 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
09-06 19:09:45.372  7409  7409 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-06 19:09:45.402  1003  1512 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:09:45.412  1003  1416 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:09:45.442  1003  1029 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:09:45.452  1003  1030 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:09:45.462  7409  7409 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
09-06 19:09:45.462  7409  7409 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-06 19:09:45.462  7409  7409 I wpa_supplicant: Skip scan - bUseNetwork false
,09-06 19:09:45.462  1003  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-06 19:09:45.472  1003  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-06 19:09:45.472  7409  7409 I wpa_supplicant: HOTSPOT20_ENABLE called
09-06 19:09:45.472  7409  7409 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:09:45.472  7409  7409 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:09:45.472  7409  7409 E wpa_supplicant: SIM READ ERROR
09-06 19:09:45.472  7409  7409 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:09:45.492  1003  1416 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,09-06 19:09:45.492  1003  1416 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:45.492  1003  1416 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-06 19:09:45.492  1003  1416 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:45.492  1003  1416 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:45.492  7409  7409 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-06 19:09:45.502  7409  7409 I wpa_supplicant: Skip scan - bUseNetwork false
,09-06 19:09:45.502  7487  7487 E Zygote  : MountEmulatedStorage()
,09-06 19:09:45.502  7487  7487 E Zygote  : v2
09-06 19:09:45.502  7487  7487 I libpersona: KNOX_SDCARD checking this for 10068
09-06 19:09:45.512  7487  7487 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:45.512  1003  1223 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:09:45.512  7487  7487 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:45.512  7487  7487 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-06 19:09:45.512  7487  7487 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-06 19:09:45.512  1003  1416 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7487 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,09-06 19:09:45.512  1003  1127 D WifiConfigStore: Loading config and enabling all networks 
,09-06 19:09:45.532  1003  1518 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:09:45.532  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-06 19:09:45.532  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:45.532  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:09:45.532  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:45.532  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:45.532  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:45.532  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:45.532  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:09:45.532  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-06 19:09:45.532  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:09:45.532  1180  1715 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-06 19:09:45.532  1180  1180 D HotspotTile: onReceive : 3, 0
,09-06 19:09:45.532  4809  4809 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:09:45.542  1003  1127 E WifiConfigStore: Not a HS20
,09-06 19:09:45.542  6822  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:45.542  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:45.542  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:45.542  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:45.542  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:45.542  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:45.542  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:45.542  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:45.542  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:09:45.542  6822  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:45.542  6822  6822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:09:45.542  1003  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-06 19:09:45.542  6822  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:09:45.552  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:45.552  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:45.552  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:45.552  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:45.552  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:45.552  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:45.552  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:45.552  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:09:45.552  6822  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:45.552  6822  6822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:09:45.552  1003  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-06 19:09:45.552  7487  7487 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:45.552  7487  7487 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:45.552  7409  7409 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-06 19:09:45.552  7409  7409 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-06 19:09:45.552  7409  7409 I wpa_supplicant: reset timer : RESET_TIMER 0
09-06 19:09:45.552  7409  7409 I wpa_supplicant: P2P: Current p2p state = IDLE
09-06 19:09:45.552  7409  7409 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-06 19:09:45.552  7409  7409 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-06 19:09:45.552  7409  7409 I wpa_supplicant: First Scan Start
09-06 19:09:45.552  7409  7409 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-06 19:09:45.562  7191  7191 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:09:45.562  1003  1127 D WifiNative-wlan0: Setting external_sim to 1
,09-06 19:09:45.562  1003  1127 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 19:09:45.562  1003  1127 I WifiNative-HAL: startHal
09-06 19:09:45.562  1003  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9f4dc88c
09-06 19:09:45.562  1003  1127 I WifiNative-HAL: Could not start hal
,09-06 19:09:45.572  1003  1127 E WifiNative-wlan0: do suspend true
,09-06 19:09:45.572  1003  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-06 19:09:45.572  1003  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-06 19:09:45.572  1003  1733 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:09:45.572   278   905 D CommandListener: Setting iface cfg
09-06 19:09:45.572   278   905 D CommandListener: Trying to bring up p2p0
09-06 19:09:45.582  1003  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-06 19:09:45.582  1003  1126 D WifiP2pService: P2pEnablingState
09-06 19:09:45.582  1003  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:09:45.582  1003  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
09-06 19:09:45.582  1003  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 19:09:45.582  1003  1045 D Tethering: interfaceStatusChanged p2p0, false
09-06 19:09:45.582  1003  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 19:09:45.582  1003  1003 D WifiScanningService: SCAN_AVAILABLE : 3
09-06 19:09:45.582  1003  1127 E WifiNative-wlan0: invaild command id : 215
09-06 19:09:45.582  1003  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 19:09:45.582  1003  1003 D RttService: SCAN_AVAILABLE : 3,
09-06 19:09:45.582  1003  1126 D WifiP2pService: P2p socket connection successful
09-06 19:09:45.582  1003  1153 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:09:45.582  1003  1126 D WifiP2pService: P2pEnabledState
09-06 19:09:45.582  1003  1152 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:09:45.582  1003  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-06 19:09:45.582  1003  1152 I WifiNative-HAL: startHal
09-06 19:09:45.582  7409  7409 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-06 19:09:45.582  1003  1129 E ConnectivityService: updateNetworkInfo()
09-06 19:09:45.582  7409  7409 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-06 19:09:45.582  1003  1152 E wifi    : getStaticLongField sWifiHalHandle 0x9e39e9bc
09-06 19:09:45.582  1003  1152 I WifiNative-HAL: Could not start hal
09-06 19:09:45.582  1003  1152 E WifiScanningService: could not start HAL
09-06 19:09:45.582  7409  7409 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-06 19:09:45.582  1003  1127 E WifiStateMachine: Failed to set frequency band 0
,09-06 19:09:45.582  1003  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:09:45.582  1003  1127 D SecContentProvider2: mCursor = null
,09-06 19:09:45.582  1003  1003 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-06 19:09:45.592  1003  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-06 19:09:45.592  1003  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:09:45.592  1003  1048 D WifiDisplayController: disconnect
09-06 19:09:45.592  1003  1048 D WifiDisplayController: updateConnection
09-06 19:09:45.592  1003  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:09:45.592  1003  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 19:09:45.592  1003  1496 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-06 19:09:45.592  1003  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:45.592  1003  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:45.592  1003  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:45.592  1003  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:45.592  7487  7487 D BadgeProvider: onCreate
,09-06 19:09:45.592  7487  7487 D BadgeProvider: DatabaseHelper
,09-06 19:09:45.602  7505  7505 E Zygote  : MountEmulatedStorage(),
09-06 19:09:45.602  7505  7505 E Zygote  : v2
,09-06 19:09:45.602  1003  1496 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7505 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,09-06 19:09:45.602  1003  1496 I ActivityManager: Killing 7042:com.android.vending/u0a26 (adj 15): empty #21
09-06 19:09:45.612  7505  7505 I libpersona: KNOX_SDCARD checking this for 10009
09-06 19:09:45.612  7505  7505 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:45.612  1003  1496 I ActivityManager: Killing 6718:com.android.defcontainer/u0a3 (adj 15): empty #22
09-06 19:09:45.612  7505  7505 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:45.612  1003  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:09:45.612  1003  1127 D SecContentProvider2: mCursor = null
,09-06 19:09:45.612  7505  7505 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:45.612  7505  7505 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-06 19:09:45.632  1180  1180 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-06 19:09:45.632  1003  1523 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 19:09:45.632  1180  1180 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-06 19:09:45.642  1003  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-06 19:09:45.642  1003  1048 D WifiDisplayAdapter: onP2pDisconnected
,09-06 19:09:45.642  1003  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:09:45.642  1003  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-06 19:09:45.642  1003  1126 D WifiNative-p2p0: p2pGetDeviceAddress
,09-06 19:09:45.642  1003  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,09-06 19:09:45.642  7505  7505 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:45.642  7505  7505 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:45.652  1003  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-06 19:09:45.652  1003  1048 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-06 19:09:45.652  1003  1048 D WifiDisplayController:  primary type: 10-0050F204-5
09-06 19:09:45.652  1003  1048 D WifiDisplayController:  secondary type: null
09-06 19:09:45.652  1003  1048 D WifiDisplayController:  wps: 0
09-06 19:09:45.652  1003  1048 D WifiDisplayController:  grpcapab: 0
09-06 19:09:45.652  1003  1048 D WifiDisplayController:  devcapab: 0
09-06 19:09:45.652  1003  1048 D WifiDisplayController:  status: 3
09-06 19:09:45.652  1003  1048 D WifiDisplayController:  wfdInfo: null
09-06 19:09:45.652  1003  1048 D WifiDisplayController:  groupownerAddress: null
09-06 19:09:45.652  1003  1048 D WifiDisplayController:  GOdeviceName: null
09-06 19:09:45.652  1003  1048 D WifiDisplayController:  interfaceAddress: 
09-06 19:09:45.652  1003  1048 D WifiDisplayController:  SConnectInfo : null
,09-06 19:09:45.652  1003  1126 D WifiP2pService: DeviceAddress: 0a:75:42
,09-06 19:09:45.672  1003  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-06 19:09:45.672  1003  1126 D WifiP2pService: InactiveState
09-06 19:09:45.672  1003  1126 D WifiP2pService: InactiveState{ what=143376 }
,09-06 19:09:45.672  1003  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 19:09:45.672  7409  7409 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-06 19:09:45.672  1003  1126 D WifiP2pService: InactiveState{ what=143376 }
09-06 19:09:45.672  1003  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 19:09:45.722  1003  1733 I ActivityManager: Killing 7158:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,09-06 19:09:45.742  1003  1029 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:09:45.742  1003  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:09:45.742  1003  1029 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:45.742  1003  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:45.742  1003  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:09:45.742  1611  1611 I Hs20UtilService: Starting #11
,09-06 19:09:45.742  1611  1654 I Hs20UtilService: Message received 5011
,09-06 19:09:45.752  6971  6971 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 19:09:45.752  6971  6971 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:09:45.752  6971  6971 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:09:45.752  6971  6971 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:09:45.762  1003  1496 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:09:45.762  1003  1496 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:09:45.762  1003  1496 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:45.762  1003  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:45.762  1003  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:09:45.762  1611  1611 I Hs20UtilService: Starting #12
,09-06 19:09:45.762  1611  1654 I Hs20UtilService: Message received 5011
,09-06 19:09:45.782  6971  6971 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 19:09:45.782  6971  6971 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:09:45.782  6971  6971 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:09:45.782  6971  6971 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:09:45.792  1003  1518 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:09:45.792  1003  1518 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:45.792  1003  1518 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 19:09:45.792  1003  1518 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:45.792  1003  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:09:45.792  1611  1611 I Hs20UtilService: Starting #13
,09-06 19:09:45.792  6971  6971 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 19:09:45.792  1003  1416 I art     : Explicit concurrent mark sweep GC freed 63144(3MB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 22MB/34MB, paused 6.169ms total 185.053ms
,09-06 19:09:45.792  1611  1654 I Hs20UtilService: Message received 5011
,09-06 19:09:45.802  6971  6971 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-06 19:09:45.802  6971  6971 D SecurityLogAgent: StateMachine : Current State = 1
,09-06 19:09:45.802  6971  6971 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:09:45.812  1003  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,09-06 19:09:45.822  1003  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 19:09:45.822  1003  1127 E WifiNative-wlan0: invaild command id : 215
,09-06 19:09:45.822  7487  7499 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
09-06 19:09:45.822  4809  4809 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-06 19:09:45.822  4809  4809 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:09:45.832  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:09:45.832  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 19:09:45.832  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:09:45.832  4809  4809 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:09:45.832  4809  4849 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:09:45.832  1003  1029 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-06 19:09:45.842  1003  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:45.842  1003  1043 W ProcessCpuTracker: Skipping unknown process pid 7158
,09-06 19:09:45.842  1003  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:45.842  1003  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:45.842  1003  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:45.852  7524  7524 E Zygote  : MountEmulatedStorage()
09-06 19:09:45.852  7524  7524 E Zygote  : v2
09-06 19:09:45.852  7524  7524 I libpersona: KNOX_SDCARD checking this for 10064
09-06 19:09:45.852  7524  7524 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:45.852  7524  7524 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:45.852  1003  1029 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7524 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-06 19:09:45.862  7524  7524 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:45.862  1003  1733 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,09-06 19:09:45.862  1003  1733 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
09-06 19:09:45.862  7524  7524 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:45.862  1003  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0,
,09-06 19:09:45.862  1003  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-06 19:09:45.872  7487  7499 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-06 19:09:45.872  7487  7499 D BadgeProvider: sendNotify, [notify] : null
09-06 19:09:45.872  7487  7499 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-06 19:09:45.872  7487  7499 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-06 19:09:45.872  7487  7499 D BadgeProvider: update, [UpdateCount] : 1
,09-06 19:09:45.872  1506  1506 D Launcher.Model: reloadBadges entered.
,09-06 19:09:45.882  7524  7524 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:45.882  7524  7524 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:45.892  7524  7524 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-06 19:09:45.902  7524  7524 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:09:45.912  7524  7524 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-06 19:09:45.912   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:09:45.932  7524  7524 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 19:09:45.932  7175  7175 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:09:45.942  1003  1137 I ActivityManager: Killing 7092:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,09-06 19:09:46.862  7409  7409 I wpa_supplicant: nl80211: Received scan results (13 BSSes),
09-06 19:09:46.862  7409  7409 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-06 19:09:46.862  7409  7409 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,09-06 19:09:46.862  7409  7409 I wpa_supplicant: Trying to associate with  'G700'
09-06 19:09:46.862  7409  7409 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-06 19:09:46.862  7409  7409 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
09-06 19:09:46.862  1003  7484 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-06 19:09:46.882  1003  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-06 19:09:46.882  1003  1127 D SecContentProvider2: mCursor = null
,09-06 19:09:46.912   291   291 E SMD     : DCD OFF,
,09-06 19:09:46.912   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:09:46.952  1003  1733 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-06 19:09:46.952  1003  1733 D BatteryService: level:98, scale:100, status:2, health:2, present:true, voltage: 4248, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
09-06 19:09:46.952  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-06 19:09:46.952  1003  1733 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-06 19:09:46.952  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate,
09-06 19:09:46.952  1003  1733 D BatteryService: stay LED for charging
,09-06 19:09:46.952  1003  1003 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-06 19:09:46.952  1003  1003 I MotionRecognitionService: Plugged,
09-06 19:09:46.952  1003  1003 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 19:09:46.962  1436  1436 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-06 19:09:46.962  1436  1436 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 98
,09-06 19:09:46.992  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:98 status:2 health:2
,09-06 19:09:46.992  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:98 status:2 health:2
,09-06 19:09:46.992  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:98 status:2 health:2
,09-06 19:09:46.992  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-06 19:09:46.992  1180  1180 D SViewCoverView: level :98 plugged : 2
,09-06 19:09:47.012  7409  7409 E wpa_supplicant: Cmd 35605 not handled,
,09-06 19:09:47.012  1003  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:09:47.012  7409  7409 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED,
09-06 19:09:47.012  1003  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:09:47.012  1003  1045 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:09:47.012  7409  7409 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,09-06 19:09:47.012  7409  7409 I wpa_supplicant: Associated with F4.99.3E
09-06 19:09:47.012  7409  7409 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-06 19:09:47.012  7409  7409 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-06 19:09:47.012  7409  7409 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
09-06 19:09:47.022  1003  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 19:09:47.022  1003  1045 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:09:47.022  1003  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:09:47.022  1003  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
09-06 19:09:47.022  1003  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:09:47.022  1003  1045 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:09:47.022  1003  1045 D Tethering: interfaceLinkStateChanged wlan0, true
09-06 19:09:47.022  1003  1045 D Tethering: interfaceStatusChanged wlan0, true
09-06 19:09:47.032  1003  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-06 19:09:47.032  1003  1132 E Tethering: No numeric data
,09-06 19:09:47.032  1003  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:09:47.032  1003  1127 D SecContentProvider2: mCursor = null
09-06 19:09:47.032  1003  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:09:47.032  1003  1132 D Tethering: clearTetheredNotification(),
09-06 19:09:47.032  1003  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:47.032  1003  1124 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:09:47.032  7409  7409 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-06 19:09:47.032  7409  7409 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
09-06 19:09:47.032  1003  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:09:47.032  1003  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:09:47.032  7409  7409 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-06 19:09:47.032  7409  7409 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030,
09-06 19:09:47.042  7409  7409 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:09:47.042  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:09:47.042  7409  7409 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-06 19:09:47.042  1180  1180 D HotspotTile: updateTetherState():false, false
09-06 19:09:47.042  7409  7409 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-06 19:09:47.042  7409  7409 I wpa_supplicant: Blacklist: Clear (temp) 
09-06 19:09:47.042  7409  7409 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-06 19:09:47.042  1003  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:09:47.042  1003  1127 D SecContentProvider2: mCursor = null
09-06 19:09:47.042  1003  1124 V NetworkStats: performPollLocked() took 8ms
09-06 19:09:47.042  1003  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:47.042  1003  1045 D Tethering: interfaceLinkStateChanged wlan0, true
09-06 19:09:47.042  1003  1045 D Tethering: interfaceStatusChanged wlan0, true
09-06 19:09:47.042  1003  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-06 19:09:47.042  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:47.042  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:47.052  1003  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-06 19:09:47.052  1003  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,09-06 19:09:47.062  1003  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-06 19:09:47.062  1003  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,09-06 19:09:47.062  1003  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:09:47.062  1003  1129 E ConnectivityService: updateNetworkInfo()
,09-06 19:09:47.062  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-06 19:09:47.062  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-06 19:09:47.062  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-06 19:09:47.062  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-06 19:09:47.062  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.072  1003  1512 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:09:47.062  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.072  1003  1512 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:09:47.062  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.062  1003  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:09:47.072  1003  1512 W ActivityManager: userId = 0, bbcId = -10000,
,09-06 19:09:47.072  1003  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:47.072  1003  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:09:47.072  1611  1611 I Hs20UtilService: Starting #14
09-06 19:09:47.072  1611  1654 I Hs20UtilService: Message received 5007
09-06 19:09:47.072  4809  4809 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
,09-06 19:09:47.072  4809  4809 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 19:09:47.072  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-06 19:09:47.082  1003  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:09:47.082  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:09:47.082  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:09:47.082  4809  4809 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:09:47.082  4809  4849 V NearbySettings: MountReceiver.mPrefHandler - 7002,
,09-06 19:09:47.092   278   905 D CommandListener: Setting iface cfg
,09-06 19:09:47.092  1003  1127 E WifiStateMachine: Start Dhcp Watchdog 2
,09-06 19:09:47.092  1003  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-06 19:09:47.092  1003  1127 D SecContentProvider2: mCursor = null
,09-06 19:09:47.102  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-06 19:09:47.102  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:47.102  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:09:47.112  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:47.112  1003  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:09:47.112  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.112  1003  1127 D SecContentProvider2: mCursor = null
09-06 19:09:47.112  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.112  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:47.112  1003  1127 E WifiNative-wlan0: do suspend false
,09-06 19:09:47.112  1003  1126 D WifiP2pService: InactiveState{ what=143375 }
,09-06 19:09:47.112  1003  1126 D WifiP2pService: P2pEnabledState{ what=143375 },
,09-06 19:09:47.222  1003  1416 D SecContentProvider: uri = 18 selection = isWifiEnabled,
09-06 19:09:47.222  1003  1416 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 19:09:47.222  1003  1416 D SecContentProvider2: mCursor = null
,09-06 19:09:47.232  1003  1416 D WifiService: setWifiEnabled: false pid=6822, uid=10170
,09-06 19:09:47.232  1003  1416 D SettingsProvider: name = wifi_on
,09-06 19:09:47.242  1003  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:09:47.252  1003  1127 E WifiNative-wlan0: do suspend true
,09-06 19:09:47.272  1003  1126 D WifiP2pService: InactiveState{ what=143375 }
,09-06 19:09:47.272  1003  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-06 19:09:47.272  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-06 19:09:47.282   278   905 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:09:47.282  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:09:47.282  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:09:47.282  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:47.282  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:47.282  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.282  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:47.282  1003  1129 E ConnectivityService: updateNetworkInfo()
09-06 19:09:47.282  1003  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:09:47.282  1003  1129 E ConnectivityService: updateNetworkInfo()
09-06 19:09:47.282  1003  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
09-06 19:09:47.282  1003  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-06 19:09:47.282   278   905 E Netd    : no such netId 503
09-06 19:09:47.282  1003  1126 D WifiP2pService: InactiveState{ what=131204 }
09-06 19:09:47.282  1003  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-06 19:09:47.282  1003  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-06 19:09:47.292  1003  1003 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-06 19:09:47.292  1003  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:47.292  1003  1129 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
09-06 19:09:47.292  1003  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-06 19:09:47.292  1003  1129 V NetworkStats: updateIfacesLocked()
09-06 19:09:47.292  1003  1129 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:09:47.292  1003  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-06 19:09:47.302  1003  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
,09-06 19:09:47.302  1003  1003 D WifiScanningService: SCAN_AVAILABLE : 1,
09-06 19:09:47.302  1003  1129 V NetworkStats: performPollLocked() took 13ms
09-06 19:09:47.302  1003  1152 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:09:47.302  1003  1003 D RttService: SCAN_AVAILABLE : 1
09-06 19:09:47.302  1003  1153 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:09:47.302  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-06 19:09:47.302  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:47.302  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:09:47.302  1003  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:47.302  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.302  1003  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
09-06 19:09:47.302  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.302  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:47.302  1003  1129 D ConnectivityService: nai.networkMonitor.doQuit()
,09-06 19:09:47.302  1003  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-06 19:09:47.302  1003  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-06 19:09:47.312  1003  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-06 19:09:47.302  1003  7540 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:09:47.302  1003  1129 E ConnectivityService: updateNetworkInfo()
,09-06 19:09:47.302  1003  7540 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-06 19:09:47.312  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:47.312  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:47.312  1003  1129 E ConnectivityService: updateNetworkInfo()
09-06 19:09:47.312  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.312  1003  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-06 19:09:47.312  1003  1048 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:09:47.312  1003  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:09:47.312  1003  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-06 19:09:47.312  1003  1003 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-06 19:09:47.312  1003  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false,
09-06 19:09:47.312  1003  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:09:47.312  1003  1048 D WifiDisplayController: disconnect
09-06 19:09:47.312  1003  1048 D WifiDisplayController: updateConnection
09-06 19:09:47.312  1003  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-06 19:09:47.312  1003  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 19:09:47.312  1003  1512 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:09:47.312  1003  1512 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:09:47.312  1003  1512 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:47.312  1003  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:47.312  1003  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:09:47.322  1611  1611 I Hs20UtilService: Starting #15
09-06 19:09:47.322  1611  1654 I Hs20UtilService: Message received 5007
,09-06 19:09:47.322  4809  4809 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 19:09:47.322  4809  4809 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:09:47.322  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:09:47.332  1003  1126 D WifiP2pService: P2pDisablingState
,09-06 19:09:47.332  1003  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
,09-06 19:09:47.332  1003  1126 D WifiP2pService: p2p socket connection lost
,09-06 19:09:47.332  1003  1126 D WifiP2pService: P2pDisabledState
,09-06 19:09:47.332  1003  1127 E WifiNative-wlan0: do suspend true
09-06 19:09:47.332  1180  1180 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-06 19:09:47.332  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:09:47.332  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:09:47.332  4809  4809 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 19:09:47.332  4809  4849 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:09:47.332  1003  1416 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
09-06 19:09:47.332  7545  7545 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
09-06 19:09:47.332  1180  1180 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-06 19:09:47.342  7545  7545 I dhcpcd  : version 5.5.6 starting,
,09-06 19:09:47.342  1003  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-06 19:09:47.342  1003  1048 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:09:47.342  1003  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:09:47.342  1003  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-06 19:09:47.352  4809  4809 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-06 19:09:47.352  4809  4809 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:09:47.352  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-06 19:09:47.352  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
09-06 19:09:47.352  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:09:47.352  4809  4809 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:09:47.352  4809  4849 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:09:47.352  7524  7524 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:09:47.362  7524  7524 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-06 19:09:47.362  7524  7524 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 19:09:47.362  7175  7175 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:09:47.372  7545  7545 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-06 19:09:47.382   278   905 D CommandListener: Clearing all IP addresses on wlan0,
09-06 19:09:47.382  1003  1126 D WifiP2pService: P2pDisabledState{ what=143375 },
09-06 19:09:47.382  1003  1126 D WifiP2pService: DefaultState{ what=143375 }
,09-06 19:09:47.382  1003  1003 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-06 19:09:47.392  7409  7409 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
09-06 19:09:47.392  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-06 19:09:47.392  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:09:47.392  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:09:47.392  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.392  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.392  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-06 19:09:47.392  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:47.402  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
,09-06 19:09:47.402  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:47.402  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:09:47.402  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.402  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.402  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.402  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:47.412  1003  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:09:47.412  1003  1127 D SecContentProvider2: mCursor = null
,09-06 19:09:47.412  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-06 19:09:47.412  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:47.412  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:09:47.412  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:47.412  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.412  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:47.412  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:47.412  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:09:47.412  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-06 19:09:47.412  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:09:47.422  1180  1180 D HotspotTile: onReceive : 0, 0
09-06 19:09:47.422  1180  1715 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
,09-06 19:09:47.422  4809  4809 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:09:47.422  1003  1137 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:09:47.422  1003  1137 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:09:47.422  1003  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:47.422  1003  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:47.422  1003  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:09:47.432  1611  1611 I Hs20UtilService: Starting #16
,09-06 19:09:47.432  1611  1654 I Hs20UtilService: Message received 5007
,09-06 19:09:47.432  4809  4809 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-06 19:09:47.432  4809  4809 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:09:47.432  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:09:47.432  6822  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:09:47.432  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:47.432  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:47.432  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:47.432  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:47.432  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:47.432  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:47.432  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:47.432  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:09:47.442  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 19:09:47.442  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:09:47.442  4809  4809 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 19:09:47.442  6822  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:47.442  6822  6822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
09-06 19:09:47.442  4809  4849 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:09:47.442  6822  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-06 19:09:47.442  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-06 19:09:47.442  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:47.442  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:47.442  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:47.442  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:47.442  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:47.442  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:47.442  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:09:47.442  6822  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:47.442  1003  1137 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:09:47.442  6822  6822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:09:47.442  1003  1137 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 19:09:47.442  1003  1137 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:47.442  1003  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:47.442  1003  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:09:47.452  1611  1611 I Hs20UtilService: Starting #17
,09-06 19:09:47.452  1611  1654 I Hs20UtilService: Message received 5011
09-06 19:09:47.452  7545  7545 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-06 19:09:47.452  7545  7545 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-06 19:09:47.452  7545  7545 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,09-06 19:09:47.452  7545  7545 I dhcpcd  : bssid match,
09-06 19:09:47.452  7545  7545 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,09-06 19:09:47.452  6971  6971 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 19:09:47.452  6971  6971 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:09:47.452  6971  6971 D SecurityLogAgent: StateMachine : Current State = 1
,09-06 19:09:47.452  6971  6971 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:09:47.552  7409  7409 I wpa_supplicant: Blacklist: Clear (all) ,
,09-06 19:09:47.632  7545  7545 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,09-06 19:09:47.632  7545  7545 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds,
,09-06 19:09:47.632  1003  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:09:47.632  1003  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 19:09:47.632  1003  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:09:47.632  7409  7409 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
,09-06 19:09:47.662  7409  7409 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
09-06 19:09:47.662  7409  7409 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-06 19:09:47.662  7409  7409 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-06 19:09:47.662  7409  7409 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-06 19:09:47.662  7409  7409 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-06 19:09:47.662  1003  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 19:09:47.662  1003  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:09:47.672  1003  1132 D Tethering: InitialState.processMessage what=4
09-06 19:09:47.672  1003  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:09:47.672  1003  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:09:47.672  1003  1045 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:09:47.672  1003  1132 E Tethering: No numeric data
,09-06 19:09:47.672  1003  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:09:47.672  1003  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:09:47.672  1003  1124 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:09:47.672  1003  1132 D Tethering: clearTetheredNotification()
09-06 19:09:47.672  1003  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:47.672  1003  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:09:47.672  1003  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:09:47.672  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:09:47.672  1180  1180 D HotspotTile: updateTetherState():false, false
,09-06 19:09:47.682  1003  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 19:09:47.682  1003  1045 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:09:47.682  1003  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:09:47.682  1003  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:47.682  1003  1124 V NetworkStats: performPollLocked() took 8ms
,09-06 19:09:47.682  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:47.682  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:47.912  7409  7409 I wpa_supplicant: Blacklist: Clear (all) ,
,09-06 19:09:47.912   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:09:47.992  1003  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:09:47.992  7409  7409 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-06 19:09:47.992  1003  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:09:47.992  1003  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:09:47.992  1003  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
09-06 19:09:47.992  1003  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:09:47.992  1003  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:09:48.102  1003  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-06 19:09:48.102  1003  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-06 19:09:48.102  7191  7191 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:09:48.102  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-06 19:09:48.112  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:09:48.112  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null,
09-06 19:09:48.112  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:09:48.112  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:48.112  1180  1715 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 19:09:48.112  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:48.112  1180  1180 D HotspotTile: onReceive : 1, 0
,09-06 19:09:48.112  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:48.112  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:48.112  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:09:48.112  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-06 19:09:48.112  4809  4809 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:09:48.122  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:48.122  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:48.122  1003  1496 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:09:48.122  1003  1496 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 19:09:48.122  1752  2185 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:09:48.122  1003  1496 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:48.122  1003  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:48.122  1003  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:09:48.122  1611  1611 I Hs20UtilService: Starting #18
,09-06 19:09:48.122  1611  1654 I Hs20UtilService: Message received 5011
,09-06 19:09:48.122  6971  6971 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 19:09:48.132  6971  6971 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:09:48.132  6971  6971 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:09:48.132  6971  6971 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:09:48.182  5874  5874 D FactoryTest: Not factory mode
,09-06 19:09:48.182  5874  5874 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-06 19:09:48.182  5874  5874 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,09-06 19:09:48.182  5874  5874 D MTPRx   : still no open session command from host, so toast
,09-06 19:09:48.192  5874  5874 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 ,
09-06 19:09:48.192  5874  5874 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,09-06 19:09:48.192  5874  5874 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:117235,
09-06 19:09:48.192  1003  1030 E PersonaManagerService: inState():  stateMachine is null !!
09-06 19:09:48.192  1003  1030 I PersonaManagerService: PersonaId don't exist,
09-06 19:09:48.192  1003  1030 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-06 19:09:48.202  1003  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,09-06 19:09:48.202  1003  1030 W ActivityManager: userId = 0, bbcId = -10000,
,09-06 19:09:48.202  1003  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:48.202  1003  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-06 19:09:48.212  1003  1030 W ActivityManager: mDVFSHelper.acquire()
,09-06 19:09:48.222  1003  1030 D PersonaManager: isKioskContainerExistOnDevice
,09-06 19:09:48.232  1003  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-06 19:09:48.232  1003  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-06 19:09:48.232  1003  1030 D InputDispatcher: Focused application set to: xxxx
,09-06 19:09:48.232  1003  1030 D InputDispatcher: Focus left window: 6822
,09-06 19:09:48.232  5874  5874 E MTPRx   : started activity for popup
,09-06 19:09:48.242  1003  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-06 19:09:48.242  1003  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 19:09:48.262  5874  5874 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,09-06 19:09:48.262  5874  5874 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,09-06 19:09:48.262  5874  5874 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-06 19:09:48.262  5874  5874 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:09:48.262  5874  5874 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-06 19:09:48.262  5874  5874 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 19:09:48.292  5874  5874 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-06 19:09:48.292  1003  1137 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-06 19:09:48.292  1003  1137 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-06 19:09:48.292  1003  1137 D InputDispatcher: Focused application set to: xxxx
,09-06 19:09:48.292  1003  1137 D InputDispatcher: Focus entered window: 6822
,09-06 19:09:48.302  1003  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-06 19:09:48.302  1003  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 19:09:48.302  1003  1518 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-06 19:09:48.302  1003  1518 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@16d278c1 attribute=null, token = android.os.BinderProxy@331ad4b0
,09-06 19:09:48.332  5874  5874 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-06 19:09:48.342  5874  5874 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-06 19:09:48.342  5874  5874 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-06 19:09:48.362  6822  6822 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-06 19:09:48.362  6822  6822 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-06 19:09:48.362  6822  6822 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-06 19:09:48.362  6822  6822 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-06 19:09:48.362  1003  1416 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-06 19:09:48.362  1003  1416 D KnoxTimeoutHandler: postActiveUserChange for user 0
,09-06 19:09:48.362  1003  1416 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-06 19:09:48.362  1003  1003 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-06 19:09:48.362  1003  1003 D PersonaManagerService: getPersonasForUser(): returning null!
,09-06 19:09:48.372  6822  6822 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-06 19:09:48.372  6822  6822 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-06 19:09:48.382  6822  6822 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3fa9a777 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@314fc92d, 16908290=android.view.AbsSavedState$1@314fc92d}, android:focusedViewId=100}]}]
09-06 19:09:48.382  6822  6822 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-06 19:09:48.382  6822  6822 V ActivityThread: updateVisibility : ActivityRecord{1450df81 token=android.os.BinderProxy@3d41228b {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-06 19:09:48.382  6822  6822 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-06 19:09:48.382  6822  6822 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-06 19:09:48.382  6822  6822 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3d41228b time:117422
,09-06 19:09:48.392  1003  1223 D PersonaManager: isKioskContainerExistOnDevice
,09-06 19:09:48.622   278   899 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,09-06 19:09:48.622  1003  1045 D Tethering: interfaceRemoved wlan0
,09-06 19:09:48.622  1003  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-06 19:09:48.792  1003  1045 D Tethering: interfaceRemoved p2p0
,09-06 19:09:48.792  1003  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-06 19:09:48.912   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:09:49.212  1003  1096 V AlarmManager: waitForAlarm result :4
,09-06 19:09:49.212   278   901 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
09-06 19:09:49.212   278   901 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-06 19:09:49.222  1003  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:49.222  1003  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:49.222  1003  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,09-06 19:09:49.472  1003  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-06 19:09:49.912   291   291 E SMD     : DCD OFF,
09-06 19:09:49.912   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-06 19:09:50.242  6822  7033 D BluetoothAdapter: enable()
,09-06 19:09:50.242  1003  1733 W ActivityManager: Permission Denial: getCurrentUser() from pid=6822, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-06 19:09:50.242  1003  1733 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-06 19:09:50.242  1003  1733 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6822, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:09:50.242  1003  1733 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 19:09:50.242  1003  1733 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-06 19:09:50.242  1003  1733 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-06 19:09:50.242  1003  1733 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-06 19:09:50.242  1003  1733 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 19:09:50.242  1003  1733 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-06 19:09:50.242  1003  1733 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:09:50.242  1003  1733 D SettingsProvider: name = bluetooth_on
,09-06 19:09:50.252  1003  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-06 19:09:50.252  1003  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:09:50.252  1003  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-06 19:09:50.262  3204  3279 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
09-06 19:09:50.262  3204  3279 D BluetoothAdapterProperties: Setting state to 11
09-06 19:09:50.262  3204  3279 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-06 19:09:50.262  3204  3279 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:09:50.262  3204  3279 D BluetoothAdapterService: updateAdapterState state is 11
,09-06 19:09:50.262  3204  3279 D BluetoothAdapterService: Autoconnection is available 
09-06 19:09:50.262  3204  3279 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
09-06 19:09:50.262  3204  3279 D BtConfig.SecureMode: isSecureModeOn:false
09-06 19:09:50.262  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-06 19:09:50.262  3204  3279 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
09-06 19:09:50.262  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-06 19:09:50.262  3204  3279 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
09-06 19:09:50.262  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-06 19:09:50.262  3204  3279 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
09-06 19:09:50.262  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:09:50.262  3204  3279 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
09-06 19:09:50.262  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 19:09:50.262  3204  3279 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
09-06 19:09:50.262  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 19:09:50.262  3204  3279 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
09-06 19:09:50.262  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:50.262  3204  3279 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
09-06 19:09:50.262  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 19:09:50.262  3204  3279 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
09-06 19:09:50.262  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:50.262  3204  3279 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:50.262  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:50.262  3204  3279 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:50.262  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-06 19:09:50.262  3204  3279 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-06 19:09:50.262  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 19:09:50.262  3204  3279 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-06 19:09:50.262  3204  3279 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
09-06 19:09:50.262  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-06 19:09:50.262  1003  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:50.262  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-06 19:09:50.262  1003  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-06 19:09:50.262  3204  3279 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-06 19:09:50.262  1003  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:50.262  1003  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.262  1003  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.262  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,09-06 19:09:50.262  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-06 19:09:50.262  3204  3279 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-06 19:09:50.272  3204  3204 D HeadsetService: Received start request. Starting profile...
09-06 19:09:50.272  3204  3204 D HeadsetService: start()
09-06 19:09:50.272  3204  3204 D HeadsetStateMachine: make
,09-06 19:09:50.272  1003  1137 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:50.272  1003  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.272  1003  1137 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.272  1003  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.272  1003  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.272  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-06 19:09:50.272  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:09:50.272  3204  3279 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-06 19:09:50.272  1003  1003 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:50.272  3204  3204 E HeadsetStateMachine: # of Max HF connection is 2
09-06 19:09:50.272  1003  1003 I InputMethodManagerService: [BT Setting State] State =11
,09-06 19:09:50.282  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 19:09:50.282  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:50.282  1180  1180 D BluetoothTile:  getBluetoothState : 11
,09-06 19:09:50.282  1003  1030 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:09:50.282  1003  1512 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 19:09:50.292  1995  1995 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:09:50.292  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-06 19:09:50.292  4809  4809 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:50.292  1180  1715 D BluetoothTile:  handleUpdatestate:false name:null
09-06 19:09:50.292  1180  1715 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-06 19:09:50.292  1003  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:50.292  1003  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-06 19:09:50.292  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:50.292  1003  1479 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.292  1003  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.292  1003  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.292  1003  1481 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-06 19:09:50.292  1003  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.292  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-06 19:09:50.292  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 19:09:50.292  3204  3279 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-06 19:09:50.302  1003  1481 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.302  1003  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:50.302  1003  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-06 19:09:50.302  1003  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:50.302  1003  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.302  1003  1029 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:50.302  1003  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.302  1003  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.302  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:50.302  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService,
09-06 19:09:50.302  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService,
,09-06 19:09:50.302  3204  3279 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-06 19:09:50.312  1683  1683 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:09:50.312  1003  1137 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:50.312  1003  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.312  1003  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:50.312  1003  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.312  1003  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.312  1003  1733 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-06 19:09:50.312  1003  1733 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.312  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-06 19:09:50.312  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:50.312  3204  3279 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-06 19:09:50.312  1003  1733 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:50.312  1003  1733 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.312  1003  1733 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-06 19:09:50.312  3204  3204 I bluedroid: get_profile_interface handsfree
,09-06 19:09:50.312  1003  1496 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:50.312  1003  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.322  1003  1496 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:50.322  1003  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.322  1003  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.322  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService,
09-06 19:09:50.322  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService,
09-06 19:09:50.322  3204  3279 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-06 19:09:50.332  1003  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:50.332  1003  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.332  1003  1481 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.332  1003  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.332  1003  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.332  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:09:50.332  3204  3204 E DualScoManager: Dual Sco Manager already instantiated
09-06 19:09:50.332  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:09:50.332  3204  3279 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:50.332  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:50.332  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:50.332  3204  3279 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:50.332  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 19:09:50.332  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-06 19:09:50.332  3204  3279 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-06 19:09:50.332  3204  3204 I DualScoManager: Set HeadsetServiceHelper
09-06 19:09:50.332  3204  3204 D BluetoothAtMessage: createCMTIContentObservers
09-06 19:09:50.332  1003  1416 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-06 19:09:50.332  1003  1416 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:50.332  1003  1416 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:50.332  1003  1416 D SettingsProvider: selectionArgs: false
09-06 19:09:50.332  1003  1416 D SettingsProvider: selectionArgs: 1002
09-06 19:09:50.332  1003  1416 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:50.332  1003  1416 D SettingsProvider: ret = -1
,09-06 19:09:50.332  3204  7578 D HeadsetStateMachine: Enter Disconnected: -2
,09-06 19:09:50.332  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-06 19:09:50.332  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 19:09:50.332  3204  3279 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-06 19:09:50.332  3204  3279 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-06 19:09:50.332  4809  4809 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:09:50.332  3204  3204 D HeadsetService: mStartError = false
09-06 19:09:50.332  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
09-06 19:09:50.332  3204  3204 D A2dpService: Received start request. Starting profile...
09-06 19:09:50.332  3204  3204 D A2dpService: start()
09-06 19:09:50.332  3204  3204 I bluedroid: get_profile_interface avrcp
,09-06 19:09:50.342  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:50.342  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-06 19:09:50.342  3204  3204 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-06 19:09:50.342  3204  3204 D Avrcp   : Initialize Media Controller
09-06 19:09:50.342  3204  3204 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-06 19:09:50.342  3204  7578 D HeadsetStateMachine: Clear mHeadsetBrsf
09-06 19:09:50.342  3204  7578 D HeadsetStateMachine: map size, before remove : 0
09-06 19:09:50.342  3204  7578 D HeadsetStateMachine: map size, after remove: 0
,09-06 19:09:50.342  3204  3204 E Avrcp   : getActiveSessions
09-06 19:09:50.342  3204  3204 D Avrcp   : pick active media Controller
09-06 19:09:50.342  3204  3204 D Avrcp   : Get the active Media Controller 
,09-06 19:09:50.342  1003  1137 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-06 19:09:50.342  1003  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:50.342  1003  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:50.342  1003  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:50.342  1003  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:50.362  7580  7580 E Zygote  : MountEmulatedStorage()
,09-06 19:09:50.362  7580  7580 E Zygote  : v2
,09-06 19:09:50.362  7580  7580 I libpersona: KNOX_SDCARD checking this for 10055
09-06 19:09:50.362  7580  7580 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:50.362  7580  7580 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:50.362  1003  1137 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7580 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-06 19:09:50.362  7580  7580 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:50.372  7580  7580 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-06 19:09:50.372  3204  3204 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-06 19:09:50.372  3204  7579 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-06 19:09:50.372  3204  3204 D A2dpStateMachine: make
,09-06 19:09:50.382  3204  3204 I bluedroid: get_profile_interface a2dp
,09-06 19:09:50.382  3204  7588 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-06 19:09:50.382  3204  3204 E bt-btif : warning : media task started media_task_refcnt 1 
09-06 19:09:50.382  3204  3204 D A2dpService: mStartError = false
09-06 19:09:50.382  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
,09-06 19:09:50.382  3204  7587 D A2dpStateMachine: Enter Disconnected: -2
09-06 19:09:50.382  3204  3204 D HidService: Received start request. Starting profile...
09-06 19:09:50.382  3204  3204 D HidService: start()
09-06 19:09:50.382  3204  3204 I bluedroid: get_profile_interface hidhost
09-06 19:09:50.382  3204  3204 D HidService: setHidService(): set to: null
09-06 19:09:50.382  3204  3204 D HidService: mStartError = false
09-06 19:09:50.382  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
09-06 19:09:50.382  3204  3204 D HeadsetStateMachine: Try to query the phonestate on bind
,09-06 19:09:50.382  1455  1473 I Telecom : BluetoothPhoneService: queryPhoneState
,09-06 19:09:50.382  1455  1455 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-06 19:09:50.382  1455  1455 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-06 19:09:50.382  1455  1473 I Telecom : BluetoothPhoneService: Result of Message : true
,09-06 19:09:50.392  3204  3204 D HealthService: Received start request. Starting profile...
09-06 19:09:50.392  3204  3204 D HealthService: start()
,09-06 19:09:50.392  3204  7579 D BluetoothMediaBrowser: no now playing list
09-06 19:09:50.392  3204  7579 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
09-06 19:09:50.392  3204  3204 I bluedroid: get_profile_interface health
09-06 19:09:50.392  3204  3204 D HealthService: mStartError = false
09-06 19:09:50.392  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
,09-06 19:09:50.392  3204  3204 D PanService: Received start request. Starting profile...
,09-06 19:09:50.392  3204  3204 D PanService: start()
09-06 19:09:50.392  3204  3204 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 19:09:50.392  3204  3204 I bluedroid: get_profile_interface pan
09-06 19:09:50.392  3204  3204 D PanService: mStartError = false
09-06 19:09:50.392  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
09-06 19:09:50.392  3204  3204 D HeadsetStateMachine: Proxy object connected
09-06 19:09:50.392  3204  3204 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-06 19:09:50.392  3204  7578 D HeadsetStateMachine: Disconnected process message: 11
,09-06 19:09:50.392  3204  3204 D BluetoothMapService: Received start request. Starting profile...
09-06 19:09:50.392  3204  3204 D BluetoothMapService: start()
09-06 19:09:50.392  3204  3204 D BluetoothMapService: mStartError = false
09-06 19:09:50.392  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
09-06 19:09:50.392  3204  3204 D HeadsetPhoneState: sendDeviceDataStateChanged
09-06 19:09:50.392  3204  3204 D HeadsetPhoneState: Signal level : previous=0 curr=4
09-06 19:09:50.392  3204  7578 D HeadsetStateMachine: Disconnected process message: 18
,09-06 19:09:50.392  3204  3204 D SapService: Received start request. Starting profile...
09-06 19:09:50.392  3204  3204 D SapService: start()
09-06 19:09:50.392  3204  3204 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-06 19:09:50.392  3204  3204 I bluedroid: get_profile_interface sap
09-06 19:09:50.392  3204  3204 D SapService: mStartError = false
09-06 19:09:50.392  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
09-06 19:09:50.392  3204  3204 E BluetoothAdapterService(138181793): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-06 19:09:50.392  3204  3204 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-06 19:09:50.392  3204  3204 E BluetoothAdapterService(138181793): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-06 19:09:50.392  3204  3204 E BluetoothAdapterService(138181793): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-06 19:09:50.392  3204  7578 D HeadsetStateMachine: Disconnected process message: 10
,09-06 19:09:50.402  3204  7578 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 19:09:50.402  3204  7578 D HeadsetStateMachine: Disconnected process message: 11
,09-06 19:09:50.402  3204  3204 E BluetoothAdapterService(138181793): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-06 19:09:50.402  3204  3204 E BluetoothAdapterService(138181793): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-06 19:09:50.412  3204  3204 E BluetoothAdapterService(138181793): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
09-06 19:09:50.412  3204  3204 E BluetoothAdapterService(138181793): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-06 19:09:50.412  3204  3279 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
09-06 19:09:50.412  3204  3279 I bluedroid: enable
,09-06 19:09:50.422  3204  3282 E bt-btif : BTM_SEC_REG[4]: id 3
,09-06 19:09:50.422  3204  3282 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-06 19:09:50.422  3204  3282 E bt-btif : BTM_SEC_REG[12]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
09-06 19:09:50.422  3204  3282 E bt-btif : L2CAP - L2CA_Register() called for PSM: 0x0011
09-06 19:09:50.422  3204  3282 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
09-06 19:09:50.422  3204  3282 E BluetoothServiceJni: populateRssiValuesNative
09-06 19:09:50.422  3204  3282 I bluedroid: getModelRssiValues
09-06 19:09:50.422  3204  3282 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-06 19:09:50.422  3204  3282 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
09-06 19:09:50.422  3204  3282 D BluetoothAdapterProperties: Name is: Galaxy A3
,09-06 19:09:50.422  1003  1003 D SettingsProvider: name = bluetooth_name
,09-06 19:09:50.422  3204  3282 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 19:09:50.422  3204  3282 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:09:50.422  3204  3282 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:09:50.422  3204  3282 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
09-06 19:09:50.422  3204  3282 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
09-06 19:09:50.422  3204  3282 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,09-06 19:09:50.422  3204  3282 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-06 19:09:50.422  3204  3282 E bt-btif : JVenable fails
,09-06 19:09:50.432  3204  3282 D bte_conf: Device ID record 1 : primary
09-06 19:09:50.432  3204  3282 D bte_conf:   vendorId            = 0075
09-06 19:09:50.432  3204  3282 D bte_conf:   vendorIdSource      = 0001
09-06 19:09:50.432  3204  3282 D bte_conf:   product             = 0100
09-06 19:09:50.432  3204  3282 D bte_conf:   version             = 0200
09-06 19:09:50.432  3204  3282 D bte_conf:   clientExecutableURL = 
09-06 19:09:50.432  3204  3282 D bte_conf:   serviceDescription  = 
09-06 19:09:50.432  3204  3282 D bte_conf:   documentationURL    = 
09-06 19:09:50.432  3204  3282 D bte_conf: bte_load_did_conf no section named DID2.
09-06 19:09:50.432  7580  7580 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:50.432  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:50.432  7580  7580 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:50.432  3204  3282 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-06 19:09:50.432  3204  3282 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-06 19:09:50.432  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:50.432  3204  3279 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-06 19:09:50.432  3204  3279 D BluetoothAdapterProperties: ScanMode =  20
09-06 19:09:50.432  3204  3279 D BluetoothAdapterProperties: State =  11
,09-06 19:09:50.432  1003  1137 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-06 19:09:50.432  3204  3279 D BluetoothAdapterProperties: Setting state to 12
09-06 19:09:50.442  3204  3279 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-06 19:09:50.442  3204  3282 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 19:09:50.442  3204  3282 D BluetoothAdapterProperties: Scan Mode:21
,09-06 19:09:50.442  3204  3282 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:09:50.442  1003  1481 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-06 19:09:50.442  1003  1481 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:50.442  1003  1481 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:50.442  1003  1481 D SettingsProvider: selectionArgs: false
09-06 19:09:50.442  1003  1481 D SettingsProvider: selectionArgs: 1002
09-06 19:09:50.442  1003  1481 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:50.442  1003  1481 D SettingsProvider: ret = -1
,09-06 19:09:50.442  3204  3279 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:09:50.442  3204  3279 D BluetoothAdapterService: updateAdapterState state is 12
09-06 19:09:50.442  1003  1137 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:50.442  1003  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.442  1003  1137 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:09:50.442  1003  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.442  1003  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.452  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:50.452  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:50.452  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:50.452  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:50.452  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:50.452  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:50.452  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:50.452  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:09:50.452  3204  3204 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
09-06 19:09:50.452  3204  3204 I BluetoothPbapService: Handler(): got msg=1
,09-06 19:09:50.452  1467  1493 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:09:50.452  3204  3279 D BluetoothAdapterService: Autoconnection is available 
09-06 19:09:50.452  3204  3279 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-06 19:09:50.452  3204  3279 D BluetoothAdapterService: starting service from this receiver
,09-06 19:09:50.452  1467  1493 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:09:50.452  1003  1496 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:50.452  1003  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.452  1003  1496 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.452  1003  1223 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy,
09-06 19:09:50.462  1003  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.462  1003  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.462  3204  3279 I BluetoothAdapterState: Entering On State from state = 11
,09-06 19:09:50.462  4809  4817 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:09:50.462  3204  7601 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-06 19:09:50.462  6822  6822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:09:50.462  4809  4817 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:50.462  1003  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 19:09:50.462  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.462  1003  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.462  1003  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.462  1003  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.472  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:50.472  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:50.472  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:50.472  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:50.472  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:50.472  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:50.472  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:50.472  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:09:50.472  4809  4819 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:50.472  1003  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 19:09:50.472  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:09:50.472  3204  7601 D BluetoothSocket: bindListen(): myUserId = 0
09-06 19:09:50.472  3204  7601 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:09:50.472  7580  7580 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-06 19:09:50.472  1003  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.472  1003  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.472  1003  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.472  4809  4819 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:09:50.472  6822  6953 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:50.472  6822  6953 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:50.482  3204  7601 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
09-06 19:09:50.482  3204  7601 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:09:50.482  3204  7601 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:09:50.482  3204  7601 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1b92f922
09-06 19:09:50.482  3204  7601 D BluetoothSocket: channel: 19
09-06 19:09:50.482  3204  7601 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
09-06 19:09:50.482  4809  4809 D BluetoothA2dp: Proxy object connected
09-06 19:09:50.482  4809  4809 D A2dpProfile: Bluetooth service connected
,09-06 19:09:50.482  6822  6822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:09:50.482  4809  4809 D HeadsetProfile: Bluetooth service connected
09-06 19:09:50.482  1455  1466 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:50.482  1003  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:09:50.482  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:09:50.482  1003  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:50.482  1003  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.482  1003  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.482  1455  1466 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:09:50.482  1455  1466 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:50.492  1003  1047 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:09:50.492  1003  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:09:50.492  1003  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:50.492  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-06 19:09:50.492  1003  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-06 19:09:50.492  1455  1466 E BluetoothHeadset: BluetoothHeadset service is binded
09-06 19:09:50.492  4809  4819 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-06 19:09:50.492  1003  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-06 19:09:50.492  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.492  1003  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:50.492  1003  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.492  1003  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.492  4809  4809 D BluetoothInputDevice: Proxy object connected
09-06 19:09:50.492  4809  4809 D HidProfile: Bluetooth service connected
,09-06 19:09:50.492  1483  3314 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:50.502  1003  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 19:09:50.502  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:09:50.502  1003  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.502  1003  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:50.502  1003  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
09-06 19:09:50.502  1483  3314 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:09:50.502  4809  4817 D Bluetoothsap: onBluetoothStateChange: up=true,
09-06 19:09:50.502  4809  4817 D Bluetoothsap: Binding service...
,09-06 19:09:50.502  4809  4817 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-06 19:09:50.502  1003  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,09-06 19:09:50.502  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.502  1003  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.502  1003  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.502  1003  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.502  4809  4817 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-06 19:09:50.502  4809  4819 D BluetoothMap: onBluetoothStateChange: up=true
09-06 19:09:50.502  7580  7580 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-06 19:09:50.502  7580  7580 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-06 19:09:50.502  7580  7580 D UserAnalysis: Create SecureDbHelper
,09-06 19:09:50.512  4809  4809 D Bluetoothsap: BluetoothSAP Proxy object connected
09-06 19:09:50.512  4809  4809 D SapProfile: Bluetooth service connected
09-06 19:09:50.512  4809  4809 D Bluetoothsap: getConnectedDevices()
,09-06 19:09:50.512  1003  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-06 19:09:50.512  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.512  1003  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.512  1003  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.512  1003  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.512  4809  4809 D BluetoothMap: Proxy object connected
,09-06 19:09:50.512  1003  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-06 19:09:50.512  4809  4809 D MapProfile: Bluetooth service connected
09-06 19:09:50.512  1003  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:09:50.512  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:09:50.512  1003  1047 E BluetoothHeadset: BluetoothHeadset service is binded
09-06 19:09:50.512  4809  4809 D BluetoothMap: getConnectedDevices()
,09-06 19:09:50.512  1483  1500 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:50.512  1483  1500 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:09:50.512  3204  3357 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:50.512  3204  3357 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:50.512  7580  7580 D IntelligenceServiceApplication: onCreate()
09-06 19:09:50.512  1752  1768 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:50.512  1752  1768 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:09:50.512  4809  7523 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:50.512  4809  7523 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:50.512  4809  4819 D BluetoothPbap: onBluetoothStateChange: up=true
,09-06 19:09:50.512  1003  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-06 19:09:50.512  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.512  1003  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.512  1003  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.512  1003  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.522  1003  1047 D BluetoothPan: Binding service...
,09-06 19:09:50.522  1003  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-06 19:09:50.522  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-06 19:09:50.522  1455  1466 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:09:50.522  1455  1466 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:09:50.522  1003  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:50.522  1003  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:09:50.522  1003  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:09:50.522  1003  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:50.522  4809  4809 D BluetoothPbap: Proxy object connected
09-06 19:09:50.522  4809  4809 D PbapServerProfile: Bluetooth service connected
,09-06 19:09:50.522  1003  1518 I ActivityManager: Killing 7114:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,09-06 19:09:50.522  7580  7580 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-06 19:09:50.522  1003  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 19:09:50.522  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.532  1003  1137 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-06 19:09:50.532  1003  1003 D BluetoothA2dp: Proxy object connected
,09-06 19:09:50.532  7580  7580 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-06 19:09:50.532  1003  1003 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 19:09:50.542  7580  7580 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-06 19:09:50.632  1003  1047 E BluetoothManagerService: Unable to call onBluetoothStateChange() on callback #20
09-06 19:09:50.632  1003  1047 E BluetoothManagerService: android.os.DeadObjectException
09-06 19:09:50.632  1003  1047 E BluetoothManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
09-06 19:09:50.632  1003  1047 E BluetoothManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
09-06 19:09:50.632  1003  1047 E BluetoothManagerService: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub$Proxy.onBluetoothStateChange(IBluetoothStateChangeCallback.java:84)
09-06 19:09:50.632  1003  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.sendBluetoothStateCallback(BluetoothManagerService.java:1053)
09-06 19:09:50.632  1003  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:2007)
09-06 19:09:50.632  1003  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.access$3900(BluetoothManagerService.java:105)
09-06 19:09:50.632  1003  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1576)
09-06 19:09:50.632  1003  1047 E BluetoothManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:50.632  1003  1047 E BluetoothManagerService: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:50.632  1003  1047 E BluetoothManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-06 19:09:50.632  1003  1047 E BluetoothManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-06 19:09:50.632  1683  1775 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:09:50.632  1683  1775 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:50.632  1180  4941 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:09:50.632  1180  4941 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:50.642  1455  1473 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:50.642  1003  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 19:09:50.642  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:09:50.642  1003  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:50.642  1003  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:50.642  1003  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.642  1455  1473 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:09:50.642  4809  7523 D BluetoothPan: Binding service...
,09-06 19:09:50.652  1003  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-06 19:09:50.652  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.652  1003  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:50.652  1003  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.652  1003  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.652  4809  4809 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 19:09:50.652  3204  3339 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:09:50.652  4809  4809 D PanProfile: Bluetooth service connected
,09-06 19:09:50.652  3204  3339 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:50.652  1003  1047 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 19:09:50.652  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.652  1003  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.652  1003  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.652  1003  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.652  1003  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-06 19:09:50.662  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-06 19:09:50.662  3204  3204 D BluetoothA2dp: Proxy object connected
09-06 19:09:50.662  3204  3204 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-06 19:09:50.662  1003  1003 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:50.662  1003  1003 I InputMethodManagerService: [BT Setting State] State =12
,09-06 19:09:50.662  1003  1003 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 19:09:50.672  1180  1180 D BluetoothTile:  onBluetoothStateChange:
09-06 19:09:50.672  1455  1455 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3bd867ac, true
,09-06 19:09:50.672  1455  1455 D BluetoothHeadset: registerMessageListener
,09-06 19:09:50.672  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 19:09:50.672  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:50.672  1180  1180 D BluetoothTile:  getBluetoothState : 12
,09-06 19:09:50.672  1180  1715 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:09:50.672  1180  1715 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:09:50.682  1180  1715 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:09:50.682  1995  1995 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:09:50.682  4809  4809 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:50.692  1003  1496 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:09:50.692  3204  3217 D HeadsetService: registerMessageListener
,09-06 19:09:50.692  1003  1523 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-06 19:09:50.692  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:09:50.692  3204  3217 D HeadsetService: registerMessageListener
09-06 19:09:50.692  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:50.692  3204  7578 D HeadsetStateMachine: Disconnected process message: 70
,09-06 19:09:50.692  3204  7578 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@17c89fb3
,09-06 19:09:50.702  1455  1455 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,09-06 19:09:50.702  1455  1455 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-06 19:09:50.702  4809  4809 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-06 19:09:50.702  4809  4809 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-06 19:09:50.702  4809  4809 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,09-06 19:09:50.702  4809  4809 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-06 19:09:50.702  3204  7606 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-06 19:09:50.702  1455  1455 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-06 19:09:50.702  1455  1455 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-06 19:09:50.702  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:50.702  1455  1455 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-06 19:09:50.702  3204  7578 D HeadsetStateMachine: Disconnected process message: 9
,09-06 19:09:50.702  3204  7578 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-06 19:09:50.712  3204  7606 D BluetoothSocket: bindListen(): myUserId = 0
09-06 19:09:50.712  3204  7606 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:09:50.712  3204  7606 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
09-06 19:09:50.712  3204  7606 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:09:50.712  3204  7606 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:09:50.712  3204  7606 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3886b970
,09-06 19:09:50.712  3204  7606 D BluetoothSocket: channel: 5
,09-06 19:09:50.712   283   283 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-06 19:09:50.712   283   283 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-06 19:09:50.712   283   283 V voice   : voice_set_parameters: exit with code(-2)
09-06 19:09:50.712   283   283 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-06 19:09:50.712   283   283 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-06 19:09:50.712   283   283 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-06 19:09:50.712   283   283 V audio_hw_primary: adev_set_parameters: exit
09-06 19:09:50.712  3204  7578 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-06 19:09:50.712  4809  4809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:09:50.712  1003  1512 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-06 19:09:50.712  1003  1512 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.712  1003  1512 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:50.722  1003  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:50.722  1003  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:09:50.722  1683  1683 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:09:50.732  4809  4809 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:09:50.732  4809  4809 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:09:50.732  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:50.732  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-06 19:09:50.742  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
,09-06 19:09:50.742  3204  3204 D BtConfig.SecureMode: isSecureModeOn:false
,09-06 19:09:50.742  1003  1223 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:50.742  1003  1223 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.742  1003  1223 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.742  1003  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.742  1003  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.752  1003  1523 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-06 19:09:50.752  1003  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:50.752  1003  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:50.752  1003  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:50.752  1003  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:50.762  7609  7609 E Zygote  : MountEmulatedStorage()
09-06 19:09:50.762  1003  1523 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7609 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-06 19:09:50.762  7609  7609 E Zygote  : v2
09-06 19:09:50.762  7609  7609 I libpersona: KNOX_SDCARD checking this for 10105
09-06 19:09:50.762  7609  7609 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:50.762  7609  7609 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:09:50.762  1003  1029 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-06 19:09:50.772  7609  7609 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:09:50.772  7609  7609 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:09:50.772  3204  7617 D BluetoothSocket: bindListen(): myUserId = 0
,09-06 19:09:50.772  3204  7617 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:09:50.782  3204  7617 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
09-06 19:09:50.782  3204  7617 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:09:50.782  3204  7617 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:09:50.782  3204  7617 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25f5fc9c
,09-06 19:09:50.782  3204  7617 D BluetoothSocket: channel: 12
09-06 19:09:50.782  3204  7617 I BtOppRfcommListener: Accept thread started.
,09-06 19:09:50.792  7609  7609 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:50.792  7609  7609 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:50.882   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-06 19:09:50.882   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:09:50.882  7609  7630 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-06 19:09:50.892   257   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-06 19:09:50.892   257   528 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:09:50.892  7609  7630 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-06 19:09:51.042  7609  7609 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:51.042  7609  7609 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:51.042  7609  7609 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:09:51.042  7609  7609 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:09:51.042  7609  7609 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 19:09:51.042  7609  7609 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-06 19:09:51.042  7609  7609 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-06 19:09:51.042  7609  7609 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-06 19:09:51.042  7609  7609 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:09:51.042  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 19:09:51.042  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:09:51.042  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:51.042  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:51.042  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:51.042  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:51.042  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:51.042  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:51.042  7609  7609 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:51.042  7609  7609 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:51.042  7609  7609 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:51.042  7609  7609 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:51.042  7609  7609 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:51.042  7609  7609 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:51.042  7609  7609 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:51.042  7609  7609 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:51.042  7609  7609 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:51.042  7609  7609 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:51.042  7609  7609 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-06 19:09:51.052  7609  7609 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-06 19:09:51.052  7609  7609 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-06 19:09:51.052  7609  7609 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.q.e.b(PG:170)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-06 19:09:51.052  7609  7609 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.q.k.d(PG:583)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.q.e.b(PG:170)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-06 19:09:51.052  7609  7609 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:51.052  7609  7609 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:51.052  7609  76,09 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:51.052  7609  7609 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:51.052  7609  7609 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-06 19:09:51.052  1003  1512 I ActivityManager: Killing 7216:com.sec.pcw.device/1000 (adj 15): empty #21
,09-06 19:09:51.112  7609  7629 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-06 19:09:51.132  1003  1518 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:51.132  1003  1518 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:51.132  1003  1518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:51.132  1003  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-06 19:09:51.212  1003  1043 W ActivityManager: mDVFSHelper.release()
,09-06 19:09:52.912   291   291 E SMD     : DCD OFF,
,09-06 19:09:53.252  6822  7033 D BluetoothAdapter: disable(),
,09-06 19:09:53.252  1003  1733 D SettingsProvider: name = bluetooth_on,
,09-06 19:09:53.272  3204  3279 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF,
09-06 19:09:53.272  3204  3279 D BluetoothAdapterProperties: Setting state to 13
09-06 19:09:53.272  1003  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:53.272  3204  3279 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 19:09:53.272  1003  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0,
09-06 19:09:53.272  3204  3279 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:09:53.272  3204  3279 D BluetoothAdapterService: updateAdapterState state is 13
09-06 19:09:53.272  1003  1479 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:53.272  1003  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:53.272  1003  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:09:53.272  3204  3204 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-06 19:09:53.272  3204  3279 D BluetoothAdapterService: Autoconnection is available 
09-06 19:09:53.272  3204  3279 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-06 19:09:53.272  3204  3279 D BluetoothAdapterService: terminating service from this receiver
,09-06 19:09:53.282  3204  3204 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@195c46a5, channel: 19, state: LISTENING
,09-06 19:09:53.282  3204  3204 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@195c46a5, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1b92f922, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@326e8a7amSocket: android.net.LocalSocket@3b9e522b impl:android.net.LocalSocketImpl@17b44688 fd:FileDescriptor[80]
09-06 19:09:53.282  3204  3204 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3b9e522b impl:android.net.LocalSocketImpl@17b44688 fd:FileDescriptor[80],
,09-06 19:09:53.282  1003  1003 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
09-06 19:09:53.282  1003  1003 I InputMethodManagerService: [BT Setting State] State =13
,09-06 19:09:53.302  1180  1180 D BluetoothTile:  onBluetoothStateChange:
,09-06 19:09:53.302  1995  1995 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:09:53.302  4809  4809 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:53.302  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 19:09:53.302  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:53.302  1180  1180 D BluetoothTile:  getBluetoothState : 13
,09-06 19:09:53.302  1180  1715 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:09:53.302  1180  1715 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:09:53.302  1180  1715 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-06 19:09:53.312  1003  3354 D SSRM:n  : SIOP:: AP = 350
,09-06 19:09:53.312  6822  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:53.312  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:53.312  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:53.312  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:53.312  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:53.312  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:53.312  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:53.312  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:53.312  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:09:53.312  6822  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:53.312  6822  6822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:09:53.312  1003  1479 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:09:53.312  1003  1512 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-06 19:09:53.312  1003  1223 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 19:09:53.312  1003  1512 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:53.312  1003  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:53.312  1003  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:53.312  6822  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:09:53.312  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:53.312  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:53.312  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:53.312  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:53.312  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:53.312  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:53.312  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:53.312  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:09:53.322  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-06 19:09:53.322  3204  3279 D BluetoothAdapterProperties: onBluetoothDisable()
09-06 19:09:53.322  3204  3279 D BluetoothAdapterProperties: mDiscovering is false
,09-06 19:09:53.322  1003  1496 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-06 19:09:53.322  3204  3279 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-06 19:09:53.322  6822  6822 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:53.322  6822  6822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:09:53.322  4809  4809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:09:53.332  3204  3282 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-06 19:09:53.332  3204  3282 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:09:53.332  1003  1518 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-06 19:09:53.332  1003  1518 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:09:53.332  1003  1518 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:53.332  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:53.332  1003  1518 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:53.332  1003  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:09:53.332  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:53.342  3204  3279 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-06 19:09:53.342  3204  3279 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-06 19:09:53.342  3204  3204 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1a6fa821, channel: 5, state: LISTENING
09-06 19:09:53.342  3204  3204 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1a6fa821, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3886b970, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@314ad446mSocket: android.net.LocalSocket@3dade607 impl:android.net.LocalSocketImpl@2f8b4334 fd:FileDescriptor[82]
09-06 19:09:53.342  3204  3204 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3dade607 impl:android.net.LocalSocketImpl@2f8b4334 fd:FileDescriptor[82]
,09-06 19:09:53.342  3204  3204 I BtOppRfcommListener: stopping Accept Thread
09-06 19:09:53.342  3204  3204 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1afda55d, channel: 12, state: LISTENING
09-06 19:09:53.342  3204  3204 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1afda55d, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25f5fc9c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@94feed2mSocket: android.net.LocalSocket@1a38dba3 impl:android.net.LocalSocketImpl@335ea0 fd:FileDescriptor[86]
09-06 19:09:53.342  3204  3204 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1a38dba3 impl:android.net.LocalSocketImpl@335ea0 fd:FileDescriptor[86]
09-06 19:09:53.342  3204  7617 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 19:09:53.342  3204  7617 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-06 19:09:53.342  3204  3279 E bt-btif : BTA got event 0x1a1c
,09-06 19:09:53.342  3204  3279 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-06 19:09:53.342  3204  3283 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,09-06 19:09:53.342  4809  4809 D BluetoothPbap: Proxy object disconnected
,09-06 19:09:53.342  4809  4809 D PbapServerProfile: Bluetooth service disconnected
,09-06 19:09:53.352  1683  1683 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:09:53.352  3204  3204 V BluetoothOppManager: cleanUp...
,09-06 19:09:53.352  3204  3283 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:09:53.352  3204  3283 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:09:53.352  3204  3283 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:09:53.352  3204  3283 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:09:53.352  3204  3283 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:09:53.352  3204  3283 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-06 19:09:53.352  4809  4809 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:09:53.362  4809  4809 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:09:53.362  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:53.362  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-06 19:09:53.452  1003  3371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-06 19:09:53.542  3204  3279 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-06 19:09:53.542  3204  3279 D BtConfig.SecureMode: isSecureModeOn:false
,09-06 19:09:53.542  3204  3279 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-06 19:09:53.542  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
,09-06 19:09:53.542  3204  3279 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
09-06 19:09:53.542  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,09-06 19:09:53.552  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-06 19:09:53.552  3204  3279 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-06 19:09:53.552  1003  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:53.552  1003  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-06 19:09:53.552  1003  1481 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:09:53.552  1003  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:53.552  1003  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:53.552  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService,
09-06 19:09:53.552  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService,
,09-06 19:09:53.562  3204  3279 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-06 19:09:53.562  1003  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:53.562  1003  1030 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:53.562  1003  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-06 19:09:53.562  1003  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:53.562  1003  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:53.562  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,09-06 19:09:53.562  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:09:53.562  3204  3279 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-06 19:09:53.562  3204  3204 D HeadsetService: Received stop request...Stopping profile...
09-06 19:09:53.562  1003  1137 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:53.562  1003  1137 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:53.562  1003  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-06 19:09:53.562  1003  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:53.562  1003  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:53.562  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
09-06 19:09:53.562  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,09-06 19:09:53.562  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 19:09:53.562  3204  3279 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-06 19:09:53.562  1003  1003 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-06 19:09:53.572  1003  1512 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:53.572  1003  1512 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-06 19:09:53.572  1003  1512 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:53.572  1003  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:53.572  1003  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:09:53.572  3204  3204 D A2dpService: Received stop request...Stopping profile...
,09-06 19:09:53.572  3204  7587 D A2dpStateMachine: Exit Disconnected: -1
,09-06 19:09:53.572  4809  4809 D HeadsetProfile: Bluetooth service disconnected
,09-06 19:09:53.572  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-06 19:09:53.572  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 19:09:53.572  3204  3279 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-06 19:09:53.572  1003  1223 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:53.572  1003  1223 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:09:53.572  1003  1223 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:53.572  1003  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:53.572  1003  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:53.582  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-06 19:09:53.582  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:53.582  3204  3279 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-06 19:09:53.582  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
,09-06 19:09:53.582  1003  1003 D BluetoothA2dp: Proxy object disconnected
,09-06 19:09:53.582  1003  1003 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-06 19:09:53.582  1003  1416 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:53.582  4809  4809 D BluetoothA2dp: Proxy object disconnected
09-06 19:09:53.582  4809  4809 D A2dpProfile: Bluetooth service disconnected
09-06 19:09:53.582  1003  1416 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:09:53.582  3204  3204 D HidService: Received stop request...Stopping profile...
,09-06 19:09:53.582  3204  3204 D HidService: Stopping Bluetooth HidService
09-06 19:09:53.582  3204  3204 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-06 19:09:53.582  3204  3204 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-06 19:09:53.582  3204  3204 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-06 19:09:53.582  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
,09-06 19:09:53.582  1003  1416 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:53.582  1003  1416 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:53.582  1003  1416 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:53.592  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-06 19:09:53.592  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 19:09:53.592  1003  1512 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:53.592  3204  3279 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-06 19:09:53.592  1003  1512 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-06 19:09:53.592  1003  1512 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:53.592  1003  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:53.592  1003  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:53.592  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService,
09-06 19:09:53.592  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:53.592  3204  3279 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:53.592  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:53.592  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:53.592  3204  3279 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,09-06 19:09:53.592  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 19:09:53.592  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-06 19:09:53.592  3204  3279 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-06 19:09:53.592  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-06 19:09:53.592  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 19:09:53.592  3204  3279 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,09-06 19:09:53.592  3204  3279 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-06 19:09:53.592  4809  4809 D BluetoothInputDevice: Proxy object disconnected
09-06 19:09:53.592  4809  4809 D HidProfile: Bluetooth service disconnected
,09-06 19:09:53.592  3204  3204 E BluetoothAdapterService(138181793): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-06 19:09:53.592  3204  3204 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:09:53.592  3204  3204 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-06 19:09:53.592  3204  3204 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-06 19:09:53.592  3204  3204 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-06 19:09:53.592  3204  3204 D HealthService: Received stop request...Stopping profile...
,09-06 19:09:53.592  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
,09-06 19:09:53.602  3204  3204 D PanService: Received stop request...Stopping profile...
,09-06 19:09:53.602  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
,09-06 19:09:53.602  1003  1003 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-06 19:09:53.602  3204  3204 E BluetoothAdapterService(138181793): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-06 19:09:53.602  3204  3204 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:09:53.602  3204  3204 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-06 19:09:53.602  3204  3204 D BluetoothA2dp: Proxy object disconnected
09-06 19:09:53.602  3204  3204 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,09-06 19:09:53.602  3204  7588 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-06 19:09:53.602  3204  3204 I GKI_LINUX: GKI_exit_task 2 done
09-06 19:09:53.602  3204  3204 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-06 19:09:53.602  3204  3204 E BluetoothAdapterService(138181793): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-06 19:09:53.602  3204  3204 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-06 19:09:53.602  3204  3204 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:53.602  3204  3204 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-06 19:09:53.602  4809  4809 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 19:09:53.602  4809  4809 D PanProfile: Bluetooth service disconnected
,09-06 19:09:53.602  3204  3204 D BluetoothMapService: Received stop request...Stopping profile...
,09-06 19:09:53.602  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
,09-06 19:09:53.612  3204  3204 D SapService: Received stop request...Stopping profile...
09-06 19:09:53.612  3204  3204 D SapService: Stopping Bluetooth SapService
09-06 19:09:53.612  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
,09-06 19:09:53.612  4809  4809 D BluetoothMap: Proxy object disconnected
09-06 19:09:53.612  4809  4809 D MapProfile: Bluetooth service disconnected
,09-06 19:09:53.612  4809  4809 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-06 19:09:53.612  4809  4809 D SapProfile: Bluetooth service disconnected
,09-06 19:09:53.612  3204  3204 E BluetoothAdapterService(138181793): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
,09-06 19:09:53.612  3204  3204 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,09-06 19:09:53.612  3204  3204 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-06 19:09:53.612  3204  3204 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:53.612  3204  3204 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 19:09:53.612  3204  3204 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-06 19:09:53.612  3204  3204 E BluetoothAdapterService(138181793): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
,09-06 19:09:53.612  3204  3204 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,09-06 19:09:53.612  3204  3204 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:53.612  3204  3204 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-06 19:09:53.612  3204  3204 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-06 19:09:53.612  3204  3204 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-06 19:09:53.622  3204  3204 E BluetoothAdapterService(138181793): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,09-06 19:09:53.622  3204  3204 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,09-06 19:09:53.622  3204  3204 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 19:09:53.622  3204  3204 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-06 19:09:53.622  3204  3204 E BluetoothAdapterService(138181793): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-06 19:09:53.622  3204  3204 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,09-06 19:09:53.622  3204  3204 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-06 19:09:53.622  3204  3204 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-06 19:09:53.622  3204  3279 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,09-06 19:09:53.622  3204  3279 D BluetoothAdapterProperties: Setting state to 10
09-06 19:09:53.622  3204  3279 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,09-06 19:09:53.622  3204  3279 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:09:53.622  3204  3279 D BluetoothAdapterService: updateAdapterState state is 10
,09-06 19:09:53.622  3204  3279 D BluetoothAdapterService: Autoconnection is available 
,09-06 19:09:53.622  3204  3279 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-06 19:09:53.622  3204  3279 I BluetoothAdapterState: Entering OffState
,09-06 19:09:53.622  1467  1484 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:53.622  1467  1484 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:53.632  4809  7523 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:09:53.632  6822  6836 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:53.632  6822  6836 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:53.632  6822  6836 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-06 19:09:53.632  6822  6836 D BluetoothLeAdvertiser: Exit stop advertising
,09-06 19:09:53.632  6822  6836 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-06 19:09:53.632  6822  6836 D BluetoothLeScanner: Exiting stopAllScan
,09-06 19:09:53.632  4809  4819 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-06 19:09:53.632  4809  7523 D Bluetoothsap: onBluetoothStateChange: up=false
,09-06 19:09:53.632  4809  7523 D Bluetoothsap: Unbinding service...
,09-06 19:09:53.632  4809  4817 D BluetoothMap: onBluetoothStateChange: up=false
,09-06 19:09:53.632  1483  1497 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:53.632  1483  1497 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:53.642  3204  7604 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:53.642  3204  7604 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:53.642  1752  1951 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:53.642  1752  1951 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:53.642  4809  4819 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:53.642  4809  4819 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:53.642  4809  7523 D BluetoothPbap: onBluetoothStateChange: up=false
,09-06 19:09:53.642  7609  7621 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:53.642  7609  7621 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:53.642  1455  7602 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:53.642  1455  7602 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:53.642  1003  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:53.642  1003  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:09:53.642  1003  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:09:53.642  1683  1700 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:53.642  1683  1700 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:53.652  1180  4941 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:53.652  1180  4941 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:53.652  3204  3217 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:09:53.652  1003  1003 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:53.652  1003  1003 I InputMethodManagerService: [BT Setting State] State =10
09-06 19:09:53.652  1003  1003 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 19:09:53.652  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:,
09-06 19:09:53.662  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:53.662  1180  1180 D BluetoothTile:  getBluetoothState : 10
,09-06 19:09:53.662  1995  1995 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:09:53.662  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:53.662  1003  1223 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:09:53.662  4809  4809 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:53.662  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:53.662  1003  1518 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 19:09:53.672  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 19:09:53.672  4809  4809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:09:53.672  1003  1481 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-06 19:09:53.672  1003  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:09:53.672  1003  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:53.672  1003  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:53.672  1003  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:09:53.682  1683  1683 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:09:53.682  4809  4809 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:09:53.682  4809  4809 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:09:53.682  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:53.682  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-06 19:09:54.912   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:09:55.922   291   291 E SMD     : DCD OFF
,09-06 19:09:55.922   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:09:56.272  6822  7033 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:09:56.272  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:56.922   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:09:57.012  1003  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-06 19:09:57.012  1003  1479 D BatteryService: level:98, scale:100, status:2, health:2, present:true, voltage: 4263, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-06 19:09:57.012  1003  1479 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-06 19:09:57.012  1003  1479 D BatteryService: stay LED for charging
,09-06 19:09:57.012  1003  1003 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-06 19:09:57.012  1003  1003 I MotionRecognitionService: Plugged
,09-06 19:09:57.012  1003  1003 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 19:09:57.022  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-06 19:09:57.022  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-06 19:09:57.022  1436  1436 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-06 19:09:57.022  1436  1436 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 98
,09-06 19:09:57.042  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:98 status:2 health:2
09-06 19:09:57.042  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:98 status:2 health:2
,09-06 19:09:57.042  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:98 status:2 health:2
09-06 19:09:57.042  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-06 19:09:57.042  1180  1180 D SViewCoverView: level :98 plugged : 2
,09-06 19:09:57.922   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:09:58.922   291   291 E SMD     : DCD OFF,
,09-06 19:09:58.922   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:09:59.272  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:09:59.272  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@14128e62 added. We now have 6 listener(s),
09-06 19:09:59.272  6822  7033 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:09:59.272  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
,09-06 19:09:59.272  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3514abf3 added. We now have 7 listener(s)
09-06 19:09:59.272  6822  7033 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:09:59.272  6822  7033 I System.out: IsBluetoothEnabled,
09-06 19:09:59.272  6822  7033 D BluetoothAdapter: disable()
09-06 19:09:59.282  1003  1481 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-06 19:09:59.282  6822  7033 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:59.282  6822  7033 D BluetoothAdapter: enable()
,09-06 19:09:59.292  1003  1733 W ActivityManager: Permission Denial: getCurrentUser() from pid=6822, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-06 19:09:59.292  1003  1733 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-06 19:09:59.292  1003  1733 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6822, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:09:59.292  1003  1733 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 19:09:59.292  1003  1733 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-06 19:09:59.292  1003  1733 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-06 19:09:59.292  1003  1733 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-06 19:09:59.292  1003  1733 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 19:09:59.292  1003  1733 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-06 19:09:59.292  1003  1733 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:09:59.292  1003  1733 D SettingsProvider: name = bluetooth_on,
,09-06 19:09:59.302  1003  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:09:59.302  1003  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:09:59.302  1003  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-06 19:09:59.302  3204  3279 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-06 19:09:59.302  3204  3279 D BluetoothAdapterProperties: Setting state to 11
,09-06 19:09:59.312  3204  3279 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-06 19:09:59.312  3204  3279 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:09:59.312  3204  3279 D BluetoothAdapterService: updateAdapterState state is 11
09-06 19:09:59.312  3204  3279 D BluetoothAdapterService: Autoconnection is available 
,09-06 19:09:59.312  3204  3279 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
09-06 19:09:59.312  3204  3279 D BtConfig.SecureMode: isSecureModeOn:false
09-06 19:09:59.312  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-06 19:09:59.312  3204  3279 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
09-06 19:09:59.312  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-06 19:09:59.312  3204  3279 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
09-06 19:09:59.312  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-06 19:09:59.312  3204  3279 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
09-06 19:09:59.312  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:09:59.312  3204  3279 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
09-06 19:09:59.312  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 19:09:59.312  3204  3279 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
09-06 19:09:59.312  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 19:09:59.312  3204  3279 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
09-06 19:09:59.312  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:59.312  3204  3279 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
09-06 19:09:59.312  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 19:09:59.312  3204  3279 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
09-06 19:09:59.312  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:59.312  3204  3279 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:59.312  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:59.312  3204  3279 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:59.312  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-06 19:09:59.312  3204  3279 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-06 19:09:59.312  1003  1496 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:59.312  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 19:09:59.312  1003  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-06 19:09:59.312  3204  3279 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-06 19:09:59.312  3204  3279 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
09-06 19:09:59.312  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-06 19:09:59.312  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hf,p.HeadsetService
09-06 19:09:59.312  3204  3279 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-06 19:09:59.312  1003  1496 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.312  1003  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.312  1003  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.312  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-06 19:09:59.312  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-06 19:09:59.312  3204  3279 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-06 19:09:59.312  1003  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:59.312  1003  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.312  1003  1481 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.312  1003  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.312  1003  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.312  3204  3204 D HeadsetService: Received start request. Starting profile...
,09-06 19:09:59.312  3204  3204 D HeadsetService: start()
09-06 19:09:59.322  3204  3204 D HeadsetStateMachine: make
,09-06 19:09:59.322  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-06 19:09:59.322  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:09:59.322  3204  3279 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-06 19:09:59.322  1003  1003 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:59.322  1003  1003 I InputMethodManagerService: [BT Setting State] State =11
,09-06 19:09:59.322  3204  3204 E HeadsetStateMachine: # of Max HF connection is 2
,09-06 19:09:59.332  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 19:09:59.332  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:59.332  1180  1180 D BluetoothTile:  getBluetoothState : 11
,09-06 19:09:59.342  1180  1715 D BluetoothTile:  handleUpdatestate:false name:null
09-06 19:09:59.342  1180  1715 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-06 19:09:59.342  4809  4809 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:59.342  1003  1496 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:09:59.342  1995  1995 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
09-06 19:09:59.342  1003  1523 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 19:09:59.342  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:59.342  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 19:09:59.342  1003  1223 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:59.342  1003  1223 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.342  1003  1223 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.342  1003  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.342  1003  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.342  1003  1137 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-06 19:09:59.342  1003  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.352  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-06 19:09:59.352  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 19:09:59.352  3204  3279 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-06 19:09:59.352  1003  1137 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.352  1003  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.352  1003  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-06 19:09:59.352  1003  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:59.352  1003  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.352  1003  1029 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:59.352  1003  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.352  1003  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.352  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,09-06 19:09:59.352  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 19:09:59.352  3204  3279 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-06 19:09:59.362  1683  1683 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:09:59.362  1003  1479 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-06 19:09:59.362  1003  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.362  1003  1479 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.362  1003  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:59.362  1003  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-06 19:09:59.362  1003  1523 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:59.362  1003  1523 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.362  1003  1523 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:59.362  1003  1523 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.362  1003  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.372  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-06 19:09:59.372  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:59.372  3204  3279 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-06 19:09:59.372  3204  3204 I bluedroid: get_profile_interface handsfree
,09-06 19:09:59.372  1003  1518 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:59.372  1003  1518 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.372  1003  1518 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:59.372  1003  1518 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.372  1003  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.382  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,09-06 19:09:59.382  4809  4809 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:09:59.382  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-06 19:09:59.382  3204  3279 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-06 19:09:59.382  1003  1512 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:59.382  1003  1512 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.382  1003  1512 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:59.382  1003  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:59.382  1003  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.382  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:09:59.382  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:09:59.382  3204  3279 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:09:59.382  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,09-06 19:09:59.392  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-06 19:09:59.392  3204  3279 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,09-06 19:09:59.392  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 19:09:59.392  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-06 19:09:59.392  3204  3279 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-06 19:09:59.392  3204  3279 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-06 19:09:59.392  3204  3279 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 19:09:59.392  3204  3279 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-06 19:09:59.392  3204  3279 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-06 19:09:59.392  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:59.392  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-06 19:09:59.392  3204  3204 E DualScoManager: Dual Sco Manager already instantiated
,09-06 19:09:59.392  3204  3204 I DualScoManager: Set HeadsetServiceHelper
09-06 19:09:59.392  3204  3204 D BluetoothAtMessage: createCMTIContentObservers
,09-06 19:09:59.402  1003  1416 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-06 19:09:59.402  1003  1416 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:59.402  1003  1416 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:59.402  1003  1416 D SettingsProvider: selectionArgs: false
09-06 19:09:59.402  1003  1416 D SettingsProvider: selectionArgs: 1002
09-06 19:09:59.402  1003  1416 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:59.402  1003  1416 D SettingsProvider: ret = -1
,09-06 19:09:59.402  3204  7655 D HeadsetStateMachine: Enter Disconnected: -2
,09-06 19:09:59.402  3204  3204 D HeadsetService: mStartError = false
,09-06 19:09:59.402  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
,09-06 19:09:59.402  3204  3204 D A2dpService: Received start request. Starting profile...
09-06 19:09:59.402  3204  3204 D A2dpService: start()
09-06 19:09:59.402  3204  3204 I bluedroid: get_profile_interface avrcp
,09-06 19:09:59.402  3204  3204 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-06 19:09:59.402  3204  3204 D Avrcp   : Initialize Media Controller
09-06 19:09:59.402  3204  3204 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-06 19:09:59.412  3204  7655 D HeadsetStateMachine: Clear mHeadsetBrsf
09-06 19:09:59.412  3204  7655 D HeadsetStateMachine: map size, before remove : 0
09-06 19:09:59.412  3204  7655 D HeadsetStateMachine: map size, after remove: 0
,09-06 19:09:59.412  3204  3204 E Avrcp   : getActiveSessions
,09-06 19:09:59.412  3204  3204 D Avrcp   : pick active media Controller
09-06 19:09:59.412  3204  3204 D Avrcp   : Get the active Media Controller 
,09-06 19:09:59.412  3204  3204 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-06 19:09:59.412  3204  7656 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-06 19:09:59.412  3204  3204 D A2dpStateMachine: make
,09-06 19:09:59.422  3204  3204 I bluedroid: get_profile_interface a2dp
,09-06 19:09:59.422  3204  7658 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-06 19:09:59.422  3204  3204 E bt-btif : warning : media task started media_task_refcnt 1 
,09-06 19:09:59.422  3204  3204 D A2dpService: mStartError = false
,09-06 19:09:59.422  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
,09-06 19:09:59.422  3204  3204 D HidService: Received start request. Starting profile...
09-06 19:09:59.422  3204  3204 D HidService: start()
09-06 19:09:59.422  3204  3204 I bluedroid: get_profile_interface hidhost
09-06 19:09:59.422  3204  3204 D HidService: setHidService(): set to: null
09-06 19:09:59.422  3204  3204 D HidService: mStartError = false
09-06 19:09:59.422  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
09-06 19:09:59.422  3204  3204 D HeadsetStateMachine: Try to query the phonestate on bind
,09-06 19:09:59.422  1455  1473 I Telecom : BluetoothPhoneService: queryPhoneState
,09-06 19:09:59.422  3204  7657 D A2dpStateMachine: Enter Disconnected: -2
,09-06 19:09:59.432  1455  1455 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-06 19:09:59.432  1455  1455 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-06 19:09:59.432  1455  1473 I Telecom : BluetoothPhoneService: Result of Message : true
,09-06 19:09:59.432  3204  7656 D BluetoothMediaBrowser: no now playing list
09-06 19:09:59.432  3204  7656 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
09-06 19:09:59.432  3204  3204 D HealthService: Received start request. Starting profile...
09-06 19:09:59.432  3204  3204 D HealthService: start()
,09-06 19:09:59.432  3204  3204 I bluedroid: get_profile_interface health
,09-06 19:09:59.432  3204  3204 D HealthService: mStartError = false
09-06 19:09:59.432  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
,09-06 19:09:59.432  3204  3204 D HeadsetStateMachine: Proxy object connected
,09-06 19:09:59.432  3204  3204 D PanService: Received start request. Starting profile...
,09-06 19:09:59.432  3204  3204 D PanService: start()
09-06 19:09:59.432  3204  3204 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 19:09:59.432  3204  3204 I bluedroid: get_profile_interface pan
09-06 19:09:59.432  3204  3204 D PanService: mStartError = false
09-06 19:09:59.432  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
,09-06 19:09:59.432  3204  3204 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-06 19:09:59.432  3204  7655 D HeadsetStateMachine: Disconnected process message: 11
,09-06 19:09:59.432  3204  3204 D BluetoothMapService: Received start request. Starting profile...
,09-06 19:09:59.432  3204  3204 D BluetoothMapService: start()
,09-06 19:09:59.432  3204  3204 D BluetoothMapService: mStartError = false
,09-06 19:09:59.432  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
,09-06 19:09:59.442  3204  3204 D SapService: Received start request. Starting profile...,
09-06 19:09:59.442  3204  3204 D SapService: start()
09-06 19:09:59.442  3204  3204 D BluetoothSAPServiceJni: initializeNative(L209): sap
,09-06 19:09:59.442  3204  3204 I bluedroid: get_profile_interface sap
09-06 19:09:59.442  3204  3204 D SapService: mStartError = false
09-06 19:09:59.442  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
09-06 19:09:59.442  3204  3204 D HeadsetPhoneState: sendDeviceDataStateChanged
09-06 19:09:59.442  3204  3204 D HeadsetPhoneState: Signal level : previous=0 curr=4
,09-06 19:09:59.442  3204  3204 E BluetoothAdapterService(138181793): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-06 19:09:59.442  3204  3204 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-06 19:09:59.442  3204  3204 E BluetoothAdapterService(138181793): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-06 19:09:59.442  3204  3204 E BluetoothAdapterService(138181793): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-06 19:09:59.442  3204  7655 D HeadsetStateMachine: Disconnected process message: 18
09-06 19:09:59.442  3204  7655 D HeadsetStateMachine: Disconnected process message: 10
09-06 19:09:59.442  3204  7655 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 19:09:59.442  3204  7655 D HeadsetStateMachine: Disconnected process message: 11
09-06 19:09:59.442  3204  3204 E BluetoothAdapterService(138181793): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,09-06 19:09:59.442  3204  3204 E BluetoothAdapterService(138181793): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-06 19:09:59.452  3204  3204 E BluetoothAdapterService(138181793): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-06 19:09:59.462  3204  3204 E BluetoothAdapterService(138181793): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-06 19:09:59.462  3204  3279 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-06 19:09:59.462  3204  3279 I bluedroid: enable
,09-06 19:09:59.462  3204  3282 E bt-btif : Calling BTA_HhEnable
,09-06 19:09:59.462  3204  3282 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-06 19:09:59.462  3204  3282 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-06 19:09:59.462  3204  3282 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-06 19:09:59.462  3204  3282 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
,09-06 19:09:59.472  3204  3282 E BluetoothServiceJni: populateRssiValuesNative
,09-06 19:09:59.472  3204  3282 I bluedroid: getModelRssiValues
09-06 19:09:59.472  3204  3282 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-06 19:09:59.472  3204  3282 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-06 19:09:59.472  1003  1003 D SettingsProvider: name = bluetooth_name
,09-06 19:09:59.472  3204  3282 D BluetoothAdapterProperties: Name is: Galaxy A3
,09-06 19:09:59.472  3204  3282 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 19:09:59.472  3204  3282 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:09:59.472  3204  3282 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 19:09:59.472  3204  3282 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
09-06 19:09:59.472  3204  3282 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
09-06 19:09:59.472  3204  3282 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,09-06 19:09:59.472  3204  3282 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-06 19:09:59.472  3204  3282 E bt-btif : JVenable fails
09-06 19:09:59.472  3204  3282 D bte_conf: Device ID record 1 : primary
09-06 19:09:59.472  3204  3282 D bte_conf:   vendorId            = 0075
09-06 19:09:59.472  3204  3282 D bte_conf:   vendorIdSource      = 0001
09-06 19:09:59.472  3204  3282 D bte_conf:   product             = 0100
09-06 19:09:59.472  3204  3282 D bte_conf:   version             = 0200
09-06 19:09:59.472  3204  3282 D bte_conf:   clientExecutableURL = 
09-06 19:09:59.472  3204  3282 D bte_conf:   serviceDescription  = 
09-06 19:09:59.472  3204  3282 D bte_conf:   documentationURL    = 
09-06 19:09:59.472  3204  3282 D bte_conf: bte_load_did_conf no section named DID2.
,09-06 19:09:59.472  3204  3282 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-06 19:09:59.472  3204  3279 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-06 19:09:59.472  3204  3279 D BluetoothAdapterProperties: ScanMode =  20
,09-06 19:09:59.472  3204  3279 D BluetoothAdapterProperties: State =  11
,09-06 19:09:59.482  3204  3282 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-06 19:09:59.482  1003  1416 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-06 19:09:59.482  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:59.482  3204  3279 D BluetoothAdapterProperties: Setting state to 12
,09-06 19:09:59.482  3204  3279 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-06 19:09:59.482  3204  3282 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-06 19:09:59.482  3204  3282 D BluetoothAdapterProperties: Scan Mode:21
09-06 19:09:59.482  3204  3282 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 19:09:59.482  1003  1518 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-06 19:09:59.482  1003  1518 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:59.482  1003  1518 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:59.482  1003  1518 D SettingsProvider: selectionArgs: false
09-06 19:09:59.482  1003  1518 D SettingsProvider: selectionArgs: 1002
,09-06 19:09:59.482  1003  1518 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:59.482  1003  1518 D SettingsProvider: ret = -1
,09-06 19:09:59.482  3204  3279 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:09:59.482  3204  3279 D BluetoothAdapterService: updateAdapterState state is 12
,09-06 19:09:59.482  1003  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:59.482  1003  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.492  1003  1479 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.492  1003  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.492  1003  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.492  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:59.492  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:59.492  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:59.492  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:59.492  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:59.492  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:59.492  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:59.492  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:09:59.492  3204  3279 D BluetoothAdapterService: Autoconnection is available 
09-06 19:09:59.492  3204  3279 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-06 19:09:59.492  3204  3279 D BluetoothAdapterService: starting service from this receiver
09-06 19:09:59.492  1467  1493 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:59.492  1467  1493 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:59.492  1003  1733 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:59.492  1003  1733 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.492  1003  1733 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:59.492  1003  1733 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.492  1003  1733 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.492  4809  4817 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:09:59.492  3204  3204 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
09-06 19:09:59.492  3204  3204 I BluetoothPbapService: Handler(): got msg=1
,09-06 19:09:59.502  1003  1416 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-06 19:09:59.502  3204  3279 I BluetoothAdapterState: Entering On State from state = 11
,09-06 19:09:59.502  4809  4817 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:59.502  6822  6822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:09:59.502  3204  7663 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-06 19:09:59.522  3204  7663 D BluetoothSocket: bindListen(): myUserId = 0
,09-06 19:09:59.522  3204  7663 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:09:59.522  3204  7663 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,09-06 19:09:59.522  3204  7663 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:09:59.522  3204  7663 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:09:59.522  3204  7663 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@165cff5
,09-06 19:09:59.522  3204  7663 D BluetoothSocket: channel: 19
09-06 19:09:59.522  3204  7663 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-06 19:09:59.642  1003  1047 I art     : Explicit concurrent mark sweep GC freed 55467(3MB) AllocSpace objects, 6(97KB) LOS objects, 33% free, 22MB/34MB, paused 2.325ms total 142.125ms
,09-06 19:09:59.642  1003  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 19:09:59.642  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.652  1003  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.652  1003  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.652  1003  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.652  4809  7523 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:59.652  1003  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:09:59.652  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:09:59.652  1003  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.652  1003  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.652  1003  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.662  4809  7523 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:09:59.662  6822  6953 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:09:59.662  6822  6953 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:59.662  4809  4809 D BluetoothA2dp: Proxy object connected
09-06 19:09:59.662  4809  4809 D A2dpProfile: Bluetooth service connected
,09-06 19:09:59.662  1455  1466 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:59.662  1003  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 19:09:59.662  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:09:59.662  1003  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.662  1003  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.662  1003  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.662  1455  1466 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:09:59.662  4809  4809 D HeadsetProfile: Bluetooth service connected
,09-06 19:09:59.662  1455  7602 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:59.672  1003  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:09:59.672  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:09:59.672  1003  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.672  1003  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.672  1003  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.672  1455  7602 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:09:59.672  4809  4819 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-06 19:09:59.672  1003  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-06 19:09:59.672  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.672  1003  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:59.672  1003  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.672  1003  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.672  4809  4809 D BluetoothInputDevice: Proxy object connected
,09-06 19:09:59.672  4809  4809 D HidProfile: Bluetooth service connected
,09-06 19:09:59.672  1483  1797 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:59.672  1003  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 19:09:59.682  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:09:59.682  1003  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.682  1003  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.682  1003  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.682  1483  1797 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:09:59.682  4809  7523 D Bluetoothsap: onBluetoothStateChange: up=true
09-06 19:09:59.682  4809  7523 D Bluetoothsap: Binding service...
,09-06 19:09:59.682  4809  7523 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-06 19:09:59.682  1003  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,09-06 19:09:59.682  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.682  1003  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:59.682  1003  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.682  1003  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.682  4809  4809 D Bluetoothsap: BluetoothSAP Proxy object connected
09-06 19:09:59.682  4809  7523 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-06 19:09:59.682  4809  4809 D SapProfile: Bluetooth service connected
09-06 19:09:59.682  4809  4809 D Bluetoothsap: getConnectedDevices()
09-06 19:09:59.682  4809  4819 D BluetoothMap: onBluetoothStateChange: up=true
,09-06 19:09:59.692  1003  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-06 19:09:59.692  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.692  1003  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.692  1003  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.692  1003  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.692  4809  4809 D BluetoothMap: Proxy object connected
,09-06 19:09:59.692  4809  4809 D MapProfile: Bluetooth service connected
09-06 19:09:59.692  4809  4809 D BluetoothMap: getConnectedDevices()
09-06 19:09:59.692  1003  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:59.692  1003  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:09:59.692  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-06 19:09:59.692  1003  1047 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:09:59.692  1483  3316 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:09:59.692  1483  3316 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:59.692  3204  7605 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:59.692  3204  7605 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:09:59.692  1752  1951 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:59.692  1752  1951 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:59.692  4809  7523 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:59.692  4809  7523 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:09:59.692  4809  4817 D BluetoothPbap: onBluetoothStateChange: up=true
,09-06 19:09:59.692  1003  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-06 19:09:59.692  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.692  1003  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.692  1003  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.692  1003  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.702  4809  4809 D BluetoothPbap: Proxy object connected
09-06 19:09:59.702  7609  7624 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:59.702  7609  7624 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:09:59.702  1003  1047 D BluetoothPan: Binding service...
,09-06 19:09:59.702  1003  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-06 19:09:59.702  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.702  1455  1466 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:59.702  1455  1466 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:59.702  1003  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:59.702  1003  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:09:59.702  1003  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:09:59.702  1003  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:59.702  1003  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 19:09:59.702  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.702  1003  1003 D BluetoothA2dp: Proxy object connected
,09-06 19:09:59.702  1683  1700 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:59.702  1683  1700 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:09:59.702  1180  1987 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:59.702  4809  4809 D PbapServerProfile: Bluetooth service connected
09-06 19:09:59.702  1180  1987 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:59.702  1455  1473 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:59.702  1003  1003 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 19:09:59.702  1003  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:09:59.702  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:09:59.702  1003  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.702  1003  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.702  1003  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.702  1455  1473 E BluetoothHeadset: BluetoothHeadset service is binded
09-06 19:09:59.702  4809  7523 D BluetoothPan: Binding service...
,09-06 19:09:59.712  1003  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-06 19:09:59.712  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.712  1003  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.712  1003  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:59.712  1003  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.712  4809  4809 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 19:09:59.712  4809  4809 D PanProfile: Bluetooth service connected
09-06 19:09:59.712  3204  3217 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:09:59.712  3204  3217 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:59.712  1003  1047 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-06 19:09:59.712  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.712  1003  1047 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.712  1003  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.712  1003  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.712  3204  3204 D BluetoothA2dp: Proxy object connected
09-06 19:09:59.712  1003  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-06 19:09:59.712  1003  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-06 19:09:59.712  3204  3204 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-06 19:09:59.722  1003  1003 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:59.722  1003  1003 I InputMethodManagerService: [BT Setting State] State =12
09-06 19:09:59.722  1003  1003 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 19:09:59.722  1180  1180 D BluetoothTile:  onBluetoothStateChange:
,09-06 19:09:59.722  1180  1180 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 19:09:59.722  1180  1715 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:09:59.732  1180  1715 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:09:59.732  1180  1180 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:59.732  1180  1180 D BluetoothTile:  getBluetoothState : 12
,09-06 19:09:59.732  1180  1715 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:09:59.732  1455  1455 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@5c2bc75, true
,09-06 19:09:59.732  1003  1029 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:09:59.732  1455  1455 D BluetoothHeadset: registerMessageListener
,09-06 19:09:59.732  1003  1496 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-06 19:09:59.742  1995  1995 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:09:59.742  1180  1180 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:09:59.742  4809  4809 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:59.742  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:59.742  3204  3357 D HeadsetService: registerMessageListener
,09-06 19:09:59.752  3204  3357 D HeadsetService: registerMessageListener
,09-06 19:09:59.752  1455  1455 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-06 19:09:59.752  3204  7664 D BluetoothMapMasInstance: set MAP SDP message type : 1
09-06 19:09:59.752  1455  1455 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-06 19:09:59.752  3204  7655 D HeadsetStateMachine: Disconnected process message: 70
09-06 19:09:59.752  3204  7655 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@357f0c56
,09-06 19:09:59.752  1455  1455 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-06 19:09:59.752  1455  1455 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-06 19:09:59.752  1455  1455 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
09-06 19:09:59.752  4809  4809 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-06 19:09:59.752  4809  4809 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-06 19:09:59.752  4809  4809 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-06 19:09:59.752  4809  4809 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-06 19:09:59.752  3204  7655 D HeadsetStateMachine: Disconnected process message: 9
09-06 19:09:59.752  3204  7655 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-06 19:09:59.752  3204  7664 D BluetoothSocket: bindListen(): myUserId = 0,
09-06 19:09:59.752  3204  7664 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:09:59.752   283  1606 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-06 19:09:59.752   283  1606 V voice   : voice_set_parameters: enter: A2dpSuspended=false
,09-06 19:09:59.752   283  1606 V voice   : voice_set_parameters: exit with code(-2)
09-06 19:09:59.752   283  1606 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-06 19:09:59.752   283  1606 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-06 19:09:59.752   283  1606 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-06 19:09:59.752   283  1606 V audio_hw_primary: adev_set_parameters: exit
,09-06 19:09:59.762  3204  7655 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
09-06 19:09:59.762  3204  7664 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
09-06 19:09:59.762  3204  7664 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:09:59.762  3204  7664 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:09:59.762  3204  7664 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1d5ea4d7
09-06 19:09:59.762  3204  7664 D BluetoothSocket: channel: 5
,09-06 19:09:59.762  4809  4809 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:09:59.762  1003  1512 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-06 19:09:59.762  1003  1512 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.762  1003  1512 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:59.762  1003  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.762  1003  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:09:59.772  1683  1683 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-06 19:09:59.782  4809  4809 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:09:59.782  4809  4809 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:09:59.782  1180  1180 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:59.782  1180  1180 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-06 19:09:59.792  3204  3204 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@83c7ca1
,09-06 19:09:59.792  3204  3204 D BtConfig.SecureMode: isSecureModeOn:false
,09-06 19:09:59.792  1003  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:59.792  1003  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.792  1003  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:59.792  1003  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.792  1003  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.802  1003  1518 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-06 19:09:59.812  3204  7669 D BluetoothSocket: bindListen(): myUserId = 0
09-06 19:09:59.812  3204  7669 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:09:59.812  3204  7669 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[85]}
09-06 19:09:59.812  3204  7669 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:09:59.812  3204  7669 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:09:59.812  3204  7669 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3c7eb773
,09-06 19:09:59.812  3204  7669 D BluetoothSocket: channel: 12
09-06 19:09:59.812  3204  7669 I BtOppRfcommListener: Accept thread started.
,09-06 19:09:59.922   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-06 19:09:59.992  1003  1096 V AlarmManager: waitForAlarm result :8
,09-06 19:10:00.302  6822  7033 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:10:00.302  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:00.302  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:00.302  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:10:00.302  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:00.302  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:00.302  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:00.302  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:10:00.312  6822  7033 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:10:00.312  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:10:00.312  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@172370b0 added. We now have 8 listener(s)
,09-06 19:10:00.312  6822  7033 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:10:00.312  1003  1518 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-06 19:10:00.322  1003  1518 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-06 19:10:00.322  1003  1518 D SecContentProvider2: mCursor = null
,09-06 19:10:00.322  1003  1518 D WifiService: setWifiEnabled: false pid=6822, uid=10170
,09-06 19:10:00.322  1003  1518 D SettingsProvider: name = wifi_on
,09-06 19:10:00.322  6822  7033 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:00.332  1003  1733 D SecContentProvider: uri = 18 selection = isWifiEnabled,
09-06 19:10:00.332  1003  1733 D WifiService: setWifiEnabled: true pid=6822, uid=10170
09-06 19:10:00.332  1003  1733 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 19:10:00.332  1003  1733 W ActivityManager: Permission Denial: getCurrentUser() from pid=6822, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:10:00.332  1003  1733 D SecContentProvider2: mCursor = null
09-06 19:10:00.332  1003  1733 W WifiService: Failed getting userId using ActivityManagerNative
09-06 19:10:00.332  1003  1733 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6822, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:10:00.332  1003  1733 W WifiService: 	,at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 19:10:00.332  1003  1733 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-06 19:10:00.332  1003  1733 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-06 19:10:00.332  1003  1733 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-06 19:10:00.332  1003  1733 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-06 19:10:00.332  1003  1733 D SettingsProvider: name = wifi_on
,09-06 19:10:00.342  1003  1127 E WifiHW  : ##################### set firmware type 0 #####################,
,09-06 19:10:00.662  1003  1045 D Tethering: interfaceAdded wlan0
,09-06 19:10:00.662  1003  1132 E Tethering: No numeric data
,09-06 19:10:00.662  1003  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:00.662  1003  1124 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:10:00.662  1003  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:10:00.662  1003  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:10:00.672  1003  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:10:00.672  1003  1132 D Tethering: clearTetheredNotification()
09-06 19:10:00.672  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:10:00.672  1180  1180 D HotspotTile: updateTetherState():false, false
,09-06 19:10:00.672  1003  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:10:00.672  1003  1045 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:10:00.672  1003  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:10:00.672  1003  1124 V NetworkStats: performPollLocked() took 9ms
,09-06 19:10:00.672  1003  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:00.672  1003  1132 D Tethering: InitialState.processMessage what=4
,09-06 19:10:00.682  1003  1132 E Tethering: No numeric data
,09-06 19:10:00.682  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:00.682  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:00.682  1003  1045 D Tethering: interfaceAdded p2p0
,09-06 19:10:00.682  1003  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-06 19:10:00.682  1003  1132 D Tethering: clearTetheredNotification()
09-06 19:10:00.682  1003  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-06 19:10:00.692  1003  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:10:00.692  1003  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:10:00.692  1003  1045 D Tethering: interfaceStatusChanged p2p0, false
09-06 19:10:00.692   278   905 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-06 19:10:00.692   278   905 D SoftapController: Softap fwReload - Ok
,09-06 19:10:00.692  1003  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:00.692  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:10:00.692   278   905 D CommandListener: Setting iface cfg
09-06 19:10:00.692  1180  1180 D HotspotTile: updateTetherState():false, false
09-06 19:10:00.692   278   905 D CommandListener: Trying to bring down wlan0
09-06 19:10:00.692  1003  1124 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:10:00.692   278   905 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:10:00.692  1003  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-06 19:10:00.692  1003  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:10:00.702  1003  1124 V NetworkStats: performPollLocked() took 6ms
,09-06 19:10:00.702  1003  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:00.702  1003  1127 E WifiHW  : supplicant_name : p2p_supplicant
09-06 19:10:00.702  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:00.702  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:00.702  1003  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-06 19:10:00.722  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-06 19:10:00.722  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:10:00.722  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:10:00.722  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:00.722  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:00.722  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:00.722  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:00.722  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:10:00.722  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-06 19:10:00.722  1180  1715 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-06 19:10:00.722  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:10:00.732  1180  1180 D HotspotTile: onReceive : 2, 0
,09-06 19:10:00.732  4809  4809 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:10:00.742  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:00.742  1003  1223 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:10:00.742  1003  1223 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:10:00.742  1003  1223 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:10:00.742  1003  1223 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:00.742  1003  1223 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:10:00.752  1611  1611 I Hs20UtilService: Starting #19
09-06 19:10:00.752  1611  1654 I Hs20UtilService: Message received 5011
,09-06 19:10:00.752  6971  6971 D SecurityLogAgent: KnoxConfiguration : Current State = 1,
,09-06 19:10:00.752  6971  6971 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:10:00.752  6971  6971 D SecurityLogAgent: StateMachine : Current State = 1
,09-06 19:10:00.752  6971  6971 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:10:00.772  7680  7680 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
09-06 19:10:00.782  7680  7680 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-06 19:10:00.782  7680  7680 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-06 19:10:00.792  7680  7680 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
09-06 19:10:00.792   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7680
09-06 19:10:00.792   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-06 19:10:00.792  7680  7680 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-06 19:10:00.792  7680  7680 I wpa_supplicant: ssSupport state is = 1
09-06 19:10:00.792  7680  7680 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-06 19:10:00.792  7680  7680 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-06 19:10:00.792   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7680,
09-06 19:10:00.792   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-06 19:10:00.952   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,09-06 19:10:00.952  7680  7680 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,09-06 19:10:01.002  7680  7680 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-06 19:10:01.002  7680  7680 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-06 19:10:01.012  7680  7680 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,09-06 19:10:01.012   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7680
09-06 19:10:01.012   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,09-06 19:10:01.012  7680  7680 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-06 19:10:01.012  7680  7680 I wpa_supplicant: ssSupport state is = 1
09-06 19:10:01.012  7680  7680 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:10:01.012  7680  7680 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:10:01.012  7680  7680 E wpa_supplicant: SIM READ ERROR,
09-06 19:10:01.012  7680  7680 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:10:01.012  7680  7680 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:10:01.012  7680  7680 E wpa_supplicant: SIM READ ERROR
09-06 19:10:01.012  7680  7680 I wpa_supplicant: Blacklist: Clear (all) 
09-06 19:10:01.012  7680  7680 I wpa_supplicant: wpa_default_ap_write_once
09-06 19:10:01.012  7680  7680 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-06 19:10:01.012  7680  7680 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:10:01.012  7680  7680 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
09-06 19:10:01.012  7680  7680 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:10:01.012  7680  7680 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-06 19:10:01.012  7680  7680 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-06 19:10:01.012  1003  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:10:01.012  1003  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:10:01.012  1003  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:10:01.192  7680  7680 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-06 19:10:01.322  7680  7680 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-06 19:10:01.322  7680  7680 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,09-06 19:10:01.332  7680  7680 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-06 19:10:01.332   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7680
09-06 19:10:01.332   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-06 19:10:01.342  7680  7680 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-06 19:10:01.342  7680  7680 I wpa_supplicant: ssSupport state is = 1
09-06 19:10:01.342  7680  7680 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-06 19:10:01.342  7680  7680 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-06 19:10:01.352  7680  7680 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,09-06 19:10:01.352   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7680
09-06 19:10:01.352   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-06 19:10:01.352  7680  7680 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
,09-06 19:10:01.352  7680  7680 I wpa_supplicant: ssSupport state is = 1
,09-06 19:10:01.352  1003  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:10:01.352  7680  7680 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-06 19:10:01.362  1003  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:10:01.352  7680  7680 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:10:01.352  7680  7680 E wpa_supplicant: SIM READ ERROR
09-06 19:10:01.352  7680  7680 I wpa_supplicant: wpa_default_ap_write_once
,09-06 19:10:01.352  7680  7680 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-06 19:10:01.352  7680  7680 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-06 19:10:01.352  1003  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:10:01.352  1003  1045 D Tethering: interfaceStatusChanged p2p0, false
09-06 19:10:01.362  1003  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:10:01.362  1003  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:10:01.402  7680  7680 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-06 19:10:01.402  7680  7680 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-06 19:10:01.462  7680  7680 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-06 19:10:01.462  7680  7680 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,09-06 19:10:01.462  7680  7680 I wpa_supplicant: Skip scan - bUseNetwork false
,09-06 19:10:01.472  1003  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,09-06 19:10:01.472  1003  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21],
09-06 19:10:01.472  7680  7680 I wpa_supplicant: HOTSPOT20_ENABLE called
,09-06 19:10:01.472  7680  7680 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:10:01.472  7680  7680 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-06 19:10:01.472  7680  7680 E wpa_supplicant: SIM READ ERROR
09-06 19:10:01.472  7680  7680 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:10:01.492  7680  7680 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-06 19:10:01.502  7680  7680 I wpa_supplicant: Skip scan - bUseNetwork false
,09-06 19:10:01.502  1003  1127 D WifiConfigStore: Loading config and enabling all networks 
,09-06 19:10:01.512  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-06 19:10:01.512  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:10:01.512  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:10:01.512  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:01.512  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:01.512  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:01.512  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:01.512  4809  4809 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:10:01.512  1180  1180 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:10:01.512  1180  1180 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-06 19:10:01.512  1180  1715 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 19:10:01.512  1180  1180 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:10:01.522  1180  1180 D HotspotTile: onReceive : 3, 0
09-06 19:10:01.522  1003  1127 E WifiConfigStore: Not a HS20
,09-06 19:10:01.522  1003  1518 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:10:01.522  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:10:01.522  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:01.522  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:01.522  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:01.522  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:01.522  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:01.522  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:01.522  6822  6822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:10:01.522  1003  1518 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:10:01.522  1003  1518 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:10:01.522  1003  1518 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:01.522  1003  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:10:01.522  1003  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
09-06 19:10:01.522  6822  6822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:10:01.522  1003  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-06 19:10:01.522  7680  7680 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-06 19:10:01.522  7680  7680 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-06 19:10:01.522  7680  7680 I wpa_supplicant: reset timer : RESET_TIMER 0
09-06 19:10:01.522  7680  7680 I wpa_supplicant: P2P: Current p2p state = IDLE
09-06 19:10:01.522  7680  7680 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-06 19:10:01.522  7680  7680 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-06 19:10:01.522  7680  7680 I wpa_supplicant: First Scan Start
09-06 19:10:01.522  7680  7680 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-06 19:10:01.532  1611  1611 I Hs20UtilService: Starting #20
09-06 19:10:01.532  1611  1654 I Hs20UtilService: Message received 5011
,09-06 19:10:01.532  6971  6971 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 19:10:01.532  1003  1127 D WifiNative-wlan0: Setting external_sim to 1
,09-06 19:10:01.532  1003  1127 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 19:10:01.532  1003  1127 I WifiNative-HAL: startHal
09-06 19:10:01.532  1003  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9f4dc88c
09-06 19:10:01.532  1003  1127 I WifiNative-HAL: Could not start hal
,09-06 19:10:01.532  7191  7191 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:10:01.532  6971  6971 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-06 19:10:01.532  6971  6971 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:10:01.532  6971  6971 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:10:01.532  1003  1127 E WifiNative-wlan0: do suspend true
,09-06 19:10:01.532  1003  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-06 19:10:01.532  1003  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-06 19:10:01.542  1003  1003 D WifiScanningService: SCAN_AVAILABLE : 3
,09-06 19:10:01.542  1003  1152 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:10:01.542  1003  1152 I WifiNative-HAL: startHal
09-06 19:10:01.542  1003  1152 E wifi    : getStaticLongField sWifiHalHandle 0x9e39e9bc
,09-06 19:10:01.542  1003  1152 I WifiNative-HAL: Could not start hal
09-06 19:10:01.542  1003  1152 E WifiScanningService: could not start HAL
09-06 19:10:01.542   278   905 D CommandListener: Setting iface cfg
09-06 19:10:01.542   278   905 D CommandListener: Trying to bring up p2p0
,09-06 19:10:01.542  1003  1003 D RttService: SCAN_AVAILABLE : 3
09-06 19:10:01.542  1003  1153 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:10:01.542  1003  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 19:10:01.542  1003  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 19:10:01.542  1003  1127 E WifiNative-wlan0: invaild command id : 215
09-06 19:10:01.542  1003  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-06 19:10:01.542  1003  1126 D WifiP2pService: P2pEnablingState
,09-06 19:10:01.542  1003  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
,09-06 19:10:01.542  1003  1126 D WifiP2pService: P2p socket connection successful
09-06 19:10:01.542  1003  1126 D WifiP2pService: P2pEnabledState
09-06 19:10:01.542  7680  7680 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-06 19:10:01.542  7680  7680 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-06 19:10:01.542  7680  7680 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,09-06 19:10:01.552  1003  1127 E WifiStateMachine: Failed to set frequency band 0
,09-06 19:10:01.552  1003  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-06 19:10:01.552  1003  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 19:10:01.552  1003  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 19:10:01.552  1003  1127 E WifiNative-wlan0: invaild command id : 215
,09-06 19:10:01.552  1003  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:10:01.552  1003  1127 D SecContentProvider2: mCursor = null
09-06 19:10:01.552  1003  1129 E ConnectivityService: updateNetworkInfo(),
09-06 19:10:01.552  1003  1003 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-06 19:10:01.552  1003  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:10:01.552  1003  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-06 19:10:01.552  1003  1127 D SecContentProvider2: mCursor = null
09-06 19:10:01.552  1003  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:10:01.552  1003  1048 D WifiDisplayController: disconnect
,09-06 19:10:01.552  1003  1048 D WifiDisplayController: updateConnection
09-06 19:10:01.552  1003  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:10:01.552  1003  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 19:10:01.552  1180  1180 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-06 19:10:01.552  1003  1416 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 19:10:01.552  1180  1180 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-06 19:10:01.562  1003  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-06 19:10:01.562  1003  1048 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:10:01.562  1003  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:10:01.562  1003  1126 D WifiNative-p2p0: p2pGetDeviceAddress
09-06 19:10:01.562  1003  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
09-06 19:10:01.562  1003  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,09-06 19:10:01.562  1003  1126 D WifiP2pService: DeviceAddress: 0a:75:42
,09-06 19:10:01.562  1003  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-06 19:10:01.562  1003  1048 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-06 19:10:01.562  1003  1048 D WifiDisplayController:  primary type: 10-0050F204-5
09-06 19:10:01.562  1003  1048 D WifiDisplayController:  secondary type: null
09-06 19:10:01.562  1003  1048 D WifiDisplayController:  wps: 0
09-06 19:10:01.562  1003  1048 D WifiDisplayController:  grpcapab: 0
09-06 19:10:01.562  1003  1048 D WifiDisplayController:  devcapab: 0
09-06 19:10:01.562  1003  1048 D WifiDisplayController:  status: 3
09-06 19:10:01.562  1003  1048 D WifiDisplayController:  wfdInfo: null
09-06 19:10:01.562  1003  1048 D WifiDisplayController:  groupownerAddress: null
09-06 19:10:01.562  1003  1048 D WifiDisplayController:  GOdeviceName: null
09-06 19:10:01.562  1003  1048 D WifiDisplayController:  interfaceAddress: 
09-06 19:10:01.562  1003  1048 D WifiDisplayController:  SConnectInfo : null
,09-06 19:10:01.562  4809  4809 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-06 19:10:01.572  4809  4809 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:10:01.572  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
,09-06 19:10:01.572  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:10:01.572  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:10:01.572  4809  4809 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:10:01.572  4809  4849 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:10:01.572  7524  7524 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:10:01.572  7524  7524 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-06 19:10:01.572  7524  7524 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 19:10:01.582  1003  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-06 19:10:01.582  1003  1126 D WifiP2pService: InactiveState
,09-06 19:10:01.582  7175  7175 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:10:01.582  1003  1126 D WifiP2pService: InactiveState{ what=143376 }
09-06 19:10:01.582  1003  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 19:10:01.582  7680  7680 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-06 19:10:01.582  1003  1126 D WifiP2pService: InactiveState{ what=143376 }
,09-06 19:10:01.582  1003  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 19:10:01.672  1003  1045 D Tethering: interfaceLinkStateChanged p2p0, false,
09-06 19:10:01.672  1003  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:10:01.672  1003  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:10:01.922   291   291 E SMD     : DCD OFF,
,09-06 19:10:02.342  6822  7033 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:10:02.342  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:02.342  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:02.342  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:02.342  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:02.342  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:02.342  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:02.342  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:10:02.352  6822  7033 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:10:02.352  6822  7033 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-06 19:10:02.352  6822  7033 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-06 19:10:02.352  6822  7033 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3fa9a777 Bundle[{}]
,09-06 19:10:02.352  6822  7033 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-06 19:10:02.352  6822  7033 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-06 19:10:02.362  6822  7033 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-06 19:10:02.362  6822  7033 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-06 19:10:02.362  6822  7033 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-06 19:10:02.362  6822  7033 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-06 19:10:02.362  6822  7033 I System.out: Running OutgoingSocketThread
,09-06 19:10:02.372  6822  7689 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1375)
,09-06 19:10:02.372  6822  7689 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 52908
,09-06 19:10:02.372  6822  7689 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-06 19:10:02.782  7680  7680 I wpa_supplicant: nl80211: Received scan results (29 BSSes),
,09-06 19:10:02.782  7680  7680 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
,09-06 19:10:02.792  1003  7686 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
09-06 19:10:02.792  7680  7680 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-06 19:10:02.792  7680  7680 I wpa_supplicant: Trying to associate with  'G700',
09-06 19:10:02.792  7680  7680 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
,09-06 19:10:02.792  7680  7680 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,09-06 19:10:02.812  1003  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-06 19:10:02.812  1003  1127 D SecContentProvider2: mCursor = null
,09-06 19:10:02.902  7680  7680 E wpa_supplicant: Cmd 35605 not handled
,09-06 19:10:02.902  7680  7680 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED,
09-06 19:10:02.902  7680  7680 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-06 19:10:02.902  1003  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:10:02.902  1003  1045 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:10:02.902  7680  7680 I wpa_supplicant: Associated with F4.99.3E,
09-06 19:10:02.902  1003  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:10:02.902  7680  7680 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-06 19:10:02.902  7680  7680 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-06 19:10:02.912  1003  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:10:02.902  7680  7680 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
09-06 19:10:02.912  1003  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:10:02.912  1003  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:10:02.912  1003  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:10:02.912  1003  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:10:02.912  1003  1045 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:10:02.912  1003  1045 D Tethering: interfaceLinkStateChanged wlan0, true
09-06 19:10:02.912  1003  1045 D Tethering: interfaceStatusChanged wlan0, true
,09-06 19:10:02.912  1003  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true,
09-06 19:10:02.912  1003  1132 E Tethering: No numeric data
09-06 19:10:02.912  1003  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:10:02.912  1003  1127 D SecContentProvider2: mCursor = null
,09-06 19:10:02.912  7680  7680 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-06 19:10:02.922  1003  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:10:02.922  1003  1132 D Tethering: clearTetheredNotification()
,09-06 19:10:02.922  7680  7680 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-06 19:10:02.922  7680  7680 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-06 19:10:02.922  7680  7680 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-06 19:10:02.922  7680  7680 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:10:02.922  7680  7680 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-06 19:10:02.922  7680  7680 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-06 19:10:02.922  7680  7680 I wpa_supplicant: Blacklist: Clear (temp) 
09-06 19:10:02.922  1003  1124 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:10:02.922  1003  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:02.922  7680  7680 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-06 19:10:02.922  1003  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:10:02.922  1003  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:10:02.922  1003  1045 D Tethering: interfaceLinkStateChanged wlan0, true
09-06 19:10:02.922  1003  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-06 19:10:02.922  1003  1045 D Tethering: interfaceStatusChanged wlan0, true
09-06 19:10:02.922  1180  1180 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:10:02.932  1180  1180 D HotspotTile: updateTetherState():false, false
,09-06 19:10:02.932  1003  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-06 19:10:02.932  1003  1127 D SecContentProvider2: mCursor = null
,09-06 19:10:02.932  1003  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:02.932  1003  1124 V NetworkStats: performPollLocked() took 10ms
,09-06 19:10:02.932  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:02.932  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:02.942  1003  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-06 19:10:02.942  1003  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,09-06 19:10:02.952  1003  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-06 19:10:02.952  1003  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-06 19:10:02.952  1003  1129 E ConnectivityService: updateNetworkInfo()
09-06 19:10:02.952  1003  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-06 19:10:02.952  1003  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 19:10:02.952  1003  1137 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:10:02.952  1003  1137 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:10:02.952  1003  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:10:02.952  1003  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:02.952  1003  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:10:02.952  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-06 19:10:02.952  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:10:02.952  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-06 19:10:02.952  1611  1611 I Hs20UtilService: Starting #21
,09-06 19:10:02.952  1611  1654 I Hs20UtilService: Message received 5007
09-06 19:10:02.962  1003  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:10:02.962  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:02.962  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:02.962  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:02.962  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:02.962  4809  4809 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 19:10:02.962  4809  4809 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:10:02.962  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:10:02.962  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 19:10:02.972  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-06 19:10:02.972  4809  4809 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 19:10:02.972  4809  4849 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:10:02.972   278   905 D CommandListener: Setting iface cfg
,09-06 19:10:02.972  1003  1127 E WifiStateMachine: Start Dhcp Watchdog 3
,09-06 19:10:02.982  1003  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:10:02.982  1003  1127 D SecContentProvider2: mCursor = null
,09-06 19:10:02.982  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-06 19:10:02.992  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:10:02.992  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:10:02.992  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:02.992  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:02.992  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:02.992  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:02.992  1003  1127 E WifiNative-wlan0: do suspend false
,09-06 19:10:02.992  1003  1126 D WifiP2pService: InactiveState{ what=143375 }
,09-06 19:10:02.992  1003  1126 D WifiP2pService: P2pEnabledState{ what=143375 },
,09-06 19:10:02.992  1003  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:10:02.992  1003  1127 D SecContentProvider2: mCursor = null
,09-06 19:10:03.212  7694  7694 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
09-06 19:10:03.212  7694  7694 I dhcpcd  : version 5.5.6 starting
09-06 19:10:03.212  7694  7694 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-06 19:10:03.272  7694  7694 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-06 19:10:03.272  7694  7694 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-06 19:10:03.272  7694  7694 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
09-06 19:10:03.272  7694  7694 I dhcpcd  : bssid match
09-06 19:10:03.272  7694  7694 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,09-06 19:10:03.332  1003  3354 D SSRM:n  : SIOP:: AP = 330,
,09-06 19:10:03.372  6822  7033 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1376),
09-06 19:10:03.372  6822  7033 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1376)
,09-06 19:10:03.372  6822  7033 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1381)
09-06 19:10:03.372  6822  7033 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-06 19:10:03.372  6822  7033 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1382)
,09-06 19:10:03.372  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:10:03.372  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e8ccb29 added. We now have 2 listener(s)
09-06 19:10:03.382  7694  7694 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,09-06 19:10:03.382  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-06 19:10:03.382  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:10:03.382  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:10:03.382  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:10:03.382  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@128f2eae added. We now have 9 listener(s)
,09-06 19:10:03.382  6822  7033 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:10:03.382  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:10:03.392  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:10:03.392  6822  7033 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:10:03.392  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:03.392  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:03.392  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:03.392  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:03.392  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:03.392  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:03.392  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:10:03.402  6822  7033 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:10:03.402  6822  7033 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:10:03.402  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:03.402  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:03.402  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:10:03.402  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38c6e7dc added. We now have 3 listener(s)
,09-06 19:10:03.412  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-06 19:10:03.412  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:10:03.412  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:10:03.412  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:10:03.412  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@377df0e5 added. We now have 10 listener(s)
,09-06 19:10:03.412  6822  7033 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:10:03.412  6822  7033 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:10:03.412  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:10:03.412  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:10:03.412  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
,09-06 19:10:03.412  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:10:03.412  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:10:03.412  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 19:10:03.412  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e8ccb29 removed from the list
09-06 19:10:03.412  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-06 19:10:03.412  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@128f2eae removed from the list
,09-06 19:10:03.412  6822  7033 D io.jxcore.node.ConnectivityMonitor: stop,
,09-06 19:10:03.412  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:03.422  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:10:03.422  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:03.422  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:10:03.422  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:03.422  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.422  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@128f2eae not in the list
09-06 19:10:03.422  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.422  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:03.422  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:03.422  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:10:03.422  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.422  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@377df0e5 removed from the list
,09-06 19:10:03.422  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:03.422  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-06 19:10:03.422  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:03.422  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:03.422  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38c6e7dc removed from the list
09-06 19:10:03.422  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:10:03.422  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@362387ba added. We now have 2 listener(s)
09-06 19:10:03.422  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
09-06 19:10:03.422  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:10:03.422  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:10:03.422  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:10:03.422  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1457a66b added. We now have 9 listener(s)
09-06 19:10:03.422  6822  7033 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:10:03.422  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:10:03.432  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:10:03.432  6822  7033 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-06 19:10:03.432  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:03.432  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:03.432  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:03.432  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:03.432  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:03.432  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:03.432  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:10:03.432  6822  7033 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:10:03.432  6822  7033 D io.jxcore.node.ConnectivityMonitor: start: OK,
09-06 19:10:03.432  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:10:03.432  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ba1b661 added. We now have 3 listener(s)
,09-06 19:10:03.432  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:03.442  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:03.442  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-06 19:10:03.442  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:10:03.442  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:10:03.442  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:10:03.442  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29726586 added. We now have 10 listener(s)
09-06 19:10:03.442  6822  7033 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
,09-06 19:10:03.442  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:10:03.442  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-06 19:10:03.442  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
09-06 19:10:03.442  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:10:03.442  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:10:03.442  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:10:03.452  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:10:03.452  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:10:03.452  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:10:03.452  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-06 19:10:03.452  6822  7033 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:10:03.462  3204  7605 D BtGatt.GattService: registerClient() - UUID=64ab00a9-57a3-4eb3-93a4-84b0812b7ec0
,09-06 19:10:03.462  7694  7694 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,09-06 19:10:03.502  3204  3282 D BtGatt.GattService: onClientRegistered() - UUID=64ab00a9-57a3-4eb3-93a4-84b0812b7ec0, clientIf=6,
,09-06 19:10:03.502  6822  6836 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:10:03.502  3204  7604 D BtGatt.GattService: start scan with filters
09-06 19:10:03.502  3204  3340 D BtGatt.ScanManager: handling starting scan,
09-06 19:10:03.502  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 19:10:03.502  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:10:03.502  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
09-06 19:10:03.502  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-06 19:10:03.512  3204  3282 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-06 19:10:03.512  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.512  3204  3340 D BtGatt.ScanManager: allow scan with filters
,09-06 19:10:03.512  3204  3340 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-06 19:10:03.512  3204  3340 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
09-06 19:10:03.512  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:10:03.512  3204  3282 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-06 19:10:03.512  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.512  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 19:10:03.512  6822  6822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:10:03.512  3204  3340 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:10:03.512  3204  3340 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:10:03.512  3204  3282 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-06 19:10:03.512  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.512  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-06 19:10:03.512  3204  3282 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-06 19:10:03.512  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.522  6822  7033 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:10:03.522  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:10:03.522  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:10:03.522  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.522  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:10:03.522  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:10:03.522  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-06 19:10:03.522  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:10:03.522  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:10:03.522  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:10:03.522  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:10:03.522  3204  3217 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:10:03.522  3204  3357 D BtGatt.GattService: unregisterClient() - clientIf=6,
,09-06 19:10:03.522  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-06 19:10:03.522  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:10:03.522  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:10:03.522  3204  3340 D BtGatt.ScanManager: filter size is 1
09-06 19:10:03.532  3204  3340 D BtGatt.ScanManager: delete FilterIndex - 6,
09-06 19:10:03.532  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:10:03.532  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:10:03.532  3204  3282 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-06 19:10:03.532  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.532  3204  3340 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:10:03.532  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:10:03.532  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:10:03.532  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:10:03.532  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:10:03.532  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:10:03.532  3204  3282 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-06 19:10:03.532  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.532  3204  3340 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 19:10:03.532  6822  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:10:03.532  6822  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:10:03.532  6822  6822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:10:03.532  3204  3282 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 19:10:03.532  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.542  6822  7033 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:10:03.542  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:10:03.542  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:10:03.542  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:03.542  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.542  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:10:03.542  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:03.542  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@362387ba removed from the list
09-06 19:10:03.542  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:10:03.542  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1457a66b removed from the list
09-06 19:10:03.542  6822  7033 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:10:03.542  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:03.542  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:10:03.542  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:03.552  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-06 19:10:03.552  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-06 19:10:03.552  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:10:03.552  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1457a66b not in the list
09-06 19:10:03.552  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.552  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:03.552  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:03.552  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:10:03.552  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.552  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29726586 removed from the list
09-06 19:10:03.552  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:03.552  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.552  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:03.552  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:03.552  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ba1b661 removed from the list
09-06 19:10:03.552  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:10:03.552  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f5412 added. We now have 2 listener(s)
,09-06 19:10:03.562  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-06 19:10:03.562  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:10:03.562  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:10:03.562  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:10:03.562  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c077e3 added. We now have 9 listener(s)
09-06 19:10:03.562  6822  7033 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:10:03.562  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:10:03.562  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:10:03.562  6822  7033 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:10:03.562  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:03.562  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:03.562  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:03.562  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:03.562  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:03.562  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:03.562  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:10:03.572  6822  7033 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:10:03.572  6822  7033 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:10:03.572  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:10:03.572  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b91d099 added. We now have 3 listener(s)
,09-06 19:10:03.572  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-06 19:10:03.572  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:10:03.572  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:10:03.572  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:10:03.572  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9fa9f5e added. We now have 10 listener(s)
09-06 19:10:03.572  6822  7033 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:10:03.572  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:10:03.572  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:10:03.572  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:10:03.572  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:10:03.572  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:10:03.572  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:10:03.572  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:10:03.582  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:03.582  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:10:03.582  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:10:03.592  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:03.592  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 19:10:03.592  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
09-06 19:10:03.592  6822  7033 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:10:03.602  3204  3357 D BtGatt.GattService: registerClient() - UUID=3eb61652-e290-4a32-ba71-5af8c4b31c5b
,09-06 19:10:03.652  3204  3282 D BtGatt.GattService: onClientRegistered() - UUID=3eb61652-e290-4a32-ba71-5af8c4b31c5b, clientIf=6,
09-06 19:10:03.652  6822  6953 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-06 19:10:03.652  3204  3219 D BtGatt.GattService: start scan with filters,
09-06 19:10:03.652  3204  3340 D BtGatt.ScanManager: handling starting scan
09-06 19:10:03.652  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 19:10:03.652  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
09-06 19:10:03.652  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:10:03.652  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:10:03.652  3204  3282 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 19:10:03.652  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.652  3204  3340 D BtGatt.ScanManager: allow scan with filters
09-06 19:10:03.652  3204  3340 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-06 19:10:03.652  3204  3340 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,09-06 19:10:03.652  3204  3282 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-06 19:10:03.652  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.662  3204  3340 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:10:03.662  3204  3340 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:10:03.662  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:10:03.662  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:10:03.662  6822  6822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:10:03.662  3204  3282 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-06 19:10:03.662  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.662  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:10:03.662  3204  3282 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-06 19:10:03.662  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.672  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-06 19:10:03.672  6822  7033 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-06 19:10:03.672  6822  7033 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:10:03.672  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:10:03.672  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:10:03.672  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:03.672  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.672  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:10:03.672  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:03.672  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f5412 removed from the list
09-06 19:10:03.672  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.672  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c077e3 removed from the list
09-06 19:10:03.672  6822  7033 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:10:03.672  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:10:03.672  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.672  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-06 19:10:03.672  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:10:03.672  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:10:03.672  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:10:03.672  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:03.672  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.672  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35c077e3 not in the list
09-06 19:10:03.672  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:10:03.672  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:10:03.672  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:10:03.672  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:10:03.672  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:10:03.672  3204  7604 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:10:03.672  3204  3340 D BtGatt.ScanManager: filter size is 1
09-06 19:10:03.672  3204  3217 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:10:03.672  3204  3340 D BtGatt.ScanManager: delete FilterIndex - 7
,09-06 19:10:03.672  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:10:03.672  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-06 19:10:03.672  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:10:03.672  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:10:03.672  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:10:03.672  3204  3282 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-06 19:10:03.672  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.672  3204  3340 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:10:03.672  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:10:03.682  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-06 19:10:03.682  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:10:03.682  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:10:03.682  3204  3282 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-06 19:10:03.682  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.682  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:03.682  3204  3340 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 19:10:03.682  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:03.682  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:10:03.682  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.682  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9fa9f5e removed from the list
09-06 19:10:03.682  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:03.682  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.682  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:03.682  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:03.682  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b91d099 removed from the list
,09-06 19:10:03.682  6822  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:10:03.682  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:10:03.682  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@354d536a added. We now have 2 listener(s)
,09-06 19:10:03.682  6822  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:10:03.682  6822  6822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:10:03.682  3204  3282 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 19:10:03.682  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.682  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
09-06 19:10:03.682  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:10:03.682  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
09-06 19:10:03.682  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:10:03.682  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f53005b added. We now have 9 listener(s)
09-06 19:10:03.682  6822  7033 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:10:03.682  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:10:03.692  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:10:03.692  6822  7033 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:10:03.692  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:03.692  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:03.692  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:03.692  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:03.692  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:03.692  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:03.692  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:10:03.692  6822  7033 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:10:03.692  6822  7033 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:10:03.692  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:10:03.692  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab3f9d1 added. We now have 3 listener(s)
,09-06 19:10:03.692  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:03.692  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-06 19:10:03.692  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:10:03.692  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:10:03.692  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:10:03.692  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d653c36 added. We now have 10 listener(s)
09-06 19:10:03.692  6822  7033 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:10:03.692  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:10:03.692  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:10:03.692  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:10:03.692  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:10:03.692  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:10:03.702  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:03.702  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:10:03.702  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:10:03.702  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:10:03.702  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:10:03.712  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:10:03.712  6822  7033 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:10:03.712  3204  3357 D BtGatt.GattService: registerClient() - UUID=562584cc-ac91-46c1-b663-4315248d2a59
,09-06 19:10:03.752  3204  3282 D BtGatt.GattService: onClientRegistered() - UUID=562584cc-ac91-46c1-b663-4315248d2a59, clientIf=6
,09-06 19:10:03.752  6822  6953 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:10:03.752  3204  3219 D BtGatt.GattService: start scan with filters
,09-06 19:10:03.752  3204  3340 D BtGatt.ScanManager: handling starting scan
,09-06 19:10:03.752  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:10:03.752  3204  3282 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-06 19:10:03.762  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:10:03.762  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:10:03.762  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:10:03.762  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.762  3204  3340 D BtGatt.ScanManager: allow scan with filters
09-06 19:10:03.762  3204  3340 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-06 19:10:03.762  3204  3340 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
,09-06 19:10:03.762  3204  3282 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-06 19:10:03.762  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.762  3204  3340 D BtGatt.ScanManager: Starting BLE batch scan
,09-06 19:10:03.762  3204  3340 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:10:03.762  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:10:03.762  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:10:03.762  6822  6822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:10:03.762  3204  3282 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-06 19:10:03.762  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.772  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:10:03.772  3204  3282 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-06 19:10:03.772  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.782  6822  7033 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:10:03.782  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:10:03.782  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:10:03.782  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:10:03.782  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:10:03.782  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-06 19:10:03.782  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 19:10:03.782  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@354d536a removed from the list
,09-06 19:10:03.782  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:10:03.782  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f53005b removed from the list
,09-06 19:10:03.792  6822  7033 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:10:03.792  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:10:03.792  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:10:03.792  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-06 19:10:03.792  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.792  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:10:03.792  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:10:03.792  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:03.792  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.792  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f53005b not in the list
09-06 19:10:03.792  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:10:03.792  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-06 19:10:03.792  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-06 19:10:03.792  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:10:03.792  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:10:03.792  3204  3357 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:10:03.792  3204  3340 D BtGatt.ScanManager: filter size is 1
,09-06 19:10:03.802  3204  3340 D BtGatt.ScanManager: delete FilterIndex - 8
,09-06 19:10:03.802  3204  3219 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:10:03.802  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-06 19:10:03.802  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:10:03.802  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:10:03.802  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:10:03.802  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 19:10:03.802  3204  3282 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-06 19:10:03.802  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.802  3204  3340 D BtGatt.ScanManager: stopping BLe Batch
09-06 19:10:03.802  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:10:03.802  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:10:03.802  6822  7033 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:10:03.802  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:10:03.802  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:03.802  6822  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:10:03.802  6822  6822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:10:03.802  6822  6822 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:10:03.802  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:03.802  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:10:03.802  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.802  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d653c36 removed from the list
09-06 19:10:03.802  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:03.802  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.802  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:03.802  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:03.802  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab3f9d1 removed from the list
09-06 19:10:03.802  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:10:03.802  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40e5c2 added. We now have 2 listener(s)
09-06 19:10:03.802  3204  3282 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-06 19:10:03.802  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.802  3204  3340 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-06 19:10:03.812  3204  3282 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 19:10:03.812  3204  3282 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.812  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-06 19:10:03.812  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:10:03.812  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:10:03.812  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:10:03.812  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17af1fd3 added. We now have 9 listener(s)
09-06 19:10:03.812  6822  7033 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:10:03.812  1003  1127 E WifiNative-wlan0: do suspend true
09-06 19:10:03.812  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:10:03.812  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:10:03.812  6822  7033 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:10:03.812  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:03.812  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:03.812  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:03.812  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:03.812  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:03.812  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:03.812  6822  7033 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:10:03.822  6822  7033 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:10:03.822  6822  7033 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:10:03.822  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:10:03.822  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d5b1209 added. We now have 3 listener(s)
09-06 19:10:03.822  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:10:03.822  6822  6822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:10:03.822  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-06 19:10:03.822  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:10:03.822  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:10:03.822  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:10:03.822  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3b9c0e added. We now have 10 listener(s)
09-06 19:10:03.822  6822  7033 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:10:03.822  6822  7033 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:10:03.822  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:10:03.832  6822  7033 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:10:03.832  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:10:03.832  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.832  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:10:03.832  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:03.832  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40e5c2 removed from the list
09-06 19:10:03.832  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.832  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17af1fd3 removed from the list
09-06 19:10:03.832  6822  7033 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:10:03.832  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:03.832  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.832  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:03.832  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:10:03.832  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:03.832  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.832  6822  7033 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17af1fd3 not in the list
09-06 19:10:03.832  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.832  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:03.832  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:03.832  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:10:03.832  6822  7033 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.832  6822  7033 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3b9c0e removed from the list
09-06 19:10:03.832  6822  7033 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:03.832  6822  7033 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.832  6822  7033 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:03.832  6822  7033 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:03.832  6822  7033 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d5b1209 removed from the list
,09-06 19:10:03.832  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-06 19:10:03.832  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-06 19:10:03.832  1003  1126 D WifiP2pService: InactiveState{ what=143375 }
09-06 19:10:03.832  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-06 19:10:03.832  1003  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-06 19:10:03.832  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:10:03.832  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-06 19:10:03.832  6822  7033 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:10:03.842  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-06 19:10:03.842  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:10:03.842  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:10:03.842  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:03.842  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:03.842  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.842  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:03.842  1003  1127 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,09-06 19:10:03.842  1003  1127 E WifiStateMachine: VerifyingLinkState enter
,09-06 19:10:03.852  1003  1129 E ConnectivityService: updateNetworkInfo()
,09-06 19:10:03.852  1003  1129 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,09-06 19:10:03.852  1003  1129 D ConnectivityService: Adding iface wlan0 to network 504
,09-06 19:10:03.862  6822  7725 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1389, name: My test thread name)
,09-06 19:10:03.862  6822  7725 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1389, thread name: My test thread name)
09-06 19:10:03.862  6822  7725 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1389, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-06 19:10:03.862  6822  7727 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1391, name: My test thread name)
09-06 19:10:03.862  6822  7727 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1391, thread name: My test thread name)
09-06 19:10:03.862  6822  7727 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1391, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-06 19:10:03.862  6822  7033 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80,
09-06 19:10:03.862  6822  7033 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-06 19:10:03.862  6822  7033 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0,
09-06 19:10:03.862  6822  7033 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-06 19:10:03.862  6822  7033 D com.test.thalitest.ThaliTestRunner: Total duration: 23245 ms
,09-06 19:10:03.872  1003  1146 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
09-06 19:10:03.872  1003  1146 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-06 19:10:03.872  1003  1146 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-06 19:10:03.872  1003  1146 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-06 19:10:03.872  1003  1146 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-06 19:10:03.872  6822  7033 I jxcore-log: *Native tests were executed*
09-06 19:10:03.872  6822  7033 I jxcore-log: 
09-06 19:10:03.872  6822  7033 I jxcore-log: Total number of executed tests:  80
09-06 19:10:03.872  6822  7033 I jxcore-log: 
,09-06 19:10:03.872  6822  7033 I jxcore-log: Number of passed tests:  80
09-06 19:10:03.872  6822  7033 I jxcore-log: 
09-06 19:10:03.872  6822  7033 I jxcore-log: Number of failed tests:  0
09-06 19:10:03.872  6822  7033 I jxcore-log: 
,09-06 19:10:03.872  6822  7033 I jxcore-log: Number of ignored tests:  0
09-06 19:10:03.872  6822  7033 I jxcore-log: 
,09-06 19:10:03.872  6822  7033 I jxcore-log: Total duration:  23245
09-06 19:10:03.872  6822  7033 I jxcore-log: 
09-06 19:10:03.872  6822  7033 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-06 19:10:03.872  6822  7033 I jxcore-log: 
09-06 19:10:03.872  1003  1129 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
09-06 19:10:03.882  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:03.882  6822  7033 I jxcore-log: 
09-06 19:10:03.882  1003  1129 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,09-06 19:10:03.882  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:03.882  6822  7033 I jxcore-log: 
09-06 19:10:03.882  1003  1129 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
09-06 19:10:03.882  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:03.882  6822  7033 I jxcore-log: 
09-06 19:10:03.882  1003  1129 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-06 19:10:03.882  1003  1129 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
09-06 19:10:03.882  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:03.882  6822  7033 I jxcore-log: 
09-06 19:10:03.882  1003  1129 D ConnectivityService: LTETest block dns file not exists
09-06 19:10:03.882  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:03.882  6822  7033 I jxcore-log: 
09-06 19:10:03.892  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:03.892  6822  7033 I jxcore-log: 
09-06 19:10:03.892  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:03.892  6822  7033 I jxcore-log: 
,09-06 19:10:03.892  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-06 19:10:03.892  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:10:03.892  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:10:03.892  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.892  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.892  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.892  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.892  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.892  6822  7033 I jxcore-log: 
09-06 19:10:03.892  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.892  6822  7033 I jxcore-log: 
,09-06 19:10:03.892  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:10:03.892  6822  7033 I jxcore-log: 
09-06 19:10:03.892  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:10:03.892  6822  7033 I jxcore-log: 
09-06 19:10:03.892  6822  6822 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-06 19:10:03.902  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:10:03.902  6822  7033 I jxcore-log: 
09-06 19:10:03.902  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.902  6822  7033 I jxcore-log: 
09-06 19:10:03.902  1003  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.902  1003  1129 V NetworkStats: updateIfacesLocked()
09-06 19:10:03.902  1003  1129 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:10:03.902  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.902  6822  7033 I jxcore-log: 
,09-06 19:10:03.902  1003  1481 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:10:03.902  1003  1481 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 19:10:03.902  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.902  6822  7033 I jxcore-log: 
,09-06 19:10:03.902  1003  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:10:03.902  1003  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:10:03.902  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.902  6822  7033 I jxcore-log: 
,09-06 19:10:03.902  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.902  6822  7033 I jxcore-log: 
,09-06 19:10:03.902  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.902  6822  7033 I jxcore-log: 
,09-06 19:10:03.912  1003  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.912  1003  1129 V NetworkStats: performPollLocked() took 6ms
09-06 19:10:03.912  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.912  6822  7033 I jxcore-log: 
,09-06 19:10:03.912  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.912  6822  7033 I jxcore-log: 
,09-06 19:10:03.912  1003  1481 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:03.912  1003  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:03.912  1003  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:10:03.912  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:10:03.912  6822  7033 I jxcore-log: 
,09-06 19:10:03.912  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:10:03.912  6822  7033 I jxcore-log: 
,09-06 19:10:03.912  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:10:03.912  6822  7033 I jxcore-log: 
09-06 19:10:03.912  1003  1129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,09-06 19:10:03.912  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:10:03.912  6822  7033 I jxcore-log: 
09-06 19:10:03.912  1611  1611 I Hs20UtilService: Starting #22
,09-06 19:10:03.912  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.912  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.912  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:10:03.912  6822  7033 I jxcore-log: 
,09-06 19:10:03.912  1611  1654 I Hs20UtilService: Message received 5007
09-06 19:10:03.912  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:10:03.912  6822  7033 I jxcore-log: 
09-06 19:10:03.912  1003  1127 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
09-06 19:10:03.912  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:10:03.912  6822  7033 I jxcore-log: 
,09-06 19:10:03.912  4809  4809 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 19:10:03.922  4809  4809 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-06 19:10:03.922  1003  1129 E ConnectivityService: updateNetworkInfo()
,09-06 19:10:03.922  1003  1129 E ConnectivityService: updateNetworkInfo()
09-06 19:10:03.922  1003  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-06 19:10:03.922  1003  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.922  1003  1129 V NetworkStats: updateIfacesLocked()
09-06 19:10:03.922  1003  1129 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:10:03.922  1003  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:10:03.922  1003  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:10:03.922  1003  1003 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-06 19:10:03.932  1003  1129 V NetworkStats: performPollLocked() took 3ms
09-06 19:10:03.932  1003  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:03.932  1003  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-06 19:10:03.932  1003  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-06 19:10:03.932  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-06 19:10:03.932  1180  1180 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:10:03.932  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-06 19:10:03.932  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:03.942  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.942  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.942  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:03.942  1003  1003 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-06 19:10:03.942  1003  1003 I WifiTrafficPoller: mBoosterFLAG : 0
09-06 19:10:03.942  1003  1003 I WifiTrafficPoller: current booster mode : FullMode
,09-06 19:10:03.942  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:10:03.952  1003  1129 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
09-06 19:10:03.942  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-06 19:10:03.952  1003  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-06 19:10:03.942  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.952  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.952  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.952  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.952  1003  7692 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:10:03.952  1003  7692 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-06 19:10:03.952  1003  7692 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:10:03.952  1003  7692 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
09-06 19:10:03.952  1003  7692 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 19:10:03.952  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.952  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:03.952  1003  1129 D ConnectivityService:    accepting network in place of null
,09-06 19:10:03.962  1003  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-06 19:10:03.962  1483  1483 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-06 19:10:03.962  1483  1483 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:10:03.962  1003  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-06 19:10:03.962  1003  1129 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1,
09-06 19:10:03.962  1003  1129 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
,09-06 19:10:03.962   278   901 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
09-06 19:10:03.962   278   901 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,09-06 19:10:03.962  1003  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-06 19:10:03.972  1003  1129 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,09-06 19:10:03.972  1003  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,09-06 19:10:03.972  1003  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-06 19:10:03.972  1003  1523 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:10:03.972  1003  1523 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:10:03.972  1003  1523 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:03.972  1003  1523 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:03.972  1003  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:10:03.972  1180  1681 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-06 19:10:03.982  1003  1003 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-06 19:10:03.982  1003  1132 D Tethering: MasterInitialState.processMessage what=3
,09-06 19:10:03.982  1611  1611 I Hs20UtilService: Starting #23
,09-06 19:10:03.982  1003  1124 V NetworkStats: updateIfacesLocked()
09-06 19:10:03.982  1003  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.982  1003  1124 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:10:03.982  1003  1124 D NetworkStatsFactory: UpdateStatsForKnox updated,
09-06 19:10:03.982  1003  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:10:03.982  1003  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:03.982  1003  1124 V NetworkStats: performPollLocked() took 4ms
09-06 19:10:03.982  1611  1654 I Hs20UtilService: Message received 5007
,09-06 19:10:03.982  1180  1180 D StatusBar.NetworkController: EthernetConnected: false
09-06 19:10:03.982  1180  1180 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-06 19:10:03.982  1180  1180 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-06 19:10:03.982  1180  1180 D StatusBar.NetworkController: updateDataNetType()
,09-06 19:10:03.992  4809  4809 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 19:10:03.992  1180  1180 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-06 19:10:03.992  1180  1180 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-06 19:10:03.992  4809  4809 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 19:10:03.992  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,09-06 19:10:03.992  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.992  1180  1180 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-06 19:10:03.992  1003  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-06 19:10:03.992  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 23 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-06 19:10:03.992  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.992  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.992  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
09-06 19:10:03.992  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.992  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-06 19:10:03.992  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.992  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
09-06 19:10:03.992  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:10:03.992  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,09-06 19:10:03.992  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.992  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.992  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.992  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.992  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:10:03.992  4809  4809 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
09-06 19:10:03.992  4809  4809 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-06 19:10:04.002  1003  1523 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:10:04.002  1003  1523 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:10:04.002  1003  1523 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:04.002  1003  1523 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:04.002  1003  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:10:04.002  1611  1611 I Hs20UtilService: Starting #24,
09-06 19:10:04.002  1611  1654 I Hs20UtilService: Message received 5007
09-06 19:10:04.002  4809  4809 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-06 19:10:04.012  4809  4809 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-06 19:10:04.012  1003  1733 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-06 19:10:04.012  1003  1518 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,09-06 19:10:04.012  1003  1518 D SecContentProvider2: mCursor = null
,09-06 19:10:04.022  1003  1512 D SecContentProvider2: uri = 15 selection = getToastGravity
09-06 19:10:04.022  1003  1512 D SecContentProvider2: mCursor = null
,09-06 19:10:04.022  1003  1523 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
09-06 19:10:04.022  1003  1523 D SecContentProvider2: mCursor = null
,09-06 19:10:04.022  1003  1223 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-06 19:10:04.022  1003  1223 D SecContentProvider2: mCursor = null
,09-06 19:10:04.022  1003  1030 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,09-06 19:10:04.022  1003  1030 D SecContentProvider2: mCursor = null
,09-06 19:10:04.022  1003  1029 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
09-06 19:10:04.022  1003  1029 D SecContentProvider2: mCursor = null
,09-06 19:10:04.032  6822  6822 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 19:10:04.042  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:10:04.042  6822  7033 I jxcore-log: 
,09-06 19:10:04.052   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,09-06 19:10:04.062  1003  1512 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1003
,09-06 19:10:04.062  1180  1180 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-06 19:10:04.152  7730  7730 D AndroidRuntime: 
09-06 19:10:04.152  7730  7730 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-06 19:10:04.152  7730  7730 D AndroidRuntime: CheckJNI is OFF,
09-06 19:10:04.152  7730  7730 D AndroidRuntime: readGMSProperty: start
09-06 19:10:04.152  7730  7730 D AndroidRuntime: readGMSProperty: already setted!!
09-06 19:10:04.152  7730  7730 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-06 19:10:04.152  7730  7730 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-06 19:10:04.152  7730  7730 D AndroidRuntime: readGMSProperty: end
,09-06 19:10:04.152  7730  7730 D AndroidRuntime: addProductProperty: start
,09-06 19:10:04.182  6822  6822 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-06 19:10:04.182  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:10:04.182  6822  7033 I jxcore-log: 
,09-06 19:10:04.302  6822  6822 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-06 19:10:04.302  6822  7033 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:10:04.302  6822  7033 I jxcore-log: 
,09-06 19:10:04.322  7730  7730 E AffinityControl: AffinityControl: registerfunction enter
,09-06 19:10:04.342  7730  7730 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-06 19:10:04.372  1003  1137 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
09-06 19:10:04.372  1003  1137 D PackageManager: START PACKAGE DELETE: observer{933984455}
09-06 19:10:04.372  1003  1137 D PackageManager: pkg{<packageName>}
09-06 19:10:04.372  1003  1137 D PackageManager: user{0}
09-06 19:10:04.372  1003  1137 D PackageManager: caller{2000},
09-06 19:10:04.372  1003  1137 D PackageManager: flags{2}
09-06 19:10:04.372  1003  1137 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-06 19:10:04.372  1003  1137 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true,
,09-06 19:10:04.372  1003  1137 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-06 19:10:04.372  1003  1137 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
,09-06 19:10:04.372  1003  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-06 19:10:04.372  1003  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-06 19:10:04.372  1003  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,09-06 19:10:04.372  1003  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
09-06 19:10:04.372  1003  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-06 19:10:04.382  1003  1058 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,09-06 19:10:04.392  1003  1043 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,09-06 19:10:04.392  1003  1043 I ActivityManager: Killing 6822:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-06 19:10:04.472  1003  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:10:04.492  1003  1481 I WindowState: WIN DEATH: Window{1f5a5f29 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-06 19:10:04.492   258  1098 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,09-06 19:10:04.502  1003  1043 I ActivityManager:   Force finishing activity ActivityRecord{ca61c13 u0 com.test.thalitest/.MainActivity t163}
,09-06 19:10:04.502   258   451 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,09-06 19:10:04.502  1003  1481 D InputDispatcher: Focus left window: 6822
,09-06 19:10:04.522  1003  1512 W ActivityManager: Spurious death for ProcessRecord{23b93ef4 6822:com.test.thalitest/u0a170}, curProc for 6822: null
09-06 19:10:04.522  1003  1058 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
09-06 19:10:04.522  1003  1058 I ActivityManager:   Force finishing activity ActivityRecord{ca61c13 u0 com.test.thalitest/.MainActivity t163 f}
09-06 19:10:04.522  1003  1058 W ActivityManager: Duplicate finish request for ActivityRecord{ca61c13 u0 com.test.thalitest/.MainActivity t163 f},
,09-06 19:10:04.532  1003  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-06 19:10:04.532  1003  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 19:10:04.542  1003  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-06 19:10:04.562  1003  1043 D InputDispatcher: Focused application released,
,09-06 19:10:04.562  1003  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:10:04.572  2821  2821 I art     : Explicit concurrent mark sweep GC freed 16608(991KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 783us total 31.520ms
,09-06 19:10:04.602  1995  1995 E SamsungIME: mOCRHelper is null
,09-06 19:10:04.612  1752  1977 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-06 19:10:04.612  1003  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-06 19:10:04.612  1003  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-06 19:10:04.622  1003  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:04.622  1003  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:04.622  1003  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:04.622  1003  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:10:04.632  7743  7743 E Zygote  : MountEmulatedStorage()
09-06 19:10:04.632  7743  7743 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:10:04.632  7743  7743 E Zygote  : v2
09-06 19:10:04.632  7743  7743 I libpersona: KNOX_SDCARD not a persona
09-06 19:10:04.632  1003  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
09-06 19:10:04.632  1003  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-06 19:10:04.632  1003  1043 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7743 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-06 19:10:04.632  1003  1042 W TextServicesManagerService: no available spell checker services found
,09-06 19:10:04.642  7743  7743 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-06 19:10:04.642  7743  7743 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 19:10:04.642  7743  7743 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:10:04.662  1467  1467 D PersonaManager: isKioskContainerExistOnDevice
,09-06 19:10:04.672  1467  1467 D RegisteredServicesCache: empty dynamic service
,09-06 19:10:04.672  1003  1124 V NetworkStats: removeUidsLocked() for UIDs [10170]
09-06 19:10:04.672  1003  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:04.672  1003  1124 V NetworkStats: performPollLocked(flags=0x3)
,09-06 19:10:04.682  1003  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:10:04.682  1003  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:10:04.692  1003  1124 V NetworkStats: performPollLocked() took 12ms
09-06 19:10:04.692  1003  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:04.692  1003  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:04.692  1467  1467 D RegisteredComponentCache: Collect Tech packages for Knox
,09-06 19:10:04.692  1467  1467 D PersonaManager: isKioskContainerExistOnDevice
,09-06 19:10:04.702  7743  7743 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:10:04.702  7743  7743 D ActivityThread: Added TimaKeyStore provider
,09-06 19:10:04.702  1003  1003 D RCPManagerService: PackageReceiver onReceive()
,09-06 19:10:04.702  1003  1003 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-06 19:10:04.712  1003  1003 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,09-06 19:10:04.712  1003  1129 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-06 19:10:04.712  1003  1003 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-06 19:10:04.712  1003  1003 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,09-06 19:10:04.722  1003  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:04.732  1003  1003 I OTPFW   : ProvisionData::getAllEntries Enter
,09-06 19:10:04.732  1003  1003 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-06 19:10:04.742  1003  1496 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,09-06 19:10:04.742  1003  1496 D SecContentProvider2: mCursor = null
,09-06 19:10:04.752  1003  1129 V NetworkStats: updateIfacesLocked()
09-06 19:10:04.752  1003  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:04.752  1003  1129 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:10:04.752  1003  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:10:04.752  1003  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:10:04.762  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:04.762  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:04.762  1003  1129 V NetworkStats: performPollLocked() took 13ms
09-06 19:10:04.762  1003  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:04.762  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:04.762  1003  1129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,09-06 19:10:04.772  1003  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:04.772  1003  1129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,09-06 19:10:04.772  1180  1681 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-06 19:10:04.772  1180  1681 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-06 19:10:04.772  1003  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:04.772  7743  7743 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-06 19:10:04.772  7743  7743 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-06 19:10:04.772  7743  7743 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-06 19:10:04.792  1003  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:04.792  7743  7743 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-06 19:10:04.792  7743  7743 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-06 19:10:04.792  7743  7743 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-06 19:10:04.792  7743  7743 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:10:04.802  1003  1479 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
09-06 19:10:04.802  1003  1479 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
09-06 19:10:04.802  1003  1479 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
09-06 19:10:04.802  1003  1479 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,09-06 19:10:04.802  1003  1479 I ActivityManager: Killing 7233:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,09-06 19:10:04.852  1003  1058 I art     : Explicit concurrent mark sweep GC freed 72551(4MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 23MB/34MB, paused 2.953ms total 216.017ms
,09-06 19:10:04.862  1003  1017 I art     : WaitForGcToComplete blocked for 211.478ms for cause HeapTrim
,09-06 19:10:04.892  1003  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-06 19:10:04.902  1003  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:04.912  1003  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:04.922   291   291 E SMD     : DCD OFF
,09-06 19:10:04.932  1003  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:04.942  1003  1058 D PackageManager: delete codoeFile: 
,09-06 19:10:04.942  1003  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-06 19:10:04.942  1003  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:10:04.942  1003  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-06 19:10:04.952  1003  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:04.952  1003  1058 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
,09-06 19:10:04.952  1003  1058 I AASA_removePackage: UID=10170 Target=com.test.thalitest
09-06 19:10:04.952  1003  1058 D PackageManager: result of delete: 1{933984455}
,09-06 19:10:04.962  7730  7730 D AndroidRuntime: Shutting down VM
,09-06 19:10:04.962  1003  1003 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-06 19:10:04.962  1003  1003 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-06 19:10:04.962  1003  1003 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-06 19:10:04.962  1003  1003 V EnterpriseBillingPolicy: uID is 10170
09-06 19:10:04.962  1003  1003 V EnterpriseBillingPolicy: Removed Packageuid is0
09-06 19:10:04.962  1003  1003 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-06 19:10:04.962  1003  1003 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-06 19:10:04.962  1003  1003 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-06 19:10:04.962  1003  1003 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-06 19:10:04.962  1003  1003 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-06 19:10:04.972  1003  1003 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-06 19:10:04.972  1003  1003 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-06 19:10:04.972  1003  1003 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-06 19:10:04.972  1003  1003 V EnterpriseBillingPolicy: uID is 10170
09-06 19:10:04.972  1003  1163 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
09-06 19:10:04.972  1003  1003 V EnterpriseBillingPolicy: Removed Packageuid is0
09-06 19:10:04.972  1003  1003 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-06 19:10:04.972  1003  1003 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-06 19:10:04.972  1003  1003 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-06 19:10:04.972  1003  1003 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-06 19:10:04.972  1003  1003 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-06 19:10:04.972  1003  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 19:10:04.972  1003  1003 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-06 19:10:04.972  1003  3354 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-06 19:10:04.972  1003  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-06 19:10:04.972  1003  1058 D PackageManager: userId{-1}
09-06 19:10:04.972  1003  1058 D PackageManager: andCode{true},
09-06 19:10:04.972  1003  1003 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
09-06 19:10:04.972  1003  1129 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-06 19:10:04.982  1003  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-06 19:10:04.982  1003  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:04.982  1003  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:04.982  1003  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:04.982  1003  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:04.982  1003  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:10:04.992  1003  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:04.992  7760  7760 I libpersona: KNOX_SDCARD checking this for 10003
09-06 19:10:04.992  1003  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
09-06 19:10:04.992  7760  7760 I libpersona: KNOX_SDCARD not a persona
09-06 19:10:04.992  7760  7760 E Zygote  : MountEmulatedStorage()
09-06 19:10:04.992  1003  1058 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7760 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-06 19:10:04.992  7760  7760 E Zygote  : v2
09-06 19:10:04.992  7760  7760 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:10:04.992  1003  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:05.002  7760  7760 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-06 19:10:05.002  1003  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 19:10:05.002  1003  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-06 19:10:05.002  7760  7760 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:10:05.002  1003  1096 V AlarmManager: waitForAlarm result :4
,09-06 19:10:05.002  1003  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 19:10:05.002  1003  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-06 19:10:05.002  1003  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:05.012  1003  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
,09-06 19:10:05.012  1003  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-06 19:10:05.022  7760  7760 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:10:05.022  7760  7760 D ActivityThread: Added TimaKeyStore provider
,09-06 19:10:05.052  1003  1030 I ActivityManager: Killing 7251:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,09-06 19:10:05.082  1003  1003 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,09-06 19:10:05.082  1003  1003 V AlarmManagerEXT: <AppSync3 Whitelist>
,09-06 19:10:05.082  1003  1003 V AlarmManagerEXT: (AppSync) ### 0 added ###
,09-06 19:10:05.082  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-06 19:10:05.082  1180  1180 D KeyguardUpdateMonitor: handleTimeUpdate
,09-06 19:10:05.082  1003  1003 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-06 19:10:05.092  1180  1180 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-06 19:10:05.092  1003  1003 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:05.092  1003  1003 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:10:05.092  1003  1003 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:05.092  1003  1003 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:10:05.092  1180  1180 D SecKeyguardClockView: HomeTimezone(): 1,
,09-06 19:10:05.092  1180  1180 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-06 19:10:05.102  7776  7776 E Zygote  : MountEmulatedStorage()
,09-06 19:10:05.102  7776  7776 E Zygote  : v2
09-06 19:10:05.102  7776  7776 I libpersona: KNOX_SDCARD checking this for 10001
09-06 19:10:05.102  7776  7776 I libpersona: KNOX_SDCARD not a persona
,09-06 19:10:05.102  1003  1003 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7776 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:10:05.102  7776  7776 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-06 19:10:05.112  1180  1180 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
09-06 19:10:05.112  1180  1180 I KeyguardEffectViewController: *** don't update sliding image ***
,09-06 19:10:05.112  7776  7776 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:10:05.112  7776  7776 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-06 19:10:05.132  7776  7776 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:10:05.132  7776  7776 D ActivityThread: Added TimaKeyStore provider
,09-06 19:10:05.142  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-06 19:10:05.142  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-06 19:10:05.142  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-06 19:10:05.152  1180  1180 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,09-06 19:10:05.172  1180  1180 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,09-06 19:10:05.182  7730  7730 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-06 19:10:05.202  1003  1518 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-06 19:10:05.202  1003  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:05.202  1003  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:05.202  1003  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:05.202  1003  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:10:05.222  1003  1518 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7795 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-06 19:10:05.222  7795  7795 E Zygote  : MountEmulatedStorage()
09-06 19:10:05.222  7795  7795 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:10:05.222  7795  7795 E Zygote  : v2
09-06 19:10:05.222  7795  7795 I libpersona: KNOX_SDCARD not a persona
,09-06 19:10:05.222  7795  7795 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 19:10:05.222  1003  1518 I ActivityManager: Killing 7268:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,09-06 19:10:05.222  7795  7795 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 19:10:05.222  7795  7795 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:10:05.242   312   312 I art     : Explicit concurrent mark sweep GC freed 8705(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 788us total 28.618ms
,09-06 19:10:05.252  7795  7795 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-06 19:10:05.252  7795  7795 D ActivityThread: Added TimaKeyStore provider
,09-06 19:10:05.262   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 709us total 20.008ms
,09-06 19:10:05.292   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 689us total 19.529ms
,09-06 19:10:05.312  7795  7795 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-06 19:10:05.312  7795  7795 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
,09-06 19:10:05.312  7795  7795 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:10:05.312  7795  7795 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:10:05.312  7795  7795 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-06 19:10:05.322  7795  7795 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
,09-06 19:10:05.322  7795  7795 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
,09-06 19:10:05.322  7795  7795 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-06 19:10:05.322  7795  7795 E, SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
,09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:10:05.322  7795  7795 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
,09-06 19:10:05.322  7795  7795 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
,09-06 19:10:05.322  7795  7795 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.,
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
,09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:10:05.322  7795  7795 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
,09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55),
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	,at java.lang.reflect.Method.invoke(Native Method)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:10:05.322  7795  7795 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:10:05.332  7795  7795 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
,09-06 19:10:05.332  7795  7795 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method),
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223),
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	,at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	,at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
,09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: ,	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-06 19:10:05.332  7795  7795 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
09-06 19:10:05.332  7795  7795 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	,at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699),
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-06 19:10:05.332  7795  7795 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
09-06 19:10:05.332  7795  7795 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878),
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:10:05.332  7795  7795 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:10:05.332  7795  7795 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-06 19:10:05.342  7795  7795 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
09-06 19:10:05.342  7795  7795 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:10:05.342  7795  7795 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
09-06 19:10:05.342  7795  7795 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:10:05.342  7795  7795 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
09-06 19:10:05.342  7795  7795 E SQLiteOpenHelper: 	
```
