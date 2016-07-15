#### Test 75789268514fc25_thali01_samsung-SM-A300FU Logs


```
--------- beginning of main
07-15 15:21:47.191  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:47.191  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-15 15:21:47.191  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
--------- beginning of system
07-15 15:21:47.191  1015  1134 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
07-15 15:21:47.191  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
07-15 15:21:47.191  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:47.191  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:47.191  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:47.191  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:47.201  3251  5672 W art     : Verification of com.google.android.gms.common.api.GoogleApiClient com.google.android.gms.games.broker.PlayerAgent.getConnectedPeopleClient(com.google.android.gms.games.broker.GamesClientContext) took 122.507ms
07-15 15:21:47.201  5714  5714 W art     : Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 132.044ms
07-15 15:21:47.201  5745  5745 E Zygote  : MountEmulatedStorage()
07-15 15:21:47.201  5745  5745 E Zygote  : v2
07-15 15:21:47.201  5745  5745 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-15 15:21:47.201  5714  5744 D Mms/ArtClassLoader: init before art
07-15 15:21:47.201  5745  5745 I libpersona: KNOX_SDCARD checking this for 10029
07-15 15:21:47.201  5745  5745 I libpersona: KNOX_SDCARD not a persona
07-15 15:21:47.211  5745  5745 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-15 15:21:47.211  5745  5745 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-15 15:21:47.211  1015  1134 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder:tagService for service com.samsung.android.app.galaxyfinder/.tag.TagReadyService: pid=5745 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
07-15 15:21:47.231  5745  5745 D TimaKeyStoreProvider: TimaSignature is unavailable
07-15 15:21:47.231  5745  5745 D ActivityThread: Added TimaKeyStore provider
07-15 15:21:47.241  5714  5714 D Mms/TelephonyPermission: start operation mode monitor
07-15 15:21:47.251  5714  5714 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-15 15:21:47.271  5714  5714 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
07-15 15:21:47.271  5714  5714 D Mms/TelephonyPermission: isDefault true
07-15 15:21:47.271  5714  5714 D Mms/MmsApp: onCreate() com.android.mms
07-15 15:21:47.331  5714  5714 D Mms/MmsApp: [start]    initCountryIso consume time = 447.537187
07-15 15:21:47.341  1015  1476 D CountryDetector: The first listener is added
07-15 15:21:47.341  5714  5714 D Mms/MmsApp: [end]    initCountryIso consume time = 15.706198
07-15 15:21:47.341  5714  5714 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.119271
07-15 15:21:47.361  5714  5714 D Mms/MmsConfig: before partial update
07-15 15:21:47.381  5714  5714 D Mms/MmsConfig: Load Resize quality : 80
07-15 15:21:47.391  5714  5714 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
07-15 15:21:47.391  5714  5714 D EasySignUpManager_1.0.1: isAuth is false
07-15 15:21:47.391  5714  5714 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
07-15 15:21:47.401  1456  4350 D TP/MmsSmsProvider: query,matched:2117, calling pid = 5714
07-15 15:21:47.401  1456  4350 D TP/MmsSmsProvider: match 2117:Elapsed time : 2.135 ms
07-15 15:21:47.411  5714  5714 D EasySignUpManager_1.0.1: isAuth is false
07-15 15:21:47.411  5714  5714 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
07-15 15:21:47.411  5714  5714 E CscParser: mps_code.dat does not exist
07-15 15:21:47.411  5714  5714 E CscParser: customer_path =/system/csc/customer.xml
07-15 15:21:47.411  5714  5714 E CscParser: fileName + /system/csc/customer.xml
07-15 15:21:47.421  5714  5714 E CscParser: mps_code.dat does not exist
07-15 15:21:47.421  5714  5714 E CscParser: customer_path =/system/csc/customer.xml
07-15 15:21:47.421  5714  5714 E CscParser: fileName + /system/csc/customer.xml
07-15 15:21:47.431  5714  5714 D CscParser: getInstance fileName =/system/csc/customer.xml
07-15 15:21:47.461  5714  5714 D Mms/MmsConfig:  enable multiwindow = false
07-15 15:21:47.461  5714  5714 E Mms/MessageUtils: setCountryDetector : update country detector info 
07-15 15:21:47.461  5714  5714 E Mms/MessageUtils: updateCountryIso : update country iso info 
07-15 15:21:47.471  5714  5714 D Mms/MmsConfig: [end]    init() consume time = 125.868073
07-15 15:21:47.471  5714  5714 D Mms/Contact: [start]    init() consume time = 0.7325
07-15 15:21:47.491  1456  1471 D TP/MmsSmsProvider: query,matched:13, calling pid = 5714
07-15 15:21:47.491  1456  1471 D TP/MmsSmsProvider: match 13:Elapsed time : 2.539 ms
07-15 15:21:47.501  5714  5714 D Mms/Contact: [end]    init consume time = 30.743698
07-15 15:21:47.521  5714  5775 D Mms/DraftCache: [start]    rebuildCache consume time = 16.797187
07-15 15:21:47.521  1456  1676 D TP/MmsSmsProvider: query,matched:12, calling pid = 5714
07-15 15:21:47.521  1456  1676 D TP/MmsSmsProvider: match 12:Elapsed time : 1.621 ms
07-15 15:21:47.531  5714  5775 D Mms/DraftCache: [end]    rebuildCache consume time = 13.661406
07-15 15:21:47.531  5714  5714 D Mms/MethodReflector: getSubId is called
07-15 15:21:47.531  5714  5714 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
07-15 15:21:47.541  5714  5714 D Mms/MethodReflector: getTelephonyProperty is called
07-15 15:21:47.541  5714  5714 D Mms/DownloadManager: roaming -> false (slotId = 0)
07-15 15:21:47.541  5714  5714 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
07-15 15:21:47.541  5714  5714 D Mms/DownloadManager: auto download without roaming -> true
07-15 15:21:47.541  5714  5714 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
07-15 15:21:47.541  5714  5714 D Mms/MethodReflector: getSubId is called
07-15 15:21:47.541  5714  5714 D Mms/MethodReflector: getDefaultSmsSubId is called
07-15 15:21:47.541  5714  5714 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
07-15 15:21:47.541  5714  5714 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
07-15 15:21:47.541  5714  5714 D Mms/MethodReflector: getTelephonyProperty is called
07-15 15:21:47.541  5714  5714 D Mms/DownloadManager: roaming -> false (slotId = 1)
07-15 15:21:47.541  5714  5714 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
07-15 15:21:47.541  5714  5714 D Mms/DownloadManager: auto download without roaming -> true
07-15 15:21:47.541  5714  5714 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
07-15 15:21:47.541  5714  5714 D Mms/DownloadManager: auto download during roaming secondary -> false
07-15 15:21:47.541  5714  5714 D Mms/DownloadManager: mAutoDownload ------> true
07-15 15:21:47.641  5714  5714 D ComposerPerformance: 1468588907642 ms / [DONE] Composer constructor
07-15 15:21:47.641  5714  5714 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
07-15 15:21:47.641  5714  5714 I Mms/ReservationManager: ReservationManager()
07-15 15:21:47.641  5714  5714 I Mms/ReservationManager: resetAfterConnected()
07-15 15:21:47.641  1456  4350 D TP/MmsSmsProvider: query,matched:7, calling pid = 5714
07-15 15:21:47.641  1456  4350 D TP/MmsSmsProvider: match 7:Elapsed time : 3.059 ms
07-15 15:21:47.651  5714  5714 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
07-15 15:21:47.651  5714  5714 D Mms/MmsApp: [end]    onCreate() consume time = 119.548594
07-15 15:21:47.651  5645  5666 W art     : Suspending all threads took: 5.143ms
07-15 15:21:47.661  5714  5778 D Mms/Conversation: [start]    init() consume time = 7.678542
07-15 15:21:47.661  1456  1475 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
07-15 15:21:47.661  1456  1475 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
07-15 15:21:47.661  1456  1475 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
07-15 15:21:47.661  1456  1475 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
07-15 15:21:47.671  1015  1296 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
07-15 15:21:47.671  1015  1296 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
07-15 15:21:47.671  1015  1296 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:47.671  1015  1296 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-15 15:21:47.671  1015  1296 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
07-15 15:21:47.671  1456  1475 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
07-15 15:21:47.671  1456  1475 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
07-15 15:21:47.681  5714  5714 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
07-15 15:21:47.681  5714  5714 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
07-15 15:21:47.681  5714  5714 D Mms/MethodReflector: getSubId is called
07-15 15:21:47.681  5714  5714 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
07-15 15:21:47.681  1456  1475 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
07-15 15:21:47.681  1456  1475 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
07-15 15:21:47.681  1456  1475 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
07-15 15:21:47.681  1456  1475 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
07-15 15:21:47.691  5714  5714 D Mms/MethodReflector: getTelephonyProperty is called
07-15 15:21:47.691  5714  5714 D Mms/DownloadManager: roaming -> false (slotId = 0)
07-15 15:21:47.691  5714  5714 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
07-15 15:21:47.691  5714  5714 D Mms/DownloadManager: auto download without roaming -> true
07-15 15:21:47.691  5714  5714 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
07-15 15:21:47.691  5714  5714 D Mms/DownloadManager: mAutoDownload ------> true
07-15 15:21:47.691  5714  5714 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
07-15 15:21:47.691  1015  1027 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
07-15 15:21:47.691  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
07-15 15:21:47.691  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:47.691  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-15 15:21:47.691  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
07-15 15:21:47.701  1015  1134 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
07-15 15:21:47.701  1456  1475 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
07-15 15:21:47.701  1456  1475 D TP/MmsSmsProvider: need read changed broadcast:false
07-15 15:21:47.701  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:47.701  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:47.701  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:47.701  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:47.711  1015  1134 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5781 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
07-15 15:21:47.711  5714  5778 D Mms/Conversation: [end]    init consume time = 57.368281
07-15 15:21:47.721  5714  5780 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
07-15 15:21:47.721  5714  5778 D Mms/MessagingNotification: [start]    init() consume time = 3.487969
07-15 15:21:47.721  5781  5781 E Zygote  : MountEmulatedStorage()
07-15 15:21:47.721  5781  5781 E Zygote  : v2
07-15 15:21:47.721  5781  5781 I libpersona: KNOX_SDCARD checking this for 10042
07-15 15:21:47.721  5781  5781 I libpersona: KNOX_SDCARD not a persona
07-15 15:21:47.721  5781  5781 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-15 15:21:47.731  5714  5780 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
07-15 15:21:47.731  5781  5781 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-15 15:21:47.731  1015  1516 I ActivityManager: Killing 5003:com.android.calendar/u0a131 (adj 15): empty #21
07-15 15:21:47.751  5781  5781 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
07-15 15:21:47.771  5714  5744 D Mms/ArtClassLoader: init [DONE] art
07-15 15:21:47.771  5781  5781 D TimaKeyStoreProvider: TimaSignature is unavailable
07-15 15:21:47.771  5781  5781 D ActivityThread: Added TimaKeyStore provider
07-15 15:21:47.881  1015  1476 I art     : Explicit concurrent mark sweep GC freed 145649(8MB) AllocSpace objects, 3(1855KB) LOS objects, 33% free, 22MB/33MB, paused 2.334ms total 153.737ms
07-15 15:21:47.891  5714  5778 D Mms/MessagingNotification: [end]    init consume time = 172.69901
07-15 15:21:47.891  1015  1516 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
07-15 15:21:47.891  1015  1516 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
07-15 15:21:47.891  1015  1516 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:47.891  1015  1516 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-15 15:21:47.891  1015  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
07-15 15:21:47.901  3251  3523 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
07-15 15:21:47.911  5714  5798 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 14.661354
07-15 15:21:47.911  5781  5781 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-15 15:21:47.911  5781  5781 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-15 15:21:47.911  5781  5781 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
07-15 15:21:47.911  5714  5799 D Mms/Synchronizer: [start]    doSync consume time = 2.119063
07-15 15:21:47.911  1456  1676 D TP/MmsSmsProvider: query,matched:0, calling pid = 5714
07-15 15:21:47.911  1456  1676 V TP/MmsSmsProvider: getSimpleConversations entered.
07-15 15:21:47.911  1456  4350 D TP/MmsSmsProvider: query,matched:400, calling pid = 5714
07-15 15:21:47.911  1456  1676 D TP/MmsSmsProvider: match 0:Elapsed time : 1.809 ms
07-15 15:21:47.911  1456  1471 D TP/MmsSmsProvider: update, matched:300, calling pid = 5714
07-15 15:21:47.911  5714  5798 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 5.156094
07-15 15:21:47.911  1456  1471 V TP/MmsSmsProvider: syncDBData start
07-15 15:21:47.911  1456  1471 V TP/MmsSmsProvider: syncDBData sms end
07-15 15:21:47.911  1456  1471 V TP/MmsSmsProvider: syncDBData mms end
07-15 15:21:47.921  1456  1471 V TP/MmsSmsProvider: syncDBData end
07-15 15:21:47.921  5714  5799 D Mms/Synchronizer: [end]    doSync consume time = 3.55927
07-15 15:21:47.931  1015  1495 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
07-15 15:21:47.941  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:47.941  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:47.941  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:47.941  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:47.951  5802  5802 E Zygote  : MountEmulatedStorage()
07-15 15:21:47.951  5802  5802 E Zygote  : v2
07-15 15:21:47.951  5802  5802 I libpersona: KNOX_SDCARD checking this for 10068
07-15 15:21:47.951  5802  5802 I libpersona: KNOX_SDCARD not a persona
07-15 15:21:47.951  5802  5802 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-15 15:21:47.961  5802  5802 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-15 15:21:47.961  1015  1495 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5802 uid=10068 gids={50068, 9997} abi=armeabi-v7a
07-15 15:21:47.961  5802  5802 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
07-15 15:21:47.981  5802  5802 D TimaKeyStoreProvider: TimaSignature is unavailable
07-15 15:21:47.981  5802  5802 D ActivityThread: Added TimaKeyStore provider
07-15 15:21:47.991  5645  5645 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
07-15 15:21:47.991  1015  1295 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
07-15 15:21:47.991  1015  1295 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:47.991  1015  1295 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:47.991  1015  1295 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:47.991  1015  1295 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.011  5818  5818 E Zygote  : MountEmulatedStorage()
07-15 15:21:48.011  5818  5818 E Zygote  : v2
07-15 15:21:48.011  5818  5818 I libpersona: KNOX_SDCARD checking this for 10148
07-15 15:21:48.011  5818  5818 I libpersona: KNOX_SDCARD not a persona
07-15 15:21:48.011  5818  5818 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-15 15:21:48.011  1015  1295 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=5818 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
07-15 15:21:48.011  5818  5818 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-15 15:21:48.011  5818  5818 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-15 15:21:48.021  1015  1522 I ActivityManager: Killing 4882:com.google.android.music:main/u0a108 (adj 15): empty #21
07-15 15:21:48.031  5818  5818 D TimaKeyStoreProvider: TimaSignature is unavailable
07-15 15:21:48.031  5818  5818 D ActivityThread: Added TimaKeyStore provider
07-15 15:21:48.031  3251  3523 D Icing   : Loaded CLD2 Version V2.0 - 20141016
07-15 15:21:48.051  5802  5802 D BadgeProvider: onCreate
07-15 15:21:48.051  5802  5802 D BadgeProvider: DatabaseHelper
07-15 15:21:48.061  1015  1497 I ActivityManager: Killing 5284:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #21
07-15 15:21:48.071  5714  5778 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
07-15 15:21:48.071  1456  4350 D TP/SmsProvider: query,matched:26, calling pid = 5714
07-15 15:21:48.071  1456  4350 D TP/SmsProvider: match 26:Elapsed time : 2.156 ms
07-15 15:21:48.081  5781  5781 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
07-15 15:21:48.081  1015  1055 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
07-15 15:21:48.081  1015  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
07-15 15:21:48.091  5818  5818 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
07-15 15:21:48.091  1456  1471 D TP/MmsSmsProvider: query,matched:6, calling pid = 5714
07-15 15:21:48.091  1456  1471 D TP/MmsSmsProvider: match 6:Elapsed time : 1.434 ms
07-15 15:21:48.091   283   283 E installd: system dir 0 : /system/app/
07-15 15:21:48.091   283   283 E installd: system dir 1 : /system/priv-app/
07-15 15:21:48.091   283   283 E installd: system dir 2 : /vendor/app/
07-15 15:21:48.091   283   283 E installd: system dir 3 : /oem/app/
07-15 15:21:48.111  1015  1522 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
07-15 15:21:48.111  1015  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.111  1015  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.111  1015  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.111  1015  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.111  1015  1055 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
07-15 15:21:48.121  5836  5836 E Zygote  : MountEmulatedStorage()
07-15 15:21:48.121  5836  5836 I libpersona: KNOX_SDCARD checking this for 1000
07-15 15:21:48.121  5836  5836 E Zygote  : v2
07-15 15:21:48.121  5836  5836 I libpersona: KNOX_SDCARD not a persona
07-15 15:21:48.121  5836  5836 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-15 15:21:48.121  1015  1522 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=5836 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-15 15:21:48.121  5836  5836 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-15 15:21:48.131  5836  5836 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-15 15:21:48.141  1015  1517 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
07-15 15:21:48.141  1015  1517 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.141  1015  1517 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.141  1015  1517 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.141  1015  1517 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.161  5572  5617 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
07-15 15:21:48.161  5852  5852 E Zygote  : MountEmulatedStorage()
07-15 15:21:48.161  5852  5852 E Zygote  : v2
07-15 15:21:48.161  5852  5852 I libpersona: KNOX_SDCARD checking this for 10023
07-15 15:21:48.161  5852  5852 I libpersona: KNOX_SDCARD not a persona
07-15 15:21:48.161  5852  5852 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-15 15:21:48.171  5852  5852 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-15 15:21:48.171  1015  1517 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5852 uid=10023 gids={50023, 9997} abi=armeabi-v7a
07-15 15:21:48.171  5852  5852 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-15 15:21:48.171  1015  1296 I ActivityManager: Killing 4602:com.google.android.talk/u0a102 (adj 15): empty #21
07-15 15:21:48.171  3251  3523 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
07-15 15:21:48.171  5836  5836 D TimaKeyStoreProvider: TimaSignature is unavailable
07-15 15:21:48.171  5836  5836 D ActivityThread: Added TimaKeyStore provider
07-15 15:21:48.181  5572  5617 I AcmsKeyStoreHelper: Key Store exist
07-15 15:21:48.181  5572  5617 I AcmsKeyStoreHelper: Hence loading the keystore file
07-15 15:21:48.191  5852  5852 D TimaKeyStoreProvider: TimaSignature is unavailable
07-15 15:21:48.191  5852  5852 D ActivityThread: Added TimaKeyStore provider
07-15 15:21:48.201  1015  1497 I ActivityManager: Killing 5426:com.google.android.gms:car/u0a11 (adj 15): empty #21
07-15 15:21:48.201  5836  5836 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
07-15 15:21:48.201  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
07-15 15:21:48.201  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:48.201  1015  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-15 15:21:48.201  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-15 15:21:48.211  1015  1134 I ActivityManager: Killing 5474:com.sec.spp.push/u0a32 (adj 15): empty #21
,07-15 15:21:48.241  1015  1516 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
07-15 15:21:48.241  5852  5852 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
07-15 15:21:48.241  1015  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.241  1015  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.241  1015  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.241  1015  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.261  5868  5868 E Zygote  : MountEmulatedStorage()
07-15 15:21:48.261  5868  5868 E Zygote  : v2
07-15 15:21:48.261  5868  5868 I libpersona: KNOX_SDCARD checking this for 10152
07-15 15:21:48.261  5868  5868 I libpersona: KNOX_SDCARD not a persona
07-15 15:21:48.261  5868  5868 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-15 15:21:48.261  5868  5868 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-15 15:21:48.261  5868  5868 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-15 15:21:48.271  5714  5778 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
07-15 15:21:48.271  1015  1516 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=5868 uid=10152 gids={50152, 9997} abi=armeabi-v7a
07-15 15:21:48.271  1015  1516 I ActivityManager: Killing 5482:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
07-15 15:21:48.281  5852  5852 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
07-15 15:21:48.281  5572  5617 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
07-15 15:21:48.281  5572  5617 I AcmsCertificateMngr: getKeyStoreForApplication success 
07-15 15:21:48.281  5852  5852 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
07-15 15:21:48.281  5572  5617 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
07-15 15:21:48.281  5572  5617 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
07-15 15:21:48.281  5572  5617 D AcmsServiceMonitor: Decrementing - Counter value: 1
07-15 15:21:48.281  5572  5617 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
07-15 15:21:48.281  5852  5852 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
07-15 15:21:48.291  5852  5852 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
07-15 15:21:48.291  5852  5852 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
07-15 15:21:48.291  5852  5852 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
07-15 15:21:48.291  5852  5852 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
07-15 15:21:48.301  5852  5852 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
07-15 15:21:48.301  5852  5852 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
07-15 15:21:48.301  5852  5852 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
07-15 15:21:48.301  5852  5852 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
07-15 15:21:48.301  5852  5852 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
07-15 15:21:48.301  5852  5852 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
07-15 15:21:48.311  5572  5617 D AcmsCore: This is NOT a valid MirrorLink app
07-15 15:21:48.311  5572  5617 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
07-15 15:21:48.311  5572  5617 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
07-15 15:21:48.311  5572  5617 D AcmsServiceMonitor: Decrementing - Counter value: 0
07-15 15:21:48.311  5572  5617 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
07-15 15:21:48.311  5868  5868 D TimaKeyStoreProvider: TimaSignature is unavailable
07-15 15:21:48.311  5868  5868 D ActivityThread: Added TimaKeyStore provider
07-15 15:21:48.321  5572  5572 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
07-15 15:21:48.321  5572  5572 D AcmsService: Enter onDestroy
07-15 15:21:48.321  1015  1134 D ActivityManager: startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
07-15 15:21:48.321  5572  5572 I AcmsService: cleanUp(): inside service clean up
07-15 15:21:48.321  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
07-15 15:21:48.321  5572  5572 D AcmsCore: AcmsCore: inside DeInit
07-15 15:21:48.321  5572  5572 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
07-15 15:21:48.321  5572  5572 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
07-15 15:21:48.321  5572  5572 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
07-15 15:21:48.321  5572  5572 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
07-15 15:21:48.321  5572  5572 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
07-15 15:21:48.331  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:48.331  1015  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-15 15:21:48.331  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
07-15 15:21:48.331  5572  5572 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
07-15 15:21:48.331  5572  5572 D AcmsService: killing acms process
07-15 15:21:48.331  5572  5572 I Process : Sending signal. PID: 5572 SIG: 9
07-15 15:21:48.331  1015  1497 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
07-15 15:21:48.341  1015  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.341  1015  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.341  1015  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.341  1015  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.341  5645  5645 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
07-15 15:21:48.351  5868  5868 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
07-15 15:21:48.351  5868  5868 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
07-15 15:21:48.351  5893  5893 E Zygote  : MountEmulatedStorage()
07-15 15:21:48.351  5893  5893 E Zygote  : v2
07-15 15:21:48.351  5893  5893 I libpersona: KNOX_SDCARD checking this for 1000
07-15 15:21:48.351  5893  5893 I libpersona: KNOX_SDCARD not a persona
07-15 15:21:48.351  5893  5893 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-15 15:21:48.361  5893  5893 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-15 15:21:48.361  5893  5893 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-15 15:21:48.361  1015  1497 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=5893 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-15 15:21:48.381  5868  5868 I TapandpayWidget:Utils: Clear T&P info.
07-15 15:21:48.381  5893  5893 D TimaKeyStoreProvider: TimaSignature is unavailable
07-15 15:21:48.381  5893  5893 D ActivityThread: Added TimaKeyStore provider
07-15 15:21:48.381  5868  5868 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
07-15 15:21:48.391  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
07-15 15:21:48.391  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.391  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.391  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.391  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.401  5909  5909 E Zygote  : MountEmulatedStorage()
07-15 15:21:48.401  5909  5909 E Zygote  : v2
07-15 15:21:48.401  5909  5909 I libpersona: KNOX_SDCARD checking this for 10009
07-15 15:21:48.401  5909  5909 I libpersona: KNOX_SDCARD not a persona
07-15 15:21:48.401  5909  5909 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-15 15:21:48.401  1015  1027 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=5909 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
07-15 15:21:48.411  1015  1027 I ActivityManager: Killing 5504:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
07-15 15:21:48.411  5909  5909 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-15 15:21:48.411  1015  1476 I ActivityManager: Process ACMS.Process (pid 5572)(adj 0) has died(45,790)
07-15 15:21:48.411  5909  5909 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
07-15 15:21:48.441  5909  5909 D TimaKeyStoreProvider: TimaSignature is unavailable
07-15 15:21:48.441  5909  5909 D ActivityThread: Added TimaKeyStore provider
07-15 15:21:48.441  5893  5893 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
07-15 15:21:48.441  5893  5893 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
07-15 15:21:48.441  1015  1134 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
07-15 15:21:48.441  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
07-15 15:21:48.451  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:48.451  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-15 15:21:48.451  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
07-15 15:21:48.451  5893  5893 I FilterInstaller: FilterPackageService : ACTION_CHANGED
07-15 15:21:48.461  5745  5762 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-15 15:21:48.471  5893  5924 E FilterInstaller: installFilters
07-15 15:21:48.481  5893  5924 E FilterInstaller: There is no requred permission
07-15 15:21:48.481  1015  3969 I ActivityManager: Killing 5521:com.samsung.helphub/1000 (adj 15): empty #21
07-15 15:21:48.491  5878  5878 D AndroidRuntime: 
07-15 15:21:48.491  5878  5878 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-15 15:21:48.491  5745  5762 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-15 15:21:48.491  5745  5762 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-15 15:21:48.491  5745  5762 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-15 15:21:48.491  5878  5878 D AndroidRuntime: CheckJNI is OFF
07-15 15:21:48.491  5878  5878 D AndroidRuntime: readGMSProperty: start
07-15 15:21:48.491  5878  5878 D AndroidRuntime: readGMSProperty: already setted!!
07-15 15:21:48.491  5878  5878 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-15 15:21:48.491  5878  5878 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-15 15:21:48.491  5878  5878 D AndroidRuntime: readGMSProperty: end
07-15 15:21:48.491  5878  5878 D AndroidRuntime: addProductProperty: start
07-15 15:21:48.611  1015  1497 I splitIntent: Queue : backgroundsplit_2 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
07-15 15:21:48.611  1015  1497 I ActivityManager: Killing 4592:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
07-15 15:21:48.641  5878  5878 E AffinityControl: AffinityControl: registerfunction enter
07-15 15:21:48.671  5878  5878 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-15 15:21:48.671  1015  1476 E PersonaManagerService: inState():  stateMachine is null !!
07-15 15:21:48.681  1015  1476 I PersonaManagerService: PersonaId don't exist
07-15 15:21:48.681  1015  1476 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-15 15:21:48.681  1015  1476 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-15 15:21:48.691  1015  1476 W ActivityManager: mDVFSHelper.acquire()
07-15 15:21:48.691   290   290 E SMD     : DCD OFF
07-15 15:21:48.691  1015  1476 D FocusedStackFrame: Set to : 0
07-15 15:21:48.701  1015  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.701  1015  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.701  1015  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.701  1015  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:48.701  1015  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-15 15:21:48.701  1015  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
07-15 15:21:48.711  5935  5935 E Zygote  : MountEmulatedStorage()
07-15 15:21:48.711  5935  5935 E Zygote  : v2
07-15 15:21:48.711  5935  5935 I libpersona: KNOX_SDCARD checking this for 10151
07-15 15:21:48.711  1015  1476 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-15 15:21:48.711  1015  1476 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5935 uid=10151 gids={50151, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-15 15:21:48.711  1015  1476 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-15 15:21:48.711  1015  1476 D InputDispatcher: Focused application set to: xxxx
07-15 15:21:48.711  1015  1476 D InputDispatcher: Focus left window: 1481
07-15 15:21:48.711  5935  5935 I libpersona: KNOX_SDCARD not a persona
07-15 15:21:48.711  5878  5878 D AndroidRuntime: Shutting down VM
07-15 15:21:48.721  5935  5935 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-15 15:21:48.721  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-15 15:21:48.721  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-15 15:21:48.721   257   257 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, uhalitest
07-15 15:21:48.721  5935  5935 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-15 15:21:48.721  5935  5935 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-15 15:21:48.741  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-15 15:21:48.741  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
07-15 15:21:48.751  5935  5935 D TimaKeyStoreProvider: TimaSignature is unavailable
07-15 15:21:48.751  5935  5935 D ActivityThread: Added TimaKeyStore provider
07-15 15:21:48.751  1015  1028 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-15 15:21:48.751  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-15 15:21:48.771  1015  1028 D PersonaManager: isKioskContainerExistOnDevice
07-15 15:21:48.781  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
07-15 15:21:48.811   257  1891 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
07-15 15:21:48.811   257  1095 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
07-15 15:21:48.811  1481  1481 V ActivityThread: updateVisibility : ActivityRecord{1180429 token=android.os.BinderProxy@2cf9adfd {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-15 15:21:48.811  1481  1481 D Launcher: onTrimMemory. Level: 20
07-15 15:21:48.881  5935  5935 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-15 15:21:48.891  5935  5935 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 2017-2018)
07-15 15:21:48.891  5935  5935 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-15 15:21:48.911  5935  5935 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {219dc24d}
07-15 15:21:48.911  5935  5935 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-15 15:21:48.911  5935  5935 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-15 15:21:48.921  5878  5878 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
07-15 15:21:48.951  5935  5935 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-15 15:21:48.951  5935  5935 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-15 15:21:48.951  5935  5935 E SysUtils: ApplicationContext is null in ApplicationStatus
07-15 15:21:48.961  5935  5952 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
07-15 15:21:48.971  5935  5935 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
07-15 15:21:48.971  5935  5935 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
07-15 15:21:48.971  5935  5935 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
07-15 15:21:48.981  5935  5935 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
07-15 15:21:48.981  5935  5935 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-15 15:21:48.981  5935  5935 I Adreno-EGL: Build Date: 04/06/15 Mon
07-15 15:21:48.981  5935  5935 I Adreno-EGL: Local Branch: 
07-15 15:21:48.981  5935  5935 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
07-15 15:21:48.981  5935  5935 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
07-15 15:21:48.981  5935  5935 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
07-15 15:21:49.101  5935  5961 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
07-15 15:21:49.151  5935  5935 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-15 15:21:49.161  5935  5935 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-15 15:21:49.171  5935  5935 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-15 15:21:49.171  5935  5935 D PhoneWindow: *FMB* installDecor flags : -2139027200
07-15 15:21:49.171  5935  5935 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
07-15 15:21:49.181  5935  5935 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-15 15:21:49.181  5935  5935 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-15 15:21:49.221  5935  5974 D OpenGLRenderer: Render dirty regions requested: true
07-15 15:21:49.231  1015  1134 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-15 15:21:49.231  1015  1134 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-15 15:21:49.231  1015  1134 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-15 15:21:49.231  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-15 15:21:49.231  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
07-15 15:21:49.241  5935  5935 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-15 15:21:49.241  5935  5935 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-15 15:21:49.251   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
07-15 15:21:49.251  1015  1516 D InputDispatcher: Focus entered window: 5935
07-15 15:21:49.261  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-15 15:21:49.261  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
07-15 15:21:49.261  5935  5935 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
07-15 15:21:49.261  5935  5974 I OpenGLRenderer: Initialized EGL, version 1.4
07-15 15:21:49.261  5935  5974 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
07-15 15:21:49.271  5935  5974 D OpenGLRenderer: Enabling debug mode 0
07-15 15:21:49.281  5935  5935 V ActivityThread: updateVisibility : ActivityRecord{2e87e5ac token=android.os.BinderProxy@aa063fe {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-15 15:21:49.291  1015  1517 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-15 15:21:49.291  1175  1175 I StatusBar: Icon Only
07-15 15:21:49.291  1175  1175 D PanelView: There is/are notification(s) 
07-15 15:21:49.291  1015  5976 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
07-15 15:21:49.331  1876  1876 I SamsungIME: getCurrentCandidateView
07-15 15:21:49.351  5935  5935 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-15 15:21:49.351  5935  5935 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@aa063fe time:122476
07-15 15:21:49.371  1015  1045 I ActivityManager: Displayed Component not be shown by security: +603ms (total +15s416ms)
07-15 15:21:49.371  1015  1045 W ActivityManager: mDVFSHelper.release()
07-15 15:21:49.371  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{324fb4e7 u0 com.test.thalitest/.MainActivity t98} time:122499
07-15 15:21:49.401   257   455 I SurfaceFlinger: id=11 Removed uhalitest (7/9)
07-15 15:21:49.401   257   445 I SurfaceFlinger: id=11 Removed uhalitest (-2/9)
07-15 15:21:49.451  1876  1876 D SamsungIME: Dismiss ExpandCandiate
07-15 15:21:49.451  5935  5935 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5935
07-15 15:21:49.571  5935  5935 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-15 15:21:49.601  1876  1876 I SamsungIME: getDebugLevel  : 0x4f4c
,07-15 15:21:49.631  1876  1876 I SamsungIME: getDebugLevel  : 0x4f4c
,07-15 15:21:49.641  1876  1876 I SamsungIME: KeybaordView init() : load resources
,07-15 15:21:49.651  5714  5714 I Mms/MmsApp:  start initViewCache mms,
07-15 15:21:49.651  5714  5714 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1734.179219
07-15 15:21:49.651  5714  5714 D Mms/ComposeMessageFragment: fillCache, easy = false
,07-15 15:21:49.681  1876  1876 I SamsungIME: getCurrentKeyboard
07-15 15:21:49.681  1876  1876 I SamsungIME: getTextKeyboard
,07-15 15:21:49.711  1876  1876 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-15 15:21:49.741  5935  5979 D jxcore_app_log: JniHelper::setJavaVM(0xb72832f0), pthread_self() = -1216482576
,07-15 15:21:49.751  5935  5979 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-15 15:21:49.751  5935  5979 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-15 15:21:49.751  5935  5979 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-15 15:21:49.751  5935  5979 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-15 15:21:49.751  5935  5979 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-15 15:21:49.751  5935  5979 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e2611dc added. We now have 1 listener(s)
,07-15 15:21:49.751  5714  5714 D AbsListView: Get MotionRecognitionManager
,07-15 15:21:49.751  1015  1495 D MotionRecognitionService:  ssp status : false
,07-15 15:21:49.761  5714  5714 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 106.186458
,07-15 15:21:49.761  5935  5979 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,07-15 15:21:49.761  5935  5979 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,07-15 15:21:49.761  5935  5979 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-15 15:21:49.771  5935  5979 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-15 15:21:49.771  5935  5979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-15 15:21:49.771  5935  5979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-15 15:21:49.771  5935  5979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-15 15:21:49.771  5935  5979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
07-15 15:21:49.771  5935  5979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-15 15:21:49.771  5935  5979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-15 15:21:49.771  5935  5979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-15 15:21:49.771  5935  5979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-15 15:21:49.771  5935  5979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-15 15:21:49.771  5935  5979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-15 15:21:49.771  5935  5979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-15 15:21:49.771  5935  5979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2578586b added. We now have 1 listener(s)
07-15 15:21:49.771  5935  5979 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-15 15:21:49.781  5935  5979 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-15 15:21:49.781  5935  5979 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,07-15 15:21:49.781  5935  5979 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-15 15:21:49.781  5935  5979 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,07-15 15:21:49.781  5935  5979 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,07-15 15:21:49.781  5935  5979 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-15 15:21:49.791  5935  5979 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-15 15:21:49.791  5935  5979 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41,
,07-15 15:21:49.791  5935  5979 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-15 15:21:49.791  5935  5979 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-15 15:21:49.791  5935  5979 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-15 15:21:49.791  5935  5979 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-15 15:21:49.791  5935  5979 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-15 15:21:49.791  5935  5979 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-15 15:21:49.791  5935  5979 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-15 15:21:49.791  5935  5979 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-15 15:21:49.791  5935  5979 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-15 15:21:49.791  5935  5979 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-15 15:21:49.791  5935  5979 D io.jxcore.node.ConnectivityMonitor: start: OK
07-15 15:21:49.801  5935  5979 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-15 15:21:49.801  5935  5979 D io.jxcore.node.JXcoreExtension: Unit Tests on
,07-15 15:21:49.821  5935  5935 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-15 15:21:49.851  5714  5714 D Mms/BubbleViewCache: fillCache bubble = 1
,07-15 15:21:49.981  1015  2737 D SSRM:n  : SIOP:: AP = 370
,07-15 15:21:50.321  5935  5985 W jxcore-log: Initializing JXcore engine
07-15 15:21:50.321  5935  5985 W jxcore-log: JXcore engine is ready
,07-15 15:21:50.381  1991  1991 E audit   : type=1400 msg=audit(1468588910.381:203): avc:  denied  { ioctl } for  pid=5985 comm="Thread-1068" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-15 15:21:50.381  1991  1991 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
07-15 15:21:50.381  1991  1991 E audit   : type=1300 msg=audit(1468588910.381:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9dd028f8 items=0 ppid=306 ppcomm=main pid=5985 auid=4294967295 uid=10151 gid=10151 euid=10151 suid=10151 fsuid=10151 egid=10151 sgid=10151 fsgid=10151 ses=4294967295 tty=(none) comm="Thread-1068" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-15 15:21:50.381  1991  1991 E audit   : type=1320 msg=audit(1468588910.381:203): 
,07-15 15:21:50.391  5935  5985 W jxcore-log: Starting JXcore engine
,07-15 15:21:50.491  5935  5985 W jxcore-log: Platform android
07-15 15:21:50.491  5935  5985 W jxcore-log: 
07-15 15:21:50.491  5935  5985 W jxcore-log: Process ARCH arm
07-15 15:21:50.491  5935  5985 W jxcore-log: 
,07-15 15:21:50.691  5935  5985 I jxcore-log: JXcore Cordova bridge is ready!
07-15 15:21:50.691  5935  5985 I jxcore-log: 
,07-15 15:21:50.691  5935  5985 W jxcore-log: JXcore engine is started
,07-15 15:21:50.701   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,07-15 15:21:50.701  5935  5979 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-15 15:21:50.701  5935  5935 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-15 15:21:50.711  5935  5985 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-15 15:21:50.711  5935  5985 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-15 15:21:50.721  5935  5935 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,07-15 15:21:50.721  5935  5935 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-15 15:21:50.721  1015  1497 D FocusedStackFrame: Set to : 0
07-15 15:21:50.721  1015  1497 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-15 15:21:50.721  1015  1497 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-15 15:21:50.721  1015  1497 D InputDispatcher: Focused application set to: xxxx
07-15 15:21:50.721  1015  1497 D InputDispatcher: Focus left window: 5935
07-15 15:21:50.731  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-15 15:21:50.731  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
07-15 15:21:50.731  1015  1497 I ActivityManager: Killing 5550:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
07-15 15:21:50.731  5935  5935 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-15 15:21:50.731  5935  5935 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-15 15:21:50.741  5935  5979 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 17ms. Plugin should use CordovaInterface.getThreadPool().
07-15 15:21:50.741  5935  5935 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:50.741  5935  5935 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-15 15:21:50.741  5935  5935 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-15 15:21:50.741  5935  5935 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-15 15:21:50.741  5935  5935 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e2611dc removed from the list
07-15 15:21:50.741  5935  5935 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:50.741  5935  5935 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2578586b removed from the list
07-15 15:21:50.741  5935  5935 D io.jxcore.node.ConnectivityMonitor: stop
07-15 15:21:50.741  5935  5935 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
07-15 15:21:50.741  5935  5935 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-15 15:21:50.761   257  1095 I SurfaceFlinger: id=12 Removed NainActivit (6/8)
,07-15 15:21:50.761   257  1891 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
,07-15 15:21:50.761  1015  1134 W ActivityManager: mDVFSHelper.acquire()
,07-15 15:21:50.771  1015  1134 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,07-15 15:21:50.791  1481  1481 D Launcher: onRestart, Launcher: 957429321
,07-15 15:21:50.791  1481  1481 D Launcher: onStart, Launcher: 957429321
,07-15 15:21:50.791  1481  1481 D Launcher.HomeView: onStart
,07-15 15:21:50.791  1481  1481 D Launcher: onResume, Launcher: 957429321
,07-15 15:21:50.801  1015  1516 D SettingsProvider: name = kids_home_mode
07-15 15:21:50.801  1015  1516 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-15 15:21:50.801  1015  1516 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-15 15:21:50.801  1015  1516 D SettingsProvider: selectionArgs: false
07-15 15:21:50.801  1015  1516 D SettingsProvider: selectionArgs: 10006
07-15 15:21:50.801  1015  1516 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-15 15:21:50.801  1015  1516 D SettingsProvider: ret = -1
,07-15 15:21:50.801  1481  1481 D Launcher.HomeView: onResume
,07-15 15:21:50.801  1481  1481 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,07-15 15:21:50.811  1481  1481 D MenuAppsGridFragment: onResume
,07-15 15:21:50.811  1481  1481 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,07-15 15:21:50.811  1015  1040 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:50.811  1481  1481 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,07-15 15:21:50.811  1015  1040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-15 15:21:50.811  1015  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,07-15 15:21:50.821  1015  1134 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
,07-15 15:21:50.821  1015  1134 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,07-15 15:21:50.821  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
,07-15 15:21:50.821  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-15 15:21:50.821  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,07-15 15:21:50.831  1015  1040 W ActivityManager: userId = 0, bbcId = -10000
,07-15 15:21:50.831  1015  1040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-15 15:21:50.831  1015  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,07-15 15:21:50.831  4962  4962 D GalleryCacheReady: Receive : home resume
,07-15 15:21:50.831  1015  1040 W ActivityManager: userId = 0, bbcId = -10000
,07-15 15:21:50.831  1015  1040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-15 15:21:50.831  1015  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
07-15 15:21:50.831  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
,07-15 15:21:50.841  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-15 15:21:50.841  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-15 15:21:50.841  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:50.841  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:50.851  5990  5990 E Zygote  : MountEmulatedStorage()
07-15 15:21:50.851  5990  5990 E Zygote  : v2
07-15 15:21:50.851  5990  5990 I libpersona: KNOX_SDCARD checking this for 10089
07-15 15:21:50.851  5990  5990 I libpersona: KNOX_SDCARD not a persona
,07-15 15:21:50.861  5990  5990 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,07-15 15:21:50.861  5990  5990 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-15 15:21:50.861  5990  5990 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
07-15 15:21:50.861  1015  1040 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=5990 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
,07-15 15:21:50.881  1015  1040 W ActivityManager: userId = 0, bbcId = -10000,
07-15 15:21:50.881  1015  1040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-15 15:21:50.881  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
07-15 15:21:50.881  1015  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,07-15 15:21:50.881  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-15 15:21:50.881  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:50.881  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:50.881  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-15 15:21:50.891  5990  5990 D TimaKeyStoreProvider: TimaSignature is unavailable
07-15 15:21:50.891   306   306 I art     : Explicit concurrent mark sweep GC freed 8683(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 28.756ms
,07-15 15:21:50.901  5990  5990 D ActivityThread: Added TimaKeyStore provider
,07-15 15:21:50.911   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 563us total 16.326ms
,07-15 15:21:50.921   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 563us total 16.142ms
,07-15 15:21:50.931  6006  6006 E Zygote  : MountEmulatedStorage(),
07-15 15:21:50.931  6006  6006 E Zygote  : v2
,07-15 15:21:50.931  6006  6006 I libpersona: KNOX_SDCARD checking this for 10139
07-15 15:21:50.931  6006  6006 I libpersona: KNOX_SDCARD not a persona
,07-15 15:21:50.931  6006  6006 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-15 15:21:50.941  6006  6006 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-15 15:21:50.941  1015  1040 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6006 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a,
07-15 15:21:50.941  1015  1476 D ActivityManager: handle home activity for 0
07-15 15:21:50.941  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
07-15 15:21:50.941  1015  1476 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
07-15 15:21:50.941  1015  1476 D KnoxTimeoutHandler: post home show event for user 0
07-15 15:21:50.941  1015  1476 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-15 15:21:50.941  1015  1476 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-15 15:21:50.941  1015  1476 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-15 15:21:50.941  1015  1015 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
07-15 15:21:50.941  1015  1015 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
07-15 15:21:50.941  1481  1481 D Launcher.HomeView: onPause
07-15 15:21:50.941  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-15 15:21:50.941  1481  1481 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
07-15 15:21:50.941  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:50.941  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-15 15:21:50.941  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
07-15 15:21:50.941  6006  6006 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-15 15:21:50.941  5714  5714 D Mms/UIEventReceiver: ui event
,07-15 15:21:50.961  1015  1296 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:50.961  1015  1296 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1481, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
07-15 15:21:50.961  1015  1296 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-15 15:21:50.961  1015  1296 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,07-15 15:21:50.971   257   257 I SurfaceFlinger: id=13 createSurf (540x960),1 flag=4, Mauncher
,07-15 15:21:50.971  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-15 15:21:50.981  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-15 15:21:50.981  5990  5990 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-15 15:21:50.981  5990  5990 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
07-15 15:21:50.981  1015  1495 D InputDispatcher: Focus entered window: 1481
,07-15 15:21:50.991  1481  1481 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
07-15 15:21:50.991  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-15 15:21:50.991  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,07-15 15:21:50.991  6006  6006 D TimaKeyStoreProvider: TimaSignature is unavailable
07-15 15:21:50.991  6006  6006 D ActivityThread: Added TimaKeyStore provider
,07-15 15:21:51.001  1015  3969 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-15 15:21:51.001  1015  6022 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-15 15:21:51.011  5935  5935 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,07-15 15:21:51.011  1876  1876 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,07-15 15:21:51.011  5986  5986 D AndroidRuntime: 
07-15 15:21:51.011  5986  5986 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,07-15 15:21:51.011  5986  5986 D AndroidRuntime: CheckJNI is OFF
,07-15 15:21:51.011  5986  5986 D AndroidRuntime: readGMSProperty: start
07-15 15:21:51.011  5986  5986 D AndroidRuntime: readGMSProperty: already setted!!
07-15 15:21:51.011  5986  5986 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-15 15:21:51.011  5986  5986 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-15 15:21:51.011  5986  5986 D AndroidRuntime: readGMSProperty: end
07-15 15:21:51.011  5986  5986 D AndroidRuntime: addProductProperty: start
,07-15 15:21:51.021  1175  1175 I StatusBar: Icon Only
07-15 15:21:51.021  1175  1175 D PanelView: There is/are notification(s) 
,07-15 15:21:51.041  1481  1481 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2cf9adfd time:124164
,07-15 15:21:51.041  1481  1481 D Launcher.HomeView: onStop
07-15 15:21:51.041  1481  1481 V ActivityThread: updateVisibility : ActivityRecord{1180429 token=android.os.BinderProxy@2cf9adfd {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,07-15 15:21:51.051  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,07-15 15:21:51.051  6006  6006 V TaskCloserActivity: TaskCloserActivity enter()
,07-15 15:21:51.051  1015  1040 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:51.051  1015  1040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-15 15:21:51.051  1015  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,07-15 15:21:51.051  2499  2499 D Recents_RecreateReceiver: onReceive by home
,07-15 15:21:51.051  6006  6006 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,07-15 15:21:51.061  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:51.061  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
07-15 15:21:51.061  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-15 15:21:51.061  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,07-15 15:21:51.061  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-15 15:21:51.061  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:51.061  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:51.061  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-15 15:21:51.071  6032  6032 E Zygote  : MountEmulatedStorage()
,07-15 15:21:51.071  6032  6032 E Zygote  : v2
,07-15 15:21:51.071  6032  6032 I libpersona: KNOX_SDCARD checking this for 10135
,07-15 15:21:51.071  6032  6032 I libpersona: KNOX_SDCARD not a persona
07-15 15:21:51.071  6032  6032 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-15 15:21:51.081  6032  6032 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-15 15:21:51.081  1015  1028 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6032 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
07-15 15:21:51.081  1015  1028 I ActivityManager: Killing 5306:com.samsung.android.sm/1000 (adj 15): empty #21
,07-15 15:21:51.081  6032  6032 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-15 15:21:51.081  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:51.081  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
07-15 15:21:51.081  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-15 15:21:51.081  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
07-15 15:21:51.081  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:51.081  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:51.081  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:51.081  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-15 15:21:51.101  6032  6032 D TimaKeyStoreProvider: TimaSignature is unavailable
07-15 15:21:51.111  6032  6032 D ActivityThread: Added TimaKeyStore provider
,07-15 15:21:51.111  6045  6045 E Zygote  : MountEmulatedStorage()
07-15 15:21:51.111  6045  6045 I libpersona: KNOX_SDCARD checking this for 10084
07-15 15:21:51.111  6045  6045 E Zygote  : v2
07-15 15:21:51.111  6045  6045 I libpersona: KNOX_SDCARD not a persona
,07-15 15:21:51.111  6045  6045 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
07-15 15:21:51.111  1015  1028 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6045 uid=10084 gids={50084, 9997} abi=armeabi-v7a
,07-15 15:21:51.121  6045  6045 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-15 15:21:51.121  6045  6045 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-15 15:21:51.121  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1e55c116 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t96} time:124246
07-15 15:21:51.121  1015  1045 W ActivityManager: mDVFSHelper.release()
,07-15 15:21:51.121  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:51.121  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-15 15:21:51.121  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,07-15 15:21:51.131  1015  1028 I ActivityManager: Killing 5537:com.osp.app.signin/u0a36 (adj 15): empty #21
,07-15 15:21:51.161  1015  1497 D PersonaManager: isKioskContainerExistOnDevice
,07-15 15:21:51.161  6045  6045 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-15 15:21:51.161  6045  6045 D ActivityThread: Added TimaKeyStore provider
07-15 15:21:51.161  5986  5986 E AffinityControl: AffinityControl: registerfunction enter
,07-15 15:21:51.181  6032  6032 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
07-15 15:21:51.181  6032  6032 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-15 15:21:51.181  6032  6032 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
07-15 15:21:51.181  6032  6032 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
07-15 15:21:51.181  6032  6032 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
07-15 15:21:51.181  6045  6045 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-15 15:21:51.191  1015  1296 I ActivityManager: Killing 5594:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,07-15 15:21:51.191  5986  5986 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-15 15:21:51.201  1015  1497 I splitIntent: Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,07-15 15:21:51.201  1015  1497 I ActivityManager: Killing 5627:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,07-15 15:21:51.201  1015  1040 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:51.201  1015  1497 D PackageManager: START PACKAGE DELETE: observer{846126007}
07-15 15:21:51.201  1015  1497 D PackageManager: pkg{<packageName>}
07-15 15:21:51.201  1015  1497 D PackageManager: user{0}
07-15 15:21:51.201  1015  1497 D PackageManager: caller{2000}
07-15 15:21:51.201  1015  1497 D PackageManager: flags{2}
07-15 15:21:51.201  1015  1040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-15 15:21:51.201  1015  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
07-15 15:21:51.201  1015  1497 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-15 15:21:51.201  1015  1497 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-15 15:21:51.201  1015  1497 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-15 15:21:51.201  1015  1497 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-15 15:21:51.211  1015  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-15 15:21:51.201  1015  1497 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-15 15:21:51.211  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-15 15:21:51.211  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-15 15:21:51.211  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
07-15 15:21:51.211  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
07-15 15:21:51.211  6006  6006 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,07-15 15:21:51.211  1015  1055 D PackageManager: !@killApplicatoin: 10151, uninstall pkg
,07-15 15:21:51.211  1015  1040 I ActivityManager: Force stopping com.test.thalitest appid=10151 user=-1: uninstall pkg
,07-15 15:21:51.211  1015  1040 I ActivityManager: Killing 5935:com.test.thalitest/u0a151 (adj 15): stop com.test.thalitest cause uninstall pkg
,07-15 15:21:51.341  1015  1055 I ActivityManager: Force stopping com.test.thalitest appid=10151 user=0: pkg removed
,07-15 15:21:51.361  1015  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,07-15 15:21:51.391  1015  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-15 15:21:51.391  1518  1790 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-15 15:21:51.391  1876  1876 E SamsungIME: mOCRHelper is null
,07-15 15:21:51.431  3925  3925 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jul 15 15:21:51 GMT+02:00 2016
,07-15 15:21:51.431  1443  1443 D PersonaManager: isKioskContainerExistOnDevice,
,07-15 15:21:51.441  1015  1015 D RCPManagerService: PackageReceiver onReceive()
,07-15 15:21:51.441  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,07-15 15:21:51.461  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
07-15 15:21:51.461  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
07-15 15:21:51.461  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10151 container id = 0
,07-15 15:21:51.461  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter
,07-15 15:21:51.461  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty
,07-15 15:21:51.461  1015  1121 V NetworkStats: removeUidsLocked() for UIDs [10151]
,07-15 15:21:51.471  1015  1121 V NetworkStats: performPollLocked(flags=0x3)
,07-15 15:21:51.471  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
07-15 15:21:51.471  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,07-15 15:21:51.471  1015  1121 V NetworkStats: performPollLocked() took 6ms
,07-15 15:21:51.471  1015  3969 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,07-15 15:21:51.471  1015  3969 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,07-15 15:21:51.481  1443  1443 D RegisteredServicesCache: empty dynamic service
,07-15 15:21:51.481  1015  3969 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:51.481  1015  3969 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-15 15:21:51.481  1015  3969 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,07-15 15:21:51.491  3925  3925 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,07-15 15:21:51.491  1015  1497 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=23, mSplitNum[2]=33, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=43
07-15 15:21:51.491  1015  1497 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,07-15 15:21:51.501  1015  1497 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,07-15 15:21:51.501  1015  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:51.501  1015  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-15 15:21:51.501  1015  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:51.501  1015  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-15 15:21:51.501  1015  1039 D EnterpriseDeviceManagerService: Package has changed for user 0
07-15 15:21:51.501  1015  1039 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,07-15 15:21:51.501  1015  1039 W TextServicesManagerService: no available spell checker services found
,07-15 15:21:51.511  6066  6066 E Zygote  : MountEmulatedStorage()
07-15 15:21:51.511  6066  6066 E Zygote  : v2
,07-15 15:21:51.511  6066  6066 I libpersona: KNOX_SDCARD checking this for 10090
07-15 15:21:51.511  6066  6066 I libpersona: KNOX_SDCARD not a persona,
,07-15 15:21:51.511  6066  6066 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-15 15:21:51.521  6066  6066 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-15 15:21:51.521  6066  6066 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-15 15:21:51.521  1015  1497 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6066 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,07-15 15:21:51.531  1443  1443 D RegisteredComponentCache: Collect Tech packages for Knox
,07-15 15:21:51.531  1443  1443 D PersonaManager: isKioskContainerExistOnDevice
,07-15 15:21:51.541  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-15 15:21:51.541  1015  1476 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-15 15:21:51.541  1015  1476 D SecContentProvider2: mCursor = null
,07-15 15:21:51.551  1015  1122 D NtpTrustedTime: forceRefresh() from cache miss
,07-15 15:21:51.551  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,07-15 15:21:51.551  3925  3925 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
07-15 15:21:51.551  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,07-15 15:21:51.551  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-15 15:21:51.551  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-15 15:21:51.551  1015  1015 V EnterpriseBillingPolicy: uID is 10151
07-15 15:21:51.551  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
07-15 15:21:51.551  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-15 15:21:51.551  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-15 15:21:51.551  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-15 15:21:51.551  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-15 15:21:51.551  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,07-15 15:21:51.551  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:51.551  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:51.551  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:51.551  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:51.551  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-15 15:21:51.561   277   941 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
07-15 15:21:51.561   277   941 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,07-15 15:21:51.561  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-15 15:21:51.561   277   941 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
07-15 15:21:51.561   277   941 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,07-15 15:21:51.561  1015  1122 D NtpTrustedTime: forceRefresh Fail.
,07-15 15:21:51.561  3925  3925 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-15 15:21:51.571  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-15 15:21:51.571  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,07-15 15:21:51.581  3925  3925 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false,
07-15 15:21:51.581  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-15 15:21:51.581  1015  1040 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=6083 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-15 15:21:51.581  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
07-15 15:21:51.581  1015  1015 V EnterpriseBillingPolicy: uID is 10151
07-15 15:21:51.581  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
07-15 15:21:51.581  1015  2737 D SSRM:bc : MSG_TYPE_APP_REMOVED::
07-15 15:21:51.581  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-15 15:21:51.581  3925  6065 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,07-15 15:21:51.581  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-15 15:21:51.581  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-15 15:21:51.581  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-15 15:21:51.581  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-15 15:21:51.581  3925  6065 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,07-15 15:21:51.591  6083  6083 E Zygote  : MountEmulatedStorage()
07-15 15:21:51.591  6083  6083 I libpersona: KNOX_SDCARD checking this for 10032
07-15 15:21:51.591  6083  6083 E Zygote  : v2
07-15 15:21:51.591  6083  6083 I libpersona: KNOX_SDCARD not a persona
07-15 15:21:51.591  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
07-15 15:21:51.591  6083  6083 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-15 15:21:51.591  3925  6065 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
07-15 15:21:51.591  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
07-15 15:21:51.591  6083  6083 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-15 15:21:51.591  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:51.591  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:51.591  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:51.591  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:51.591  6083  6083 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
07-15 15:21:51.591  1015  1015 V AlarmManagerEXT: com.test.thalitest(10151) is removed.
07-15 15:21:51.601  3925  6065 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,07-15 15:21:51.611  1015  1040 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6092 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
07-15 15:21:51.611  6066  6066 D TimaKeyStoreProvider: TimaSignature is unavailable
07-15 15:21:51.611  6066  6066 D ActivityThread: Added TimaKeyStore provider
07-15 15:21:51.611  6092  6092 E Zygote  : MountEmulatedStorage()
07-15 15:21:51.611  6092  6092 E Zygote  : v2
07-15 15:21:51.611  6092  6092 I libpersona: KNOX_SDCARD checking this for 10052
07-15 15:21:51.611  6092  6092 I libpersona: KNOX_SDCARD not a persona
07-15 15:21:51.611  6092  6092 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-15 15:21:51.621  6092  6092 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-15 15:21:51.621  6092  6092 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-15 15:21:51.631  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,07-15 15:21:51.641  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:51.641  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:51.641  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:51.641  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-15 15:21:51.641  6083  6083 D TimaKeyStoreProvider: TimaSignature is unavailable
07-15 15:21:51.641  6083  6083 D ActivityThread: Added TimaKeyStore provider
,07-15 15:21:51.651  6092  6092 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-15 15:21:51.651  6092  6092 D ActivityThread: Added TimaKeyStore provider
,07-15 15:21:51.651  6113  6113 E Zygote  : MountEmulatedStorage()
07-15 15:21:51.651  6113  6113 I libpersona: KNOX_SDCARD checking this for 10098
07-15 15:21:51.651  6113  6113 E Zygote  : v2
07-15 15:21:51.651  6113  6113 I libpersona: KNOX_SDCARD not a persona
07-15 15:21:51.651  6113  6113 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-15 15:21:51.661  6113  6113 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-15 15:21:51.661  6113  6113 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-15 15:21:51.661  1015  1040 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6113 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,07-15 15:21:51.691   290   290 E SMD     : DCD OFF
,07-15 15:21:51.701   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,07-15 15:21:51.711  6113  6113 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-15 15:21:51.711  1015  1055 I art     : Explicit concurrent mark sweep GC freed 42884(3MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 22MB/34MB, paused 4.213ms total 280.265ms
07-15 15:21:51.711  6113  6113 D ActivityThread: Added TimaKeyStore provider
,07-15 15:21:51.711  6066  6066 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,07-15 15:21:51.721  6066  6066 D elm:15121: ELMEngine.ELMEngine( context ).
,07-15 15:21:51.721  6066  6066 D elm:15121: MDMBridge.setEnterpriseBridge()
,07-15 15:21:51.731  1015  1495 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,07-15 15:21:51.731  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,07-15 15:21:51.731  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
,07-15 15:21:51.731  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-15 15:21:51.731  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,07-15 15:21:51.741  6066  6066 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,07-15 15:21:51.741  3383  3383 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,07-15 15:21:51.741  3383  3383 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,07-15 15:21:51.741  3383  3383 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
07-15 15:21:51.741  3383  3383 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-15 15:21:51.741  3383  3383 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
07-15 15:21:51.741  3383  3383 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
07-15 15:21:51.741  3383  3383 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
07-15 15:21:51.741  3383  3383 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:21:51.741  3383  3383 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-15 15:21:51.741  3383  3383 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-15 15:21:51.741  3383  3383 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:21:51.741  3383  3383 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-15 15:21:51.741  3383  3383 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-15 15:21:51.741  3383  3383 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,07-15 15:21:51.751  6066  6066 D elm:15121: ElmAgentService : onCreate()
,07-15 15:21:51.751  3925  6065 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,07-15 15:21:51.761  6066  6128 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,07-15 15:21:51.761  6066  6128 D elm:15121: MainReceiver.listeningToPackageRemoved()
07-15 15:21:51.761  6066  6128 D elm:15121: MDMBridge.getInstance()
07-15 15:21:51.761  6066  6128 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,07-15 15:21:51.761  1015  3969 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,07-15 15:21:51.771  6066  6128 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,07-15 15:21:51.781  1015  3969 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:51.781  3925  6065 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,07-15 15:21:51.781  1015  3969 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:51.781  1015  3969 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:51.781  1015  3969 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-15 15:21:51.781  3925  6065 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,07-15 15:21:51.791  6083  6130 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,07-15 15:21:51.791  6083  6130 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,07-15 15:21:51.791  6132  6132 E Zygote  : MountEmulatedStorage(),
07-15 15:21:51.801  6132  6132 E Zygote  : v2,
07-15 15:21:51.801  6132  6132 I libpersona: KNOX_SDCARD checking this for 1000
07-15 15:21:51.801  1015  1039 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
07-15 15:21:51.801  6132  6132 I libpersona: KNOX_SDCARD not a persona
,07-15 15:21:51.801  6132  6132 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-15 15:21:51.801  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-15 15:21:51.801  6132  6132 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-15 15:21:51.801  6132  6132 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-15 15:21:51.801  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-15 15:21:51.811  1015  3969 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6132 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-15 15:21:51.811  1015  1055 D PackageManager: delete codoeFile: 
,07-15 15:21:51.821  6083  6130 D SPPClientService: PushLog.txt file is not deleted.,
07-15 15:21:51.821  6083  6130 D SPPClientService: PushLog.txt file is not deleted.
07-15 15:21:51.821  6083  6130 D SPPClientService: ============PushLog. stop!
,07-15 15:21:51.821  6066  6066 D elm:15121: ElmAgentService : onDestroy().
,07-15 15:21:51.821  3925  3925 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,07-15 15:21:51.831  1015  1055 D AASAuninstall: userId = 0, info.removedAppID = 10151, info.uid = 10151, packageName = com.test.thalitest
,07-15 15:21:51.831  1015  1055 I AASA_removePackage: UID=10151 Target=com.test.thalitest
07-15 15:21:51.831  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-15 15:21:51.831  1015  1055 D PackageManager: result of delete: 1{846126007}
,07-15 15:21:51.841  1015  1495 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,07-15 15:21:51.841  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,07-15 15:21:51.841  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
,07-15 15:21:51.841  1015  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-15 15:21:51.841  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,07-15 15:21:51.841  1586  1586 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
07-15 15:21:51.841  1586  1586 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,07-15 15:21:51.851  5986  5986 D AndroidRuntime: Shutting down VM
,07-15 15:21:51.851  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,07-15 15:21:51.861  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:51.861  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:51.861  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:51.861  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-15 15:21:51.861  1015  1039 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
07-15 15:21:51.861  1015  1039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-15 15:21:51.861  1015  1039 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-15 15:21:51.861  6132  6132 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-15 15:21:51.861  6132  6132 D ActivityThread: Added TimaKeyStore provider
,07-15 15:21:51.861  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-15 15:21:51.871  1015  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-15 15:21:51.871  1015  1055 D PackageManager: userId{-1}
07-15 15:21:51.871  1015  1055 D PackageManager: andCode{true}
,07-15 15:21:51.871  6149  6149 E Zygote  : MountEmulatedStorage(),
,07-15 15:21:51.871  6149  6149 E Zygote  : v2
,07-15 15:21:51.871  6149  6149 I libpersona: KNOX_SDCARD checking this for 10032
07-15 15:21:51.871  6149  6149 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-15 15:21:51.871  6149  6149 I libpersona: KNOX_SDCARD not a persona
,07-15 15:21:51.871  6149  6149 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,07-15 15:21:51.871  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-15 15:21:51.871  6149  6149 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,07-15 15:21:51.881  1015  1027 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6149 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-15 15:21:51.881  1015  1027 I ActivityManager: Killing 5679:com.sec.pcw.device/1000 (adj 15): empty #21
,07-15 15:21:51.881  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-15 15:21:51.881  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-15 15:21:51.881  1015  1027 I ActivityManager: Killing 5393:com.android.vending/u0a26 (adj 15): empty #21
07-15 15:21:51.881  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-15 15:21:51.891  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-15 15:21:51.891  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-15 15:21:51.891  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-15 15:21:51.901  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-15 15:21:51.901  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-15 15:21:51.901  1015  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
07-15 15:21:51.901  1015  3969 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
07-15 15:21:51.901  1015  3969 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,07-15 15:21:51.901  1015  3969 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:51.901  1015  3969 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-15 15:21:51.901  1015  3969 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,07-15 15:21:51.901  6149  6149 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-15 15:21:51.901  6149  6149 D ActivityThread: Added TimaKeyStore provider
,07-15 15:21:51.911  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-15 15:21:51.921  3251  6164 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,07-15 15:21:51.921  3251  6164 D AccountUtils: Clearing selected account for com.test.thalitest
,07-15 15:21:51.931  6092  6148 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,07-15 15:21:51.931  1015  1039 D UsbSettingsManager: clearDefaults: com.test.thalitest
07-15 15:21:51.931  1015  1039 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,07-15 15:21:51.931  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-15 15:21:51.931  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,07-15 15:21:51.931  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-15 15:21:51.941  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-15 15:21:51.941  1015  3969 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-15 15:21:51.941  1015  3969 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
,07-15 15:21:51.941  1015  3969 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:51.941  1015  3969 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-15 15:21:51.941  1015  3969 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-15 15:21:51.941  3251  3251 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy}
07-15 15:21:51.941  3251  3251 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy} to Chimera receiver impl com.google.android.gms.games.receiver.PlaySystemBroadcastReceiver
07-15 15:21:51.941  3251  3251 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-15 15:21:51.941  3251  3251 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,07-15 15:21:51.951  1015  1517 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,07-15 15:21:51.951  3251  6164 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,07-15 15:21:51.951  1015  1517 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:51.951  1015  1517 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:51.951  1015  1517 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:51.951  1015  1517 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-15 15:21:51.981  6169  6169 E Zygote  : MountEmulatedStorage(),
07-15 15:21:51.981  6169  6169 E Zygote  : v2
07-15 15:21:51.981  6169  6169 I libpersona: KNOX_SDCARD checking this for 10055
07-15 15:21:51.981  6169  6169 I libpersona: KNOX_SDCARD not a persona
,07-15 15:21:51.981  6169  6169 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-15 15:21:51.991  6169  6169 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
07-15 15:21:51.991  6169  6169 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-15 15:21:52.001  1015  1517 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6169 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,07-15 15:21:52.001  1015  1028 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,07-15 15:21:52.001  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
,07-15 15:21:52.001  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:52.001  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-15 15:21:52.001  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-15 15:21:52.011  1015  1296 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-15 15:21:52.011  1015  1296 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:52.011  1015  1296 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-15 15:21:52.011  1015  1296 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-15 15:21:52.021  1015  1495 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,07-15 15:21:52.021  6169  6169 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-15 15:21:52.021  6169  6169 D ActivityThread: Added TimaKeyStore provider
,07-15 15:21:52.021  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:52.021  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:52.021  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:52.021  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-15 15:21:52.031  6186  6186 E Zygote  : MountEmulatedStorage()
,07-15 15:21:52.041  6186  6186 E Zygote  : v2
,07-15 15:21:52.041  6186  6186 I libpersona: KNOX_SDCARD checking this for 1000
07-15 15:21:52.041  6186  6186 I libpersona: KNOX_SDCARD not a persona
07-15 15:21:52.041  6186  6186 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-15 15:21:52.041  6149  6185 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,07-15 15:21:52.041  6149  6185 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
07-15 15:21:52.041  6186  6186 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-15 15:21:52.041  6186  6186 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-15 15:21:52.051  1015  1495 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6186 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-15 15:21:52.051  1015  1295 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
07-15 15:21:52.051  6149  6185 D SPPClientService: PushLog.txt file is not deleted.
07-15 15:21:52.051  6149  6185 D SPPClientService: PushLog.txt file is not deleted.
07-15 15:21:52.051  6149  6185 D SPPClientService: ============PushLog. stop!
,07-15 15:21:52.051  1015  1295 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:52.051  1015  1295 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-15 15:21:52.051  1015  1295 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-15 15:21:52.061  5986  5986 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,07-15 15:21:52.071   306   306 I art     : Explicit concurrent mark sweep GC freed 8700(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 638us total 33.237ms
,07-15 15:21:52.081  3251  6184 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1,
07-15 15:21:52.081  3251  6184 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
07-15 15:21:52.081  6186  6186 D TimaKeyStoreProvider: TimaSignature is unavailable
07-15 15:21:52.081  6186  6186 D ActivityThread: Added TimaKeyStore provider
,07-15 15:21:52.081  3251  3251 D ChimeraSrvcProxy: Creating service proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy}
07-15 15:21:52.081  3251  3251 D ChimeraSrvcProxy: Proxying container service ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy} to Chimera service impl com.google.android.gms.games.service.PlayGamesAsyncService
07-15 15:21:52.081  3251  3251 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-15 15:21:52.081  3251  3251 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,07-15 15:21:52.091  1586  1586 I ConfigService: onDestroy
07-15 15:21:52.091  1015  1517 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,07-15 15:21:52.091  1015  1517 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-15 15:21:52.091  1015  1517 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:52.091  1015  1517 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:52.091  1015  1517 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:52.091   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 584us total 18.760ms
,07-15 15:21:52.091  3251  6184 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
,07-15 15:21:52.091  3251  6184 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,07-15 15:21:52.111   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 580us total 16.657ms
,07-15 15:21:52.111  3251  6184 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
07-15 15:21:52.111  3251  6184 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,07-15 15:21:52.111  3251  6184 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,07-15 15:21:52.121  6169  6169 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,07-15 15:21:52.131  6207  6207 E Zygote  : MountEmulatedStorage(),
07-15 15:21:52.131  6207  6207 E Zygote  : v2
07-15 15:21:52.131  6207  6207 I libpersona: KNOX_SDCARD checking this for 10014
07-15 15:21:52.131  6207  6207 I libpersona: KNOX_SDCARD not a persona
07-15 15:21:52.131  6207  6207 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-15 15:21:52.131  6207  6207 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
07-15 15:21:52.131  6207  6207 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-15 15:21:52.131  3251  6184 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
07-15 15:21:52.141  1015  1517 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6207 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
07-15 15:21:52.131  3251  6184 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
07-15 15:21:52.141  1015  1516 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-15 15:21:52.141  3251  6184 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
07-15 15:21:52.141  1015  1516 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
07-15 15:21:52.141  1015  1516 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:52.141  1015  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:52.141  1015  1516 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-15 15:21:52.141  1015  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:52.141  1015  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-15 15:21:52.141  1015  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:52.141  1015  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-15 15:21:52.161  6207  6207 D TimaKeyStoreProvider: TimaSignature is unavailable
07-15 15:21:52.161  6169  6169 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,07-15 15:21:52.161  6169  6169 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
07-15 15:21:52.161  6169  6169 D UserAnalysis: Create SecureDbHelper
,07-15 15:21:52.161  6207  6207 D ActivityThread: Added TimaKeyStore provider,
07-15 15:21:52.171  6223  6223 E Zygote  : MountEmulatedStorage()
07-15 15:21:52.171  6223  6223 E Zygote  : v2
07-15 15:21:52.171  6223  6223 I libpersona: KNOX_SDCARD checking this for 10011
07-15 15:21:52.171  6223  6223 I libpersona: KNOX_SDCARD not a persona
07-15 15:21:52.171  1015  1516 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=6223 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,07-15 15:21:52.171  6223  6223 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-15 15:21:52.171  6223  6223 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
07-15 15:21:52.171  6223  6223 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-15 15:21:52.181  1015  1296 D LocationManagerService: getProviders()=[passive, gps]
,07-15 15:21:52.181  6169  6169 D IntelligenceServiceApplication: onCreate()
,07-15 15:21:52.191  6169  6169 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
07-15 15:21:52.191  1015  1495 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,07-15 15:21:52.191  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:52.191  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:52.191  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:52.191  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-15 15:21:52.201  6169  6169 D IntelligenceServiceApplication: no applications having user consent for prediction
,07-15 15:21:52.211  6239  6239 E Zygote  : MountEmulatedStorage()
,07-15 15:21:52.211  6239  6239 E Zygote  : v2
07-15 15:21:52.211  6239  6239 I libpersona: KNOX_SDCARD checking this for 10036
07-15 15:21:52.211  6239  6239 I libpersona: KNOX_SDCARD not a persona
07-15 15:21:52.211  1015  1495 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver: pid=6239 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-15 15:21:52.211  6223  6223 D TimaKeyStoreProvider: TimaSignature is unavailable
07-15 15:21:52.211  1015  1495 I ActivityManager: Killing 5696:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
,07-15 15:21:52.211  6239  6239 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-15 15:21:52.211  6223  6223 D ActivityThread: Added TimaKeyStore provider
,07-15 15:21:52.211  1015  1522 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-15 15:21:52.211  1015  1522 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:52.211  1015  1522 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-15 15:21:52.211  1015  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-15 15:21:52.221  6239  6239 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-15 15:21:52.221  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,07-15 15:21:52.221  6239  6239 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,07-15 15:21:52.221  1015  1495 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
07-15 15:21:52.221  6169  6169 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,07-15 15:21:52.231  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:52.231  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:52.231  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:52.231  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-15 15:21:52.241  6239  6239 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-15 15:21:52.251  6239  6239 D ActivityThread: Added TimaKeyStore provider
,07-15 15:21:52.251  6260  6260 E Zygote  : MountEmulatedStorage()
07-15 15:21:52.251  6260  6260 I libpersona: KNOX_SDCARD checking this for 1000
07-15 15:21:52.251  6260  6260 E Zygote  : v2
07-15 15:21:52.251  6260  6260 I libpersona: KNOX_SDCARD not a persona
,07-15 15:21:52.261  1015  1495 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=6260 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-15 15:21:52.261  1015  1495 I ActivityManager: Killing 5781:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
07-15 15:21:52.261  6223  6223 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-15 15:21:52.261  6223  6223 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-15 15:21:52.271  6260  6260 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-15 15:21:52.271  6260  6260 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-15 15:21:52.271  6260  6260 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-15 15:21:52.281  5645  5645 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,07-15 15:21:52.291  1015  6222 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-15 15:21:52.291  1015  6222 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
07-15 15:21:52.291  1015  6222 W ActivityManager: userId = 0, bbcId = -10000
07-15 15:21:52.291  1015  6222 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-15 15:21:52.291  1015  6222 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-15 15:21:52.291  6260  6260 D TimaKeyStoreProvider: TimaSignature is unavailable
07-15 15:21:52.291  1015  1134 I ActivityManager: Killing 5604:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,07-15 15:21:52.291  6260  6260 D ActivityThread: Added TimaKeyStore provider
,07-15 15:21:52.301  6169  6169 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,07-15 15:21:52.301  6169  6169 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,07-15 15:21:52.311  1015  1495 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,07-15 15:21:52.311  6169  6169 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
07-15 15:21:52.311  6169  6169 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-15 15:21:52.311  6169  6169 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-15 15:21:52.311  6169  6169 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-15 15:21:52.311  6169  6169 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-15 15:21:52.311  6169  6169 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-15 15:21:52.311  6169  6169 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-15 15:21:52.311  6169  6169 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-15 15:21:52.311  6169  6169 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-15 15:21:52.311  6169  6169 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-15 15:21:52.311  6169  6169 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-15 15:21:52.311  6169  6169 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-15 15:21:52.311  6169  6169 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-15 15:21:52.311  6169  6169 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-15 15:21:52.311  6169  6169 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-15 15:21:52.311  6169  6169 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
07-15 15:21:52.311  6169  6169 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
07-15 15:21:52.311  6169  6169 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-15 15:21:52.311  6169  6169 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-15 15:21:52.311  6169  6169 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-15 15:21:52.311  6169  6169 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-15 15:21:52.311  6169  6169 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:21:52.311  6169  6169 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-15 15:21:52.311  6169  6169 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-15 15:21:52.311  6169  6169 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-15 15:21:52.311  6169  6169 D AndroidRuntime: Shutting down VM
,07-15 15:21:52.311  6169  6169 E AndroidRuntime: FATAL EXCEPTION: main
07-15 15:21:52.311  6169  6169 E AndroidRuntime: Process: com.samsung.android.intelligenceservice, PID: 6169
07-15 15:21:52.311  6169  6169 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-15 15:21:52.311  6169  6169 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-15 15:21:52.311  6169  6169 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-15 15:21:52.311  6169  6169 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-15 15:21:52.311  6169  6169 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-15 15:21:52.311  6169  6169 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-15 15:21:52.311  6169  6169 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-15 15:21:52.311  6169  6169 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-15 15:21:52.311  6169  6169 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-15 15:21:52.311  6169  6169 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-15 15:21:52.311  6169  6169 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-15 15:21:52.311  6169  6169 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-15 15:21:52.311  6169  6169 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-15 15:21:52.311  6169  6169 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-15 15:21:52.311  6169  6169 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
07-15 15:21:52.311  6169  6169 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
07-15 15:21:52.311  6169  6169 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
07-15 15:21:52.311  6169  6169 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-15 15:21:52.311  6169  6169 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
07-15 15:21:52.311  6169  6169 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-15 15:21:52.311  6169  6169 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:21:52.311  6169  6169 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-15 15:21:52.311  6169  6169 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-15 15:21:52.311  6169  6169 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-15 15:21:52.311  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:52.311  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:52.311  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:52.311  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-15 15:21:52.321  6260  6260 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-15 15:21:52.321  6186  6186 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 

```
