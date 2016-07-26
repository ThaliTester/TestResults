#### Test 757892686f45c73_thali01_samsung-SM-A300FU Logs


```
--------- beginning of main
07-26 15:20:54.171  6467  6467 E Mms/MessageUtils: setCountryDetector : update country detector info 
07-26 15:20:54.171  6467  6467 E Mms/MessageUtils: updateCountryIso : update country iso info 
07-26 15:20:54.171  6467  6467 D Mms/MmsConfig: [end]    init() consume time = 197.251718
07-26 15:20:54.181  6467  6467 D Mms/Contact: [start]    init() consume time = 1.170781
07-26 15:20:54.181  6348  6394 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 696 ms] updated apps [took 696 ms] 
--------- beginning of system
07-26 15:20:54.181  1017  1545 I ActivityManager: Killing 5722:com.google.android.music:main/u0a108 (adj 15): empty #21
07-26 15:20:54.201  1480  1717 D TP/MmsSmsProvider: query,matched:13, calling pid = 6467
07-26 15:20:54.201  1480  1717 D TP/MmsSmsProvider: match 13:Elapsed time : 0.971 ms
07-26 15:20:54.201  1017  1546 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
07-26 15:20:54.201  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:54.201  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:54.201  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:54.201  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:54.211  6467  6467 D Mms/Contact: [end]    init consume time = 30.068855
07-26 15:20:54.221  6578  6578 E Zygote  : MountEmulatedStorage()
07-26 15:20:54.221  6578  6578 E Zygote  : v2
07-26 15:20:54.221  6578  6578 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-26 15:20:54.221  6467  6577 D Mms/DraftCache: [start]    rebuildCache consume time = 14.477656
07-26 15:20:54.221  6578  6578 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-26 15:20:54.221  6578  6578 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-26 15:20:54.221  6578  6578 I libpersona: KNOX_SDCARD checking this for 10152
07-26 15:20:54.221  6578  6578 I libpersona: KNOX_SDCARD not a persona
07-26 15:20:54.231  1017  1546 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=6578 uid=10152 gids={50152, 9997} abi=armeabi-v7a
07-26 15:20:54.231  1017  1546 I ActivityManager: Killing 5858:com.sec.android.app.videoplayer/u0a45 (adj 15): empty #21
07-26 15:20:54.241  1480  1492 D TP/MmsSmsProvider: query,matched:12, calling pid = 6467
07-26 15:20:54.241  1480  1492 D TP/MmsSmsProvider: match 12:Elapsed time : 1.301 ms
07-26 15:20:54.241  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:54.241  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:20:54.241  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
07-26 15:20:54.241  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
07-26 15:20:54.241  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
07-26 15:20:54.241  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:54.241  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:54.241  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:54.241  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:54.251  6467  6467 D Mms/MethodReflector: getSubId is called
07-26 15:20:54.251  6467  6467 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
07-26 15:20:54.251  6467  6467 D Mms/MethodReflector: getTelephonyProperty is called
07-26 15:20:54.251  6467  6467 D Mms/DownloadManager: roaming -> false (slotId = 0)
07-26 15:20:54.251  6467  6467 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
07-26 15:20:54.251  6467  6467 D Mms/DownloadManager: auto download without roaming -> true
07-26 15:20:54.251  6467  6467 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
07-26 15:20:54.251  6467  6467 D Mms/MethodReflector: getSubId is called
07-26 15:20:54.251  6467  6467 D Mms/MethodReflector: getDefaultSmsSubId is called
07-26 15:20:54.251  6467  6467 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
07-26 15:20:54.251  6467  6467 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
07-26 15:20:54.251  6467  6467 D Mms/MethodReflector: getTelephonyProperty is called
07-26 15:20:54.251  6467  6467 D Mms/DownloadManager: roaming -> false (slotId = 1)
07-26 15:20:54.251  6467  6467 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
07-26 15:20:54.251  6467  6467 D Mms/DownloadManager: auto download without roaming -> true
07-26 15:20:54.251  6467  6467 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
07-26 15:20:54.251  6467  6467 D Mms/DownloadManager: auto download during roaming secondary -> false
07-26 15:20:54.251  6467  6467 D Mms/DownloadManager: mAutoDownload ------> true
07-26 15:20:54.261  6595  6595 E Zygote  : MountEmulatedStorage()
07-26 15:20:54.261  6595  6595 I libpersona: KNOX_SDCARD checking this for 10029
07-26 15:20:54.261  6595  6595 E Zygote  : v2
07-26 15:20:54.261  6595  6595 I libpersona: KNOX_SDCARD not a persona
07-26 15:20:54.261  6595  6595 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-26 15:20:54.271  1017  1030 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder:tagService for service com.samsung.android.app.galaxyfinder/.tag.TagReadyService: pid=6595 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
07-26 15:20:54.271  6595  6595 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-26 15:20:54.271  6595  6595 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-26 15:20:54.271  6467  6577 D Mms/DraftCache: [end]    rebuildCache consume time = 54.288333
07-26 15:20:54.291  6578  6578 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 15:20:54.291  6578  6578 D ActivityThread: Added TimaKeyStore provider
07-26 15:20:54.301  6595  6595 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 15:20:54.301  6595  6595 D ActivityThread: Added TimaKeyStore provider
07-26 15:20:54.321  1017  1248 I art     : Explicit concurrent mark sweep GC freed 128001(7MB) AllocSpace objects, 3(1591KB) LOS objects, 33% free, 22MB/34MB, paused 3.123ms total 172.898ms
07-26 15:20:54.351  6578  6578 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
07-26 15:20:54.351  6578  6578 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
07-26 15:20:54.361  6578  6578 I TapandpayWidget:Utils: Clear T&P info.
07-26 15:20:54.371  6467  6467 D ComposerPerformance: 1469539254382 ms / [DONE] Composer constructor
07-26 15:20:54.371  6467  6536 W art     : Verification of int com.android.mms.util.HandleComposerAttachment.getAvailableSlideCount(int) took 115.245ms
07-26 15:20:54.371  6467  6467 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
07-26 15:20:54.371  6467  6467 I Mms/ReservationManager: ReservationManager()
07-26 15:20:54.371  6467  6467 I Mms/ReservationManager: resetAfterConnected()
07-26 15:20:54.381  1480  2522 D TP/MmsSmsProvider: query,matched:7, calling pid = 6467
07-26 15:20:54.381  1480  2522 D TP/MmsSmsProvider: match 7:Elapsed time : 1.765 ms
07-26 15:20:54.381  6467  6614 D Mms/Conversation: [start]    init() consume time = 109.614844
07-26 15:20:54.391  6467  6467 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
07-26 15:20:54.391  6578  6578 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
07-26 15:20:54.391  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
07-26 15:20:54.391  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:54.391  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:54.391  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:54.391  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:54.401  6467  6467 D Mms/MmsApp: [end]    onCreate() consume time = 13.582344
07-26 15:20:54.411  6619  6619 E Zygote  : MountEmulatedStorage()
07-26 15:20:54.411  6619  6619 E Zygote  : v2
07-26 15:20:54.411  6619  6619 I libpersona: KNOX_SDCARD checking this for 10009
07-26 15:20:54.411  6619  6619 I libpersona: KNOX_SDCARD not a persona
07-26 15:20:54.411  6619  6619 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-26 15:20:54.411  6619  6619 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-26 15:20:54.421  1017  1030 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=6619 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
07-26 15:20:54.421  6619  6619 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
07-26 15:20:54.421  6467  6467 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
07-26 15:20:54.421  6467  6467 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
07-26 15:20:54.421  6467  6467 D Mms/MethodReflector: getSubId is called
07-26 15:20:54.421  1017  1030 I ActivityManager: Killing 5337:com.android.calendar/u0a131 (adj 15): empty #21
07-26 15:20:54.421  6467  6467 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
07-26 15:20:54.421  6467  6467 D Mms/MethodReflector: getTelephonyProperty is called
07-26 15:20:54.421  6467  6467 D Mms/DownloadManager: roaming -> false (slotId = 0)
07-26 15:20:54.421  6467  6467 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
07-26 15:20:54.431  1480  1492 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
07-26 15:20:54.431  6467  6467 D Mms/DownloadManager: auto download without roaming -> true
07-26 15:20:54.431  6467  6467 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
07-26 15:20:54.431  6467  6467 D Mms/DownloadManager: mAutoDownload ------> true
07-26 15:20:54.431  1480  1492 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
07-26 15:20:54.431  1480  1492 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
07-26 15:20:54.441  1480  1492 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
07-26 15:20:54.451  1480  1492 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
07-26 15:20:54.451  1480  1492 D TP/MmsSmsProvider: need read changed broadcast:false
07-26 15:20:54.451  6619  6619 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 15:20:54.451  6619  6619 D ActivityThread: Added TimaKeyStore provider
07-26 15:20:54.461  6467  6614 D Mms/Conversation: [end]    init consume time = 57.657031
07-26 15:20:54.461  6467  6467 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
07-26 15:20:54.461  6467  6614 D Mms/MessagingNotification: [start]    init() consume time = 2.701562
07-26 15:20:54.461  1017  4272 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
07-26 15:20:54.461  1017  4272 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
07-26 15:20:54.461  1017  4272 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:54.471  1017  4272 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:20:54.471  1017  4272 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
07-26 15:20:54.471  6467  6614 D Mms/MessagingNotification: [end]    init consume time = 12.475417
07-26 15:20:54.471  1017  1503 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
07-26 15:20:54.471  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:54.471  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:54.471  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:54.471  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:54.481  6467  6636 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 10.263125
07-26 15:20:54.481  6467  6637 D Mms/Synchronizer: [start]    doSync consume time = 3.157083
07-26 15:20:54.491  6638  6638 E Zygote  : MountEmulatedStorage()
07-26 15:20:54.491  6638  6638 I libpersona: KNOX_SDCARD checking this for 10042
07-26 15:20:54.491  6638  6638 E Zygote  : v2
07-26 15:20:54.491  6638  6638 I libpersona: KNOX_SDCARD not a persona
07-26 15:20:54.491  6638  6638 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-26 15:20:54.491  6638  6638 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-26 15:20:54.491  1017  1503 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6638 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
07-26 15:20:54.491  6638  6638 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
07-26 15:20:54.511  1480  2522 D TP/MmsSmsProvider: query,matched:0, calling pid = 6467
07-26 15:20:54.511  1480  2522 V TP/MmsSmsProvider: getSimpleConversations entered.
07-26 15:20:54.511  1480  2522 D TP/MmsSmsProvider: match 0:Elapsed time : 1.903 ms
07-26 15:20:54.511  1480  2520 D TP/MmsSmsProvider: query,matched:400, calling pid = 6467
07-26 15:20:54.511  3509  6433 W art     : Verification of com.google.android.gms.common.api.GoogleApiClient com.google.android.gms.games.broker.PlayerAgent.getConnectedPeopleClient(com.google.android.gms.games.broker.GamesClientContext) took 172.623ms
07-26 15:20:54.521  6638  6638 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 15:20:54.521  6638  6638 D ActivityThread: Added TimaKeyStore provider
07-26 15:20:54.531  6467  6636 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 41.860677
07-26 15:20:54.531  1480  1492 D TP/MmsSmsProvider: update, matched:300, calling pid = 6467
07-26 15:20:54.531  1480  1492 V TP/MmsSmsProvider: syncDBData start
07-26 15:20:54.531  1017  1546 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
07-26 15:20:54.531  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:54.531  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:54.531  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:54.531  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:54.531  1480  1492 V TP/MmsSmsProvider: syncDBData sms end
07-26 15:20:54.531  1480  1492 V TP/MmsSmsProvider: syncDBData mms end
07-26 15:20:54.531  1480  1492 V TP/MmsSmsProvider: syncDBData end
07-26 15:20:54.551  6657  6657 E Zygote  : MountEmulatedStorage()
07-26 15:20:54.551  6657  6657 E Zygote  : v2
07-26 15:20:54.551  6657  6657 I libpersona: KNOX_SDCARD checking this for 10068
07-26 15:20:54.551  6657  6657 I libpersona: KNOX_SDCARD not a persona
07-26 15:20:54.551  6657  6657 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-26 15:20:54.551  6657  6657 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-26 15:20:54.551  6467  6656 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
07-26 15:20:54.551  6467  6656 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
07-26 15:20:54.551  6638  6638 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-26 15:20:54.551  6638  6638 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-26 15:20:54.551  6638  6638 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
07-26 15:20:54.561  6657  6657 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
07-26 15:20:54.561  1017  1546 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6657 uid=10068 gids={50068, 9997} abi=armeabi-v7a
07-26 15:20:54.561  6467  6637 D Mms/Synchronizer: [end]    doSync consume time = 33.866094
07-26 15:20:54.561  1017  1333 I ActivityManager: Killing 6214:com.google.android.gms:car/u0a11 (adj 15): empty #21
07-26 15:20:54.581  6657  6657 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 15:20:54.591  6657  6657 D ActivityThread: Added TimaKeyStore provider
07-26 15:20:54.591  1017  3164 I ActivityManager: Killing 6165:com.android.defcontainer/u0a3 (adj 15): empty #21
07-26 15:20:54.631  6657  6657 D BadgeProvider: onCreate
07-26 15:20:54.631  6657  6657 D BadgeProvider: DatabaseHelper
07-26 15:20:54.631  6467  6536 W art     : Verification of void com.android.mms.util.HandleComposerAttachment.processingActivityResult(int, int, android.content.Intent) took 138.267ms
07-26 15:20:54.641  1017  3164 I ActivityManager: Killing 6267:com.sec.spp.push/u0a32 (adj 15): empty #21
07-26 15:20:54.661  6467  6614 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
07-26 15:20:54.681  1480  2522 D TP/SmsProvider: query,matched:26, calling pid = 6467
07-26 15:20:54.681  1480  2522 D TP/SmsProvider: match 26:Elapsed time : 1.104 ms
07-26 15:20:54.691  6467  6536 D Mms/ArtClassLoader: init [DONE] art
07-26 15:20:54.701  1480  1717 D TP/MmsSmsProvider: query,matched:6, calling pid = 6467
07-26 15:20:54.701  1480  1717 D TP/MmsSmsProvider: match 6:Elapsed time : 1.620 ms
07-26 15:20:54.721  6638  6638 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
07-26 15:20:54.731  1017  1030 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
07-26 15:20:54.731  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:54.731  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:54.731  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:54.731  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:54.761  6676  6676 E Zygote  : MountEmulatedStorage()
07-26 15:20:54.761  1017  1030 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6676 uid=10023 gids={50023, 9997} abi=armeabi-v7a
07-26 15:20:54.761  6676  6676 E Zygote  : v2
07-26 15:20:54.761  1017  1216 I ActivityManager: Killing 6282:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
07-26 15:20:54.761  6676  6676 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-26 15:20:54.761  6676  6676 I libpersona: KNOX_SDCARD checking this for 10023
07-26 15:20:54.761  6676  6676 I libpersona: KNOX_SDCARD not a persona
07-26 15:20:54.761  1017  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
07-26 15:20:54.761  1017  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
07-26 15:20:54.761  1017  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:54.761  6676  6676 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-26 15:20:54.761  1017  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:54.761  1017  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:54.761  1017  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:54.761  6676  6676 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-26 15:20:54.781  1017  1058 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6691 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
07-26 15:20:54.781  6676  6676 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 15:20:54.781  6676  6676 D ActivityThread: Added TimaKeyStore provider
07-26 15:20:54.791  6691  6691 E Zygote  : MountEmulatedStorage()
07-26 15:20:54.791  6691  6691 E Zygote  : v2
07-26 15:20:54.791  6691  6691 I libpersona: KNOX_SDCARD checking this for 10003
07-26 15:20:54.791  6691  6691 I libpersona: KNOX_SDCARD not a persona
07-26 15:20:54.791  6691  6691 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-26 15:20:54.791  1017  1546 I ActivityManager: Killing 6297:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
07-26 15:20:54.791  6691  6691 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-26 15:20:54.791  6691  6691 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-26 15:20:54.821   316   316 I art     : Explicit concurrent mark sweep GC freed 8690(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 610us total 41.660ms
07-26 15:20:54.831  6691  6691 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 15:20:54.831  6691  6691 D ActivityThread: Added TimaKeyStore provider
07-26 15:20:54.851   316   316 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 731us total 21.783ms
07-26 15:20:54.861   290   290 E installd: system dir 0 : /system/app/
07-26 15:20:54.861   290   290 E installd: system dir 1 : /system/priv-app/
07-26 15:20:54.861   290   290 E installd: system dir 2 : /vendor/app/
07-26 15:20:54.861   290   290 E installd: system dir 3 : /oem/app/
07-26 15:20:54.861  6676  6676 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
07-26 15:20:54.871   316   316 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 648us total 19.291ms
07-26 15:20:54.881  6467  6614 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
07-26 15:20:54.891  1017  1058 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
07-26 15:20:54.901  6676  6676 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
07-26 15:20:54.901  6676  6676 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
07-26 15:20:54.901  6676  6676 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
07-26 15:20:54.911  6676  6676 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
07-26 15:20:54.911  6676  6676 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
07-26 15:20:54.911  6676  6676 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
07-26 15:20:54.911  6676  6676 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
07-26 15:20:54.911  6676  6676 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
07-26 15:20:54.911  6676  6676 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
07-26 15:20:54.911  6676  6676 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
07-26 15:20:54.911  6676  6676 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
07-26 15:20:54.921  6676  6676 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
07-26 15:20:54.921  6676  6676 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
07-26 15:20:55.081  6492  6492 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-26 15:20:55.141  3509  4193 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
07-26 15:20:55.171  3509  4193 D Icing   : Loaded CLD2 Version V2.0 - 20141016
07-26 15:20:55.211  1017  1504 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
07-26 15:20:55.211  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:55.211  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:55.211  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:55.211  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:55.231  6719  6719 E Zygote  : MountEmulatedStorage()
07-26 15:20:55.231  6719  6719 E Zygote  : v2
07-26 15:20:55.231  6719  6719 I libpersona: KNOX_SDCARD checking this for 1000
07-26 15:20:55.231  6719  6719 I libpersona: KNOX_SDCARD not a persona
07-26 15:20:55.231  6719  6719 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-26 15:20:55.231  1017  1504 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=6719 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-26 15:20:55.231  6719  6719 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-26 15:20:55.231  6719  6719 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-26 15:20:55.241  1017  1216 D ActivityManager: startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
07-26 15:20:55.241  1017  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
07-26 15:20:55.241  1017  1216 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:55.241  1017  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-26 15:20:55.241  1017  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
07-26 15:20:55.251  6492  6492 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
07-26 15:20:55.261  6719  6719 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 15:20:55.261  6719  6719 D ActivityThread: Added TimaKeyStore provider
07-26 15:20:55.271  3509  4193 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
07-26 15:20:55.291  1017  3164 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
07-26 15:20:55.291  6719  6719 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
07-26 15:20:55.291  1017  3164 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:55.291  1017  3164 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-26 15:20:55.291  1017  3164 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-26 15:20:55.301  6719  6719 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
07-26 15:20:55.301  1017  3164 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
07-26 15:20:55.301  1017  3164 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
07-26 15:20:55.301  1017  3164 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:55.301  1017  3164 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:20:55.301  1017  3164 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
07-26 15:20:55.301  1017  4272 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
07-26 15:20:55.321  6719  6719 I FilterInstaller: FilterPackageService : ACTION_CHANGED
07-26 15:20:55.331  6719  6739 E FilterInstaller: installFilters
07-26 15:20:55.331  6719  6739 E FilterInstaller: There is no requred permission
07-26 15:20:55.331  1017  1029 I ActivityManager: Killing 4761:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
07-26 15:20:55.371   335   335 I ServiceManager: Waiting for service AtCmdFwd...
07-26 15:20:55.381  6713  6713 D AndroidRuntime: 
07-26 15:20:55.381  6713  6713 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-26 15:20:55.381  6713  6713 D AndroidRuntime: CheckJNI is OFF
07-26 15:20:55.381  6713  6713 D AndroidRuntime: readGMSProperty: start
07-26 15:20:55.381  6713  6713 D AndroidRuntime: readGMSProperty: already setted!!
07-26 15:20:55.381  6713  6713 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-26 15:20:55.381  6713  6713 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-26 15:20:55.381  6713  6713 D AndroidRuntime: readGMSProperty: end
07-26 15:20:55.381  6713  6713 D AndroidRuntime: addProductProperty: start
07-26 15:20:55.451  6595  6612 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-26 15:20:55.471  6595  6612 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-26 15:20:55.471  6595  6612 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-26 15:20:55.471  6595  6612 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-26 15:20:55.511  6713  6713 E AffinityControl: AffinityControl: registerfunction enter
07-26 15:20:55.531  6713  6713 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-26 15:20:55.541  1017  1333 E PersonaManagerService: inState():  stateMachine is null !!
07-26 15:20:55.541  1017  1333 I PersonaManagerService: PersonaId don't exist
07-26 15:20:55.541  1017  1333 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-26 15:20:55.541  1017  1333 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-26 15:20:55.561  1017  1333 W ActivityManager: mDVFSHelper.acquire()
07-26 15:20:55.571  1017  1333 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:55.571  1017  1333 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:55.571  1017  1333 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:55.571  1017  1333 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:55.571  1017  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-26 15:20:55.571  1017  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
07-26 15:20:55.581  1017  1333 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
07-26 15:20:55.581  1017  1333 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6749 uid=10151 gids={50151, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-26 15:20:55.581  1017  1333 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-26 15:20:55.581  6749  6749 I libpersona: KNOX_SDCARD checking this for 10151
07-26 15:20:55.581  6749  6749 E Zygote  : MountEmulatedStorage()
07-26 15:20:55.581  6749  6749 I libpersona: KNOX_SDCARD not a persona
07-26 15:20:55.581  6749  6749 E Zygote  : v2
07-26 15:20:55.581  1017  1333 D InputDispatcher: Focused application set to: xxxx
07-26 15:20:55.581  1017  1333 D InputDispatcher: Focus left window: 4647
07-26 15:20:55.581  6749  6749 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-26 15:20:55.591  6713  6713 D AndroidRuntime: Shutting down VM
07-26 15:20:55.591  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-26 15:20:55.591  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-26 15:20:55.591  3509  3509 I ConfigFetchService: fetch service done; releasing wakelock
07-26 15:20:55.591  6749  6749 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-26 15:20:55.591  3509  3509 I ConfigFetchService: stopping self
07-26 15:20:55.591  6749  6749 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-26 15:20:55.591   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
07-26 15:20:55.601  1017  4270 I ActivityManager: Killing 6330:com.samsung.helphub/1000 (adj 15): empty #21
07-26 15:20:55.611  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-26 15:20:55.611  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
07-26 15:20:55.611  6749  6749 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 15:20:55.621  6749  6749 D ActivityThread: Added TimaKeyStore provider
07-26 15:20:55.621  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-26 15:20:55.641  1017  1030 D PersonaManager: isKioskContainerExistOnDevice
07-26 15:20:55.661   258   448 I SurfaceFlinger: id=10 Removed YUIInstallC (5/9)
07-26 15:20:55.671   258   445 I SurfaceFlinger: id=10 Removed YUIInstallC (-2/9)
07-26 15:20:55.671  4647  4647 V ActivityThread: updateVisibility : ActivityRecord{355d8b83 token=android.os.BinderProxy@2b65dad6 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
07-26 15:20:55.741  6749  6749 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-26 15:20:55.751  6749  6749 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4132-4134)
07-26 15:20:55.751  6749  6749 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-26 15:20:55.781  6749  6749 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3a227eaf}
07-26 15:20:55.781  6749  6749 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-26 15:20:55.781  6749  6749 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-26 15:20:55.791  6713  6713 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
07-26 15:20:55.811  6749  6749 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-26 15:20:55.821  6749  6749 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-26 15:20:55.821  6749  6749 E SysUtils: ApplicationContext is null in ApplicationStatus
07-26 15:20:55.841  6749  6749 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
07-26 15:20:55.841  6749  6749 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
07-26 15:20:55.841  6749  6749 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
07-26 15:20:55.841  6749  6749 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
07-26 15:20:55.841  6749  6749 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-26 15:20:55.841  6749  6749 I Adreno-EGL: Build Date: 04/06/15 Mon
07-26 15:20:55.841  6749  6749 I Adreno-EGL: Local Branch: 
07-26 15:20:55.841  6749  6749 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
07-26 15:20:55.841  6749  6749 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
07-26 15:20:55.841  6749  6749 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
07-26 15:20:56.021  6749  6776 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
07-26 15:20:56.071  6749  6749 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-26 15:20:56.081  6749  6749 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-26 15:20:56.091  6749  6749 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-26 15:20:56.091  6749  6749 D PhoneWindow: *FMB* installDecor flags : -2139027200
07-26 15:20:56.101  6749  6749 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
07-26 15:20:56.111  6749  6749 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-26 15:20:56.111  6749  6749 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-26 15:20:56.141  1017  1043 W ActivityManager: Activity pause timeout for ActivityRecord{e7c978a u0 com.test.thalitest/.MainActivity t99}
07-26 15:20:56.171  6749  6789 D OpenGLRenderer: Render dirty regions requested: true
07-26 15:20:56.181  1017  1216 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-26 15:20:56.181  1017  1216 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-26 15:20:56.181  1017  1216 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-26 15:20:56.181  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-26 15:20:56.181  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
07-26 15:20:56.191  6749  6749 V ActivityThread: updateVisibility : ActivityRecord{6bf2816 token=android.os.BinderProxy@17d761d8 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-26 15:20:56.191  6749  6749 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-26 15:20:56.191  6749  6749 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-26 15:20:56.201   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
07-26 15:20:56.201  1017  1520 D InputDispatcher: Focus entered window: 6749
07-26 15:20:56.211  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-26 15:20:56.211  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
07-26 15:20:56.211  6749  6749 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
07-26 15:20:56.211  6749  6789 I OpenGLRenderer: Initialized EGL, version 1.4
07-26 15:20:56.211  6749  6789 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
07-26 15:20:56.211  6749  6789 D OpenGLRenderer: Enabling debug mode 0
07-26 15:20:56.231  1017  1248 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-26 15:20:56.241  1171  1171 I StatusBar: Icon Only
07-26 15:20:56.241  1171  1171 D PanelView: There is/are notification(s) 
07-26 15:20:56.241  6749  6749 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@17d761d8 time:124621
07-26 15:20:56.241  6749  6749 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-26 15:20:56.241  1017  6791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
07-26 15:20:56.251  1017  1048 I ActivityManager: Displayed Component not be shown by security: +607ms (total +9s314ms)
07-26 15:20:56.251  1017  1048 W ActivityManager: mDVFSHelper.release()
07-26 15:20:56.251  1017  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{e7c978a u0 com.test.thalitest/.MainActivity t99} time:124635
07-26 15:20:56.251  1838  1838 I SamsungIME: getCurrentCandidateView
07-26 15:20:56.261   258  1913 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
07-26 15:20:56.261   258   448 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
07-26 15:20:56.331  1838  1838 D SamsungIME: Dismiss ExpandCandiate
07-26 15:20:56.341   297   297 E SMD     : DCD OFF
07-26 15:20:56.371   335   335 I ServiceManager: Waiting for service AtCmdFwd...
07-26 15:20:56.401  6467  6467 I Mms/MmsApp:  start initViewCache mms
07-26 15:20:56.401  6467  6467 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1838.75552
07-26 15:20:56.401  6467  6467 D Mms/ComposeMessageFragment: fillCache, easy = false
07-26 15:20:56.441  6749  6749 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6749
07-26 15:20:56.481  6467  6467 D AbsListView: Get MotionRecognitionManager
07-26 15:20:56.481  1017  4270 D MotionRecognitionService:  ssp status : false
07-26 15:20:56.501  6467  6467 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 97.494584
07-26 15:20:56.501  1838  1838 I SamsungIME: getDebugLevel  : 0x4f4c
,07-26 15:20:56.541  1838  1838 I SamsungIME: getDebugLevel  : 0x4f4c
,07-26 15:20:56.561  1838  1838 I SamsungIME: KeybaordView init() : load resources
,07-26 15:20:56.581  1838  1838 I SamsungIME: getCurrentKeyboard
,07-26 15:20:56.581  1838  1838 I SamsungIME: getTextKeyboard
,07-26 15:20:56.601  6749  6749 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-26 15:20:56.601  6467  6467 D Mms/BubbleViewCache: fillCache bubble = 1
,07-26 15:20:56.611  1838  1838 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-26 15:20:56.711  6749  6794 D jxcore_app_log: JniHelper::setJavaVM(0xb77682f0), pthread_self() = -1211360800
,07-26 15:20:56.721  6749  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-26 15:20:56.721  6749  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-26 15:20:56.721  6749  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-26 15:20:56.721  6749  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-26 15:20:56.721  6749  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-26 15:20:56.721  6749  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1efc2c6 added. We now have 1 listener(s)
,07-26 15:20:56.731  6749  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,07-26 15:20:56.731  6749  6794 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,07-26 15:20:56.731  6749  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-26 15:20:56.731  6749  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-26 15:20:56.741  6749  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-26 15:20:56.741  6749  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-26 15:20:56.741  6749  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-26 15:20:56.741  6749  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
07-26 15:20:56.741  6749  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-26 15:20:56.741  6749  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-26 15:20:56.741  6749  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-26 15:20:56.741  6749  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-26 15:20:56.741  6749  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
07-26 15:20:56.741  6749  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-26 15:20:56.741  6749  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-26 15:20:56.741  6749  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-26 15:20:56.741  6749  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-26 15:20:56.741  6749  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-26 15:20:56.741  6749  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@334045dd added. We now have 1 listener(s)
,07-26 15:20:56.741  6749  6794 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 15:20:56.741  6749  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-26 15:20:56.741  6749  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,07-26 15:20:56.741  6749  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-26 15:20:56.741  6749  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-26 15:20:56.751  6749  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 15:20:56.751  6749  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,07-26 15:20:56.751  6749  6794 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,07-26 15:20:56.761  6749  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:20:56.761  6749  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:56.761  6749  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:20:56.761  6749  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:56.761  6749  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:56.761  6749  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: 84:b2:61:1a:ce:70
07-26 15:20:56.761  6749  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:20:56.761  6749  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-26 15:20:56.761  6749  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-26 15:20:56.761  6749  6794 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-26 15:20:56.761  6749  6794 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-26 15:20:56.761  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:20:56.761  6749  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:20:56.791  6369  6421 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,07-26 15:20:56.791  6749  6749 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-26 15:20:56.801  6369  6421 I AcmsKeyStoreHelper: Key Store exist,
07-26 15:20:56.801  6369  6421 I AcmsKeyStoreHelper: Hence loading the keystore file
,07-26 15:20:56.861  6369  6421 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
07-26 15:20:56.861  6369  6421 I AcmsCertificateMngr: getKeyStoreForApplication success 
07-26 15:20:56.861  6369  6421 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
07-26 15:20:56.861  6369  6421 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
07-26 15:20:56.861  6369  6421 D AcmsServiceMonitor: Decrementing - Counter value: 1
07-26 15:20:56.861  6369  6421 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,07-26 15:20:56.861  6369  6421 D AcmsCore: This is NOT a valid MirrorLink app
07-26 15:20:56.861  6369  6421 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
07-26 15:20:56.861  6369  6421 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
07-26 15:20:56.861  6369  6421 D AcmsServiceMonitor: Decrementing - Counter value: 0
07-26 15:20:56.861  6369  6421 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,07-26 15:20:56.861  6369  6369 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
07-26 15:20:56.861  6369  6369 D AcmsService: Enter onDestroy
07-26 15:20:56.861  6369  6369 I AcmsService: cleanUp(): inside service clean up
07-26 15:20:56.861  6369  6369 D AcmsCore: AcmsCore: inside DeInit
07-26 15:20:56.861  6369  6369 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
07-26 15:20:56.861  6369  6369 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
07-26 15:20:56.861  6369  6369 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
07-26 15:20:56.861  6369  6369 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
07-26 15:20:56.861  6369  6369 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,07-26 15:20:56.861  6369  6369 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
07-26 15:20:56.861  6369  6369 D AcmsService: killing acms process
07-26 15:20:56.861  6369  6369 I Process : Sending signal. PID: 6369 SIG: 9
,07-26 15:20:56.931  1017  1333 I ActivityManager: Process ACMS.Process (pid 6369)(adj 0) has died(29,769)
,07-26 15:20:57.201  6749  6800 W jxcore-log: Initializing JXcore engine
07-26 15:20:57.201  6749  6800 W jxcore-log: JXcore engine is ready
,07-26 15:20:57.261  1961  1961 E audit   : type=1400 msg=audit(1469539257.261:205): avc:  denied  { ioctl } for  pid=6800 comm="Thread-1248" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,07-26 15:20:57.261  1961  1961 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
07-26 15:20:57.261  1961  1961 E audit   : type=1300 msg=audit(1469539257.261:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=a03ff8f8 items=0 ppid=316 ppcomm=main pid=6800 auid=4294967295 uid=10151 gid=10151 euid=10151 suid=10151 fsuid=10151 egid=10151 sgid=10151 fsgid=10151 ses=4294967295 tty=(none) comm="Thread-1248" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-26 15:20:57.261  1961  1961 E audit   : type=1320 msg=audit(1469539257.261:205): 
,07-26 15:20:57.271  6749  6800 W jxcore-log: Starting JXcore engine
,07-26 15:20:57.371  6749  6800 W jxcore-log: Platform android
07-26 15:20:57.371  6749  6800 W jxcore-log: 
07-26 15:20:57.371  6749  6800 W jxcore-log: Process ARCH arm
07-26 15:20:57.371  6749  6800 W jxcore-log: 
,07-26 15:20:57.371   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,07-26 15:20:57.541  6749  6800 I jxcore-log: JXcore Cordova bridge is ready!
07-26 15:20:57.541  6749  6800 I jxcore-log: 
,07-26 15:20:57.541  6749  6800 W jxcore-log: JXcore engine is started
,07-26 15:20:57.551  6749  6794 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-26 15:20:57.551  6749  6749 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-26 15:20:57.561  6749  6800 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-26 15:20:57.561  6749  6800 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-26 15:20:57.571  6749  6749 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,07-26 15:20:57.571  6749  6749 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-26 15:20:57.571  1017  1248 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-26 15:20:57.571  1017  1248 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
07-26 15:20:57.571  1017  1248 D InputDispatcher: Focused application set to: xxxx
07-26 15:20:57.581  1017  1248 I ActivityManager: Killing 6315:com.osp.app.signin/u0a36 (adj 15): empty #21
07-26 15:20:57.581  6749  6749 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-26 15:20:57.581  6749  6749 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,07-26 15:20:57.581  6749  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:57.581  6749  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:57.581  6749  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:57.581  6749  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:20:57.591  6749  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1efc2c6 removed from the list
07-26 15:20:57.591  6749  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:20:57.591  6749  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@334045dd removed from the list
07-26 15:20:57.591  6749  6749 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:57.591  6749  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,07-26 15:20:57.591  6749  6749 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-26 15:20:57.601   258  1913 I SurfaceFlinger: id=14 Removed NainActivit (6/8)
,07-26 15:20:57.601   258   445 I SurfaceFlinger: id=14 Removed NainActivit (-2/8),
07-26 15:20:57.601  1017  4268 W ActivityManager: mDVFSHelper.acquire()
,07-26 15:20:57.601  1017  3165 D InputDispatcher: Focus left window: 6749
,07-26 15:20:57.611  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-26 15:20:57.611  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,07-26 15:20:57.611  6749  6749 E ViewRootImpl: sendUserActionEvent() mView == null
,07-26 15:20:57.641  4647  4647 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,07-26 15:20:57.641  4647  4647 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 0
,07-26 15:20:57.661  4647  4647 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,07-26 15:20:57.671  4647  4647 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,07-26 15:20:57.671  4647  4647 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 0
,07-26 15:20:57.671  4647  4647 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,07-26 15:20:57.681  4647  4647 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,07-26 15:20:57.691  4647  4647 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,07-26 15:20:57.701  4647  4647 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,07-26 15:20:57.711  1017  3165 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,07-26 15:20:57.711  1017  3165 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,07-26 15:20:57.711  1017  1017 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,07-26 15:20:57.721  4647  4647 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 0
,07-26 15:20:57.721  1171  1171 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,07-26 15:20:57.721  1171  1171 D PersonaManager: isKioskContainerExistOnDevice
,07-26 15:20:57.721  1171  1171 D PersonaManager: isKioskContainerExistOnDevice
,07-26 15:20:57.721  1171  1171 I PhoneStatusBar: Icon Only
07-26 15:20:57.721  1171  1171 I StatusBar: Icon Only
,07-26 15:20:57.721  1171  1171 D PanelView: There is/are notification(s) 
07-26 15:20:57.721  1171  1171 D PanelView: kidsfalse mQsExpansionEnabled:true
07-26 15:20:57.731  4647  4647 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,07-26 15:20:57.731  1171  1171 D PersonaManager: isKioskContainerExistOnDevice
,07-26 15:20:57.731  1171  1171 I PhoneStatusBar: Icon Only
,07-26 15:20:57.731  1171  1171 I StatusBar: Icon Only
07-26 15:20:57.731  1171  1171 D PanelView: There is/are notification(s) 
07-26 15:20:57.731  1171  1171 D PanelView: kidsfalse mQsExpansionEnabled:true
,07-26 15:20:57.731  4647  4647 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,07-26 15:20:57.731  4647  4647 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,07-26 15:20:57.731  4647  4647 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,07-26 15:20:57.741  4647  4647 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,07-26 15:20:57.741  1017  4272 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-26 15:20:57.741  1017  4272 D KnoxTimeoutHandler: postActiveUserChange for user 0
,07-26 15:20:57.741  1017  4272 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,07-26 15:20:57.741  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-26 15:20:57.741  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
07-26 15:20:57.741  4647  4647 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,07-26 15:20:57.741   258   258 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=404, YUIInstallC
,07-26 15:20:57.741  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-26 15:20:57.751  1017  4270 D InputDispatcher: Focus entered window: 4647
,07-26 15:20:57.751  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,07-26 15:20:57.751  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,07-26 15:20:57.751  4647  4647 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! ,
,07-26 15:20:57.761  1017  1333 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-26 15:20:57.761  6749  6749 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,07-26 15:20:57.761  1017  6806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-26 15:20:57.761  1838  1838 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,07-26 15:20:57.771  1171  1171 I StatusBar: Icon Only,
,07-26 15:20:57.771  1171  1171 D PanelView: There is/are notification(s) 
,07-26 15:20:57.791  4647  4647 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2b65dad6 time:126177
,07-26 15:20:57.791  4647  4647 V ActivityThread: updateVisibility : ActivityRecord{355d8b83 token=android.os.BinderProxy@2b65dad6 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,07-26 15:20:57.801  1171  1171 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,07-26 15:20:57.821  1017  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{856030b u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t97} time:126200
07-26 15:20:57.821  1017  1048 W ActivityManager: mDVFSHelper.release()
,07-26 15:20:57.831  6802  6802 D AndroidRuntime: 
07-26 15:20:57.831  6802  6802 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,07-26 15:20:57.841  6802  6802 D AndroidRuntime: CheckJNI is OFF
,07-26 15:20:57.841  6802  6802 D AndroidRuntime: readGMSProperty: start
07-26 15:20:57.841  6802  6802 D AndroidRuntime: readGMSProperty: already setted!!
07-26 15:20:57.841  6802  6802 D AndroidRuntime: propertySet: couldn't set property (it is from app)
,07-26 15:20:57.841  6802  6802 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-26 15:20:57.841  6802  6802 D AndroidRuntime: readGMSProperty: end
07-26 15:20:57.841  6802  6802 D AndroidRuntime: addProductProperty: start
,07-26 15:20:57.901  1017  1520 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
07-26 15:20:57.901  1017  1520 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-26 15:20:57.901  1017  1520 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-26 15:20:57.901  1017  1520 D BatteryService: stay LED for fully charged
07-26 15:20:57.901  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-26 15:20:57.901  1017  1017 I MotionRecognitionService: Plugged
07-26 15:20:57.901  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,07-26 15:20:57.911  1171  1171 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-26 15:20:57.911  1171  1171 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-26 15:20:57.911  1424  1424 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-26 15:20:57.911  1424  1424 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-26 15:20:57.921  2814  2814 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-26 15:20:57.921  2814  2944 D HeadsetStateMachine: Disconnected process message: 10
,07-26 15:20:57.931  1171  1171 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
07-26 15:20:57.931  1171  1171 D SViewCoverView: level :100 plugged : 2
,07-26 15:20:57.931  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-26 15:20:57.931  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-26 15:20:57.931  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-26 15:20:57.971  6802  6802 E AffinityControl: AffinityControl: registerfunction enter
,07-26 15:20:58.001  6802  6802 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-26 15:20:58.021  1017  1504 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
07-26 15:20:58.021  1017  1504 D PackageManager: START PACKAGE DELETE: observer{124946351},
07-26 15:20:58.021  1017  1504 D PackageManager: pkg{<packageName>}
07-26 15:20:58.021  1017  1504 D PackageManager: user{0}
07-26 15:20:58.021  1017  1504 D PackageManager: caller{2000}
07-26 15:20:58.021  1017  1504 D PackageManager: flags{2}
07-26 15:20:58.021  1017  1504 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-26 15:20:58.021  1017  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-26 15:20:58.021  1017  1504 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,07-26 15:20:58.021  1017  1058 D PackageManager: !@killApplicatoin: 10151, uninstall pkg
07-26 15:20:58.021  1017  1504 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-26 15:20:58.021  1017  1504 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-26 15:20:58.021  1017  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-26 15:20:58.021  1017  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1,
07-26 15:20:58.021  1017  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
07-26 15:20:58.021  1017  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,07-26 15:20:58.021  1017  1043 I ActivityManager: Force stopping com.test.thalitest appid=10151 user=-1: uninstall pkg
07-26 15:20:58.021  1017  1043 I ActivityManager: Killing 6749:com.test.thalitest/u0a151 (adj 9): stop com.test.thalitest cause uninstall pkg
,07-26 15:20:58.031  1017  1043 D PersonaManager: isKioskContainerExistOnDevice
,07-26 15:20:58.181  1017  1058 I ActivityManager: Force stopping com.test.thalitest appid=10151 user=0: pkg removed
,07-26 15:20:58.211  1017  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,07-26 15:20:58.231  6181  6181 I art     : Explicit concurrent mark sweep GC freed 244(26KB) AllocSpace objects, 0(0B) LOS objects, 27% free, 5MB/7MB, paused 1.278ms total 35.426ms
,07-26 15:20:58.231  6119  6119 I art     : Explicit concurrent mark sweep GC freed 12849(706KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 4MB/6MB, paused 807us total 42.095ms
,07-26 15:20:58.251  1017  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-26 15:20:58.251  1838  1838 E SamsungIME: mOCRHelper is null
,07-26 15:20:58.261  1749  1869 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-26 15:20:58.301  4381  4381 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jul 26 15:20:58 GMT+02:00 2016
,07-26 15:20:58.301  1017  1123 V NetworkStats: removeUidsLocked() for UIDs [10151]
07-26 15:20:58.301  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:20:58.301  1017  1123 V NetworkStats: performPollLocked(flags=0x3)
,07-26 15:20:58.311  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
07-26 15:20:58.311  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,07-26 15:20:58.311  1017  4270 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
07-26 15:20:58.311  1017  4270 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,07-26 15:20:58.311  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:20:58.311  1017  1123 V NetworkStats: performPollLocked() took 11ms
,07-26 15:20:58.321  1017  1017 D RCPManagerService: PackageReceiver onReceive()
07-26 15:20:58.321  1465  1465 D PersonaManager: isKioskContainerExistOnDevice
07-26 15:20:58.321  1017  4270 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:58.321  1017  4270 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:20:58.321  1017  4270 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,07-26 15:20:58.331  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,07-26 15:20:58.331  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
07-26 15:20:58.331  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
07-26 15:20:58.331  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10151 container id = 0
,07-26 15:20:58.341  1465  1465 D RegisteredServicesCache: empty dynamic service
,07-26 15:20:58.341  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,07-26 15:20:58.351  4381  4381 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,07-26 15:20:58.351  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,07-26 15:20:58.351  1017  4268 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=23, mSplitNum[2]=33, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=43
07-26 15:20:58.351  1017  4268 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,07-26 15:20:58.351  1017  4268 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,07-26 15:20:58.351  1017  4268 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:58.351  1017  4268 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:58.351  1017  4268 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:58.351  1017  4268 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:58.371  6820  6820 E Zygote  : MountEmulatedStorage(),
07-26 15:20:58.371  6820  6820 E Zygote  : v2
07-26 15:20:58.371  6820  6820 I libpersona: KNOX_SDCARD checking this for 10090
07-26 15:20:58.371  6820  6820 I libpersona: KNOX_SDCARD not a persona
,07-26 15:20:58.371  6820  6820 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-26 15:20:58.371  4381  4381 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,07-26 15:20:58.371  6820  6820 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-26 15:20:58.371  1017  4268 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6820 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,07-26 15:20:58.371  6820  6820 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-26 15:20:58.371  4381  4381 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
07-26 15:20:58.371  1017  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
07-26 15:20:58.371  1017  1042 W TextServicesManagerService: no available spell checker services found
07-26 15:20:58.371  1017  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
07-26 15:20:58.381   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,07-26 15:20:58.381  4381  4381 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,07-26 15:20:58.391  4381  6819 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,07-26 15:20:58.391  4381  6819 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,07-26 15:20:58.391  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:20:58.401  1017  1503 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-26 15:20:58.401  1017  1503 D SecContentProvider2: mCursor = null
,07-26 15:20:58.401  4381  6819 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START,
07-26 15:20:58.401  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:20:58.401  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 15:20:58.401  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,07-26 15:20:58.401  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:58.401  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:58.401  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:58.401  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:58.411  4381  6819 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,07-26 15:20:58.421  6835  6835 E Zygote  : MountEmulatedStorage()
07-26 15:20:58.421  6835  6835 I libpersona: KNOX_SDCARD checking this for 10032
07-26 15:20:58.421  6835  6835 E Zygote  : v2
07-26 15:20:58.421  6835  6835 I libpersona: KNOX_SDCARD not a persona
07-26 15:20:58.421  6835  6835 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-26 15:20:58.421  1017  1043 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=6835 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-26 15:20:58.421  6820  6820 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 15:20:58.421  6835  6835 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-26 15:20:58.421  6820  6820 D ActivityThread: Added TimaKeyStore provider
,07-26 15:20:58.431  6835  6835 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,07-26 15:20:58.431  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:20:58.441  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,07-26 15:20:58.451  1465  1465 D RegisteredComponentCache: Collect Tech packages for Knox
07-26 15:20:58.451  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:58.451  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:58.451  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:58.451  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:58.461  6849  6849 E Zygote  : MountEmulatedStorage(),
07-26 15:20:58.461  6849  6849 E Zygote  : v2
07-26 15:20:58.461  6849  6849 I libpersona: KNOX_SDCARD checking this for 10098
07-26 15:20:58.461  6849  6849 I libpersona: KNOX_SDCARD not a persona
,07-26 15:20:58.461  6849  6849 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-26 15:20:58.461  6849  6849 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
07-26 15:20:58.461  1465  1465 D PersonaManager: isKioskContainerExistOnDevice
07-26 15:20:58.461  1017  1043 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6849 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
07-26 15:20:58.461  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
07-26 15:20:58.471  6849  6849 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-26 15:20:58.461  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
07-26 15:20:58.471  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:58.481  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-26 15:20:58.481  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,07-26 15:20:58.491  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-26 15:20:58.491  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:20:58.491  6835  6835 D TimaKeyStoreProvider: TimaSignature is unavailable,
07-26 15:20:58.491  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-26 15:20:58.491  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-26 15:20:58.491  1017  1017 V EnterpriseBillingPolicy: uID is 10151
07-26 15:20:58.491  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
07-26 15:20:58.491  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,07-26 15:20:58.491  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-26 15:20:58.491  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-26 15:20:58.491  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-26 15:20:58.491  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-26 15:20:58.491  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
07-26 15:20:58.501  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-26 15:20:58.501  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
07-26 15:20:58.501  1017  1017 V EnterpriseBillingPolicy: uID is 10151
07-26 15:20:58.501  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
07-26 15:20:58.501  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-26 15:20:58.501  1017  2896 D SSRM:bc : MSG_TYPE_APP_REMOVED::
07-26 15:20:58.501  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-26 15:20:58.501  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-26 15:20:58.501  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-26 15:20:58.501  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-26 15:20:58.501  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
07-26 15:20:58.501  1017  1017 V AlarmManagerEXT: com.test.thalitest(10151) is removed.
07-26 15:20:58.511  6835  6835 D ActivityThread: Added TimaKeyStore provider
07-26 15:20:58.511  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-26 15:20:58.511  6348  6859 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
07-26 15:20:58.521  6849  6849 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 15:20:58.521  6849  6849 D ActivityThread: Added TimaKeyStore provider
07-26 15:20:58.521  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
07-26 15:20:58.531  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:58.531  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:58.531  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:58.531  4381  6819 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
07-26 15:20:58.531  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:58.541  4381  6819 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,07-26 15:20:58.541  4381  6819 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END,
,07-26 15:20:58.551  6866  6866 E Zygote  : MountEmulatedStorage(),
07-26 15:20:58.551  6866  6866 E Zygote  : v2
07-26 15:20:58.551  6866  6866 I libpersona: KNOX_SDCARD checking this for 10055
07-26 15:20:58.551  6866  6866 I libpersona: KNOX_SDCARD not a persona
,07-26 15:20:58.551  6866  6866 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,07-26 15:20:58.551  6866  6866 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,07-26 15:20:58.561  6866  6866 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-26 15:20:58.571  1017  1030 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6866 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,07-26 15:20:58.581  1017  1161 D TaskPersister: removeObsoleteFile: deleting file=97_task.xml
,07-26 15:20:58.581  4381  4381 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,07-26 15:20:58.581  6820  6820 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,07-26 15:20:58.591  6866  6866 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:20:58.591  6866  6866 D ActivityThread: Added TimaKeyStore provider
,07-26 15:20:58.591  6820  6820 D elm:15121: ELMEngine.ELMEngine( context ).
,07-26 15:20:58.601  6820  6820 D elm:15121: MDMBridge.setEnterpriseBridge()
,07-26 15:20:58.611  1017  4268 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,07-26 15:20:58.611  1017  4268 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,07-26 15:20:58.611  1017  4268 W ActivityManager: userId = 0, bbcId = -10000
,07-26 15:20:58.611  1017  4268 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:20:58.611  1017  4268 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,07-26 15:20:58.621  6820  6820 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,07-26 15:20:58.621  1017  1503 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,07-26 15:20:58.621  3574  3574 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,07-26 15:20:58.621  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:58.621  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:58.621  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:58.621  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:58.631  3574  3574 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-26 15:20:58.631  3574  3574 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
07-26 15:20:58.631  3574  3574 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-26 15:20:58.631  3574  3574 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
07-26 15:20:58.631  3574  3574 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
07-26 15:20:58.631  3574  3574 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
07-26 15:20:58.631  3574  3574 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:20:58.631  3574  3574 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-26 15:20:58.631  3574  3574 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-26 15:20:58.631  3574  3574 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:20:58.631  3574  3574 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-26 15:20:58.631  3574  3574 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-26 15:20:58.631  3574  3574 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,07-26 15:20:58.641  6883  6883 E Zygote  : MountEmulatedStorage()
07-26 15:20:58.641  6883  6883 E Zygote  : v2
07-26 15:20:58.641  6883  6883 I libpersona: KNOX_SDCARD checking this for 1000
07-26 15:20:58.641  6883  6883 I libpersona: KNOX_SDCARD not a persona
,07-26 15:20:58.641  6883  6883 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-26 15:20:58.641  1017  1503 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6883 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-26 15:20:58.641  6883  6883 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-26 15:20:58.641  6883  6883 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-26 15:20:58.651  1017  1546 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,07-26 15:20:58.651  6835  6882 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
07-26 15:20:58.651  6835  6882 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,07-26 15:20:58.661  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:58.661  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:58.661  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:58.661  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:58.661  6835  6882 D SPPClientService: PushLog.txt file is not deleted.
,07-26 15:20:58.661  6835  6882 D SPPClientService: PushLog.txt file is not deleted.
07-26 15:20:58.661  6835  6882 D SPPClientService: ============PushLog. stop!
,07-26 15:20:58.671  6820  6820 D elm:15121: ElmAgentService : onCreate(),
07-26 15:20:58.671  6820  6881 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
07-26 15:20:58.671  6820  6881 D elm:15121: MainReceiver.listeningToPackageRemoved()
07-26 15:20:58.671  6820  6881 D elm:15121: MDMBridge.getInstance()
07-26 15:20:58.671  6820  6881 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,07-26 15:20:58.671  6820  6881 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,07-26 15:20:58.671  6883  6883 D TimaKeyStoreProvider: TimaSignature is unavailable,
,07-26 15:20:58.671  6883  6883 D ActivityThread: Added TimaKeyStore provider
,07-26 15:20:58.681  6901  6901 E Zygote  : MountEmulatedStorage()
07-26 15:20:58.681  6901  6901 E Zygote  : v2
07-26 15:20:58.681  6901  6901 I libpersona: KNOX_SDCARD checking this for 10032
07-26 15:20:58.681  6901  6901 I libpersona: KNOX_SDCARD not a persona
07-26 15:20:58.681  6901  6901 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-26 15:20:58.681  6901  6901 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-26 15:20:58.681  1017  1546 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6901 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-26 15:20:58.681  6901  6901 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,07-26 15:20:58.691  1658  1658 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
07-26 15:20:58.691  1658  1658 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,07-26 15:20:58.701  6901  6901 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:20:58.711  6901  6901 D ActivityThread: Added TimaKeyStore provider
,07-26 15:20:58.721  1017  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,07-26 15:20:58.721  6866  6866 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,07-26 15:20:58.721  6820  6820 D elm:15121: ElmAgentService : onDestroy().
,07-26 15:20:58.731  1017  3164 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
07-26 15:20:58.731  1017  3164 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,07-26 15:20:58.731  1017  3164 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:58.731  1017  3164 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-26 15:20:58.731  1017  3164 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,07-26 15:20:58.741  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:20:58.741  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-26 15:20:58.741  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,07-26 15:20:58.741  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,07-26 15:20:58.741  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-26 15:20:58.741  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-26 15:20:58.751  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:20:58.751  3509  3509 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy}
07-26 15:20:58.751  3509  3509 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy} to Chimera receiver impl com.google.android.gms.games.receiver.PlaySystemBroadcastReceiver
07-26 15:20:58.751  3509  3509 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-26 15:20:58.751  3509  3509 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,07-26 15:20:58.761  3509  6917 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,07-26 15:20:58.761  1017  1504 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-26 15:20:58.761  6866  6866 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,07-26 15:20:58.761  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:58.761  1017  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-26 15:20:58.761  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-26 15:20:58.761  6866  6866 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
07-26 15:20:58.761  6866  6866 D UserAnalysis: Create SecureDbHelper
,07-26 15:20:58.771  3509  6917 D AccountUtils: Clearing selected account for com.test.thalitest
,07-26 15:20:58.771  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:20:58.781  6866  6866 D IntelligenceServiceApplication: onCreate()
,07-26 15:20:58.781  3509  3509 D ChimeraSrvcProxy: Creating service proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy}
07-26 15:20:58.781  6866  6866 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,07-26 15:20:58.781  1017  1248 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,07-26 15:20:58.781  1017  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:58.781  1017  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:58.781  1017  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:58.781  1017  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:58.781  1017  1058 I art     : Explicit concurrent mark sweep GC freed 41594(3MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 23MB/34MB, paused 5.733ms total 507.076ms
07-26 15:20:58.781  3509  3509 D ChimeraSrvcProxy: Proxying container service ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy} to Chimera service impl com.google.android.gms.games.service.PlayGamesAsyncService
07-26 15:20:58.781  3509  3509 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-26 15:20:58.781  3509  3509 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,07-26 15:20:58.791  6866  6866 D IntelligenceServiceApplication: no applications having user consent for prediction
,07-26 15:20:58.801  6921  6921 E Zygote  : MountEmulatedStorage()
07-26 15:20:58.801  6921  6921 E Zygote  : v2
07-26 15:20:58.801  6921  6921 I libpersona: KNOX_SDCARD checking this for 1000
07-26 15:20:58.801  6921  6921 I libpersona: KNOX_SDCARD not a persona
,07-26 15:20:58.801  6921  6921 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-26 15:20:58.801  6921  6921 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-26 15:20:58.801  1017  1248 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6921 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-26 15:20:58.801  6921  6921 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-26 15:20:58.811  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,07-26 15:20:58.811  1017  1333 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-26 15:20:58.811  1017  1333 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:58.811  1017  1333 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-26 15:20:58.811  1017  1333 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-26 15:20:58.811  1017  1333 I ActivityManager: Killing 5804:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,07-26 15:20:58.821  6866  6866 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,07-26 15:20:58.821  6901  6922 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,07-26 15:20:58.821  6901  6922 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,07-26 15:20:58.831  6901  6922 D SPPClientService: PushLog.txt file is not deleted.
07-26 15:20:58.831  6901  6922 D SPPClientService: PushLog.txt file is not deleted.
07-26 15:20:58.831  6901  6922 D SPPClientService: ============PushLog. stop!
,07-26 15:20:58.831  1017  3165 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-26 15:20:58.831  6866  6866 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,07-26 15:20:58.841  1017  3165 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:58.841  1017  3165 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-26 15:20:58.841  1017  3165 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-26 15:20:58.841  6921  6921 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 15:20:58.841  1017  1504 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,07-26 15:20:58.841  6921  6921 D ActivityThread: Added TimaKeyStore provider
,07-26 15:20:58.841  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:58.841  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:58.841  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:58.841  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:58.851  1017  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,07-26 15:20:58.851  1017  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-26 15:20:58.851  1017  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-26 15:20:58.851  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:20:58.851  1017  1058 D PackageManager: delete codoeFile: 
07-26 15:20:58.861  6940  6940 E Zygote  : MountEmulatedStorage()
07-26 15:20:58.861  6940  6940 E Zygote  : v2
07-26 15:20:58.861  6940  6940 I libpersona: KNOX_SDCARD checking this for 10036
07-26 15:20:58.861  6940  6940 I libpersona: KNOX_SDCARD not a persona
07-26 15:20:58.861  6940  6940 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-26 15:20:58.861  1017  1504 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver: pid=6940 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,07-26 15:20:58.861  1017  1504 I ActivityManager: Killing 6384:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,07-26 15:20:58.861  6940  6940 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-26 15:20:58.861  6940  6940 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,07-26 15:20:58.861  1017  1058 D AASAuninstall: userId = 0, info.removedAppID = 10151, info.uid = 10151, packageName = com.test.thalitest
07-26 15:20:58.861  1017  1058 I AASA_removePackage: UID=10151 Target=com.test.thalitest
,07-26 15:20:58.871  1017  1058 D PackageManager: result of delete: 1{124946351}
,07-26 15:20:58.871  6866  6866 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
07-26 15:20:58.871  1017  1546 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-26 15:20:58.871  6866  6866 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
07-26 15:20:58.871  1017  1546 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
,07-26 15:20:58.871  6866  6866 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
07-26 15:20:58.871  6866  6866 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,07-26 15:20:58.871  6866  6866 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,07-26 15:20:58.871  6866  6866 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
07-26 15:20:58.871  6866  6866 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
07-26 15:20:58.881  6866  6866 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
07-26 15:20:58.881  6866  6866 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
07-26 15:20:58.881  6866  6866 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
,07-26 15:20:58.881  6866  6866 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,07-26 15:20:58.881  6866  6866 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
07-26 15:20:58.881  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:58.881  1017  1546 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-26 15:20:58.881  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-26 15:20:58.881  6866  6866 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
07-26 15:20:58.881  6866  6866 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
07-26 15:20:58.881  6866  6866 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
07-26 15:20:58.881  6866  6866 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
07-26 15:20:58.881  6866  6866 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
07-26 15:20:58.881  6866  6866 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
07-26 15:20:58.881  6866  6866 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,07-26 15:20:58.881  6866  6866 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,07-26 15:20:58.891  6866  6866 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,07-26 15:20:58.891  3509  6917 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,07-26 15:20:58.891  6866  6866 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
07-26 15:20:58.891  6866  6866 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
07-26 15:20:58.891  6866  6866 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,07-26 15:20:58.901  6802  6802 D AndroidRuntime: Shutting down VM
,07-26 15:20:58.911  1017  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-26 15:20:58.911  1017  1058 D PackageManager: userId{-1}
07-26 15:20:58.911  1017  1058 D PackageManager: andCode{true}
,07-26 15:20:58.911  6866  6866 D BluetoothAdapter: cancelDiscovery
,07-26 15:20:58.911  1017  4268 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
07-26 15:20:58.911  1017  4268 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
,07-26 15:20:58.911  1017  4268 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:58.911  1017  4268 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-26 15:20:58.911  1017  4268 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-26 15:20:58.911  6940  6940 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:20:58.911  6940  6940 D ActivityThread: Added TimaKeyStore provider
,07-26 15:20:58.921  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:20:58.921  6119  6937 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,07-26 15:20:58.921  1017  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,07-26 15:20:58.921  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:20:58.931  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-26 15:20:58.931  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-26 15:20:58.931  6921  6921 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,07-26 15:20:58.931  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:20:58.931  6444  6444 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,07-26 15:20:58.941  6444  6444 I PCWCLIENTTRACE_PushUtil: sales region : global
,07-26 15:20:58.941  6444  6444 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-26 15:20:58.941  6444  6444 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
07-26 15:20:58.941  1017  3164 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-26 15:20:58.941  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:20:58.941  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-26 15:20:58.941  1017  3164 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:58.941  1017  3164 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-26 15:20:58.941  1017  3164 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,07-26 15:20:58.941  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-26 15:20:58.941  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-26 15:20:58.951  1017  1248 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-26 15:20:58.951  1017  1248 W ActivityManager: userId = 0, bbcId = -10000
,07-26 15:20:58.951  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-26 15:20:58.951  1017  1248 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,07-26 15:20:58.951  1017  1248 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-26 15:20:58.961  1017  1029 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
07-26 15:20:58.961  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,07-26 15:20:58.961  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,07-26 15:20:58.961  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:20:58.961  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,07-26 15:20:58.961  2814  2827 D BluetoothAdapterProperties: mDiscovering is false
,07-26 15:20:58.961  2814  2827 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
,07-26 15:20:58.961  6866  6866 D BluetoothAdapter: cancelDiscovery = true
,07-26 15:20:58.961  6866  6866 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,07-26 15:20:58.971  1017  1503 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,07-26 15:20:58.971  1017  1520 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-26 15:20:58.971  6866  6866 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
07-26 15:20:58.971  1017  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
07-26 15:20:58.971  1017  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,07-26 15:20:58.971  6866  6866 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
07-26 15:20:58.971  1017  1520 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,07-26 15:20:58.971  1017  1520 W ActivityManager: userId = 0, bbcId = -10000
,07-26 15:20:58.971  1017  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-26 15:20:58.971  1017  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-26 15:20:58.971  1017  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:58.971  1017  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:58.981  1017  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:58.981  1017  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:58.981  6119  6119 I art     : Explicit concurrent mark sweep GC freed 1146(56KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 4MB/6MB, paused 827us total 57.614ms
,07-26 15:20:58.991  6960  6960 E Zygote  : MountEmulatedStorage()
07-26 15:20:58.991  6960  6960 I libpersona: KNOX_SDCARD checking this for 10011
07-26 15:20:58.991  6960  6960 E Zygote  : v2
07-26 15:20:58.991  6960  6960 I libpersona: KNOX_SDCARD not a persona
07-26 15:20:58.991  6960  6960 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-26 15:20:59.001  1017  1520 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=6960 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
07-26 15:20:58.991  6960  6960 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-26 15:20:59.001  1017  1248 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,07-26 15:20:59.001  6960  6960 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
07-26 15:20:59.001  1017  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.001  1017  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.001  1017  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.001  1017  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:59.011  6960  6960 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:20:59.011  6960  6960 D ActivityThread: Added TimaKeyStore provider
,07-26 15:20:59.021   316   316 I art     : Explicit concurrent mark sweep GC freed 8714(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 852us total 25.746ms
,07-26 15:20:59.031  6940  6940 I SA      : [SSP] onCreated
,07-26 15:20:59.041   316   316 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 16.489ms
,07-26 15:20:59.041  3509  6958 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
07-26 15:20:59.041  3509  6958 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,07-26 15:20:59.041  3509  6958 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
07-26 15:20:59.041  3509  6958 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,07-26 15:20:59.051  3509  6958 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
07-26 15:20:59.051  3509  6958 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,07-26 15:20:59.051  3509  6958 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,07-26 15:20:59.061   316   316 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 16.547ms
,07-26 15:20:59.071  6975  6975 E Zygote  : MountEmulatedStorage()
07-26 15:20:59.071  6975  6975 E Zygote  : v2
07-26 15:20:59.071  6975  6975 I libpersona: KNOX_SDCARD checking this for 1000
07-26 15:20:59.071  6975  6975 I libpersona: KNOX_SDCARD not a persona
,07-26 15:20:59.071  6975  6975 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-26 15:20:59.071  1017  1248 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6975 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-26 15:20:59.071  6975  6975 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-26 15:20:59.081  3509  6958 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
07-26 15:20:59.081  3509  6958 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
07-26 15:20:59.081  6975  6975 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-26 15:20:59.081  3509  6958 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,07-26 15:20:59.101  6975  6975 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 15:20:59.101  1017  1248 I ActivityManager: Killing 6406:com.google.android.apps.plus/u0a117 (adj 15): empty #21
07-26 15:20:59.101  6975  6975 D ActivityThread: Added TimaKeyStore provider
,07-26 15:20:59.111  6802  6802 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,07-26 15:20:59.121  6425  6425 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,07-26 15:20:59.121  6960  6960 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,07-26 15:20:59.121  6960  6960 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-26 15:20:59.121  1017  1504 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
07-26 15:20:59.121  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,07-26 15:20:59.121  6657  6671 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
07-26 15:20:59.121  6657  6671 D BadgeProvider: sendNotify, [notify] : null
07-26 15:20:59.121  6657  6671 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
07-26 15:20:59.121  6657  6671 D BadgeProvider: update, [BadgeCount] : badgecount=0
07-26 15:20:59.121  6657  6671 D BadgeProvider: update, [UpdateCount] : 1
,07-26 15:20:59.131  6511  6529 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,07-26 15:20:59.131  6511  6529 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-26 15:20:59.131  6511  6529 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-26 15:20:59.131  6511  6529 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
07-26 15:20:59.131  6511  6529 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,07-26 15:20:59.131  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:59.131  1017  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:20:59.131  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,07-26 15:20:59.131  6348  6859 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 620 ms] updated apps [took 620 ms] 
,07-26 15:20:59.141  1017  3164 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,07-26 15:20:59.141  1017  3164 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.141  1017  3164 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.141  1017  3164 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.141  1017  3164 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:59.141  6940  6940 I SA      : [TPM] There is no property file
,07-26 15:20:59.151  6511  6529 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,07-26 15:20:59.151  6511  6529 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
07-26 15:20:59.151  6511  6529 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-26 15:20:59.151  6511  6529 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-26 15:20:59.151  6511  6529 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-26 15:20:59.151  6511  6529 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-26 15:20:59.151  6995  6995 E Zygote  : MountEmulatedStorage(),
07-26 15:20:59.151  6995  6995 E Zygote  : v2
07-26 15:20:59.151  6995  6995 I libpersona: KNOX_SDCARD checking this for 1000
,07-26 15:20:59.151  6995  6995 I libpersona: KNOX_SDCARD not a persona
,07-26 15:20:59.161  6995  6995 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-26 15:20:59.161  6995  6995 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-26 15:20:59.161  1017  3164 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6995 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-26 15:20:59.161  6995  6995 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-26 15:20:59.161  1017  1545 I ActivityManager: Killing 6538:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,07-26 15:20:59.161  1017  1216 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-26 15:20:59.171  1017  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
,07-26 15:20:59.171  1017  1216 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:59.171  1017  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-26 15:20:59.171  1017  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-26 15:20:59.171  6940  6940 I SA      : [SCU] isHaveSA() - false
,07-26 15:20:59.171  1017  4268 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-26 15:20:59.181  6940  6940 I SA      : [TPM] getModelProperty : null
07-26 15:20:59.181  6940  6940 I SA      : [TPM] getCSCProperty : null
,07-26 15:20:59.181  6940  6940 I SA      : [DM] FLOATING AMOLED FEATURE: true
07-26 15:20:59.181  6940  6940 I SA      : [DM] PRODUCT AMOLED FEATURE: false
07-26 15:20:59.181  6940  6940 I SA      : [DM] TFT FEATURE: false
,07-26 15:20:59.181  6940  6940 I SA      : [DM] init START
07-26 15:20:59.181  6492  6492 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
07-26 15:20:59.181  1017  4268 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:59.181  1017  4268 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-26 15:20:59.181  1017  4268 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-26 15:20:59.191  6995  6995 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 15:20:59.191  1017  4270 I ActivityManager: Killing 6558:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
07-26 15:20:59.191  6995  6995 D ActivityThread: Added TimaKeyStore provider
,07-26 15:20:59.201  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
07-26 15:20:59.201  6940  6940 I SA      : [DM] This device is not a Vodafone
07-26 15:20:59.201  3509  3509 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
07-26 15:20:59.201  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.201  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.201  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.201  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:59.211  6975  7013 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED
07-26 15:20:59.211  6511  6529 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-26 15:20:59.211  6511  6529 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-26 15:20:59.211  6511  6529 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-26 15:20:59.211  6975  7013 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,07-26 15:20:59.221  6960  6960 I MultiDex: VM with version 2.1.0 has multidex support
07-26 15:20:59.221  6960  6960 I MultiDex: install
07-26 15:20:59.221  6960  6960 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-26 15:20:59.221  7014  7014 E Zygote  : MountEmulatedStorage(),
07-26 15:20:59.221  7014  7014 E Zygote  : v2
07-26 15:20:59.221  7014  7014 I libpersona: KNOX_SDCARD checking this for 10117
07-26 15:20:59.221  7014  7014 I libpersona: KNOX_SDCARD not a persona
07-26 15:20:59.221  6995  6995 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-26 15:20:59.221  7014  7014 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-26 15:20:59.221  7014  7014 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-26 15:20:59.231  7014  7014 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-26 15:20:59.231  1017  1030 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7014 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
07-26 15:20:59.231  1017  1030 I ActivityManager: Killing 6578:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,07-26 15:20:59.231  3509  3509 I ConfigFetchService: service connected
07-26 15:20:59.231  6511  6529 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
07-26 15:20:59.231  6511  6529 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-26 15:20:59.231  6511  6529 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
07-26 15:20:59.231  1017  1333 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
07-26 15:20:59.231  1017  1333 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,07-26 15:20:59.231  1017  1333 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:59.231  1017  1333 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:20:59.231  1017  1333 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,07-26 15:20:59.241  6940  6940 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,07-26 15:20:59.241  6940  6940 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
07-26 15:20:59.241  6940  6940 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
07-26 15:20:59.241  6940  6940 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
07-26 15:20:59.241  6940  6940 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
07-26 15:20:59.241  6975  6975 D AcmsService: Enter Oncreate
07-26 15:20:59.241  6940  6940 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
07-26 15:20:59.241  6975  6975 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
07-26 15:20:59.241  6975  6975 D AcmsService: creating AcmsCore
07-26 15:20:59.241  6940  6940 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
07-26 15:20:59.241  6975  6975 D AcmsCore: AcmsCore.getAcmsCore() - Enter
07-26 15:20:59.241  6975  6975 D AcmsCore: AcmsCore
07-26 15:20:59.241  6940  6940 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-26 15:20:59.241  1017  1248 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-26 15:20:59.241  1017  1248 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
07-26 15:20:59.241  6940  6940 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
07-26 15:20:59.241  6940  6940 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
07-26 15:20:59.241  6940  6940 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
07-26 15:20:59.241  6940  6940 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
07-26 15:20:59.241  6940  6940 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,07-26 15:20:59.251  1017  1248 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:59.251  1017  1248 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-26 15:20:59.251  1017  1248 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-26 15:20:59.251  6940  6940 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,07-26 15:20:59.261  6940  6940 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,07-26 15:20:59.261  6940  6940 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
07-26 15:20:59.261  6940  6940 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,07-26 15:20:59.261  7014  7014 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 15:20:59.261  1017  1520 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-26 15:20:59.261  7014  7014 D ActivityThread: Added TimaKeyStore provider
07-26 15:20:59.261  1017  1520 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,07-26 15:20:59.261  1017  1520 W ActivityManager: userId = 0, bbcId = -10000
,07-26 15:20:59.261  1017  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-26 15:20:59.261  1017  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-26 15:20:59.261  6940  6940 W ResourceType: Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
07-26 15:20:59.261  6975  6975 D AcmsCore: init
07-26 15:20:59.261  6975  6975 D AcmsCore: Looper handler is not null
07-26 15:20:59.261  6940  6940 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
07-26 15:20:59.261  6940  6940 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,07-26 15:20:59.261  6975  6975 D AcmsCore: Post to AcmsCoreHandler
07-26 15:20:59.261  6975  6975 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
07-26 15:20:59.261  6940  6940 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,07-26 15:20:59.261  6975  6975 D AcmsServiceMonitor: Incrementing - Counter value: 1
07-26 15:20:59.261  6975  6975 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
07-26 15:20:59.261  6940  6940 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
07-26 15:20:59.261  6975  6975 D AcmsService: onStartCommand
,07-26 15:20:59.261  6975  6975 D AcmsService: Action: android.intent.action.PACKAGE_REMOVED
07-26 15:20:59.261  6975  6975 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
07-26 15:20:59.271  6975  6975 D AcmsServiceMonitor: Incrementing - Counter value: 2
07-26 15:20:59.271  6975  6975 D AcmsService: Incremented Counter Value : onStartCommand
,07-26 15:20:59.271  6995  6995 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
07-26 15:20:59.271  1017  1030 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
,07-26 15:20:59.271  1017  1030 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,07-26 15:20:59.271  6975  7024 D AcmsCertificateMngr: AcmsCertificateMngr
07-26 15:20:59.271  6940  6940 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
07-26 15:20:59.271  6940  6940 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,07-26 15:20:59.271  6940  6940 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
07-26 15:20:59.271  6975  7024 D AcmsRevocationMngr: AcmsRevocationMngr
07-26 15:20:59.271  6940  6940 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
07-26 15:20:59.271  3509  4193 I Icing   : doRemovePackageData com.test.thalitest
,07-26 15:20:59.271  1017  4269 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,07-26 15:20:59.281  3509  7031 I PeopleContactsSync: CP2 sync disabled
07-26 15:20:59.281  6975  6975 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,07-26 15:20:59.281  6940  6940 I SA      : [SCU] isHaveSA() - false
07-26 15:20:59.281  6511  6529 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-26 15:20:59.281  6940  6940 I SA      : support phone number id : false
07-26 15:20:59.281  6511  6529 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-26 15:20:59.281  6940  6940 I SA      : [DM] Supports Ref Jpn : true
07-26 15:20:59.281  6511  6529 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-26 15:20:59.281  6940  6940 I SA      : [DM] init END
07-26 15:20:59.281  6511  6529 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
07-26 15:20:59.281  6511  6529 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-26 15:20:59.291  6960  6960 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,07-26 15:20:59.291  6511  6529 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-26 15:20:59.291  6511  6529 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-26 15:20:59.291  6940  6940 I SA      : [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOJ5 PSS = 4.497050696380942  ]
07-26 15:20:59.291  6940  6940 I SA      : [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10151 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,07-26 15:20:59.291  6719  6719 D FilterInstaller: onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest
07-26 15:20:59.291  6719  6719 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,07-26 15:20:59.301  1017  4270 I ActivityManager: Killing 6619:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,07-26 15:20:59.301  6511  6529 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-26 15:20:59.301  6511  6529 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-26 15:20:59.301  6511  6529 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-26 15:20:59.301  1017  1248 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
,07-26 15:20:59.311  1017  1248 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
,07-26 15:20:59.311  1017  1248 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:59.311  1017  1248 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:20:59.311  1017  1248 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,07-26 15:20:59.311  1017  1545 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-26 15:20:59.311  1017  1545 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.disconnect.FitCleanupService; callingUser = 0; userId(target) = 0
07-26 15:20:59.311  1017  1545 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:59.311  1017  1545 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-26 15:20:59.311  1017  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-26 15:20:59.321  1505  1505 D Launcher.Model: reloadBadges entered.
07-26 15:20:59.321  7014  7014 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-26 15:20:59.321  6511  6529 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
07-26 15:20:59.321  6511  6529 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-26 15:20:59.321  6511  6529 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-26 15:20:59.321  6511  6529 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,07-26 15:20:59.321  1017  4270 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
,07-26 15:20:59.321  1017  4270 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,07-26 15:20:59.331  6719  6719 I FilterInstaller: FilterPackageService : ACTION_PACKAGE_REMOVED
,07-26 15:20:59.331  6719  7034 I FilterInstaller: FilterPackageService : ACTION_REMOVED
,07-26 15:20:59.331  6719  7034 D FilterUnInstaller: before removeFromFS
,07-26 15:20:59.331  1017  4270 W ActivityManager: userId = 0, bbcId = -10000
07-26 15:20:59.331  1017  4270 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-26 15:20:59.331  1017  4270 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,07-26 15:20:59.331  3509  6991 W BaseAppContext: Using Auth Proxy for data requests.
,07-26 15:20:59.331  1017  1029 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.provider.filterprovider
,07-26 15:20:59.341  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.341  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.341  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.341  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.341  1017  1050 I PowerManagerService: [PWL] Off : 50s ago
07-26 15:20:59.341  1017  1050 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
07-26 15:20:59.341  1017  1050 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
07-26 15:20:59.341  1017  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'Icing' (uid=10011, pid=3509, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=588)
,07-26 15:20:59.341  6511  6529 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
07-26 15:20:59.341  6511  6529 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-26 15:20:59.341  6511  6529 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-26 15:20:59.341  6511  6529 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-26 15:20:59.341   297   297 E SMD     : DCD OFF
,07-26 15:20:59.351  7038  7038 E Zygote  : MountEmulatedStorage()
,07-26 15:20:59.351  7038  7038 E Zygote  : v2
07-26 15:20:59.351  7038  7038 I libpersona: KNOX_SDCARD checking this for 10095
07-26 15:20:59.351  7038  7038 I libpersona: KNOX_SDCARD not a persona
,07-26 15:20:59.361  7038  7038 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-26 15:20:59.361  6975  6975 D AcmsService: Inside handle Intent
07-26 15:20:59.361  6975  6975 D AcmsService: App removed - package name: com.test.thalitest
07-26 15:20:59.361  6975  6975 D AcmsCore: Post to AcmsCoreHandler
07-26 15:20:59.361  6975  6975 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
07-26 15:20:59.361  6975  6975 D AcmsServiceMonitor: Incrementing - Counter value: 3
07-26 15:20:59.361  6975  6975 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>5
07-26 15:20:59.361  6975  6975 D AcmsService: Decremented Counter Value : handleStartIntent
07-26 15:20:59.361  6975  6975 D AcmsServiceMonitor: Decrementing - Counter value: 2
,07-26 15:20:59.361  7038  7038 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-26 15:20:59.361  7038  7038 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-26 15:20:59.361  1017  1029 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=7038 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,07-26 15:20:59.381   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,07-26 15:20:59.381  1017  1503 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,07-26 15:20:59.381  6511  6529 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
07-26 15:20:59.381  6511  6529 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-26 15:20:59.381  6511  6529 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-26 15:20:59.381  6511  6529 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-26 15:20:59.391  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.391  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.391  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:59.391  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:20:59.401  6511  6529 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.

```
