#### Test 79763830cfa9ed9_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
08-26 15:42:33.928  6630  6630 D Mms/Contact: [end]    init consume time = 26.619688
08-26 15:42:33.928  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:33.928  1017  1546 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:33.928  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 15:42:33.928  6630  6834 D Mms/DraftCache: [start]    rebuildCache consume time = 7.342812
--------- beginning of system
08-26 15:42:33.928  1017  1546 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:42:33.928  1017  1546 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-26 15:42:33.938  1458  1486 D TP/MmsSmsProvider: query,matched:12, calling pid = 6630
08-26 15:42:33.938  1458  1486 D TP/MmsSmsProvider: match 12:Elapsed time : 2.486 ms
08-26 15:42:33.938  1017  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-26 15:42:33.938  1017  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 15:42:33.938  1017  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 15:42:33.948  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:42:33.948  6630  6834 D Mms/DraftCache: [end]    rebuildCache consume time = 15.195157
08-26 15:42:33.948  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:42:33.948  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:42:33.948  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:42:33.948  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-26 15:42:33.958  6630  6630 D Mms/MethodReflector: getSubId is called
08-26 15:42:33.958  6630  6630 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-26 15:42:33.958  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:42:33.968  6630  6630 D Mms/MethodReflector: getTelephonyProperty is called
08-26 15:42:33.968  6630  6630 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-26 15:42:33.968  6630  6630 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-26 15:42:33.968  6630  6630 D Mms/DownloadManager: auto download without roaming -> true
08-26 15:42:33.968  6630  6630 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-26 15:42:33.968  6630  6630 D Mms/MethodReflector: getSubId is called
08-26 15:42:33.978  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:42:33.978  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-26 15:42:33.978  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:42:33.978  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-26 15:42:33.978  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:42:33.978  6630  6630 D Mms/MethodReflector: getDefaultSmsSubId is called
08-26 15:42:33.978  6630  6630 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
08-26 15:42:33.978  6630  6630 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
08-26 15:42:33.978  6630  6630 D Mms/MethodReflector: getTelephonyProperty is called
08-26 15:42:33.978  6630  6630 D Mms/DownloadManager: roaming -> false (slotId = 1)
08-26 15:42:33.978  6630  6630 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-26 15:42:33.978  6630  6630 D Mms/DownloadManager: auto download without roaming -> true
08-26 15:42:33.978  6630  6630 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-26 15:42:33.978  6630  6630 D Mms/DownloadManager: auto download during roaming secondary -> false
08-26 15:42:33.978  6630  6630 D Mms/DownloadManager: mAutoDownload ------> true
08-26 15:42:33.988  1832  6691 W BaseAppContext: Using Auth Proxy for data requests.
08-26 15:42:33.998  1017  1041 I CrashAnrDetector: onPackageAdded : com.test.thalitest
08-26 15:42:34.038  6630  6630 D ComposerPerformance: 1472218954041 ms / [DONE] Composer constructor
08-26 15:42:34.038  6630  6630 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
08-26 15:42:34.038  6630  6630 I Mms/ReservationManager: ReservationManager()
08-26 15:42:34.038  6630  6630 I Mms/ReservationManager: resetAfterConnected()
08-26 15:42:34.038  1458  1661 D TP/MmsSmsProvider: query,matched:7, calling pid = 6630
08-26 15:42:34.038  1458  1661 D TP/MmsSmsProvider: match 7:Elapsed time : 1.963 ms
08-26 15:42:34.038  1017  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-26 15:42:34.048  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:34.048  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:34.048  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
08-26 15:42:34.048  6630  6630 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
08-26 15:42:34.058  6630  6630 D Mms/MmsApp: [end]    onCreate() consume time = 0.015521
08-26 15:42:34.058  6630  6838 D Mms/Conversation: [start]    init() consume time = 111.246666
08-26 15:42:34.058  1458  2484 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-26 15:42:34.068  1458  2484 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-26 15:42:34.068  1017  3830 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-26 15:42:34.068  1458  2484 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
08-26 15:42:34.068  1458  2484 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
08-26 15:42:34.068  1017  3830 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:34.068  1017  3830 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:34.068  1017  3830 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 15:42:34.078  1458  2484 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-26 15:42:34.078  1458  2484 D TP/MmsSmsProvider: need read changed broadcast:false
08-26 15:42:34.078  6630  6838 D Mms/Conversation: [end]    init consume time = 23.177813
08-26 15:42:34.088  6630  6838 D Mms/MessagingNotification: [start]    init() consume time = 3.592395
08-26 15:42:34.088  6630  6838 D Mms/MessagingNotification: [end]    init consume time = 1.97125
08-26 15:42:34.088  6630  6839 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 3.681823
08-26 15:42:34.088  6630  6840 D Mms/Synchronizer: [start]    doSync consume time = 1.603907
08-26 15:42:34.098  1458  2484 D TP/MmsSmsProvider: query,matched:400, calling pid = 6630
08-26 15:42:34.098  1458  1786 D TP/MmsSmsProvider: query,matched:0, calling pid = 6630
08-26 15:42:34.098  6630  6630 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
08-26 15:42:34.098  1458  1786 V TP/MmsSmsProvider: getSimpleConversations entered.
08-26 15:42:34.098  6630  6630 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
08-26 15:42:34.108  6630  6839 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 10.56401
08-26 15:42:34.108  1458  1786 D TP/MmsSmsProvider: match 0:Elapsed time : 9.286 ms
08-26 15:42:34.108  6630  6630 D Mms/MethodReflector: getSubId is called
08-26 15:42:34.108  6630  6630 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-26 15:42:34.108  6630  6630 D Mms/MethodReflector: getTelephonyProperty is called
08-26 15:42:34.108  6630  6630 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-26 15:42:34.128  1458  1486 D TP/MmsSmsProvider: update, matched:300, calling pid = 6630
08-26 15:42:34.128  1458  1486 V TP/MmsSmsProvider: syncDBData start
08-26 15:42:34.128  1458  1486 V TP/MmsSmsProvider: syncDBData sms end
08-26 15:42:34.128  1458  1486 V TP/MmsSmsProvider: syncDBData mms end
08-26 15:42:34.128  1458  1486 V TP/MmsSmsProvider: syncDBData end
08-26 15:42:34.138  6630  6630 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-26 15:42:34.138  6630  6630 D Mms/DownloadManager: auto download without roaming -> true
08-26 15:42:34.138  6630  6630 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-26 15:42:34.138  6630  6630 D Mms/DownloadManager: mAutoDownload ------> true
08-26 15:42:34.138  6630  6630 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
08-26 15:42:34.148  6630  6840 D Mms/Synchronizer: [end]    doSync consume time = 40.020521
08-26 15:42:34.148  1017  3829 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-26 15:42:34.148  1017  3829 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
08-26 15:42:34.158  1017  3829 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:34.158  1017  3829 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:34.158  1017  3829 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
08-26 15:42:34.158  6630  6760 D Mms/ArtClassLoader: init [DONE] art
08-26 15:42:34.158  1017  1456 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:42:34.168  1017  1456 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-26 15:42:34.168  1832  6654 I qtaguid : Untagging socket 96
08-26 15:42:34.168  1017  1456 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:34.168  1017  1456 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:34.168  1017  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 15:42:34.168  1017  1136 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
08-26 15:42:34.168  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:34.168  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:34.168  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:34.168  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:34.178  1832  1832 I ConfigFetchService: fetch service done; releasing wakelock
08-26 15:42:34.188  1832  1832 I ConfigFetchService: stopping self
08-26 15:42:34.188  6842  6842 I libpersona: KNOX_SDCARD checking this for 10042
08-26 15:42:34.188  6842  6842 E Zygote  : MountEmulatedStorage()
08-26 15:42:34.188  6842  6842 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:34.188  6842  6842 E Zygote  : v2
08-26 15:42:34.188  6842  6842 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:42:34.188  6842  6842 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:34.188  6842  6842 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
08-26 15:42:34.188  1017  1136 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6842 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
08-26 15:42:34.198  1017  1029 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
08-26 15:42:34.198  6630  6841 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
08-26 15:42:34.198  6630  6841 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
08-26 15:42:34.198  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:34.198  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:34.198  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:34.198  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:34.198  6591  6653 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 702 ms] updated apps [took 702 ms] 
08-26 15:42:34.218  6851  6851 E Zygote  : MountEmulatedStorage()
08-26 15:42:34.218  6851  6851 E Zygote  : v2
08-26 15:42:34.218  6851  6851 I libpersona: KNOX_SDCARD checking this for 10068
08-26 15:42:34.218  6851  6851 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:34.218  6851  6851 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:42:34.228  6851  6851 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:34.228  6851  6851 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-26 15:42:34.238  1017  1029 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6851 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-26 15:42:34.238  1017  3830 I ActivityManager: Killing 6397:com.android.calendar/u0a131 (adj 15): empty #21
08-26 15:42:34.248  1017  3827 I ActivityManager: Killing 6486:com.sec.android.app.videoplayer/u0a45 (adj 15): empty #21
08-26 15:42:34.248  6842  6842 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:42:34.248  6842  6842 D ActivityThread: Added TimaKeyStore provider
08-26 15:42:34.268  6851  6851 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:42:34.268  6851  6851 D ActivityThread: Added TimaKeyStore provider
08-26 15:42:34.278  1017  1489 I ActivityManager: Killing 6467:com.android.defcontainer/u0a3 (adj 15): empty #21
08-26 15:42:34.298  6842  6842 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 15:42:34.308  6842  6842 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-26 15:42:34.308  6851  6851 D BadgeProvider: onCreate
08-26 15:42:34.308  6842  6842 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-26 15:42:34.308  1017  1030 I art     : Explicit concurrent mark sweep GC freed 143558(8MB) AllocSpace objects, 6(1895KB) LOS objects, 33% free, 23MB/34MB, paused 2.811ms total 200.025ms
08-26 15:42:34.308  6851  6851 D BadgeProvider: DatabaseHelper
08-26 15:42:34.348  6630  6838 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
08-26 15:42:34.348  1458  1486 D TP/SmsProvider: query,matched:26, calling pid = 6630
08-26 15:42:34.348  1458  1486 D TP/SmsProvider: match 26:Elapsed time : 1.289 ms
08-26 15:42:34.358  1017  1488 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-26 15:42:34.358  1458  1786 D TP/MmsSmsProvider: query,matched:6, calling pid = 6630
08-26 15:42:34.358  1458  1786 D TP/MmsSmsProvider: match 6:Elapsed time : 1.439 ms
08-26 15:42:34.388  1017  1456 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
08-26 15:42:34.388  1017  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:34.388  1017  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:34.388  1017  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:34.388  1017  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:34.398  6872  6872 E Zygote  : MountEmulatedStorage()
08-26 15:42:34.398  6872  6872 E Zygote  : v2
08-26 15:42:34.398  6872  6872 I libpersona: KNOX_SDCARD checking this for 10023
08-26 15:42:34.398  6872  6872 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:34.398  6872  6872 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:42:34.398  6872  6872 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:34.398  1017  1456 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6872 uid=10023 gids={50023, 9997} abi=armeabi-v7a
08-26 15:42:34.408  6872  6872 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 15:42:34.428   305   305 I art     : Explicit concurrent mark sweep GC freed 8695(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 607us total 28.513ms
08-26 15:42:34.438  6872  6872 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:42:34.438  6872  6872 D ActivityThread: Added TimaKeyStore provider
08-26 15:42:34.448  1017  1489 I ActivityManager: Killing 6215:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
08-26 15:42:34.458   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 20.979ms
08-26 15:42:34.458  6842  6842 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-26 15:42:34.468  1017  1057 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
08-26 15:42:34.468  1017  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-26 15:42:34.468  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:34.468  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:34.468  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:34.468  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:34.468   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 16.663ms
08-26 15:42:34.488  6889  6889 E Zygote  : MountEmulatedStorage()
08-26 15:42:34.488  6889  6889 E Zygote  : v2
08-26 15:42:34.488  6889  6889 I libpersona: KNOX_SDCARD checking this for 10003
08-26 15:42:34.488  6889  6889 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:34.488  6889  6889 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:42:34.488  6889  6889 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:34.488  6889  6889 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 15:42:34.518  1017  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6889 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-26 15:42:34.518  6889  6889 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:42:34.518  1017  3827 I ActivityManager: Killing 6526:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
08-26 15:42:34.518  6889  6889 D ActivityThread: Added TimaKeyStore provider
08-26 15:42:34.548  6872  6872 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
08-26 15:42:34.568   284   284 E installd: system dir 0 : /system/app/
08-26 15:42:34.568   284   284 E installd: system dir 1 : /system/priv-app/
08-26 15:42:34.568   284   284 E installd: system dir 2 : /vendor/app/
08-26 15:42:34.568   284   284 E installd: system dir 3 : /oem/app/
08-26 15:42:34.568  6630  6838 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
08-26 15:42:34.578  1017  1057 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-26 15:42:34.598  6872  6872 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
08-26 15:42:34.598  6872  6872 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-26 15:42:34.598  6872  6872 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
08-26 15:42:34.598  6872  6872 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
08-26 15:42:34.608  6872  6872 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
08-26 15:42:34.608  6872  6872 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
08-26 15:42:34.608  6872  6872 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
08-26 15:42:34.608  6872  6872 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
08-26 15:42:34.608  6872  6872 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
08-26 15:42:34.608  6872  6872 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
08-26 15:42:34.618  6872  6872 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
08-26 15:42:34.618  6872  6872 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
08-26 15:42:34.618  6872  6872 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
08-26 15:42:34.658  6699  6790 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-26 15:42:34.658  6699  6790 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-26 15:42:34.658  6699  6790 I GAv4    :   adb logcat -s GAv4
,08-26 15:42:34.688  6699  6790 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-26 15:42:34.698  1017  1227 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-26 15:42:34.718  6699  6790 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
08-26 15:42:34.758  6699  6790 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
08-26 15:42:34.758  6699  6912 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
08-26 15:42:34.808  6610  6650 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
08-26 15:42:34.828  6610  6650 I AcmsKeyStoreHelper: Key Store exist
08-26 15:42:34.828  6610  6650 I AcmsKeyStoreHelper: Hence loading the keystore file
08-26 15:42:34.888  1017  1546 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
08-26 15:42:34.888  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:34.888  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:34.888  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:34.888  6610  6650 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
08-26 15:42:34.888  6610  6650 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-26 15:42:34.888  6610  6650 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-26 15:42:34.888  6610  6650 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-26 15:42:34.888  6610  6650 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-26 15:42:34.888  6610  6650 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
08-26 15:42:34.888  6610  6650 D AcmsCore: This is NOT a valid MirrorLink app
08-26 15:42:34.888  6610  6650 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-26 15:42:34.888  6610  6650 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-26 15:42:34.888  6610  6650 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-26 15:42:34.888  6610  6650 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
08-26 15:42:34.888  1017  1546 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:34.898  6916  6916 E Zygote  : MountEmulatedStorage()
08-26 15:42:34.898  6916  6916 E Zygote  : v2
08-26 15:42:34.898  6916  6916 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:42:34.898  6916  6916 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:34.908  6916  6916 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:42:34.908  6916  6916 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:34.908  6916  6916 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 15:42:34.908  1017  1546 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=6916 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 15:42:34.908  6610  6610 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-26 15:42:34.908  1017  1546 I ActivityManager: Killing 5052:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
08-26 15:42:34.908  6610  6610 D AcmsService: Enter onDestroy
08-26 15:42:34.908  6610  6610 I AcmsService: cleanUp(): inside service clean up
08-26 15:42:34.908  6610  6610 D AcmsCore: AcmsCore: inside DeInit
08-26 15:42:34.908  6610  6610 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
08-26 15:42:34.908  6610  6610 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
08-26 15:42:34.908  6610  6610 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-26 15:42:34.908  6610  6610 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-26 15:42:34.908  6610  6610 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
08-26 15:42:34.908  6610  6610 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-26 15:42:34.908  6610  6610 D AcmsService: killing acms process
08-26 15:42:34.908  6610  6610 I Process : Sending signal. PID: 6610 SIG: 9
08-26 15:42:34.938  6909  6909 D AndroidRuntime: 
08-26 15:42:34.938  6909  6909 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 15:42:34.938  6909  6909 D AndroidRuntime: CheckJNI is OFF
08-26 15:42:34.938  6909  6909 D AndroidRuntime: readGMSProperty: start
08-26 15:42:34.938  6909  6909 D AndroidRuntime: readGMSProperty: already setted!!
08-26 15:42:34.938  6909  6909 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-26 15:42:34.938  6909  6909 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-26 15:42:34.938  6909  6909 D AndroidRuntime: readGMSProperty: end
08-26 15:42:34.938  6909  6909 D AndroidRuntime: addProductProperty: start
08-26 15:42:34.948  6916  6916 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:42:34.948  6916  6916 D ActivityThread: Added TimaKeyStore provider
08-26 15:42:34.978  1017  1227 I ActivityManager: Process ACMS.Process (pid 6610)(adj 0) has died(61,758)
08-26 15:42:34.978  6916  6916 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
08-26 15:42:34.978  6916  6916 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
08-26 15:42:34.978  1017  1544 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
08-26 15:42:34.988  1017  1544 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
08-26 15:42:34.988  1017  1544 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:34.988  1017  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:34.988  1017  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
08-26 15:42:34.988  1017  3830 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
08-26 15:42:34.988  6916  6916 I FilterInstaller: FilterPackageService : ACTION_CHANGED
08-26 15:42:35.008  6916  6932 E FilterInstaller: installFilters
08-26 15:42:35.008  6916  6932 E FilterInstaller: There is no requred permission
08-26 15:42:35.008  1017  1546 I ActivityManager: Killing 6552:com.sec.spp.push/u0a32 (adj 15): empty #21
08-26 15:42:35.038  6699  6914 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-26 15:42:35.038  6699  6914 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-26 15:42:35.068  6699  6914 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
08-26 15:42:35.068  1017  1017 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
08-26 15:42:35.068  1017  1017 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
08-26 15:42:35.078  1017  1393 D NtpTrustedTime: forceRefresh() from cache miss
08-26 15:42:35.088   278   995 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 15:42:35.088   278   995 D Netd    : getNetworkForDns: using netid 502 for uid 1000
08-26 15:42:35.088  1017  1017 I BackgroundCompactionService: onStart. jobID=801
08-26 15:42:35.088  1017  1017 I BackgroundCompactionService: onStart done. jobID=801
08-26 15:42:35.088  1017  6941 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
08-26 15:42:35.098  6909  6909 E AffinityControl: AffinityControl: registerfunction enter
08-26 15:42:35.098  1017  6941 I BackgroundCompactionService: compact_memory command done
08-26 15:42:35.118  6909  6909 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-26 15:42:35.128  6699  6914 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-26 15:42:35.128  6699  6914 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1d217dfa: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-26 15:42:35.128  6699  6914 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-26 15:42:35.138  1017  1544 E PersonaManagerService: inState():  stateMachine is null !!
08-26 15:42:35.138  1017  1544 I PersonaManagerService: PersonaId don't exist
08-26 15:42:35.138  1017  1544 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-26 15:42:35.148  1017  1544 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 15:42:35.158  1017  1393 D NtpTrustedTime: requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1472218955596 mCachedNtpElapsedRealtime : 94762 mCachedNtpCertainty : 9
08-26 15:42:35.158  1017  1393 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:35.158  1017  1393 D AlarmManagerService: Setting time of day to sec=1472218955
08-26 15:42:35.158  1017  1393 D AlarmManagerService: Trying to open a file
08-26 15:42:35.158  1017  1393 D AlarmManagerService: File Open Success
08-26 15:42:35.158  1017  1393 D AlarmManagerService: File Close Success
08-26 15:42:35.596  1017  1095 V AlarmManager: waitForAlarm result :65536
08-26 15:42:35.158  1017  1393 I AlarmManagerService: DRM_TIME_PATH CHMOD 666 for resetState done 
08-26 15:42:35.596  1017  1393 W AlarmManagerService: Unable to set rtc to 1472218955: Invalid argument
08-26 15:42:35.596  1017  1544 W ActivityManager: mDVFSHelper.acquire()
08-26 15:42:35.596  1017  1544 D FocusedStackFrame: Set to : 0
08-26 15:42:35.615  1017  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:35.615  1017  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:35.615  1017  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:35.615  1017  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:35.615  1017  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-26 15:42:35.615  1017  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-26 15:42:35.635  6945  6945 E Zygote  : MountEmulatedStorage()
08-26 15:42:35.635  6945  6945 I libpersona: KNOX_SDCARD checking this for 10170
08-26 15:42:35.635  6945  6945 E Zygote  : v2
08-26 15:42:35.635  6945  6945 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:35.635  1832  4349 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
08-26 15:42:35.635  1017  1544 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6945 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-26 15:42:35.635  1017  1544 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-26 15:42:35.635  1017  1544 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 15:42:35.635  1017  1544 D InputDispatcher: Focused application set to: xxxx
08-26 15:42:35.635  1017  1544 D InputDispatcher: Focus left window: 1490
08-26 15:42:35.635  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-26 15:42:35.635  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-26 15:42:35.635   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-26 15:42:35.635  6945  6945 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:42:35.645  6909  6909 D AndroidRuntime: Shutting down VM
08-26 15:42:35.645  1017  1095 V AlarmManager: No more alarm at this time.nowELAPSED=94823 batch.start=107976
08-26 15:42:35.645  6945  6945 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:35.645  1017  1017 D OTPFW   : OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1472218955655
08-26 15:42:35.655  6945  6945 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-26 15:42:35.655  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
08-26 15:42:35.655  1177  1177 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_SET
08-26 15:42:35.665  1017  1017 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
08-26 15:42:35.665  1017  1017 I DowntimeConditions: android.intent.action.TIME_SET ignored because schedule turned off.
08-26 15:42:35.665  1177  1177 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 15:42:35.675  1177  1177 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
08-26 15:42:35.675  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 15:42:35.675  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-26 15:42:35.675  1017  1017 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:35.675  6945  6945 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:42:35.685  6945  6945 D ActivityThread: Added TimaKeyStore provider
08-26 15:42:35.685  1177  1177 D SecKeyguardClockView: HomeTimezone(): 1
08-26 15:42:35.685  1017  1489 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-26 15:42:35.695  1017  1017 I DrmEventService:  no response from SecureClock 
08-26 15:42:35.695  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-26 15:42:35.695  1017  1488 D SettingsProvider: name = lockscreen_zoom_panning_effect
08-26 15:42:35.695  1017  1488 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:35.695  1017  1488 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:35.695  1017  1488 D SettingsProvider: selectionArgs: false
08-26 15:42:35.695  1017  1488 D SettingsProvider: selectionArgs: 10049
08-26 15:42:35.695  1017  1488 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:35.695  1017  1488 D SettingsProvider: ret = -1
08-26 15:42:35.695  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-26 15:42:35.715  1017  1489 D PersonaManager: isKioskContainerExistOnDevice
08-26 15:42:35.715  1017  1017 I splitIntent: intent=android.intent.action.TIME_SET will be not split. because same process=com.google.android.gms is in other queue. index=4
08-26 15:42:35.715  1017  1017 I splitIntent: base  index=4, name=com.google.android.gms com.google.android.gms.checkin.CheckinService$Receiver
08-26 15:42:35.715  1017  1017 I splitIntent: other index=7, name=com.google.android.gms com.google.android.gms.reminders.notification.NotificationReceiver
08-26 15:42:35.715  1017  1017 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.TIME_SET !! do not split it!!
08-26 15:42:35.725  1017  1488 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10049
08-26 15:42:35.725  1017  1017 V ActivityManager: Display changed displayId=0
08-26 15:42:35.725  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
08-26 15:42:35.725  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:35.725  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:35.725  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:35.725  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:35.725  1832  4349 D Icing   : Loaded CLD2 Version V2.0 - 20141016
08-26 15:42:35.725  1177  1177 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
08-26 15:42:35.735  1177  1177 D KeyguardEffectViewController: isPreloadedWallpaper=true
08-26 15:42:35.735  1177  1177 I GeometricMosaic_Keyguard: update
08-26 15:42:35.735  1177  1177 D KeyguardEffectViewUtil: getCurrentWallpaper() mWallpaperPath :null
08-26 15:42:35.735  6962  6962 E Zygote  : MountEmulatedStorage()
08-26 15:42:35.735  6962  6962 I libpersona: KNOX_SDCARD checking this for 10008
08-26 15:42:35.735  6962  6962 E Zygote  : v2
08-26 15:42:35.735  6962  6962 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:35.745  6962  6962 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:42:35.745  6962  6962 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:35.745  1017  1017 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6962 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 15:42:35.745  6962  6962 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-26 15:42:35.755   258  1102 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
08-26 15:42:35.755   258  1937 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
08-26 15:42:35.755   288   288 E SMD     : DCD OFF
08-26 15:42:35.765  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-26 15:42:35.765  1177  1203 I art     : Background sticky concurrent mark sweep GC freed 9229(528KB) AllocSpace objects, 1(16KB) LOS objects, 0% free, 20MB/20MB, paused 8.664ms total 24.345ms
08-26 15:42:35.785  6962  6962 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:42:35.785  6962  6962 D ActivityThread: Added TimaKeyStore provider
08-26 15:42:35.785  1490  1490 V ActivityThread: updateVisibility : ActivityRecord{198f94cf token=android.os.BinderProxy@213181a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-26 15:42:35.785  1490  1490 D Launcher: onTrimMemory. Level: 20
08-26 15:42:35.835  1177  1177 I KeyguardEffectViewUtil: set current wallpaper info
08-26 15:42:35.835  1017  1545 D SettingsProvider: name = keyguard_current_wallpaper_type
08-26 15:42:35.835  1017  1545 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:35.835  1017  1545 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:35.835  1017  1545 D SettingsProvider: selectionArgs: false
08-26 15:42:35.835  1017  1545 D SettingsProvider: selectionArgs: 10049
08-26 15:42:35.835  1017  1545 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:35.835  1017  1545 D SettingsProvider: ret = -1
08-26 15:42:35.845  1832  4349 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
08-26 15:42:35.855  6909  6909 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-26 15:42:35.865  1017  1545 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,08-26 15:42:35.865  1017  1488 D SettingsProvider: name = keyguard_current_wallpaper_file_path
,08-26 15:42:35.865  1017  1488 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:35.865  1017  1488 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:35.865  1017  1488 D SettingsProvider: selectionArgs: false
08-26 15:42:35.865  1017  1488 D SettingsProvider: selectionArgs: 10049
08-26 15:42:35.865  1017  1488 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:35.865  1017  1488 D SettingsProvider: ret = -1
,08-26 15:42:35.875  1017  1488 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,08-26 15:42:35.875  6962  6962 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-26 15:42:35.875  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-26 15:42:35.875  1017  1136 D SettingsProvider: name = keyguard_current_wallpaper_res_id
08-26 15:42:35.875  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:35.875  6945  6945 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-26 15:42:35.875  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:35.875  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:35.875  1017  1136 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 15:42:35.875  1017  1136 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:35.875  1017  1136 D SettingsProvider: selectionArgs: false
08-26 15:42:35.875  1017  1136 D SettingsProvider: selectionArgs: 10049
,08-26 15:42:35.875  1017  1136 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:35.875  1017  1136 D SettingsProvider: ret = -1
,08-26 15:42:35.885  1017  1136 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,08-26 15:42:35.905  6962  6962 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,08-26 15:42:35.905  1017  1307 I ActivityManager: Killing 6540:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,08-26 15:42:35.915  1017  3829 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:42:35.915  1017  3829 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,08-26 15:42:35.915  1017  3829 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:35.915  1017  3829 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:35.915  1017  3829 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:35.935  6945  6945 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 5112-5114)
,08-26 15:42:35.935  6945  6945 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-26 15:42:35.955  1017  1545 I ActivityManager: Killing 6574:com.samsung.helphub/1000 (adj 15): empty #21
,08-26 15:42:35.965  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:42:35.965  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:42:35.965  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:42:35.965  1177  1604 D TEST    : run!!!
,08-26 15:42:35.965  6945  6945 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {159f764}
,08-26 15:42:35.965  6945  6945 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-26 15:42:35.975  1177  1177 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,08-26 15:42:35.975  1017  1227 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 15:42:35.975  1017  1227 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,08-26 15:42:35.975  1017  1227 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:35.975  1017  1227 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:35.975  1017  1227 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:35.975  6945  6945 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 15:42:35.985  1177  1604 I GeometricMosaic_Renderer: setBackgroundBitmap
,08-26 15:42:35.985  1177  1177 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
08-26 15:42:35.985  1177  1177 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-26 15:42:35.995  2849  2849 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Fri Aug 26 15:42:35 GMT+02:00 2016
,08-26 15:42:35.995  1017  3829 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-26 15:42:35.995  1017  3829 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-26 15:42:35.995  1017  3829 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:35.995  1017  3829 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:42:35.995  1017  3829 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-26 15:42:35.995  1177  1177 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-26 15:42:35.995  2849  2849 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-26 15:42:35.995  1017  3830 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-26 15:42:36.005  1017  3830 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:36.005  1017  3830 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:36.005  1017  3830 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:36.005  1017  3830 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:36.005  1177  1177 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-26 15:42:36.005  2849  2849 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-26 15:42:36.015  6983  6983 E Zygote  : MountEmulatedStorage()
08-26 15:42:36.015  6983  6983 E Zygote  : v2
08-26 15:42:36.015  6983  6983 I libpersona: KNOX_SDCARD checking this for 10036
08-26 15:42:36.015  6983  6983 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:36.015  6983  6983 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:36.015  2849  2849 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-26 15:42:36.015  1017  3830 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=6983 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 15:42:36.015  1177  1177 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
08-26 15:42:36.015  6983  6983 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:42:36.025  6983  6983 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-26 15:42:36.025  2849  2849 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-26 15:42:36.025  1177  1177 D KeyguardEffectViewController: isPreloadedWallpaper=true
,08-26 15:42:36.025  2849  6982 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,08-26 15:42:36.035  6945  6945 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-26 15:42:36.035  2849  6982 I KLMS-2.5.123: : KLMSIntentService(): TIME_CHANGED
,08-26 15:42:36.035  6945  6945 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 15:42:36.035  2849  6982 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().START : Fri Aug 26 15:42:36 GMT+02:00 2016
,08-26 15:42:36.045  6983  6983 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:36.045  6945  6945 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 15:42:36.045  6983  6983 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:36.055  2849  6982 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().END
,08-26 15:42:36.055  2849  2849 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-26 15:42:36.075  6983  6983 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@27251acc
,08-26 15:42:36.085  6983  6983 I SA      : [SSP] onCreated
,08-26 15:42:36.105  6983  6983 I SA      : [TPM] There is no property file
,08-26 15:42:36.105  6983  6983 I SA      : [SCU] isHaveSA() - false
,08-26 15:42:36.105  6983  6983 I SA      : [TPM] getModelProperty : null
08-26 15:42:36.105  6983  6983 I SA      : [TPM] getCSCProperty : null
,08-26 15:42:36.105  6983  6983 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-26 15:42:36.105  6983  6983 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-26 15:42:36.105  6983  6983 I SA      : [DM] TFT FEATURE: false
,08-26 15:42:36.105  6945  6945 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 15:42:36.105  6945  6945 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 15:42:36.105  6945  6945 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 15:42:36.105  6945  6945 I Adreno-EGL: Local Branch: 
08-26 15:42:36.105  6945  6945 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 15:42:36.105  6945  6945 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 15:42:36.105  6945  6945 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 15:42:36.115  6983  6983 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
08-26 15:42:36.115  6983  6983 I SA      : [DM] init START
,08-26 15:42:36.115  6983  6983 I SA      : [DM] This device is not a Vodafone
,08-26 15:42:36.125  6983  6983 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-26 15:42:36.125  6983  6983 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-26 15:42:36.125  6983  6983 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-26 15:42:36.125  6983  6983 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-26 15:42:36.125  6983  6983 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-26 15:42:36.125  6983  6983 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-26 15:42:36.125  6983  6983 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-26 15:42:36.125  6983  6983 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-26 15:42:36.125  6983  6983 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-26 15:42:36.125  6983  6983 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-26 15:42:36.125  6983  6983 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-26 15:42:36.125  6983  6983 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-26 15:42:36.125  6983  6983 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-26 15:42:36.125  6983  6983 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-26 15:42:36.125  6983  6983 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-26 15:42:36.135  6983  6983 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-26 15:42:36.135  6983  6983 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,08-26 15:42:36.135  6983  6983 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-26 15:42:36.135  6983  6983 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
08-26 15:42:36.135  6983  6983 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-26 15:42:36.135  6983  6983 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-26 15:42:36.135  6983  6983 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
08-26 15:42:36.135  6983  6983 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-26 15:42:36.135  6983  6983 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-26 15:42:36.135  6983  6983 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-26 15:42:36.135  6983  6983 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-26 15:42:36.135  6983  6983 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-26 15:42:36.135  6983  6983 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-26 15:42:36.145  6983  6983 I SA      : [SCU] isHaveSA() - false
,08-26 15:42:36.145  6983  6983 I SA      : support phone number id : false
08-26 15:42:36.145  6983  6983 I SA      : [DM] Supports Ref Jpn : true
08-26 15:42:36.145  6983  6983 I SA      : [DM] init END
,08-26 15:42:36.215  6945  6945 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 15:42:36.215  1017  1042 W ActivityManager: Activity pause timeout for ActivityRecord{eade948 u0 com.test.thalitest/.MainActivity t163}
,08-26 15:42:36.225  6945  6945 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-26 15:42:36.225  6945  6945 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-26 15:42:36.245  6945  6945 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-26 15:42:36.245  6945  6945 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-26 15:42:36.275  1017  1488 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,08-26 15:42:36.275  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:36.275  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:36.275  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:36.275  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:36.285  7017  7017 E Zygote  : MountEmulatedStorage()
,08-26 15:42:36.285  7017  7017 E Zygote  : v2
08-26 15:42:36.285  7017  7017 I libpersona: KNOX_SDCARD checking this for 10058
08-26 15:42:36.285  7017  7017 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:36.285  1017  1488 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=7017 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 15:42:36.285  1017  1488 I ActivityManager: Killing 6237:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
08-26 15:42:36.285  7017  7017 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:36.295  7017  7017 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 15:42:36.295  7017  7017 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:42:36.305  7017  7017 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:36.305  7017  7017 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:36.365  7017  7017 I ExternalOEMControlProvider: onCreate
,08-26 15:42:36.385  1017  1029 I ActivityManager: Killing 6153:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-26 15:42:36.385  6945  6945 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 15:42:36.385  1775  1775 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,08-26 15:42:36.385  1775  1775 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-26 15:42:36.385  1017  1307 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,08-26 15:42:36.395  1017  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:36.395  1017  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:36.395  1017  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:36.395  1017  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:36.395  7017  7035 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,08-26 15:42:36.405  7036  7036 E Zygote  : MountEmulatedStorage(),
08-26 15:42:36.405  6945  6945 W AwContents: onDetachedFromWindow called when already detached. Ignoring,
,08-26 15:42:36.405  7036  7036 E Zygote  : v2,
08-26 15:42:36.405  7036  7036 I libpersona: KNOX_SDCARD checking this for 10081
08-26 15:42:36.405  7036  7036 I libpersona: KNOX_SDCARD not a persona,
,08-26 15:42:36.405  7036  7036 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:36.415  1017  1307 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=7036 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 15:42:36.415  7036  7036 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 15:42:36.415  7036  7036 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:42:36.415  6945  6945 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-26 15:42:36.415  6945  6945 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-26 15:42:36.425  6945  6945 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-26 15:42:36.435  6945  6945 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 15:42:36.435  6945  6945 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 15:42:36.445  7036  7036 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:36.445  7036  7036 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:36.455  7036  7036 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-26 15:42:36.455  7036  7036 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-26 15:42:36.465  7036  7036 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 15:42:36.465  7036  7036 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 15:42:36.465  7036  7036 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,08-26 15:42:36.475  6945  7055 D OpenGLRenderer: Render dirty regions requested: true
,08-26 15:42:36.485  1017  1136 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-26 15:42:36.485  1017  1136 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-26 15:42:36.485  1017  1136 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-26 15:42:36.485  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-26 15:42:36.485  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,08-26 15:42:36.485  6630  6630 I Mms/MmsApp:  start initViewCache mms
,08-26 15:42:36.485  6630  6630 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1916.514009
,08-26 15:42:36.485  6630  6630 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-26 15:42:36.495  6945  7011 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
08-26 15:42:36.495  6945  6945 V ActivityThread: updateVisibility : ActivityRecord{166a52d7 token=android.os.BinderProxy@253cf471 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-26 15:42:36.495  6945  6945 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-26 15:42:36.495  6945  6945 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-26 15:42:36.515   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-26 15:42:36.515  1017  1029 D SettingsProvider: name = next_alarm_formatted
08-26 15:42:36.515  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:36.515  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:36.515  1017  1029 D SettingsProvider: selectionArgs: false
08-26 15:42:36.515  1017  1029 D SettingsProvider: selectionArgs: 10081
08-26 15:42:36.515  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:36.515  1017  1029 D SettingsProvider: ret = -1
,08-26 15:42:36.525  1017  1545 D InputDispatcher: Focus entered window: 6945
,08-26 15:42:36.535  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-26 15:42:36.535  6945  6945 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-26 15:42:36.535  6945  7055 I OpenGLRenderer: Initialized EGL, version 1.4
08-26 15:42:36.535  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 15:42:36.535  6945  7055 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-26 15:42:36.535  6945  7055 D OpenGLRenderer: Enabling debug mode 0
,08-26 15:42:36.565  1017  1489 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-26 15:42:36.565  1177  1177 D PanelView: There is/are notification(s) 
,08-26 15:42:36.575  1017  7059 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:42:36.585  1017  1047 I ActivityManager: Displayed Component not be shown by security: +862ms (total +968ms)
,08-26 15:42:36.585  6945  6945 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-26 15:42:36.585  6945  6945 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@253cf471 time:95762
,08-26 15:42:36.585  1017  1047 W ActivityManager: mDVFSHelper.release()
,08-26 15:42:36.585  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{eade948 u0 com.test.thalitest/.MainActivity t163} time:95767
,08-26 15:42:36.595   258   442 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-26 15:42:36.595   258   447 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-26 15:42:36.595  6630  6630 D AbsListView: Get MotionRecognitionManager
,08-26 15:42:36.605  1017  1503 D MotionRecognitionService:  ssp status : false,
,08-26 15:42:36.605  6630  6630 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 119.599896,
,08-26 15:42:36.645  7036  7036 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 118.960ms
,08-26 15:42:36.695  6630  6630 D Mms/BubbleViewCache: fillCache bubble = 1
,08-26 15:42:36.705  1017  1488 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-26 15:42:36.705  1017  1488 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:42:36.705  1017  1488 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:42:36.705  1017  1488 D BatteryService: stay LED for charging
08-26 15:42:36.705  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 15:42:36.705  1017  1017 I MotionRecognitionService: Plugged
08-26 15:42:36.705  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:42:36.705  1962  1962 I SamsungIME: getCurrentCandidateView
,08-26 15:42:36.705  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:42:36.705  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:42:36.715  1423  1423 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:42:36.715  1423  1423 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:42:36.725  3209  3209 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:42:36.725  3209  3353 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:42:36.735  6945  6945 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6945
,08-26 15:42:36.745  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:42:36.745  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:42:36.745  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:42:36.745  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:42:36.745  1177  1177 D SViewCoverView: level :100 plugged : 2
,08-26 15:42:36.765  1017  1456 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-26 15:42:36.765  1017  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:36.765  1017  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:36.765  1017  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:36.765  1017  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:36.775  7065  7065 E Zygote  : MountEmulatedStorage()
08-26 15:42:36.775  7065  7065 E Zygote  : v2
08-26 15:42:36.775  7065  7065 I libpersona: KNOX_SDCARD checking this for 10090
08-26 15:42:36.775  7065  7065 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:36.785  7065  7065 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:36.785  7065  7065 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:36.785  1017  1456 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7065 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
08-26 15:42:36.785  1017  1456 I ActivityManager: Killing 6591:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-26 15:42:36.795  7065  7065 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:42:36.815  7065  7065 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:36.815  7065  7065 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:36.835  7065  7065 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,08-26 15:42:36.835  7065  7065 D elm:15121: ELMEngine.ELMEngine( context ).
,08-26 15:42:36.835  7065  7065 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-26 15:42:36.845  1017  1503 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,08-26 15:42:36.845  1017  1503 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-26 15:42:36.845  1017  1503 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:36.845  1017  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:36.845  1017  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-26 15:42:36.845  1962  1962 D SamsungIME: Dismiss ExpandCandiate
,08-26 15:42:36.845  7065  7065 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,08-26 15:42:36.845  1017  3829 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,08-26 15:42:36.845  7065  7065 D elm:15121: ElmAgentService : onCreate()
,08-26 15:42:36.845  1017  3829 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:36.845  1017  3829 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:36.845  1017  3829 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:36.845  7065  7082 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
08-26 15:42:36.845  1017  3829 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:36.855  7065  7082 D elm:15121: ELMAgentService.listeningToTimeDateChanges( context, intent ).
,08-26 15:42:36.855  7065  7065 D elm:15121: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,08-26 15:42:36.855  7065  7065 D elm:15121: ModuleBase.ModifySetAlarm()
08-26 15:42:36.855  7065  7065 D elm:15121: MDMBridge.getInstance()
08-26 15:42:36.855  7065  7065 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-26 15:42:36.865  7084  7084 E Zygote  : MountEmulatedStorage()
08-26 15:42:36.865  7084  7084 E Zygote  : v2
08-26 15:42:36.865  7084  7084 I libpersona: KNOX_SDCARD checking this for 10130
08-26 15:42:36.865  7084  7084 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:36.865  7084  7084 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:36.865  7084  7084 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:36.865  1017  3829 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7084 uid=10130 gids={50130, 9997} abi=armeabi-v7a
08-26 15:42:36.865  7084  7084 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-26 15:42:36.895  7084  7084 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:36.895  7084  7084 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:36.915  7084  7084 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 15:42:36.915  7084  7084 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-26 15:42:36.915  7065  7065 D elm:15121: ElmAgentService : onDestroy().
,08-26 15:42:36.915  1017  1307 I ActivityManager: Killing 6657:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,08-26 15:42:36.935  1017  3827 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,08-26 15:42:36.935  1017  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:36.935  1017  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:36.935  1017  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:36.935  1017  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:36.955  7100  7100 E Zygote  : MountEmulatedStorage()
,08-26 15:42:36.955  7100  7100 I libpersona: KNOX_SDCARD checking this for 10131
08-26 15:42:36.955  7100  7100 E Zygote  : v2
08-26 15:42:36.955  7100  7100 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:36.955  7100  7100 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:42:36.955  1017  3827 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7100 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
08-26 15:42:36.955  7100  7100 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:36.955  1017  3827 I ActivityManager: Killing 6674:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,08-26 15:42:36.955  7100  7100 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:42:36.975  7100  7100 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:36.975  7100  7100 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:36.995  7100  7100 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-26 15:42:36.995  7100  7100 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 15:42:36.995  7100  7100 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 15:42:36.995  6945  6945 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 15:42:37.035  2675  2689 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-26 15:42:37.035  1962  1962 I SamsungIME: getDebugLevel  : 0x4f4c
,08-26 15:42:37.045  1017  1227 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-26 15:42:37.055  1017  1227 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-26 15:42:37.055  1017  1227 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:37.055  1017  1227 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:37.055  1017  1227 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-26 15:42:37.065  1017  1136 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-26 15:42:37.065  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-26 15:42:37.075  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:37.075  1017  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:37.075  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-26 15:42:37.075  1017  1547 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-26 15:42:37.075  1017  1547 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:37.075  1017  1547 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:37.075  1017  1547 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:37.075  1017  1547 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:37.095  1962  1962 I SamsungIME: getDebugLevel  : 0x4f4c
,08-26 15:42:37.095  7121  7121 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:42:37.095  7121  7121 E Zygote  : MountEmulatedStorage()
08-26 15:42:37.095  7121  7121 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:37.095  7121  7121 E Zygote  : v2
08-26 15:42:37.095  7121  7121 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:42:37.105  1017  1547 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.DateTimeChangedReceiver: pid=7121 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 15:42:37.095  7121  7121 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:37.095  7121  7121 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 15:42:37.095  6945  7061 D jxcore_app_log: JniHelper::setJavaVM(0xb8f732b0), pthread_self() = -1185932704
08-26 15:42:37.105  1017  1029 D ActivityManager: getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,08-26 15:42:37.105  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:37.105  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:37.105  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:37.105  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:37.115  6945  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 15:42:37.115  6945  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 15:42:37.115  6945  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 15:42:37.115  6945  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 15:42:37.115  6945  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-26 15:42:37.115  6945  7061 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f5073a added. We now have 1 listener(s)
,08-26 15:42:37.115  1962  1962 I SamsungIME: KeybaordView init() : load resources
,08-26 15:42:37.115  7121  7121 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:37.115  7121  7121 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:37.125   305   305 I art     : Explicit concurrent mark sweep GC freed 8698(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 704us total 22.513ms
,08-26 15:42:37.135  1962  1962 I SamsungIME: getCurrentKeyboard
08-26 15:42:37.135  1962  1962 I SamsungIME: getTextKeyboard
,08-26 15:42:37.135   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 574us total 16.263ms
,08-26 15:42:37.155  1962  1962 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
08-26 15:42:37.155   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 575us total 17.121ms
,08-26 15:42:37.165  7136  7136 E Zygote  : MountEmulatedStorage(),
,08-26 15:42:37.175  7136  7136 E Zygote  : v2,
08-26 15:42:37.175  7136  7136 I libpersona: KNOX_SDCARD checking this for 10037
08-26 15:42:37.175  1017  1029 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7136 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 15:42:37.175  7136  7136 I libpersona: KNOX_SDCARD not a persona,
,08-26 15:42:37.175  7136  7136 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:37.175  6945  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
08-26 15:42:37.175  6945  7061 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-26 15:42:37.175  7136  7136 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:42:37.175  6945  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:42:37.175  6945  7061 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 15:42:37.175  7136  7136 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-26 15:42:37.185  6945  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 15:42:37.185  6945  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 15:42:37.185  6945  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 15:42:37.185  6945  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-26 15:42:37.185  6945  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 15:42:37.185  6945  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 15:42:37.185  6945  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 15:42:37.185  6945  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 15:42:37.185  6945  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 15:42:37.185  6945  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 15:42:37.185  6945  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 15:42:37.185  6945  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 15:42:37.185  6945  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 15:42:37.185  6945  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 15:42:37.185  6945  7061 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe2dbe1 added. We now have 1 listener(s)
,08-26 15:42:37.185  6945  7061 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:42:37.195  6945  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 15:42:37.195  6945  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 15:42:37.195  6945  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 15:42:37.195  6945  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 15:42:37.195  6945  7061 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-26 15:42:37.195  6945  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:42:37.195  7136  7136 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:37.205  7136  7136 D ActivityThread: Added TimaKeyStore provider
08-26 15:42:37.205  6945  7061 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41,
,08-26 15:42:37.215  6945  7061 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-26 15:42:37.215  6945  7061 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:37.215  6945  7061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:37.215  6945  7061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:37.215  6945  7061 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:37.215  6945  7061 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:37.215  6945  7061 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:37.215  6945  7061 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:37.215  6945  7061 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:42:37.215  6945  7061 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 15:42:37.215  6945  7061 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:42:37.215  6945  7061 I io.jxcore.node.LifeCycleMonitor: start: OK,
,08-26 15:42:37.225  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:37.225  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:37.225  7121  7121 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 15:42:37.225  7121  7121 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 15:42:37.225  7121  7121 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 15:42:37.235  1017  1456 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,08-26 15:42:37.235  1017  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:37.235  1017  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:37.235  1017  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:37.235  1017  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:37.245  7136  7136 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,08-26 15:42:37.255  1017  1456 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=7154 uid=10153 gids={50153, 9997} abi=armeabi-v7a
,08-26 15:42:37.265  7154  7154 E Zygote  : MountEmulatedStorage()
08-26 15:42:37.255  1017  1456 I ActivityManager: Killing 6699:com.google.android.apps.docs/u0a87 (adj 15): empty #21
08-26 15:42:37.265  7154  7154 E Zygote  : v2
08-26 15:42:37.265  7154  7154 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:42:37.265  7154  7154 I libpersona: KNOX_SDCARD checking this for 10153
08-26 15:42:37.265  6945  6945 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-26 15:42:37.265  7154  7154 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:37.275  7154  7154 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:42:37.275  7154  7154 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:42:37.295  7154  7154 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:42:37.295  7154  7154 D ActivityThread: Added TimaKeyStore provider
08-26 15:42:37.295  7136  7136 I CalendarProvider2: CalendarProvider2.onCreate() called
,08-26 15:42:37.325  7154  7154 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 15:42:37.335  1017  1545 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,08-26 15:42:37.335  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 15:42:37.335  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:37.335  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:37.335  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:37.355  7170  7170 E Zygote  : MountEmulatedStorage()
08-26 15:42:37.355  7170  7170 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:42:37.355  7170  7170 E Zygote  : v2
08-26 15:42:37.355  7170  7170 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:37.355  7170  7170 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:37.355  1017  1545 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7170 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 15:42:37.355  7170  7170 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:37.355  1017  1545 I ActivityManager: Killing 6714:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
08-26 15:42:37.355  7170  7170 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:42:37.375  7170  7170 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:37.375  7170  7170 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:37.515  1017  1503 I art     : Explicit concurrent mark sweep GC freed 20622(1136KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.515ms total 134.007ms
,08-26 15:42:37.535  1017  1029 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
08-26 15:42:37.535  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
08-26 15:42:37.535  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:37.535  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:37.535  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
08-26 15:42:37.545  7170  7170 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1472218957546
08-26 15:42:37.545  7170  7170 D         : TimeServiceNative: User Time to be set is 1472218957547
08-26 15:42:37.545  7170  7170 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
08-26 15:42:37.545  7170  7170 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-26 15:42:37.545  7170  7170 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1472218957547
08-26 15:42:37.545   317   561 D QC-time-services: Daemon: Connection accepted:time_genoff
08-26 15:42:37.545  7170  7170 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-26 15:42:37.545   317  7189 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1472218957547
08-26 15:42:37.545   317  7189 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1472218957547, operation = 0
08-26 15:42:37.545   317  7189 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS1/21/71 7:25:28
08-26 15:42:37.545   317  7189 D QC-time-services: Daemon:Value read from RTC seconds = 35969128000
08-26 15:42:37.545   317  7189 D QC-time-services: Daemon:new time 1472218957547 
08-26 15:42:37.545   317  7189 D QC-time-services: Daemon: delta 1436249829547 genoff 1436249829547 
08-26 15:42:37.545   317  7189 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249829547 to memory
08-26 15:42:37.545   317  7189 D QC-time-services: Daemon:Opening File: /data/time/ats_2
08-26 15:42:37.545   317  7189 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-26 15:42:37.575   317  7189 D QC-time-services: Updating the TOD offset
08-26 15:42:37.575   317  7189 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249829547 to memory
08-26 15:42:37.575   317  7189 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-26 15:42:37.575   317  7189 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-26 15:42:37.575   317  7189 E QC-time-services: Daemon:Update to modem bit set
08-26 15:42:37.575   317  7189 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
08-26 15:42:37.575   317  7189 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120285029547
,08-26 15:42:37.575  7170  7170 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,08-26 15:42:37.575   317   557 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,08-26 15:42:37.575   317   561 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-26 15:42:37.575  1017  1136 I ActivityManager: Killing 6754:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
08-26 15:42:37.585  2675  2675 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
08-26 15:42:37.585  2675  2675 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
08-26 15:42:37.585  2675  2675 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-26 15:42:37.595  2675  2675 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings,
,08-26 15:42:37.605  2675  2675 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
08-26 15:42:37.605  1017  3829 I ActivityManager: Killing 6733:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,08-26 15:42:37.615  2675  2675 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,08-26 15:42:37.615  2675  2675 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-26 15:42:37.615  2675  2675 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
08-26 15:42:37.615  2675  2675 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-26 15:42:37.615  2675  2675 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-26 15:42:37.615  2675  2675 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
08-26 15:42:37.615  2675  2675 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-26 15:42:37.625  2675  2675 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,08-26 15:42:37.625  2675  2675 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,08-26 15:42:37.625  2675  2675 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
08-26 15:42:37.625  2675  2675 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,08-26 15:42:37.625  2675  2675 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-26 15:42:37.635  2675  2675 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,08-26 15:42:37.645  2675  2675 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
08-26 15:42:37.645  2675  2675 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,08-26 15:42:37.885  6945  7152 W jxcore-log: Initializing JXcore engine
08-26 15:42:37.885  6945  7152 W jxcore-log: JXcore engine is ready
,08-26 15:42:37.945  1942  1942 E audit   : type=1400 msg=audit(1472218957.945:205): avc:  denied  { ioctl } for  pid=7152 comm="Thread-1310" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-26 15:42:37.945  1942  1942 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:42:37.945  1942  1942 E audit   : type=1300 msg=audit(1472218957.945:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e3848f8 items=0 ppid=305 ppcomm=main pid=7152 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1310" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-26 15:42:37.945  1942  1942 E audit   : type=1320 msg=audit(1472218957.945:205): 
,08-26 15:42:37.955  6945  7152 W jxcore-log: Starting JXcore engine
,08-26 15:42:38.075  6945  7152 W jxcore-log: Platform android
08-26 15:42:38.075  6945  7152 W jxcore-log: 
08-26 15:42:38.075  6945  7152 W jxcore-log: Process ARCH arm
08-26 15:42:38.075  6945  7152 W jxcore-log: 
,08-26 15:42:38.285  6945  7152 I jxcore-log: JXcore Cordova bridge is ready!
08-26 15:42:38.285  6945  7152 I jxcore-log: 
,08-26 15:42:38.285  6945  7152 W jxcore-log: JXcore engine is started
,08-26 15:42:38.295  6945  7061 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-26 15:42:38.295  6945  6945 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 15:42:38.535  7136  7136 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,08-26 15:42:38.545  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:38.545  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:38.545  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,08-26 15:42:38.545  1017  3830 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:38.545  1017  3830 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:38.545  1017  3830 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,08-26 15:42:38.555  1017  1456 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,08-26 15:42:38.555  1017  1456 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:38.555  1017  1456 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:38.555  1017  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-26 15:42:38.555  1017  1227 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
08-26 15:42:38.555  1017  1227 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-26 15:42:38.555  1017  1227 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:38.555  1017  1227 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:38.555  1017  1227 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-26 15:42:38.565  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:38.565  1017  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:38.565  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,08-26 15:42:38.575  1017  1136 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-26 15:42:38.575  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-26 15:42:38.575  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:38.575  1017  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:38.575  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-26 15:42:38.585  1017  3827 I ActivityManager: Killing 6792:com.sec.pcw.device/1000 (adj 15): empty #21
,08-26 15:42:38.645   270   270 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb789d7c8
08-26 15:42:38.645   270   270 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-26 15:42:38.645   270   270 I rmt_storage: wakelock acquired: 1, error no: 42
08-26 15:42:38.645   270   375 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1215702904)
,08-26 15:42:38.685   270   375 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504,
08-26 15:42:38.685   270   375 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-26 15:42:38.685   270   375 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1215702904) wakelock released: 1, error no: 0,
08-26 15:42:38.685   270   375 I rmt_storage: 
,08-26 15:42:38.685   270   270 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb789d7c8
,08-26 15:42:38.765   288   288 E SMD     : DCD OFF,
,08-26 15:42:39.185  1017  3410 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:42:39.725  1668  1668 I ConfigService: onDestroy
,08-26 15:42:41.765   288   288 E SMD     : DCD OFF
,08-26 15:42:43.775  1017  3380 D SSRM:n  : SIOP:: AP = 410
,08-26 15:42:44.195  1017  3410 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:42:44.765   288   288 E SMD     : DCD OFF
,08-26 15:42:45.055  1017  1057 D PackageManager: [MSG] MCS_UNBIND
,08-26 15:42:45.065  1017  1030 I ActivityManager: Killing 6810:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-26 15:42:45.615  1017  1057 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-26 15:42:46.745  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:42:46.745  1017  1029 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4275, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-26 15:42:46.745  1017  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:42:46.745  1017  1029 D BatteryService: stay LED for charging
,08-26 15:42:46.745  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:42:46.745  1017  1017 I MotionRecognitionService: Plugged
,08-26 15:42:46.745  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:42:46.755  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:42:46.755  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:42:46.755  1423  1423 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:42:46.755  1423  1423 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:42:46.765  3209  3209 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:42:46.765  3209  3353 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:42:46.785  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:42:46.785  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:42:46.785  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:42:46.785  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-26 15:42:46.785  1177  1177 D SViewCoverView: level :100 plugged : 2
,08-26 15:42:47.765   288   288 E SMD     : DCD OFF
,08-26 15:42:48.795  1017  1095 V AlarmManager: waitForAlarm result :4
08-26 15:42:48.795  1017  1330 E Watchdog: !@Sync 3
08-26 15:42:48.795  1017  1095 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,08-26 15:42:49.035  6100  6209 D Finsky  : [1119] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,08-26 15:42:49.035  6100  6100 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-26 15:42:49.775   314   314 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-26 15:42:49.775   314   314 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-26 15:42:50.645  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-26 15:42:50.645  6945  7152 I jxcore-log: 
,08-26 15:42:50.645  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-26 15:42:50.645  6945  7152 I jxcore-log: 
,08-26 15:42:50.655  6945  7152 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-26 15:42:50.655  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:50.655  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:50.655  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
08-26 15:42:50.655  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:50.655  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:50.655  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:50.655  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:42:50.655  6945  7152 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:50.655  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 15:42:50.655  6945  7152 I jxcore-log: 
08-26 15:42:50.655  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 15:42:50.655  6945  7152 I jxcore-log: 
,08-26 15:42:50.765   288   288 E SMD     : DCD OFF
,08-26 15:42:51.305  6945  7152 D executeNativeTests: Running unit tests
,08-26 15:42:51.395  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:42:51.395  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27809b8a added. We now have 2 listener(s)
,08-26 15:42:51.405  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-26 15:42:51.405  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:42:51.405  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 15:42:51.405  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:42:51.405  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb added. We now have 2 listener(s)
08-26 15:42:51.405  6945  7152 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:42:51.405  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 15:42:51.405  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:42:51.405  6945  7152 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:51.405  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:51.405  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:51.405  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:51.405  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:51.405  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:51.405  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:51.405  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:42:51.415  6945  7152 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 15:42:51.415  6945  7152 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:42:51.415  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:51.415  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 15:42:51.415  6945  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 15:42:51.415  6945  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 15:42:51.415  6945  7152 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-26 15:42:51.415  6945  7152 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 15:42:51.415  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 15:42:51.415  6945  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 15:42:51.415  6945  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 15:42:51.415  6945  7152 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.415  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.415  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.415  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.415  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.415  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:42:51.415  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:42:51.415  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27809b8a removed from the list
08-26 15:42:51.415  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.415  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb removed from the list
,08-26 15:42:51.415  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:51.425  6945  7152 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 15:42:51.425  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:51.425  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.425  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:51.425  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.425  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.425  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.425  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
,08-26 15:42:51.425  6945  7152 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-26 15:42:51.425  6945  7152 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 15:42:51.425  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.425  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 15:42:51.425  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.425  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.425  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.425  6945  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27809b8a not in the list
08-26 15:42:51.425  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.425  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.425  6945  7152 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.425  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.425  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.425  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.425  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:51.425  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 15:42:51.435  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.435  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.435  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
,08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no pe,er name> 36:2610:2610:2610:2610:2610]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 15:42:51.435  6945  7152 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.435  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.435  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.435  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.435  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.435  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:51.435  6945  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27809b8a not in the list
08-26 15:42:51.435  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.435  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.435  6945  7152 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.435  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:42:51.435  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.435  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.435  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.435  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.435  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.435  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:42:51.435  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.435  6945  7152 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 15:42:51.435  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:42:51.445  6945  7152 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:51.445  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:51.445  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:51.445  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:51.445  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:51.445  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:51.445  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:51.445  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:42:51.445  6945  7152 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 15:42:51.445  6945  7152 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 15:42:51.445  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:42:51.445  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 15:42:51.445  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 15:42:51.445  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:51.445  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 15:42:51.445  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:51.445  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 15:42:51.455  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:51.455  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 15:42:51.465  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 15:42:51.465  6945  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-26 15:42:51.465  6945  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-26 15:42:51.465  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 15:42:51.465  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 15:42:51.465  6945  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 15:42:51.485  3209  3377 D BtGatt.GattService: registerClient() - UUID=a9df16f0-4ca8-4bca-bdee-3bb05719dc8d
,08-26 15:42:51.525  3209  3288 D BtGatt.GattService: onClientRegistered() - UUID=a9df16f0-4ca8-4bca-bdee-3bb05719dc8d, clientIf=6
,08-26 15:42:51.535  6945  6953 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 15:42:51.535  3209  3225 D BtGatt.GattService: start scan with filters
,08-26 15:42:51.535  3209  3352 D BtGatt.ScanManager: handling starting scan
,08-26 15:42:51.535  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 15:42:51.535  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 15:42:51.535  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 15:42:51.535  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 15:42:51.535  3209  3352 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
,08-26 15:42:51.545  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 15:42:51.545  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 15:42:51.545  6945  6945 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 15:42:51.545  3209  3288 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 15:42:51.555  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:42:51.555  3209  3352 D BtGatt.ScanManager: allow scan with filters
08-26 15:42:51.555  3209  3352 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 15:42:51.555  3209  3352 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-26 15:42:51.555  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 15:42:51.555  6945  7152 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 15:42:51.555  3209  3288 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 15:42:51.565  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:51.565  3209  3352 D BtGatt.ScanManager: Starting BLE batch scan
08-26 15:42:51.565  3209  3352 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 15:42:51.565  6945  7152 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 15:42:51.565  6945  7152 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 15:42:51.565  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.565  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-26 15:42:51.565  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:42:51.565  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 15:42:51.565  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 15:42:51.565  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 15:42:51.575  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-26 15:42:51.575  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 15:42:51.575  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 15:42:51.575  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 15:42:51.575  3209  3288 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-26 15:42:51.575  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:51.575  3209  3220 D BtGatt.GattService: stopScan() - queue size =1
,08-26 15:42:51.575  3209  3377 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 15:42:51.575  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 15:42:51.575  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-26 15:42:51.575  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 15:42:51.575  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 15:42:51.575  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 15:42:51.585  3209  3288 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 15:42:51.585  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:51.585  3209  3352 D BtGatt.ScanManager: filter size is 1
,08-26 15:42:51.585  3209  3352 D BtGatt.ScanManager: delete FilterIndex - 3
,08-26 15:42:51.585  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:42:51.585  3209  3288 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 15:42:51.595  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:42:51.595  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 15:42:51.595  3209  3352 D BtGatt.ScanManager: stopping BLe Batch
,08-26 15:42:51.595  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
08-26 15:42:51.595  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 15:42:51.595  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-26 15:42:51.595  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.595  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.595  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-26 15:42:51.595  6945  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27809b8a not in the list
08-26 15:42:51.595  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.595  6945  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:42:51.595  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.595  6945  7152 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.595  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.595  6945  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:42:51.595  6945  6945 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:42:51.595  6945  7152 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 15:42:51.595  3209  3288 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 15:42:51.595  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:51.595  3209  3352 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 15:42:51.595  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:42:51.605  3209  3288 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-26 15:42:51.605  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:51.605  6945  7152 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:51.605  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:51.605  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:51.605  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:51.605  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:51.605  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:51.605  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:51.605  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:42:51.605  6945  7152 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 15:42:51.605  6945  7152 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:42:51.615  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:42:51.615  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 15:42:51.615  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 15:42:51.615  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:51.615  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 15:42:51.615  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:51.615  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 15:42:51.615  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:51.615  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 15:42:51.625  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 15:42:51.625  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 15:42:51.625  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 15:42:51.625  6945  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 15:42:51.625  3209  3377 D BtGatt.GattService: registerClient() - UUID=a090cd43-7126-4943-9d87-d8c6efb12f16
,08-26 15:42:51.665  3209  3288 D BtGatt.GattService: onClientRegistered() - UUID=a090cd43-7126-4943-9d87-d8c6efb12f16, clientIf=6
08-26 15:42:51.675  6945  6955 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 15:42:51.675  3209  3225 D BtGatt.GattService: start scan with filters
,08-26 15:42:51.675  3209  3352 D BtGatt.ScanManager: handling starting scan
,08-26 15:42:51.675  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 15:42:51.675  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 15:42:51.675  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 15:42:51.675  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 15:42:51.685  3209  3288 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 15:42:51.685  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:51.685  3209  3352 D BtGatt.ScanManager: allow scan with filters
,08-26 15:42:51.685  3209  3352 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 15:42:51.685  3209  3352 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-26 15:42:51.685  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 15:42:51.685  6945  6945 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 15:42:51.685  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 15:42:51.685  3209  3288 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
08-26 15:42:51.695  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:51.695  3209  3352 D BtGatt.ScanManager: Starting BLE batch scan
08-26 15:42:51.695  3209  3352 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 15:42:51.695  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 15:42:51.695  3209  3288 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 15:42:51.695  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:51.705  6945  7152 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 15:42:51.705  6945  7152 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 15:42:51.705  3209  3288 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 15:42:51.705  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:51.705  6945  7152 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 15:42:51.705  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.715  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-26 15:42:51.715  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.715  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 15:42:51.715  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 15:42:51.715  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 15:42:51.715  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 15:42:51.715  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 15:42:51.715  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 15:42:51.715  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 15:42:51.715  3209  3220 D BtGatt.GattService: stopScan() - queue size =1
,08-26 15:42:51.715  3209  3352 D BtGatt.ScanManager: filter size is 1
,08-26 15:42:51.715  3209  3352 D BtGatt.ScanManager: delete FilterIndex - 4
,08-26 15:42:51.715  3209  3377 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 15:42:51.715  3209  3288 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 15:42:51.715  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:42:51.715  3209  3352 D BtGatt.ScanManager: stopping BLe Batch,
08-26 15:42:51.715  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:42:51.715  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 15:42:51.715  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
08-26 15:42:51.715  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 15:42:51.715  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 15:42:51.715  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:42:51.725  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 15:42:51.725  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 15:42:51.725  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 15:42:51.725  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 15:42:51.725  3209  3288 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-26 15:42:51.725  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:51.725  3209  3352 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 15:42:51.725  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.725  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.725  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:42:51.725  6945  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27809b8a not in the list
08-26 15:42:51.725  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.725  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.725  6945  7152 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.725  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.725  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.725  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:51.725  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.725  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.725  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.725  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
,08-26 15:42:51.725  6945  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:42:51.725  6945  7152 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 15:42:51.725  6945  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:42:51.725  6945  6945 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:42:51.725  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:42:51.735  3209  3288 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-26 15:42:51.735  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:51.735  6945  7152 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:51.735  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:51.735  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:51.735  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:51.735  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:51.735  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:51.735  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:51.735  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:42:51.735  6945  7152 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 15:42:51.735  6945  7152 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:42:51.735  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:51.745  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:42:51.745  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 15:42:51.745  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 15:42:51.745  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:51.745  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 15:42:51.745  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:51.745  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 15:42:51.755  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 15:42:51.755  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 15:42:51.755  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 15:42:51.755  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 15:42:51.755  6945  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 15:42:51.755  3209  3225 D BtGatt.GattService: registerClient() - UUID=db794911-e8cb-4669-b42d-324b0e23b38f
,08-26 15:42:51.795  3209  3288 D BtGatt.GattService: onClientRegistered() - UUID=db794911-e8cb-4669-b42d-324b0e23b38f, clientIf=6
,08-26 15:42:51.805  6945  6955 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 15:42:51.805  3209  3291 D BtGatt.GattService: start scan with filters
,08-26 15:42:51.805  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 15:42:51.805  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 15:42:51.805  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 15:42:51.805  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 15:42:51.805  3209  3352 D BtGatt.ScanManager: handling starting scan
,08-26 15:42:51.805  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 15:42:51.805  6945  6945 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 15:42:51.805  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 15:42:51.805  3209  3288 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 15:42:51.805  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:42:51.805  3209  3352 D BtGatt.ScanManager: allow scan with filters
08-26 15:42:51.805  3209  3352 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 15:42:51.815  3209  3352 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-26 15:42:51.815  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 15:42:51.815  6945  7152 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 15:42:51.815  6945  7152 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.815  6945  7152 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 15:42:51.815  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.815  3209  3288 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 15:42:51.815  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 15:42:51.815  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.815  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 15:42:51.815  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 15:42:51.815  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 15:42:51.815  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 15:42:51.815  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 15:42:51.815  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 15:42:51.815  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 15:42:51.815  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:42:51.815  3209  3352 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 15:42:51.815  3209  3352 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 15:42:51.815  3209  3291 D BtGatt.GattService: stopScan() - queue size =1
,08-26 15:42:51.815  3209  3377 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 15:42:51.815  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-26 15:42:51.815  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 15:42:51.815  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 15:42:51.815  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 15:42:51.815  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 15:42:51.825  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:42:51.825  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 15:42:51.825  3209  3288 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-26 15:42:51.825  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:51.825  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 15:42:51.825  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 15:42:51.825  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 15:42:51.825  6945  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 15:42:51.825  6945  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:42:51.825  6945  6945 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:42:51.825  6945  7152 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 15:42:51.825  6945  7152 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 15:42:51.825  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.835  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.835  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.835  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.835  3209  3288 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-26 15:42:51.835  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:42:51.835  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:42:51.835  6945  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27809b8a not in the list
08-26 15:42:51.835  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.835  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.835  6945  7152 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.835  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.835  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.835  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:51.835  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.835  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.835  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.835  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
,08-26 15:42:51.835  6945  7152 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-26 15:42:51.835  6945  7152 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.835  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.835  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.835  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.835  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.835  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.835  6945  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27809b8a not in the list
08-26 15:42:51.835  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.835  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.835  6945  7152 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.835  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.835  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.835  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.835  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:51.835  3209  3352 D BtGatt.ScanManager: filter size is 1
08-26 15:42:51.835  3209  3352 D BtGatt.ScanManager: delete FilterIndex - 5
08-26 15:42:51.835  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.835  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.835  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.835  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
,08-26 15:42:51.835  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 15:42:51.835  6945  7152 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.835  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.835  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.835  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.835  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.835  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.835  6945  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27809b8a not in the list
08-26 15:42:51.835  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.835  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.835  6945  7152 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.835  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.835  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.835  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.835  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:51.845  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.845  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.845  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:42:51.845  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.845  6945  7152 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 15:42:51.845  6945  7152 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.845  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.845  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.845  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.845  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.845  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.845  6945  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27809b8a not in the list
,08-26 15:42:51.845  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.845  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.845  6945  7152 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.845  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.845  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.845  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-26 15:42:51.845  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.845  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.845  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 15:42:51.845  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:42:51.845  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.845  6945  7152 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 15:42:51.845  6945  7152 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.845  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.845  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.845  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.845  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:42:51.845  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.845  6945  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27809b8a not in the list
08-26 15:42:51.845  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.845  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.845  6945  7152 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.845  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:42:51.845  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 15:42:51.845  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.845  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.845  3209  3288 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 15:42:51.845  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:51.845  3209  3352 D BtGatt.ScanManager: stopping BLe Batch
08-26 15:42:51.845  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.845  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.845  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.845  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
,08-26 15:42:51.845  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 15:42:51.845  6945  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 15:42:51.845  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 15:42:51.845  6945  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 15:42:51.845  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 15:42:51.845  6945  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 15:42:51.845  6945  7152 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.845  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 15:42:51.845  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.845  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.845  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.845  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 15:42:51.845  6945  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27809b8a not in the list
08-26 15:42:51.845  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:42:51.845  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
,08-26 15:42:51.845  6945  7152 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.845  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.845  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.845  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.845  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.845  3209  3288 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 15:42:51.845  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:42:51.845  3209  3352 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-26 15:42:51.845  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.845  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.845  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.845  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.845  6945  7152 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 15:42:51.845  6945  7152 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 15:42:51.845  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 15:42:51.855  6945  7152 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 15:42:51.855  6945  7152 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410],
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 15:42:51.855  6945  7152 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 15:42:51.855  6945  7152 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 15:42:51.855  6945  7152 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 15:42:51.855  6945  7152 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 15:42:51.855  6945  7152 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-26 15:42:51.855  6945  7152 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 15:42:51.855  6945  7152 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 15:42:51.855  6945  7152 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 15:42:51.855  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 15:42:51.855  3209  3288 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 15:42:51.855  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:42:51.855  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 15:42:51.855  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 15:42:51.855  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 15:42:51.855  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 15:42:51.855  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-26 15:42:51.855  6945  7152 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 15:42:51.855  6945  7152 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 15:42:51.855  6945  7152 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 15:42:51.855  6945  7152 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.855  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.855  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 15:42:51.855  6945  7202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1374)
08-26 15:42:51.855  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.855  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.855  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.855  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 15:42:51.855  6945  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27809b8a not in the list
08-26 15:42:51.855  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.855  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.855  6945  7152 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.855  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.855  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.855  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.855  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.865  6945  7203 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1374
08-26 15:42:51.865  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.865  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.865  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.865  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.865  6945  7152 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 15:42:51.865  6945  7152 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 15:42:51.865  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.865  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.865  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.865  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.865  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.865  6945  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27809b8a not in the list
08-26 15:42:51.865  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:42:51.865  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.865  6945  7152 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.865  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.865  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.865  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.865  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.865  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.865  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 15:42:51.865  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.865  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.865  6945  7152 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 15:42:51.865  6945  7152 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.865  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.865  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 15:42:51.865  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.865  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.865  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.865  6945  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27809b8a not in the list
08-26 15:42:51.865  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.865  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
,08-26 15:42:51.865  6945  7152 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.865  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.865  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.865  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.865  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.865  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.865  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.865  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:42:51.865  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.865  6945  7152 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 15:42:51.865  6945  7152 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 15:42:51.865  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 15:42:51.865  6945  7152 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 15:42:51.865  6945  7152 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 15:42:51.865  6945  7152 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 15:42:51.865  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 15:42:51.865  6945  7152 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,08-26 15:42:51.865  6945  7152 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 15:42:51.865  6945  7152 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 15:42:51.865  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 15:42:51.865  6945  7152 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 15:42:51.865  6945  7152 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.865  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.865  6945  7202 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,08-26 15:42:51.865  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.865  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.865  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.865  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.865  6945  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27809b8a not in the list
08-26 15:42:51.865  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.865  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.865  6945  7152 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.865  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.865  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.865  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.865  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:51.865  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.865  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.865  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.865  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.865  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 15:42:51.865  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.865  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.875  6945  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27809b8a not in the list
08-26 15:42:51.875  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.875  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.875  6945  7152 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.875  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:42:51.875  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.875  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.875  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.875  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.875  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.875  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:51.875  6945  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27809b8a not in the list
08-26 15:42:51.875  6945  7152 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.875  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.875  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.875  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.875  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:42:51.875  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.875  6945  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27809b8a not in the list
08-26 15:42:51.875  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.875  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.875  6945  7152 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.875  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.875  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.875  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.875  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.875  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.875  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.875  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.875  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.875  6945  7202 D BluetoothSocket: connect(): myUserId = 0
08-26 15:42:51.875  6945  7202 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 15:42:51.875  6945  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 15:42:51.875  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:42:51.875  3209  3377 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:42:51.875  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 15:42:51.875  6945  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 15:42:51.875  6945  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 15:42:51.875  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 15:42:51.875  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 15:42:51.875  6945  6945 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 15:42:51.875  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.875  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 15:42:51.875  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 15:42:51.875  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 15:42:51.875  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.875  6945  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 15:42:51.875  6945  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27809b8a not in the list
08-26 15:42:51.875  6945  6945 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 15:42:51.875  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.875  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 15:42:51.875  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 15:42:51.875  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 15:42:51.875  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.875  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.875  6945  7202 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
08-26 15:42:51.885  6945  7204 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 15:42:51.885  6945  7204 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-26 15:42:51.885  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:42:51.885  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.885  6945  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:42:51.885  6945  7152 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.885  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.885  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.885  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.885  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.885  6945  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:42:51.885  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.885  6945  6945 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 15:42:51.885  6945  6945 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 15:42:51.885  6945  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27809b8a not in the list
08-26 15:42:51.885  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.885  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.885  6945  7152 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.885  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.885  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.885  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.885  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:51.885  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.885  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.885  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.885  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
,08-26 15:42:51.885  6945  7152 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 15:42:51.885  6945  7152 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 15:42:51.885  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-26 15:42:51.885  6945  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 15:42:51.885  6945  7152 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.885  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.885  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.885  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 15:42:51.885  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.885  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.885  6945  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27809b8a not in the list
08-26 15:42:51.885  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.885  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.885  6945  7152 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.885  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.885  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.885  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.885  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:51.885  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.885  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.885  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.885  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
,08-26 15:42:51.895  6945  7152 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.895  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.895  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 15:42:51.895  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.895  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.895  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.895  6945  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27809b8a not in the list
08-26 15:42:51.895  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.895  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.895  6945  7152 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.895  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.895  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.895  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.895  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:51.895  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 15:42:51.895  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.895  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.895  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.895  6945  7152 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:51.895  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:51.895  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:51.895  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:51.895  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:42:51.895  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.895  6945  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27809b8a not in the list
08-26 15:42:51.895  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:51.895  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.895  6945  7152 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:51.895  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.895  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.895  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:51.895  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:51.895  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:51.895  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:51.895  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:42:51.895  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17e275fb not in the list
08-26 15:42:51.895  6945  7152 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 15:42:51.895  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 15:42:51.895  6945  7152 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 15:42:51.895  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 15:42:51.895  6945  7152 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 15:42:51.895  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-26 15:42:51.895  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 15:42:51.895  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 15:42:51.895  6945  7152 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 15:42:51.895  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 15:42:51.895  6945  7152 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 15:42:51.895  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-26 15:42:51.895  6945  7152 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 15:42:51.895  6945  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 15:42:51.905  6945  7152 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 15:42:51.905  6945  7152 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 15:42:51.905  6945  7152 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 15:42:51.905  6945  7152 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 15:42:51.905  6945  7152 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 15:42:51.905  6945  7152 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-26 15:42:51.905  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:42:51.905  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ad90265 added. We now have 2 listener(s)
08-26 15:42:51.905  6945  7152 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:42:51.905  6945  7152 D BluetoothAdapter: enable()
,08-26 15:42:51.905  6945  7152 D BluetoothAdapter: enable(): BT is already enabled..!
,08-26 15:42:51.905  1017  1546 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 15:42:51.905  1017  1546 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 15:42:51.905  1017  1546 D SecContentProvider2: mCursor = null
,08-26 15:42:51.905  1017  1546 D WifiService: setWifiEnabled: true pid=6945, uid=10170
08-26 15:42:51.905  1017  1546 W ActivityManager: Permission Denial: getCurrentUser() from pid=6945, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-26 15:42:51.915  1017  1546 W WifiService: Failed getting userId using ActivityManagerNative
08-26 15:42:51.915  1017  1546 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6945, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-26 15:42:51.915  1017  1546 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 15:42:51.915  1017  1546 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 15:42:51.915  1017  1546 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 15:42:51.915  1017  1546 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 15:42:51.915  1017  1546 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 15:42:51.915  1017  1546 D SettingsProvider: name = wifi_on
,08-26 15:42:51.915  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:42:51.915  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c3efb3a added. We now have 3 listener(s)
08-26 15:42:51.915  6945  7152 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:42:51.915  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:42:51.915  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1038d3eb added. We now have 4 listener(s)
08-26 15:42:51.915  6945  7152 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:42:51.925  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:42:51.925  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b860548 added. We now have 5 listener(s)
08-26 15:42:51.925  6945  7152 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:42:51.925  1017  1547 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 15:42:51.925  1017  1547 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 15:42:51.925  1017  1547 D SecContentProvider2: mCursor = null
,08-26 15:42:51.925  1017  1547 D WifiService: setWifiEnabled: false pid=6945, uid=10170
,08-26 15:42:51.925  1017  1547 D SettingsProvider: name = wifi_on
,08-26 15:42:51.935  6945  7152 D BluetoothAdapter: disable()
,08-26 15:42:51.935  1017  1126 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-26 15:42:51.935  1017  1227 D SettingsProvider: name = bluetooth_on
08-26 15:42:51.935  1381  1381 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 15:42:51.935  1381  1381 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-26 15:42:51.935  1381  1381 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-26 15:42:51.935  1381  1381 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-26 15:42:51.945  3209  3285 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-26 15:42:51.945  1017  1307 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:51.945  3209  3285 D BluetoothAdapterProperties: Setting state to 13
08-26 15:42:51.945  1017  1307 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-26 15:42:51.945  3209  3285 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 15:42:51.945  3209  3285 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 15:42:51.945  3209  3285 D BluetoothAdapterService: updateAdapterState state is 13
08-26 15:42:51.945  1381  1381 I wpa_supplicant: Scan aborted because the firmware maybe busy.
08-26 15:42:51.945  1381  1381 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
08-26 15:42:51.945  1381  1381 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
,08-26 15:42:51.945  1017  1307 W ActivityManager: userId = 0, bbcId = -10000,
08-26 15:42:51.945  1017  1307 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:51.945  1017  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:51.945  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:51.945  3209  3209 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-26 15:42:51.955  3209  3285 D BluetoothAdapterService: Autoconnection is available 
,08-26 15:42:51.955  3209  3285 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-26 15:42:51.955  3209  3209 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1dda08b7, channel: 19, state: LISTENING
,08-26 15:42:51.955  3209  3209 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1dda08b7, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@58738c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1907a824mSocket: android.net.LocalSocket@2d55bf8d impl:android.net.LocalSocketImpl@21edb542 fd:FileDescriptor[82]
08-26 15:42:51.955  3209  3209 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2d55bf8d impl:android.net.LocalSocketImpl@21edb542 fd:FileDescriptor[82]
08-26 15:42:51.955  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 15:42:51.955  3209  3285 D BluetoothAdapterService: terminating service from this receiver
,08-26 15:42:51.955  1017  1546 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 15:42:51.955  4726  4726 D BluetoothPbap: Proxy object disconnected,
08-26 15:42:51.955  4726  4726 D PbapServerProfile: Bluetooth service disconnected
08-26 15:42:51.955  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:51.955  1017  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:51.965  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:51.965  3209  3285 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 15:42:51.965  3209  3285 D BluetoothAdapterProperties: mDiscovering is false
,08-26 15:42:51.965  1017  1136 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 15:42:51.965  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:51.965  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,08-26 15:42:51.965  3209  3285 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-26 15:42:51.965  1177  1177 D BluetoothTile:  onBluetoothStateChange:
08-26 15:42:51.965  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:51.965  6945  7152 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:51.965  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:51.965  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:51.965  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:51.965  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:51.965  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:51.965  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:51.965  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:42:51.975  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 15:42:51.975  6945  7152 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:51.975  6945  7152 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:42:51.975  1177  1666 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 15:42:51.975  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 15:42:51.975  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:42:51.975  1177  1177 D BluetoothTile:  getBluetoothState : 13
08-26 15:42:51.975  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:51.975  1017  1126 E WifiNative-wlan0: do suspend true
08-26 15:42:51.975  1177  1666 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 15:42:51.975  1962  1962 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 15:42:51.975  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:51.975  1177  1666 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 15:42:51.985  4726  4726 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:42:51.985  1017  1503 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 15:42:51.985  1017  1489 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 15:42:51.995  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 15:42:51.995  6945  6945 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:51.995  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:51.995  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:51.995  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:51.995  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:51.995  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:51.995  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:51.995  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:51.995  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:42:51.995  6945  6945 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:51.995  6945  6945 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 15:42:51.995  3209  3288 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-26 15:42:51.995  3209  3209 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@35292290, channel: 5, state: LISTENING
08-26 15:42:51.995  3209  3209 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@35292290, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@399ac0bf, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@366bc789mSocket: android.net.LocalSocket@1fa5e38e impl:android.net.LocalSocketImpl@12cb57af fd:FileDescriptor[80]
08-26 15:42:51.995  3209  3209 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1fa5e38e impl:android.net.LocalSocketImpl@12cb57af fd:FileDescriptor[80]
,08-26 15:42:51.995  3209  3209 I BtOppRfcommListener: stopping Accept Thread
,08-26 15:42:51.995  3209  3209 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@35a5d7bc, channel: 12, state: LISTENING
08-26 15:42:51.995  3209  3209 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@35a5d7bc, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@17bc13b6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@36c05345mSocket: android.net.LocalSocket@15a0aa9a impl:android.net.LocalSocketImpl@367fbfcb fd:FileDescriptor[85]
08-26 15:42:51.995  3209  3209 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@15a0aa9a impl:android.net.LocalSocketImpl@367fbfcb fd:FileDescriptor[85]
,08-26 15:42:52.005  3209  5300 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 15:42:52.005  3209  5300 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 15:42:52.005  3209  3288 D BluetoothAdapterProperties: Scan Mode:20
08-26 15:42:52.005  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:52.005  3209  3285 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 15:42:52.005  3209  3285 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-26 15:42:52.005  3209  3285 E bt-btif : cmd socket is not created
08-26 15:42:52.005  3209  3295 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-26 15:42:52.005  3209  3285 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 15:42:52.005  6945  7202 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@14919106, channel: -1, state: INIT
08-26 15:42:52.005  4726  4726 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 15:42:52.005  6945  7202 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@14919106, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@ccec3c7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@269a2df4mSocket: android.net.LocalSocket@285e191d impl:android.net.LocalSocketImpl@2525b792 fd:FileDescriptor[106]
08-26 15:42:52.005  6945  7202 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@285e191d impl:android.net.LocalSocketImpl@2525b792 fd:FileDescriptor[106]
,08-26 15:42:52.005  3209  3209 V BluetoothOppManager: cleanUp...
08-26 15:42:52.005  1017  1030 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 15:42:52.005  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-26 15:42:52.005  6945  7202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1374)
,08-26 15:42:52.005  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:52.005  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:52.005  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.005  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 15:42:52.015  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:52.015  1668  1668 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 15:42:52.015  3209  3295 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 15:42:52.015  3209  3295 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 15:42:52.015  3209  3295 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 15:42:52.015  3209  3295 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 15:42:52.015  3209  3295 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 15:42:52.015  3209  3295 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 15:42:52.015  3209  3295 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
08-26 15:42:52.015  3209  3295 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
08-26 15:42:52.015  3209  3295 W bt-btif : invalid rfc slot id: 4
,08-26 15:42:52.015  4726  4726 D DockEventReceiver: finishStartingService: stopping service
,08-26 15:42:52.025  4726  4726 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 15:42:52.025  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:42:52.025  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-26 15:42:52.025  1017  3830 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-26 15:42:52.025  1017  3830 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:52.025  1017  3830 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:52.025  1017  3830 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:52.025  1017  3830 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:52.045  1017  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-26 15:42:52.045  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 15:42:52.045  1017  3830 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7211 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a,
,08-26 15:42:52.045   278   999 D CommandListener: Clearing all IP addresses on wlan0
,08-26 15:42:52.055  1668  2531 V NativeCrypto: Read error: ssl=0xb94a4658: I/O error during system call, Connection timed out
,08-26 15:42:52.055  1017  1128 E ConnectivityService: updateNetworkInfo(),
08-26 15:42:52.055  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 15:42:52.055  1017  1128 E ConnectivityService: updateNetworkInfo()
08-26 15:42:52.055  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
08-26 15:42:52.055  7211  7211 E Zygote  : MountEmulatedStorage()
08-26 15:42:52.055  7211  7211 E Zygote  : v2
08-26 15:42:52.055  7211  7211 I libpersona: KNOX_SDCARD checking this for 10055
,08-26 15:42:52.055  1668  2531 V NativeCrypto: SSL shutdown failed: ssl=0xb94a4658: I/O error during system call, Broken pipe
08-26 15:42:52.055  7211  7211 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:52.055  7211  7211 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:52.065  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 15:42:52.065  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 15:42:52.065  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.065  1017  1503 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011,
08-26 15:42:52.065  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.065  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.065  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.065  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 15:42:52.065  1017  1746 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 15:42:52.065  1017  1746 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:52.065  1017  1746 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-26 15:42:52.065  7211  7211 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:52.065  1017  1746 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:52.065  1017  1746 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,08-26 15:42:52.065  7211  7211 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 15:42:52.065  1017  1746 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:42:52.065  1017  1746 I qtaguid : Tagging socket 324 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1017, getuid(): 1000
,08-26 15:42:52.075  1017  1125 D WifiP2pService: InactiveState{ what=131204 }
,08-26 15:42:52.075  1017  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
08-26 15:42:52.075  1017  1746 I qtaguid : Untagging socket 324
08-26 15:42:52.075  1017  1746 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 15:42:52.075  1017  1126 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-26 15:42:52.085  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 15:42:52.085  1017  1151 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 15:42:52.085  1017  1017 D RttService: SCAN_AVAILABLE : 1
08-26 15:42:52.085  1017  1152 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 15:42:52.085  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-26 15:42:52.095  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
08-26 15:42:52.095  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
,08-26 15:42:52.095  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 15:42:52.095  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:52.095  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-26 15:42:52.095  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 15:42:52.095  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 15:42:52.095  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.095  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
08-26 15:42:52.095  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.095  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:52.095  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.095  1017  1125 D WifiP2pService: P2pDisablingState,
08-26 15:42:52.095  1017  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
08-26 15:42:52.095  1017  1125 D WifiP2pService: p2p socket connection lost
,08-26 15:42:52.095  1017  1125 D WifiP2pService: P2pDisabledState
08-26 15:42:52.105  1017  1126 E WifiNative-wlan0: do suspend true
,08-26 15:42:52.105  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED,
08-26 15:42:52.105  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-26 15:42:52.105  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 15:42:52.105  1017  1047 D WifiDisplayController: disconnect
08-26 15:42:52.105  1017  1047 D WifiDisplayController: updateConnection
,08-26 15:42:52.105  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 15:42:52.105  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 15:42:52.105  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 15:42:52.105  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-26 15:42:52.105  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 15:42:52.105  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 15:42:52.105  7211  7211 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-26 15:42:52.105  7211  7211 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:52.115  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-26 15:42:52.115  1017  3829 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 15:42:52.115  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 15:42:52.135  7211  7211 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
08-26 15:42:52.135  1017  1125 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-26 15:42:52.135  1017  1125 D WifiP2pService: DefaultState{ what=143375 }
,08-26 15:42:52.135  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 15:42:52.135  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:52.135  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 15:42:52.135   278   995 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 15:42:52.135   278   995 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-26 15:42:52.135   278   999 D CommandListener: Clearing all IP addresses on wlan0,
08-26 15:42:52.145  1017  1128 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-26 15:42:52.145  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:52.145  1017  1128 V NetworkStats: updateIfacesLocked()
08-26 15:42:52.145  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
08-26 15:42:52.145  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-26 15:42:52.145  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 15:42:52.145  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-26 15:42:52.145  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:52.145  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:52.145  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.145  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.145  1017  1746 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-26 15:42:52.145  1017  1746 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-26 15:42:52.145  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:52.145  1017  1128 V NetworkStats: performPollLocked() took 6ms
08-26 15:42:52.145  1381  1381 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-26 15:42:52.155  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:52.155  1017  1128 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-26 15:42:52.155  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:52.155  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 15:42:52.155  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:52.155  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 15:42:52.155  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.155  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.155  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.155  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:52.165  1177  1647 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-26 15:42:52.165  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-26 15:42:52.165  1017  1128 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:42:52.165  1017  1746 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:52.165  1017  1128 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-26 15:42:52.165  1017  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-26 15:42:52.165  1017  1128 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-26 15:42:52.165  1458  1458 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-26 15:42:52.165  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 15:42:52.165  1458  1458 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 15:42:52.165  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 15:42:52.165  1017  1126 D SecContentProvider2: mCursor = null
,08-26 15:42:52.165  7211  7211 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-26 15:42:52.175  7211  7211 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-26 15:42:52.175  7211  7211 D UserAnalysis: Create SecureDbHelper
,08-26 15:42:52.175  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 15:42:52.175  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:52.175  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 15:42:52.175  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.175  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.175  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.175  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.175  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:52.175  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-26 15:42:52.175  4726  4726 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:52.175  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:52.175  1177  1666 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 15:42:52.185  1017  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-26 15:42:52.185  1017  1128 D ConnectivityService: nai.networkMonitor.doQuit()
08-26 15:42:52.185  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 15:42:52.185  1017  1128 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-26 15:42:52.185  1017  1128 E ConnectivityService: updateNetworkInfo()
08-26 15:42:52.185  1017  1128 E ConnectivityService: updateNetworkInfo()
08-26 15:42:52.185  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-26 15:42:52.185  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-26 15:42:52.185  1017  1131 D Tethering: MasterInitialState.processMessage what=3
,08-26 15:42:52.185  6945  6945 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:52.185  1177  1177 D HotspotTile: onReceive : 0, 0
,08-26 15:42:52.185  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:52.185  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:52.185  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:52.185  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:52.185  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:52.185  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:52.185  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:52.185  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:42:52.185  1017  1123 V NetworkStats: updateIfacesLocked()
08-26 15:42:52.185  6945  6945 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:52.185  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-26 15:42:52.185  6945  6945 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:42:52.185  7211  7211 D IntelligenceServiceApplication: onCreate()
08-26 15:42:52.185  6945  6945 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:52.185  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:52.185  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:52.185  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:52.185  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:52.185  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:52.185  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:52.185  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:52.185  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:42:52.185  6945  6945 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:52.195  1017  1123 V NetworkStats: performPollLocked() took 3ms
08-26 15:42:52.185  6945  6945 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:42:52.185  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:52.185  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:42:52.185  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 15:42:52.195  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:52.195  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:52.195  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:52.195  1017  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,08-26 15:42:52.195  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:52.195  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:52.195  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-26 15:42:52.195  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 15:42:52.195  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 15:42:52.195  1177  1177 D StatusBar.NetworkController: updateDataNetType()
,08-26 15:42:52.195  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-26 15:42:52.195  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-26 15:42:52.195  7211  7211 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-26 15:42:52.195  1017  1544 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-26 15:42:52.205  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-26 15:42:52.205  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 23 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-26 15:42:52.205  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:52.205  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:52.205  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-26 15:42:52.205  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-26 15:42:52.205  7211  7211 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-26 15:42:52.205  1017  3827 I ActivityManager: Killing 6842:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
08-26 15:42:52.205  7211  7211 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-26 15:42:52.205  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 15:42:52.205  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:52.205  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 15:42:52.205  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.205  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.205  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.205  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:52.215  3209  3285 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 15:42:52.215  3209  3285 D BtConfig.SecureMode: isSecureModeOn:false
08-26 15:42:52.215  3209  3285 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-26 15:42:52.215  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-26 15:42:52.215  3209  3285 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-26 15:42:52.215  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 15:42:52.215  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-26 15:42:52.215  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-26 15:42:52.215  1017  3827 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-26 15:42:52.215  1017  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:52.215  1017  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:52.215  1017  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:52.215  1017  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:52.225  7233  7233 E Zygote  : MountEmulatedStorage(),
,08-26 15:42:52.225  7233  7233 I libpersona: KNOX_SDCARD checking this for 10105
08-26 15:42:52.225  7233  7233 E Zygote  : v2
08-26 15:42:52.225  7233  7233 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:52.225  7233  7233 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:42:52.225  1017  3827 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7233 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-26 15:42:52.225  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:52.225  1017  1546 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:52.225  1017  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.225  1017  1546 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-26 15:42:52.225  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 15:42:52.235  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 15:42:52.235  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 15:42:52.235  7233  7233 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 15:42:52.235  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-26 15:42:52.235  1017  3830 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:52.235  3209  3209 D HeadsetService: Received stop request...Stopping profile...
,08-26 15:42:52.235  1017  3830 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-26 15:42:52.235  1017  3830 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:52.235  1017  3830 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.235  1017  3830 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 15:42:52.235  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-26 15:42:52.235  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 15:42:52.235  7233  7233 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-26 15:42:52.235  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 15:42:52.235  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
08-26 15:42:52.235  1017  1544 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:52.235  1017  1544 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:52.235  1017  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-26 15:42:52.235  1017  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.235  1017  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:52.245  4726  4726 D HeadsetProfile: Bluetooth service disconnected
08-26 15:42:52.245  3209  3209 D A2dpService: Received stop request...Stopping profile...
08-26 15:42:52.245  3209  3370 D A2dpStateMachine: Exit Disconnected: -1
,08-26 15:42:52.245  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 15:42:52.245  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-26 15:42:52.245  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-26 15:42:52.245  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 15:42:52.245  1017  1503 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:52.245  1017  1503 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 15:42:52.245  1017  1503 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:52.245  1017  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.245  1017  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 15:42:52.245  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-26 15:42:52.245  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 15:42:52.245  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
08-26 15:42:52.245  1017  1017 D BluetoothA2dp: Proxy object disconnected
08-26 15:42:52.245  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-26 15:42:52.245  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-26 15:42:52.245  4726  4726 D BluetoothA2dp: Proxy object disconnected
08-26 15:42:52.245  4726  4726 D A2dpProfile: Bluetooth service disconnected
,08-26 15:42:52.255  1017  3829 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:52.255  1017  3829 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 15:42:52.255  1017  3829 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:52.255  1017  3829 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.255  1017  3829 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:52.255  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 15:42:52.255  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-26 15:42:52.255  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 15:42:52.255  1017  1136 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:52.255  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 15:42:52.255  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:52.255  1017  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.255  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:52.255  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-26 15:42:52.255  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 15:42:52.255  3209  3285 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 15:42:52.255  1017  3830 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:52.255  1017  3830 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-26 15:42:52.255  1017  3830 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:52.255  1017  3830 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:42:52.255  1017  3830 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 15:42:52.265  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:42:52.265  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 15:42:52.265  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:42:52.265  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:42:52.265  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-26 15:42:52.265  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:42:52.265  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 15:42:52.265  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-26 15:42:52.265  7233  7233 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:42:52.265  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 15:42:52.265  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-26 15:42:52.265  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-26 15:42:52.265  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 15:42:52.265  3209  3285 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 15:42:52.265  3209  3209 E BluetoothAdapterService(441650423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-26 15:42:52.265  3209  3209 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 15:42:52.265  3209  3209 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-26 15:42:52.265  7233  7233 D ActivityThread: Added TimaKeyStore provider
08-26 15:42:52.265  3209  3209 D HidService: Received stop request...Stopping profile...
08-26 15:42:52.265  3209  3209 D HidService: Stopping Bluetooth HidService
08-26 15:42:52.265  3209  3209 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 15:42:52.265  3209  3209 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-26 15:42:52.265  3209  3209 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 15:42:52.265  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
,08-26 15:42:52.265  4726  4726 D BluetoothInputDevice: Proxy object disconnected
08-26 15:42:52.265  4726  4726 D HidProfile: Bluetooth service disconnected
,08-26 15:42:52.275  3209  3209 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 15:42:52.275  3209  3209 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-26 15:42:52.275  3209  3209 D HealthService: Received stop request...Stopping profile...
08-26 15:42:52.275  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
,08-26 15:42:52.275  3209  3209 E BluetoothAdapterService(441650423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-26 15:42:52.275  3209  3209 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 15:42:52.275  3209  3209 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-26 15:42:52.275  3209  3209 D BluetoothA2dp: Proxy object disconnected
08-26 15:42:52.275  3209  3209 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-26 15:42:52.275  3209  3371 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-26 15:42:52.275  3209  3209 I GKI_LINUX: GKI_exit_task 2 done
08-26 15:42:52.275  3209  3209 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-26 15:42:52.275  3209  3209 D PanService: Received stop request...Stopping profile...
08-26 15:42:52.275  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
08-26 15:42:52.285  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 15:42:52.285  3209  3209 D BluetoothMapService: Received stop request...Stopping profile...
,08-26 15:42:52.285  4726  4726 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 15:42:52.285  4726  4726 D PanProfile: Bluetooth service disconnected
,08-26 15:42:52.285  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
,08-26 15:42:52.285  3209  3209 D SapService: Received stop request...Stopping profile...
,08-26 15:42:52.285  3209  3209 D SapService: Stopping Bluetooth SapService
,08-26 15:42:52.285  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
,08-26 15:42:52.295  4726  4726 D BluetoothMap: Proxy object disconnected
,08-26 15:42:52.295  4726  4726 D MapProfile: Bluetooth service disconnected
08-26 15:42:52.295  3209  3209 E BluetoothAdapterService(441650423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-26 15:42:52.295  3209  3209 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 15:42:52.295  3209  3209 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:42:52.295  3209  3209 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-26 15:42:52.295  3209  3209 E BluetoothAdapterService(441650423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-26 15:42:52.295  3209  3209 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 15:42:52.295  3209  3209 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:42:52.295  3209  3209 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-26 15:42:52.295  3209  3209 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 15:42:52.295  3209  3209 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 15:42:52.295  3209  3209 E BluetoothAdapterService(441650423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-26 15:42:52.295  3209  3209 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 15:42:52.295  3209  3209 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:42:52.295  3209  3209 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-26 15:42:52.295  4726  4726 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-26 15:42:52.295  3209  3209 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 15:42:52.295  3209  3209 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 15:42:52.295  4726  4726 D SapProfile: Bluetooth service disconnected
,08-26 15:42:52.295  3209  3209 E BluetoothAdapterService(441650423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-26 15:42:52.295  3209  3209 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 15:42:52.295  3209  3209 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 15:42:52.295  3209  3209 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-26 15:42:52.295  3209  3209 E BluetoothAdapterService(441650423): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-26 15:42:52.295  3209  3209 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,08-26 15:42:52.295  3209  3209 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-26 15:42:52.295  3209  3209 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-26 15:42:52.295  3209  3285 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-26 15:42:52.295  3209  3285 D BluetoothAdapterProperties: Setting state to 10
08-26 15:42:52.295  3209  3285 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 15:42:52.295  3209  3285 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 15:42:52.295  3209  3285 D BluetoothAdapterService: updateAdapterState state is 10
08-26 15:42:52.295  3209  3285 D BluetoothAdapterService: Autoconnection is available 
08-26 15:42:52.295  3209  3285 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-26 15:42:52.295  3209  3285 I BluetoothAdapterState: Entering OffState
,08-26 15:42:52.295  1177  3283 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:42:52.295  1177  3283 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:42:52.305  1458  1482 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 15:42:52.305  1458  1482 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 15:42:52.305  1639  1655 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:42:52.305  1639  1655 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:42:52.305  3209  3291 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 15:42:52.315  4726  4736 D Bluetoothsap: onBluetoothStateChange: up=false
08-26 15:42:52.315  4726  4736 D Bluetoothsap: Unbinding service...
,08-26 15:42:52.315  4726  4734 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 15:42:52.315  6945  6953 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:42:52.315  6945  6953 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 15:42:52.315  6945  6953 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-26 15:42:52.315  6945  6953 D BluetoothLeAdvertiser: Exit stop advertising
08-26 15:42:52.315  6945  6953 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-26 15:42:52.315  6945  6953 D BluetoothLeScanner: Exiting stopAllScan
,08-26 15:42:52.315  4726  4734 D BluetoothInputDevice: onBluetoothStateChange: up=false,
08-26 15:42:52.315  4726  4736 D BluetoothAdapter: onBluetoothStateChange: up=false,
08-26 15:42:52.315  4726  4736 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 15:42:52.315  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 15:42:52.315  1668  1751 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:42:52.315  1668  1751 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 15:42:52.315  4726  4734 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 15:42:52.315  4726  4736 D BluetoothMap: onBluetoothStateChange: up=false
08-26 15:42:52.315  1441  1457 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:42:52.315  1441  1457 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:42:52.325  1381  1381 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 15:42:52.325  3209  3377 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:42:52.325  3209  3377 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:42:52.325  1448  1466 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:42:52.325  1448  1466 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:42:52.325  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:42:52.325  1017  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:42:52.345  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:52.345  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
08-26 15:42:52.345  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 15:42:52.355  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 15:42:52.355  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:52.355  1177  1177 D BluetoothTile:  getBluetoothState : 10
,08-26 15:42:52.355  1962  1962 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 15:42:52.355  4726  4726 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:42:52.355  1017  1029 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 15:42:52.355  1017  1546 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-26 15:42:52.355  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 15:42:52.355  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 15:42:52.355  6945  6945 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:52.355  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:52.355  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:52.355  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:52.355  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:52.355  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:52.355  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:52.355  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:52.355  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:42:52.365  1381  1381 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-26 15:42:52.365  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 15:42:52.365  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 15:42:52.365  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-26 15:42:52.365  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:52.365  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.365  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:52.375  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.375  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:52.375  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.375  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 15:42:52.375  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.375  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:52.385  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.385  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:52.385  6945  6945 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 15:42:52.385  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.385  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:52.385  1381  1381 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-26 15:42:52.385  1381  1381 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-26 15:42:52.385  1381  1381 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-26 15:42:52.385  1381  1381 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-26 15:42:52.385  1381  1381 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-26 15:42:52.385  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:42:52.385  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-26 15:42:52.385  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 15:42:52.395  1017  1131 D Tethering: InitialState.processMessage what=4
08-26 15:42:52.395  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.395  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:42:52.395  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-26 15:42:52.395  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:52.395  1017  1131 E Tethering: No numeric data
08-26 15:42:52.395  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 15:42:52.395  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 15:42:52.395  1017  1131 D Tethering: clearTetheredNotification()
,08-26 15:42:52.395  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-26 15:42:52.395  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:52.395  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:42:52.395  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 15:42:52.395  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.395  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-26 15:42:52.395  1177  1177 D HotspotTile: updateTetherState():false, false
08-26 15:42:52.395  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:52.395  1017  1123 V NetworkStats: performPollLocked() took 4ms
,08-26 15:42:52.405  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:42:52.405  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-26 15:42:52.405  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 15:42:52.405  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:52.405  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 15:42:52.405  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:52.405  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-26 15:42:52.405  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:42:52.405  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-26 15:42:52.405  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 15:42:52.405  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 15:42:52.405  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.405  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 15:42:52.405  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.405  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 15:42:52.405  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.415  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
08-26 15:42:52.415  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.415  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:52.415  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.415  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:52.415  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.415  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 15:42:52.415   257   535 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 15:42:52.415   257   535 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 15:42:52.415  7233  7257 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-26 15:42:52.425   257   535 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 15:42:52.425   257   535 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 15:42:52.425  7233  7257 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-26 15:42:52.575  7233  7233 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 15:42:52.575  7233  7233 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:42:52.575  7233  7233 D StrictMode: StrictMode policy violation; ~duration=149 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:42:52.575  7233  7233 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08,-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:42:52.575  7233  7233 D StrictMode: StrictMode policy violation; ~duration=144 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.q.k.d(PG:583)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:42:52.575  7233  7233 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:42:52.575  7233  7233 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:42:52.575  7233  7233 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:52.575  7233  7233 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:42:52.585  1017  3827 I ActivityManager: Killing 6851:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
08-26 15:42:52.585  1017  3829 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 15:42:52.585  1017  3829 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 15:42:52.585  1017  3829 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:52.585  1017  3829 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.585  1017  3829 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 15:42:52.585  2214  2214 I Hs20UtilService: Starting #8
08-26 15:42:52.585  2214  2229 I Hs20UtilService: Message received 5007
08-26 15:42:52.595  4726  4726 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 15:42:52.595  4726  4726 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 15:42:52.595  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 15:42:52.605  1381  1381 I wpa_supplicant: Blacklist: Clear (all) 
08-26 15:42:52.605  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 15:42:52.605  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 15:42:52.605  4726  4726 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 15:42:52.605  4726  4795 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-26 15:42:52.605  1017  1545 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:52.605  1017  1545 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:52.605  1017  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
08-26 15:42:52.605  1017  1545 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
08-26 15:42:52.605  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:52.605  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:52.605  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:52.605  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:52.625  7278  7278 E Zygote  : MountEmulatedStorage()
08-26 15:42:52.625  7278  7278 E Zygote  : v2
08-26 15:42:52.625  7278  7278 I libpersona: KNOX_SDCARD checking this for 10102
08-26 15:42:52.625  7278  7278 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:52.625  7278  7278 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:42:52.635  1017  1545 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7278 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-26 15:42:52.635  7278  7278 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:52.635  7278  7278 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-26 15:42:52.635  7233  7273 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-26 15:42:52.655  7278  7278 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:52.655  7278  7278 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:52.665  1017  1488 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:52.665  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:52.665  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:52.665  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-26 15:42:52.675  1381  1381 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-26 15:42:52.675  7278  7278 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 15:42:52.675  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:52.685  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 15:42:52.685  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-26 15:42:52.685  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 15:42:52.685  1017  1017 I ApplicationPolicy: updateDataUsageMap
,08-26 15:42:52.695  1017  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:52.705  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:52.705  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:52.785  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-26 15:42:52.785  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 15:42:52.795  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 15:42:52.795  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:52.795  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 15:42:52.795  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.795  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.795  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.795  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:52.795  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.795  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:52.795  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-26 15:42:52.795  1177  1177 D HotspotTile: onReceive : 1, 0
08-26 15:42:52.795  1177  1666 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 15:42:52.795  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:52.805  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:52.805  1639  2133 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:42:52.805  4726  4726 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:42:52.895  7278  7300 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-26 15:42:52.895  7278  7300 I Babel_SMS: MmsConfig.loadMmsSettings
08-26 15:42:52.895  7278  7300 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-26 15:42:52.895  7278  7300 I Babel_SMS: MmsConfig.loadFromDatabase
,08-26 15:42:52.905  7278  7300 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-26 15:42:52.905  7278  7300 I Babel_SMS: MmsConfig.loadFromResources
,08-26 15:42:52.925  7278  7300 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-26 15:42:52.925  7278  7300 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-26 15:42:52.945  1017  1456 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-26 15:42:52.945  1017  1456 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-26 15:42:52.945  1017  1456 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:52.945  1017  1456 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:52.945  1017  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 15:42:52.965  7278  7278 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:42:52.965  7278  7278 I Babel_Crash: startup - clean
,08-26 15:42:52.995  4726  4726 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 15:42:52.995  4726  4726 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 15:42:52.995  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 15:42:52.995  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 15:42:52.995  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-26 15:42:52.995  4726  4726 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 15:42:52.995  4726  4795 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 15:42:53.005  1017  3827 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-26 15:42:53.005  1017  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:53.005  1017  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.005  1017  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:53.005  1017  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:53.005  7278  7278 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
,08-26 15:42:53.005  7278  7278 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 15:42:53.015  7278  7278 W AudioCapabilities: Unsupported mime audio/qcelp
,08-26 15:42:53.015  7303  7303 E Zygote  : MountEmulatedStorage()
,08-26 15:42:53.015  7303  7303 E Zygote  : v2
08-26 15:42:53.015  7303  7303 I libpersona: KNOX_SDCARD checking this for 10064
08-26 15:42:53.015  7303  7303 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:53.015  1017  3827 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7303 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 15:42:53.015  7303  7303 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:53.015  7303  7303 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 15:42:53.025  7303  7303 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:42:53.025  7278  7278 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-26 15:42:53.025  7278  7278 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-26 15:42:53.025  7278  7278 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-26 15:42:53.025  7278  7278 W AudioCapabilities: Unsupported mime audio/x-ima
,08-26 15:42:53.045  7278  7278 W AudioCapabilities: Unsupported mime audio/qcelp
,08-26 15:42:53.045  7303  7303 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:53.045  7278  7278 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 15:42:53.045  1017  1095 V AlarmManager: waitForAlarm result :4
,08-26 15:42:53.045  7303  7303 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:53.055  7278  7278 W VideoCapabilities: Unsupported mime video/wvc1
,08-26 15:42:53.055  7278  7278 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-26 15:42:53.065  7278  7278 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
08-26 15:42:53.065  7303  7303 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-26 15:42:53.065  7278  7278 W VideoCapabilities: Unsupported mime video/wvc1
08-26 15:42:53.065  7278  7278 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-26 15:42:53.075  7278  7278 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-26 15:42:53.075  7278  7278 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-26 15:42:53.085  7303  7303 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 15:42:53.085  7278  7278 W VideoCapabilities: Unsupported mime video/mp43
08-26 15:42:53.085  7303  7303 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-26 15:42:53.095  7278  7278 W VideoCapabilities: Unsupported mime video/sorenson
08-26 15:42:53.095  7278  7278 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-26 15:42:53.115  7278  7278 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-26 15:42:53.125  7303  7303 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 15:42:53.125  1017  1456 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-26 15:42:53.125  1017  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 15:42:53.125  1017  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.125  1017  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.125  1017  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:53.145  1017  1456 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7318 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 15:42:53.145  7318  7318 E Zygote  : MountEmulatedStorage()
08-26 15:42:53.145  7318  7318 I libpersona: KNOX_SDCARD checking this for 10065
08-26 15:42:53.145  7318  7318 E Zygote  : v2
08-26 15:42:53.145  7318  7318 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:53.145  1017  1456 I ActivityManager: Killing 6872:com.wsomacp/u0a23 (adj 15): empty #21
,08-26 15:42:53.145  7318  7318 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:53.145  7318  7318 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:42:53.145  7318  7318 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:42:53.145  7278  7278 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-26 15:42:53.145  7278  7278 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 15:42:53.155  7278  7278 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 15:42:53.155  7278  7278 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 15:42:53.165  1017  1136 I ActivityManager: Killing 6916:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,08-26 15:42:53.165  7278  7278 I vclib   : onServiceConnected
,08-26 15:42:53.175  7318  7318 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:53.175  7318  7318 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:53.195  7318  7318 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 15:42:53.205  1017  3829 I ActivityManager: Killing 6962:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-26 15:42:53.215  1017  1307 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 15:42:53.215  1017  1307 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 15:42:53.215  1017  1307 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:53.215  1017  1307 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:53.215  1017  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:42:53.215  2214  2214 I Hs20UtilService: Starting #9
08-26 15:42:53.215  2214  2229 I Hs20UtilService: Message received 5007
,08-26 15:42:53.215  4726  4726 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 15:42:53.215  4726  4726 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 15:42:53.215  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 15:42:53.225  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 15:42:53.225  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-26 15:42:53.225  4726  4726 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 15:42:53.225  1017  3830 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 15:42:53.225  4726  4795 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 15:42:53.225  1017  3830 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 15:42:53.225  1017  3830 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:53.225  1017  3830 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:53.225  1017  3830 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:42:53.235  2214  2214 I Hs20UtilService: Starting #10
,08-26 15:42:53.235  2214  2229 I Hs20UtilService: Message received 5011
,08-26 15:42:53.235  7121  7121 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 15:42:53.235  7121  7121 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 15:42:53.235  7121  7121 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 15:42:53.235  7121  7121 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 15:42:53.245  1017  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:53.255  1017  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:53.255  1017  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:53.255  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:53.255  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:53.255  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:53.255  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:53.255  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:53.255  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:53.265  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:53.265  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:53.265  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:53.265  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:53.265  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:53.265  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:53.265  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:53.265  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:53.265  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:53.275  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:53.275  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:42:53.275  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:53.275  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:53.275  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:53.275  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:53.275  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:53.275  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:53.275  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:53.285  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:53.285  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:53.285  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:53.285  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:53.285  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:53.285  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system,
,08-26 15:42:53.285  1017  1017 W ActivityManager: userId = 0, bbcId = -10000,
08-26 15:42:53.285  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:53.285  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:53.295  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:53.295  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:53.295  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:53.305  4726  4726 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 15:42:53.305  1017  1546 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 15:42:53.305  1017  1546 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 15:42:53.305  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:53.305  1017  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:42:53.305  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 15:42:53.315  1017  1044 D Tethering: interfaceRemoved wlan0
,08-26 15:42:53.315  1017  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-26 15:42:53.315  1668  1668 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 15:42:53.325  4726  4726 D DockEventReceiver: finishStartingService: stopping service
,08-26 15:42:53.325  4726  4726 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 15:42:53.335  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:42:53.335  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-26 15:42:53.345  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:53.345  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:53.345  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:53.355  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:53.355  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:53.355  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:53.355  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-26 15:42:53.355  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.355  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.355  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.355  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:53.365  1017  1017 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7335 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 15:42:53.365  7335  7335 E Zygote  : MountEmulatedStorage()
08-26 15:42:53.365  7335  7335 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:42:53.365  7335  7335 E Zygote  : v2
08-26 15:42:53.365  7335  7335 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:53.365  7335  7335 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:53.375  7335  7335 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:42:53.375  7335  7335 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:42:53.395  7335  7335 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:53.395  7335  7335 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:53.415  7335  7335 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-26 15:42:53.415  7335  7335 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-26 15:42:53.415  7335  7335 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-26 15:42:53.425  1017  1049 I PowerManagerService: [PWL] Off : 50s ago
,08-26 15:42:53.425  1017  1049 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-26 15:42:53.425  1017  1049 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-26 15:42:53.425  1017  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1017, ws=null) (elapsedTime=1242)
,08-26 15:42:53.425  1017  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1017, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=380)
,08-26 15:42:53.435  7335  7335 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-26 15:42:53.435  7335  7335 I PCWCLIENTTRACE_PushUtil: sales region : global
08-26 15:42:53.435  7335  7335 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-26 15:42:53.435  7335  7335 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:53.435  1017  1136 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,08-26 15:42:53.435  1017  1136 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
08-26 15:42:53.435  1017  1136 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-26 15:42:53.435  7335  7351 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-26 15:42:53.435  1017  1136 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-26 15:42:53.435  1017  1136 I ActivityManager: Killing 1832:com.google.android.gms/u0a11 (adj 15): empty #21
,08-26 15:42:53.445  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-26 15:42:53.445  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:53.445  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.445  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.445  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:53.455  7353  7353 E Zygote  : MountEmulatedStorage()
08-26 15:42:53.455  7353  7353 E Zygote  : v2
08-26 15:42:53.455  7353  7353 I libpersona: KNOX_SDCARD checking this for 10001
08-26 15:42:53.455  7353  7353 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:53.455  7353  7353 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:53.465  7353  7353 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 15:42:53.465  7353  7353 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-26 15:42:53.465  1017  1017 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7353 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 15:42:53.475  7353  7353 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:53.485  7353  7353 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:53.535  1017  1044 D Tethering: interfaceRemoved p2p0
,08-26 15:42:53.535  1017  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-26 15:42:53.555  1017  1307 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-26 15:42:53.555  1017  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:53.555  1017  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.555  1017  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.555  1017  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:53.575  7371  7371 E Zygote  : MountEmulatedStorage(),
08-26 15:42:53.575  7371  7371 E Zygote  : v2
08-26 15:42:53.575  7371  7371 I libpersona: KNOX_SDCARD checking this for 1000,
08-26 15:42:53.575  7371  7371 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:53.585  1017  1307 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7371 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 15:42:53.585  7371  7371 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:53.585  1017  1307 I ActivityManager: Killing 6983:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-26 15:42:53.585  7371  7371 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:53.585  7371  7371 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-26 15:42:53.605  7371  7371 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-26 15:42:53.605  7371  7371 D ActivityThread: Added TimaKeyStore provider,
,08-26 15:42:53.605   305   305 I art     : Explicit concurrent mark sweep GC freed 8708(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 30.685ms
,08-26 15:42:53.625   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 572us total 16.398ms
,08-26 15:42:53.635  7371  7371 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] ,
,08-26 15:42:53.645   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 16.365ms
,08-26 15:42:53.765  7371  7371 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-26 15:42:53.765   288   288 E SMD     : DCD OFF
,08-26 15:42:53.775  7371  7371 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-26 15:42:53.775  7371  7371 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:53.775  7371  7371 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-26 15:42:53.775  7371  7371 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-26 15:42:53.775  7371  7371 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-26 15:42:53.785  1017  3830 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-26 15:42:53.785  1017  3830 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:53.785  1017  3830 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.785  1017  3830 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.785  1017  3830 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:53.785  1017  3380 D SSRM:n  : SIOP:: AP = 400,
,08-26 15:42:53.795  7386  7386 E Zygote  : MountEmulatedStorage(),
08-26 15:42:53.795  1017  3830 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7386 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 15:42:53.795  7386  7386 E Zygote  : v2
08-26 15:42:53.795  7386  7386 I libpersona: KNOX_SDCARD checking this for 10008
08-26 15:42:53.795  7386  7386 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:53.795  1017  3830 I ActivityManager: Killing 6630:com.android.mms/u0a41 (adj 15): empty #21
,08-26 15:42:53.795  7386  7386 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:53.805  7386  7386 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:53.805  7386  7386 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-26 15:42:53.825  7386  7386 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:53.825  7386  7386 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:53.895  1017  3827 D ActivityManager: startProcessLocked calleePkgName: com.google.android.gms, hostingType: broadcast
,08-26 15:42:53.895  1017  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 15:42:53.895  1017  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.895  1017  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.895  1017  3827 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:53.915  7401  7401 E Zygote  : MountEmulatedStorage(),
08-26 15:42:53.915  1017  3827 I ActivityManager: Start proc com.google.android.gms for broadcast com.google.android.gms/.gcm.gmsproc.GmsAutoStarter: pid=7401 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
08-26 15:42:53.915  1017  3827 I ActivityManager: Killing 7017:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-26 15:42:53.915  7401  7401 E Zygote  : v2
08-26 15:42:53.915  7401  7401 I libpersona: KNOX_SDCARD checking this for 10011
08-26 15:42:53.915  7401  7401 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:42:53.915  7401  7401 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:53.915  7401  7401 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:53.925  7401  7401 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 15:42:53.945  7401  7401 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:42:53.945  1017  1227 D CountryDetector: No listener is left
,08-26 15:42:53.945  7401  7401 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:53.975  7401  7401 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-26 15:42:53.975  7401  7401 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-26 15:42:54.015  7401  7401 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-26 15:42:54.015  7401  7401 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-26 15:42:54.015  7401  7401 I MultiDex: VM with version 2.1.0 has multidex support
,08-26 15:42:54.015  7401  7401 I MultiDex: install
08-26 15:42:54.025  7401  7401 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-26 15:42:54.125  7401  7401 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-26 15:42:54.175  7401  7401 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-26 15:42:54.175  7401  7401 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@21524fc0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-26 15:42:54.175  7401  7401 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-26 15:42:54.185  1017  1489 I ActivityManager: Killing 6266:com.samsung.android.sm/1000 (adj 15): empty #21
,08-26 15:42:54.195  1017  1456 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-26 15:42:54.195  1017  1456 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-26 15:42:54.195  1017  1456 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:54.195  1017  1456 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:54.195  1017  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 15:42:54.215  7401  7419 D NativeLibraryUtils: Install completed successfully. count=0 extracted=0
,08-26 15:42:54.265  7401  7423 I iu.SyncManager: SYNC; picasa accounts
,08-26 15:42:54.265  7401  7401 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-26 15:42:54.295  1017  1546 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 15:42:54.295  1017  1546 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,08-26 15:42:54.295  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:54.295  1017  1546 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:54.295  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:54.315  7401  7401 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 15:42:54.335  7401  7401 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,08-26 15:42:54.345  2849  2849 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Aug 26 15:42:54 GMT+02:00 2016
,08-26 15:42:54.345  1017  3827 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-26 15:42:54.345  1017  3827 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-26 15:42:54.345  1017  3827 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:54.345  1017  3827 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:54.345  1017  3827 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-26 15:42:54.355  2849  2849 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-26 15:42:54.355  1017  1545 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast,
08-26 15:42:54.365  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 15:42:54.365  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:54.365  2849  2849 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
08-26 15:42:54.365  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:54.365  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:54.365  2849  2849 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-26 15:42:54.365  2849  2849 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-26 15:42:54.375  2849  7427 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
08-26 15:42:54.375  7428  7428 I libpersona: KNOX_SDCARD checking this for 10031
08-26 15:42:54.375  7428  7428 E Zygote  : MountEmulatedStorage()
,08-26 15:42:54.375  7428  7428 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:54.375  7428  7428 E Zygote  : v2
08-26 15:42:54.375  2849  7427 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-26 15:42:54.375  7428  7428 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:54.385  2849  7427 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
08-26 15:42:54.385  7428  7428 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:42:54.385  7428  7428 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:42:54.385  2849  7427 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-26 15:42:54.395  1017  1545 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7428 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-26 15:42:54.395  2849  2849 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-26 15:42:54.405  7428  7428 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:54.405  7428  7428 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:54.435  7428  7428 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-26 15:42:54.435  1017  1227 I ActivityManager: Killing 7036:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-26 15:42:54.445  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-26 15:42:54.445  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-26 15:42:54.445  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:54.445  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:54.445  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:54.445  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:54.455  2785  7443 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-26 15:42:54.455  2785  7443 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-26 15:42:54.455  2785  7443 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
08-26 15:42:54.455  2785  7443 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
08-26 15:42:54.455  2785  7443 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-26 15:42:54.465  7444  7444 E Zygote  : MountEmulatedStorage()
,08-26 15:42:54.465  7444  7444 E Zygote  : v2
08-26 15:42:54.465  7444  7444 I libpersona: KNOX_SDCARD checking this for 10032
08-26 15:42:54.465  7444  7444 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:54.465  7444  7444 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:42:54.465  1017  1029 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7444 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 15:42:54.465  7444  7444 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 15:42:54.465  7444  7444 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-26 15:42:54.495  7444  7444 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:54.495  7444  7444 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:54.555  7444  7459 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-26 15:42:54.555  7444  7459 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-26 15:42:54.565  7444  7459 D SPPClientService: PushLog.txt file is not deleted.
08-26 15:42:54.565  7444  7459 D SPPClientService: PushLog.txt file is not deleted.
08-26 15:42:54.565  7444  7459 D SPPClientService: ============PushLog. stop!
,08-26 15:42:54.565  7444  7444 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-26 15:42:54.575  1017  1136 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-26 15:42:54.575  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:54.575  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:54.575  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:54.575  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:54.595  7461  7461 E Zygote  : MountEmulatedStorage()
08-26 15:42:54.595  7461  7461 E Zygote  : v2
08-26 15:42:54.595  7461  7461 I libpersona: KNOX_SDCARD checking this for 10036
08-26 15:42:54.595  7461  7461 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:54.595  1017  1136 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7461 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 15:42:54.595  1017  1136 I ActivityManager: Killing 7065:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,08-26 15:42:54.595  1017  1545 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push,
08-26 15:42:54.595  1017  1545 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
08-26 15:42:54.595  7461  7461 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:54.595  1017  1545 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:54.595  1017  1545 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-26 15:42:54.595  1017  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
08-26 15:42:54.595  7461  7461 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:42:54.605  7461  7461 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-26 15:42:54.615  7461  7461 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:54.615  7461  7461 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:54.635  7444  7467 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-26 15:42:54.655  7461  7461 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@27251acc
,08-26 15:42:54.665  7461  7461 I SA      : [SSP] onCreated
,08-26 15:42:54.675  7461  7461 I SA      : [TPM] There is no property file
,08-26 15:42:54.675  7461  7461 I SA      : [SCU] isHaveSA() - false
,08-26 15:42:54.675  7461  7461 I SA      : [TPM] getModelProperty : null
,08-26 15:42:54.675  7461  7461 I SA      : [TPM] getCSCProperty : null
,08-26 15:42:54.685  7461  7461 I SA      : [DM] FLOATING AMOLED FEATURE: true
,08-26 15:42:54.685  7461  7461 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-26 15:42:54.685  7461  7461 I SA      : [DM] TFT FEATURE: false
,08-26 15:42:54.685  7461  7461 I SA      : [DM] init START
,08-26 15:42:54.685  7461  7461 I SA      : [DM] This device is not a Vodafone
,08-26 15:42:54.695  7461  7461 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-26 15:42:54.695  7461  7461 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-26 15:42:54.695  7461  7461 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-26 15:42:54.695  7461  7461 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-26 15:42:54.695  7461  7461 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-26 15:42:54.695  7461  7461 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-26 15:42:54.695  7461  7461 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-26 15:42:54.695  7461  7461 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-26 15:42:54.695  7461  7461 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-26 15:42:54.695  7461  7461 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-26 15:42:54.705  7461  7461 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-26 15:42:54.705  7461  7461 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-26 15:42:54.705  7461  7461 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-26 15:42:54.705  7461  7461 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-26 15:42:54.705  7461  7461 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-26 15:42:54.705  7461  7461 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-26 15:42:54.705  7461  7461 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,08-26 15:42:54.705  7461  7461 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-26 15:42:54.705  7461  7461 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-26 15:42:54.705  7461  7461 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-26 15:42:54.705  7461  7461 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-26 15:42:54.705  7461  7461 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-26 15:42:54.705  7461  7461 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-26 15:42:54.705  7461  7461 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-26 15:42:54.705  7461  7461 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-26 15:42:54.705  7461  7461 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-26 15:42:54.705  7461  7461 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-26 15:42:54.705  7461  7461 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-26 15:42:54.715  7461  7461 I SA      : [SCU] isHaveSA() - false
08-26 15:42:54.715  7461  7461 I SA      : support phone number id : false
08-26 15:42:54.715  7461  7461 I SA      : [DM] Supports Ref Jpn : true
,08-26 15:42:54.715  7461  7461 I SA      : [DM] init END
08-26 15:42:54.715  7461  7461 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-26 15:42:54.715  7461  7461 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-26 15:42:54.715  7461  7461 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-26 15:42:54.725  7461  7461 I SA      : [SLFUCHKMGR] constructor called
,08-26 15:42:54.725  7461  7461 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-26 15:42:54.725  7461  7461 I SA      : [OR] == isSIMCardReady false ==
,08-26 15:42:54.725  7461  7461 I SA      : [SCU] == networkStateCheck == false
08-26 15:42:54.725  7461  7461 I SA      : [OR] onReceive END
,08-26 15:42:54.725  1017  1456 I ActivityManager: Killing 7154:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-26 15:42:54.735  1228  1228 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:54.735  1775  1775 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-26 15:42:54.745  2675  6453 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,08-26 15:42:54.745  1775  1775 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-26 15:42:54.745  1775  1775 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,08-26 15:42:54.745  1775  1775 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-26 15:42:54.745  1775  1775 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-26 15:42:54.755  1775  1775 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-26 15:42:54.755  1775  1775 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-26 15:42:54.755  1017  3829 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-26 15:42:54.755  1017  3829 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:54.755  1017  3829 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:54.755  1017  3829 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:54.755  1017  3829 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:54.765  1017  3829 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7483 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-26 15:42:54.765  7483  7483 E Zygote  : MountEmulatedStorage()
08-26 15:42:54.765  7483  7483 E Zygote  : v2
08-26 15:42:54.765  7483  7483 I libpersona: KNOX_SDCARD checking this for 10077
08-26 15:42:54.765  7483  7483 I libpersona: KNOX_SDCARD not a persona,
08-26 15:42:54.765  7483  7483 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:54.775  7483  7483 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 15:42:54.775   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:42:54.775  7483  7483 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL,
,08-26 15:42:54.785  7483  7483 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:54.795  7483  7483 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:54.945  1017  1547 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-26 15:42:54.945  1017  1547 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-26 15:42:54.955  1017  1547 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:54.955  1017  1547 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:54.955  1017  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 15:42:54.955  1017  3830 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-26 15:42:54.955  1017  3830 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:54.955  1017  3830 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:54.955  1017  3830 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:54.955  1017  3830 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:54.975  7501  7501 E Zygote  : MountEmulatedStorage(),
,08-26 15:42:54.975  1017  3830 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7501 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-26 15:42:54.975  1017  1503 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-26 15:42:54.975  1017  1503 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
08-26 15:42:54.975  7501  7501 E Zygote  : v2
08-26 15:42:54.975  1017  1503 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:54.975  1017  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:42:54.975  1017  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-26 15:42:54.975  7501  7501 I libpersona: KNOX_SDCARD checking this for 10110
08-26 15:42:54.975  7501  7501 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:54.975  1017  3830 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 15:42:54.975  1017  3830 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 15:42:54.975  1017  3830 D SecContentProvider2: mCursor = null
08-26 15:42:54.975  7501  7501 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:42:54.975  7278  7500 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
08-26 15:42:54.975  1017  3830 D WifiService: setWifiEnabled: true pid=6945, uid=10170
08-26 15:42:54.975  1017  3830 W ActivityManager: Permission Denial: getCurrentUser() from pid=6945, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-26 15:42:54.975  1017  3830 W WifiService: Failed getting userId using ActivityManagerNative
08-26 15:42:54.975  1017  3830 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6945, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-26 15:42:54.975  1017  3830 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 15:42:54.975  1017  3830 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 15:42:54.975  1017  3830 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 15:42:54.975  1017  3830 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 15:42:54.975  1017  3830 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-26 15:42:54.975  1017  3830 D SettingsProvider: name = wifi_on
,08-26 15:42:54.985  7501  7501 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:42:54.985  7501  7501 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-26 15:42:54.985  1017  1456 I ActivityManager: Killing 7170:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-26 15:42:54.985  1017  1126 E WifiHW  : ##################### set firmware type 0 #####################
,08-26 15:42:55.005  7501  7501 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:55.005  7501  7501 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:55.135  1017  1547 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 15:42:55.245   257   535 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-26 15:42:55.245   257   535 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 15:42:55.245  7501  7520 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-26 15:42:55.255   257   535 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-26 15:42:55.255   257   535 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 15:42:55.255  7501  7520 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-26 15:42:55.265   257   535 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-26 15:42:55.265   257   535 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 15:42:55.265  7501  7521 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-26 15:42:55.265   257   535 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-26 15:42:55.265   257   535 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 15:42:55.265  7501  7521 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-26 15:42:55.295  7501  7501 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-26 15:42:55.295  7501  7501 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-26 15:42:55.295  7501  7501 I GAv4    :   adb logcat -s GAv4
,08-26 15:42:55.325  7501  7501 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-26 15:42:55.325  1017  1489 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 15:42:55.335  7501  7501 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-26 15:42:55.345  7501  7529 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-26 15:42:55.455  1017  1044 D Tethering: interfaceAdded wlan0
,08-26 15:42:55.455  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 15:42:55.455  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-26 15:42:55.455  1017  1131 E Tethering: No numeric data
,08-26 15:42:55.455  1017  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0,
08-26 15:42:55.455  1017  1131 D Tethering: clearTetheredNotification()
,08-26 15:42:55.465  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-26 15:42:55.465  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:55.465  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 15:42:55.465  1177  1177 D HotspotTile: updateTetherState():false, false
,08-26 15:42:55.465  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 15:42:55.465  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 15:42:55.465  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 15:42:55.465  1017  1131 D Tethering: InitialState.processMessage what=4
,08-26 15:42:55.465  1017  1123 V NetworkStats: performPollLocked() took 5ms
08-26 15:42:55.465  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:55.465  1017  1044 D Tethering: interfaceAdded p2p0
,08-26 15:42:55.465  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:55.465  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:55.465  1017  1131 E Tethering: No numeric data
,08-26 15:42:55.465  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 15:42:55.475  1017  1131 D Tethering: clearTetheredNotification()
08-26 15:42:55.475  1017  1044 D Tethering: p2p0 is not a tetherable iface, ignoring,
08-26 15:42:55.475  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 15:42:55.475  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-26 15:42:55.475  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:55.475  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 15:42:55.475  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:42:55.475  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-26 15:42:55.475  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 15:42:55.475   278   999 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-26 15:42:55.475  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-26 15:42:55.475  1177  1177 D HotspotTile: updateTetherState():false, false
08-26 15:42:55.475  1017  1123 V NetworkStats: performPollLocked() took 4ms
08-26 15:42:55.475  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:55.475   278   999 D SoftapController: Softap fwReload - Ok
,08-26 15:42:55.475  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:55.475  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:55.475   278   999 D CommandListener: Setting iface cfg
08-26 15:42:55.475   278   999 D CommandListener: Trying to bring down wlan0
,08-26 15:42:55.475   278   999 D CommandListener: Clearing all IP addresses on wlan0
,08-26 15:42:55.485  1017  1126 E WifiHW  : supplicant_name : p2p_supplicant
,08-26 15:42:55.535  7542  7542 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-26 15:42:55.535  7542  7542 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 15:42:55.535  7542  7542 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-26 15:42:55.575  7542  7542 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-26 15:42:55.575   335   335 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7542
08-26 15:42:55.575   335   335 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
,08-26 15:42:55.575  7542  7542 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-26 15:42:55.575  7542  7542 I wpa_supplicant: ssSupport state is = 1
08-26 15:42:55.575  7542  7542 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-26 15:42:55.575  7542  7542 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-26 15:42:55.575   335   335 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7542
08-26 15:42:55.575   335   335 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-26 15:42:55.585  1017  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-26 15:42:55.595  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 15:42:55.595  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 15:42:55.605  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-26 15:42:55.605  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:55.605  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:55.605  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:55.605  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:55.605  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:55.605  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-26 15:42:55.605  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:42:55.605  1177  1177 D HotspotTile: onReceive : 2, 0
08-26 15:42:55.605  1177  1666 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 15:42:55.605  4726  4726 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:42:55.605  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:55.615  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:55.615  1017  1307 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:55.625  7501  7501 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-26 15:42:55.625  1017  1307 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:55.625  1017  1307 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:55.625  1017  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-26 15:42:55.645  7501  7501 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 4825-4828)
,08-26 15:42:55.645  7501  7501 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-26 15:42:55.675  7501  7501 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1dda08b7},
08-26 15:42:55.675  7501  7501 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-26 15:42:55.675  7501  7501 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 15:42:55.695  7501  7501 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-26 15:42:55.695  7501  7501 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 15:42:55.705  7501  7501 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 15:42:55.715  7501  7501 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 15:42:55.715  7501  7501 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 15:42:55.715  7501  7501 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 15:42:55.715  7501  7501 I Adreno-EGL: Local Branch: 
08-26 15:42:55.715  7501  7501 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 15:42:55.715  7501  7501 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 15:42:55.715  7501  7501 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 15:42:55.775   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:42:55.785   335   335 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
08-26 15:42:55.785  7542  7542 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-26 15:42:55.795  7501  7560 W cr.media: Requires BLUETOOTH permission
,08-26 15:42:55.805  7501  7501 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 15:42:55.815  7501  7501 I NSApplication: Starting up...
,08-26 15:42:55.815  1017  1030 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 15:42:55.815  1017  1503 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 15:42:55.825  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-26 15:42:55.825  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:55.825  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:55.825  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:55.825  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:55.835  7542  7542 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-26 15:42:55.835  7542  7542 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-26 15:42:55.835  7565  7565 E Zygote  : MountEmulatedStorage()
,08-26 15:42:55.835  7565  7565 E Zygote  : v2
08-26 15:42:55.835  7565  7565 I libpersona: KNOX_SDCARD checking this for 10117
,08-26 15:42:55.845  7565  7565 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:55.845  1017  1029 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7565 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-26 15:42:55.845  1017  1029 I ActivityManager: Killing 7136:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-26 15:42:55.845  7565  7565 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:55.845  7565  7565 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:42:55.845  7565  7565 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 15:42:55.855  7542  7542 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-26 15:42:55.855   335   335 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7542
08-26 15:42:55.855   335   335 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-26 15:42:55.855  7542  7542 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-26 15:42:55.855  7542  7542 I wpa_supplicant: ssSupport state is = 1
08-26 15:42:55.855  7542  7542 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-26 15:42:55.855  7542  7542 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 15:42:55.855  7542  7542 E wpa_supplicant: SIM READ ERROR
08-26 15:42:55.855  7542  7542 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:42:55.855  7542  7542 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 15:42:55.855  7542  7542 E wpa_supplicant: SIM READ ERROR
08-26 15:42:55.855  7542  7542 I wpa_supplicant: Blacklist: Clear (all) 
08-26 15:42:55.865  7542  7542 I wpa_supplicant: wpa_default_ap_write_once
,08-26 15:42:55.865  7542  7542 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 15:42:55.865  7542  7542 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:42:55.865  7542  7542 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-26 15:42:55.865  7542  7542 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:42:55.865  7542  7542 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 15:42:55.865  7542  7542 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-26 15:42:55.865  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 15:42:55.865  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-26 15:42:55.865  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 15:42:55.865  7565  7565 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:55.875  7565  7565 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:55.885  7565  7565 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 15:42:55.925  7542  7542 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-26 15:42:56.055  7542  7542 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
08-26 15:42:56.055  7542  7542 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage,
,08-26 15:42:56.065  7542  7542 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-26 15:42:56.065   335   335 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7542
08-26 15:42:56.065   335   335 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
08-26 15:42:56.065  7542  7542 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-26 15:42:56.065  7542  7542 I wpa_supplicant: ssSupport state is = 1
,08-26 15:42:56.065  7542  7542 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-26 15:42:56.065  7542  7542 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-26 15:42:56.075  7542  7542 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-26 15:42:56.075   335   335 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7542
08-26 15:42:56.075   335   335 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
08-26 15:42:56.075  7542  7542 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-26 15:42:56.075  7542  7542 I wpa_supplicant: ssSupport state is = 1
08-26 15:42:56.075  7542  7542 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:42:56.075  7542  7542 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 15:42:56.075  7542  7542 E wpa_supplicant: SIM READ ERROR,
08-26 15:42:56.075  7542  7542 I wpa_supplicant: wpa_default_ap_write_once
08-26 15:42:56.075  7542  7542 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 15:42:56.075  7542  7542 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 15:42:56.085  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 15:42:56.085  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-26 15:42:56.085  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 15:42:56.085  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 15:42:56.085  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
08-26 15:42:56.085  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 15:42:56.145  7542  7542 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-26 15:42:56.145  7542  7542 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-26 15:42:56.185  7542  7542 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-26 15:42:56.185  7542  7542 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-26 15:42:56.185  7542  7542 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 15:42:56.195  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-26 15:42:56.195  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 15:42:56.195  7542  7542 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-26 15:42:56.195  7542  7542 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-26 15:42:56.205  7542  7542 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-26 15:42:56.205  7542  7542 E wpa_supplicant: SIM READ ERROR
08-26 15:42:56.205  7542  7542 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 15:42:56.235  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-26 15:42:56.235  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:56.235  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:56.235  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:56.235  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:56.245  7591  7591 E Zygote  : MountEmulatedStorage(),
08-26 15:42:56.245  7591  7591 E Zygote  : v2
08-26 15:42:56.245  7591  7591 I libpersona: KNOX_SDCARD checking this for 10121
,08-26 15:42:56.245  7591  7591 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:56.255  1017  1029 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7591 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-26 15:42:56.255  1017  1029 I ActivityManager: Killing 7084:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-26 15:42:56.255  7591  7591 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:56.265  7591  7591 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:42:56.265  7591  7591 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:42:56.275  7591  7591 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:56.275  7591  7591 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:56.285  7542  7542 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-26 15:42:56.295  7591  7591 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 15:42:56.295  7591  7591 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-26 15:42:56.295  7591  7591 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 15:42:56.305  7542  7542 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 15:42:56.305  1017  1126 D WifiConfigStore: Loading config and enabling all networks 
,08-26 15:42:56.305  7591  7591 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:56.315  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 15:42:56.315  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:56.315  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 15:42:56.315  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:56.315  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:56.315  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-26 15:42:56.315  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:56.315  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:56.315  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:42:56.315  1177  1666 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 15:42:56.315  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-26 15:42:56.315  1177  1177 D HotspotTile: onReceive : 3, 0
08-26 15:42:56.315  4726  4726 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:42:56.325  1017  1126 E WifiConfigStore: Not a HS20
,08-26 15:42:56.325  6945  6945 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 15:42:56.325  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:56.325  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:56.325  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:56.325  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:56.325  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:56.325  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:56.325  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:56.325  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:42:56.325  6945  6945 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:56.325  6945  6945 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:42:56.325  7591  7591 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-26 15:42:56.325  1017  1126 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-26 15:42:56.335  6945  6945 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 15:42:56.335  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:56.335  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:56.335  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:56.335  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:56.335  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:56.335  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:56.335  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:56.335  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:42:56.335  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-26 15:42:56.335  7542  7542 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-26 15:42:56.335  7542  7542 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-26 15:42:56.335  6945  6945 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:56.335  6945  6945 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:42:56.335  7542  7542 I wpa_supplicant: reset timer : RESET_TIMER 0
,08-26 15:42:56.335  7542  7542 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 15:42:56.335  7542  7542 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-26 15:42:56.335  7542  7542 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-26 15:42:56.335  7542  7542 I wpa_supplicant: First Scan Start
08-26 15:42:56.335  7542  7542 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-26 15:42:56.335  7591  7591 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
08-26 15:42:56.335  1017  1126 D WifiNative-wlan0: Setting external_sim to 1
,08-26 15:42:56.335  1017  1126 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 15:42:56.335  1017  1126 I WifiNative-HAL: startHal
08-26 15:42:56.335  1017  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9f20c88c
08-26 15:42:56.335  1017  1126 I WifiNative-HAL: Could not start hal
,08-26 15:42:56.335  1017  1307 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-26 15:42:56.335  7278  7278 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:42:56.345  1017  1126 E WifiNative-wlan0: do suspend true,
,08-26 15:42:56.345  1017  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:56.345  1017  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:56.345  1017  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 15:42:56.345  1017  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:56.345  1017  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
08-26 15:42:56.345   278   999 D CommandListener: Setting iface cfg
08-26 15:42:56.345   278   999 D CommandListener: Trying to bring up p2p0
,08-26 15:42:56.345  1017  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 15:42:56.345  1017  1125 D WifiP2pService: P2pEnablingState
08-26 15:42:56.345  1017  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
08-26 15:42:56.345  1017  1125 D WifiP2pService: P2p socket connection successful
08-26 15:42:56.345  1017  1125 D WifiP2pService: P2pEnabledState
,08-26 15:42:56.365  7610  7610 E Zygote  : MountEmulatedStorage()
,08-26 15:42:56.365  7610  7610 I libpersona: KNOX_SDCARD checking this for 10141,
08-26 15:42:56.365  7610  7610 E Zygote  : v2
08-26 15:42:56.365  7610  7610 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:56.365  7610  7610 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:42:56.365  1017  1307 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7610 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-26 15:42:56.365  1017  1307 I ActivityManager: Killing 7100:com.android.calendar/u0a131 (adj 15): empty #21
08-26 15:42:56.365  7610  7610 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:56.365  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-26 15:42:56.365  1017  1128 E ConnectivityService: updateNetworkInfo()
08-26 15:42:56.365  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-26 15:42:56.365  7610  7610 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 15:42:56.365  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-26 15:42:56.365  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-26 15:42:56.365  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 15:42:56.365  1017  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 15:42:56.365  1017  1047 D WifiDisplayController: disconnect
08-26 15:42:56.365  1017  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 15:42:56.365  1017  1047 D WifiDisplayController: updateConnection
08-26 15:42:56.365  1017  1126 E WifiNative-wlan0: invaild command id : 215
,08-26 15:42:56.365  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 15:42:56.365  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 15:42:56.375  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 15:42:56.375  1017  1151 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:56.375  1017  1151 I WifiNative-HAL: startHal
08-26 15:42:56.375  1017  1017 D RttService: SCAN_AVAILABLE : 3
08-26 15:42:56.375  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:42:56.375  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-26 15:42:56.375  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 15:42:56.375  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null,
08-26 15:42:56.375  7542  7542 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 15:42:56.375  1017  1152 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 15:42:56.375  7542  7542 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,08-26 15:42:56.375  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-26 15:42:56.375  1017  1136 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 15:42:56.385  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-26 15:42:56.385  1017  1125 D WifiNative-p2p0: p2pGetDeviceAddress
,08-26 15:42:56.385  1017  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
08-26 15:42:56.385  1017  1151 E wifi    : getStaticLongField sWifiHalHandle 0x9e0ce9bc
08-26 15:42:56.385  1017  1151 I WifiNative-HAL: Could not start hal
08-26 15:42:56.385  1017  1151 E WifiScanningService: could not start HAL
,08-26 15:42:56.385  1017  1125 D WifiP2pService: DeviceAddress: 0a:75:42
08-26 15:42:56.385  7542  7542 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-26 15:42:56.385  1017  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-26 15:42:56.385  1017  1047 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-26 15:42:56.385  1017  1047 D WifiDisplayController:  primary type: 10-0050F204-5
08-26 15:42:56.385  1017  1047 D WifiDisplayController:  secondary type: null
08-26 15:42:56.385  1017  1047 D WifiDisplayController:  wps: 0
08-26 15:42:56.385  1017  1047 D WifiDisplayController:  grpcapab: 0
08-26 15:42:56.385  1017  1047 D WifiDisplayController:  devcapab: 0
08-26 15:42:56.385  1017  1047 D WifiDisplayController:  status: 3
08-26 15:42:56.385  1017  1047 D WifiDisplayController:  wfdInfo: null
08-26 15:42:56.385  1017  1047 D WifiDisplayController:  groupownerAddress: null
08-26 15:42:56.385  1017  1047 D WifiDisplayController:  GOdeviceName: null
08-26 15:42:56.385  1017  1047 D WifiDisplayController:  interfaceAddress: 
08-26 15:42:56.385  1017  1047 D WifiDisplayController:  SConnectInfo : null
,08-26 15:42:56.385  1017  1126 E WifiStateMachine: Failed to set frequency band 0
,08-26 15:42:56.385  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 15:42:56.385  1017  1126 D SecContentProvider2: mCursor = null
08-26 15:42:56.395  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 15:42:56.395  1017  1126 D SecContentProvider2: mCursor = null
08-26 15:42:56.395  7610  7610 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:56.395  7610  7610 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:56.415  7610  7610 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-26 15:42:56.415  7610  7610 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,08-26 15:42:56.415  7610  7610 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 15:42:56.415  7610  7610 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-26 15:42:56.415  1017  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
08-26 15:42:56.415  1017  1125 D WifiP2pService: InactiveState
08-26 15:42:56.415  7542  7542 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 15:42:56.415  1017  1125 D WifiP2pService: InactiveState{ what=143376 }
08-26 15:42:56.415  1017  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
08-26 15:42:56.415  1017  1125 D WifiP2pService: InactiveState{ what=143376 }
08-26 15:42:56.415  1017  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 15:42:56.455  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,08-26 15:42:56.455  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-26 15:42:56.455  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 15:42:56.465  1017  1547 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 15:42:56.475  1017  1544 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 15:42:56.495  1017  3827 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 15:42:56.505  1017  1307 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 15:42:56.545  1017  1456 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-26 15:42:56.545  1017  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:56.545  1017  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:56.545  1017  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:56.545  1017  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:56.565  7632  7632 E Zygote  : MountEmulatedStorage()
08-26 15:42:56.565  7632  7632 I libpersona: KNOX_SDCARD checking this for 10068
08-26 15:42:56.565  7632  7632 E Zygote  : v2
08-26 15:42:56.565  7632  7632 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:56.565  1017  1456 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7632 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-26 15:42:56.565  7632  7632 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:56.565  7632  7632 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:42:56.565  7632  7632 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,08-26 15:42:56.585  7632  7632 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:42:56.585  7632  7632 D ActivityThread: Added TimaKeyStore provider
08-26 15:42:56.585   305   305 I art     : Explicit concurrent mark sweep GC freed 8704(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 609us total 21.426ms
,08-26 15:42:56.585  1017  1546 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 15:42:56.595  1017  1544 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 15:42:56.605   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 19.102ms
,08-26 15:42:56.615  7632  7632 D BadgeProvider: onCreate
,08-26 15:42:56.615  7632  7632 D BadgeProvider: DatabaseHelper
,08-26 15:42:56.625  1017  1547 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 15:42:56.625   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 606us total 17.793ms
,08-26 15:42:56.635  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-26 15:42:56.635  7632  7647 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-26 15:42:56.635  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:56.635  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:56.635  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:56.635  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:56.655  7648  7648 E Zygote  : MountEmulatedStorage(),
08-26 15:42:56.655  7648  7648 I libpersona: KNOX_SDCARD checking this for 10009
08-26 15:42:56.655  7648  7648 E Zygote  : v2
,08-26 15:42:56.655  7648  7648 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:56.655  7648  7648 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:42:56.655  1017  1029 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7648 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,08-26 15:42:56.655  1017  1029 I ActivityManager: Killing 6100:com.android.vending/u0a26 (adj 15): empty #21,
08-26 15:42:56.655  1017  1029 I ActivityManager: Killing 6889:com.android.defcontainer/u0a3 (adj 15): empty #22
,08-26 15:42:56.665  7648  7648 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:56.665  7648  7648 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-26 15:42:56.695  7648  7648 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:56.695  7648  7648 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:56.765   288   288 E SMD     : DCD OFF
,08-26 15:42:56.785   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:42:56.785  1017  1227 I ActivityManager: Killing 7303:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-26 15:42:56.795  1017  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:42:56.795  1017  1489 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4262, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-26 15:42:56.795  1017  1489 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:42:56.795  1017  1489 D BatteryService: stay LED for charging
,08-26 15:42:56.795  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:42:56.805  1017  1017 I MotionRecognitionService: Plugged
,08-26 15:42:56.805  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:42:56.815  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:42:56.815  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:42:56.815  1423  1423 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:42:56.815  1423  1423 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:42:56.835  1017  1545 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 15:42:56.835  1017  1545 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:42:56.835  1017  1545 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:56.835  1017  1545 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:42:56.835  1017  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:42:56.845  2214  2214 I Hs20UtilService: Starting #11
,08-26 15:42:56.845  1017  1136 I art     : Explicit concurrent mark sweep GC freed 69610(3MB) AllocSpace objects, 12(240KB) LOS objects, 33% free, 23MB/34MB, paused 2.593ms total 176.964ms
,08-26 15:42:56.845  2214  2229 I Hs20UtilService: Message received 5011
,08-26 15:42:56.845  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:42:56.845  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:42:56.845  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 15:42:56.845  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 15:42:56.845  1177  1177 D SViewCoverView: level :100 plugged : 2
,08-26 15:42:56.845  7121  7121 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 15:42:56.845  7121  7121 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 15:42:56.845  7121  7121 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 15:42:56.855  7121  7121 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 15:42:56.855  7632  7640 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,08-26 15:42:56.855  7632  7640 D BadgeProvider: sendNotify, [notify] : null
08-26 15:42:56.855  7632  7640 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-26 15:42:56.855  7632  7640 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-26 15:42:56.855  7632  7640 D BadgeProvider: update, [UpdateCount] : 1
,08-26 15:42:56.855  1490  1490 D Launcher.Model: reloadBadges entered.
,08-26 15:42:56.875  1017  3829 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:56.875  1017  3829 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:56.875  1017  3829 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:56.875   278   995 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 15:42:56.875   278   995 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-26 15:42:56.885  1017  3827 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-26 15:42:56.885  1017  3827 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
08-26 15:42:56.885  1017  1544 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-26 15:42:56.885  1017  1544 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
08-26 15:42:56.885  1017  1544 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:56.885  1017  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:56.885  1017  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 15:42:56.885  1017  1547 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-26 15:42:56.885  1017  1030 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
08-26 15:42:56.885  1017  1030 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
08-26 15:42:56.885  1017  1030 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
08-26 15:42:56.885  1017  1030 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
08-26 15:42:56.885  1668  4239 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-26 15:42:56.885  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:56.885  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:56.885  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:56.895  1017  3827 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-26 15:42:56.905  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:56.905  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:56.905  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:56.905  1668  1668 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-26 15:42:56.915  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:56.915  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:56.915  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:56.915  1017  1227 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-26 15:42:56.915  1017  1227 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,08-26 15:42:56.915  1017  1227 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:56.915  1017  1227 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:56.915  1017  1227 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 15:42:56.915  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:56.925  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:56.925  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:56.925  1668  1668 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 15:42:56.925  1668  1668 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
08-26 15:42:56.925  1017  3830 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:56.925  1017  3830 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:56.925  1017  3830 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:56.935  7401  7401 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,08-26 15:42:56.935  1017  1547 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 15:42:56.935  1017  1547 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,08-26 15:42:56.935  1017  1547 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:56.945  1017  1547 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:56.945  1017  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:56.945  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:56.945  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:56.945  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:56.945  1017  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:56.945  1017  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:56.945  1017  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:56.965  1017  1456 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:56.965  1017  1456 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:56.965  1017  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:56.965  1017  3830 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:56.965  1017  3830 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:56.965  1017  3830 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:56.965  1017  3830 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:56.965  1017  3830 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:56.965  1017  3830 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:56.965  1017  3830 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:56.965  1017  3830 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:56.975  7669  7669 E Zygote  : MountEmulatedStorage()
08-26 15:42:56.975  7669  7669 I libpersona: KNOX_SDCARD checking this for 10011
08-26 15:42:56.975  7669  7669 E Zygote  : v2
08-26 15:42:56.975  7669  7669 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:56.985  7669  7669 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:42:56.985  1017  3830 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7669 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-26 15:42:56.985  7669  7669 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 15:42:56.985  1017  1456 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:56.985  1017  1456 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:56.985  1017  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 15:42:56.985  7669  7669 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-26 15:42:56.995  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:56.995  1017  1546 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:56.995  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:57.005  7669  7669 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:57.005  7669  7669 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:57.025  7669  7669 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-26 15:42:57.025  7669  7669 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-26 15:42:57.055  1458  1486 D TP/SmsProvider: query,matched:0, calling pid = 7401,
08-26 15:42:57.055  7669  7669 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
08-26 15:42:57.055  7669  7669 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
08-26 15:42:57.055  1458  1486 D TP/SmsProvider: match 0:Elapsed time : 1.424 ms
,08-26 15:42:57.065  1017  1544 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:57.065  7669  7669 I MultiDex: VM with version 2.1.0 has multidex support
08-26 15:42:57.065  7669  7669 I MultiDex: install
08-26 15:42:57.065  7669  7669 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-26 15:42:57.065  1017  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.065  1017  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:57.065  1458  1786 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 7401
,08-26 15:42:57.075  1017  1544 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:57.075  1017  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.075  1017  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:57.075  1017  1546 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:57.075  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:57.075  1017  1546 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.075  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:57.085  1017  1307 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:57.085  1017  1307 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.085  1017  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:57.095  1017  1488 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 15:42:57.095  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:42:57.095  7669  7669 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-26 15:42:57.095  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:57.095  1017  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:57.095  1458  2484 D TP/SmsProvider: query,matched:0, calling pid = 7401
,08-26 15:42:57.095  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:42:57.095  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:42:57.095  1458  2484 D TP/SmsProvider: match 0:Elapsed time : 1.657 ms
08-26 15:42:57.095  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,08-26 15:42:57.095  2214  2214 I Hs20UtilService: Starting #12
08-26 15:42:57.095  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:57.095  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.095  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 15:42:57.105  2214  2229 I Hs20UtilService: Message received 5011
,08-26 15:42:57.105  7401  7688 D LocationInitializer: Restart initialization of location
,08-26 15:42:57.105  7121  7121 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 15:42:57.105  7121  7121 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 15:42:57.105  7121  7121 D SecurityLogAgent: StateMachine : Current State = 1
08-26 15:42:57.105  7121  7121 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 15:42:57.105  1017  1547 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 15:42:57.105  1017  1547 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,08-26 15:42:57.115  1017  1547 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:57.115  1017  1547 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.115  1017  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:57.125  1017  1456 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 15:42:57.125  1017  1456 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:42:57.125  1017  1456 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:57.125  1017  1456 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:57.125  1017  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:42:57.125  1458  1661 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 7401
,08-26 15:42:57.125  1017  3827 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:57.125  2214  2214 I Hs20UtilService: Starting #13
,08-26 15:42:57.125  2214  2229 I Hs20UtilService: Message received 5011
,08-26 15:42:57.135  1017  3827 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:57.135  1017  3827 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.135  1017  3827 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 15:42:57.135  1017  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 15:42:57.135  1017  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 15:42:57.135  1017  1126 E WifiNative-wlan0: invaild command id : 215
,08-26 15:42:57.145  7121  7121 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 15:42:57.145  7121  7121 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 15:42:57.145  7121  7121 D SecurityLogAgent: StateMachine : Current State = 1
08-26 15:42:57.145  7121  7121 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 15:42:57.145  4726  4726 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 15:42:57.145  4726  4726 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 15:42:57.155  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 15:42:57.155  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 15:42:57.155  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-26 15:42:57.165  4726  4726 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 15:42:57.165  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-26 15:42:57.165  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:57.165  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:57.165  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:57.165  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:57.165  4726  4795 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 15:42:57.175  7669  7669 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@bfaa160: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-26 15:42:57.175  7669  7669 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-26 15:42:57.175  7669  7669 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-26 15:42:57.175  7690  7690 E Zygote  : MountEmulatedStorage()
,08-26 15:42:57.175  7690  7690 E Zygote  : v2
08-26 15:42:57.175  7690  7690 I libpersona: KNOX_SDCARD checking this for 10064
08-26 15:42:57.175  7690  7690 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:57.175  7690  7690 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-26 15:42:57.175  1017  1029 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7690 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-26 15:42:57.185  7690  7690 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:42:57.185  7690  7690 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:42:57.195  7669  7669 D WearableService: callingUid 10011, callindPid: 7669
,08-26 15:42:57.225  7690  7690 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:57.225  7690  7690 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:57.235  7669  7699 D NativeLibraryUtils: Install completed successfully. count=0 extracted=0
,08-26 15:42:57.265  7690  7690 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-26 15:42:57.285  1668  1678 I art     : Explicit concurrent mark sweep GC freed 12260(586KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 8MB/13MB, paused 996us total 44.667ms
,08-26 15:42:57.285  7690  7690 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 15:42:57.295  1639  2695 E MDM     : [154] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-26 15:42:57.295  7690  7690 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-26 15:42:57.325  7690  7690 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 15:42:57.325  7318  7318 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 15:42:57.325  1017  1503 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:57.325  1017  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.325  1017  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-26 15:42:57.335  1017  1227 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:57.335  1017  1227 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.335  1017  1227 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:57.345  1017  3829 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-26 15:42:57.345  1017  3829 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-26 15:42:57.345  1017  3829 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:57.345  1017  3829 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.345  1017  3829 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 15:42:57.345  1017  1456 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,08-26 15:42:57.345  1017  1456 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
08-26 15:42:57.345  1017  1456 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
,08-26 15:42:57.345  1017  1456 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
08-26 15:42:57.345  1668  5047 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-26 15:42:57.345  1017  1456 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:57.345  1017  1456 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.345  1017  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:57.355  1017  1456 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:57.355  1017  1456 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.355  1017  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:57.355  1668  1668 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-26 15:42:57.355  1017  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:57.355  1017  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.355  1017  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:57.365  1017  1546 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms,
08-26 15:42:57.365  1017  1546 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,08-26 15:42:57.365  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:57.365  1017  1546 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.365  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 15:42:57.365  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:57.365  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.365  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:57.375  1668  1668 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 15:42:57.375  1668  1668 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 15:42:57.375  1017  1227 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:57.375  1017  1227 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.375  1017  1227 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:57.375  7401  7401 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,08-26 15:42:57.385  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:42:57.385  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,08-26 15:42:57.385  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:57.385  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.385  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:57.385  1017  1545 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:57.385  1017  1545 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.385  1017  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:57.395  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:57.395  1017  1546 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.395  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:57.395  1017  3830 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:57.395  1017  3830 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.395  1017  3830 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:57.405  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:57.405  1017  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.405  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:57.405  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:57.405  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.405  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:57.405  1639  3153 E MDM     : [156] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-26 15:42:57.415  1017  3827 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:57.415  1017  3827 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.415  1017  3827 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:57.415  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:57.415  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.415  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:57.425  1017  1503 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,08-26 15:42:57.425  1017  1503 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:57.425  1017  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.425  1017  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:57.425  1017  1544 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:57.425  1017  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.425  1017  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:57.435  1017  1227 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 15:42:57.435  1017  1227 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,08-26 15:42:57.435  1017  1227 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:57.435  1017  1227 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.435  1017  1227 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:57.435  7401  7710 D LocationInitializer: Restart initialization of location,
,08-26 15:42:57.435  1017  1136 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:42:57.435  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:57.435  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
08-26 15:42:57.435  1017  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:57.435  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:57.605  7542  7542 I wpa_supplicant: nl80211: Received scan results (21 BSSes)
,08-26 15:42:57.615  7542  7542 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-26 15:42:57.615  7542  7542 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-26 15:42:57.615  7542  7542 I wpa_supplicant: Trying to associate with  'G700'
08-26 15:42:57.615  7542  7542 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-26 15:42:57.615  7542  7542 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
08-26 15:42:57.615  1017  7589 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-26 15:42:57.635  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-26 15:42:57.635  1017  1126 D SecContentProvider2: mCursor = null
,08-26 15:42:57.725  7542  7542 E wpa_supplicant: Cmd 35605 not handled
,08-26 15:42:57.725  7542  7542 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-26 15:42:57.725  7542  7542 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-26 15:42:57.725  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-26 15:42:57.725  7542  7542 I wpa_supplicant: Associated with F4.99.3E
08-26 15:42:57.725  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 15:42:57.725  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:42:57.725  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-26 15:42:57.725  7542  7542 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e,
08-26 15:42:57.725  7542  7542 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-26 15:42:57.725  7542  7542 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-26 15:42:57.725  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:42:57.725  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-26 15:42:57.725  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 15:42:57.725  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 15:42:57.725  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-26 15:42:57.725  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true,
08-26 15:42:57.725  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
08-26 15:42:57.735  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-26 15:42:57.735  1017  1131 E Tethering: No numeric data
,08-26 15:42:57.735  7542  7542 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-26 15:42:57.735  7542  7542 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-26 15:42:57.735  1017  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 15:42:57.735  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 15:42:57.735  1017  1131 D Tethering: clearTetheredNotification()
08-26 15:42:57.735  1177  1177 D HotspotTile: updateTetherState():false, false
08-26 15:42:57.735  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-26 15:42:57.735  7542  7542 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-26 15:42:57.735  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 15:42:57.735  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:57.745  7542  7542 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-26 15:42:57.745  1017  1126 D SecContentProvider2: mCursor = null
08-26 15:42:57.745  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 15:42:57.745  1017  1126 D SecContentProvider2: mCursor = null
08-26 15:42:57.745  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:42:57.745  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 15:42:57.755  7542  7542 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP],
08-26 15:42:57.755  7542  7542 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-26 15:42:57.755  1017  1123 V NetworkStats: performPollLocked() took 11ms
08-26 15:42:57.755  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:57.755  7542  7542 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=],
08-26 15:42:57.755  7542  7542 I wpa_supplicant: Blacklist: Clear (temp) 
08-26 15:42:57.755  7542  7542 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-26 15:42:57.755  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
,08-26 15:42:57.755  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:57.755  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:57.755  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-26 15:42:57.755  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,08-26 15:42:57.755  1017  1126 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-26 15:42:57.765  1017  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,08-26 15:42:57.765  1017  1128 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false,
08-26 15:42:57.765  1017  1126 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-26 15:42:57.765  1017  1128 E ConnectivityService: updateNetworkInfo()
08-26 15:42:57.765  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-26 15:42:57.765  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 15:42:57.775  1017  1488 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 15:42:57.775  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:42:57.775  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:57.775  1017  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:57.775  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:42:57.775  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 15:42:57.775  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:57.775  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 15:42:57.775  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 15:42:57.775  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:57.775  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:57.775  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:57.775  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:57.775  2214  2214 I Hs20UtilService: Starting #14
,08-26 15:42:57.785  2214  2229 I Hs20UtilService: Message received 5007
,08-26 15:42:57.785   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:42:57.785  4726  4726 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 15:42:57.785  4726  4726 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 15:42:57.785  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 15:42:57.785  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 15:42:57.785  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 15:42:57.785  4726  4726 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 15:42:57.785  4726  4795 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 15:42:57.795   278   999 D CommandListener: Setting iface cfg
,08-26 15:42:57.795  1017  1126 E WifiStateMachine: Start Dhcp Watchdog 2
,08-26 15:42:57.795  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 15:42:57.795  1017  1126 D SecContentProvider2: mCursor = null
,08-26 15:42:57.805  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 15:42:57.805  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 15:42:57.805  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 15:42:57.805  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:57.805  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:57.805  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:57.805  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:57.815  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 15:42:57.815  1017  1126 D SecContentProvider2: mCursor = null
,08-26 15:42:57.815  1017  1126 E WifiNative-wlan0: do suspend false
,08-26 15:42:57.825  1017  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-26 15:42:57.825  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 15:42:57.985  1017  1029 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 15:42:57.985  1017  1029 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 15:42:57.985  1017  1029 D SecContentProvider2: mCursor = null
,08-26 15:42:57.995  1017  1029 D WifiService: setWifiEnabled: false pid=6945, uid=10170
,08-26 15:42:57.995  1017  1029 D SettingsProvider: name = wifi_on
,08-26 15:42:58.005  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 15:42:58.015  1017  1126 E WifiNative-wlan0: do suspend true,
,08-26 15:42:58.035  1017  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-26 15:42:58.035   278   999 D CommandListener: Clearing all IP addresses on wlan0
08-26 15:42:58.035  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 15:42:58.045  1017  1128 E ConnectivityService: updateNetworkInfo()
08-26 15:42:58.045  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 15:42:58.045  1017  1128 E ConnectivityService: updateNetworkInfo()
08-26 15:42:58.045  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-26 15:42:58.045   278   999 E Netd    : no such netId 503
08-26 15:42:58.045  7717  7717 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-26 15:42:58.045  7717  7717 I dhcpcd  : version 5.5.6 starting
,08-26 15:42:58.055  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-26 15:42:58.055  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 15:42:58.055  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:58.055  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 15:42:58.055  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:58.055  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:58.055  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:58.055  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:58.055  7717  7717 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-26 15:42:58.065  1017  1136 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-26 15:42:58.065  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
08-26 15:42:58.075  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 15:42:58.075  1017  1128 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
08-26 15:42:58.075  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:58.075  1017  1128 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-26 15:42:58.075  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 15:42:58.075  1017  1128 V NetworkStats: updateIfacesLocked()
08-26 15:42:58.075  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:58.075  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
08-26 15:42:58.075  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:58.075  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:58.075  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:58.075  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:58.075  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:58.075  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:42:58.075  1017  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:58.075  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 15:42:58.075  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 15:42:58.075  2214  2214 I Hs20UtilService: Starting #15
,08-26 15:42:58.075  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 15:42:58.075  1017  1151 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 15:42:58.075  1017  1017 D RttService: SCAN_AVAILABLE : 1
08-26 15:42:58.075  1017  1152 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:58.075  2214  2229 I Hs20UtilService: Message received 5007
08-26 15:42:58.075  1017  1126 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-26 15:42:58.075  1017  1125 D WifiP2pService: InactiveState{ what=131204 }
08-26 15:42:58.085  1017  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
08-26 15:42:58.085  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-26 15:42:58.085  1017  1128 V NetworkStats: performPollLocked() took 14ms
,08-26 15:42:58.085  4726  4726 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 15:42:58.085  4726  4726 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 15:42:58.095  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 15:42:58.095  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:58.095  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 15:42:58.095  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 15:42:58.095  4726  4726 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 15:42:58.095  4726  4795 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 15:42:58.095  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 15:42:58.095  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-26 15:42:58.095  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 15:42:58.095  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 15:42:58.105  1017  1128 D ConnectivityService: nai.networkMonitor.doQuit(),
08-26 15:42:58.105  1017  1128 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,08-26 15:42:58.105  1017  1128 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-26 15:42:58.105  1017  1128 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-26 15:42:58.105  1017  1128 E ConnectivityService: updateNetworkInfo()
,08-26 15:42:58.105  1017  1128 E ConnectivityService: updateNetworkInfo()
08-26 15:42:58.105  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-26 15:42:58.105  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:58.105  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:58.105  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-26 15:42:58.115  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-26 15:42:58.115  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 15:42:58.115  1017  1047 D WifiDisplayController: disconnect
08-26 15:42:58.115  1017  1047 D WifiDisplayController: updateConnection
08-26 15:42:58.115  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 15:42:58.115  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 15:42:58.125  4726  4726 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 15:42:58.125  4726  4726 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 15:42:58.125  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 15:42:58.135  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 15:42:58.135  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-26 15:42:58.135  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-26 15:42:58.135  4726  4726 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 15:42:58.135  4726  4795 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-26 15:42:58.135  1017  1125 D WifiP2pService: P2pDisablingState
08-26 15:42:58.135  1017  1227 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 15:42:58.135  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 15:42:58.135  1017  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
08-26 15:42:58.135  1017  1125 D WifiP2pService: p2p socket connection lost
08-26 15:42:58.135  1017  1126 E WifiNative-wlan0: do suspend true
08-26 15:42:58.135  1017  1125 D WifiP2pService: P2pDisabledState
,08-26 15:42:58.135  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-26 15:42:58.135  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
,08-26 15:42:58.135  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 15:42:58.135  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 15:42:58.145  7690  7690 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 15:42:58.145  7690  7690 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-26 15:42:58.145  7690  7690 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 15:42:58.155  7318  7318 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 15:42:58.155  7717  7717 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-26 15:42:58.155  7717  7717 E dhcpcd  : wlan0: sendmsg: Network is unreachable
,08-26 15:42:58.155  4726  4726 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 15:42:58.155  4726  4726 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 15:42:58.155  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 15:42:58.155  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 15:42:58.155  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 15:42:58.155  4726  4726 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 15:42:58.155  4726  4795 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 15:42:58.165  7717  7717 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,08-26 15:42:58.165  1017  1125 D WifiP2pService: P2pDisabledState{ what=143375 }
08-26 15:42:58.165  7690  7690 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-26 15:42:58.165  1017  1125 D WifiP2pService: DefaultState{ what=143375 }
08-26 15:42:58.165  7717  7717 I dhcpcd  : bssid match
,08-26 15:42:58.165  7717  7717 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
08-26 15:42:58.165  7690  7690 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-26 15:42:58.165  7690  7690 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 15:42:58.175  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 15:42:58.175  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:58.175   278   999 D CommandListener: Clearing all IP addresses on wlan0
08-26 15:42:58.175  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 15:42:58.175  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:58.175  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:58.175  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:58.175  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:58.185  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 15:42:58.185  7542  7542 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-26 15:42:58.195  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 15:42:58.195  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:58.195  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 15:42:58.195  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 15:42:58.195  1017  1126 D SecContentProvider2: mCursor = null
,08-26 15:42:58.195  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:58.195  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:58.195  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:58.195  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:58.205  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 15:42:58.205  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:58.205  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-26 15:42:58.205  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:58.205  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:58.205  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:58.205  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:58.205  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:58.205  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-26 15:42:58.205  1177  1666 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 15:42:58.205  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:42:58.205  4726  4726 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:42:58.215  1177  1177 D HotspotTile: onReceive : 0, 0
,08-26 15:42:58.215  7318  7318 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 15:42:58.215  7717  7717 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,08-26 15:42:58.215  6945  6945 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-26 15:42:58.215  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:58.215  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:58.215  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:58.215  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false,
08-26 15:42:58.215  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:58.215  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:58.215  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:58.215  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:42:58.215  6945  6945 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-26 15:42:58.215  6945  6945 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:42:58.215  6945  6945 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:58.225  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:58.225  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:58.225  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:58.225  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:58.225  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:58.225  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:58.225  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:58.225  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:42:58.225  6945  6945 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
,08-26 15:42:58.225  6945  6945 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:42:58.225  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 15:42:58.225  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:42:58.225  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:58.225  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:42:58.235  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:42:58.235  2214  2214 I Hs20UtilService: Starting #16
08-26 15:42:58.235  4726  4726 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 15:42:58.235  4726  4726 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 15:42:58.235  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 15:42:58.235  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 15:42:58.235  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 15:42:58.235  4726  4726 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 15:42:58.235  2214  2229 I Hs20UtilService: Message received 5007
08-26 15:42:58.235  4726  4795 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 15:42:58.245  1017  3827 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 15:42:58.245  1017  3827 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:42:58.245  1017  3827 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:58.245  1017  3827 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:58.245  1017  3827 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:42:58.255  2214  2214 I Hs20UtilService: Starting #17
08-26 15:42:58.255  2214  2229 I Hs20UtilService: Message received 5011
,08-26 15:42:58.255  7121  7121 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 15:42:58.255  7121  7121 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 15:42:58.255  7121  7121 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 15:42:58.255  7121  7121 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 15:42:58.335  7717  7717 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,08-26 15:42:58.355  7542  7542 I wpa_supplicant: Blacklist: Clear (all) ,
,08-26 15:42:58.425  7542  7542 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
,08-26 15:42:58.425  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 15:42:58.425  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 15:42:58.425  1017  1044 D Tethering: interfaceStatusChanged p2p0, false,
,08-26 15:42:58.445  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:42:58.445  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-26 15:42:58.445  1017  1131 D Tethering: InitialState.processMessage what=4
08-26 15:42:58.445  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 15:42:58.445  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 15:42:58.455  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 15:42:58.445  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-26 15:42:58.455  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 15:42:58.445  7542  7542 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-26 15:42:58.455  1177  1177 D HotspotTile: updateTetherState():false, false
08-26 15:42:58.445  1017  1131 E Tethering: No numeric data
08-26 15:42:58.455  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-26 15:42:58.445  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 15:42:58.455  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 15:42:58.445  1017  1131 D Tethering: clearTetheredNotification()
08-26 15:42:58.455  7542  7542 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-26 15:42:58.455  7542  7542 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-26 15:42:58.455  7542  7542 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-26 15:42:58.455  7542  7542 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-26 15:42:58.455  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:58.455  1017  1123 V NetworkStats: performPollLocked() took 3ms
08-26 15:42:58.455  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:42:58.455  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-26 15:42:58.455  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:42:58.455  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 15:42:58.455  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:58.455  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:58.455  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:58.725  7542  7542 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 15:42:58.725  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 15:42:58.725  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-26 15:42:58.725  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 15:42:58.785   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:42:58.845  1017  1095 V AlarmManager: waitForAlarm result :4
,08-26 15:42:58.855  7542  7542 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-26 15:42:58.855  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:42:58.855  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-26 15:42:58.855  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 15:42:58.865  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:58.865  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:42:58.865  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-26 15:42:58.965  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-26 15:42:58.965  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 15:42:58.975  7278  7278 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:42:58.975  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 15:42:58.975  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:58.975  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 15:42:58.975  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:58.975  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:58.975  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:58.975  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:58.975  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:58.975  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-26 15:42:58.975  1177  1666 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 15:42:58.975  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:42:58.975  1177  1177 D HotspotTile: onReceive : 1, 0
,08-26 15:42:58.975  4726  4726 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:42:58.985  1639  2133 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:42:58.985  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:58.985  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:58.985  1017  1489 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 15:42:58.985  1017  1489 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:42:58.985  1017  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:58.995  1017  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:42:58.995  1017  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:42:58.995  7121  7121 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 15:42:58.995  7121  7121 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-26 15:42:58.995  7121  7121 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 15:42:58.995  2214  2214 I Hs20UtilService: Starting #18
,08-26 15:42:58.995  7121  7121 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 15:42:59.005  2214  2229 I Hs20UtilService: Message received 5011
,08-26 15:42:59.605  5971  5971 D FactoryTest: Not factory mode
,08-26 15:42:59.605  5971  5971 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-26 15:42:59.615   278   993 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-26 15:42:59.615  5971  5971 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-26 15:42:59.615  5971  5971 D MTPRx   : still no open session command from host, so toast
,08-26 15:42:59.615  1017  1044 D Tethering: interfaceRemoved wlan0
,08-26 15:42:59.615  1017  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-26 15:42:59.615  5971  5971 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-26 15:42:59.615  5971  5971 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-26 15:42:59.625  5971  5971 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:118800
,08-26 15:42:59.625  1017  1544 E PersonaManagerService: inState():  stateMachine is null !!
,08-26 15:42:59.625  1017  1544 I PersonaManagerService: PersonaId don't exist
,08-26 15:42:59.625  1017  1544 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-26 15:42:59.625  1017  1544 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,08-26 15:42:59.625  1017  1544 W ActivityManager: userId = 0, bbcId = -10000,
08-26 15:42:59.625  1017  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:42:59.625  1017  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-26 15:42:59.645  1017  1544 W ActivityManager: mDVFSHelper.acquire()
,08-26 15:42:59.665  1017  1544 D PersonaManager: isKioskContainerExistOnDevice
,08-26 15:42:59.665  1017  1544 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 15:42:59.665  1017  1544 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-26 15:42:59.665  1017  1544 D InputDispatcher: Focused application set to: xxxx
,08-26 15:42:59.665  1017  1544 D InputDispatcher: Focus left window: 6945
,08-26 15:42:59.665  5971  5971 E MTPRx   : started activity for popup
,08-26 15:42:59.675  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-26 15:42:59.675  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 15:42:59.705  5971  5971 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-26 15:42:59.705  5971  5971 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-26 15:42:59.705  5971  5971 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-26 15:42:59.705  5971  5971 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 15:42:59.705  5971  5971 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 15:42:59.705  5971  5971 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 15:42:59.725  5971  5971 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-26 15:42:59.735  1017  3827 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-26 15:42:59.735  1017  3827 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-26 15:42:59.735  1017  3827 D InputDispatcher: Focused application set to: xxxx
,08-26 15:42:59.735  1017  3827 D InputDispatcher: Focus entered window: 6945
,08-26 15:42:59.735  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-26 15:42:59.735  1017  1488 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-26 15:42:59.735  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 15:42:59.745  1017  1488 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@d9438c9 attribute=null, token = android.os.BinderProxy@19048e66
,08-26 15:42:59.755  1017  1044 D Tethering: interfaceRemoved p2p0
08-26 15:42:59.755  1017  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-26 15:42:59.775   288   288 E SMD     : DCD OFF
,08-26 15:42:59.775  5971  5971 D SettingsReceiverActivity: dev.kiessupport is : TRUE,
,08-26 15:42:59.785  5971  5971 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-26 15:42:59.785  5971  5971 D PhoneWindow: *FMB* installDecor flags : 8388610
08-26 15:42:59.785   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-26 15:42:59.805  6945  6945 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-26 15:42:59.805  6945  6945 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
08-26 15:42:59.805  6945  6945 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-26 15:42:59.805  6945  6945 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-26 15:42:59.805  1017  1029 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false,
08-26 15:42:59.805  1017  1029 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-26 15:42:59.805  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
08-26 15:42:59.805  1017  1029 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-26 15:42:59.805  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-26 15:42:59.815  6945  6945 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 15:42:59.825  6945  6945 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-26 15:42:59.825  6945  6945 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3f9ff43d Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@1be9d563, 16908290=android.view.AbsSavedState$1@1be9d563}, android:focusedViewId=100}]}]
,08-26 15:42:59.825  6945  6945 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-26 15:42:59.825  6945  6945 V ActivityThread: updateVisibility : ActivityRecord{166a52d7 token=android.os.BinderProxy@253cf471 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-26 15:42:59.825  6945  6945 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-26 15:42:59.825  6945  6945 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-26 15:42:59.825  6945  6945 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@253cf471 time:119008
,08-26 15:42:59.835  1017  3830 D PersonaManager: isKioskContainerExistOnDevice
,08-26 15:42:59.995  1017  1095 V AlarmManager: waitForAlarm result :8
,08-26 15:43:00.505  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-26 15:43:00.995  6945  7152 D BluetoothAdapter: enable()
,08-26 15:43:01.005  1017  1227 W ActivityManager: Permission Denial: getCurrentUser() from pid=6945, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-26 15:43:01.005  1017  1227 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-26 15:43:01.005  1017  1227 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6945, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-26 15:43:01.005  1017  1227 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 15:43:01.005  1017  1227 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-26 15:43:01.005  1017  1227 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-26 15:43:01.005  1017  1227 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-26 15:43:01.005  1017  1227 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 15:43:01.005  1017  1227 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 15:43:01.015  1017  1227 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 15:43:01.015  1017  1227 D SettingsProvider: name = bluetooth_on,
,08-26 15:43:01.015  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 15:43:01.015  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 15:43:01.015  1017  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-26 15:43:01.025  3209  3285 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-26 15:43:01.025  3209  3285 D BluetoothAdapterProperties: Setting state to 11
08-26 15:43:01.025  3209  3285 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 15:43:01.025  3209  3285 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 15:43:01.025  3209  3285 D BluetoothAdapterService: updateAdapterState state is 11
,08-26 15:43:01.025  3209  3285 D BluetoothAdapterService: Autoconnection is available 
08-26 15:43:01.025  3209  3285 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-26 15:43:01.025  3209  3285 D BtConfig.SecureMode: isSecureModeOn:false
08-26 15:43:01.025  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-26 15:43:01.025  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-26 15:43:01.025  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 15:43:01.025  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-26 15:43:01.025  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 15:43:01.025  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-26 15:43:01.025  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 15:43:01.025  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-26 15:43:01.025  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 15:43:01.025  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-26 15:43:01.025  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 15:43:01.025  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-26 15:43:01.025  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:43:01.025  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-26 15:43:01.025  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 15:43:01.025  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-26 15:43:01.025  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:43:01.025  3209  3285 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:43:01.025  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:43:01.025  3209  3285 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:43:01.025  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 15:43:01.025  3209  3285 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-26 15:43:01.025  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 15:43:01.025  3209  3285 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-26 15:43:01.025  3209  3285 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-26 15:43:01.025  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 15:43:01.025  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 15:43:01.025  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-26 15:43:01.025  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:01.025  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,08-26 15:43:01.035  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 15:43:01.035  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:01.035  1177  1177 D BluetoothTile:  getBluetoothState : 11
08-26 15:43:01.035  4726  4726 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:01.035  1962  1962 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 15:43:01.035  1017  1029 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 15:43:01.035  1017  1547 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 15:43:01.045  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 15:43:01.045  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:01.045  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-26 15:43:01.045  1017  1136 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:01.045  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.045  1177  1666 D BluetoothTile:  handleUpdatestate:false name:null
08-26 15:43:01.045  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:01.045  1177  1666 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 15:43:01.045  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:01.045  1017  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.045  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.045  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,08-26 15:43:01.045  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 15:43:01.045  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 15:43:01.045  3209  3209 D HeadsetService: Received start request. Starting profile...
08-26 15:43:01.045  3209  3209 D HeadsetService: start()
08-26 15:43:01.045  3209  3209 D HeadsetStateMachine: make
,08-26 15:43:01.055  3209  3209 E HeadsetStateMachine: # of Max HF connection is 2
,08-26 15:43:01.055  1668  1668 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 15:43:01.055  1017  1489 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-26 15:43:01.055  1017  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.065  1017  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:01.065  1017  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.065  1017  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-26 15:43:01.065  1017  1456 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:43:01.065  1017  1456 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.065  1017  1456 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:01.065  1017  1456 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.065  1017  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.065  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-26 15:43:01.065  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 15:43:01.065  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 15:43:01.065  1017  1546 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:43:01.065  1017  1546 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.075  4726  4726 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 15:43:01.075  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:01.075  1017  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.075  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.075  1017  1503 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-26 15:43:01.075  1017  1503 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.075  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,08-26 15:43:01.075  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 15:43:01.075  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 15:43:01.075  1017  1503 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:01.075  1017  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.075  1017  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 15:43:01.075  3209  3209 I bluedroid: get_profile_interface handsfree
,08-26 15:43:01.085  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:01.085  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-26 15:43:01.085  1017  1136 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:43:01.085  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.085  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:01.085  1017  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.085  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.095  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-26 15:43:01.095  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 15:43:01.095  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 15:43:01.095  1017  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:01.095  1017  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.095  1017  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:01.095  1017  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.095  1017  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.095  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,08-26 15:43:01.095  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:43:01.095  3209  3209 E DualScoManager: Dual Sco Manager already instantiated
08-26 15:43:01.095  3209  3209 I DualScoManager: Set HeadsetServiceHelper
08-26 15:43:01.095  3209  3209 D BluetoothAtMessage: createCMTIContentObservers
,08-26 15:43:01.095  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-26 15:43:01.095  1017  1456 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:01.095  1017  3827 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-26 15:43:01.095  1017  3827 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:43:01.095  1017  3827 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:43:01.095  1017  3827 D SettingsProvider: selectionArgs: false
08-26 15:43:01.095  1017  3827 D SettingsProvider: selectionArgs: 1002
08-26 15:43:01.095  1017  3827 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:43:01.095  1017  3827 D SettingsProvider: ret = -1
,08-26 15:43:01.105  3209  7750 D HeadsetStateMachine: Enter Disconnected: -2
08-26 15:43:01.105  1017  1456 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.105  1017  1456 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:01.105  1017  1456 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.105  1017  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.105  3209  3209 D HeadsetService: mStartError = false
,08-26 15:43:01.105  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
08-26 15:43:01.105  3209  3209 D HeadsetStateMachine: Try to query the phonestate on bind
,08-26 15:43:01.105  1441  1457 I Telecom : BluetoothPhoneService: queryPhoneState
,08-26 15:43:01.105  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-26 15:43:01.105  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-26 15:43:01.105  3209  3285 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 15:43:01.105  1441  1441 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-26 15:43:01.105  1441  1441 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-26 15:43:01.115  1441  1457 I Telecom : BluetoothPhoneService: Result of Message : true
,08-26 15:43:01.115  3209  3209 D A2dpService: Received start request. Starting profile...
,08-26 15:43:01.115  3209  3209 D A2dpService: start()
08-26 15:43:01.115  3209  3209 I bluedroid: get_profile_interface avrcp
,08-26 15:43:01.115  1017  1307 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:43:01.115  1017  1307 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.115  1017  1307 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:01.115  1017  1307 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.115  1017  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.125  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 15:43:01.125  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 15:43:01.125  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:43:01.125  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:43:01.125  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:43:01.125  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:43:01.125  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 15:43:01.125  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 15:43:01.125  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,08-26 15:43:01.125  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-26 15:43:01.125  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 15:43:01.125  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 15:43:01.125  3209  3285 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-26 15:43:01.125  3209  7750 D HeadsetStateMachine: Clear mHeadsetBrsf
08-26 15:43:01.125  3209  7750 D HeadsetStateMachine: map size, before remove : 0
08-26 15:43:01.125  3209  7750 D HeadsetStateMachine: map size, after remove: 0
,08-26 15:43:01.125  3209  3209 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 15:43:01.125  3209  3209 D Avrcp   : Initialize Media Controller
08-26 15:43:01.125  3209  3209 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-26 15:43:01.125  3209  3209 E Avrcp   : getActiveSessions
,08-26 15:43:01.125  3209  3209 D Avrcp   : pick active media Controller
08-26 15:43:01.125  3209  3209 D Avrcp   : Get the active Media Controller 
,08-26 15:43:01.135  3209  3209 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-26 15:43:01.135  3209  7751 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-26 15:43:01.135  3209  3209 D A2dpStateMachine: make
,08-26 15:43:01.145  3209  3209 I bluedroid: get_profile_interface a2dp
,08-26 15:43:01.145  3209  7753 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-26 15:43:01.145  3209  3209 E bt-btif : warning : media task started media_task_refcnt 1 
,08-26 15:43:01.145  3209  3209 D A2dpService: mStartError = false
,08-26 15:43:01.145  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
08-26 15:43:01.145  3209  3209 D HeadsetStateMachine: Proxy object connected
08-26 15:43:01.145  3209  3209 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-26 15:43:01.145  3209  7750 D HeadsetStateMachine: Disconnected process message: 11
,08-26 15:43:01.145  3209  3209 D HidService: Received start request. Starting profile...
08-26 15:43:01.145  3209  3209 D HidService: start()
08-26 15:43:01.145  3209  3209 I bluedroid: get_profile_interface hidhost
08-26 15:43:01.145  3209  3209 D HidService: setHidService(): set to: null
08-26 15:43:01.145  3209  3209 D HidService: mStartError = false
08-26 15:43:01.145  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
08-26 15:43:01.145  3209  7752 D A2dpStateMachine: Enter Disconnected: -2
08-26 15:43:01.145  3209  3209 D HealthService: Received start request. Starting profile...
08-26 15:43:01.145  3209  3209 D HealthService: start()
,08-26 15:43:01.145  3209  7751 D BluetoothMediaBrowser: no now playing list
08-26 15:43:01.145  3209  7751 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-26 15:43:01.145  3209  3209 I bluedroid: get_profile_interface health
,08-26 15:43:01.145  3209  3209 D HealthService: mStartError = false
08-26 15:43:01.145  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
08-26 15:43:01.145  3209  3209 D HeadsetPhoneState: sendDeviceDataStateChanged
08-26 15:43:01.145  3209  3209 D HeadsetPhoneState: Signal level : previous=0 curr=4
,08-26 15:43:01.145  3209  7750 D HeadsetStateMachine: Disconnected process message: 18
,08-26 15:43:01.145  3209  3209 D PanService: Received start request. Starting profile...
08-26 15:43:01.145  3209  3209 D PanService: start()
08-26 15:43:01.145  3209  3209 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 15:43:01.145  3209  3209 I bluedroid: get_profile_interface pan
08-26 15:43:01.145  3209  3209 D PanService: mStartError = false
08-26 15:43:01.145  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
,08-26 15:43:01.145  3209  3209 D BluetoothMapService: Received start request. Starting profile...
08-26 15:43:01.145  3209  3209 D BluetoothMapService: start()
,08-26 15:43:01.155  3209  3209 D BluetoothMapService: mStartError = false
,08-26 15:43:01.155  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
08-26 15:43:01.155  3209  3209 E BluetoothAdapterService(441650423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-26 15:43:01.155  3209  3209 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:43:01.155  3209  7750 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:43:01.155  3209  3209 D SapService: Received start request. Starting profile...
08-26 15:43:01.155  3209  3209 D SapService: start()
08-26 15:43:01.155  3209  3209 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-26 15:43:01.155  3209  3209 I bluedroid: get_profile_interface sap
08-26 15:43:01.155  3209  3209 D SapService: mStartError = false
08-26 15:43:01.155  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
08-26 15:43:01.155  3209  3209 E BluetoothAdapterService(441650423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-26 15:43:01.155  3209  3209 E BluetoothAdapterService(441650423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-26 15:43:01.155  3209  3209 E BluetoothAdapterService(441650423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-26 15:43:01.155  3209  3209 E BluetoothAdapterService(441650423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-26 15:43:01.165  3209  7750 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-26 15:43:01.165  3209  7750 D HeadsetStateMachine: Disconnected process message: 11
,08-26 15:43:01.175  3209  3209 E BluetoothAdapterService(441650423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-26 15:43:01.175  3209  3209 E BluetoothAdapterService(441650423): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-26 15:43:01.175  3209  3285 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-26 15:43:01.175  3209  3285 I bluedroid: enable
,08-26 15:43:01.185  3209  3288 E bt-btif : Calling BTA_HhEnable
,08-26 15:43:01.185  3209  3288 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-26 15:43:01.185  3209  3288 E bt-btif :                : sec: 0xb6, service name [ion && *section, chan_id 1
08-26 15:43:01.185  3209  3288 E bt-btif : BTM_SEC_REG[11et_adapter_p, servi service_] (up to 21 ch
08-26 15:43:01.185  3209  3288 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
,08-26 15:43:01.185  3209  3288 E BluetoothServiceJni: populateRssiValuesNative
08-26 15:43:01.185  3209  3288 I bluedroid: getModelRssiValues
08-26 15:43:01.185  3209  3288 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-26 15:43:01.185  3209  3288 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 15:43:01.185  3209  3288 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-26 15:43:01.185  1017  1017 D SettingsProvider: name = bluetooth_name
,08-26 15:43:01.185  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-26 15:43:01.195  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:01.195  3209  3288 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-26 15:43:01.195  3209  3288 D BluetoothAdapterProperties: Scan Mode:20
08-26 15:43:01.195  3209  3288 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 15:43:01.195  3209  3288 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
,08-26 15:43:01.195  3209  3288 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-26 15:43:01.195  3209  3288 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-26 15:43:01.195  3209  3288 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-26 15:43:01.195  3209  3288 E bt-btif : JVenable fails
,08-26 15:43:01.195  3209  3288 D bte_conf: Device ID record 1 : primary
,08-26 15:43:01.195  3209  3288 D bte_conf:   vendorId            = 0075
08-26 15:43:01.195  3209  3288 D bte_conf:   vendorIdSource      = 0001
08-26 15:43:01.195  3209  3288 D bte_conf:   product             = 0100
,08-26 15:43:01.195  3209  3288 D bte_conf:   version             = 0200
08-26 15:43:01.195  3209  3288 D bte_conf:   clientExecutableURL = 
08-26 15:43:01.195  3209  3288 D bte_conf:   serviceDescription  = 
08-26 15:43:01.195  3209  3288 D bte_conf:   documentationURL    = 
08-26 15:43:01.195  3209  3288 D bte_conf: bte_load_did_conf no section named DID2.
08-26 15:43:01.195  3209  3288 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-26 15:43:01.195  3209  3288 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 15:43:01.195  3209  3285 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 15:43:01.195  3209  3285 D BluetoothAdapterProperties: ScanMode =  20
08-26 15:43:01.195  3209  3285 D BluetoothAdapterProperties: State =  11
08-26 15:43:01.195  1017  3829 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-26 15:43:01.195  3209  3285 D BluetoothAdapterProperties: Setting state to 12
08-26 15:43:01.195  3209  3285 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 15:43:01.205  3209  3288 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 15:43:01.205  3209  3288 D BluetoothAdapterProperties: Scan Mode:21
08-26 15:43:01.205  3209  3288 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 15:43:01.205  1017  1030 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-26 15:43:01.205  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 15:43:01.205  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:43:01.205  1017  1030 D SettingsProvider: selectionArgs: false
,08-26 15:43:01.205  1017  1030 D SettingsProvider: selectionArgs: 1002
08-26 15:43:01.205  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 15:43:01.205  1017  1030 D SettingsProvider: ret = -1
,08-26 15:43:01.205  3209  3285 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-26 15:43:01.205  3209  3285 D BluetoothAdapterService: updateAdapterState state is 12
,08-26 15:43:01.205  1017  1546 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:43:01.215  1017  1546 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.215  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:01.215  1017  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:43:01.215  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.215  7233  7242 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 15:43:01.215  7233  7242 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:43:01.215  3209  3285 D BluetoothAdapterService: Autoconnection is available 
,08-26 15:43:01.215  3209  3285 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-26 15:43:01.215  3209  3285 D BluetoothAdapterService: starting service from this receiver
08-26 15:43:01.215  1017  1136 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:01.215  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.225  1177  1189 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:01.225  1177  1189 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:43:01.225  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:01.225  1017  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.225  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.225  3209  3285 I BluetoothAdapterState: Entering On State from state = 11
,08-26 15:43:01.225  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:01.225  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:01.225  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:01.225  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:43:01.225  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:01.225  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:01.225  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:01.225  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:01.225  1458  1786 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 15:43:01.225  1458  1786 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on,
08-26 15:43:01.225  3209  3209 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-26 15:43:01.225  1639  1862 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:01.225  1639  1862 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on,
08-26 15:43:01.225  1017  1046 D BluetoothPan: Binding service...
08-26 15:43:01.225  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 15:43:01.225  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.225  6945  6945 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:01.235  1441  1481 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:01.235  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 15:43:01.235  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 15:43:01.235  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:01.235  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.235  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.235  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:01.235  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:01.235  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:01.235  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:43:01.235  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:01.235  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:01.235  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:01.235  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:01.235  3209  3209 I BluetoothPbapService: Handler(): got msg=1
,08-26 15:43:01.235  1441  1481 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 15:43:01.235  1017  1307 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 15:43:01.245  1441  1457 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:01.245  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 15:43:01.245  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 15:43:01.245  1017  1046 W ActivityManager: userId = 0, bbcId = -10000,
08-26 15:43:01.245  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.245  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.245  6945  6945 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:01.245  1441  1457 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 15:43:01.245  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 15:43:01.245  3209  3220 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 15:43:01.245  3209  7758 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-26 15:43:01.255  3209  3220 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:01.255  1017  1046 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 15:43:01.255  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.255  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:01.255  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.255  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.255  4726  4736 D Bluetoothsap: onBluetoothStateChange: up=true
08-26 15:43:01.255  4726  4736 D Bluetoothsap: Binding service...
,08-26 15:43:01.255  3209  3209 D BluetoothA2dp: Proxy object connected
08-26 15:43:01.255  3209  3209 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-26 15:43:01.255  3209  7758 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 15:43:01.255  3209  7758 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 15:43:01.255  4726  4736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-26 15:43:01.255  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-26 15:43:01.255  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.255  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:01.255  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.255  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.255  4726  4736 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-26 15:43:01.265  1017  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-26 15:43:01.265  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 15:43:01.265  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-26 15:43:01.265  1017  1046 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 15:43:01.265  4726  4734 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 15:43:01.265  4726  4726 D Bluetoothsap: BluetoothSAP Proxy object connected
08-26 15:43:01.265  4726  4726 D SapProfile: Bluetooth service connected
08-26 15:43:01.265  4726  4726 D Bluetoothsap: getConnectedDevices()
,08-26 15:43:01.265  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-26 15:43:01.265  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.265  3209  7758 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-26 15:43:01.265  3209  7758 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 15:43:01.265  3209  7758 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 15:43:01.265  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:01.265  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.265  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-26 15:43:01.265  3209  7758 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3160ae20
,08-26 15:43:01.265  3209  7758 D BluetoothSocket: channel: 19
08-26 15:43:01.265  3209  7758 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-26 15:43:01.265  6945  6955 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:01.265  6945  6955 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:43:01.265  4726  4726 D BluetoothPbap: Proxy object connected
,08-26 15:43:01.265  4726  4726 D PbapServerProfile: Bluetooth service connected
08-26 15:43:01.265  4726  4736 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:01.275  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 15:43:01.275  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 15:43:01.275  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:01.275  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.275  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.275  4726  4736 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 15:43:01.275  4726  4736 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 15:43:01.275  4726  4726 D HeadsetProfile: Bluetooth service connected
,08-26 15:43:01.275  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-26 15:43:01.275  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.275  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:01.275  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.275  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth,
,08-26 15:43:01.275  4726  4736 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 15:43:01.275  4726  4736 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 15:43:01.275  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 15:43:01.275  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-26 15:43:01.275  1017  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-26 15:43:01.275  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-26 15:43:01.275  1017  1017 D BluetoothA2dp: Proxy object connected
,08-26 15:43:01.275  1668  1678 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 15:43:01.275  1668  1678 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:43:01.285  4726  7760 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 15:43:01.285  4726  4726 D BluetoothInputDevice: Proxy object connected
08-26 15:43:01.285  4726  4726 D HidProfile: Bluetooth service connected
,08-26 15:43:01.285  4726  7760 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:01.285  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 15:43:01.285  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.285  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:01.285  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.285  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.285  4726  4734 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 15:43:01.285  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-26 15:43:01.285  4726  4726 D BluetoothA2dp: Proxy object connected
08-26 15:43:01.285  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-26 15:43:01.285  4726  4726 D A2dpProfile: Bluetooth service connected
,08-26 15:43:01.285  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:01.285  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.285  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.285  1441  1457 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:01.285  1441  1457 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:43:01.285  4726  4736 D BluetoothPan: Binding service...
,08-26 15:43:01.285  4726  4726 D BluetoothMap: Proxy object connected
,08-26 15:43:01.285  4726  4726 D MapProfile: Bluetooth service connected
08-26 15:43:01.285  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 15:43:01.285  4726  4726 D BluetoothMap: getConnectedDevices()
08-26 15:43:01.285  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.285  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:01.295  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.295  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.295  4726  4726 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 15:43:01.295  1441  1481 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-26 15:43:01.295  4726  4726 D PanProfile: Bluetooth service connected
,08-26 15:43:01.295  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 15:43:01.295  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 15:43:01.295  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:01.295  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.295  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.295  1441  1481 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 15:43:01.295  3209  3220 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:01.295  3209  3220 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:43:01.295  1448  1466 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 15:43:01.295  1448  1466 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:43:01.295  1458  1482 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:01.295  1017  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 15:43:01.295  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 15:43:01.295  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:01.295  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.295  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.305  1458  1482 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 15:43:01.305  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:01.305  1017  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:43:01.305  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-26 15:43:01.305  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 15:43:01.305  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:01.305  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
08-26 15:43:01.305  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 15:43:01.305  1441  1441 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@7f5073a, true
,08-26 15:43:01.315  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-26 15:43:01.315  1441  1441 D BluetoothHeadset: registerMessageListener
,08-26 15:43:01.315  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 15:43:01.315  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:01.315  4726  4726 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:01.315  1177  1177 D BluetoothTile:  getBluetoothState : 12
,08-26 15:43:01.315  1962  1962 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 15:43:01.315  1177  1666 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 15:43:01.315  3209  7749 D HeadsetService: registerMessageListener
,08-26 15:43:01.325  3209  7749 D HeadsetService: registerMessageListener
,08-26 15:43:01.325  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:01.325  3209  7750 D HeadsetStateMachine: Disconnected process message: 70
,08-26 15:43:01.325  3209  7750 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@7f813d9
,08-26 15:43:01.325  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:01.325  1017  1547 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 15:43:01.325  1017  3827 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-26 15:43:01.325  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 15:43:01.325  1441  1441 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-26 15:43:01.325  1441  1441 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-26 15:43:01.325  3209  7761 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-26 15:43:01.325  1177  1666 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 15:43:01.335  4726  4726 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-26 15:43:01.335  4726  4726 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-26 15:43:01.335  4726  4726 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-26 15:43:01.335  4726  4726 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-26 15:43:01.335  1177  1666 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 15:43:01.335  1441  1441 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-26 15:43:01.335  1441  1441 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-26 15:43:01.335  1441  1441 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-26 15:43:01.335  3209  7761 D BluetoothSocket: bindListen(): myUserId = 0,
08-26 15:43:01.335  3209  7761 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 15:43:01.335  3209  7750 D HeadsetStateMachine: Disconnected process message: 9
08-26 15:43:01.335  3209  7750 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-26 15:43:01.335  3209  7761 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]},
08-26 15:43:01.335  3209  7761 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 15:43:01.335  3209  7761 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 15:43:01.335  3209  7761 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d82c19e
08-26 15:43:01.335  3209  7761 D BluetoothSocket: channel: 5
,08-26 15:43:01.335   283   699 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-26 15:43:01.335   283   699 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-26 15:43:01.335   283   699 V voice   : voice_set_parameters: exit with code(-2)
,08-26 15:43:01.345   283   699 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-26 15:43:01.345   283   699 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-26 15:43:01.345   283   699 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-26 15:43:01.345   283   699 V audio_hw_primary: adev_set_parameters: exit
,08-26 15:43:01.345  3209  7750 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-26 15:43:01.345  4726  4726 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 15:43:01.345  1017  1307 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 15:43:01.345  1017  1307 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.345  1017  1307 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:01.345  1017  1307 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:43:01.345  1017  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 15:43:01.355  1668  1668 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 15:43:01.355  4726  4726 D DockEventReceiver: finishStartingService: stopping service
,08-26 15:43:01.355  4726  4726 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 15:43:01.365  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:01.365  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-26 15:43:01.365  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
,08-26 15:43:01.365  3209  3209 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 15:43:01.365  1017  1307 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:43:01.365  1017  1307 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.375  1017  1307 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:01.375  1017  1307 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.375  1017  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.385  1017  1136 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 15:43:01.395  3209  7767 D BluetoothSocket: bindListen(): myUserId = 0
08-26 15:43:01.395  3209  7767 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 15:43:01.395  3209  7767 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
08-26 15:43:01.395  3209  7767 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 15:43:01.395  3209  7767 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 15:43:01.395  3209  7767 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@27d559aa
,08-26 15:43:01.395  3209  7767 D BluetoothSocket: channel: 12
,08-26 15:43:01.395  3209  7767 I BtOppRfcommListener: Accept thread started.
,08-26 15:43:02.415  1017  1547 I ActivityManager: Killing 7335:com.sec.pcw.device/1000 (adj 15): empty #21
,08-26 15:43:02.465  1017  1030 I ActivityManager: Killing 7353:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-26 15:43:02.635  1017  1042 W ActivityManager: mDVFSHelper.release()
,08-26 15:43:02.775   288   288 E SMD     : DCD OFF
,08-26 15:43:02.775  1017  1095 V AlarmManager: waitForAlarm result :4
,08-26 15:43:02.785  1017  1017 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-26 15:43:02.785  1017  1017 V AlarmManagerEXT: <AppSync3 Whitelist>
08-26 15:43:02.785  1017  1017 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-26 15:43:02.795   278   995 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 15:43:02.795   278   995 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-26 15:43:02.795  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
08-26 15:43:02.795  1177  1177 D KeyguardUpdateMonitor: handleTimeUpdate
,08-26 15:43:02.805  1177  1177 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-26 15:43:02.805  1177  1177 D SecKeyguardClockView: HomeTimezone(): 1
,08-26 15:43:02.815  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:43:02.815  1177  1177 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,08-26 15:43:02.815  1177  1177 I KeyguardEffectViewController: *** don't update sliding image ***
,08-26 15:43:02.825  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:02.825  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:43:02.825  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-26 15:43:02.855  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:43:02.855  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:43:02.865  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:43:02.865  1177  1177 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,08-26 15:43:02.875  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:43:03.825  1017  3380 D SSRM:n  : SIOP:: AP = 380
,08-26 15:43:04.015  6945  7152 D BluetoothAdapter: disable()
,08-26 15:43:04.025  1017  1545 D SettingsProvider: name = bluetooth_on
,08-26 15:43:04.035  3209  3285 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-26 15:43:04.035  3209  3285 D BluetoothAdapterProperties: Setting state to 13
08-26 15:43:04.035  3209  3285 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 15:43:04.035  3209  3285 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 15:43:04.035  3209  3285 D BluetoothAdapterService: updateAdapterState state is 13
08-26 15:43:04.035  1017  3827 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:04.035  1017  3827 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 15:43:04.035  1017  3827 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:04.035  1017  3827 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:04.035  1017  3827 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:04.035  3209  3285 D BluetoothAdapterService: Autoconnection is available 
,08-26 15:43:04.035  3209  3285 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-26 15:43:04.035  3209  3285 D BluetoothAdapterService: terminating service from this receiver
,08-26 15:43:04.035  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-26 15:43:04.035  3209  3209 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-26 15:43:04.035  3209  3209 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3aa5299b, channel: 19, state: LISTENING
,08-26 15:43:04.035  3209  3209 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3aa5299b, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3160ae20, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@13e22138mSocket: android.net.LocalSocket@6b76511 impl:android.net.LocalSocketImpl@39076676 fd:FileDescriptor[80]
08-26 15:43:04.035  3209  3209 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@6b76511 impl:android.net.LocalSocketImpl@39076676 fd:FileDescriptor[80]
,08-26 15:43:04.045  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:04.045  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:04.045  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:04.045  3209  3285 D BluetoothAdapterProperties: onBluetoothDisable()
,08-26 15:43:04.045  3209  3285 D BluetoothAdapterProperties: mDiscovering is false
,08-26 15:43:04.045  1017  1029 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 15:43:04.045  3209  3285 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-26 15:43:04.055  4726  4726 D BluetoothPbap: Proxy object disconnected
08-26 15:43:04.055  4726  4726 D PbapServerProfile: Bluetooth service disconnected
,08-26 15:43:04.055  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:04.055  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,08-26 15:43:04.055  3209  3288 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 15:43:04.055  3209  3288 D BluetoothAdapterProperties: Scan Mode:20
,08-26 15:43:04.065  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-26 15:43:04.065  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 15:43:04.065  1177  1666 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 15:43:04.065  1177  1666 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 15:43:04.065  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:04.065  1177  1177 D BluetoothTile:  getBluetoothState : 13
,08-26 15:43:04.075  1177  1666 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 15:43:04.075  1017  1488 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 15:43:04.075  1017  3829 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 15:43:04.075  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 15:43:04.085  1962  1962 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 15:43:04.085  4726  4726 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:04.095  3209  3285 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 15:43:04.095  3209  3285 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-26 15:43:04.095  3209  3285 E bt-btif : cmd socket is not created
,08-26 15:43:04.095  3209  3285 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 15:43:04.095  3209  3295 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-26 15:43:04.095  3209  7767 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-26 15:43:04.105  4726  4726 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 15:43:04.105  3209  3295 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 15:43:04.105  3209  3295 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 15:43:04.105  3209  3295 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 15:43:04.105  3209  3295 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 15:43:04.105  3209  3295 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 15:43:04.105  3209  3295 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 15:43:04.105  1017  3829 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 15:43:04.105  1017  3829 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 15:43:04.105  1017  3829 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:04.105  1017  3829 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:04.105  1017  3829 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 15:43:04.105  6945  6945 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 15:43:04.105  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:04.105  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:04.105  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:04.105  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:43:04.105  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:43:04.105  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:04.105  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:04.105  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:04.105  6945  6945 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 15:43:04.115  6945  6945 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:04.115  6945  6945 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 15:43:04.115  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:04.115  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:04.115  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:04.115  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:43:04.115  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:43:04.115  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:04.115  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:04.115  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:04.115  6945  6945 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 15:43:04.115  6945  6945 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:04.115  1668  1668 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 15:43:04.125  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:04.125  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:04.125  4726  4726 D DockEventReceiver: finishStartingService: stopping service
,08-26 15:43:04.125  3209  3209 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2e3418e4, channel: 5, state: LISTENING
08-26 15:43:04.125  4726  4726 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 15:43:04.125  3209  3209 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2e3418e4, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d82c19e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@301c414dmSocket: android.net.LocalSocket@267b7402 impl:android.net.LocalSocketImpl@3b753113 fd:FileDescriptor[82]
,08-26 15:43:04.125  3209  3209 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@267b7402 impl:android.net.LocalSocketImpl@3b753113 fd:FileDescriptor[82]
,08-26 15:43:04.135  3209  3209 I BtOppRfcommListener: stopping Accept Thread
08-26 15:43:04.135  3209  3209 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@d8bdf50, channel: 12, state: LISTENING
,08-26 15:43:04.135  3209  3209 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@d8bdf50, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@27d559aa, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2a78a549mSocket: android.net.LocalSocket@3730ce4e impl:android.net.LocalSocketImpl@3cf7cb6f fd:FileDescriptor[86]
08-26 15:43:04.135  3209  3209 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3730ce4e impl:android.net.LocalSocketImpl@3cf7cb6f fd:FileDescriptor[86]
,08-26 15:43:04.135  3209  7767 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 15:43:04.135  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:04.135  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-26 15:43:04.135  3209  3209 V BluetoothOppManager: cleanUp...
,08-26 15:43:04.195  1017  3410 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:43:04.295  3209  3285 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-26 15:43:04.295  3209  3285 D BtConfig.SecureMode: isSecureModeOn:false
08-26 15:43:04.295  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:04.295  3209  3285 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-26 15:43:04.295  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 15:43:04.295  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
,08-26 15:43:04.295  3209  3285 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-26 15:43:04.295  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 15:43:04.295  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 15:43:04.295  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-26 15:43:04.305  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:04.305  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:04.305  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:04.305  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService,
08-26 15:43:04.305  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-26 15:43:04.305  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 15:43:04.305  1017  3827 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-26 15:43:04.305  1017  3827 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 15:43:04.305  1017  3827 W ActivityManager: userId = 0, bbcId = -10000,
,08-26 15:43:04.315  1017  3827 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:04.315  1017  3827 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:04.315  3209  3209 D HeadsetService: Received stop request...Stopping profile...
,08-26 15:43:04.315  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-26 15:43:04.315  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 15:43:04.315  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 15:43:04.315  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
,08-26 15:43:04.315  1017  3830 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:43:04.315  1017  3830 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 15:43:04.315  1017  3830 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:04.315  1017  3830 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:04.315  1017  3830 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:04.315  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-26 15:43:04.325  3209  3209 D A2dpService: Received stop request...Stopping profile...
08-26 15:43:04.325  4726  4726 D HeadsetProfile: Bluetooth service disconnected
08-26 15:43:04.325  3209  7752 D A2dpStateMachine: Exit Disconnected: -1
,08-26 15:43:04.325  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-26 15:43:04.325  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 15:43:04.325  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 15:43:04.325  1017  1547 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:04.325  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
,08-26 15:43:04.325  1017  1547 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 15:43:04.325  1017  1547 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:04.325  1017  1547 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:04.325  1017  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:04.325  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-26 15:43:04.325  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 15:43:04.325  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 15:43:04.325  1017  1545 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:43:04.325  1017  1545 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 15:43:04.335  1017  1017 D BluetoothA2dp: Proxy object disconnected
08-26 15:43:04.335  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-26 15:43:04.335  4726  4726 D BluetoothA2dp: Proxy object disconnected
08-26 15:43:04.335  4726  4726 D A2dpProfile: Bluetooth service disconnected
,08-26 15:43:04.335  1017  1545 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:04.335  1017  1545 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:04.335  1017  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:04.335  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 15:43:04.335  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:43:04.335  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 15:43:04.335  1017  1544 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:43:04.335  1017  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 15:43:04.335  1017  1544 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:04.335  1017  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:04.335  1017  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:04.335  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,08-26 15:43:04.335  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-26 15:43:04.335  3209  3285 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 15:43:04.335  1017  1456 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:04.335  1017  1456 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 15:43:04.345  1017  1456 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:04.345  1017  1456 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:04.345  1017  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:04.345  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 15:43:04.345  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:43:04.345  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:43:04.345  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-26 15:43:04.345  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-26 15:43:04.345  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:43:04.345  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 15:43:04.345  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-26 15:43:04.345  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,08-26 15:43:04.345  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-26 15:43:04.345  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService,
08-26 15:43:04.345  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 15:43:04.345  3209  3285 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-26 15:43:04.345  3209  3209 E BluetoothAdapterService(441650423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-26 15:43:04.345  3209  3209 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 15:43:04.345  3209  3209 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-26 15:43:04.345  3209  3209 D HidService: Received stop request...Stopping profile...
08-26 15:43:04.345  3209  3209 D HidService: Stopping Bluetooth HidService
,08-26 15:43:04.345  3209  3209 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 15:43:04.345  3209  3209 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-26 15:43:04.345  3209  3209 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 15:43:04.345  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
,08-26 15:43:04.355  4726  4726 D BluetoothInputDevice: Proxy object disconnected
08-26 15:43:04.355  4726  4726 D HidProfile: Bluetooth service disconnected
,08-26 15:43:04.365  3209  3209 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-26 15:43:04.365  3209  3209 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-26 15:43:04.365  3209  3209 E BluetoothAdapterService(441650423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-26 15:43:04.365  3209  3209 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 15:43:04.365  3209  3209 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-26 15:43:04.365  3209  3209 D HealthService: Received stop request...Stopping profile...
,08-26 15:43:04.365  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
,08-26 15:43:04.365  3209  3209 D BluetoothA2dp: Proxy object disconnected
,08-26 15:43:04.365  3209  3209 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-26 15:43:04.365  3209  7753 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-26 15:43:04.365  3209  3209 I GKI_LINUX: GKI_exit_task 2 done
08-26 15:43:04.365  3209  3209 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-26 15:43:04.365  3209  3209 D PanService: Received stop request...Stopping profile...
08-26 15:43:04.365  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
,08-26 15:43:04.365  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 15:43:04.375  3209  3209 D BluetoothMapService: Received stop request...Stopping profile...
,08-26 15:43:04.375  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
,08-26 15:43:04.375  4726  4726 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 15:43:04.375  4726  4726 D PanProfile: Bluetooth service disconnected
,08-26 15:43:04.375  3209  3209 D SapService: Received stop request...Stopping profile...
08-26 15:43:04.375  3209  3209 D SapService: Stopping Bluetooth SapService
08-26 15:43:04.375  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
08-26 15:43:04.375  4726  4726 D BluetoothMap: Proxy object disconnected
08-26 15:43:04.375  4726  4726 D MapProfile: Bluetooth service disconnected
,08-26 15:43:04.375  3209  3209 E BluetoothAdapterService(441650423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,08-26 15:43:04.375  3209  3209 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 15:43:04.375  3209  3209 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-26 15:43:04.375  3209  3209 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-26 15:43:04.375  3209  3209 E BluetoothAdapterService(441650423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-26 15:43:04.375  3209  3209 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,08-26 15:43:04.375  3209  3209 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:43:04.375  3209  3209 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-26 15:43:04.375  3209  3209 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 15:43:04.375  3209  3209 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-26 15:43:04.375  3209  3209 E BluetoothAdapterService(441650423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
,08-26 15:43:04.385  3209  3209 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 15:43:04.385  3209  3209 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:43:04.385  3209  3209 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 15:43:04.385  3209  3209 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 15:43:04.385  3209  3209 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-26 15:43:04.385  4726  4726 D Bluetoothsap: BluetoothSAP Proxy object disconnected
,08-26 15:43:04.385  3209  3209 E BluetoothAdapterService(441650423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-26 15:43:04.385  3209  3209 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 15:43:04.385  3209  3209 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 15:43:04.385  3209  3209 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-26 15:43:04.385  3209  3209 E BluetoothAdapterService(441650423): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-26 15:43:04.385  3209  3209 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 15:43:04.385  3209  3209 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-26 15:43:04.385  3209  3209 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-26 15:43:04.385  4726  4726 D SapProfile: Bluetooth service disconnected
,08-26 15:43:04.385  3209  3285 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-26 15:43:04.385  3209  3285 D BluetoothAdapterProperties: Setting state to 10
08-26 15:43:04.385  3209  3285 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 15:43:04.385  3209  3285 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 15:43:04.385  3209  3285 D BluetoothAdapterService: updateAdapterState state is 10
,08-26 15:43:04.385  3209  3285 D BluetoothAdapterService: Autoconnection is available 
,08-26 15:43:04.385  3209  3285 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-26 15:43:04.385  3209  3285 I BluetoothAdapterState: Entering OffState
,08-26 15:43:04.385  7233  7241 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 15:43:04.385  7233  7241 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:43:04.385  1177  1742 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:43:04.385  1177  1742 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:43:04.385  1458  1786 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:43:04.385  1458  1786 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:43:04.385  1639  1655 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 15:43:04.385  1639  1655 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:43:04.395  3209  7762 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 15:43:04.395  4726  4736 D Bluetoothsap: onBluetoothStateChange: up=false
,08-26 15:43:04.395  4726  4736 D Bluetoothsap: Unbinding service...
,08-26 15:43:04.395  4726  4734 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 15:43:04.395  6945  7665 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 15:43:04.395  6945  7665 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 15:43:04.395  6945  7665 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-26 15:43:04.395  6945  7665 D BluetoothLeAdvertiser: Exit stop advertising
08-26 15:43:04.395  6945  7665 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,08-26 15:43:04.395  6945  7665 D BluetoothLeScanner: Exiting stopAllScan
,08-26 15:43:04.395  4726  4736 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 15:43:04.395  4726  4734 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:43:04.395  4726  4734 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 15:43:04.395  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 15:43:04.395  1668  1748 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:43:04.395  1668  1748 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 15:43:04.395  4726  7760 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 15:43:04.395  4726  4736 D BluetoothMap: onBluetoothStateChange: up=false
,08-26 15:43:04.395  1441  1457 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 15:43:04.405  1441  1457 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:43:04.405  3209  3291 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 15:43:04.405  3209  3291 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:43:04.405  1448  1466 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:43:04.405  1448  1466 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:43:04.405  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 15:43:04.405  1017  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:43:04.405  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
08-26 15:43:04.405  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
08-26 15:43:04.405  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 15:43:04.415  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 15:43:04.415  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:04.415  1177  1177 D BluetoothTile:  getBluetoothState : 10
,08-26 15:43:04.415  1962  1962 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 15:43:04.415  1017  1030 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 15:43:04.415  4726  4726 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:04.415  1017  1503 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 15:43:04.415  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 15:43:04.415  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:04.425  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:04.425  4726  4726 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 15:43:04.425  1017  1029 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 15:43:04.425  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 15:43:04.425  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:04.425  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:43:04.425  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 15:43:04.435  1668  1668 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 15:43:04.435  4726  4726 D DockEventReceiver: finishStartingService: stopping service
,08-26 15:43:04.435  4726  4726 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 15:43:04.435  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:04.435  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-26 15:43:04.785   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:43:05.775   288   288 E SMD     : DCD OFF,
,08-26 15:43:05.785   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:43:06.785   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:43:06.845  1017  1307 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:43:06.845  1017  1307 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4302, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:43:06.845  1017  1307 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:43:06.845  1017  1307 D BatteryService: stay LED for charging
08-26 15:43:06.845  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:43:06.855  1017  1017 I MotionRecognitionService: Plugged
08-26 15:43:06.855  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:43:06.855  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:43:06.855  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate,
,08-26 15:43:06.855  1423  1423 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:43:06.855  1423  1423 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:43:06.875  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:43:06.875  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:43:06.885  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 15:43:06.885  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-26 15:43:06.885  1177  1177 D SViewCoverView: level :100 plugged : 2
,08-26 15:43:07.025  6945  7152 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 15:43:07.035  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:07.785   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:43:08.775   288   288 E SMD     : DCD OFF,
,08-26 15:43:08.785   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:43:09.785   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-26 15:43:10.035  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-26 15:43:10.035  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f263560 added. We now have 6 listener(s)
08-26 15:43:10.035  6945  7152 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-26 15:43:10.035  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:10.035  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3fc82a19 added. We now have 7 listener(s),
08-26 15:43:10.035  6945  7152 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:10.035  6945  7152 I System.out: IsBluetoothEnabled
,08-26 15:43:10.035  6945  7152 D BluetoothAdapter: disable()
,08-26 15:43:10.045  1017  1307 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-26 15:43:10.045  6945  7152 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:10.055  6945  7152 D BluetoothAdapter: enable()
,08-26 15:43:10.055  1017  1489 W ActivityManager: Permission Denial: getCurrentUser() from pid=6945, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-26 15:43:10.055  1017  1489 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-26 15:43:10.055  1017  1489 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6945, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-26 15:43:10.055  1017  1489 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 15:43:10.055  1017  1489 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-26 15:43:10.055  1017  1489 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-26 15:43:10.055  1017  1489 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-26 15:43:10.055  1017  1489 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 15:43:10.055  1017  1489 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 15:43:10.055  1017  1489 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 15:43:10.055  1017  1489 D SettingsProvider: name = bluetooth_on,
,08-26 15:43:10.065  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 15:43:10.065  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 15:43:10.065  1017  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-26 15:43:10.075  3209  3285 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-26 15:43:10.075  3209  3285 D BluetoothAdapterProperties: Setting state to 11
,08-26 15:43:10.075  3209  3285 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 15:43:10.075  3209  3285 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-26 15:43:10.075  3209  3285 D BluetoothAdapterService: updateAdapterState state is 11
,08-26 15:43:10.075  3209  3285 D BluetoothAdapterService: Autoconnection is available 
,08-26 15:43:10.075  3209  3285 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-26 15:43:10.075  3209  3285 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 15:43:10.075  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-26 15:43:10.075  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,08-26 15:43:10.075  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 15:43:10.075  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
,08-26 15:43:10.075  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 15:43:10.075  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-26 15:43:10.075  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 15:43:10.075  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-26 15:43:10.075  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-26 15:43:10.075  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-26 15:43:10.075  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 15:43:10.075  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-26 15:43:10.075  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-26 15:43:10.075  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-26 15:43:10.075  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 15:43:10.075  3209  3285 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-26 15:43:10.075  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:43:10.085  1017  1503 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:10.075  3209  3285 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:43:10.085  1017  1503 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-26 15:43:10.075  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:43:10.075  3209  3285 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:43:10.075  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 15:43:10.075  3209  3285 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-26 15:43:10.075  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 15:43:10.075  3209  3285 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-26 15:43:10.075  3209  3285 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-26 15:43:10.075  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 15:43:10.075  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 15:43:10.075  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-26 15:43:10.085  1017  1503 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:10.085  1017  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.085  1017  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.085  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService,
08-26 15:43:10.085  1017  1545 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:43:10.085  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 15:43:10.085  1017  1545 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-26 15:43:10.085  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-26 15:43:10.085  3209  3209 D HeadsetService: Received start request. Starting profile...
,08-26 15:43:10.085  3209  3209 D HeadsetService: start()
08-26 15:43:10.085  3209  3209 D HeadsetStateMachine: make
08-26 15:43:10.085  1017  1545 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:10.085  1017  1545 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.085  1017  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.085  3209  3209 E HeadsetStateMachine: # of Max HF connection is 2
,08-26 15:43:10.095  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService,
08-26 15:43:10.095  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 15:43:10.095  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 15:43:10.095  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:10.095  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,08-26 15:43:10.105  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 15:43:10.105  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:10.105  1177  1177 D BluetoothTile:  getBluetoothState : 11
,08-26 15:43:10.105  1177  1666 D BluetoothTile:  handleUpdatestate:false name:null
08-26 15:43:10.105  1177  1666 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 15:43:10.105  4726  4726 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:10.105  1962  1962 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 15:43:10.115  1017  1136 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:10.115  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 15:43:10.115  1017  1545 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 15:43:10.115  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:10.115  1017  3830 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 15:43:10.115  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:10.115  1017  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.115  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.115  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 15:43:10.115  1017  3827 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-26 15:43:10.115  1017  3827 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-26 15:43:10.125  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,08-26 15:43:10.125  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 15:43:10.125  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 15:43:10.125  1017  3827 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:10.125  1017  3827 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.125  1017  3827 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 15:43:10.125  1017  3829 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-26 15:43:10.125  1017  3829 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-26 15:43:10.125  1017  3829 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:10.125  1017  3829 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.125  1017  3829 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 15:43:10.125  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:43:10.125  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 15:43:10.125  3209  3209 I bluedroid: get_profile_interface handsfree
,08-26 15:43:10.125  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:10.135  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:43:10.135  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.135  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-26 15:43:10.135  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 15:43:10.135  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 15:43:10.135  1668  1668 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 15:43:10.145  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:43:10.145  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 15:43:10.145  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:10.145  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.145  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.145  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 15:43:10.145  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:43:10.145  3209  3285 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-26 15:43:10.145  3209  3209 E DualScoManager: Dual Sco Manager already instantiated
08-26 15:43:10.145  3209  3209 I DualScoManager: Set HeadsetServiceHelper
08-26 15:43:10.145  3209  3209 D BluetoothAtMessage: createCMTIContentObservers
,08-26 15:43:10.145  1017  1545 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-26 15:43:10.145  1017  1456 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:10.145  1017  1545 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:43:10.145  1017  1456 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-26 15:43:10.145  1017  1545 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:43:10.145  1017  1545 D SettingsProvider: selectionArgs: false
08-26 15:43:10.145  1017  1545 D SettingsProvider: selectionArgs: 1002
08-26 15:43:10.145  1017  1545 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:43:10.145  1017  1545 D SettingsProvider: ret = -1
,08-26 15:43:10.155  1017  1456 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:10.155  1017  1456 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.155  1017  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 15:43:10.155  3209  7783 D HeadsetStateMachine: Enter Disconnected: -2
,08-26 15:43:10.155  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-26 15:43:10.155  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 15:43:10.155  3209  3285 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-26 15:43:10.155  1017  1503 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:10.155  1017  1503 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 15:43:10.155  1017  1503 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:10.155  1017  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.155  1017  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.155  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 15:43:10.155  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:43:10.155  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:43:10.155  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:43:10.155  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:43:10.155  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:43:10.155  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 15:43:10.155  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 15:43:10.155  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 15:43:10.155  3209  3285 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-26 15:43:10.155  3209  3285 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 15:43:10.155  3209  3285 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 15:43:10.155  3209  3285 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-26 15:43:10.165  3209  3209 D HeadsetService: mStartError = false
08-26 15:43:10.165  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
,08-26 15:43:10.165  3209  3209 D A2dpService: Received start request. Starting profile...
,08-26 15:43:10.165  3209  3209 D A2dpService: start()
08-26 15:43:10.165  3209  3209 I bluedroid: get_profile_interface avrcp
,08-26 15:43:10.165  3209  7783 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-26 15:43:10.165  3209  7783 D HeadsetStateMachine: map size, before remove : 0
08-26 15:43:10.165  3209  7783 D HeadsetStateMachine: map size, after remove: 0
08-26 15:43:10.165  4726  4726 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 15:43:10.165  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:10.175  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-26 15:43:10.175  3209  3209 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 15:43:10.175  3209  3209 D Avrcp   : Initialize Media Controller
08-26 15:43:10.175  3209  3209 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-26 15:43:10.175  3209  3209 E Avrcp   : getActiveSessions
08-26 15:43:10.175  3209  3209 D Avrcp   : pick active media Controller
08-26 15:43:10.175  3209  3209 D Avrcp   : Get the active Media Controller 
,08-26 15:43:10.185  3209  3209 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-26 15:43:10.185  3209  3209 D A2dpStateMachine: make
,08-26 15:43:10.185  3209  7784 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-26 15:43:10.195  3209  3209 I bluedroid: get_profile_interface a2dp
,08-26 15:43:10.195  3209  7786 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-26 15:43:10.195  3209  3209 E bt-btif : warning : media task started media_task_refcnt 1 
08-26 15:43:10.195  3209  3209 D A2dpService: mStartError = false
08-26 15:43:10.195  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
,08-26 15:43:10.195  3209  3209 D HeadsetStateMachine: Proxy object connected
08-26 15:43:10.195  3209  3209 D HeadsetStateMachine: Try to query the phonestate on bind
,08-26 15:43:10.195  3209  7785 D A2dpStateMachine: Enter Disconnected: -2
08-26 15:43:10.195  1441  7759 I Telecom : BluetoothPhoneService: queryPhoneState
08-26 15:43:10.195  1441  1441 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-26 15:43:10.195  1441  1441 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-26 15:43:10.195  1441  7759 I Telecom : BluetoothPhoneService: Result of Message : true
,08-26 15:43:10.195  3209  3209 D HidService: Received start request. Starting profile...
08-26 15:43:10.195  3209  3209 D HidService: start()
08-26 15:43:10.195  3209  3209 I bluedroid: get_profile_interface hidhost
08-26 15:43:10.195  3209  3209 D HidService: setHidService(): set to: null
08-26 15:43:10.195  3209  3209 D HidService: mStartError = false
08-26 15:43:10.195  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
,08-26 15:43:10.195  3209  3209 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-26 15:43:10.195  3209  7783 D HeadsetStateMachine: Disconnected process message: 11
08-26 15:43:10.195  3209  3209 D HealthService: Received start request. Starting profile...
08-26 15:43:10.195  3209  3209 D HealthService: start()
,08-26 15:43:10.205  3209  7784 D BluetoothMediaBrowser: no now playing list
08-26 15:43:10.205  3209  7784 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-26 15:43:10.205  3209  3209 I bluedroid: get_profile_interface health
08-26 15:43:10.205  3209  3209 D HealthService: mStartError = false
08-26 15:43:10.205  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
08-26 15:43:10.205  3209  3209 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-26 15:43:10.205  3209  3209 D HeadsetPhoneState: Signal level : previous=0 curr=4
,08-26 15:43:10.205  3209  7783 D HeadsetStateMachine: Disconnected process message: 18
08-26 15:43:10.205  3209  3209 D PanService: Received start request. Starting profile...
08-26 15:43:10.205  3209  3209 D PanService: start()
,08-26 15:43:10.205  3209  3209 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 15:43:10.205  3209  3209 I bluedroid: get_profile_interface pan
08-26 15:43:10.205  3209  3209 D PanService: mStartError = false
08-26 15:43:10.205  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
08-26 15:43:10.205  3209  3209 D BluetoothMapService: Received start request. Starting profile...
08-26 15:43:10.205  3209  3209 D BluetoothMapService: start()
08-26 15:43:10.205  3209  3209 D BluetoothMapService: mStartError = false
08-26 15:43:10.205  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7,
08-26 15:43:10.205  3209  3209 D SapService: Received start request. Starting profile...
08-26 15:43:10.205  3209  3209 D SapService: start()
08-26 15:43:10.205  3209  3209 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-26 15:43:10.205  3209  3209 I bluedroid: get_profile_interface sap
08-26 15:43:10.205  3209  3209 D SapService: mStartError = false
08-26 15:43:10.205  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
08-26 15:43:10.205  3209  3209 E BluetoothAdapterService(441650423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-26 15:43:10.205  3209  3209 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 15:43:10.205  3209  7783 D HeadsetStateMachine: Disconnected process message: 10
08-26 15:43:10.205  3209  7783 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 15:43:10.205  3209  7783 D HeadsetStateMachine: Disconnected process message: 11
08-26 15:43:10.205  3209  3209 E BluetoothAdapterService(441650423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-26 15:43:10.205  3209  3209 E BluetoothAdapterService(441650423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-26 15:43:10.215  3209  3209 E BluetoothAdapterService(441650423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-26 15:43:10.215  3209  3209 E BluetoothAdapterService(441650423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-26 15:43:10.225  3209  3209 E BluetoothAdapterService(441650423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true,
08-26 15:43:10.225  3209  3209 E BluetoothAdapterService(441650423): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-26 15:43:10.225  3209  3285 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-26 15:43:10.225  3209  3285 I bluedroid: enable
,08-26 15:43:10.225  3209  3288 E bt-btif : Calling BTA_HhEnable
08-26 15:43:10.225  3209  3288 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-26 15:43:10.225  3209  3288 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-26 15:43:10.225  3209  3288 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
08-26 15:43:10.225  3209  3288 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-26 15:43:10.225  3209  3288 E BluetoothServiceJni: populateRssiValuesNative
08-26 15:43:10.225  3209  3288 I bluedroid: getModelRssiValues
08-26 15:43:10.225  3209  3288 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-26 15:43:10.225  3209  3288 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 15:43:10.235  3209  3288 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-26 15:43:10.235  1017  1017 D SettingsProvider: name = bluetooth_name
,08-26 15:43:10.235  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:10.235  3209  3288 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 15:43:10.235  3209  3288 D BluetoothAdapterProperties: Scan Mode:20
08-26 15:43:10.235  3209  3288 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 15:43:10.235  3209  3288 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-26 15:43:10.235  3209  3288 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
,08-26 15:43:10.235  3209  3288 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-26 15:43:10.235  3209  3288 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-26 15:43:10.245  3209  3288 E bt-btif : JVenable fails
,08-26 15:43:10.245  3209  3288 D bte_conf: Device ID record 1 : primary
08-26 15:43:10.245  3209  3288 D bte_conf:   vendorId            = 0075
08-26 15:43:10.245  3209  3288 D bte_conf:   vendorIdSource      = 0001
08-26 15:43:10.245  3209  3288 D bte_conf:   product             = 0100
08-26 15:43:10.245  3209  3288 D bte_conf:   version             = 0200
08-26 15:43:10.245  3209  3288 D bte_conf:   clientExecutableURL = 
08-26 15:43:10.245  3209  3288 D bte_conf:   serviceDescription  = 
08-26 15:43:10.245  3209  3288 D bte_conf:   documentationURL    = 
08-26 15:43:10.245  3209  3288 D bte_conf: bte_load_did_conf no section named DID2.
08-26 15:43:10.245  3209  3288 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-26 15:43:10.245  3209  3288 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 15:43:10.245  3209  3285 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-26 15:43:10.245  3209  3285 D BluetoothAdapterProperties: ScanMode =  20
08-26 15:43:10.245  3209  3285 D BluetoothAdapterProperties: State =  11
,08-26 15:43:10.245  1017  1546 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 15:43:10.245  3209  3285 D BluetoothAdapterProperties: Setting state to 12,
08-26 15:43:10.245  3209  3285 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 15:43:10.245  1017  1544 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-26 15:43:10.245  1017  1544 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:43:10.245  1017  1544 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 15:43:10.245  1017  1544 D SettingsProvider: selectionArgs: false
08-26 15:43:10.245  1017  1544 D SettingsProvider: selectionArgs: 1002
08-26 15:43:10.245  1017  3830 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:10.245  1017  1544 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 15:43:10.245  1017  3830 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-26 15:43:10.245  1017  1544 D SettingsProvider: ret = -1
08-26 15:43:10.245  3209  3285 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 15:43:10.245  3209  3285 D BluetoothAdapterService: updateAdapterState state is 12
,08-26 15:43:10.245  1017  3830 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:10.245  1017  3830 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:43:10.245  1017  3830 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.255  3209  3285 D BluetoothAdapterService: Autoconnection is available 
08-26 15:43:10.255  3209  3285 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-26 15:43:10.255  3209  3285 D BluetoothAdapterService: starting service from this receiver
,08-26 15:43:10.255  7233  7241 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:10.255  7233  7241 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 15:43:10.255  1017  3829 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:10.255  1017  3829 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 15:43:10.255  1177  3560 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:10.255  1177  3560 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 15:43:10.255  1017  3829 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:10.255  1017  3829 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.255  1017  3829 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 15:43:10.255  3209  3209 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-26 15:43:10.255  3209  3209 I BluetoothPbapService: Handler(): got msg=1
,08-26 15:43:10.255  1017  1489 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 15:43:10.255  1458  2484 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:10.255  1458  2484 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:43:10.255  3209  3285 I BluetoothAdapterState: Entering On State from state = 11
,08-26 15:43:10.265  1639  1652 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:10.265  1639  1652 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 15:43:10.265  1017  1046 D BluetoothPan: Binding service...
08-26 15:43:10.265  3209  3288 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 15:43:10.265  3209  3288 D BluetoothAdapterProperties: Scan Mode:21
,08-26 15:43:10.265  3209  3288 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 15:43:10.265  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 15:43:10.265  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 15:43:10.265  1441  1481 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:10.265  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 15:43:10.265  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 15:43:10.265  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:10.265  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.265  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.275  1441  1481 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 15:43:10.275  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:10.275  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:10.275  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:10.275  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:43:10.275  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:10.275  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:10.275  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:10.275  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:10.275  1441  1457 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:10.275  3209  7791 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-26 15:43:10.275  6945  6945 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:10.275  3209  7791 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 15:43:10.275  3209  7791 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 15:43:10.285  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 15:43:10.285  3209  7791 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-26 15:43:10.285  3209  7791 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 15:43:10.285  3209  7791 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 15:43:10.285  3209  7791 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2b1df747
08-26 15:43:10.285  3209  7791 D BluetoothSocket: channel: 19
08-26 15:43:10.285  3209  7791 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-26 15:43:10.285  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 15:43:10.285  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 15:43:10.285  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:10.285  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.285  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.285  1441  1457 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 15:43:10.285  3209  3377 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 15:43:10.285  3209  3377 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:10.285  1017  1046 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-26 15:43:10.285  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 15:43:10.285  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:10.285  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.295  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.295  3209  3209 D BluetoothA2dp: Proxy object connected
08-26 15:43:10.295  3209  3209 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-26 15:43:10.295  4726  7760 D Bluetoothsap: onBluetoothStateChange: up=true
08-26 15:43:10.295  4726  7760 D Bluetoothsap: Binding service...
,08-26 15:43:10.295  4726  7760 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-26 15:43:10.435  1017  1046 I art     : Explicit concurrent mark sweep GC freed 62345(3MB) AllocSpace objects, 6(97KB) LOS objects, 33% free, 22MB/34MB, paused 2.330ms total 140.180ms
08-26 15:43:10.435  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-26 15:43:10.435  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 15:43:10.435  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:10.435  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.435  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.435  4726  7760 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-26 15:43:10.435  1017  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-26 15:43:10.435  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 15:43:10.435  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 15:43:10.435  1017  1046 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 15:43:10.435  4726  4736 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 15:43:10.445  4726  4726 D Bluetoothsap: BluetoothSAP Proxy object connected
08-26 15:43:10.445  4726  4726 D SapProfile: Bluetooth service connected
08-26 15:43:10.445  4726  4726 D Bluetoothsap: getConnectedDevices()
,08-26 15:43:10.445  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-26 15:43:10.445  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 15:43:10.445  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:10.445  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.445  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.445  6945  6955 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:10.445  6945  6955 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:43:10.445  4726  4726 D BluetoothPbap: Proxy object connected
08-26 15:43:10.445  4726  4726 D PbapServerProfile: Bluetooth service connected
,08-26 15:43:10.445  4726  4734 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:10.445  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 15:43:10.445  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 15:43:10.445  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:10.445  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.445  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.445  4726  4734 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 15:43:10.445  4726  4726 D HeadsetProfile: Bluetooth service connected
,08-26 15:43:10.445  4726  7760 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 15:43:10.455  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-26 15:43:10.455  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 15:43:10.455  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:10.455  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.455  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.455  4726  4736 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 15:43:10.455  4726  4736 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:43:10.455  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 15:43:10.455  1017  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:10.455  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 15:43:10.455  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-26 15:43:10.455  1017  1017 D BluetoothA2dp: Proxy object connected
,08-26 15:43:10.455  1668  1676 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 15:43:10.455  1668  1676 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:43:10.455  4726  7760 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 15:43:10.455  4726  4726 D BluetoothInputDevice: Proxy object connected
08-26 15:43:10.455  4726  4726 D HidProfile: Bluetooth service connected
,08-26 15:43:10.455  4726  7760 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:10.455  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-26 15:43:10.455  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 15:43:10.455  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:10.455  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.455  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.465  4726  4736 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 15:43:10.465  4726  4726 D BluetoothA2dp: Proxy object connected
,08-26 15:43:10.465  4726  4726 D A2dpProfile: Bluetooth service connected
08-26 15:43:10.465  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-26 15:43:10.465  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 15:43:10.465  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:10.465  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.465  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.465  1441  7759 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 15:43:10.465  1441  7759 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:43:10.465  4726  7792 D BluetoothPan: Binding service...
,08-26 15:43:10.465  4726  4726 D BluetoothMap: Proxy object connected
,08-26 15:43:10.465  4726  4726 D MapProfile: Bluetooth service connected
,08-26 15:43:10.465  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 15:43:10.465  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-26 15:43:10.465  4726  4726 D BluetoothMap: getConnectedDevices()
,08-26 15:43:10.465  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:10.465  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.465  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.465  1441  1457 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:10.475  4726  4726 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 15:43:10.475  4726  4726 D PanProfile: Bluetooth service connected
,08-26 15:43:10.475  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 15:43:10.475  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 15:43:10.475  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:10.475  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.475  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.475  1441  1457 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 15:43:10.475  3209  7749 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 15:43:10.475  3209  7749 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:43:10.475  1448  1468 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 15:43:10.475  1448  1468 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:43:10.475  1458  1482 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:10.475  1017  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 15:43:10.475  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 15:43:10.475  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:10.475  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.475  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.475  1458  1482 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 15:43:10.475  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:10.475  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-26 15:43:10.475  1017  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 15:43:10.475  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 15:43:10.485  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:10.485  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
08-26 15:43:10.485  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 15:43:10.485  1441  1441 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@1c63efeb, true
,08-26 15:43:10.485  1441  1441 D BluetoothHeadset: registerMessageListener
,08-26 15:43:10.485  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-26 15:43:10.485  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:10.485  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 15:43:10.485  1177  1177 D BluetoothTile:  getBluetoothState : 12
08-26 15:43:10.485  1177  1666 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 15:43:10.495  1177  1666 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 15:43:10.495  1177  1666 D BluetoothTile:  handleUpdatestate:false name:null
08-26 15:43:10.495  1962  1962 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 15:43:10.495  4726  4726 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:10.495  1017  1489 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 15:43:10.495  1017  1307 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-26 15:43:10.495  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:10.495  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 15:43:10.505  3209  3220 D HeadsetService: registerMessageListener
,08-26 15:43:10.505  3209  7793 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-26 15:43:10.505  3209  3220 D HeadsetService: registerMessageListener
,08-26 15:43:10.505  3209  7783 D HeadsetStateMachine: Disconnected process message: 70
08-26 15:43:10.505  3209  7783 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@5041b74
08-26 15:43:10.505  1441  1441 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-26 15:43:10.505  1441  1441 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-26 15:43:10.505  4726  4726 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-26 15:43:10.505  4726  4726 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-26 15:43:10.505  4726  4726 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-26 15:43:10.505  4726  4726 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-26 15:43:10.505  1441  1441 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-26 15:43:10.505  1441  1441 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-26 15:43:10.505  1441  1441 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-26 15:43:10.505  3209  7793 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 15:43:10.505  3209  7783 D HeadsetStateMachine: Disconnected process message: 9
,08-26 15:43:10.505  3209  7793 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 15:43:10.505  3209  7783 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
08-26 15:43:10.515  3209  7793 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-26 15:43:10.515  3209  7793 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 15:43:10.515  3209  7793 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 15:43:10.515  3209  7793 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@12d5389d
,08-26 15:43:10.515  3209  7793 D BluetoothSocket: channel: 5
,08-26 15:43:10.515  4726  4726 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 15:43:10.515   283   679 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-26 15:43:10.515   283   679 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-26 15:43:10.515   283   679 V voice   : voice_set_parameters: exit with code(-2)
08-26 15:43:10.515  1017  1546 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 15:43:10.515  1017  1546 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 15:43:10.515   283   679 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-26 15:43:10.515   283   679 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-26 15:43:10.515   283   679 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-26 15:43:10.515   283   679 V audio_hw_primary: adev_set_parameters: exit
08-26 15:43:10.515  3209  7783 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-26 15:43:10.515  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:10.515  1017  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:43:10.515  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 15:43:10.525  4726  4726 D DockEventReceiver: finishStartingService: stopping service
,08-26 15:43:10.525  1668  1668 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 15:43:10.535  4726  4726 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 15:43:10.535  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:10.535  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-26 15:43:10.535  3209  3209 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a530cf7
,08-26 15:43:10.545  3209  3209 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 15:43:10.545  1017  1503 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:43:10.545  1017  1503 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-26 15:43:10.545  1017  1503 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:10.545  1017  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:43:10.545  1017  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.555  1017  1544 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 15:43:10.565  3209  7798 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 15:43:10.565  3209  7798 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 15:43:10.565  3209  7798 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
,08-26 15:43:10.565  3209  7798 D BluetoothSocket: bindListen(), new LocalSocket 
,08-26 15:43:10.565  3209  7798 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-26 15:43:10.565  3209  7798 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2751c199
,08-26 15:43:10.565  3209  7798 D BluetoothSocket: channel: 12
,08-26 15:43:10.565  3209  7798 I BtOppRfcommListener: Accept thread started.
,08-26 15:43:10.645  1017  1095 V AlarmManager: waitForAlarm result :4
,08-26 15:43:10.655   278   995 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 15:43:10.655   278   995 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-26 15:43:10.665  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:10.665  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:43:10.665  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-26 15:43:11.075  6945  7152 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:11.075  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:11.075  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:11.075  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:43:11.075  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:11.075  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:11.075  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:11.075  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:11.075  6945  7152 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:11.075  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 15:43:11.075  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d63bade added. We now have 8 listener(s)
,08-26 15:43:11.075  6945  7152 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:43:11.085  1017  1307 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 15:43:11.085  1017  1307 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-26 15:43:11.085  1017  1307 D SecContentProvider2: mCursor = null
,08-26 15:43:11.085  1017  1307 D WifiService: setWifiEnabled: false pid=6945, uid=10170
,08-26 15:43:11.085  1017  1307 D SettingsProvider: name = wifi_on
,08-26 15:43:11.095  6945  7152 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:11.095  1017  1030 D WifiService: setWifiEnabled: true pid=6945, uid=10170
08-26 15:43:11.095  1017  1030 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 15:43:11.095  1017  1030 W ActivityManager: Permission Denial: getCurrentUser() from pid=6945, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-26 15:43:11.095  1017  1030 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 15:43:11.095  1017  1030 D SecContentProvider2: mCursor = null
08-26 15:43:11.095  1017  1030 W WifiService: Failed getting userId using ActivityManagerNative
08-26 15:43:11.095  1017  1030 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6945, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-26 15:43:11.095  1017  1030 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 15:43:11.095  1017  1030 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 15:43:11.095  1017  1030 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 15:43:11.095  1017  1030 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 15:43:11.095  1017  1030 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-26 15:43:11.095  1017  1030 D SettingsProvider: name = wifi_on
,08-26 15:43:11.105  1017  1126 E WifiHW  : ##################### set firmware type 0 #####################
,08-26 15:43:11.465  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
08-26 15:43:11.465  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-26 15:43:11.465  1017  1044 D Tethering: interfaceStatusChanged wlan0, false,
08-26 15:43:11.465  1017  1044 D Tethering: interfaceAdded wlan0
,08-26 15:43:11.475  1017  1131 E Tethering: No numeric data,
08-26 15:43:11.475   278   999 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-26 15:43:11.475  1017  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 15:43:11.475  1017  1131 D Tethering: clearTetheredNotification()
08-26 15:43:11.475  1017  1123 V NetworkStats: performPollLocked(flags=0x1),
08-26 15:43:11.475   278   999 D SoftapController: Softap fwReload - Ok
,08-26 15:43:11.475  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
08-26 15:43:11.475  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:43:11.485  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 15:43:11.475  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 15:43:11.485  1177  1177 D HotspotTile: updateTetherState():false, false
08-26 15:43:11.485  1017  1044 D Tethering: interfaceAdded p2p0
08-26 15:43:11.485   278   999 D CommandListener: Setting iface cfg
08-26 15:43:11.485   278   999 D CommandListener: Trying to bring down wlan0
08-26 15:43:11.485  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 15:43:11.485  1017  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
08-26 15:43:11.485  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,08-26 15:43:11.485  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-26 15:43:11.485   278   999 D CommandListener: Clearing all IP addresses on wlan0
,08-26 15:43:11.495  1017  1123 V NetworkStats: performPollLocked() took 16ms
,08-26 15:43:11.495  1017  1126 E WifiHW  : supplicant_name : p2p_supplicant
08-26 15:43:11.495  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:11.495  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:11.495  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:11.495  1017  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-26 15:43:11.505  1017  1126 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-26 15:43:11.515  4726  4726 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:43:11.515  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:11.515  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 15:43:11.515  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:43:11.515  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 15:43:11.515  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:11.515  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:11.515  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:43:11.515  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:11.515  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:11.515  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:43:11.515  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-26 15:43:11.515  1177  1666 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 15:43:11.515  1177  1177 D HotspotTile: onReceive : 2, 0
08-26 15:43:11.515  1017  1545 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 15:43:11.515  1017  1545 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:43:11.515  1017  1545 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:11.515  1017  1545 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:11.515  1017  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:43:11.525  2214  2214 I Hs20UtilService: Starting #19
,08-26 15:43:11.525  7121  7121 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 15:43:11.525  7121  7121 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 15:43:11.525  7121  7121 D SecurityLogAgent: StateMachine : Current State = 1
08-26 15:43:11.525  7121  7121 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 15:43:11.525  2214  2229 I Hs20UtilService: Message received 5011
,08-26 15:43:11.545  7811  7811 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
,08-26 15:43:11.545  7811  7811 I wpa_supplicant: Successfully initialized wpa_supplicant
08-26 15:43:11.545  7811  7811 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-26 15:43:11.565  7811  7811 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-26 15:43:11.565   335   335 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7811,
08-26 15:43:11.565   335   335 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-26 15:43:11.565  7811  7811 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
,08-26 15:43:11.565  7811  7811 I wpa_supplicant: ssSupport state is = 1
08-26 15:43:11.565  7811  7811 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-26 15:43:11.565  7811  7811 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-26 15:43:11.565   335   335 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7811
08-26 15:43:11.565   335   335 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-26 15:43:11.725   335   335 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
08-26 15:43:11.725  7811  7811 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-26 15:43:11.765  7811  7811 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-26 15:43:11.765  7811  7811 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-26 15:43:11.775  7811  7811 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-26 15:43:11.775   335   335 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7811
08-26 15:43:11.775   335   335 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-26 15:43:11.775  7811  7811 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-26 15:43:11.775  7811  7811 I wpa_supplicant: ssSupport state is = 1,
08-26 15:43:11.775  7811  7811 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:43:11.775  7811  7811 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 15:43:11.775  7811  7811 E wpa_supplicant: SIM READ ERROR,
08-26 15:43:11.775  7811  7811 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:43:11.775  7811  7811 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 15:43:11.775  7811  7811 E wpa_supplicant: SIM READ ERROR
08-26 15:43:11.775  7811  7811 I wpa_supplicant: Blacklist: Clear (all) ,
08-26 15:43:11.775  7811  7811 I wpa_supplicant: wpa_default_ap_write_once
08-26 15:43:11.775  7811  7811 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 15:43:11.775  7811  7811 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:43:11.775  7811  7811 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
08-26 15:43:11.775  7811  7811 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:43:11.775  7811  7811 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 15:43:11.775   288   288 E SMD     : DCD OFF
08-26 15:43:11.775  7811  7811 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 15:43:11.785  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
08-26 15:43:11.785  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 15:43:11.785  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-26 15:43:11.785  1017  1131 D Tethering: InitialState.processMessage what=4
,08-26 15:43:11.785  1017  1131 E Tethering: No numeric data,
08-26 15:43:11.785  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-26 15:43:11.785  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-26 15:43:11.785  1017  1131 D Tethering: clearTetheredNotification()
08-26 15:43:11.785  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
08-26 15:43:11.785  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:43:11.785  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 15:43:11.785  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 15:43:11.785  1177  1177 D HotspotTile: updateTetherState():false, false
,08-26 15:43:11.785  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:11.785  1017  1123 V NetworkStats: performPollLocked() took 4ms
,08-26 15:43:11.795  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:11.795  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:11.835  7811  7811 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-26 15:43:12.025  7811  7811 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-26 15:43:12.025  7811  7811 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-26 15:43:12.035  7811  7811 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-26 15:43:12.035   335   335 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7811
08-26 15:43:12.035   335   335 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-26 15:43:12.045  7811  7811 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-26 15:43:12.045  7811  7811 I wpa_supplicant: ssSupport state is = 1
,08-26 15:43:12.045  7811  7811 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-26 15:43:12.045  7811  7811 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-26 15:43:12.055  7811  7811 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-26 15:43:12.055   335   335 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7811
08-26 15:43:12.055   335   335 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-26 15:43:12.055  7811  7811 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-26 15:43:12.055  7811  7811 I wpa_supplicant: ssSupport state is = 1
08-26 15:43:12.055  7811  7811 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:43:12.055  7811  7811 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-26 15:43:12.055  7811  7811 E wpa_supplicant: SIM READ ERROR
08-26 15:43:12.055  7811  7811 I wpa_supplicant: wpa_default_ap_write_once
08-26 15:43:12.055  7811  7811 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,08-26 15:43:12.055  7811  7811 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 15:43:12.055  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false,
08-26 15:43:12.055  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 15:43:12.055  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-26 15:43:12.065  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 15:43:12.065  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 15:43:12.065  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-26 15:43:12.165  7811  7811 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-26 15:43:12.165  7811  7811 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-26 15:43:12.225  7811  7811 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-26 15:43:12.225  7811  7811 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-26 15:43:12.225  7811  7811 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 15:43:12.455  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 15:43:12.455  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 15:43:12.455  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-26 15:43:12.505  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,08-26 15:43:12.505  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-26 15:43:12.505  7811  7811 I wpa_supplicant: HOTSPOT20_ENABLE called
,08-26 15:43:12.505  7811  7811 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:43:12.505  7811  7811 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 15:43:12.505  7811  7811 E wpa_supplicant: SIM READ ERROR
08-26 15:43:12.505  7811  7811 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 15:43:12.535  7811  7811 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-26 15:43:12.545  7811  7811 I wpa_supplicant: Skip scan - bUseNetwork false,
08-26 15:43:12.545  1017  1126 D WifiConfigStore: Loading config and enabling all networks 
,08-26 15:43:12.555  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 15:43:12.555  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 15:43:12.555  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 15:43:12.555  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:12.555  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:12.565  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:12.565  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:12.565  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-26 15:43:12.565  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-26 15:43:12.565  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:43:12.565  4726  4726 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:43:12.565  1177  1666 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 15:43:12.565  1177  1177 D HotspotTile: onReceive : 3, 0
,08-26 15:43:12.565  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 15:43:12.565  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:43:12.565  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:12.575  1017  1126 E WifiConfigStore: Not a HS20
08-26 15:43:12.575  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:12.575  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:12.575  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:12.575  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:12.575  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:12.575  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:12.575  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:12.575  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:12.575  6945  6945 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:12.575  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:43:12.575  6945  6945 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:12.575  1017  1126 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-26 15:43:12.575  1017  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-26 15:43:12.575  7811  7811 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-26 15:43:12.575  7811  7811 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-26 15:43:12.575  7811  7811 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 15:43:12.575  7811  7811 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 15:43:12.575  7811  7811 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-26 15:43:12.575  7811  7811 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-26 15:43:12.575  7811  7811 I wpa_supplicant: First Scan Start
08-26 15:43:12.575  7811  7811 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-26 15:43:12.575  2214  2214 I Hs20UtilService: Starting #20
08-26 15:43:12.575  2214  2229 I Hs20UtilService: Message received 5011
,08-26 15:43:12.585  1017  1126 D WifiNative-wlan0: Setting external_sim to 1
,08-26 15:43:12.585  1017  1126 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 15:43:12.585  1017  1126 I WifiNative-HAL: startHal
08-26 15:43:12.585  1017  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9f20c88c
08-26 15:43:12.585  1017  1126 I WifiNative-HAL: Could not start hal
,08-26 15:43:12.585  7278  7278 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:43:12.585  7121  7121 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 15:43:12.585  7121  7121 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-26 15:43:12.585  7121  7121 D SecurityLogAgent: StateMachine : Current State = 1
08-26 15:43:12.585  7121  7121 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 15:43:12.585  1017  1126 E WifiNative-wlan0: do suspend true
,08-26 15:43:12.585  1017  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-26 15:43:12.585  1017  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
08-26 15:43:12.585  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
,08-26 15:43:12.585  1017  1151 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:12.585  1017  1151 I WifiNative-HAL: startHal
08-26 15:43:12.585  1017  1151 E wifi    : getStaticLongField sWifiHalHandle 0x9e0ce9bc
08-26 15:43:12.585  1017  1151 I WifiNative-HAL: Could not start hal
,08-26 15:43:12.585  1017  1151 E WifiScanningService: could not start HAL
08-26 15:43:12.585  1017  1017 D RttService: SCAN_AVAILABLE : 3,
08-26 15:43:12.585  1017  1152 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:12.595  1017  1125 D WifiP2pService: P2pEnablingState
,08-26 15:43:12.595   278   999 D CommandListener: Setting iface cfg
08-26 15:43:12.595  1017  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
08-26 15:43:12.595   278   999 D CommandListener: Trying to bring up p2p0
08-26 15:43:12.595  1017  1125 D WifiP2pService: P2p socket connection successful
08-26 15:43:12.595  1017  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 15:43:12.595  1017  1125 D WifiP2pService: P2pEnabledState
08-26 15:43:12.595  1017  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 15:43:12.595  1017  1126 E WifiNative-wlan0: invaild command id : 215
08-26 15:43:12.595  1017  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 15:43:12.595  7811  7811 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 15:43:12.595  7811  7811 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 15:43:12.595  7811  7811 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-26 15:43:12.595  1017  1126 E WifiStateMachine: Failed to set frequency band 0
08-26 15:43:12.605  1017  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 15:43:12.605  1017  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 15:43:12.605  1017  1126 E WifiNative-wlan0: invaild command id : 215
,08-26 15:43:12.605  1017  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-26 15:43:12.605  1017  1128 E ConnectivityService: updateNetworkInfo()
08-26 15:43:12.605  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 15:43:12.605  1017  1126 D SecContentProvider2: mCursor = null
,08-26 15:43:12.605  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-26 15:43:12.605  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-26 15:43:12.605  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 15:43:12.605  1017  1047 D WifiDisplayController: disconnect
08-26 15:43:12.605  1017  1047 D WifiDisplayController: updateConnection
08-26 15:43:12.605  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 15:43:12.605  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 15:43:12.605  1017  1125 D WifiNative-p2p0: p2pGetDeviceAddress
08-26 15:43:12.605  1017  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-26 15:43:12.615  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 15:43:12.615  1017  1126 D SecContentProvider2: mCursor = null
,08-26 15:43:12.615  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:43:12.615  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-26 15:43:12.615  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 15:43:12.615  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
08-26 15:43:12.615  1017  1125 D WifiP2pService: DeviceAddress: 0a:75:42
,08-26 15:43:12.615  4726  4726 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 15:43:12.615  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-26 15:43:12.615  1017  3830 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 15:43:12.615  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-26 15:43:12.615  1017  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-26 15:43:12.615  1017  1047 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-26 15:43:12.615  1017  1047 D WifiDisplayController:  primary type: 10-0050F204-5
08-26 15:43:12.615  1017  1047 D WifiDisplayController:  secondary type: null
08-26 15:43:12.615  1017  1047 D WifiDisplayController:  wps: 0
08-26 15:43:12.615  1017  1047 D WifiDisplayController:  grpcapab: 0
08-26 15:43:12.615  1017  1047 D WifiDisplayController:  devcapab: 0
08-26 15:43:12.615  1017  1047 D WifiDisplayController:  status: 3
08-26 15:43:12.615  1017  1047 D WifiDisplayController:  wfdInfo: null
08-26 15:43:12.615  1017  1047 D WifiDisplayController:  groupownerAddress: null
08-26 15:43:12.615  1017  1047 D WifiDisplayController:  GOdeviceName: null
08-26 15:43:12.615  1017  1047 D WifiDisplayController:  interfaceAddress: 
08-26 15:43:12.615  1017  1047 D WifiDisplayController:  SConnectInfo : null
08-26 15:43:12.615  4726  4726 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 15:43:12.615  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 15:43:12.615  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 15:43:12.615  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 15:43:12.615  4726  4726 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 15:43:12.615  4726  4795 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 15:43:12.625  7690  7690 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 15:43:12.625  7690  7690 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-26 15:43:12.625  7690  7690 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 15:43:12.635  7318  7318 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 15:43:12.635  1017  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-26 15:43:12.635  1017  1125 D WifiP2pService: InactiveState
,08-26 15:43:12.635  1017  1125 D WifiP2pService: InactiveState{ what=143376 }
08-26 15:43:12.635  1017  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 15:43:12.635  7811  7811 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 15:43:12.635  1017  1125 D WifiP2pService: InactiveState{ what=143376 }
,08-26 15:43:12.635  1017  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 15:43:13.115  6945  7152 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:13.115  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:13.115  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:13.115  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:13.115  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:13.115  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:13.115  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:13.115  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:13.125  6945  7152 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:13.125  6945  7152 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-26 15:43:13.125  6945  7152 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 15:43:13.135  6945  7152 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3f9ff43d Bundle[{}],
,08-26 15:43:13.135  6945  7152 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 15:43:13.135  6945  7152 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-26 15:43:13.135  6945  7152 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-26 15:43:13.135  6945  7152 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-26 15:43:13.135  6945  7152 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-26 15:43:13.135  6945  7152 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 15:43:13.145  6945  7152 I System.out: Running OutgoingSocketThread
,08-26 15:43:13.145  6945  7822 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1405)
,08-26 15:43:13.145  6945  7822 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 52705
,08-26 15:43:13.145  6945  7822 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 15:43:13.765  7811  7811 I wpa_supplicant: nl80211: Received scan results (23 BSSes),
08-26 15:43:13.765  7811  7811 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
08-26 15:43:13.765  7811  7811 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-26 15:43:13.765  7811  7811 I wpa_supplicant: Trying to associate with  'G700'
08-26 15:43:13.765  7811  7811 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
08-26 15:43:13.765  7811  7811 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-26 15:43:13.765  1017  7819 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-26 15:43:13.785  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 15:43:13.785  1017  1126 D SecContentProvider2: mCursor = null
,08-26 15:43:13.845  1017  3380 D SSRM:n  : SIOP:: AP = 340,
,08-26 15:43:13.935  7811  7811 E wpa_supplicant: Cmd 35605 not handled
08-26 15:43:13.935  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:43:13.935  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-26 15:43:13.935  7811  7811 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED,
08-26 15:43:13.935  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 15:43:13.935  7811  7811 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-26 15:43:13.935  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 15:43:13.935  7811  7811 I wpa_supplicant: Associated with F4.99.3E
08-26 15:43:13.935  7811  7811 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 15:43:13.935  7811  7811 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-26 15:43:13.935  7811  7811 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-26 15:43:13.935  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:43:13.935  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 15:43:13.935  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-26 15:43:13.935  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:43:13.935  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-26 15:43:13.935  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 15:43:13.935  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true,
08-26 15:43:13.935  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,08-26 15:43:13.945  1017  1131 E Tethering: No numeric data
08-26 15:43:13.945  1017  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 15:43:13.945  1017  1131 D Tethering: clearTetheredNotification()
08-26 15:43:13.945  7811  7811 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 15:43:13.945  7811  7811 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-26 15:43:13.945  7811  7811 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-26 15:43:13.945  7811  7811 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-26 15:43:13.945  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:13.945  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-26 15:43:13.945  7811  7811 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 15:43:13.945  7811  7811 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,08-26 15:43:13.945  7811  7811 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-26 15:43:13.945  7811  7811 I wpa_supplicant: Blacklist: Clear (temp) 
08-26 15:43:13.945  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-26 15:43:13.945  7811  7811 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-26 15:43:13.945  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-26 15:43:13.945  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 15:43:13.955  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 15:43:13.945  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 15:43:13.955  1177  1177 D HotspotTile: updateTetherState():false, false
,08-26 15:43:13.945  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
08-26 15:43:13.955  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 15:43:13.955  1017  1123 V NetworkStats: performPollLocked() took 9ms
08-26 15:43:13.955  1017  1126 D SecContentProvider2: mCursor = null
,08-26 15:43:13.955  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:13.955  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:13.955  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:13.955  1017  1126 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-26 15:43:13.965  1017  1126 E WifiConfigStore: setLastSelectedConfiguration -1,
,08-26 15:43:13.965  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 15:43:13.965  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:43:13.965  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 15:43:13.965  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:13.965  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:13.975  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:13.975  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:13.975  1017  1544 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 15:43:13.975  1017  1544 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:43:13.975  1017  1126 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-26 15:43:13.975  1017  1128 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-26 15:43:13.975  1017  1128 E ConnectivityService: updateNetworkInfo()
,08-26 15:43:13.975  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-26 15:43:13.975  1017  1544 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:13.975  1017  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:43:13.975  1017  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 15:43:13.975  2214  2214 I Hs20UtilService: Starting #21
08-26 15:43:13.975  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 15:43:13.975  2214  2229 I Hs20UtilService: Message received 5007
,08-26 15:43:13.975  4726  4726 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 15:43:13.985  4726  4726 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 15:43:13.985  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 15:43:13.985  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 15:43:13.985  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-26 15:43:13.985  4726  4726 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 15:43:13.985  4726  4795 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 15:43:13.995  1017  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 15:43:14.005   278   999 D CommandListener: Setting iface cfg
,08-26 15:43:14.005  1017  1126 E WifiStateMachine: Start Dhcp Watchdog 3
,08-26 15:43:14.005  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 15:43:14.005  1017  1126 D SecContentProvider2: mCursor = null
,08-26 15:43:14.015  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 15:43:14.015  1017  1126 D SecContentProvider2: mCursor = null
,08-26 15:43:14.025  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 15:43:14.025  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 15:43:14.025  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 15:43:14.025  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:14.025  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:14.025  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:14.025  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:14.035  1017  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 15:43:14.035  1017  1126 D SecContentProvider2: mCursor = null
,08-26 15:43:14.035  1017  1126 E WifiNative-wlan0: do suspend false
,08-26 15:43:14.035  1017  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-26 15:43:14.035  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 15:43:14.145  6945  7152 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1406)
,08-26 15:43:14.145  6945  7152 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1406)
,08-26 15:43:14.155  6945  7152 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1411)
,08-26 15:43:14.155  6945  7152 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-26 15:43:14.155  6945  7152 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1412)
,08-26 15:43:14.155  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 15:43:14.155  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c1a64bf added. We now have 2 listener(s)
,08-26 15:43:14.165  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-26 15:43:14.165  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 15:43:14.165  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 15:43:14.165  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 15:43:14.165  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca9478c added. We now have 9 listener(s)
,08-26 15:43:14.165  6945  7152 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:43:14.165  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 15:43:14.165  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:43:14.175  6945  7152 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:43:14.175  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:14.175  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:14.175  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:14.175  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:14.175  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:14.175  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:14.175  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:14.175  6945  7152 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:43:14.175  6945  7152 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 15:43:14.175  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:14.175  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38eca6ea added. We now have 3 listener(s)
,08-26 15:43:14.175  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:14.185  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:14.185  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-26 15:43:14.185  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:14.185  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:14.185  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:14.185  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a9a8ddb added. We now have 10 listener(s)
08-26 15:43:14.185  6945  7152 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-26 15:43:14.185  6945  7152 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 15:43:14.185  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:43:14.185  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:43:14.185  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 15:43:14.185  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.185  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 15:43:14.185  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:14.185  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c1a64bf removed from the list
08-26 15:43:14.185  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:14.185  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca9478c removed from the list
08-26 15:43:14.185  6945  7152 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 15:43:14.185  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:14.185  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.185  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 15:43:14.185  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:14.185  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:14.185  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:14.185  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca9478c not in the list
08-26 15:43:14.185  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:43:14.185  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:14.185  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:14.185  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:14.185  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:43:14.185  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a9a8ddb removed from the list
08-26 15:43:14.185  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:14.185  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.185  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:14.185  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 15:43:14.185  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38eca6ea removed from the list
08-26 15:43:14.185  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 15:43:14.185  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d695078 added. We now have 2 listener(s)
08-26 15:43:14.185  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-26 15:43:14.185  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 15:43:14.185  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-26 15:43:14.185  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:14.195  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@312c0351 added. We now have 9 listener(s)
08-26 15:43:14.195  6945  7152 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:14.195  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 15:43:14.195  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-26 15:43:14.195  6945  7152 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:43:14.195  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:14.195  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:14.195  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:14.195  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:14.195  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:14.195  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:14.195  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:14.205  6945  7152 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:14.205  6945  7152 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:43:14.205  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-26 15:43:14.205  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:14.205  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@342a2cb7 added. We now have 3 listener(s)
,08-26 15:43:14.205  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:14.205  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-26 15:43:14.215  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 15:43:14.215  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 15:43:14.215  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 15:43:14.215  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c1efc24 added. We now have 10 listener(s)
,08-26 15:43:14.215  6945  7152 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:43:14.215  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 15:43:14.215  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 15:43:14.215  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 15:43:14.215  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:43:14.215  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 15:43:14.215  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 15:43:14.225  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 15:43:14.225  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 15:43:14.225  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 15:43:14.225  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 15:43:14.225  6945  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 15:43:14.235  3209  3220 D BtGatt.GattService: registerClient() - UUID=6963fc2c-d531-4f42-8458-a8c4d5ebe681
,08-26 15:43:14.245  7826  7826 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-26 15:43:14.255  7826  7826 I dhcpcd  : version 5.5.6 starting,
,08-26 15:43:14.255  7826  7826 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-26 15:43:14.275  3209  3288 D BtGatt.GattService: onClientRegistered() - UUID=6963fc2c-d531-4f42-8458-a8c4d5ebe681, clientIf=6
,08-26 15:43:14.275  6945  6955 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
,08-26 15:43:14.275  3209  3225 D BtGatt.GattService: start scan with filters
,08-26 15:43:14.285  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 15:43:14.285  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 15:43:14.285  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 15:43:14.285  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 15:43:14.285  3209  3352 D BtGatt.ScanManager: handling starting scan
,08-26 15:43:14.285  3209  3288 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 15:43:14.285  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:14.295  3209  3352 D BtGatt.ScanManager: allow scan with filters
,08-26 15:43:14.295  3209  3352 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 15:43:14.295  3209  3352 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
,08-26 15:43:14.295  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 15:43:14.295  6945  6945 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 15:43:14.295  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 15:43:14.295  3209  3288 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 15:43:14.295  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:43:14.295  3209  3352 D BtGatt.ScanManager: Starting BLE batch scan
08-26 15:43:14.295  3209  3352 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 15:43:14.305  3209  3288 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 15:43:14.305  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:14.305  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 15:43:14.305  3209  3288 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-26 15:43:14.305  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:14.315  6945  7152 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation,
08-26 15:43:14.315  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 15:43:14.315  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything,
08-26 15:43:14.315  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.315  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 15:43:14.315  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 15:43:14.315  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 15:43:14.315  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 15:43:14.315  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 15:43:14.315  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-26 15:43:14.315  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 15:43:14.325  3209  3291 D BtGatt.GattService: stopScan() - queue size =1
08-26 15:43:14.325  3209  3352 D BtGatt.ScanManager: filter size is 1
08-26 15:43:14.325  3209  3352 D BtGatt.ScanManager: delete FilterIndex - 6
08-26 15:43:14.325  3209  7749 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 15:43:14.325  3209  3288 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 15:43:14.325  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:43:14.335  3209  3352 D BtGatt.ScanManager: stopping BLe Batch
08-26 15:43:14.335  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:43:14.335  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 15:43:14.335  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 15:43:14.335  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 15:43:14.335  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 15:43:14.335  7826  7826 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-26 15:43:14.335  7826  7826 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address,
08-26 15:43:14.335  7826  7826 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-26 15:43:14.335  7826  7826 I dhcpcd  : bssid match
08-26 15:43:14.335  7826  7826 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
08-26 15:43:14.335  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 15:43:14.335  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 15:43:14.335  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 15:43:14.335  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 15:43:14.335  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 15:43:14.335  3209  3288 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 15:43:14.335  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:43:14.335  3209  3352 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 15:43:14.335  3209  3288 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-26 15:43:14.335  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:14.345  6945  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 15:43:14.345  6945  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:43:14.345  6945  6945 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:43:14.345  6945  7152 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 15:43:14.345  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 15:43:14.345  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 15:43:14.345  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 15:43:14.345  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:43:14.345  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 15:43:14.345  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:14.345  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d695078 removed from the list
,08-26 15:43:14.345  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:43:14.345  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@312c0351 removed from the list
08-26 15:43:14.345  6945  7152 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 15:43:14.345  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:14.345  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:43:14.345  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:14.355  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 15:43:14.355  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 15:43:14.355  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:43:14.355  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@312c0351 not in the list
,08-26 15:43:14.355  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.355  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:14.355  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 15:43:14.355  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:14.355  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:43:14.355  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c1efc24 removed from the list
08-26 15:43:14.355  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:14.355  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.355  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:14.355  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:14.355  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@342a2cb7 removed from the list
,08-26 15:43:14.355  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 15:43:14.355  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3461b690 added. We now have 2 listener(s)
,08-26 15:43:14.355  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-26 15:43:14.365  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:14.365  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:14.365  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:14.365  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@169acb89 added. We now have 9 listener(s)
08-26 15:43:14.365  6945  7152 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:43:14.365  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 15:43:14.365  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:43:14.365  6945  7152 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:43:14.365  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:14.365  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:14.365  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:14.365  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:14.365  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:14.365  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:14.365  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:14.365  6945  7152 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:14.365  6945  7152 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 15:43:14.365  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:14.365  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@167bfbaf added. We now have 3 listener(s)
,08-26 15:43:14.375  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:14.375  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-26 15:43:14.375  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:14.375  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:14.375  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:14.375  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31d3abbc added. We now have 10 listener(s)
08-26 15:43:14.375  6945  7152 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:14.375  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:43:14.375  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:43:14.375  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 15:43:14.375  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 15:43:14.375  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:43:14.375  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 15:43:14.375  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:14.375  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 15:43:14.385  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 15:43:14.385  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 15:43:14.385  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 15:43:14.385  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 15:43:14.385  6945  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 15:43:14.395  3209  7749 D BtGatt.GattService: registerClient() - UUID=255b499b-911b-43a9-bd6e-b802206deb3e
,08-26 15:43:14.405  7826  7826 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,08-26 15:43:14.435  3209  3288 D BtGatt.GattService: onClientRegistered() - UUID=255b499b-911b-43a9-bd6e-b802206deb3e, clientIf=6
,08-26 15:43:14.435  6945  7665 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 15:43:14.435  3209  3220 D BtGatt.GattService: start scan with filters
,08-26 15:43:14.435  3209  3352 D BtGatt.ScanManager: handling starting scan
,08-26 15:43:14.435  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 15:43:14.435  3209  3288 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 15:43:14.435  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:43:14.435  3209  3352 D BtGatt.ScanManager: allow scan with filters
,08-26 15:43:14.435  3209  3352 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 15:43:14.435  3209  3352 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,08-26 15:43:14.435  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 15:43:14.435  3209  3288 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 15:43:14.445  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 15:43:14.445  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 15:43:14.445  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:43:14.445  3209  3352 D BtGatt.ScanManager: Starting BLE batch scan
08-26 15:43:14.445  3209  3352 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 15:43:14.445  3209  3288 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 15:43:14.445  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:14.445  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 15:43:14.445  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 15:43:14.445  6945  6945 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 15:43:14.445  3209  3288 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-26 15:43:14.445  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:14.455  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 15:43:14.455  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 15:43:14.455  6945  7152 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-26 15:43:14.455  6945  7152 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 15:43:14.455  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 15:43:14.455  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 15:43:14.455  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 15:43:14.455  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.455  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 15:43:14.455  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 15:43:14.455  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3461b690 removed from the list
,08-26 15:43:14.455  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:14.455  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@169acb89 removed from the list
,08-26 15:43:14.455  6945  7152 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 15:43:14.465  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 15:43:14.465  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.465  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-26 15:43:14.465  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.465  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:43:14.465  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:14.465  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:14.465  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:14.465  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@169acb89 not in the list
08-26 15:43:14.465  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 15:43:14.465  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 15:43:14.465  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 15:43:14.465  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 15:43:14.465  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 15:43:14.465  3209  3377 D BtGatt.GattService: stopScan() - queue size =1
,08-26 15:43:14.465  3209  7762 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 15:43:14.465  3209  3352 D BtGatt.ScanManager: filter size is 1
08-26 15:43:14.465  3209  3352 D BtGatt.ScanManager: delete FilterIndex - 7
08-26 15:43:14.465  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:43:14.465  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 15:43:14.465  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 15:43:14.465  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 15:43:14.465  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 15:43:14.465  3209  3288 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 15:43:14.465  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:43:14.465  3209  3352 D BtGatt.ScanManager: stopping BLe Batch
,08-26 15:43:14.465  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:43:14.475  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 15:43:14.475  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 15:43:14.475  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 15:43:14.475  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:14.475  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:14.475  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:14.475  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:14.475  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31d3abbc removed from the list
08-26 15:43:14.475  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:14.475  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.475  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:14.475  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:14.475  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@167bfbaf removed from the list
,08-26 15:43:14.475  6945  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:43:14.475  6945  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 15:43:14.475  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:14.475  6945  6945 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 15:43:14.475  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360dc7a8 added. We now have 2 listener(s)
,08-26 15:43:14.475  3209  3288 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 15:43:14.475  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:43:14.475  3209  3352 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 15:43:14.475  3209  3288 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-26 15:43:14.475  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:14.475  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
,08-26 15:43:14.475  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-26 15:43:14.475  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 15:43:14.475  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:14.475  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa362c1 added. We now have 9 listener(s)
,08-26 15:43:14.475  6945  7152 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:14.475  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 15:43:14.485  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:43:14.485  6945  7152 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:43:14.485  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:14.485  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:14.485  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:14.485  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:14.485  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:14.485  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:14.485  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:14.485  6945  7152 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:14.485  6945  7152 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:43:14.485  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:14.485  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a69b1a7 added. We now have 3 listener(s)
,08-26 15:43:14.495  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-26 15:43:14.495  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:14.495  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-26 15:43:14.495  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 15:43:14.495  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 15:43:14.495  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 15:43:14.495  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214bb654 added. We now have 10 listener(s)
,08-26 15:43:14.495  6945  7152 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:14.495  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:43:14.495  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only,
08-26 15:43:14.495  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 15:43:14.495  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:43:14.495  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
,08-26 15:43:14.505  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 15:43:14.505  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 15:43:14.505  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 15:43:14.505  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 15:43:14.505  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 15:43:14.505  6945  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 15:43:14.515  3209  3225 D BtGatt.GattService: registerClient() - UUID=ac437d84-c93e-419e-a7f8-d640332fe827
,08-26 15:43:14.555  7826  7826 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,08-26 15:43:14.555  3209  3288 D BtGatt.GattService: onClientRegistered() - UUID=ac437d84-c93e-419e-a7f8-d640332fe827, clientIf=6,
,08-26 15:43:14.555  6945  6953 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
08-26 15:43:14.555  3209  3377 D BtGatt.GattService: start scan with filters
,08-26 15:43:14.565  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 15:43:14.565  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 15:43:14.565  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 15:43:14.565  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 15:43:14.565  3209  3352 D BtGatt.ScanManager: handling starting scan
,08-26 15:43:14.565  3209  3288 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-26 15:43:14.565  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:43:14.565  3209  3352 D BtGatt.ScanManager: allow scan with filters,
08-26 15:43:14.565  3209  3352 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 15:43:14.565  3209  3352 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
,08-26 15:43:14.565  3209  3288 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 15:43:14.565  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:14.565  3209  3352 D BtGatt.ScanManager: Starting BLE batch scan
08-26 15:43:14.565  3209  3352 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 15:43:14.565  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 15:43:14.565  6945  6945 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 15:43:14.565  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 15:43:14.575  3209  3288 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-26 15:43:14.575  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:14.575  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 15:43:14.575  3209  3288 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-26 15:43:14.575  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:14.595  6945  7152 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 15:43:14.595  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:43:14.595  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:43:14.595  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 15:43:14.595  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.595  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 15:43:14.595  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:14.595  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360dc7a8 removed from the list
08-26 15:43:14.595  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:14.595  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa362c1 removed from the list
,08-26 15:43:14.595  6945  7152 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:43:14.595  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 15:43:14.595  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.595  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 15:43:14.595  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:43:14.595  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 15:43:14.605  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-26 15:43:14.605  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:14.605  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:14.605  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa362c1 not in the list
08-26 15:43:14.605  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 15:43:14.605  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-26 15:43:14.605  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 15:43:14.605  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 15:43:14.605  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 15:43:14.605  3209  3225 D BtGatt.GattService: stopScan() - queue size =1
,08-26 15:43:14.605  3209  3352 D BtGatt.ScanManager: filter size is 1
,08-26 15:43:14.605  3209  3352 D BtGatt.ScanManager: delete FilterIndex - 8
,08-26 15:43:14.605  3209  3288 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
08-26 15:43:14.605  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:43:14.605  3209  3377 D BtGatt.GattService: unregisterClient() - clientIf=6
08-26 15:43:14.605  3209  3352 D BtGatt.ScanManager: stopping BLe Batch
,08-26 15:43:14.615  3209  3288 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-26 15:43:14.615  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:43:14.615  3209  3352 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-26 15:43:14.615  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:43:14.615  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-26 15:43:14.615  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 15:43:14.615  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 15:43:14.615  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 15:43:14.615  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:43:14.615  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-26 15:43:14.615  6945  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 15:43:14.615  3209  3288 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 15:43:14.615  3209  3288 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:43:14.615  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 15:43:14.615  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:14.625  6945  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 15:43:14.625  6945  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 15:43:14.625  6945  6945 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:43:14.625  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:14.625  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:14.625  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-26 15:43:14.625  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214bb654 removed from the list
08-26 15:43:14.625  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 15:43:14.625  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.625  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:14.625  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 15:43:14.625  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a69b1a7 removed from the list
08-26 15:43:14.625  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:14.625  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39d7e3c0 added. We now have 2 listener(s)
,08-26 15:43:14.635  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-26 15:43:14.635  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:14.635  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:14.635  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-26 15:43:14.635  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed0a8f9 added. We now have 9 listener(s)
,08-26 15:43:14.635  6945  7152 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:14.635  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
,08-26 15:43:14.645  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:43:14.655  6945  7152 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:43:14.655  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:14.655  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:14.655  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:14.655  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:14.655  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:14.655  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:14.655  6945  7152 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:14.655  6945  7152 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:43:14.655  6945  7152 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:43:14.655  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:14.655  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca92e9f added. We now have 3 listener(s)
,08-26 15:43:14.655  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:14.655  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-26 15:43:14.655  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:14.655  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:14.655  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:14.655  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e377bec added. We now have 10 listener(s)
08-26 15:43:14.655  6945  7152 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:14.655  6945  7152 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:43:14.655  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:43:14.655  6945  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:43:14.655  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:14.655  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.655  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:43:14.655  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:14.655  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39d7e3c0 removed from the list
08-26 15:43:14.655  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:14.655  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed0a8f9 removed from the list
,08-26 15:43:14.665  6945  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:14.665  6945  7152 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:43:14.665  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 15:43:14.665  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.665  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:14.665  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:14.665  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:14.665  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:14.665  6945  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ed0a8f9 not in the list,
08-26 15:43:14.665  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.665  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 15:43:14.665  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:14.665  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-26 15:43:14.665  6945  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:14.665  6945  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e377bec removed from the list
08-26 15:43:14.665  6945  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:14.665  6945  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-26 15:43:14.665  6945  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:14.665  6945  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:14.665  6945  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca92e9f removed from the list,
08-26 15:43:14.665  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-26 15:43:14.665  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 15:43:14.665  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything,
08-26 15:43:14.665  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:43:14.665  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 15:43:14.675  6945  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything,
,08-26 15:43:14.675  6945  7845 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1419, name: My test thread name)
08-26 15:43:14.675  6945  7845 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1419, thread name: My test thread name)
08-26 15:43:14.675  6945  7845 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1419, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 15:43:14.685  6945  7846 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1421, name: My test thread name)
,08-26 15:43:14.685  6945  7846 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1421, thread name: My test thread name)
,08-26 15:43:14.685  6945  7846 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1421, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 15:43:14.695  6945  7152 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80,
08-26 15:43:14.695  6945  7152 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 15:43:14.695  6945  7152 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 15:43:14.695  6945  7152 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-26 15:43:14.695  6945  7152 D com.test.thalitest.ThaliTestRunner: Total duration: 23295 ms
08-26 15:43:14.695  6945  7152 I jxcore-log: *Native tests were executed*,
08-26 15:43:14.695  6945  7152 I jxcore-log: 
08-26 15:43:14.695  6945  7152 I jxcore-log: Total number of executed tests:  80
08-26 15:43:14.695  6945  7152 I jxcore-log: 
08-26 15:43:14.695  6945  7152 I jxcore-log: Number of passed tests:  80
08-26 15:43:14.695  6945  7152 I jxcore-log: 
,08-26 15:43:14.695  6945  7152 I jxcore-log: Number of failed tests:  0
08-26 15:43:14.695  6945  7152 I jxcore-log: 
08-26 15:43:14.695  6945  7152 I jxcore-log: Number of ignored tests:  0
08-26 15:43:14.695  6945  7152 I jxcore-log: 
,08-26 15:43:14.695  6945  7152 I jxcore-log: Total duration:  23295,
08-26 15:43:14.695  6945  7152 I jxcore-log: 
08-26 15:43:14.695  6945  7152 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 15:43:14.695  6945  7152 I jxcore-log: 
,08-26 15:43:14.695  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:14.695  6945  7152 I jxcore-log: 
08-26 15:43:14.705  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:14.705  6945  7152 I jxcore-log: 
08-26 15:43:14.705  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:14.705  6945  7152 I jxcore-log: 
08-26 15:43:14.705  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:14.705  6945  7152 I jxcore-log: 
08-26 15:43:14.705  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:14.705  6945  7152 I jxcore-log: 
08-26 15:43:14.705  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:14.705  6945  7152 I jxcore-log: 
08-26 15:43:14.715  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:14.715  6945  7152 I jxcore-log: 
08-26 15:43:14.715  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-26 15:43:14.715  6945  7152 I jxcore-log: 
,08-26 15:43:14.715  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.715  6945  7152 I jxcore-log: 
08-26 15:43:14.715  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 15:43:14.715  6945  7152 I jxcore-log: 
08-26 15:43:14.715  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 15:43:14.715  6945  7152 I jxcore-log: 
08-26 15:43:14.715  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 15:43:14.715  6945  7152 I jxcore-log: 
08-26 15:43:14.715  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.715  6945  7152 I jxcore-log: 
,08-26 15:43:14.725  6945  6945 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 15:43:14.725  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.725  6945  7152 I jxcore-log: 
,08-26 15:43:14.725  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.725  6945  7152 I jxcore-log: 
08-26 15:43:14.725  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.725  6945  7152 I jxcore-log: 
,08-26 15:43:14.725  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.725  6945  7152 I jxcore-log: 
,08-26 15:43:14.725  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.725  6945  7152 I jxcore-log: 
,08-26 15:43:14.725  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.725  6945  7152 I jxcore-log: 
,08-26 15:43:14.725  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.725  6945  7152 I jxcore-log: 
,08-26 15:43:14.725  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 15:43:14.725  6945  7152 I jxcore-log: 
,08-26 15:43:14.725  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 15:43:14.725  6945  7152 I jxcore-log: 
08-26 15:43:14.725  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-26 15:43:14.725  6945  7152 I jxcore-log: 
08-26 15:43:14.725  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-26 15:43:14.725  6945  7152 I jxcore-log: 
08-26 15:43:14.725  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
,08-26 15:43:14.725  6945  7152 I jxcore-log: 
,08-26 15:43:14.725  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 15:43:14.725  6945  7152 I jxcore-log: 
08-26 15:43:14.725  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 15:43:14.725  6945  7152 I jxcore-log: 
,08-26 15:43:14.775   288   288 E SMD     : DCD OFF
,08-26 15:43:14.845  6945  6945 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 15:43:14.845  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 15:43:14.845  6945  7152 I jxcore-log: 
08-26 15:43:14.845  1017  1126 E WifiNative-wlan0: do suspend true
,08-26 15:43:14.875  1017  1125 D WifiP2pService: InactiveState{ what=143375 },
08-26 15:43:14.875  1017  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 15:43:14.875  1017  1126 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK,
,08-26 15:43:14.875  1017  1126 E WifiStateMachine: VerifyingLinkState enter
08-26 15:43:14.875  1017  1128 E ConnectivityService: updateNetworkInfo()
,08-26 15:43:14.885  1017  1128 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-26 15:43:14.885  1017  1128 D ConnectivityService: Adding iface wlan0 to network 504
08-26 15:43:14.885  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 15:43:14.885  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:43:14.885  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 15:43:14.885  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:14.885  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:14.885  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:14.885  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:14.885  1017  1145 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
08-26 15:43:14.885  1017  1145 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-26 15:43:14.885  1017  1145 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-26 15:43:14.885  1017  1145 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-26 15:43:14.885  1017  1145 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-26 15:43:14.895  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 15:43:14.895  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:14.895  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 15:43:14.895  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:14.895  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:43:14.895  2214  2214 I Hs20UtilService: Starting #22,
08-26 15:43:14.895  2214  2229 I Hs20UtilService: Message received 5007
08-26 15:43:14.895  4726  4726 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 15:43:14.895  4726  4726 I NearbySettings: MountReceiver.onReceive - Keep current state
08-26 15:43:14.895  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 15:43:14.895  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:43:14.895  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 15:43:14.895  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:14.895  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:14.895  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:14.895  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:14.905  1017  1126 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-26 15:43:14.915  1017  1128 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-26 15:43:14.915  1017  1128 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-26 15:43:14.915  1017  1128 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
08-26 15:43:14.915  1017  1128 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 15:43:14.915  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 15:43:14.915  1017  1128 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
,08-26 15:43:14.925  1017  1128 D ConnectivityService: LTETest block dns file not exists
,08-26 15:43:14.925  1017  1126 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 15:43:14.925  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 15:43:14.925  1017  1017 I WifiTrafficPoller: mBoosterFLAG : 0
08-26 15:43:14.925  1017  1017 I WifiTrafficPoller: current booster mode : FullMode
,08-26 15:43:14.925  1017  1126 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 15:43:14.925  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 15:43:14.925  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:43:14.925  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 15:43:14.925  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-26 15:43:14.925  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:14.925  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:14.925  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:14.935  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-26 15:43:14.935  1017  1128 V NetworkStats: updateIfacesLocked()
08-26 15:43:14.935  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 15:43:14.935  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
,08-26 15:43:14.935  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:14.935  1017  1136 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 15:43:14.935  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:14.935  1017  1136 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 15:43:14.935  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:43:14.945  1017  1128 V NetworkStats: performPollLocked() took 4ms
,08-26 15:43:14.935  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 15:43:14.935  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:14.935  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-26 15:43:14.935  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:14.945  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:14.945  1017  1136 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:14.945  1017  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:14.945  1017  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:43:14.955  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:14.955  1017  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-26 15:43:14.955  1017  1128 E ConnectivityService: updateNetworkInfo()
08-26 15:43:14.955  1017  1128 E ConnectivityService: updateNetworkInfo()
08-26 15:43:14.955  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:14.955  1017  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 15:43:14.955  2214  2214 I Hs20UtilService: Starting #23
08-26 15:43:14.955  4726  4726 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 15:43:14.955  4726  4726 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 15:43:14.955  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:14.955  1017  1128 V NetworkStats: updateIfacesLocked()
08-26 15:43:14.955  2214  2229 I Hs20UtilService: Message received 5007
08-26 15:43:14.955  1017  1128 V NetworkStats: performPollLocked(flags=0x1)
,08-26 15:43:14.955  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 15:43:14.955  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:43:14.955  1017  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 15:43:14.955  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 15:43:14.955  4726  4726 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 15:43:14.955  4726  4726 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 15:43:14.955  4726  4795 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 15:43:14.955  1017  1128 V NetworkStats: performPollLocked() took 3ms
08-26 15:43:14.955  1017  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:14.965  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:14.965  1017  1128 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-26 15:43:14.965  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:14.965  1017  1456 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 15:43:14.965  1017  7823 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:14.965  1017  1128 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-26 15:43:14.965  1017  7823 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-26 15:43:14.965  1017  1456 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 15:43:14.965  1017  7823 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:14.965  1017  1128 D ConnectivityService:    accepting network in place of null
08-26 15:43:14.965  1017  7823 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-26 15:43:14.965  1017  7823 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 15:43:14.965  1017  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-26 15:43:14.965  1017  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-26 15:43:14.965  1458  1458 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-26 15:43:14.965  1458  1458 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 15:43:14.965  1017  1456 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:14.965  1017  1456 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:14.965  1017  1456 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:43:14.975   278   995 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 15:43:14.975   278   995 D Netd    : getNetworkForDns: using netid 504 for uid 1000
08-26 15:43:14.975  1017  1128 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-26 15:43:14.975  2214  2214 I Hs20UtilService: Starting #24
08-26 15:43:14.975  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 15:43:14.975  1017  1128 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,08-26 15:43:14.975  2214  2229 I Hs20UtilService: Message received 5007
,08-26 15:43:14.975  6945  6945 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-26 15:43:14.975  4726  4726 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 15:43:14.975  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 15:43:14.975  6945  7152 I jxcore-log: 
,08-26 15:43:14.975  1017  1128 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-26 15:43:14.975  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-26 15:43:14.975  1017  1131 D Tethering: MasterInitialState.processMessage what=3
08-26 15:43:14.975  4726  4726 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-26 15:43:14.975  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:14.975  1017  1123 V NetworkStats: updateIfacesLocked(),
08-26 15:43:14.975  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:43:14.975  1017  1123 V NetworkStats: performPollLocked(flags=0x1)
08-26 15:43:14.975  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 15:43:14.985  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-26 15:43:14.985  1017  1128 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-26 15:43:14.985  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 15:43:14.985  1017  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-26 15:43:14.985  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 15:43:14.985  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-26 15:43:14.985  1017  1123 V NetworkStats: performPollLocked() took 4ms
08-26 15:43:14.985  1177  1647 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 15:43:14.985  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:14.985  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:14.985  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:14.985  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:14.985  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:14.985  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 15:43:14.985  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-26 15:43:14.985  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-26 15:43:14.985  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 23 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-26 15:43:14.985  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-26 15:43:14.985  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-26 15:43:14.985  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:43:14.985  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-26 15:43:14.985  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:14.985  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:14.985  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:14.985  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:14.985  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:14.985  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:14.995  1017  1544 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-26 15:43:14.995  7855  7855 D AndroidRuntime: 
08-26 15:43:14.995  7855  7855 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-26 15:43:14.995  1017  1030 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-26 15:43:14.995  1017  1030 D SecContentProvider2: mCursor = null
,08-26 15:43:14.995  1017  3830 D SecContentProvider2: uri = 15 selection = getToastGravity
08-26 15:43:14.995  1017  3830 D SecContentProvider2: mCursor = null
08-26 15:43:14.995  1017  1456 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-26 15:43:14.995  1017  1456 D SecContentProvider2: mCursor = null
08-26 15:43:14.995  7855  7855 D AndroidRuntime: CheckJNI is OFF
08-26 15:43:14.995  7855  7855 D AndroidRuntime: readGMSProperty: start
08-26 15:43:14.995  7855  7855 D AndroidRuntime: readGMSProperty: already setted!!
,08-26 15:43:14.995  7855  7855 D AndroidRuntime: propertySet: couldn't set property (it is from app)
,08-26 15:43:14.995  7855  7855 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
,08-26 15:43:14.995  7855  7855 D AndroidRuntime: readGMSProperty: end
08-26 15:43:14.995  7855  7855 D AndroidRuntime: addProductProperty: start
08-26 15:43:14.995  1017  1545 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-26 15:43:14.995  1017  1545 D SecContentProvider2: mCursor = null
08-26 15:43:15.005  1017  1227 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-26 15:43:15.005  1017  1227 D SecContentProvider2: mCursor = null
,08-26 15:43:15.005  1017  1503 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-26 15:43:15.005  1017  1503 D SecContentProvider2: mCursor = null
,08-26 15:43:15.025   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-26 15:43:15.035  1017  1547 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
,08-26 15:43:15.045  1177  1177 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! ,
,08-26 15:43:15.085  1017  7823 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 15:43:15.125  6945  6945 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 15:43:15.125  6945  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 15:43:15.125  6945  7152 I jxcore-log: 
,08-26 15:43:15.155  1017  7823 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 13:43:15 GMT], X-Android-Received-Millis=[1472218995154], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472218995117]}
08-26 15:43:15.155  1017  7823 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-26 15:43:15.155  1017  7823 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-26 15:43:15.155  1017  1128 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-26 15:43:15.155  1017  1128 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-26 15:43:15.155  1017  1128 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-26 15:43:15.155  1017  1128 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-26 15:43:15.155  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 15:43:15.155  1177  1647 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 15:43:15.155  7855  7855 E AffinityControl: AffinityControl: registerfunction enter
,08-26 15:43:15.175  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-26 15:43:15.175  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 15:43:15.175  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 15:43:15.175  1177  1177 D StatusBar.NetworkController: updateDataNetType()
,08-26 15:43:15.175  1177  1177 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 15:43:15.175  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-26 15:43:15.175  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-26 15:43:15.175  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 23 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-26 15:43:15.175  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
,08-26 15:43:15.175  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-26 15:43:15.175  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:43:15.175  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-26 15:43:15.175  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:15.185  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:15.185  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:15.185  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:15.185  7855  7855 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-26 15:43:15.205  1017  1503 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-26 15:43:15.205  1017  1503 D PackageManager: START PACKAGE DELETE: observer{843279639}
08-26 15:43:15.205  1017  1503 D PackageManager: pkg{<packageName>}
08-26 15:43:15.205  1017  1503 D PackageManager: user{0}
08-26 15:43:15.205  1017  1503 D PackageManager: caller{2000}
08-26 15:43:15.205  1017  1503 D PackageManager: flags{2},
08-26 15:43:15.205  1017  1503 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-26 15:43:15.205  1017  1503 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-26 15:43:15.205  1017  1503 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
08-26 15:43:15.205  1017  1503 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-26 15:43:15.215  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-26 15:43:15.215  1017  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,08-26 15:43:15.215  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-26 15:43:15.215  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
08-26 15:43:15.215  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-26 15:43:15.225  1017  1057 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,08-26 15:43:15.235  1017  1042 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,08-26 15:43:15.245  1017  1042 I ActivityManager: Killing 6945:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-26 15:43:15.345  1017  1042 I ActivityManager:   Force finishing activity ActivityRecord{eade948 u0 com.test.thalitest/.MainActivity t163}
,08-26 15:43:15.345  1017  1042 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-26 15:43:15.355  1017  1042 D InputDispatcher: Focus left window: 6945
,08-26 15:43:15.355   258  1937 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-26 15:43:15.355   258   442 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-26 15:43:15.385  1017  1042 D InputDispatcher: Focused application released,
,08-26 15:43:15.395  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 15:43:15.395  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 15:43:15.395  1017  1057 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,08-26 15:43:15.415  1017  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-26 15:43:15.445  1017  1098 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 15:43:15.445  2865  2865 I art     : Explicit concurrent mark sweep GC freed 18192(1059KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 826us total 31.492ms
,08-26 15:43:15.465  1017  1017 D RCPManagerService: PackageReceiver onReceive()
,08-26 15:43:15.465  1639  1875 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 15:43:15.465  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-26 15:43:15.465  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-26 15:43:15.465  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-26 15:43:15.465  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-26 15:43:15.465  1962  1962 E SamsungIME: mOCRHelper is null
,08-26 15:43:15.475  1017  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:43:15.485  2849  2849 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Aug 26 15:43:15 GMT+02:00 2016
,08-26 15:43:15.485  1448  1448 D PersonaManager: isKioskContainerExistOnDevice
08-26 15:43:15.495  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,08-26 15:43:15.495  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-26 15:43:15.505  1017  1123 V NetworkStats: removeUidsLocked() for UIDs [10170]
08-26 15:43:15.505  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:15.505  1017  1123 V NetworkStats: performPollLocked(flags=0x3)
,08-26 15:43:15.505  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:43:15.505  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 15:43:15.505  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:15.505  1017  1123 V NetworkStats: performPollLocked() took 4ms
,08-26 15:43:15.525  1017  1544 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-26 15:43:15.525  1017  1544 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-26 15:43:15.525  1017  1544 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:15.525  1017  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:15.525  1017  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-26 15:43:15.535  1448  1448 D RegisteredServicesCache: empty dynamic service
,08-26 15:43:15.535  2849  2849 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-26 15:43:15.555  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:15.555  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:15.555  1017  1503 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=42
08-26 15:43:15.555  1017  1503 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-26 15:43:15.555  1017  1503 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-26 15:43:15.555  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:15.555  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:15.565  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:15.565  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:15.565  2849  2849 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-26 15:43:15.565  1017  1547 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-26 15:43:15.565  1017  1547 D SecContentProvider2: mCursor = null
,08-26 15:43:15.565  2849  2849 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-26 15:43:15.575  7876  7876 E Zygote  : MountEmulatedStorage()
,08-26 15:43:15.575  7876  7876 E Zygote  : v2
08-26 15:43:15.575  7876  7876 I libpersona: KNOX_SDCARD checking this for 10090
08-26 15:43:15.575  7876  7876 I libpersona: KNOX_SDCARD not a persona
,08-26 15:43:15.575  1017  1503 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7876 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,08-26 15:43:15.575  7876  7876 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:43:15.585  2849  2849 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false,
,08-26 15:43:15.585  2849  7875 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) },
08-26 15:43:15.585  7876  7876 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 15:43:15.585  2849  7875 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-26 15:43:15.585  7876  7876 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:43:15.585  2849  7875 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,08-26 15:43:15.595  2849  7875 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-26 15:43:15.615  7876  7876 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:43:15.615  7876  7876 D ActivityThread: Added TimaKeyStore provider
,08-26 15:43:15.635  1017  1057 W art     : Suspending all threads took: 6.355ms
,08-26 15:43:15.645  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,08-26 15:43:15.645  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:15.645  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:15.645  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:15.645  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:15.655  7891  7891 E Zygote  : MountEmulatedStorage()
,08-26 15:43:15.655  7891  7891 E Zygote  : v2
08-26 15:43:15.655  7891  7891 I libpersona: KNOX_SDCARD checking this for 10052
08-26 15:43:15.655  7891  7891 I libpersona: KNOX_SDCARD not a persona
,08-26 15:43:15.655  7891  7891 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:43:15.655  1017  1042 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7891 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a,
,08-26 15:43:15.665  7891  7891 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:43:15.665  7891  7891 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-26 15:43:15.665  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,08-26 15:43:15.675  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:15.675  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:15.675  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:15.675  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:15.685  7905  7905 E Zygote  : MountEmulatedStorage()
08-26 15:43:15.685  7905  7905 E Zygote  : v2
08-26 15:43:15.685  7905  7905 I libpersona: KNOX_SDCARD checking this for 10098
08-26 15:43:15.685  7905  7905 I libpersona: KNOX_SDCARD not a persona
,08-26 15:43:15.685  7905  7905 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:43:15.695  7905  7905 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:43:15.695  7905  7905 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:43:15.695  1017  1042 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7905 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-26 15:43:15.695  7891  7891 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:43:15.705  7891  7891 D ActivityThread: Added TimaKeyStore provider
,08-26 15:43:15.705  1017  1057 I art     : Explicit concurrent mark sweep GC freed 65924(4MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 23MB/35MB, paused 10.060ms total 229.962ms
,08-26 15:43:15.715  2849  7875 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-26 15:43:15.725  7905  7905 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:43:15.725  7905  7905 D ActivityThread: Added TimaKeyStore provider
,08-26 15:43:15.725  2849  7875 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-26 15:43:15.725  2849  7875 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-26 15:43:15.735  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-26 15:43:15.735  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:15.735  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:15.735  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:15.735  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:15.745  7921  7921 E Zygote  : MountEmulatedStorage()
08-26 15:43:15.745  7921  7921 E Zygote  : v2
08-26 15:43:15.745  7921  7921 I libpersona: KNOX_SDCARD checking this for 10032
08-26 15:43:15.745  7921  7921 I libpersona: KNOX_SDCARD not a persona
,08-26 15:43:15.745  7921  7921 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:43:15.745  1017  1029 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7921 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 15:43:15.755  7921  7921 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:43:15.755  7921  7921 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-26 15:43:15.755  7876  7876 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-26 15:43:15.765  7876  7876 D elm:15121: ELMEngine.ELMEngine( context ).
,08-26 15:43:15.765  7876  7876 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-26 15:43:15.775  1448  1448 D RegisteredComponentCache: Collect Tech packages for Knox
,08-26 15:43:15.775  2849  2849 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-26 15:43:15.785  1017  1029 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,08-26 15:43:15.785  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-26 15:43:15.785  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:15.785  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:15.785  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-26 15:43:15.785  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-26 15:43:15.785  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-26 15:43:15.785  7876  7876 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-26 15:43:15.785  1448  1448 D PersonaManager: isKioskContainerExistOnDevice
,08-26 15:43:15.785  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-26 15:43:15.785  1017  1017 V EnterpriseBillingPolicy: uID is 10170
08-26 15:43:15.785  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-26 15:43:15.785  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-26 15:43:15.785  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-26 15:43:15.785  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-26 15:43:15.785  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-26 15:43:15.785  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-26 15:43:15.795  7876  7876 D elm:15121: ElmAgentService : onCreate()
,08-26 15:43:15.805  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-26 15:43:15.805  7921  7921 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:43:15.805  7921  7921 D ActivityThread: Added TimaKeyStore provider
,08-26 15:43:15.805  7876  7936 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-26 15:43:15.805  7876  7936 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-26 15:43:15.805  7876  7936 D elm:15121: MDMBridge.getInstance()
08-26 15:43:15.805  7876  7936 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-26 15:43:15.805  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 15:43:15.805  7876  7936 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-26 15:43:15.805  1017  1017 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,08-26 15:43:15.815  1017  1162 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,08-26 15:43:15.825  1017  1057 D PackageManager: delete codoeFile: 
,08-26 15:43:15.835  7876  7876 D elm:15121: ElmAgentService : onDestroy().
,08-26 15:43:15.835  1017  1136 I ActivityManager: Killing 7371:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,08-26 15:43:15.845  1017  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
08-26 15:43:15.845  1017  1057 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
08-26 15:43:15.845  1017  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-26 15:43:15.845  1017  1057 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,08-26 15:43:15.845  1017  1041 W TextServicesManagerService: no available spell checker services found
,08-26 15:43:15.845  1017  1057 D PackageManager: result of delete: 1{843279639}
,08-26 15:43:15.855  1017  1544 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,08-26 15:43:15.855  1017  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:15.855  1017  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:15.855  1017  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:15.855  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:43:15.855  1017  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:15.865  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 15:43:15.865  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 15:43:15.875  7938  7938 E Zygote  : MountEmulatedStorage()
08-26 15:43:15.875  7938  7938 E Zygote  : v2
08-26 15:43:15.875  7938  7938 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:43:15.875  7938  7938 I libpersona: KNOX_SDCARD not a persona
,08-26 15:43:15.875  7938  7938 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:43:15.875  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:43:15.875  7938  7938 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:43:15.875  7938  7938 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:43:15.875  7855  7855 D AndroidRuntime: Shutting down VM
,08-26 15:43:15.885  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-26 15:43:15.885  1017  1017 V EnterpriseBillingPolicy: uID is 10170
08-26 15:43:15.885  1017  3380 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-26 15:43:15.885  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-26 15:43:15.885  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-26 15:43:15.885  1017  1544 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7938 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 15:43:15.885  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-26 15:43:15.885  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
,08-26 15:43:15.885  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-26 15:43:15.885  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-26 15:43:15.885  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-26 15:43:15.895  1017  1136 I ActivityManager: Killing 7386:com.sec.android.fotaclient/u0a8 (adj 15): empty #21,
,08-26 15:43:15.905  7938  7938 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:43:15.915  7938  7938 D ActivityThread: Added TimaKeyStore provider
,08-26 15:43:15.925  1668  1668 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
08-26 15:43:15.925  1668  1668 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-26 15:43:15.935  7921  7954 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-26 15:43:15.935  7921  7954 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-26 15:43:15.935  1017  1546 I ActivityManager: Killing 7428:com.sec.android.soagent/u0a31 (adj 15): empty #21
,08-26 15:43:15.945  1017  1488 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
08-26 15:43:15.945  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,08-26 15:43:15.945  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:15.945  1017  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:15.955  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,08-26 15:43:15.955  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-26 15:43:15.955  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,08-26 15:43:15.955  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:15.955  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:43:15.955  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 15:43:15.955  7921  7954 D SPPClientService: PushLog.txt file is not deleted.
08-26 15:43:15.955  7921  7954 D SPPClientService: PushLog.txt file is not deleted.
08-26 15:43:15.955  7921  7954 D SPPClientService: ============PushLog. stop!
,08-26 15:43:15.965  1017  1227 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,08-26 15:43:15.965  1017  1227 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:15.965  1017  1227 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:15.965  1017  1227 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:15.965  1017  1227 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:15.975  7401  7956 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-26 15:43:15.985  7958  7958 E Zygote  : MountEmulatedStorage(),
08-26 15:43:15.985  7958  7958 I libpersona: KNOX_SDCARD checking this for 10039
,08-26 15:43:15.985  7958  7958 E Zygote  : v2
08-26 15:43:15.985  7958  7958 I libpersona: KNOX_SDCARD not a persona
08-26 15:43:15.985  7958  7958 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:43:15.985  1017  1128 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-26 15:43:15.985  7958  7958 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:43:15.985  1017  1227 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7958 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
08-26 15:43:15.985  7958  7958 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:43:16.005  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,08-26 15:43:16.005  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-26 15:43:16.005  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:16.005  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:43:16.005  7958  7958 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:43:16.005  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-26 15:43:16.005  7958  7958 D ActivityThread: Added TimaKeyStore provider
,08-26 15:43:16.015  1017  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-26 15:43:16.015  1017  1307 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,08-26 15:43:16.015  1017  1307 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-26 15:43:16.015  1017  1307 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:16.015  1017  1307 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:43:16.015  1017  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
08-26 15:43:16.025  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 15:43:16.025  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 15:43:16.025  1017  3830 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,08-26 15:43:16.025  1017  3830 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.025  1017  3830 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.025  1017  3830 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.025  1017  3830 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:16.025  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 15:43:16.035  7958  7958 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-26 15:43:16.035  7958  7958 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 15:43:16.035  7958  7958 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 15:43:16.035  7958  7958 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,08-26 15:43:16.035  1017  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-26 15:43:16.035  1017  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 15:43:16.035  1017  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 15:43:16.035  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:43:16.035  7958  7958 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-26 15:43:16.035  7958  7958 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-26 15:43:16.035  7958  7958 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-26 15:43:16.035  7401  7956 D AccountUtils: Clearing selected account for com.test.thalitest
,08-26 15:43:16.035  7975  7975 E Zygote  : MountEmulatedStorage()
08-26 15:43:16.035  7975  7975 E Zygote  : v2
08-26 15:43:16.035  7975  7975 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:43:16.035  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:43:16.035  7975  7975 I libpersona: KNOX_SDCARD not a persona
08-26 15:43:16.045  7975  7975 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:43:16.045  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 15:43:16.045  7975  7975 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:43:16.045  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:43:16.045  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-26 15:43:16.045  7975  7975 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:43:16.045  1017  3830 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7975 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 15:43:16.045  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 15:43:16.055  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 15:43:16.055  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-26 15:43:16.065  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 15:43:16.065  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-26 15:43:16.065  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 15:43:16.065  1017  1488 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:43:16.075  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:16.075  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:43:16.075  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:43:16.075  7975  7975 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:43:16.075  7975  7975 D ActivityThread: Added TimaKeyStore provider
,08-26 15:43:16.075  1017  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-26 15:43:16.095  7855  7855 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-26 15:43:16.095  1017  3829 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:43:16.095  1017  3829 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:16.095  1017  3829 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:43:16.095  1017  3829 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 15:43:16.095  1017  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-26 15:43:16.095  1017  1545 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:43:16.095  1017  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:43:16.105  1017  1545 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
,08-26 15:43:16.105  7211  7211 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,08-26 15:43:16.105  1017  1545 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:16.105  1017  1545 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:43:16.105  1017  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:43:16.105  1017  1545 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,08-26 15:43:16.105  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.105  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.105  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.105  1017  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:16.125  7994  7994 E Zygote  : MountEmulatedStorage(),
08-26 15:43:16.125  7994  7994 E Zygote  : v2
08-26 15:43:16.125  7994  7994 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:43:16.125  7994  7994 I libpersona: KNOX_SDCARD not a persona
,08-26 15:43:16.125  1017  1545 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=7994 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 15:43:16.125  7401  7956 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-26 15:43:16.135  1017  3829 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-26 15:43:16.135  1017  3829 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
,08-26 15:43:16.135  1017  3829 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:16.135  1017  3829 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:43:16.135  1017  3829 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 15:43:16.145  7994  7994 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:43:16.145  7994  7994 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:43:16.145  7994  7994 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:43:16.145   305   305 I art     : Explicit concurrent mark sweep GC freed 8710(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 635us total 23.085ms
,08-26 15:43:16.155  1017  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-26 15:43:16.155  1017  1057 D PackageManager: userId{-1}
08-26 15:43:16.155  1017  1057 D PackageManager: andCode{true}
,08-26 15:43:16.165  7211  7211 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
08-26 15:43:16.165  7211  7211 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,08-26 15:43:16.165  7211  7211 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
,08-26 15:43:16.165  7211  7211 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-26 15:43:16.165  7211  7211 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,08-26 15:43:16.165  7211  7211 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-26 15:43:16.165   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 703us total 17.883ms
08-26 15:43:16.165  7211  7211 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-26 15:43:16.165  7211  7211 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
08-26 15:43:16.165  7211  7211 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
,08-26 15:43:16.175  1017  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-26 15:43:16.175  7211  7211 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
,08-26 15:43:16.175  7211  7211 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-26 15:43:16.175  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.175  7994  7994 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:43:16.175  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.175  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.185  7211  7211 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-26 15:43:16.175  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.185  7994  7994 D ActivityThread: Added TimaKeyStore provider
08-26 15:43:16.185  7211  7211 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-26 15:43:16.185  7211  7211 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-26 15:43:16.185  7211  7211 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
,08-26 15:43:16.185  7211  7211 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
08-26 15:43:16.185  7211  7211 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
,08-26 15:43:16.185  7401  7401 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-26 15:43:16.185  7211  7211 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-26 15:43:16.185  7211  7211 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-26 15:43:16.185  7211  7211 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-26 15:43:16.185  7211  7211 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,08-26 15:43:16.185  7211  7211 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
08-26 15:43:16.185  7401  7401 D ChimeraModuleLdr: Loading module APK com.google.android.play.games
08-26 15:43:16.185  7211  7211 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
08-26 15:43:16.185  7211  7211 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,08-26 15:43:16.185   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 606us total 17.517ms
,08-26 15:43:16.195  7211  7211 D BluetoothAdapter: cancelDiscovery
,08-26 15:43:16.205  8015  8015 E Zygote  : MountEmulatedStorage()
08-26 15:43:16.205  8015  8015 E Zygote  : v2
,08-26 15:43:16.205  8015  8015 I libpersona: KNOX_SDCARD checking this for 10003
08-26 15:43:16.205  8015  8015 I libpersona: KNOX_SDCARD not a persona
,08-26 15:43:16.205  8015  8015 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:43:16.205  8015  8015 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:43:16.205  8015  8015 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:43:16.215  1017  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8015 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-26 15:43:16.215  1017  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:43:16.225  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:16.225  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:43:16.225  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:43:16.225  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:43:16.225  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,08-26 15:43:16.225  7975  7975 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,08-26 15:43:16.235  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:16.235  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:43:16.235  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:43:16.235  1017  1546 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
08-26 15:43:16.235  1017  1546 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,08-26 15:43:16.235  3209  3291 D BluetoothAdapterProperties: mDiscovering is false
08-26 15:43:16.235  3209  3291 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
,08-26 15:43:16.235  1017  1546 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:16.235  1017  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:16.235  1017  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
08-26 15:43:16.245  7211  7211 D BluetoothAdapter: cancelDiscovery = true
,08-26 15:43:16.245  7211  7211 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,08-26 15:43:16.245  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-26 15:43:16.245  7211  7211 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-26 15:43:16.245  7211  7211 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-26 15:43:16.255  3209  3286 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 15:43:16.255  1017  1503 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,08-26 15:43:16.255  7401  8008 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,08-26 15:43:16.255  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.255  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.255  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.255  1017  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:16.265  8015  8015 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:43:16.265  8015  8015 D ActivityThread: Added TimaKeyStore provider
,08-26 15:43:16.275  7401  8008 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2,
,08-26 15:43:16.275  7994  7994 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
,08-26 15:43:16.275  7401  8008 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
08-26 15:43:16.275  7401  8008 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
08-26 15:43:16.275  8035  8035 E Zygote  : MountEmulatedStorage()
08-26 15:43:16.275  8035  8035 E Zygote  : v2
08-26 15:43:16.275  8035  8035 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:43:16.275  8035  8035 I libpersona: KNOX_SDCARD not a persona
,08-26 15:43:16.275  1017  1503 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=8035 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 15:43:16.285  8035  8035 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-26 15:43:16.285  8035  8035 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:43:16.295  8035  8035 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:43:16.305  7401  8008 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
08-26 15:43:16.305  7401  8008 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,08-26 15:43:16.325  1017  3829 I ActivityManager: Killing 7461:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-26 15:43:16.325  7401  8008 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,08-26 15:43:16.325  8035  8035 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:43:16.325  8035  8035 D ActivityThread: Added TimaKeyStore provider
,08-26 15:43:16.335  1017  1136 I ActivityManager: Killing 7483:com.android.chrome/u0a77 (adj 15): empty #21
,08-26 15:43:16.335  7211  7211 E SQLiteLog: (10) unixWrite() File Descriptor : 26 gets errno : 9
,08-26 15:43:16.345  7401  8008 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,08-26 15:43:16.345  7401  8008 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,08-26 15:43:16.345  7401  8008 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,08-26 15:43:16.345  7401  8008 E SQLiteLog: (3850) statement aborts at 25: [DELETE FROM suggestions WHERE app_package_name="com.test.thalitest"] disk I/O error
,08-26 15:43:16.355  7401  8008 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
08-26 15:43:16.355  7211  7211 E SQLiteDatabase: Error inserting timestamp=1472218996247 message=Predictor: service stopped by removePlaceCategories()
08-26 15:43:16.355  7211  7211 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
08-26 15:43:16.355  7211  7211 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-26 15:43:16.355  7211  7211 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-26 15:43:16.355  7211  7211 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-26 15:43:16.355  7211  7211 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-26 15:43:16.355  7211  7211 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-26 15:43:16.355  7211  7211 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-26 15:43:16.355  7211  7211 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
08-26 15:43:16.355  7211  7211 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
08-26 15:43:16.355  7211  7211 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 15:43:16.355  7211  7211 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 15:43:16.355  7211  7211 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:43:16.355  7211  7211 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:43:16.355  7211  7211 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:43:16.355  7211  7211 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:43:16.355  7211  7211 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:43:16.355  7211  7211 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:43:16.355  7211  7211 E UserAnalysis: It failed to insert to dump_log table
08-26 15:43:16.355  1017  3829 D LocationManagerService: getProviders()=[passive, gps]
,08-26 15:43:16.365  7994  7994 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/lowpowercontext-system-db" with flag (131138) and mode_t (0) due to error (30)
,08-26 15:43:16.365  7994  7994 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/lowpowercontext-system-db'.
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f$b.a(DataStore.java:2443)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(DataStore.java:85)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextProvider.onCreate(LowpowerContextProvider.java:303)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:43:16.365  7994  7994 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 15:43:16.365  7401  8008 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
08-26 15:43:16.365  7401  8008 E AndroidRuntime: Process: com.google.android.gms, PID: 7401
08-26 15:43:16.365  7401  8008 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 15:43:16.365  7401  8008 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 15:43:16.365  7401  8008 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
08-26 15:43:16.365  7401  8008 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 15:43:16.365  7401  8008 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 15:43:16.365  7401  8008 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
08-26 15:43:16.365  7401  8008 E AndroidRuntime: 	at com.google.android.gms.googlehelp.search.b.e(SourceFile:105)
08-26 15:43:16.365  7401  8008 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:53)
08-26 15:43:16.365  7401  8008 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-26 15:43:16.365  7401  8008 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:43:16.365  7401  8008 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:43:16.365  7401  8008 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 15:43:16.365  1017  1136 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,08-26 15:43:16.375  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-26 15:43:16.375  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.375  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.375  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.375  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:16.375  7994  7994 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/sm.db" with flag (131138) and mode_t (0) due to error (30)
,08-26 15:43:16.385  1017  8053 E DropBoxManagerService: Can't write: system_app_crash
08-26 15:43:16.385  1017  8053 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop196.tmp: open failed: EROFS (Read-only file system)
08-26 15:43:16.385  1017  8053 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-26 15:43:16.385  1017  8053 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 15:43:16.385  1017  8053 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 15:43:16.385  1017  8053 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 15:43:16.385  1017  8053 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-26 15:43:16.385  1017  8053 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
08-26 15:43:16.385  1017  8053 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 15:43:16.385  1017  8053 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 15:43:16.385  1017  8053 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 15:43:16.385  1017  8053 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-26 15:43:16.385  1017  8053 E DropBoxManagerService: 	... 5 more
,08-26 15:43:16.395  7994  7994 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/sm.db'.,
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318),
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
,08-26 15:43:16.395  7994  7994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: ,	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: 	at com.samsung.android.sm.database.b.<init>(SmDatabaseHelper.java:65)
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: 	at com.samsung.android.sm.database.b.a(SmDatabaseHelper.java:54),
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: 	at com.samsung.android.sm.database.SmProvider.onCreate(SmProvider.java:89)
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698),
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: ,	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:43:16.395  7994  7994 E SQLiteDatabase: 	,at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:43:16.395  7994  7994 D AndroidRuntime: Shutting down VM
08-26 15:43:16.395  1017  1042 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=8055 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 15:43:16.395  7994  7994 E AndroidRuntime: FATAL EXCEPTION: main,
08-26 15:43:16.395  7994  7994 E AndroidRuntime: Process: com.samsung.android.sm, PID: 7994,
08-26 15:43:16.395  7994  7994 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.samsung.android.sm.database.SmProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 15:43:16.395  7994  7994 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
,08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at com.samsung.android.sm.database.b.<init>(SmDatabaseHelper.java:65)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at com.samsung.android.sm.database.b.a(SmDatabaseHelper.java:54)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at com.samsung.android.sm.database.SmProvider.onCreate(SmProvider.java:89)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-26 15:43:16.395  7994  7994 E AndroidRuntime: 	... 11 more
,08-26 15:43:16.395  1017  1136 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup,
08-26 15:43:16.395  7401  8008 I Process : Sending signal. PID: 7401 SIG: 9
08-26 15:43:16.405  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:16.405  7958  7958 D NearbySource: Nearby Source Create!
,08-26 15:43:16.405  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.405  7958  7958 D NearbyContext: Nearby Context Create!
,08-26 15:43:16.405  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.405  1017  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:16.415  8055  8055 E Zygote  : MountEmulatedStorage()
08-26 15:43:16.415  8055  8055 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:43:16.415  8055  8055 E Zygote  : v2
08-26 15:43:16.415  8055  8055 I libpersona: KNOX_SDCARD not a persona
,08-26 15:43:16.415  8055  8055 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:43:16.415  8055  8055 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:43:16.425  8055  8055 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:43:16.425  8035  8056 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED
,08-26 15:43:16.425  8035  8056 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 

```
