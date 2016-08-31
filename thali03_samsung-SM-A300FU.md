#### Test 832760828839a22_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
08-31 11:29:16.010  1847  1847 I ConfigFetchService: stopping self
08-31 11:29:16.010  6325  6325 D Mms/MmsConfig:  enable multiwindow = false
08-31 11:29:16.040  6325  6325 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-31 11:29:16.040  6325  6325 E Mms/MessageUtils: updateCountryIso : update country iso info 
08-31 11:29:16.040  6325  6325 D Mms/MmsConfig: [end]    init() consume time = 256.423958
08-31 11:29:16.040  6325  6325 D Mms/Contact: [start]    init() consume time = 0.789636
08-31 11:29:16.060  1018  1322 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:16.060  1018  1322 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:16.060  1018  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
--------- beginning of system
08-31 11:29:16.060  1018  1494 I ActivityManager: Killing 5414:com.google.android.music:main/u0a108 (adj 15): empty #21
08-31 11:29:16.060  1018  1322 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-31 11:29:16.070  1018  1720 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:16.070  1018  1720 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:16.070  1018  1720 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-31 11:29:16.070  1018  1720 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 11:29:16.070  1018  1720 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-31 11:29:16.080  6325  6325 D Mms/Contact: [end]    init consume time = 40.712239
08-31 11:29:16.080  1018  1322 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-31 11:29:16.090  1018  1322 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:16.090  1018  1322 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:16.090  1018  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-31 11:29:16.090  1458  1488 D TP/MmsSmsProvider: query,matched:13, calling pid = 6325
08-31 11:29:16.090  1458  1488 D TP/MmsSmsProvider: match 13:Elapsed time : 1.636 ms
08-31 11:29:16.110  6325  6549 D Mms/DraftCache: [start]    rebuildCache consume time = 28.726979
08-31 11:29:16.120  1458  2484 D TP/MmsSmsProvider: query,matched:12, calling pid = 6325
08-31 11:29:16.120  1458  2484 D TP/MmsSmsProvider: match 12:Elapsed time : 2.065 ms
08-31 11:29:16.120  6325  6549 D Mms/DraftCache: [end]    rebuildCache consume time = 9.886615
08-31 11:29:16.130  1018  1218 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 11:29:16.130  1018  1218 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-31 11:29:16.130  1018  1218 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:16.130  1018  1218 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:16.130  1018  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-31 11:29:16.130  6325  6325 D Mms/MethodReflector: getSubId is called
08-31 11:29:16.130  6325  6325 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-31 11:29:16.130  6325  6325 D Mms/MethodReflector: getTelephonyProperty is called
08-31 11:29:16.130  6325  6325 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-31 11:29:16.130  6325  6325 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-31 11:29:16.130  6325  6325 D Mms/DownloadManager: auto download without roaming -> true
08-31 11:29:16.140  6325  6325 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-31 11:29:16.140  6325  6325 D Mms/MethodReflector: getSubId is called
08-31 11:29:16.140  6325  6325 D Mms/MethodReflector: getDefaultSmsSubId is called
08-31 11:29:16.140  6325  6325 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
08-31 11:29:16.140  6325  6325 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
08-31 11:29:16.140  6325  6325 D Mms/MethodReflector: getTelephonyProperty is called
08-31 11:29:16.140  6325  6325 D Mms/DownloadManager: roaming -> false (slotId = 1)
08-31 11:29:16.140  6325  6325 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-31 11:29:16.140  6325  6325 D Mms/DownloadManager: auto download without roaming -> true
08-31 11:29:16.140  6325  6325 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-31 11:29:16.140  6325  6325 D Mms/DownloadManager: auto download during roaming secondary -> false
08-31 11:29:16.140  6325  6325 D Mms/DownloadManager: mAutoDownload ------> true
08-31 11:29:16.140  1018  1494 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-31 11:29:16.150  1018  1494 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:16.150  1018  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:16.150  1018  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-31 11:29:16.160  1018  1730 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-31 11:29:16.160  1018  1730 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:16.160  1018  1730 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:16.160  1018  1730 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
08-31 11:29:16.170  1018  1136 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-31 11:29:16.180  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:16.180  1018  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:16.180  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-31 11:29:16.180  1018  1720 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 11:29:16.180  1018  1720 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-31 11:29:16.190  1018  1720 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:16.190  1018  1720 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:16.190  1018  1720 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-31 11:29:16.190  6325  6502 D Mms/ArtClassLoader: init [DONE] art
08-31 11:29:16.200  1018  1136 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-31 11:29:16.200  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:16.200  1018  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:16.200  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-31 11:29:16.200  6325  6325 D ComposerPerformance: 1472635756208 ms / [DONE] Composer constructor
08-31 11:29:16.200  6325  6325 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
08-31 11:29:16.200  6325  6325 I Mms/ReservationManager: ReservationManager()
08-31 11:29:16.200  6325  6325 I Mms/ReservationManager: resetAfterConnected()
08-31 11:29:16.210  1458  2484 D TP/MmsSmsProvider: query,matched:7, calling pid = 6325
08-31 11:29:16.210  6325  6553 D Mms/Conversation: [start]    init() consume time = 90.791146
08-31 11:29:16.210  1458  2484 D TP/MmsSmsProvider: match 7:Elapsed time : 4.541 ms
08-31 11:29:16.210  1458  2039 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-31 11:29:16.220  1458  2039 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-31 11:29:16.220  1458  2039 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
08-31 11:29:16.220  1458  2039 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
08-31 11:29:16.220  1458  2039 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-31 11:29:16.220  1458  2039 D TP/MmsSmsProvider: need read changed broadcast:false
08-31 11:29:16.220  6325  6553 D Mms/Conversation: [end]    init consume time = 11.580416
08-31 11:29:16.230  6325  6325 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
08-31 11:29:16.230  6325  6553 D Mms/MessagingNotification: [start]    init() consume time = 4.442136
08-31 11:29:16.230  6325  6325 D Mms/MmsApp: [end]    onCreate() consume time = 0.74875
08-31 11:29:16.230  6325  6553 D Mms/MessagingNotification: [end]    init consume time = 2.117135
08-31 11:29:16.230  6325  6554 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 1.873438
08-31 11:29:16.230  6325  6555 D Mms/Synchronizer: [start]    doSync consume time = 1.446771
08-31 11:29:16.230  1458  2676 D TP/MmsSmsProvider: query,matched:0, calling pid = 6325
08-31 11:29:16.230  1458  2676 V TP/MmsSmsProvider: getSimpleConversations entered.
08-31 11:29:16.240  1458  2676 D TP/MmsSmsProvider: match 0:Elapsed time : 1.878 ms
08-31 11:29:16.240  1458  1479 D TP/MmsSmsProvider: update, matched:300, calling pid = 6325
08-31 11:29:16.240  1458  1479 V TP/MmsSmsProvider: syncDBData start
08-31 11:29:16.240  1458  1479 V TP/MmsSmsProvider: syncDBData sms end
08-31 11:29:16.240  1458  1479 V TP/MmsSmsProvider: syncDBData mms end
08-31 11:29:16.240  1458  1479 V TP/MmsSmsProvider: syncDBData end
08-31 11:29:16.240  6325  6555 D Mms/Synchronizer: [end]    doSync consume time = 7.809218
08-31 11:29:16.240  1458  2039 D TP/MmsSmsProvider: query,matched:400, calling pid = 6325
08-31 11:29:16.250  1018  1489 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
08-31 11:29:16.250  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:16.250  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:16.250  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:16.250  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:16.260  6325  6325 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
08-31 11:29:16.260  6556  6556 E Zygote  : MountEmulatedStorage()
08-31 11:29:16.260  6556  6556 E Zygote  : v2
08-31 11:29:16.260  6556  6556 I libpersona: KNOX_SDCARD checking this for 10068
08-31 11:29:16.260  6556  6556 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:16.260  6325  6325 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
08-31 11:29:16.260  6556  6556 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:29:16.260  6325  6325 D Mms/MethodReflector: getSubId is called
08-31 11:29:16.260  6325  6325 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-31 11:29:16.270  6325  6325 D Mms/MethodReflector: getTelephonyProperty is called
08-31 11:29:16.270  6325  6325 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-31 11:29:16.270  6556  6556 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:16.270  6325  6325 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-31 11:29:16.270  6325  6325 D Mms/DownloadManager: auto download without roaming -> true
08-31 11:29:16.270  6325  6325 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-31 11:29:16.270  6325  6325 D Mms/DownloadManager: mAutoDownload ------> true
08-31 11:29:16.270  6556  6556 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-31 11:29:16.280  1018  1489 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6556 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-31 11:29:16.290  6325  6554 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 47.914844
08-31 11:29:16.290  6556  6556 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 11:29:16.290  6556  6556 D ActivityThread: Added TimaKeyStore provider
08-31 11:29:16.300  6325  6325 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
08-31 11:29:16.300  1018  1320 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-31 11:29:16.300  1018  1320 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
08-31 11:29:16.300  1018  1320 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:16.300  1018  1320 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:16.300  1018  1320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
08-31 11:29:16.310  1018  1322 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 11:29:16.310  1018  1322 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-31 11:29:16.310  1018  1322 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:16.310  1018  1322 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:16.310  1018  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-31 11:29:16.320  1018  1490 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
08-31 11:29:16.320  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:16.320  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:16.320  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:16.320  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:16.330  6571  6571 E Zygote  : MountEmulatedStorage()
08-31 11:29:16.330  6571  6571 E Zygote  : v2
08-31 11:29:16.330  6571  6571 I libpersona: KNOX_SDCARD checking this for 10042
08-31 11:29:16.330  6571  6571 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:16.330  6571  6571 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:29:16.340  6571  6571 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:16.340  6571  6571 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
08-31 11:29:16.340  1018  1490 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6571 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
08-31 11:29:16.340  6556  6556 D BadgeProvider: onCreate
08-31 11:29:16.340  6556  6556 D BadgeProvider: DatabaseHelper
08-31 11:29:16.350  6325  6579 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
08-31 11:29:16.350  6325  6579 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
08-31 11:29:16.350  1018  1496 I ActivityManager: Killing 6031:com.android.calendar/u0a131 (adj 15): empty #21
08-31 11:29:16.350  1018  1496 I ActivityManager: Killing 6132:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #22
08-31 11:29:16.380  6310  6366 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 640 ms] updated apps [took 640 ms] 
08-31 11:29:16.380  6571  6571 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 11:29:16.380  6571  6571 D ActivityThread: Added TimaKeyStore provider
08-31 11:29:16.380  1018  3256 I ActivityManager: Killing 6195:com.android.defcontainer/u0a3 (adj 15): empty #21
08-31 11:29:16.500   287   287 E SMD     : DCD OFF
08-31 11:29:16.540  1018  1494 I art     : Explicit concurrent mark sweep GC freed 144468(8MB) AllocSpace objects, 3(1847KB) LOS objects, 33% free, 22MB/34MB, paused 2.533ms total 175.233ms
08-31 11:29:16.560  6325  6553 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
08-31 11:29:16.560  1018  1136 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-31 11:29:16.560  1458  2039 D TP/SmsProvider: query,matched:26, calling pid = 6325
08-31 11:29:16.560  1458  2039 D TP/SmsProvider: match 26:Elapsed time : 0.882 ms
08-31 11:29:16.580  1458  1488 D TP/MmsSmsProvider: query,matched:6, calling pid = 6325
08-31 11:29:16.580  1458  1488 D TP/MmsSmsProvider: match 6:Elapsed time : 1.493 ms
08-31 11:29:16.600  6571  6571 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-31 11:29:16.600  6571  6571 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-31 11:29:16.600  6571  6571 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-31 11:29:16.630  1018  1496 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
08-31 11:29:16.630  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:16.630  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:16.630  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:16.630  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:16.640  1018  1496 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6590 uid=10023 gids={50023, 9997} abi=armeabi-v7a
08-31 11:29:16.640  6590  6590 E Zygote  : MountEmulatedStorage()
08-31 11:29:16.640  6590  6590 E Zygote  : v2
08-31 11:29:16.640  6590  6590 I libpersona: KNOX_SDCARD checking this for 10023
08-31 11:29:16.640  6590  6590 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:16.640  6590  6590 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:29:16.650  6590  6590 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:16.650  6590  6590 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 11:29:16.670  6590  6590 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 11:29:16.680  6590  6590 D ActivityThread: Added TimaKeyStore provider
08-31 11:29:16.680  1018  3256 I ActivityManager: Killing 5889:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
08-31 11:29:16.700  6571  6571 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-31 11:29:16.710  1018  1489 I ActivityManager: Killing 6242:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
08-31 11:29:16.710  1018  1056 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
08-31 11:29:16.710  1018  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-31 11:29:16.710  1018  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:16.710  1018  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:16.710  1018  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:16.710  1018  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:16.720  6605  6605 E Zygote  : MountEmulatedStorage()
08-31 11:29:16.720  6605  6605 E Zygote  : v2
08-31 11:29:16.720  6605  6605 I libpersona: KNOX_SDCARD checking this for 10003
08-31 11:29:16.720  6605  6605 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:16.720  6605  6605 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:29:16.720  1018  1056 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6605 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-31 11:29:16.730  6605  6605 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:16.730  6605  6605 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 11:29:16.750  6605  6605 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 11:29:16.750  6605  6605 D ActivityThread: Added TimaKeyStore provider
08-31 11:29:16.760  6590  6590 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
08-31 11:29:16.770  6430  6506 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-31 11:29:16.770  6430  6506 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-31 11:29:16.770  6430  6506 I GAv4    :   adb logcat -s GAv4
,08-31 11:29:16.780  6325  6553 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
08-31 11:29:16.790   283   283 E installd: system dir 0 : /system/app/
08-31 11:29:16.790   283   283 E installd: system dir 1 : /system/priv-app/
08-31 11:29:16.790   283   283 E installd: system dir 2 : /vendor/app/
08-31 11:29:16.790   283   283 E installd: system dir 3 : /oem/app/
08-31 11:29:16.800  6590  6590 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
08-31 11:29:16.800  6590  6590 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-31 11:29:16.800  6590  6590 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
08-31 11:29:16.800  6590  6590 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
08-31 11:29:16.800  6590  6590 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
08-31 11:29:16.800  6590  6590 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
08-31 11:29:16.810  6590  6590 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
08-31 11:29:16.810  6590  6590 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
08-31 11:29:16.810  6590  6590 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
08-31 11:29:16.810  6590  6590 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
08-31 11:29:16.810  6590  6590 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
08-31 11:29:16.810  6590  6590 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
08-31 11:29:16.810  6590  6590 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
08-31 11:29:16.810  1018  1056 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-31 11:29:16.830  6430  6506 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-31 11:29:16.830  1018  1730 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-31 11:29:16.850  6430  6506 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
08-31 11:29:16.860  6430  6626 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
08-31 11:29:16.860  6430  6506 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
08-31 11:29:17.040  6623  6623 D AndroidRuntime: 
08-31 11:29:17.040  6623  6623 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 11:29:17.040  6623  6623 D AndroidRuntime: CheckJNI is OFF
08-31 11:29:17.040  6623  6623 D AndroidRuntime: readGMSProperty: start
08-31 11:29:17.040  6623  6623 D AndroidRuntime: readGMSProperty: already setted!!
08-31 11:29:17.040  6623  6623 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-31 11:29:17.040  6623  6623 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 11:29:17.040  6623  6623 D AndroidRuntime: readGMSProperty: end
08-31 11:29:17.040  6623  6623 D AndroidRuntime: addProductProperty: start
08-31 11:29:17.080  1018  1494 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
08-31 11:29:17.080  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:17.080  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:17.080  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:17.080  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:17.100  6639  6639 E Zygote  : MountEmulatedStorage()
08-31 11:29:17.100  6639  6639 E Zygote  : v2
08-31 11:29:17.100  6639  6639 I libpersona: KNOX_SDCARD checking this for 1000
08-31 11:29:17.100  6639  6639 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:17.110  6639  6639 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:29:17.110  1018  1494 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=6639 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-31 11:29:17.110  1018  1494 I ActivityManager: Killing 6254:com.sec.spp.push/u0a32 (adj 15): empty #21
08-31 11:29:17.110  6639  6639 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:17.130   309   309 I art     : Explicit concurrent mark sweep GC freed 8709(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 614us total 22.585ms
08-31 11:29:17.130  6639  6639 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 11:29:17.150   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 580us total 16.921ms
08-31 11:29:17.160  6639  6639 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 11:29:17.160  6639  6639 D ActivityThread: Added TimaKeyStore provider
08-31 11:29:17.170   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 16.867ms
08-31 11:29:17.180  6639  6639 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
08-31 11:29:17.190  6430  6631 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-31 11:29:17.190  1018  1218 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:17.190  6430  6631 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-31 11:29:17.190  1018  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:17.190  6639  6639 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
08-31 11:29:17.190  1018  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
08-31 11:29:17.190  1018  1218 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
08-31 11:29:17.190  6623  6623 E AffinityControl: AffinityControl: registerfunction enter
08-31 11:29:17.190  1018  1218 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
08-31 11:29:17.190  1018  1489 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
08-31 11:29:17.200  1018  1018 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
08-31 11:29:17.200  1018  1018 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
08-31 11:29:17.210  1018  1387 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:17.210  1018  1387 D AlarmManagerService: Setting time of day to sec=1472635757
08-31 11:29:17.210  1018  1387 D AlarmManagerService: Trying to open a file
08-31 11:29:17.220  6639  6639 I FilterInstaller: FilterPackageService : ACTION_CHANGED
08-31 11:29:17.220  1018  1387 D AlarmManagerService: File Open Success
08-31 11:29:17.220  1018  1387 D AlarmManagerService: File Close Success
08-31 11:29:17.220  1018  1387 I AlarmManagerService: DRM_TIME_PATH CHMOD 666 for resetState done 
08-31 11:29:17.427  1018  1096 V AlarmManager: waitForAlarm result :65536
08-31 11:29:17.427  1018  1387 W AlarmManagerService: Unable to set rtc to 1472635757: Invalid argument
08-31 11:29:17.427  6623  6623 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-31 11:29:17.427  1018  1096 V AlarmManager: No more alarm at this time.nowELAPSED=95757 batch.start=109081
08-31 11:29:17.427  1018  1018 I BackgroundCompactionService: onStart. jobID=801
08-31 11:29:17.436  1190  1190 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
08-31 11:29:17.436  1190  1190 D KeyguardUpdateMonitor: handleTimeUpdate
08-31 11:29:17.436  6639  6655 E FilterInstaller: installFilters
08-31 11:29:17.436  6639  6655 E FilterInstaller: There is no requred permission
08-31 11:29:17.446  1018  1018 I BackgroundCompactionService: onStart done. jobID=801
08-31 11:29:17.446  1018  1018 D OTPFW   : OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1472635757457
08-31 11:29:17.446  1018  6658 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
08-31 11:29:17.446  1018  6658 I BackgroundCompactionService: compact_memory command done
08-31 11:29:17.446  6430  6631 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
08-31 11:29:17.446  1190  1190 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
08-31 11:29:17.456  1018  1030 E PersonaManagerService: inState():  stateMachine is null !!
08-31 11:29:17.456  1190  1190 D SecKeyguardClockView: HomeTimezone(): 1
08-31 11:29:17.456  1018  1018 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
08-31 11:29:17.456  1018  1018 I DowntimeConditions: android.intent.action.TIME_SET ignored because schedule turned off.
08-31 11:29:17.456  1018  1030 I PersonaManagerService: PersonaId don't exist
08-31 11:29:17.456  1018  1030 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-31 11:29:17.466  1190  1190 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-31 11:29:17.466  1190  1190 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
08-31 11:29:17.466  1190  1190 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_SET
08-31 11:29:17.476  1190  1190 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-31 11:29:17.476  1190  1190 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-31 11:29:17.476  1190  1190 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-31 11:29:17.486  1018  1018 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:29:17.486  1018  3256 I ActivityManager: Killing 5022:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
08-31 11:29:17.496  1190  1190 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
08-31 11:29:17.496  1018  1730 D SettingsProvider: name = lockscreen_zoom_panning_effect
08-31 11:29:17.496  1018  1730 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:17.496  1018  1730 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:17.496  1018  1730 D SettingsProvider: selectionArgs: false
08-31 11:29:17.496  1018  1730 D SettingsProvider: selectionArgs: 10049
08-31 11:29:17.496  1018  1730 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:17.496  1018  1730 D SettingsProvider: ret = -1
08-31 11:29:17.526  1018  1018 I DrmEventService:  no response from SecureClock 
08-31 11:29:17.526  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-31 11:29:17.536  6430  6631 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-31 11:29:17.536  6430  6631 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@11b86c07: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-31 11:29:17.546  6430  6631 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-31 11:29:17.546  1018  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-31 11:29:17.546  1018  1320 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4180, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-31 11:29:17.546  1018  1320 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-31 11:29:17.546  1018  1320 D BatteryService: stay LED for charging
08-31 11:29:17.546  1018  1030 W ActivityManager: mDVFSHelper.acquire()
08-31 11:29:17.556  1018  1730 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10049
08-31 11:29:17.556  1018  1030 D FocusedStackFrame: Set to : 0
08-31 11:29:17.556  1190  1190 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
08-31 11:29:17.556  1190  1190 D KeyguardEffectViewController: isPreloadedWallpaper=true
08-31 11:29:17.566  1190  1190 I GeometricMosaic_Keyguard: update
08-31 11:29:17.566  1190  1190 D KeyguardEffectViewUtil: getCurrentWallpaper() mWallpaperPath :null
08-31 11:29:17.566  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:17.566  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:17.566  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:17.566  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:17.566  1018  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-31 11:29:17.566  1018  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-31 11:29:17.576  6662  6662 E Zygote  : MountEmulatedStorage()
08-31 11:29:17.576  6662  6662 I libpersona: KNOX_SDCARD checking this for 10170
08-31 11:29:17.576  6662  6662 E Zygote  : v2
08-31 11:29:17.576  6662  6662 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:17.576  6662  6662 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:29:17.586  6662  6662 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:17.586  1018  1030 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6662 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-31 11:29:17.586  1847  3977 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
08-31 11:29:17.586  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-31 11:29:17.586  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-31 11:29:17.586  1018  1030 D InputDispatcher: Focused application set to: xxxx
08-31 11:29:17.586  6662  6662 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-31 11:29:17.586  1018  1030 D InputDispatcher: Focus left window: 1491
08-31 11:29:17.586  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-31 11:29:17.586  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-31 11:29:17.586   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-31 11:29:17.596  6623  6623 D AndroidRuntime: Shutting down VM
08-31 11:29:17.596  1018  1018 I splitIntent: intent=android.intent.action.TIME_SET will be not split. because same process=com.google.android.gms is in other queue. index=4
08-31 11:29:17.596  1018  1018 I splitIntent: base  index=4, name=com.google.android.gms com.google.android.gms.checkin.CheckinService$Receiver
08-31 11:29:17.596  1018  1018 I splitIntent: other index=7, name=com.google.android.gms com.google.android.gms.reminders.notification.NotificationReceiver
08-31 11:29:17.596  1018  1018 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.TIME_SET !! do not split it!!
08-31 11:29:17.606  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-31 11:29:17.606  6662  6662 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 11:29:17.606  6662  6662 D ActivityThread: Added TimaKeyStore provider
08-31 11:29:17.606  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-31 11:29:17.606  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-31 11:29:17.616  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 11:29:17.616  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 11:29:17.616  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
08-31 11:29:17.616  2788  2788 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 11:29:17.616  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:17.626  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:17.626  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:17.626  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:17.626  2788  2915 D HeadsetStateMachine: Disconnected process message: 10
08-31 11:29:17.636  6677  6677 E Zygote  : MountEmulatedStorage()
08-31 11:29:17.636  6677  6677 I libpersona: KNOX_SDCARD checking this for 10008
08-31 11:29:17.636  6677  6677 E Zygote  : v2
08-31 11:29:17.636  6677  6677 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:17.636  6677  6677 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:29:17.646  6677  6677 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:17.646  6677  6677 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-31 11:29:17.656  1018  1018 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6677 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 11:29:17.656  1018  1018 I MotionRecognitionService: Plugged
08-31 11:29:17.656  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-31 11:29:17.666  1018  1030 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-31 11:29:17.666  1018  1018 V ActivityManager: Display changed displayId=0
08-31 11:29:17.666  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-31 11:29:17.686  6677  6677 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 11:29:17.686  6677  6677 D ActivityThread: Added TimaKeyStore provider
08-31 11:29:17.696  1018  1030 D PersonaManager: isKioskContainerExistOnDevice
08-31 11:29:17.696  1190  1190 I KeyguardEffectViewUtil: set current wallpaper info
08-31 11:29:17.696  1018  1320 D SettingsProvider: name = keyguard_current_wallpaper_type
08-31 11:29:17.706  1018  1320 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:17.706  1018  1320 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:17.706  1018  1320 D SettingsProvider: selectionArgs: false
08-31 11:29:17.706  1018  1320 D SettingsProvider: selectionArgs: 10049
08-31 11:29:17.706  1018  1320 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:17.706  1018  1320 D SettingsProvider: ret = -1
08-31 11:29:17.706  1018  1320 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10049
08-31 11:29:17.716  1018  1030 D SettingsProvider: name = keyguard_current_wallpaper_file_path
08-31 11:29:17.716  1018  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:17.716  1018  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:17.716  1018  1030 D SettingsProvider: selectionArgs: false
08-31 11:29:17.716  1018  1030 D SettingsProvider: selectionArgs: 10049
08-31 11:29:17.716  1018  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:17.716  1018  1030 D SettingsProvider: ret = -1
08-31 11:29:17.716  1018  1730 D SettingsProvider: name = keyguard_current_wallpaper_res_id
08-31 11:29:17.716  1018  1730 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:17.716  1018  1730 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:17.716  1018  1730 D SettingsProvider: selectionArgs: false
08-31 11:29:17.716  1018  1730 D SettingsProvider: selectionArgs: 10049
08-31 11:29:17.716  1018  1730 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:17.716  1018  1730 D SettingsProvider: ret = -1
08-31 11:29:17.726  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-31 11:29:17.746  1018  2890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-31 11:29:17.746   257   454 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
08-31 11:29:17.746   257  1098 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
08-31 11:29:17.756  1491  1491 D Launcher: onTrimMemory. Level: 20
08-31 11:29:17.756  1491  1491 V ActivityThread: updateVisibility : ActivityRecord{34bd3136 token=android.os.BinderProxy@c77bdfd {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-31 11:29:17.756  6339  6365 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
08-31 11:29:17.786  6339  6365 I AcmsKeyStoreHelper: Key Store exist
08-31 11:29:17.786  6339  6365 I AcmsKeyStoreHelper: Hence loading the keystore file
08-31 11:29:17.786  1847  3977 D Icing   : Loaded CLD2 Version V2.0 - 20141016
08-31 11:29:17.806  6623  6623 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-31 11:29:17.816  1190  1606 D TEST    : run!!!
,08-31 11:29:17.816  1190  1190 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-31 11:29:17.826  1190  1190 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-31 11:29:17.826  1190  1190 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-31 11:29:17.826  1190  1190 D SViewCoverView: level :100 plugged : 2
,08-31 11:29:17.826  1190  1606 I GeometricMosaic_Renderer: setBackgroundBitmap
,08-31 11:29:17.826  1190  1190 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 11:29:17.826  1190  1190 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-31 11:29:17.826  1190  1190 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 11:29:17.836  1190  1190 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-31 11:29:17.836  1190  1190 D KeyguardEffectViewController: isPreloadedWallpaper=true
08-31 11:29:17.836  1190  1190 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 11:29:17.846  6677  6677 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-31 11:29:17.846  6662  6662 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-31 11:29:17.856  6677  6677 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,08-31 11:29:17.856  6339  6365 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
08-31 11:29:17.856  6339  6365 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-31 11:29:17.856  6339  6365 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-31 11:29:17.856  6339  6365 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-31 11:29:17.856  6339  6365 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-31 11:29:17.856  6339  6365 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,08-31 11:29:17.856  6339  6365 D AcmsCore: This is NOT a valid MirrorLink app
08-31 11:29:17.856  6339  6365 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-31 11:29:17.856  6339  6365 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-31 11:29:17.856  6339  6365 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-31 11:29:17.856  6339  6365 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,08-31 11:29:17.866  6339  6339 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-31 11:29:17.866  6339  6339 D AcmsService: Enter onDestroy
08-31 11:29:17.866  6339  6339 I AcmsService: cleanUp(): inside service clean up
08-31 11:29:17.866  6339  6339 D AcmsCore: AcmsCore: inside DeInit
08-31 11:29:17.866  6339  6339 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
08-31 11:29:17.866  6339  6339 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
08-31 11:29:17.866  6339  6339 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-31 11:29:17.866  6339  6339 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-31 11:29:17.866  6339  6339 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,08-31 11:29:17.866  6339  6339 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-31 11:29:17.866  6339  6339 D AcmsService: killing acms process
08-31 11:29:17.866  6339  6339 I Process : Sending signal. PID: 6339 SIG: 9
,08-31 11:29:17.866  1018  1322 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 11:29:17.866  1018  1322 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,08-31 11:29:17.866  1018  1322 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:17.866  1018  1322 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:17.866  1018  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:17.876  6662  6662 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 6211-6214)
,08-31 11:29:17.876  6662  6662 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-31 11:29:17.896  6662  6662 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {24cc4649}
,08-31 11:29:17.896  6662  6662 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-31 11:29:17.896  6662  6662 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 11:29:17.906  1847  3977 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
,08-31 11:29:17.906  1018  1031 I ActivityManager: Killing 6290:com.samsung.helphub/1000 (adj 15): empty #21
,08-31 11:29:17.916  1018  1136 I ActivityManager: Process ACMS.Process (pid 6339)(adj 0) has died(39,771)
,08-31 11:29:17.926  1018  1322 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 11:29:17.926  1018  1322 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,08-31 11:29:17.926  1018  1322 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:17.926  1018  1322 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:17.926  1018  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:17.926  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-31 11:29:17.926  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:17.926  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:17.926  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:17.936  2928  2928 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Wed Aug 31 11:29:17 GMT+02:00 2016
,08-31 11:29:17.936  1018  1496 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-31 11:29:17.936  1018  1496 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-31 11:29:17.936  1018  1496 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:17.936  1018  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:17.936  6662  6662 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-31 11:29:17.936  1018  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-31 11:29:17.936  6662  6662 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 11:29:17.946  2928  2928 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-31 11:29:17.946  1018  1322 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
08-31 11:29:17.946  6662  6662 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 11:29:17.946  1018  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:17.946  1018  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:17.946  1018  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:17.946  1018  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:17.956  2928  2928 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-31 11:29:17.956  2928  2928 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-31 11:29:17.966  2928  2928 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-31 11:29:17.966  6662  6662 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 11:29:17.966  6662  6662 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 11:29:17.966  6662  6662 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 11:29:17.966  6662  6662 I Adreno-EGL: Local Branch: 
08-31 11:29:17.966  6662  6662 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 11:29:17.966  6662  6662 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 11:29:17.966  6662  6662 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-31 11:29:17.966  6703  6703 I libpersona: KNOX_SDCARD checking this for 10036
08-31 11:29:17.966  6703  6703 E Zygote  : MountEmulatedStorage()
08-31 11:29:17.966  6703  6703 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:17.966  6703  6703 E Zygote  : v2
,08-31 11:29:17.966  6703  6703 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:17.966  6703  6703 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:17.966  1018  1322 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=6703 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 11:29:17.966  6703  6703 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-31 11:29:17.966  2928  6698 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,08-31 11:29:17.966  2928  6698 I KLMS-2.5.123: : KLMSIntentService(): TIME_CHANGED
,08-31 11:29:17.976  2928  6698 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().START : Wed Aug 31 11:29:17 GMT+02:00 2016
,08-31 11:29:17.976  1018  1494 I ActivityManager: Killing 6263:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,08-31 11:29:17.986  2928  6698 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().END
,08-31 11:29:17.986  2928  2928 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-31 11:29:17.996  6703  6703 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:17.996  6703  6703 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:18.036  6703  6703 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@b1be611
,08-31 11:29:18.036  6662  6662 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-31 11:29:18.046  6703  6703 I SA      : [SSP] onCreated
,08-31 11:29:18.056  6662  6662 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-31 11:29:18.056  6662  6662 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-31 11:29:18.066  6703  6703 I SA      : [TPM] There is no property file
,08-31 11:29:18.066  6662  6662 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-31 11:29:18.066  6662  6662 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-31 11:29:18.066  6703  6703 I SA      : [SCU] isHaveSA() - false
,08-31 11:29:18.066  6703  6703 I SA      : [TPM] getModelProperty : null
08-31 11:29:18.066  6703  6703 I SA      : [TPM] getCSCProperty : null
,08-31 11:29:18.066  6703  6703 I SA      : [DM] FLOATING AMOLED FEATURE: true
,08-31 11:29:18.066  6703  6703 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-31 11:29:18.066  6703  6703 I SA      : [DM] TFT FEATURE: false
,08-31 11:29:18.076  6703  6703 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
08-31 11:29:18.076  6703  6703 I SA      : [DM] init START
,08-31 11:29:18.086  6703  6703 I SA      : [DM] This device is not a Vodafone
,08-31 11:29:18.086  6703  6703 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-31 11:29:18.086  6703  6703 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-31 11:29:18.096  6703  6703 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-31 11:29:18.096  6703  6703 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-31 11:29:18.096  6703  6703 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-31 11:29:18.096  6703  6703 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-31 11:29:18.096  6703  6703 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-31 11:29:18.096  6703  6703 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-31 11:29:18.096  6703  6703 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-31 11:29:18.096  6703  6703 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-31 11:29:18.096  6703  6703 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-31 11:29:18.106  6703  6703 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-31 11:29:18.106  6703  6703 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-31 11:29:18.106  6703  6703 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-31 11:29:18.106  6703  6703 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-31 11:29:18.106  6703  6703 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-31 11:29:18.106  6703  6703 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,08-31 11:29:18.106  6703  6703 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-31 11:29:18.106  6703  6703 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-31 11:29:18.106  6703  6703 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-31 11:29:18.106  6703  6703 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-31 11:29:18.106  6703  6703 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-31 11:29:18.106  6703  6703 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-31 11:29:18.106  6703  6703 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-31 11:29:18.106  6703  6703 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-31 11:29:18.106  6703  6703 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-31 11:29:18.106  6703  6703 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-31 11:29:18.116  6703  6703 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-31 11:29:18.116  6703  6703 I SA      : [SCU] isHaveSA() - false
08-31 11:29:18.116  6703  6703 I SA      : support phone number id : false
08-31 11:29:18.116  6703  6703 I SA      : [DM] Supports Ref Jpn : true
,08-31 11:29:18.116  6703  6703 I SA      : [DM] init END
,08-31 11:29:18.176  1018  3255 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,08-31 11:29:18.176  1018  3255 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:18.176  1018  3255 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:18.186  1018  3255 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:18.186  1018  3255 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:18.196  6736  6736 E Zygote  : MountEmulatedStorage(),
08-31 11:29:18.196  6736  6736 E Zygote  : v2
,08-31 11:29:18.196  6736  6736 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:18.196  1018  3255 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6736 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 11:29:18.196  6736  6736 I libpersona: KNOX_SDCARD checking this for 10058
08-31 11:29:18.196  6736  6736 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:18.196  1018  3255 I ActivityManager: Killing 5494:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,08-31 11:29:18.196  6736  6736 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:18.196  6736  6736 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:18.196  1018  1043 W ActivityManager: Activity pause timeout for ActivityRecord{2602a496 u0 com.test.thalitest/.MainActivity t163}
,08-31 11:29:18.206  6662  6662 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 11:29:18.216  6662  6662 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-31 11:29:18.226  6662  6662 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-31 11:29:18.226  6662  6662 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-31 11:29:18.236  6736  6736 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:18.236  6736  6736 D ActivityThread: Added TimaKeyStore provider
08-31 11:29:18.236  6662  6662 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-31 11:29:18.246  6662  6662 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-31 11:29:18.246  6662  6662 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 11:29:18.286  6736  6736 I ExternalOEMControlProvider: onCreate
,08-31 11:29:18.296  6662  6754 D OpenGLRenderer: Render dirty regions requested: true
,08-31 11:29:18.296  1018  1320 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-31 11:29:18.306  1018  1320 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-31 11:29:18.306  1018  1320 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-31 11:29:18.306  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-31 11:29:18.306  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,08-31 11:29:18.306  6736  6753 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,08-31 11:29:18.306  6662  6723 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-31 11:29:18.306  6662  6662 V ActivityThread: updateVisibility : ActivityRecord{28b69d29 token=android.os.BinderProxy@372a5862 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-31 11:29:18.316  1018  1218 I ActivityManager: Killing 5838:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-31 11:29:18.316  6662  6662 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-31 11:29:18.316  6662  6662 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-31 11:29:18.316  1891  1891 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,08-31 11:29:18.316  1891  1891 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-31 11:29:18.316  1018  1322 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,08-31 11:29:18.326  1018  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:18.326  1018  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:18.326  1018  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:18.326  1018  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:18.336  6759  6759 E Zygote  : MountEmulatedStorage()
,08-31 11:29:18.336  6759  6759 E Zygote  : v2
08-31 11:29:18.336  6759  6759 I libpersona: KNOX_SDCARD checking this for 10081
08-31 11:29:18.336  6759  6759 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:18.336  6759  6759 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:18.336  1018  1322 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6759 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 11:29:18.336  6759  6759 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:18.336  6759  6759 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:18.336   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-31 11:29:18.346  1018  1322 D InputDispatcher: Focus entered window: 6662
,08-31 11:29:18.356  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-31 11:29:18.356  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 11:29:18.356  6662  6662 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-31 11:29:18.356  6662  6754 I OpenGLRenderer: Initialized EGL, version 1.4
,08-31 11:29:18.366  6662  6754 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-31 11:29:18.366  6662  6754 D OpenGLRenderer: Enabling debug mode 0
,08-31 11:29:18.366  6759  6759 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:18.366  6759  6759 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:18.386  6759  6759 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-31 11:29:18.386  6759  6759 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-31 11:29:18.386  6759  6759 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:29:18.386  6759  6759 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-31 11:29:18.386  6759  6759 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,08-31 11:29:18.406  1018  1720 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false,
,08-31 11:29:18.406  1190  1190 D PanelView: There is/are notification(s) 
,08-31 11:29:18.406  1018  6775 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 11:29:18.426  1018  1048 I ActivityManager: Displayed Component not be shown by security: +723ms (total +858ms)
,08-31 11:29:18.426  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2602a496 u0 com.test.thalitest/.MainActivity t163} time:96761
08-31 11:29:18.426  1018  1048 W ActivityManager: mDVFSHelper.release()
,08-31 11:29:18.426  6325  6325 I Mms/MmsApp:  start initViewCache mms
08-31 11:29:18.426  6325  6325 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1938.923124
,08-31 11:29:18.426   257   452 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-31 11:29:18.426   257  1098 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-31 11:29:18.436  6662  6662 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-31 11:29:18.436  6662  6662 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@372a5862 time:96772
,08-31 11:29:18.436  6325  6325 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-31 11:29:18.446  1973  1973 I SamsungIME: getCurrentCandidateView
,08-31 11:29:18.466  1018  3256 D SettingsProvider: name = next_alarm_formatted
08-31 11:29:18.466  1018  3256 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:18.466  1018  3256 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:18.466  1018  3256 D SettingsProvider: selectionArgs: false
08-31 11:29:18.466  1018  3256 D SettingsProvider: selectionArgs: 10081
08-31 11:29:18.466  1018  3256 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:18.466  1018  3256 D SettingsProvider: ret = -1
,08-31 11:29:18.556  6325  6325 D AbsListView: Get MotionRecognitionManager
,08-31 11:29:18.566  1018  1496 D MotionRecognitionService:  ssp status : false
,08-31 11:29:18.566  6325  6325 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 142.621198
,08-31 11:29:18.576  6662  6662 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6662
,08-31 11:29:18.606  6759  6759 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 129.537ms
,08-31 11:29:18.636  1973  1973 D SamsungIME: Dismiss ExpandCandiate
,08-31 11:29:18.666  6325  6325 D Mms/BubbleViewCache: fillCache bubble = 1
,08-31 11:29:18.706  1018  1320 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-31 11:29:18.716  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:18.716  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:18.716  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:18.716  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:18.726  6784  6784 E Zygote  : MountEmulatedStorage()
,08-31 11:29:18.726  6784  6784 E Zygote  : v2
08-31 11:29:18.726  6784  6784 I libpersona: KNOX_SDCARD checking this for 10090
08-31 11:29:18.726  6784  6784 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:18.726  6784  6784 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 11:29:18.726  1018  1320 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6784 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,08-31 11:29:18.736  6784  6784 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:18.736  1018  1320 I ActivityManager: Killing 6374:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,08-31 11:29:18.736  6784  6784 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-31 11:29:18.766  6784  6784 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:18.766  6784  6784 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:18.796  6784  6784 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,08-31 11:29:18.796  6784  6784 D elm:15121: ELMEngine.ELMEngine( context ).
,08-31 11:29:18.796  6784  6784 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-31 11:29:18.806  1018  1494 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,08-31 11:29:18.806  1018  1494 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-31 11:29:18.806  1018  1494 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:18.806  1018  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:18.806  1018  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-31 11:29:18.806  6784  6784 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,08-31 11:29:18.806  1018  3255 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,08-31 11:29:18.806  6784  6784 D elm:15121: ElmAgentService : onCreate()
,08-31 11:29:18.806  6784  6800 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,08-31 11:29:18.816  1018  3255 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:18.816  1018  3255 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:18.816  1018  3255 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:18.816  1018  3255 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:18.816  1973  1973 I SamsungIME: getDebugLevel  : 0x4f4c
,08-31 11:29:18.816  6784  6800 D elm:15121: ELMAgentService.listeningToTimeDateChanges( context, intent ).
,08-31 11:29:18.826  6784  6784 D elm:15121: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,08-31 11:29:18.826  6784  6784 D elm:15121: ModuleBase.ModifySetAlarm()
08-31 11:29:18.826  6784  6784 D elm:15121: MDMBridge.getInstance()
08-31 11:29:18.826  6784  6784 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-31 11:29:18.836  6802  6802 E Zygote  : MountEmulatedStorage(),
,08-31 11:29:18.836  6802  6802 E Zygote  : v2
,08-31 11:29:18.836  6802  6802 I libpersona: KNOX_SDCARD checking this for 10130
08-31 11:29:18.836  6802  6802 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:18.836  6802  6802 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:29:18.836  1018  3255 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6802 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,08-31 11:29:18.846  6802  6802 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:18.846  6662  6662 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-31 11:29:18.846  6802  6802 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-31 11:29:18.866  6802  6802 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:18.866  6802  6802 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:18.876  6784  6784 D elm:15121: ElmAgentService : onDestroy().
,08-31 11:29:18.876  1018  1136 I ActivityManager: Killing 6392:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,08-31 11:29:18.886  6802  6802 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-31 11:29:18.886  6802  6802 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-31 11:29:18.896  1973  1973 I SamsungIME: getDebugLevel  : 0x4f4c
,08-31 11:29:18.896  1018  1494 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,08-31 11:29:18.896  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:18.896  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:18.896  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:18.906  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:18.916  1973  1973 I SamsungIME: KeybaordView init() : load resources
,08-31 11:29:18.916  6817  6817 E Zygote  : MountEmulatedStorage(),
08-31 11:29:18.916  6817  6817 E Zygote  : v2
,08-31 11:29:18.916  6817  6817 I libpersona: KNOX_SDCARD checking this for 10131
08-31 11:29:18.916  6817  6817 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:18.916  6817  6817 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:29:18.916  1018  1494 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6817 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-31 11:29:18.926  1018  1494 I ActivityManager: Killing 6430:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-31 11:29:18.926  6817  6817 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:18.926  6817  6817 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:18.946  6662  6777 D jxcore_app_log: JniHelper::setJavaVM(0xb7b8e2b0), pthread_self() = -1206797600
,08-31 11:29:18.946  1973  1973 I SamsungIME: getCurrentKeyboard
,08-31 11:29:18.946  1973  1973 I SamsungIME: getTextKeyboard
,08-31 11:29:18.956  6662  6777 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 11:29:18.956  6662  6777 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 11:29:18.956  6662  6777 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 11:29:18.956  6662  6777 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 11:29:18.956  6662  6777 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-31 11:29:18.956  6662  6777 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fc5a047 added. We now have 1 listener(s)
,08-31 11:29:18.956  6817  6817 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:18.956  6817  6817 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:18.956  6662  6777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,08-31 11:29:18.956  6662  6777 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-31 11:29:18.966  6662  6777 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 11:29:18.966  6662  6777 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 11:29:18.966  1973  1973 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-31 11:29:18.966  6662  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 11:29:18.966  6662  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 11:29:18.966  6662  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 11:29:18.966  6662  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-31 11:29:18.966  6662  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 11:29:18.966  6662  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 11:29:18.966  6662  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 11:29:18.966  6662  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 11:29:18.966  6662  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 11:29:18.966  6662  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 11:29:18.966  6662  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 11:29:18.966  6662  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 11:29:18.966  6662  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 11:29:18.966  6662  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-31 11:29:18.966  6662  6777 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@121d9e12 added. We now have 1 listener(s)
,08-31 11:29:18.966  6662  6777 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:29:18.966  6817  6817 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-31 11:29:18.966  6817  6817 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 11:29:18.976  6817  6817 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-31 11:29:18.976  6662  6777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:29:18.976  6662  6777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-31 11:29:18.976  6662  6777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 11:29:18.976  6662  6777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 11:29:18.976  6662  6777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-31 11:29:18.986  6662  6777 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:29:18.986  6662  6777 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,08-31 11:29:18.996  6662  6777 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-31 11:29:18.996  6662  6777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:18.996  6662  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:18.996  6662  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:18.996  6662  6777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:18.996  6662  6777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:18.996  6662  6777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:18.996  6662  6777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:18.996  6662  6777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:29:18.996  6662  6777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 11:29:18.996  6662  6777 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:29:18.996  6662  6777 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 11:29:18.996  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:18.996  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:19.016  2702  2707 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-31 11:29:19.016  1018  3256 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
08-31 11:29:19.016  1018  3256 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-31 11:29:19.016  1018  3256 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:19.026  1018  3256 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:19.026  1018  3256 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-31 11:29:19.026  6662  6662 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 11:29:19.056  1018  1490 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
08-31 11:29:19.056  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-31 11:29:19.056  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:19.056  1018  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:19.056  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-31 11:29:19.056  1018  1030 D ActivityManager: getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,08-31 11:29:19.066  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:19.066  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:19.066  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:19.066  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:19.076  6840  6840 E Zygote  : MountEmulatedStorage()
08-31 11:29:19.076  6840  6840 I libpersona: KNOX_SDCARD checking this for 10037
08-31 11:29:19.076  6840  6840 E Zygote  : v2
08-31 11:29:19.076  6840  6840 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:19.076  6840  6840 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:19.076  1018  1030 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6840 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 11:29:19.076  6840  6840 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-31 11:29:19.076  1018  1730 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
08-31 11:29:19.076  6840  6840 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-31 11:29:19.086  1018  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:19.086  1018  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:19.086  1018  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:19.086  1018  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:19.096  6849  6849 E Zygote  : MountEmulatedStorage()
08-31 11:29:19.096  6849  6849 I libpersona: KNOX_SDCARD checking this for 1000
08-31 11:29:19.096  6849  6849 E Zygote  : v2
08-31 11:29:19.096  6849  6849 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:19.096  6849  6849 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-31 11:29:19.106  1018  1730 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.DateTimeChangedReceiver: pid=6849 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-31 11:29:19.106  6849  6849 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:19.106  6849  6849 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:19.116  6840  6840 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:19.116  6840  6840 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:19.136  6849  6849 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:19.136  6849  6849 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:19.146  6840  6840 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,08-31 11:29:19.166  6849  6849 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 11:29:19.166  6849  6849 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 11:29:19.166  6849  6849 D SecurityLogAgent: StateMachine : Current State = 1
,08-31 11:29:19.176  1018  1490 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,08-31 11:29:19.176  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:19.176  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:19.176  6840  6840 I CalendarProvider2: CalendarProvider2.onCreate() called
08-31 11:29:19.176  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-31 11:29:19.176  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:19.186  6871  6871 E Zygote  : MountEmulatedStorage()
,08-31 11:29:19.186  6871  6871 E Zygote  : v2
08-31 11:29:19.186  6871  6871 I libpersona: KNOX_SDCARD checking this for 10153
08-31 11:29:19.186  6871  6871 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:19.186  1018  1490 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=6871 uid=10153 gids={50153, 9997} abi=armeabi-v7a
08-31 11:29:19.196  6871  6871 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:19.196  6871  6871 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:19.196  1018  1490 I ActivityManager: Killing 6413:com.google.android.partnersetup/u0a14 (adj 15): empty #21
08-31 11:29:19.196  6871  6871 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:19.216  6871  6871 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:19.216   309   309 I art     : Explicit concurrent mark sweep GC freed 8673(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 766us total 25.120ms
08-31 11:29:19.216  6871  6871 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:19.236   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 639us total 16.964ms
,08-31 11:29:19.236   271   271 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb88a17c8
08-31 11:29:19.236   271   271 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
08-31 11:29:19.236   271   271 I rmt_storage: wakelock acquired: 1, error no: 42
08-31 11:29:19.236   271   338 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1198910152)
,08-31 11:29:19.246  6871  6871 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-31 11:29:19.246   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 16.732ms
,08-31 11:29:19.256  1018  1136 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,08-31 11:29:19.266  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:19.266  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:19.266  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:19.266  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:19.276  6887  6887 E Zygote  : MountEmulatedStorage()
08-31 11:29:19.276  6887  6887 I libpersona: KNOX_SDCARD checking this for 1000
08-31 11:29:19.276  6887  6887 E Zygote  : v2
08-31 11:29:19.276  6887  6887 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:19.286  6887  6887 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:29:19.286  1018  1136 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6887 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-31 11:29:19.286  6887  6887 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:19.286  1018  1136 I ActivityManager: Killing 6451:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
08-31 11:29:19.286  6887  6887 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:19.306   271   338 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
,08-31 11:29:19.306   271   338 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-31 11:29:19.306   271   338 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1198910152) wakelock released: 1, error no: 0
08-31 11:29:19.306   271   338 I rmt_storage: 
,08-31 11:29:19.316   271   271 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb88a17c8
,08-31 11:29:19.316  6887  6887 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:19.316  6887  6887 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:19.326  1018  3256 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
08-31 11:29:19.326  1018  3256 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,08-31 11:29:19.326  1018  3256 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:19.326  1018  3256 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:19.326  1018  3256 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-31 11:29:19.376  6887  6887 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1472635759387
08-31 11:29:19.376  6887  6887 D         : TimeServiceNative: User Time to be set is 1472635759387
08-31 11:29:19.376  6887  6887 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
08-31 11:29:19.376  6887  6887 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-31 11:29:19.376  6887  6887 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1472635759387
08-31 11:29:19.376  6887  6887 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-31 11:29:19.376   327   551 D QC-time-services: Daemon: Connection accepted:time_genoff
,08-31 11:29:19.376   327  6906 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1472635759387
08-31 11:29:19.376   327  6906 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1472635759387, operation = 0
,08-31 11:29:19.376   327  6906 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS1/26/71 3:12:7
08-31 11:29:19.376   327  6906 D QC-time-services: Daemon:Value read from RTC seconds = 36385927000
08-31 11:29:19.376   327  6906 D QC-time-services: Daemon:new time 1472635759387 
08-31 11:29:19.376   327  6906 D QC-time-services: Daemon: delta 1436249832387 genoff 1436249832387 
08-31 11:29:19.376   327  6906 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249832387 to memory
08-31 11:29:19.376   327  6906 D QC-time-services: Daemon:Opening File: /data/time/ats_2
08-31 11:29:19.376   327  6906 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-31 11:29:19.406   327  6906 D QC-time-services: Updating the TOD offset
08-31 11:29:19.406   327  6906 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249832387 to memory
08-31 11:29:19.406   327  6906 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-31 11:29:19.406   327  6906 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-31 11:29:19.406   327  6906 E QC-time-services: Daemon:Update to modem bit set,
08-31 11:29:19.406   327  6906 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
08-31 11:29:19.406   327  6906 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120285032387
,08-31 11:29:19.406   327   549 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
08-31 11:29:19.406   327   551 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
08-31 11:29:19.406  6887  6887 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,08-31 11:29:19.406  1018  1494 I ActivityManager: Killing 6461:com.sec.pcw.device/1000 (adj 15): empty #21
,08-31 11:29:19.416  2702  2702 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,08-31 11:29:19.426  2702  2702 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,08-31 11:29:19.426  2702  2702 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-31 11:29:19.486  1018  1489 I art     : Explicit concurrent mark sweep GC freed 20772(1169KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 22MB/34MB, paused 2.462ms total 137.432ms
,08-31 11:29:19.486  2702  2702 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-31 11:29:19.496  2702  2702 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
08-31 11:29:19.496  2702  2702 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
08-31 11:29:19.496  2702  2702 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-31 11:29:19.496  2702  2702 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
08-31 11:29:19.496  2702  2702 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-31 11:29:19.496  2702  2702 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-31 11:29:19.496  2702  2702 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
08-31 11:29:19.496  2702  2702 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
08-31 11:29:19.506  2702  2702 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
08-31 11:29:19.516  1018  1720 I ActivityManager: Killing 5770:com.android.vending/u0a26 (adj 15): empty #21
08-31 11:29:19.516  2702  2702 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
08-31 11:29:19.516  2702  2702 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
08-31 11:29:19.516  2702  2702 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
08-31 11:29:19.516  2702  2702 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
08-31 11:29:19.516  2702  2702 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,08-31 11:29:19.526  2702  2702 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,08-31 11:29:19.526  2702  2702 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,08-31 11:29:19.686  6662  6834 W jxcore-log: Initializing JXcore engine
08-31 11:29:19.686  6662  6834 W jxcore-log: JXcore engine is ready
,08-31 11:29:19.706   287   287 E SMD     : DCD OFF
,08-31 11:29:19.746  1969  1969 E audit   : type=1400 msg=audit(1472635759.746:205): avc:  denied  { ioctl } for  pid=6834 comm="Thread-1245" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-31 11:29:19.746  1969  1969 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:19.746  1969  1969 E audit   : type=1300 msg=audit(1472635759.746:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9ddf38f8 items=0 ppid=309 ppcomm=main pid=6834 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1245" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-31 11:29:19.746  1969  1969 E audit   : type=1320 msg=audit(1472635759.746:205): 
,08-31 11:29:19.756  6662  6834 W jxcore-log: Starting JXcore engine
,08-31 11:29:19.876  6662  6834 W jxcore-log: Platform android
08-31 11:29:19.876  6662  6834 W jxcore-log: 
,08-31 11:29:19.876  6662  6834 W jxcore-log: Process ARCH arm
08-31 11:29:19.876  6662  6834 W jxcore-log: 
,08-31 11:29:20.086  6662  6834 I jxcore-log: JXcore Cordova bridge is ready!
08-31 11:29:20.086  6662  6834 I jxcore-log: 
,08-31 11:29:20.086  6662  6834 W jxcore-log: JXcore engine is started
,08-31 11:29:20.086  6662  6777 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-31 11:29:20.096  6662  6662 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 11:29:20.326  6840  6840 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,08-31 11:29:20.336  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:20.336  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:20.336  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,08-31 11:29:20.336  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:20.336  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:20.336  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,08-31 11:29:20.346  1018  1720 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,08-31 11:29:20.346  1018  1720 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:20.346  1018  1720 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:20.346  1018  1720 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-31 11:29:20.346  1018  1031 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-31 11:29:20.346  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-31 11:29:20.356  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:20.356  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:20.356  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-31 11:29:20.356  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:20.356  1018  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:20.356  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,08-31 11:29:20.366  1018  1320 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-31 11:29:20.366  1018  1320 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-31 11:29:20.366  1018  1320 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:20.366  1018  1320 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:20.366  1018  1320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-31 11:29:20.376  1018  1031 I ActivityManager: Killing 6507:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,08-31 11:29:21.276  1681  1681 I ConfigService: onDestroy
,08-31 11:29:22.706   287   287 E SMD     : DCD OFF,
,08-31 11:29:24.646  1018  2869 D SSRM:n  : SIOP:: AP = 400
,08-31 11:29:25.706   287   287 E SMD     : DCD OFF,
,08-31 11:29:27.056  1018  1056 D PackageManager: [MSG] MCS_UNBIND
,08-31 11:29:27.066  1018  1490 I ActivityManager: Killing 6526:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-31 11:29:27.566  1018  1056 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-31 11:29:27.586  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 11:29:27.586  1018  1031 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4247, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-31 11:29:27.586  1018  1031 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-31 11:29:27.596  1018  1031 D BatteryService: stay LED for charging
08-31 11:29:27.596  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 11:29:27.596  1018  1018 I MotionRecognitionService: Plugged
,08-31 11:29:27.596  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 11:29:27.596  1190  1190 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-31 11:29:27.596  1190  1190 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 11:29:27.606  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-31 11:29:27.606  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-31 11:29:27.616  2788  2788 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-31 11:29:27.616  2788  2915 D HeadsetStateMachine: Disconnected process message: 10
,08-31 11:29:27.626  1190  1190 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-31 11:29:27.626  1190  1190 D SViewCoverView: level :100 plugged : 2
,08-31 11:29:27.636  1190  1190 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 11:29:27.636  1190  1190 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-31 11:29:27.636  1190  1190 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 11:29:28.706   287   287 E SMD     : DCD OFF
,08-31 11:29:29.836  1018  1333 E Watchdog: !@Sync 3
,08-31 11:29:29.946  1018  1043 I ActivityManager: Waited long enough for: ServiceRecord{edde84e u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,08-31 11:29:30.706   325   325 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-31 11:29:30.706   325   325 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-31 11:29:30.746  1018  1096 V AlarmManager: waitForAlarm result :4,
,08-31 11:29:30.746  1018  1096 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0,
08-31 11:29:30.746  1018  1096 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:30.746  1018  1096 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:30.746  1018  1096 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:30.746  1018  1096 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:30.756  6915  6915 E Zygote  : MountEmulatedStorage()
,08-31 11:29:30.756  6915  6915 E Zygote  : v2
08-31 11:29:30.756  6915  6915 I libpersona: KNOX_SDCARD checking this for 10026
08-31 11:29:30.756  6915  6915 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:30.756  1018  1096 I ActivityManager: Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6915 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 11:29:30.766  6915  6915 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:30.766  6915  6915 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:30.766  6915  6915 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 11:29:30.786  6915  6915 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:30.786  6915  6915 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:30.866  6915  6915 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 11:29:30.866  6915  6915 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 11:29:30.906  6915  6915 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-31 11:29:30.906  6915  6915 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 11:29:30.996  6915  6915 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 11:29:30.996  6915  6915 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 11:29:31.006  6915  6915 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 11:29:31.006  6915  6915 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 11:29:31.006  6915  6915 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 11:29:31.016  6915  6915 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 11:29:31.016  6915  6915 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 11:29:31.016  6915  6915 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 11:29:31.016  6915  6915 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 11:29:31.016  6915  6915 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 11:29:31.016  6915  6915 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 11:29:31.016  6915  6915 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 11:29:31.016  6915  6915 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 11:29:31.026  6915  6915 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 11:29:31.026  6915  6915 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 11:29:31.026  6915  6915 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 11:29:31.026  6915  6915 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-31 11:29:31.036  6915  6915 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-31 11:29:31.046  6915  6915 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-31 11:29:31.066  6915  6915 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 11:29:31.066  6915  6915 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 11:29:31.066  6915  6915 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-31 11:29:31.096  6915  6915 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-31 11:29:31.096  1018  1496 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
08-31 11:29:31.096  1018  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,08-31 11:29:31.096  1018  1496 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:31.096  1018  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:31.096  1018  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,08-31 11:29:31.106  6915  6951 D Ads     : Skipping gmscore version check
,08-31 11:29:31.126  1018  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:31.126  6915  6915 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.,
08-31 11:29:31.126  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:31.126  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:31.126  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,08-31 11:29:31.146  6915  6915 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-31 11:29:31.326  6915  6948 D Finsky  : [1299] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,08-31 11:29:31.326  6915  6915 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-31 11:29:31.326  1018  1720 I ActivityManager: Killing 6556:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-31 11:29:31.706   287   287 E SMD     : DCD OFF,
,08-31 11:29:32.326  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-31 11:29:32.326  6662  6834 I jxcore-log: 
,08-31 11:29:32.326  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,08-31 11:29:32.326  6662  6834 I jxcore-log: 
,08-31 11:29:32.336  6662  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:32.336  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:32.336  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:32.336  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:32.336  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:32.336  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:32.336  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:32.336  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:29:32.336  6662  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:29:32.336  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 11:29:32.336  6662  6834 I jxcore-log: 
,08-31 11:29:32.346  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 11:29:32.346  6662  6834 I jxcore-log: 
,08-31 11:29:32.986  6662  6834 I jxcore-log: Unit Test app is loaded,
08-31 11:29:32.986  6662  6834 I jxcore-log: 
,08-31 11:29:32.996  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:32.996  6662  6834 I jxcore-log: 
,08-31 11:29:33.006  6662  6662 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-31 11:29:33.006  6662  6834 D executeNativeTests: Running unit tests
,08-31 11:29:33.096  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 11:29:33.096  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cd5757 added. We now have 2 listener(s)
,08-31 11:29:33.106  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-31 11:29:33.106  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:33.106  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:29:33.106  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:29:33.106  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 added. We now have 2 listener(s)
08-31 11:29:33.106  6662  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:33.106  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 11:29:33.106  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:29:33.106  6662  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:33.106  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:33.106  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:33.106  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:33.106  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:33.106  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:33.106  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:33.106  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:29:33.116  6662  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:29:33.116  6662  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:29:33.116  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:33.116  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:33.116  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-31 11:29:33.116  6662  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:29:33.116  6662  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-31 11:29:33.126  6662  6834 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-31 11:29:33.126  6662  6834 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 11:29:33.126  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 11:29:33.126  6662  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:29:33.126  6662  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-31 11:29:33.126  6662  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:33.126  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:29:33.126  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:33.126  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:33.126  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.126  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:29:33.126  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:33.126  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cd5757 removed from the list
08-31 11:29:33.126  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.126  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 removed from the list
08-31 11:29:33.126  6662  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:33.126  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:33.126  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.126  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:33.126  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:33.126  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:33.126  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.126  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
,08-31 11:29:33.126  6662  6834 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-31 11:29:33.126  6662  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:33.126  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:33.126  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 11:29:33.126  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:33.126  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.126  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.126  6662  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cd5757 not in the list
08-31 11:29:33.126  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.126  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.126  6662  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:33.126  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.126  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.126  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.126  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:33.136  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:33.136  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:33.136  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.136  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
,08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 11:29:33.136  6662  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:33.136  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:33.136  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:33.136  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:33.136  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.136  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.136  6662  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cd5757 not in the list
08-31 11:29:33.136  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.136  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.136  6662  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:33.136  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.136  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.136  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.136  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.136  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:33.136  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:33.136  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.136  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.136  6662  6834 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 11:29:33.146  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:33.146  6662  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:33.146  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:33.146  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:33.146  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:33.146  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:33.146  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:33.146  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:33.146  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:29:33.146  6662  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:33.146  6662  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:29:33.146  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:29:33.146  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:29:33.146  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:29:33.146  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:33.146  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:29:33.156  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 11:29:33.156  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:33.156  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:33.156  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 11:29:33.166  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-31 11:29:33.166  6662  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-31 11:29:33.166  6662  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-31 11:29:33.166  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 11:29:33.166  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 11:29:33.166  6662  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 11:29:33.186  2788  2798 D BtGatt.GattService: registerClient() - UUID=0177128f-89c6-4aa1-a764-dd56d046936c
,08-31 11:29:33.226  2788  2848 D BtGatt.GattService: onClientRegistered() - UUID=0177128f-89c6-4aa1-a764-dd56d046936c, clientIf=6
,08-31 11:29:33.236  6662  6670 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-31 11:29:33.236  2788  2849 D BtGatt.GattService: start scan with filters
,08-31 11:29:33.236  2788  2905 D BtGatt.ScanManager: handling starting scan
,08-31 11:29:33.236  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 11:29:33.236  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-31 11:29:33.236  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-31 11:29:33.236  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 11:29:33.236  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:29:33.246  2788  2905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
,08-31 11:29:33.246  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 11:29:33.246  6662  6662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:29:33.256  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 11:29:33.256  2788  2848 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-31 11:29:33.256  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:33.256  2788  2905 D BtGatt.ScanManager: allow scan with filters
08-31 11:29:33.256  2788  2905 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-31 11:29:33.256  2788  2905 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-31 11:29:33.266  6662  6834 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 11:29:33.266  2788  2848 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-31 11:29:33.266  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:33.266  2788  2905 D BtGatt.ScanManager: Starting BLE batch scan
,08-31 11:29:33.266  2788  2905 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 11:29:33.266  6662  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:29:33.276  6662  6834 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-31 11:29:33.276  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:33.276  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-31 11:29:33.276  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.276  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-31 11:29:33.276  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 11:29:33.276  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:29:33.276  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-31 11:29:33.276  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 11:29:33.276  2788  2848 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-31 11:29:33.276  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:33.276  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-31 11:29:33.276  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 11:29:33.286  2788  2803 D BtGatt.GattService: stopScan() - queue size =1
,08-31 11:29:33.286  2788  2848 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-31 11:29:33.286  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:33.286  2788  2905 D BtGatt.ScanManager: filter size is 1
,08-31 11:29:33.286  2788  2905 D BtGatt.ScanManager: delete FilterIndex - 3
,08-31 11:29:33.296  2788  2798 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 11:29:33.296  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 11:29:33.296  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-31 11:29:33.296  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 11:29:33.296  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-31 11:29:33.296  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 11:29:33.296  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:29:33.296  2788  2848 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-31 11:29:33.296  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:33.296  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 11:29:33.296  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:29:33.296  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 11:29:33.296  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:29:33.296  2788  2905 D BtGatt.ScanManager: stopping BLe Batch
,08-31 11:29:33.306  6662  6662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 11:29:33.306  6662  6662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 11:29:33.306  6662  6662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:29:33.306  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:33.306  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.306  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:29:33.306  6662  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cd5757 not in the list
08-31 11:29:33.306  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.306  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.306  6662  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:33.306  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.306  6662  6834 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-31 11:29:33.306  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:29:33.306  2788  2848 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-31 11:29:33.306  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:33.306  2788  2905 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-31 11:29:33.316  6662  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:33.316  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:33.316  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:33.316  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:33.316  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:33.316  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:33.316  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:33.316  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:29:33.316  2788  2848 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-31 11:29:33.316  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:33.316  6662  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:29:33.316  6662  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:29:33.326  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:29:33.326  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:29:33.326  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:29:33.326  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:33.326  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 11:29:33.326  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:33.326  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:33.326  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 11:29:33.336  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 11:29:33.336  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,08-31 11:29:33.336  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 11:29:33.336  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 11:29:33.336  6662  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 11:29:33.346  2788  2849 D BtGatt.GattService: registerClient() - UUID=f866a051-101e-483a-a961-643557e34d0f
,08-31 11:29:33.386  2788  2848 D BtGatt.GattService: onClientRegistered() - UUID=f866a051-101e-483a-a961-643557e34d0f, clientIf=6
,08-31 11:29:33.386  6662  6671 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
08-31 11:29:33.386  2788  2803 D BtGatt.GattService: start scan with filters
,08-31 11:29:33.386  2788  2905 D BtGatt.ScanManager: handling starting scan
,08-31 11:29:33.386  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 11:29:33.386  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 11:29:33.386  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-31 11:29:33.386  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 11:29:33.386  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:29:33.396  2788  2848 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-31 11:29:33.396  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:33.396  2788  2905 D BtGatt.ScanManager: allow scan with filters
,08-31 11:29:33.396  2788  2905 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-31 11:29:33.396  2788  2905 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-31 11:29:33.396  6662  6662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:29:33.396  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 11:29:33.396  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 11:29:33.396  2788  2848 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-31 11:29:33.396  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:33.396  2788  2905 D BtGatt.ScanManager: Starting BLE batch scan
08-31 11:29:33.396  2788  2905 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 11:29:33.406  6662  6834 I io.jxcore.node.ConnectionHelper: start: OK,
,08-31 11:29:33.406  6662  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:29:33.406  6662  6834 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 11:29:33.406  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:29:33.406  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 11:29:33.406  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.406  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-31 11:29:33.406  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-31 11:29:33.406  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:29:33.406  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:29:33.406  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 11:29:33.406  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-31 11:29:33.406  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 11:29:33.406  2788  2848 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-31 11:29:33.406  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:33.406  2788  2798 D BtGatt.GattService: stopScan() - queue size =1
,08-31 11:29:33.416  2788  2849 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 11:29:33.416  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 11:29:33.416  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 11:29:33.416  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 11:29:33.416  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 11:29:33.416  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 11:29:33.416  2788  2848 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-31 11:29:33.416  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:29:33.416  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:33.416  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 11:29:33.416  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:29:33.416  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:29:33.416  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:29:33.416  2788  2905 D BtGatt.ScanManager: filter size is 1
08-31 11:29:33.416  2788  2905 D BtGatt.ScanManager: delete FilterIndex - 4
,08-31 11:29:33.416  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:33.416  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.416  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:29:33.416  6662  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cd5757 not in the list
08-31 11:29:33.416  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.416  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.416  6662  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:33.416  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.416  6662  6662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 11:29:33.416  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.416  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:33.416  6662  6662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:33.416  6662  6662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:29:33.416  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:33.416  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:33.416  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.416  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
,08-31 11:29:33.426  6662  6834 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-31 11:29:33.426  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:29:33.426  2788  2848 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-31 11:29:33.426  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:33.426  2788  2905 D BtGatt.ScanManager: stopping BLe Batch
,08-31 11:29:33.426  6662  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:33.426  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:33.426  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:33.426  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:33.426  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:33.426  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:33.426  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:33.426  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:29:33.426  6662  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:33.426  6662  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:29:33.426  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:29:33.426  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:29:33.426  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:29:33.426  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:33.426  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 11:29:33.426  2788  2848 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-31 11:29:33.426  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:33.426  2788  2905 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-31 11:29:33.436  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 11:29:33.436  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:33.436  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:33.436  2788  2848 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-31 11:29:33.436  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:33.446  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 11:29:33.446  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 11:29:33.446  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 11:29:33.446  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 11:29:33.446  6662  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 11:29:33.446  2788  2849 D BtGatt.GattService: registerClient() - UUID=0b1db07e-f7de-418f-897e-70ed9ba4848c
,08-31 11:29:33.486  2788  2848 D BtGatt.GattService: onClientRegistered() - UUID=0b1db07e-f7de-418f-897e-70ed9ba4848c, clientIf=6
,08-31 11:29:33.486  6662  6671 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-31 11:29:33.486  2788  2798 D BtGatt.GattService: start scan with filters
,08-31 11:29:33.496  2788  2905 D BtGatt.ScanManager: handling starting scan
,08-31 11:29:33.496  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 11:29:33.496  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 11:29:33.496  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 11:29:33.496  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 11:29:33.496  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:29:33.496  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 11:29:33.496  6662  6662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:29:33.496  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 11:29:33.496  2788  2848 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-31 11:29:33.496  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:33.496  2788  2905 D BtGatt.ScanManager: allow scan with filters
08-31 11:29:33.496  2788  2905 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-31 11:29:33.496  2788  2905 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-31 11:29:33.506  2788  2848 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-31 11:29:33.506  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:33.506  2788  2905 D BtGatt.ScanManager: Starting BLE batch scan
08-31 11:29:33.506  2788  2905 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 11:29:33.506  2788  2848 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-31 11:29:33.506  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:33.506  6662  6834 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 11:29:33.506  6662  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:33.506  6662  6834 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-31 11:29:33.506  2788  2848 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-31 11:29:33.506  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:33.516  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:33.516  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 11:29:33.516  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.516  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:29:33.516  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 11:29:33.516  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:29:33.516  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:29:33.516  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:29:33.516  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:29:33.516  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 11:29:33.516  2788  2803 D BtGatt.GattService: stopScan() - queue size =1
,08-31 11:29:33.516  2788  2905 D BtGatt.ScanManager: filter size is 1
,08-31 11:29:33.516  2788  2905 D BtGatt.ScanManager: delete FilterIndex - 5
,08-31 11:29:33.516  2788  2848 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-31 11:29:33.516  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:33.516  2788  2849 D BtGatt.GattService: unregisterClient() - clientIf=6
08-31 11:29:33.516  2788  2905 D BtGatt.ScanManager: stopping BLe Batch
,08-31 11:29:33.516  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:29:33.516  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 11:29:33.516  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 11:29:33.516  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 11:29:33.516  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 11:29:33.516  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:29:33.516  2788  2848 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-31 11:29:33.516  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:33.516  2788  2905 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-31 11:29:33.526  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-31 11:29:33.526  2788  2848 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-31 11:29:33.526  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:33.526  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:29:33.526  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:29:33.526  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:29:33.526  6662  6662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:33.526  6662  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:29:33.526  6662  6662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:33.526  6662  6662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:29:33.526  6662  6834 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-31 11:29:33.526  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:33.526  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 11:29:33.526  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:33.526  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.526  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:29:33.526  6662  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cd5757 not in the list
08-31 11:29:33.526  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.526  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.526  6662  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:33.526  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.526  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.526  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:33.526  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:33.526  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:33.526  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.526  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
,08-31 11:29:33.526  6662  6834 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-31 11:29:33.526  6662  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:33.526  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:33.526  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:33.526  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:33.526  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:29:33.526  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.526  6662  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cd5757 not in the list
08-31 11:29:33.526  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.526  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.526  6662  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:33.526  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.526  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.526  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.526  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:33.536  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:33.536  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:33.536  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.536  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
,08-31 11:29:33.536  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 11:29:33.536  6662  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:33.536  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:33.536  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:33.536  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:33.536  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.536  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.536  6662  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cd5757 not in the list
08-31 11:29:33.536  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.536  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.536  6662  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:33.536  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.536  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.536  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.536  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:33.536  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:33.536  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:33.536  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.536  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
,08-31 11:29:33.536  6662  6834 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-31 11:29:33.536  6662  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:33.536  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:33.536  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:33.536  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:33.536  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:29:33.536  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.536  6662  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cd5757 not in the list
08-31 11:29:33.536  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.536  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.536  6662  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:33.536  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:29:33.536  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.536  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.536  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.536  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:33.536  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:33.536  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-31 11:29:33.536  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.536  6662  6834 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-31 11:29:33.536  6662  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:33.536  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:33.536  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-31 11:29:33.536  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:33.536  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.536  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.536  6662  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cd5757 not in the list
08-31 11:29:33.536  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:29:33.536  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
,08-31 11:29:33.536  6662  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:33.536  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:29:33.536  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.536  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.536  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.536  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
,08-31 11:29:33.536  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:33.536  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.536  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
,08-31 11:29:33.536  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 11:29:33.536  6662  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:29:33.536  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 11:29:33.536  6662  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:29:33.536  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 11:29:33.536  6662  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 11:29:33.536  6662  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:29:33.536  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:33.536  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:33.536  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:33.536  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.536  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.536  6662  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cd5757 not in the list
08-31 11:29:33.536  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:29:33.536  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.536  6662  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:33.536  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.536  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.536  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.536  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.536  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 11:29:33.536  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:33.536  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.536  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.536  6662  6834 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:29:33.536  6662  6834 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-31 11:29:33.536  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 11:29:33.546  6662  6834 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:29:33.546  6662  6834 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010],
,08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210],
,08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-31 11:29:33.546  6662  6834 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-31 11:29:33.546  6662  6834 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 11:29:33.546  6662  6834 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-31 11:29:33.546  6662  6834 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:29:33.546  6662  6834 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 11:29:33.546  6662  6834 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-31 11:29:33.546  6662  6834 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-31 11:29:33.546  6662  6834 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 11:29:33.546  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-31 11:29:33.546  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-31 11:29:33.546  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-31 11:29:33.546  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-31 11:29:33.546  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-31 11:29:33.546  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-31 11:29:33.546  6662  6834 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-31 11:29:33.546  6662  6834 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 11:29:33.546  6662  6834 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-31 11:29:33.546  6662  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:33.546  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:33.546  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:33.546  6662  6957 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1309)
08-31 11:29:33.546  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:33.546  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.546  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.546  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-31 11:29:33.546  6662  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cd5757 not in the list
08-31 11:29:33.546  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.546  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.546  6662  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:33.546  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.546  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:33.546  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.546  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.546  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:33.546  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:33.546  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.546  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.556  6662  6958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1309
08-31 11:29:33.556  6662  6834 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-31 11:29:33.556  6662  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:29:33.556  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:33.556  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:33.556  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:33.556  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.556  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.556  6662  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cd5757 not in the list
08-31 11:29:33.556  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.556  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
,08-31 11:29:33.556  6662  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:33.556  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.556  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.556  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.556  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.556  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:33.556  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:33.556  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:29:33.556  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.556  6662  6834 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-31 11:29:33.556  6662  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:33.556  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:33.556  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:33.556  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:33.556  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:29:33.556  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.556  6662  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cd5757 not in the list
08-31 11:29:33.556  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.556  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.556  6662  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:33.556  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.556  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.556  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:29:33.556  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.556  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:33.556  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:33.556  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.556  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.556  6662  6834 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-31 11:29:33.556  6662  6834 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-31 11:29:33.556  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-31 11:29:33.556  6662  6834 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-31 11:29:33.556  6662  6834 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 11:29:33.556  6662  6834 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-31 11:29:33.556  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 11:29:33.556  6662  6834 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-31 11:29:33.556  6662  6834 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 11:29:33.556  6662  6834 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 11:29:33.556  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 11:29:33.556  6662  6834 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,08-31 11:29:33.556  6662  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:33.556  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:33.556  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:33.556  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:33.556  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.556  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.556  6662  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cd5757 not in the list
,08-31 11:29:33.556  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.556  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.556  6662  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:33.556  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.556  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.556  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.556  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:33.556  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:33.556  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:33.556  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.556  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.556  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:33.556  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.556  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.556  6662  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cd5757 not in the list
,08-31 11:29:33.556  6662  6957 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-31 11:29:33.556  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.556  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.556  6662  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:33.556  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.556  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.556  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.556  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.556  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:33.556  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.556  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.556  6662  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cd5757 not in the list
,08-31 11:29:33.556  6662  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:33.556  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:33.556  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:33.556  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:33.556  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.556  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.556  6662  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cd5757 not in the list
08-31 11:29:33.556  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.556  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.556  6662  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:33.556  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:29:33.556  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.556  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.556  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.566  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:33.566  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:33.566  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.566  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.566  6662  6834 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-31 11:29:33.566  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:33.566  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-31 11:29:33.566  6662  6957 D BluetoothSocket: connect(): myUserId = 0
08-31 11:29:33.566  6662  6957 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:29:33.566  6662  6834 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-31 11:29:33.566  6662  6834 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-31 11:29:33.566  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-31 11:29:33.566  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-31 11:29:33.566  6662  6662 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-31 11:29:33.566  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:33.566  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-31 11:29:33.566  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-31 11:29:33.566  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-31 11:29:33.566  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:33.566  6662  6834 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-31 11:29:33.566  6662  6662 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-31 11:29:33.566  6662  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cd5757 not in the list
08-31 11:29:33.566  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.566  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:29:33.566  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-31 11:29:33.566  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:29:33.566  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.566  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.566  2788  2803 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:33.566  6662  6959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-31 11:29:33.566  6662  6959 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-31 11:29:33.566  6662  6957 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
08-31 11:29:33.566  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:29:33.566  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.566  6662  6662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:33.566  6662  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:33.566  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:33.566  6662  6662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:33.566  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:33.566  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:33.566  6662  6662 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-31 11:29:33.566  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.566  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.566  6662  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cd5757 not in the list
08-31 11:29:33.566  6662  6662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:29:33.566  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.566  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.566  6662  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:33.566  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.566  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.566  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.566  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bluetoo,thManager: release: 1 listener(s) left
08-31 11:29:33.576  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:33.576  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:33.576  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.576  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.576  6662  6834 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-31 11:29:33.576  6662  6834 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 11:29:33.576  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 11:29:33.576  6662  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 11:29:33.576  6662  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:33.576  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:33.576  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:33.576  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:33.576  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.576  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:33.576  6662  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cd5757 not in the list
08-31 11:29:33.576  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.576  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.576  6662  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:33.576  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.576  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.576  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.576  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.576  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:33.576  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:33.576  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.576  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
,08-31 11:29:33.576  6662  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:33.576  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:33.576  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:33.576  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:33.576  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.576  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:33.576  6662  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cd5757 not in the list
08-31 11:29:33.576  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.576  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.576  6662  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:33.576  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.576  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.576  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.576  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:33.576  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:33.576  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:33.576  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.576  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
08-31 11:29:33.576  6662  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:33.576  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:29:33.576  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:33.586  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:33.586  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.586  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.586  6662  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35cd5757 not in the list
08-31 11:29:33.586  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.586  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
,08-31 11:29:33.586  6662  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:33.586  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.586  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.586  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:33.586  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:33.586  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:33.586  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:33.586  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:33.586  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d54e244 not in the list
,08-31 11:29:33.586  6662  6834 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-31 11:29:33.586  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 11:29:33.586  6662  6834 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-31 11:29:33.586  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 11:29:33.586  6662  6834 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-31 11:29:33.586  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 11:29:33.586  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 11:29:33.586  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-31 11:29:33.586  6662  6834 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-31 11:29:33.586  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-31 11:29:33.586  6662  6834 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-31 11:29:33.586  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 11:29:33.586  6662  6834 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-31 11:29:33.586  6662  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-31 11:29:33.586  6662  6834 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-31 11:29:33.586  6662  6834 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-31 11:29:33.586  6662  6834 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-31 11:29:33.586  6662  6834 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-31 11:29:33.586  6662  6834 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-31 11:29:33.586  6662  6834 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-31 11:29:33.586  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:33.586  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@31ad4386 added. We now have 2 listener(s)
08-31 11:29:33.586  6662  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:33.586  6662  6834 D BluetoothAdapter: enable()
,08-31 11:29:33.586  6662  6834 D BluetoothAdapter: enable(): BT is already enabled..!
,08-31 11:29:33.596  1018  1136 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-31 11:29:33.596  1018  1136 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-31 11:29:33.596  1018  1136 D SecContentProvider2: mCursor = null
,08-31 11:29:33.596  1018  1136 D WifiService: setWifiEnabled: true pid=6662, uid=10170
08-31 11:29:33.596  1018  1136 W ActivityManager: Permission Denial: getCurrentUser() from pid=6662, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-31 11:29:33.596  1018  1136 W WifiService: Failed getting userId using ActivityManagerNative
08-31 11:29:33.596  1018  1136 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6662, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-31 11:29:33.596  1018  1136 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 11:29:33.596  1018  1136 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-31 11:29:33.596  1018  1136 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-31 11:29:33.596  1018  1136 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-31 11:29:33.596  1018  1136 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-31 11:29:33.596  1018  1136 D SettingsProvider: name = wifi_on
08-31 11:29:33.596  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:33.596  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@30fcc447 added. We now have 3 listener(s)
08-31 11:29:33.596  6662  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:33.606  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:29:33.606  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@35576474 added. We now have 4 listener(s)
08-31 11:29:33.606  6662  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:33.606  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:33.606  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3c894d9d added. We now have 5 listener(s)
08-31 11:29:33.606  6662  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:33.606  1018  1496 D SecContentProvider: uri = 18 selection = isWifiEnabled,
08-31 11:29:33.606  1018  1496 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-31 11:29:33.606  1018  1496 D SecContentProvider2: mCursor = null
,08-31 11:29:33.606  1018  1496 D WifiService: setWifiEnabled: false pid=6662, uid=10170
08-31 11:29:33.606  1018  1496 D SettingsProvider: name = wifi_on
,08-31 11:29:33.616  1018  1128 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-31 11:29:33.616  1365  1365 I wpa_supplicant: reset timer : RESET_TIMER 0
08-31 11:29:33.616  1365  1365 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-31 11:29:33.616  6662  6834 D BluetoothAdapter: disable()
08-31 11:29:33.616  1365  1365 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-31 11:29:33.616  1018  1720 D SettingsProvider: name = bluetooth_on
08-31 11:29:33.616  1365  1365 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-31 11:29:33.626  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:29:33.626  1018  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:29:33.626  2788  2845 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-31 11:29:33.626  2788  2845 D BluetoothAdapterProperties: Setting state to 13
08-31 11:29:33.626  2788  2845 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 11:29:33.626  2788  2845 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 11:29:33.626  2788  2845 D BluetoothAdapterService: updateAdapterState state is 13
,08-31 11:29:33.626  1018  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:33.626  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 11:29:33.626  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:33.626  1018  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:33.626  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:33.636  2788  2788 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-31 11:29:33.636  2788  2845 D BluetoothAdapterService: Autoconnection is available 
08-31 11:29:33.636  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:33.636  2788  2845 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-31 11:29:33.636  1018  1018 I InputMethodManagerService: [BT Setting State] State =13
08-31 11:29:33.636  2788  2845 D BluetoothAdapterService: terminating service from this receiver
,08-31 11:29:33.636  2788  2788 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3b0521d3, channel: 19, state: LISTENING,
08-31 11:29:33.636  2788  2788 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3b0521d3, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2b2c25b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2dafe110mSocket: android.net.LocalSocket@2cd5e409 impl:android.net.LocalSocketImpl@2a83060e fd:FileDescriptor[74]
08-31 11:29:33.636  2788  2788 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2cd5e409 impl:android.net.LocalSocketImpl@2a83060e fd:FileDescriptor[74]
,08-31 11:29:33.636  1190  1190 D BluetoothTile:  onBluetoothStateChange:
,08-31 11:29:33.646  1365  1365 I wpa_supplicant: Scan aborted because the firmware maybe busy.
08-31 11:29:33.646  1190  1190 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 11:29:33.646  1365  1365 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
08-31 11:29:33.646  1365  1365 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
08-31 11:29:33.646  1018  1128 E WifiNative-wlan0: do suspend true
,08-31 11:29:33.646  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:29:33.646  6662  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:33.646  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:33.646  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:33.646  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:33.646  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:33.646  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:33.646  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:33.646  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:29:33.646  1190  1190 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:33.646  1190  1190 D BluetoothTile:  getBluetoothState : 13
,08-31 11:29:33.646  1973  1973 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 11:29:33.646  1190  1716 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 11:29:33.646  1190  1716 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 11:29:33.646  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:33.646  6662  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:33.646  6662  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 11:29:33.656  1190  1716 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-31 11:29:33.656  4482  4482 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:33.656  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:33.656  1018  1730 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 11:29:33.656  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:33.656  1018  1218 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 11:29:33.666  1018  3256 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-31 11:29:33.666  1018  3256 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:33.666  1018  3256 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:33.666  1018  3256 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:33.666  1190  1190 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-31 11:29:33.666  2788  2845 D BluetoothAdapterProperties: onBluetoothDisable()
,08-31 11:29:33.666  2788  2845 D BluetoothAdapterProperties: mDiscovering is false
08-31 11:29:33.666  1018  1490 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-31 11:29:33.666  2788  2845 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true,
,08-31 11:29:33.666  6662  6662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:33.666  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:33.666  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:33.666  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:33.666  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:33.666  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:33.666  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:33.666  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:33.666  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:29:33.666  6662  6662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:33.666  6662  6662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:29:33.676  2788  2848 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 11:29:33.676  2788  2848 D BluetoothAdapterProperties: Scan Mode:20
08-31 11:29:33.676  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:33.676  2788  2845 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-31 11:29:33.676  2788  2845 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-31 11:29:33.676  2788  2845 E bt-btif : cmd socket is not created
08-31 11:29:33.676  2788  5307 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:29:33.676  2788  2852 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-31 11:29:33.676  6662  6957 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@18375de3, channel: -1, state: INIT
,08-31 11:29:33.676  6662  6957 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@18375de3, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2ec053e0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@b22699mSocket: android.net.LocalSocket@6f33d5e impl:android.net.LocalSocketImpl@26f7f53f fd:FileDescriptor[106]
08-31 11:29:33.676  6662  6957 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@6f33d5e impl:android.net.LocalSocketImpl@26f7f53f fd:FileDescriptor[106]
08-31 11:29:33.676  2788  2845 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 11:29:33.676  6662  6957 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1309)
08-31 11:29:33.676  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:33.686  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:33.686  4482  4482 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:29:33.686  2788  2788 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@276082f, channel: 5, state: LISTENING
08-31 11:29:33.686  2788  2788 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@276082f, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@ab6aaf8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@619fe3cmSocket: android.net.LocalSocket@22efb7c5 impl:android.net.LocalSocketImpl@116d751a fd:FileDescriptor[76]
08-31 11:29:33.686  2788  2788 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@22efb7c5 impl:android.net.LocalSocketImpl@116d751a fd:FileDescriptor[76]
,08-31 11:29:33.686  1018  1720 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-31 11:29:33.686  1018  1720 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 11:29:33.686  2788  2788 I BtOppRfcommListener: stopping Accept Thread
,08-31 11:29:33.686  2788  2788 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3164f84b, channel: 12, state: LISTENING
08-31 11:29:33.686  2788  2788 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3164f84b, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1705afc2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@20a6c228mSocket: android.net.LocalSocket@9190b41 impl:android.net.LocalSocketImpl@365dc8e6 fd:FileDescriptor[81]
08-31 11:29:33.686  2788  2788 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@9190b41 impl:android.net.LocalSocketImpl@365dc8e6 fd:FileDescriptor[81]
,08-31 11:29:33.686  2788  5307 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 11:29:33.686  1018  1720 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:33.686  1018  1720 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:33.686  1018  1720 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 11:29:33.686  2788  2852 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-31 11:29:33.686  2788  2852 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:29:33.686  2788  2852 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:29:33.686  2788  2852 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:29:33.686  2788  2852 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:29:33.686  2788  2852 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:29:33.686  2788  2852 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
08-31 11:29:33.686  2788  2852 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
08-31 11:29:33.686  2788  2852 W bt-btif : invalid rfc slot id: 4
,08-31 11:29:33.696  4482  4482 D BluetoothPbap: Proxy object disconnected,
08-31 11:29:33.696  4482  4482 D PbapServerProfile: Bluetooth service disconnected
08-31 11:29:33.696  2788  2788 V BluetoothOppManager: cleanUp...
,08-31 11:29:33.696  1681  1681 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:29:33.706  4482  4482 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:29:33.706  4482  4482 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 11:29:33.706  1190  1190 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:33.706  1190  1190 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-31 11:29:33.706  1018  1127 D WifiP2pService: InactiveState{ what=143375 }
,08-31 11:29:33.706  1018  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 11:29:33.716   277   967 D CommandListener: Clearing all IP addresses on wlan0
,08-31 11:29:33.716  1190  1190 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:33.716  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-31 11:29:33.716  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:33.716  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:33.716  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:33.716  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:33.716  1681  2534 V NativeCrypto: Read error: ssl=0xb80bd9f0: I/O error during system call, Connection timed out
08-31 11:29:33.716  1018  1489 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
08-31 11:29:33.716  1018  1130 E ConnectivityService: updateNetworkInfo()
08-31 11:29:33.716  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:29:33.716  1018  1130 E ConnectivityService: updateNetworkInfo()
08-31 11:29:33.716  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,08-31 11:29:33.716  1681  2534 V NativeCrypto: SSL shutdown failed: ssl=0xb80bd9f0: I/O error during system call, Broken pipe
08-31 11:29:33.716  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:33.726  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:33.726  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:33.726  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:33.726  1018  1781 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:29:33.726  1018  1322 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
08-31 11:29:33.726  1018  1781 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:29:33.726  1018  1781 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-31 11:29:33.726  1018  1781 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:29:33.726  1018  1781 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
08-31 11:29:33.726  1018  1781 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-31 11:29:33.726  1018  1781 I qtaguid : Tagging socket 346 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1018, getuid(): 1000
,08-31 11:29:33.726  1018  1781 I qtaguid : Untagging socket 346,
,08-31 11:29:33.726  1018  1781 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 11:29:33.736  1018  1489 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6968 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a,
08-31 11:29:33.746  6968  6968 E Zygote  : MountEmulatedStorage()
08-31 11:29:33.746  6968  6968 E Zygote  : v2
08-31 11:29:33.746  6968  6968 I libpersona: KNOX_SDCARD checking this for 10055
08-31 11:29:33.746  6968  6968 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:33.746  6968  6968 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:29:33.746  1018  1128 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-31 11:29:33.746  6968  6968 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:33.746  1018  1127 D WifiP2pService: InactiveState{ what=131204 }
08-31 11:29:33.746  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-31 11:29:33.746  1018  1127 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-31 11:29:33.746  1018  1127 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-31 11:29:33.746  6968  6968 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:33.756  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 1
08-31 11:29:33.756  1018  1152 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 11:29:33.756  1018  1018 D RttService: SCAN_AVAILABLE : 1,
,08-31 11:29:33.766  1018  1153 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler },
,08-31 11:29:33.766  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:29:33.766  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-31 11:29:33.766  1018  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-31 11:29:33.766  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-31 11:29:33.766  1190  1190 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-31 11:29:33.776  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:33.776  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:29:33.776  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:33.776  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:33.776  1018  1127 D WifiP2pService: P2pDisablingState
08-31 11:29:33.776  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:33.776  1018  1127 D WifiP2pService: P2pDisablingState{ what=147458 }
08-31 11:29:33.776  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:33.776  1018  1127 D WifiP2pService: p2p socket connection lost
08-31 11:29:33.776  1018  1128 E WifiNative-wlan0: do suspend true
08-31 11:29:33.776  1018  1127 D WifiP2pService: P2pDisabledState
,08-31 11:29:33.776  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 11:29:33.776  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
08-31 11:29:33.776  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-31 11:29:33.776  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 11:29:33.776  1018  1048 D WifiDisplayController: disconnect
08-31 11:29:33.776  1018  1048 D WifiDisplayController: updateConnection
08-31 11:29:33.776  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-31 11:29:33.776  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 11:29:33.776  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-31 11:29:33.776  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-31 11:29:33.776  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 11:29:33.776  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-31 11:29:33.776  6968  6968 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 11:29:33.786  6968  6968 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:33.786  1190  1190 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-31 11:29:33.796  1018  1720 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 11:29:33.796  1190  1190 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-31 11:29:33.806  1018  1127 D WifiP2pService: P2pDisabledState{ what=143375 },
08-31 11:29:33.806  1018  1127 D WifiP2pService: DefaultState{ what=143375 },
,08-31 11:29:33.806  1190  1190 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-31 11:29:33.806   277   963 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 11:29:33.806   277   963 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-31 11:29:33.816  1018  1130 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,08-31 11:29:33.816  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:33.816  1018  1130 V NetworkStats: updateIfacesLocked()
08-31 11:29:33.816  1018  1130 V NetworkStats: performPollLocked(flags=0x1)
08-31 11:29:33.816  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:33.816  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:29:33.816  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:29:33.816  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:33.816  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 11:29:33.816  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:33.816  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:33.816  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:33.816   277   967 D CommandListener: Clearing all IP addresses on wlan0
,08-31 11:29:33.816  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit,
08-31 11:29:33.816  1018  1130 V NetworkStats: performPollLocked() took 5ms
,08-31 11:29:33.816  1018  1130 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-31 11:29:33.816  1018  1130 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:29:33.816  1190  1680 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-31 11:29:33.816  1018  1130 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-31 11:29:33.816  1018  1127 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-31 11:29:33.816  1018  1130 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-31 11:29:33.816  1018  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-31 11:29:33.816  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:33.816  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
08-31 11:29:33.816  1018  1781 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-31 11:29:33.816  1018  1781 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-31 11:29:33.816  1018  1781 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:29:33.816  1458  1458 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-31 11:29:33.816  1458  1458 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ],
08-31 11:29:33.826  1018  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-31 11:29:33.826  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-31 11:29:33.826  1365  1365 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-31 11:29:33.836  1018  1018 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-31 11:29:33.836  1018  1131 D Tethering: MasterInitialState.processMessage what=3
08-31 11:29:33.836  1018  1130 D ConnectivityService: nai.networkMonitor.doQuit()
08-31 11:29:33.836  1018  1130 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
,08-31 11:29:33.836  1018  1130 E ConnectivityService: updateNetworkInfo()
08-31 11:29:33.836  1018  1130 E ConnectivityService: updateNetworkInfo()
08-31 11:29:33.836  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-31 11:29:33.836  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:33.836  1018  1125 V NetworkStats: updateIfacesLocked()
08-31 11:29:33.836  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
08-31 11:29:33.836  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:29:33.836  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 11:29:33.836  6968  6968 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-31 11:29:33.836  1018  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-31 11:29:33.836  1018  1125 V NetworkStats: performPollLocked() took 4ms
08-31 11:29:33.836  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:33.846  1018  1128 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-31 11:29:33.846  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:29:33.846  1018  1128 D SecContentProvider2: mCursor = null
08-31 11:29:33.846  1190  1190 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-31 11:29:33.846  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:33.846  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:29:33.846  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:33.846  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:33.846  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:33.846  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:33.846  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:33.846  1190  1190 D StatusBar.NetworkController: EthernetConnected: false
08-31 11:29:33.846  1190  1190 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-31 11:29:33.846  1018  1126 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-31 11:29:33.846  1190  1190 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-31 11:29:33.846  1190  1190 D StatusBar.NetworkController: updateDataNetType()
08-31 11:29:33.846  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:33.846  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:33.846  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:33.846  1190  1190 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-31 11:29:33.846  1190  1190 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-31 11:29:33.846  1190  1190 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-31 11:29:33.846  1190  1190 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 24 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,08-31 11:29:33.846  1190  1190 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
,08-31 11:29:33.846  1190  1190 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-31 11:29:33.856  4482  4482 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:29:33.856  1190  1190 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-31 11:29:33.856  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:33.856  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:29:33.856  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:33.856  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:33.856  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:33.856  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:33.856  6662  6662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:33.856  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:33.856  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:33.856  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:33.856  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:33.856  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:33.856  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:33.856  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:33.856  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:29:33.856  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:33.856  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:33.856  6662  6662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:33.856  6662  6662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:33.866  6662  6662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:29:33.866  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:33.866  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:33.866  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:33.866  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:33.866  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:33.866  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:33.866  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false,
08-31 11:29:33.866  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:33.866  6662  6662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-31 11:29:33.866  6662  6662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:29:33.866  1190  1190 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:29:33.866  1190  1190 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:29:33.866  1190  1716 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 11:29:33.866  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:33.866  1190  1190 D HotspotTile: onReceive : 0, 0
08-31 11:29:33.866  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 11:29:33.866  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:33.866  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:33.866  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:33.866  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:33.866  1190  1190 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:29:33.866  1190  1190 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-31 11:29:33.876  2788  2845 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-31 11:29:33.876  6968  6968 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-31 11:29:33.876  2788  2845 D BtConfig.SecureMode: isSecureModeOn:false
08-31 11:29:33.876  2788  2845 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-31 11:29:33.876  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-31 11:29:33.876  2788  2845 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-31 11:29:33.876  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-31 11:29:33.876  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-31 11:29:33.876  2788  2845 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-31 11:29:33.876  6968  6968 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-31 11:29:33.876  6968  6968 D UserAnalysis: Create SecureDbHelper
,08-31 11:29:33.886  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:33.886  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-31 11:29:33.886  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:33.886  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:33.886  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:33.886  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-31 11:29:33.886  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-31 11:29:33.886  2788  2845 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-31 11:29:33.886  2788  2788 D HeadsetService: Received stop request...Stopping profile...
,08-31 11:29:33.886  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:33.886  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 11:29:33.886  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:33.886  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:33.886  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:33.886  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
,08-31 11:29:33.896  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-31 11:29:33.896  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-31 11:29:33.896  2788  2845 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-31 11:29:33.896  1018  3255 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:33.896  1018  3255 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 11:29:33.896  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-31 11:29:33.896  4482  4482 D HeadsetProfile: Bluetooth service disconnected
08-31 11:29:33.896  6968  6968 D IntelligenceServiceApplication: onCreate()
,08-31 11:29:33.896  1018  3255 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:33.896  1018  3255 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:33.896  1018  3255 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 11:29:33.896  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-31 11:29:33.896  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 11:29:33.896  2788  2845 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-31 11:29:33.906  1018  1320 I ActivityManager: Killing 6571:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,08-31 11:29:33.906  1018  1322 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:33.906  1018  1322 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-31 11:29:33.906  1018  1322 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:33.906  1018  1322 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:33.906  1018  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 11:29:33.906  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-31 11:29:33.906  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 11:29:33.906  6968  6968 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-31 11:29:33.906  2788  2845 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-31 11:29:33.916  1018  1730 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:33.916  1018  1730 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 11:29:33.916  1018  1730 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:33.916  1018  1730 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:33.916  1018  1730 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 11:29:33.916  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-31 11:29:33.916  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-31 11:29:33.916  2788  2845 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-31 11:29:33.916  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:33.916  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 11:29:33.916  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:33.916  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:33.916  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 11:29:33.916  1365  1365 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 11:29:33.916  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-31 11:29:33.916  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-31 11:29:33.916  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-31 11:29:33.916  2788  2845 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-31 11:29:33.916  6968  6968 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-31 11:29:33.926  1018  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:33.926  1018  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 11:29:33.926  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:33.926  1018  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:33.926  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:33.926  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:29:33.926  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:29:33.926  2788  2845 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:29:33.926  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:33.926  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:33.926  2788  2845 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:33.926  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-31 11:29:33.926  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-31 11:29:33.926  2788  2845 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-31 11:29:33.926  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-31 11:29:33.926  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 11:29:33.926  2788  2845 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-31 11:29:33.926  2788  2845 D BluetoothAdapterState: Stopping profile services that were post enabled
08-31 11:29:33.926  2788  2788 E BluetoothAdapterService(777348176): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-31 11:29:33.926  2788  2788 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 11:29:33.926  2788  2788 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-31 11:29:33.926  2788  2788 D A2dpService: Received stop request...Stopping profile...
,08-31 11:29:33.926  2788  2935 D A2dpStateMachine: Exit Disconnected: -1
,08-31 11:29:33.926  6968  6968 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-31 11:29:33.936  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
,08-31 11:29:33.936  1018  1018 D BluetoothA2dp: Proxy object disconnected
08-31 11:29:33.936  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-31 11:29:33.936  4482  4482 D BluetoothA2dp: Proxy object disconnected
,08-31 11:29:33.936  4482  4482 D A2dpProfile: Bluetooth service disconnected
,08-31 11:29:33.946  2788  2788 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 11:29:33.946  2788  2788 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-31 11:29:33.946  2788  2788 D HidService: Received stop request...Stopping profile...
08-31 11:29:33.946  2788  2788 D HidService: Stopping Bluetooth HidService
08-31 11:29:33.946  2788  2788 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 11:29:33.946  2788  2788 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-31 11:29:33.946  2788  2788 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 11:29:33.946  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
,08-31 11:29:33.946  2788  2788 D HealthService: Received stop request...Stopping profile...
,08-31 11:29:33.946  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
,08-31 11:29:33.946  2788  2788 D PanService: Received stop request...Stopping profile...
08-31 11:29:33.946  4482  4482 D BluetoothInputDevice: Proxy object disconnected
08-31 11:29:33.946  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
08-31 11:29:33.946  4482  4482 D HidProfile: Bluetooth service disconnected
,08-31 11:29:33.946  1018  1496 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-31 11:29:33.956  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:33.956  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:33.956  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:33.956  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:33.966  6988  6988 E Zygote  : MountEmulatedStorage()
,08-31 11:29:33.966  6988  6988 I libpersona: KNOX_SDCARD checking this for 10105
08-31 11:29:33.966  6988  6988 E Zygote  : v2
08-31 11:29:33.966  6988  6988 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:33.966  6988  6988 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:33.966  6988  6988 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:33.966  6988  6988 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 11:29:33.976  1018  1496 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6988 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-31 11:29:33.976  1018  1018 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-31 11:29:33.976  4482  4482 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 11:29:33.976  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 11:29:33.976  4482  4482 D PanProfile: Bluetooth service disconnected
08-31 11:29:33.976  2788  2788 D BluetoothMapService: Received stop request...Stopping profile...
,08-31 11:29:33.986  1365  1365 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-31 11:29:33.986  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 11:29:33.986  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 11:29:33.986  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-31 11:29:33.986  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
08-31 11:29:33.986  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 11:29:33.986  2788  2788 D SapService: Received stop request...Stopping profile...
08-31 11:29:33.986  2788  2788 D SapService: Stopping Bluetooth SapService
08-31 11:29:33.986  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
,08-31 11:29:33.986  4482  4482 D BluetoothMap: Proxy object disconnected
08-31 11:29:33.986  4482  4482 D MapProfile: Bluetooth service disconnected
,08-31 11:29:33.986  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 11:29:33.986  2788  2788 E BluetoothAdapterService(777348176): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-31 11:29:33.986  2788  2788 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 11:29:33.996  2788  2788 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-31 11:29:33.996  2788  2788 D BluetoothA2dp: Proxy object disconnected
08-31 11:29:33.996  2788  2788 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-31 11:29:33.996  2788  2937 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-31 11:29:33.996  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 11:29:33.996  2788  2788 I GKI_LINUX: GKI_exit_task 2 done
08-31 11:29:33.996  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 11:29:33.996  2788  2788 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-31 11:29:33.996  4482  4482 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-31 11:29:33.996  4482  4482 D SapProfile: Bluetooth service disconnected
08-31 11:29:33.996  2788  2788 E BluetoothAdapterService(777348176): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-31 11:29:33.996  2788  2788 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-31 11:29:33.996  2788  2788 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:33.996  2788  2788 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:33.996  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 11:29:33.996  2788  2788 E BluetoothAdapterService(777348176): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-31 11:29:33.996  2788  2788 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-31 11:29:33.996  2788  2788 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:33.996  2788  2788 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:33.996  2788  2788 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-31 11:29:33.996  2788  2788 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 11:29:33.996  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 11:29:33.996  2788  2788 E BluetoothAdapterService(777348176): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-31 11:29:33.996  2788  2788 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-31 11:29:33.996  2788  2788 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:33.996  2788  2788 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:33.996  2788  2788 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 11:29:33.996  2788  2788 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-31 11:29:33.996  2788  2788 E BluetoothAdapterService(777348176): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-31 11:29:33.996  2788  2788 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-31 11:29:33.996  2788  2788 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 11:29:33.996  2788  2788 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-31 11:29:33.996  2788  2788 E BluetoothAdapterService(777348176): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-31 11:29:33.996  2788  2788 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,08-31 11:29:33.996  2788  2788 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-31 11:29:33.996  2788  2788 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-31 11:29:33.996  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 11:29:33.996  2788  2845 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-31 11:29:33.996  2788  2845 D BluetoothAdapterProperties: Setting state to 10
08-31 11:29:33.996  2788  2845 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-31 11:29:33.996  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 11:29:33.996  2788  2845 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 11:29:33.996  2788  2845 D BluetoothAdapterService: updateAdapterState state is 10
,08-31 11:29:33.996  2788  2845 D BluetoothAdapterService: Autoconnection is available 
08-31 11:29:33.996  2788  2845 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-31 11:29:33.996  2788  2845 I BluetoothAdapterState: Entering OffState
08-31 11:29:33.996  6662  6670 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:29:33.996  6662  6670 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:29:33.996  6662  6670 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-31 11:29:33.996  6662  6670 D BluetoothLeAdvertiser: Exit stop advertising
08-31 11:29:33.996  6662  6670 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-31 11:29:33.996  6662  6670 D BluetoothLeScanner: Exiting stopAllScan
,08-31 11:29:33.996  2788  2798 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 11:29:34.006  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 11:29:34.006  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 11:29:34.006  6988  6988 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 11:29:34.006  6988  6988 D ActivityThread: Added TimaKeyStore provider
08-31 11:29:34.006  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 11:29:34.006  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 11:29:34.006  1448  1459 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:29:34.006  1448  1459 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:29:34.006  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 11:29:34.006  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 11:29:34.006  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 11:29:34.006  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 11:29:34.006  1365  1365 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-31 11:29:34.016  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:29:34.016  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:34.016  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-31 11:29:34.016  1365  1365 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-31 11:29:34.016  1365  1365 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-31 11:29:34.016  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:34.016  1018  1131 D Tethering: InitialState.processMessage what=4
08-31 11:29:34.016  1365  1365 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-31 11:29:34.016  1365  1365 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-31 11:29:34.016  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:29:34.016  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 11:29:34.016  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-31 11:29:34.016  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 11:29:34.016  1018  1131 E Tethering: No numeric data
,08-31 11:29:34.016  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:29:34.016  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:34.016  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:29:34.016  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 11:29:34.016  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 11:29:34.016  1018  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 11:29:34.016  1018  1131 D Tethering: clearTetheredNotification()
,08-31 11:29:34.016  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 11:29:34.016  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 11:29:34.016  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:34.016  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
08-31 11:29:34.016  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 11:29:34.016  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 11:29:34.016  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:29:34.016  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:29:34.026  1190  1190 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 11:29:34.026  1190  1190 D HotspotTile: updateTetherState():false, false
08-31 11:29:34.026  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 11:29:34.026  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 11:29:34.026  4482  4490 D BluetoothMap: onBluetoothStateChange: up=false
,08-31 11:29:34.026  1458  2676 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:29:34.026  1458  2676 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 11:29:34.026  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 11:29:34.026  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 11:29:34.026  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:34.026  1018  1125 V NetworkStats: performPollLocked() took 6ms
08-31 11:29:34.026  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 11:29:34.026  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:34.026  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:34.026  4482  4491 D BluetoothPbap: onBluetoothStateChange: up=false
,08-31 11:29:34.026  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 11:29:34.026  1739  1748 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:29:34.026  1739  1748 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 11:29:34.026  1681  1769 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:29:34.026  1681  1769 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:29:34.026  4482  4490 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 11:29:34.026  4482  4491 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:29:34.036  4482  4491 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 11:29:34.036  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:29:34.036  1018  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:29:34.036  4482  4490 D Bluetoothsap: onBluetoothStateChange: up=false
08-31 11:29:34.036  4482  4490 D Bluetoothsap: Unbinding service...
,08-31 11:29:34.036  1190  1967 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:29:34.036  1190  1967 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:29:34.036  2788  2803 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:29:34.036  2788  2803 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 11:29:34.036  4482  4491 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-31 11:29:34.036  1440  1454 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:29:34.036  1440  1454 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:29:34.036  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:34.036  1018  1018 I InputMethodManagerService: [BT Setting State] State =10
08-31 11:29:34.036  1018  1018 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-31 11:29:34.046  1190  1190 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 11:29:34.046  1190  1190 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:34.046  1190  1190 D BluetoothTile:  getBluetoothState : 10
,08-31 11:29:34.046  1973  1973 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 11:29:34.046  1018  1494 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-31 11:29:34.056  1018  1490 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-31 11:29:34.056  1190  1190 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 11:29:34.056  4482  4482 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:34.056  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-31 11:29:34.056  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-31 11:29:34.066  6662  6662 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 11:29:34.126   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-31 11:29:34.126   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 11:29:34.126  6988  7021 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-31 11:29:34.136   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-31 11:29:34.136   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 11:29:34.136  6988  7021 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-31 11:29:34.176  1365  1365 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 11:29:34.226  1365  1365 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-31 11:29:34.226  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:34.226  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:29:34.226  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:29:34.236  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-31 11:29:34.236  1018  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-31 11:29:34.236  1190  1190 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:29:34.236  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:34.236  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 11:29:34.236  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:34.236  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:34.236  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:34.236  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:34.236  1190  1190 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:29:34.236  1190  1190 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:29:34.236  1190  1190 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-31 11:29:34.236  1190  1716 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 11:29:34.246  1190  1190 D HotspotTile: onReceive : 1, 0
,08-31 11:29:34.246  4482  4482 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:29:34.246  1739  2188 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:29:34.246  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:34.246  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:34.296  6988  6988 D StrictMode: StrictMode policy violation; ~duration=159 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-31 11:29:34.296  6988  6988 D StrictMode: StrictMode policy violation; ~duration=158 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:34.296  6988  6988 D StrictMode: StrictMode policy violation; ~duration=156 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:34.296  6988  6988 D StrictMode: StrictMode policy violation; ~duration=154 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.q.e.b(PG:170)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08,-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:34.296  6988  6988 D StrictMode: StrictMode policy violation; ~duration=152 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.q.k.d(PG:583)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.q.e.b(PG:170)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:34.296  6988  6988 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:34.296  6988  6988 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:34.296  6988  6988 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:34.296  6988  6988 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:34.306  1018  3255 I ActivityManager: Killing 6590:com.wsomacp/u0a23 (adj 15): empty #21
08-31 11:29:34.306  1018  1730 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 11:29:34.306  1018  1730 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 11:29:34.306  1018  1730 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:34.306  1018  1730 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:34.306  1018  1730 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 11:29:34.316  1631  1631 I Hs20UtilService: Starting #8
08-31 11:29:34.316  1631  1655 I Hs20UtilService: Message received 5007
08-31 11:29:34.316  4482  4482 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 11:29:34.316  4482  4482 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-31 11:29:34.316  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-31 11:29:34.316  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 11:29:34.316  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 11:29:34.316  4482  4482 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 11:29:34.326  4482  4521 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-31 11:29:34.326  1018  1320 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:34.326  1018  1320 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:34.326  1018  1320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
08-31 11:29:34.326  1018  1320 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
08-31 11:29:34.326  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:34.326  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:34.326  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:34.326  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:34.336  1018  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-31 11:29:34.346  7032  7032 E Zygote  : MountEmulatedStorage()
08-31 11:29:34.346  7032  7032 I libpersona: KNOX_SDCARD checking this for 10102
08-31 11:29:34.346  7032  7032 E Zygote  : v2
08-31 11:29:34.346  7032  7032 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:34.346  7032  7032 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:29:34.346  1018  1320 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7032 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-31 11:29:34.346  7032  7032 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:34.346  7032  7032 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-31 11:29:34.356  1018  1018 I ApplicationPolicy: updateDataUsageMap
,08-31 11:29:34.376  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:34.386  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:34.386  7032  7032 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:34.386  7032  7032 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:34.396  6988  7031 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-31 11:29:34.416  7032  7032 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-31 11:29:34.416  1018  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:29:34.416  1018  1489 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:34.416  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:34.416  1018  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:34.416  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-31 11:29:34.516  1018  1050 I PowerManagerService: [PWL] Off : 50s ago
,08-31 11:29:34.516  1018  1050 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-31 11:29:34.516  1018  1050 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,08-31 11:29:34.516  1018  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1018, ws=null) (elapsedTime=681)
,08-31 11:29:34.616  7032  7054 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-31 11:29:34.616  7032  7054 I Babel_SMS: MmsConfig.loadMmsSettings
08-31 11:29:34.616  7032  7054 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-31 11:29:34.616  7032  7054 I Babel_SMS: MmsConfig.loadFromDatabase
,08-31 11:29:34.636  7032  7054 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-31 11:29:34.636  7032  7054 I Babel_SMS: MmsConfig.loadFromResources
,08-31 11:29:34.636  7032  7054 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-31 11:29:34.636  7032  7054 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-31 11:29:34.646  1018  1136 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-31 11:29:34.646  1018  1136 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-31 11:29:34.646  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:34.646  1018  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:34.646  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-31 11:29:34.666  1018  2869 D SSRM:n  : SIOP:: AP = 380
,08-31 11:29:34.686  7032  7032 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:29:34.686  7032  7032 I Babel_Crash: startup - clean
,08-31 11:29:34.706   287   287 E SMD     : DCD OFF,
,08-31 11:29:34.716  4482  4482 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE,
08-31 11:29:34.716  4482  4482 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 11:29:34.716  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 11:29:34.716  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 11:29:34.716  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 11:29:34.716  4482  4482 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 11:29:34.716  4482  4521 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 11:29:34.716  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-31 11:29:34.726  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-31 11:29:34.726  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:34.726  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:34.726  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:34.726  7032  7032 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
,08-31 11:29:34.726  7032  7032 W AudioCapabilities: Unsupported mime audio/evrc
08-31 11:29:34.726  7032  7032 W AudioCapabilities: Unsupported mime audio/qcelp
,08-31 11:29:34.736  7032  7032 W AudioCapabilities: Unsupported mime audio/mpeg-L1,
08-31 11:29:34.736  7032  7032 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-31 11:29:34.736  7032  7032 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-31 11:29:34.736  7032  7032 W AudioCapabilities: Unsupported mime audio/x-ima
,08-31 11:29:34.736  7032  7032 W AudioCapabilities: Unsupported mime audio/qcelp
,08-31 11:29:34.736  7032  7032 W AudioCapabilities: Unsupported mime audio/evrc
,08-31 11:29:34.746  7058  7058 E Zygote  : MountEmulatedStorage()
08-31 11:29:34.746  7058  7058 E Zygote  : v2
08-31 11:29:34.746  7058  7058 I libpersona: KNOX_SDCARD checking this for 10064
08-31 11:29:34.746  7058  7058 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:34.746  7058  7058 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 11:29:34.746  7032  7032 W VideoCapabilities: Unsupported mime video/wvc1,
08-31 11:29:34.746  1018  1031 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7058 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 11:29:34.746  7032  7032 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-31 11:29:34.756  7058  7058 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:34.756  7058  7058 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:34.766  7032  7032 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-31 11:29:34.766  7032  7032 W VideoCapabilities: Unsupported mime video/wvc1
,08-31 11:29:34.766  7032  7032 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-31 11:29:34.766  7032  7032 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-31 11:29:34.766  7058  7058 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:34.766  7058  7058 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:34.766  7032  7032 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-31 11:29:34.776  7032  7032 W VideoCapabilities: Unsupported mime video/mp43
,08-31 11:29:34.786  7032  7032 W VideoCapabilities: Unsupported mime video/sorenson
,08-31 11:29:34.786  7058  7058 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-31 11:29:34.786  7032  7032 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-31 11:29:34.806  7058  7058 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 11:29:34.806  7032  7032 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-31 11:29:34.806  1018  1045 D Tethering: interfaceRemoved wlan0
08-31 11:29:34.806  1018  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-31 11:29:34.816  7058  7058 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-31 11:29:34.836  7032  7032 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 11:29:34.836  7032  7032 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 11:29:34.836  7032  7032 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 11:29:34.836  7032  7032 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 11:29:34.846  7058  7058 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 11:29:34.846  1018  1218 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-31 11:29:34.846  1018  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:34.846  1018  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:34.846  1018  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:34.846  1018  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:34.856  7073  7073 E Zygote  : MountEmulatedStorage()
,08-31 11:29:34.856  7073  7073 E Zygote  : v2
08-31 11:29:34.856  7073  7073 I libpersona: KNOX_SDCARD checking this for 10065
08-31 11:29:34.856  7073  7073 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:34.856  7073  7073 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-31 11:29:34.856  1018  1218 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7073 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 11:29:34.856  1018  1218 I ActivityManager: Killing 6639:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,08-31 11:29:34.866  7032  7032 I vclib   : onServiceConnected
,08-31 11:29:34.866  1018  1218 I ActivityManager: Killing 6310:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
08-31 11:29:34.866  7073  7073 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:34.866  7073  7073 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:34.886  7073  7073 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:34.886  7073  7073 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:34.906  7073  7073 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 11:29:34.916  1018  1494 I ActivityManager: Killing 6677:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-31 11:29:34.916  1018  1720 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 11:29:34.916  1018  1720 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:29:34.916  1018  1720 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:34.916  1018  1720 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:34.916  1018  1720 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:29:34.926  1631  1631 I Hs20UtilService: Starting #9
,08-31 11:29:34.926  1631  1655 I Hs20UtilService: Message received 5007
,08-31 11:29:34.926  4482  4482 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 11:29:34.926  4482  4482 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 11:29:34.926  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 11:29:34.926  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 11:29:34.926  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 11:29:34.926  4482  4482 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 11:29:34.926  4482  4521 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 11:29:34.926  1018  1730 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:34.926  1018  1730 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:34.926  1018  1730 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:34.936  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 11:29:34.936  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:29:34.936  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:34.936  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:34.936  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 11:29:34.936  1631  1631 I Hs20UtilService: Starting #10
,08-31 11:29:34.936  1631  1655 I Hs20UtilService: Message received 5011
,08-31 11:29:34.946  6849  6849 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 11:29:34.946  6849  6849 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 11:29:34.946  6849  6849 D SecurityLogAgent: StateMachine : Current State = 1
08-31 11:29:34.946  6849  6849 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 11:29:34.956  1018  1720 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:34.956  1018  1720 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:34.956  1018  1720 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:34.956  1018  1045 D Tethering: interfaceRemoved p2p0
,08-31 11:29:34.956  1018  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-31 11:29:34.956  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:34.956  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:34.956  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:34.966  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:34.966  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:34.966  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:34.966  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:34.966  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:34.966  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:34.976  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:34.976  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:34.976  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:34.976  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:34.976  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:34.976  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:34.976  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:34.976  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:34.976  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:34.986  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:34.986  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:34.986  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:34.986  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:34.986  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:34.986  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:34.986  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:34.986  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:34.986  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:34.996  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:34.996  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:34.996  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:34.996  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:34.996  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:34.996  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:34.996  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:34.996  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:34.996  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:34.996  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:34.996  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:34.996  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 11:29:35.006  4482  4482 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:29:35.006  1018  1030 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-31 11:29:35.006  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 11:29:35.006  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:35.006  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:35.006  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 11:29:35.016  1681  1681 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:29:35.016  4482  4482 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:29:35.016  4482  4482 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 11:29:35.026  1190  1190 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:35.026  1190  1190 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-31 11:29:35.036  1018  1031 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 11:29:35.036  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:29:35.036  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:35.036  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:35.036  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:29:35.036  1631  1631 I Hs20UtilService: Starting #11
,08-31 11:29:35.046  1631  1655 I Hs20UtilService: Message received 5011
,08-31 11:29:35.046  6849  6849 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 11:29:35.046  6849  6849 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 11:29:35.046  6849  6849 D SecurityLogAgent: StateMachine : Current State = 1
08-31 11:29:35.046  6849  6849 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 11:29:35.046  1018  1218 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-31 11:29:35.056  1018  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:35.056  1018  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:35.056  1018  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:35.056  1018  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:35.066  1018  1218 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7090 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-31 11:29:35.066  7090  7090 E Zygote  : MountEmulatedStorage()
08-31 11:29:35.066  7090  7090 E Zygote  : v2
08-31 11:29:35.066  7090  7090 I libpersona: KNOX_SDCARD checking this for 1000
08-31 11:29:35.066  7090  7090 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:35.066  7090  7090 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:35.076  7090  7090 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:35.076  7090  7090 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:35.096  7090  7090 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:35.096  7090  7090 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:35.116  7090  7090 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-31 11:29:35.116  7090  7090 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-31 11:29:35.116  7090  7090 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-31 11:29:35.126  7090  7090 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-31 11:29:35.126  7090  7090 I PCWCLIENTTRACE_PushUtil: sales region : global
08-31 11:29:35.126  7090  7090 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,08-31 11:29:35.126  7090  7090 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:29:35.136  1018  1494 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,08-31 11:29:35.136  1018  1494 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
08-31 11:29:35.136  1018  1494 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-31 11:29:35.136  1018  1494 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-31 11:29:35.136  7090  7105 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-31 11:29:35.136  1018  1494 I ActivityManager: Killing 6703:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-31 11:29:35.146  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-31 11:29:35.146  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:35.146  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:35.146  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:35.146  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:35.156  7107  7107 E Zygote  : MountEmulatedStorage()
08-31 11:29:35.156  7107  7107 I libpersona: KNOX_SDCARD checking this for 10001
08-31 11:29:35.156  7107  7107 E Zygote  : v2
08-31 11:29:35.156  7107  7107 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:35.156  7107  7107 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:29:35.156  7107  7107 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:35.156  7107  7107 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:35.166  1018  1018 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7107 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 11:29:35.176  7107  7107 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:35.176  7107  7107 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:35.216  1018  1494 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-31 11:29:35.216  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:35.216  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:35.216  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:35.226  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:35.236  7125  7125 E Zygote  : MountEmulatedStorage(),
,08-31 11:29:35.236  1018  1494 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7125 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,08-31 11:29:35.236  7125  7125 E Zygote  : v2
08-31 11:29:35.236  1018  1494 I ActivityManager: Killing 6325:com.android.mms/u0a41 (adj 15): empty #21
08-31 11:29:35.236  7125  7125 I libpersona: KNOX_SDCARD checking this for 1000
08-31 11:29:35.236  7125  7125 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:35.246  7125  7125 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:35.246  7125  7125 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:35.246  7125  7125 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:35.256  7125  7125 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:35.256  7125  7125 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:35.296  7125  7125 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-31 11:29:35.316  1018  1720 D CountryDetector: No listener is left
,08-31 11:29:35.416  7125  7125 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-31 11:29:35.426  7125  7125 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-31 11:29:35.426  7125  7125 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:29:35.426  7125  7125 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-31 11:29:35.426  7125  7125 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-31 11:29:35.436  7125  7125 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-31 11:29:35.436  1018  1489 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-31 11:29:35.436  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:35.436  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:35.436  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:35.436  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:35.456  7140  7140 E Zygote  : MountEmulatedStorage(),
08-31 11:29:35.456  7140  7140 E Zygote  : v2
08-31 11:29:35.456  7140  7140 I libpersona: KNOX_SDCARD checking this for 10008
08-31 11:29:35.456  7140  7140 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:35.456  7140  7140 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:35.456  7140  7140 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-31 11:29:35.466  7140  7140 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
08-31 11:29:35.466  1018  1489 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7140 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 11:29:35.466  1018  1489 I ActivityManager: Killing 6736:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-31 11:29:35.496  7140  7140 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:35.496  7140  7140 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:35.496   309   309 I art     : Explicit concurrent mark sweep GC freed 8712(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 996us total 37.455ms,
,08-31 11:29:35.516   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 682us total 20.640ms
,08-31 11:29:35.536   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 691us total 19.764ms
,08-31 11:29:35.576  1018  1320 I ActivityManager: Killing 6155:com.samsung.android.sm/1000 (adj 15): empty #21
,08-31 11:29:35.576  1018  1720 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-31 11:29:35.576  1018  1720 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-31 11:29:35.576  1018  1720 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:35.576  1018  1720 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:35.576  1018  1720 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-31 11:29:35.586  1847  1847 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-31 11:29:35.586  1847  4752 I iu.UploadsManager: num queued entries: 0
,08-31 11:29:35.586  1847  4752 I iu.UploadsManager: num updated entries: 0
,08-31 11:29:35.596  1018  3256 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 11:29:35.596  1847  4752 I iu.SyncManager: NEXT; no task
08-31 11:29:35.596  1018  3256 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,08-31 11:29:35.596  1018  3256 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:35.596  1018  3256 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:35.596  1018  3256 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:35.606  1847  1847 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 11:29:35.606  1847  1847 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,08-31 11:29:35.616  2928  2928 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 31 11:29:35 GMT+02:00 2016
,08-31 11:29:35.616  1018  1496 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-31 11:29:35.616  1018  1496 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-31 11:29:35.616  1018  1496 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:35.616  1018  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:35.616  1018  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-31 11:29:35.636  2928  2928 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-31 11:29:35.646  2928  2928 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-31 11:29:35.646  1018  1494 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-31 11:29:35.646  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:35.646  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:35.646  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:35.646  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:35.656  2928  2928 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-31 11:29:35.656  2928  2928 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-31 11:29:35.656  2928  7156 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
08-31 11:29:35.656  2928  7156 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
08-31 11:29:35.656  7157  7157 E Zygote  : MountEmulatedStorage()
08-31 11:29:35.656  7157  7157 E Zygote  : v2
,08-31 11:29:35.666  7157  7157 I libpersona: KNOX_SDCARD checking this for 10031
,08-31 11:29:35.666  7157  7157 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:35.666  7157  7157 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:35.666  1018  1494 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7157 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-31 11:29:35.666  7157  7157 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:35.666  2928  7156 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-31 11:29:35.666  2928  7156 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-31 11:29:35.676  7157  7157 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:35.676  2928  2928 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-31 11:29:35.686  7157  7157 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:35.686  7157  7157 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:35.706   325   325 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 11:29:35.716  7157  7157 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-31 11:29:35.726  1018  1031 I ActivityManager: Killing 6759:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-31 11:29:35.736  1018  1730 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-31 11:29:35.736  1018  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:35.736  1018  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:35.736  1018  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:35.736  1018  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:35.736  3514  7173 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-31 11:29:35.746  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-31 11:29:35.746  7174  7174 E Zygote  : MountEmulatedStorage()
,08-31 11:29:35.746  7174  7174 E Zygote  : v2
08-31 11:29:35.746  7174  7174 I libpersona: KNOX_SDCARD checking this for 10032
08-31 11:29:35.746  7174  7174 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:35.746  7174  7174 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 11:29:35.756  1018  1730 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7174 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 11:29:35.756  3514  7173 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false,
,08-31 11:29:35.756  3514  7173 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-31 11:29:35.756  7174  7174 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-31 11:29:35.756  3514  7173 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-31 11:29:35.756  3514  7173 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... ,
08-31 11:29:35.756  7174  7174 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-31 11:29:35.776  7174  7174 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:35.776  7174  7174 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:35.856  7174  7189 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-31 11:29:35.856  7174  7174 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-31 11:29:35.856  7174  7189 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-31 11:29:35.856  1018  1322 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-31 11:29:35.856  1018  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:35.856  1018  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:35.856  1018  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:35.866  1018  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:35.876  7191  7191 E Zygote  : MountEmulatedStorage(),
08-31 11:29:35.876  7191  7191 E Zygote  : v2
08-31 11:29:35.876  7191  7191 I libpersona: KNOX_SDCARD checking this for 10036
08-31 11:29:35.876  7191  7191 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:35.876  7191  7191 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 11:29:35.876  7191  7191 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:35.876  1018  1322 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7191 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 11:29:35.876  1018  1322 I ActivityManager: Killing 6784:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,08-31 11:29:35.876  7174  7189 D SPPClientService: PushLog.txt file is not deleted.
08-31 11:29:35.876  7174  7189 D SPPClientService: PushLog.txt file is not deleted.
,08-31 11:29:35.876  1018  1136 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-31 11:29:35.876  7174  7189 D SPPClientService: ============PushLog. stop!
08-31 11:29:35.876  1018  1136 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
08-31 11:29:35.876  7191  7191 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-31 11:29:35.876  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:35.876  1018  1136 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-31 11:29:35.876  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-31 11:29:35.896  7174  7198 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-31 11:29:35.896  7191  7191 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:35.896  7191  7191 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:35.936  7191  7191 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@b1be611
,08-31 11:29:35.946  7191  7191 I SA      : [SSP] onCreated
,08-31 11:29:35.956  7191  7191 I SA      : [TPM] There is no property file
,08-31 11:29:35.956  7191  7191 I SA      : [SCU] isHaveSA() - false
,08-31 11:29:35.956  7191  7191 I SA      : [TPM] getModelProperty : null
,08-31 11:29:35.956  7191  7191 I SA      : [TPM] getCSCProperty : null
,08-31 11:29:35.966  7191  7191 I SA      : [DM] FLOATING AMOLED FEATURE: true
,08-31 11:29:35.966  7191  7191 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-31 11:29:35.966  7191  7191 I SA      : [DM] TFT FEATURE: false
,08-31 11:29:35.966  7191  7191 I SA      : [DM] init START
,08-31 11:29:35.966  7191  7191 I SA      : [DM] This device is not a Vodafone
,08-31 11:29:35.976  7191  7191 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-31 11:29:35.976  7191  7191 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-31 11:29:35.976  7191  7191 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-31 11:29:35.976  7191  7191 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-31 11:29:35.976  7191  7191 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-31 11:29:35.976  7191  7191 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-31 11:29:35.976  7191  7191 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-31 11:29:35.976  7191  7191 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-31 11:29:35.976  7191  7191 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-31 11:29:35.976  7191  7191 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-31 11:29:35.976  7191  7191 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-31 11:29:35.986  7191  7191 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-31 11:29:35.986  7191  7191 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-31 11:29:35.986  7191  7191 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-31 11:29:35.986  7191  7191 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-31 11:29:35.986  7191  7191 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-31 11:29:35.986  7191  7191 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,08-31 11:29:35.986  7191  7191 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-31 11:29:35.986  7191  7191 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-31 11:29:35.986  7191  7191 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-31 11:29:35.986  7191  7191 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-31 11:29:35.986  7191  7191 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-31 11:29:35.986  7191  7191 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-31 11:29:35.986  7191  7191 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-31 11:29:35.986  7191  7191 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-31 11:29:35.986  7191  7191 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-31 11:29:35.986  7191  7191 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,08-31 11:29:35.996  7191  7191 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-31 11:29:35.996  7191  7191 I SA      : [SCU] isHaveSA() - false
08-31 11:29:35.996  7191  7191 I SA      : support phone number id : false
08-31 11:29:35.996  7191  7191 I SA      : [DM] Supports Ref Jpn : true
,08-31 11:29:35.996  7191  7191 I SA      : [DM] init END
,08-31 11:29:35.996  7191  7191 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-31 11:29:35.996  7191  7191 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-31 11:29:35.996  7191  7191 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-31 11:29:35.996  7191  7191 I SA      : [SLFUCHKMGR] constructor called,
,08-31 11:29:36.006  7191  7191 I SA      : [TPMU]  strSIMState ,	:SIM_STATE_ABSENT
08-31 11:29:36.006  7191  7191 I SA      : [OR] == isSIMCardReady false ==
,08-31 11:29:36.006  7191  7191 I SA      : [SCU] == networkStateCheck == false
08-31 11:29:36.006  7191  7191 I SA      : [OR] onReceive END
,08-31 11:29:36.006  1018  1030 I ActivityManager: Killing 6871:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-31 11:29:36.016  1225  1225 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:29:36.016  1891  1891 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-31 11:29:36.026  2702  2707 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2,
08-31 11:29:36.026  1891  1891 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
08-31 11:29:36.026  1891  1891 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-31 11:29:36.026  1891  1891 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-31 11:29:36.026  1891  1891 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-31 11:29:36.026  1891  1891 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-31 11:29:36.036  1891  1891 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-31 11:29:36.036  1018  1496 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-31 11:29:36.036  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:36.036  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:36.036  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:36.036  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:36.046  7213  7213 E Zygote  : MountEmulatedStorage(),
08-31 11:29:36.046  1018  1496 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7213 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 11:29:36.046  7213  7213 E Zygote  : v2
08-31 11:29:36.046  7213  7213 I libpersona: KNOX_SDCARD checking this for 10077
08-31 11:29:36.046  7213  7213 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-31 11:29:36.046  7213  7213 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:36.046  7213  7213 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:36.056  7213  7213 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL,
,08-31 11:29:36.066  7213  7213 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 11:29:36.066  7213  7213 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:36.166  1018  3256 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-31 11:29:36.166  1018  3256 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-31 11:29:36.166  1018  3256 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:36.166  1018  3256 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:36.166  1018  3256 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-31 11:29:36.176  1018  1320 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-31 11:29:36.176  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:36.176  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:36.176  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:36.176  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:36.186  7231  7231 E Zygote  : MountEmulatedStorage()
,08-31 11:29:36.186  1018  1320 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7231 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 11:29:36.186  7231  7231 E Zygote  : v2
08-31 11:29:36.186  7231  7231 I libpersona: KNOX_SDCARD checking this for 10110
08-31 11:29:36.186  7231  7231 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:36.196  7231  7231 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:29:36.196  1018  1489 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-31 11:29:36.196  1018  1489 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-31 11:29:36.196  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:36.196  1018  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:36.196  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-31 11:29:36.196  7231  7231 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:36.196  7231  7231 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
08-31 11:29:36.206  7032  7230 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-31 11:29:36.216  1018  1494 I ActivityManager: Killing 6887:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-31 11:29:36.226  7231  7231 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:36.226  7231  7231 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:36.276  1018  1494 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-31 11:29:36.356   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-31 11:29:36.356   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 11:29:36.356  7231  7249 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-31 11:29:36.366   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-31 11:29:36.366   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 11:29:36.366  7231  7249 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-31 11:29:36.376  7231  7231 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-31 11:29:36.376  7231  7231 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-31 11:29:36.376  7231  7231 I GAv4    :   adb logcat -s GAv4
,08-31 11:29:36.386   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-31 11:29:36.386   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 11:29:36.386  7231  7250 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-31 11:29:36.386   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-31 11:29:36.386   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 11:29:36.386  7231  7250 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-31 11:29:36.396  7231  7231 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-31 11:29:36.396  1018  3255 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-31 11:29:36.406  7231  7231 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-31 11:29:36.416  7231  7252 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-31 11:29:36.646  1018  1322 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:36.646  1018  1322 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:36.646  1018  1322 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:36.646  1018  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-31 11:29:36.646  7231  7231 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-31 11:29:36.656  1018  3256 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-31 11:29:36.656  1018  3256 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-31 11:29:36.656  1018  3256 D SecContentProvider2: mCursor = null
,08-31 11:29:36.656  1018  3256 D WifiService: setWifiEnabled: true pid=6662, uid=10170
,08-31 11:29:36.656  1018  3256 W ActivityManager: Permission Denial: getCurrentUser() from pid=6662, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-31 11:29:36.656  1018  3256 W WifiService: Failed getting userId using ActivityManagerNative
08-31 11:29:36.656  1018  3256 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6662, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-31 11:29:36.656  1018  3256 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 11:29:36.656  1018  3256 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-31 11:29:36.656  1018  3256 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-31 11:29:36.656  1018  3256 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-31 11:29:36.656  1018  3256 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-31 11:29:36.656  1018  3256 D SettingsProvider: name = wifi_on
,08-31 11:29:36.656  1018  1128 E WifiHW  : ##################### set firmware type 0 #####################
,08-31 11:29:36.676  7231  7231 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 5010-5012)
,08-31 11:29:36.676  7231  7231 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-31 11:29:36.686  7231  7231 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2dafe110}
,08-31 11:29:36.686  7231  7231 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-31 11:29:36.686  7231  7231 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 11:29:36.706  7231  7231 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-31 11:29:36.706   325   325 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 11:29:36.706  7231  7231 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 11:29:36.716  7231  7231 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 11:29:36.736  7231  7231 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 11:29:36.736  7231  7231 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 11:29:36.736  7231  7231 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 11:29:36.736  7231  7231 I Adreno-EGL: Local Branch: 
08-31 11:29:36.736  7231  7231 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 11:29:36.736  7231  7231 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 11:29:36.736  7231  7231 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 11:29:36.896  7231  7231 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-31 11:29:36.906  7231  7287 W cr.media: Requires BLUETOOTH permission
08-31 11:29:36.906  7231  7231 I NSApplication: Starting up...
,08-31 11:29:36.906  1018  1031 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-31 11:29:36.916  1018  1322 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-31 11:29:36.916  1018  1489 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-31 11:29:36.916  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:36.916  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:36.916  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:36.916  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:36.936  7292  7292 E Zygote  : MountEmulatedStorage()
,08-31 11:29:36.936  7292  7292 E Zygote  : v2
08-31 11:29:36.936  7292  7292 I libpersona: KNOX_SDCARD checking this for 10117
08-31 11:29:36.936  7292  7292 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:36.936  7292  7292 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:36.936  1018  1489 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7292 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-31 11:29:36.936  1018  1489 I ActivityManager: Killing 6840:com.android.providers.calendar/u0a37 (adj 15): empty #21
08-31 11:29:36.936  7292  7292 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:36.946  7292  7292 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 11:29:36.966  7292  7292 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:36.966  7292  7292 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:36.986  7292  7292 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 11:29:37.016  1018  1045 D Tethering: interfaceAdded wlan0
,08-31 11:29:37.026  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:29:37.026  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:37.026  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:29:37.026  1018  1131 E Tethering: No numeric data
,08-31 11:29:37.026  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-31 11:29:37.026  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:37.026  1190  1190 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-31 11:29:37.036  1190  1190 D HotspotTile: updateTetherState():false, false
08-31 11:29:37.036  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:29:37.036  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:29:37.036  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 11:29:37.036  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 11:29:37.036  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-31 11:29:37.036  1018  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 11:29:37.036  1018  1131 D Tethering: clearTetheredNotification()
08-31 11:29:37.036  1018  1131 D Tethering: InitialState.processMessage what=4
08-31 11:29:37.036   277   967 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-31 11:29:37.036   277   967 D SoftapController: Softap fwReload - Ok
08-31 11:29:37.036  1018  1045 D Tethering: interfaceAdded p2p0
,08-31 11:29:37.036  1018  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-31 11:29:37.036  1018  1125 V NetworkStats: performPollLocked() took 7ms
08-31 11:29:37.036  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:37.036   277   967 D CommandListener: Setting iface cfg
08-31 11:29:37.036   277   967 D CommandListener: Trying to bring down wlan0
,08-31 11:29:37.036   277   967 D CommandListener: Clearing all IP addresses on wlan0
08-31 11:29:37.036  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:37.036  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:37.036  1018  1131 E Tethering: No numeric data
08-31 11:29:37.036  1018  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 11:29:37.036  1018  1131 D Tethering: clearTetheredNotification()
,08-31 11:29:37.036  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
08-31 11:29:37.036  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:37.046  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-31 11:29:37.046  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:29:37.046  1190  1190 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 11:29:37.046  1018  1128 E WifiHW  : supplicant_name : p2p_supplicant
,08-31 11:29:37.046  1190  1190 D HotspotTile: updateTetherState():false, false,
08-31 11:29:37.046  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:37.046  1018  1125 V NetworkStats: performPollLocked() took 4ms
,08-31 11:29:37.046  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:37.046  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:37.096  7310  7310 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
08-31 11:29:37.096  7310  7310 I wpa_supplicant: Successfully initialized wpa_supplicant
08-31 11:29:37.096  7310  7310 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-31 11:29:37.106  7310  7310 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-31 11:29:37.106   396   396 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7310
08-31 11:29:37.106   396   396 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
,08-31 11:29:37.106  7310  7310 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-31 11:29:37.106  7310  7310 I wpa_supplicant: ssSupport state is = 1
08-31 11:29:37.106  7310  7310 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-31 11:29:37.106  7310  7310 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-31 11:29:37.116   396   396 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7310
08-31 11:29:37.116   396   396 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-31 11:29:37.146  1018  1128 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,08-31 11:29:37.156  4482  4482 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
08-31 11:29:37.156  1190  1190 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-31 11:29:37.156  1190  1190 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:29:37.156  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:37.156  1190  1716 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 11:29:37.156  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 11:29:37.156  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:37.156  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:37.156  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:37.156  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:37.156  1190  1190 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:29:37.156  1190  1190 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-31 11:29:37.166  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-31 11:29:37.166  1190  1190 D HotspotTile: onReceive : 2, 0
08-31 11:29:37.166  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:37.286   396   396 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-31 11:29:37.286  7310  7310 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed,
,08-31 11:29:37.326  1018  1320 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-31 11:29:37.326  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:37.326  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:37.326  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:37.326  1018  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:37.336  7310  7310 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-31 11:29:37.336  7310  7310 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-31 11:29:37.336  7316  7316 E Zygote  : MountEmulatedStorage()
,08-31 11:29:37.336  7316  7316 E Zygote  : v2
08-31 11:29:37.336  7316  7316 I libpersona: KNOX_SDCARD checking this for 10121
08-31 11:29:37.336  7316  7316 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:37.346  1018  1320 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7316 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-31 11:29:37.346  7316  7316 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 11:29:37.346  1018  1320 I ActivityManager: Killing 6802:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-31 11:29:37.346  7316  7316 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:37.356  7316  7316 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:37.356  7310  7310 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-31 11:29:37.356   396   396 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7310
08-31 11:29:37.356   396   396 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-31 11:29:37.356  7310  7310 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-31 11:29:37.356  7310  7310 I wpa_supplicant: ssSupport state is = 1
08-31 11:29:37.356  7310  7310 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-31 11:29:37.356  7310  7310 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 11:29:37.356  7310  7310 E wpa_supplicant: SIM READ ERROR
08-31 11:29:37.356  7310  7310 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 11:29:37.356  7310  7310 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 11:29:37.356  7310  7310 E wpa_supplicant: SIM READ ERROR
08-31 11:29:37.356  7310  7310 I wpa_supplicant: Blacklist: Clear (all) 
08-31 11:29:37.366  7310  7310 I wpa_supplicant: wpa_default_ap_write_once
08-31 11:29:37.366  7310  7310 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 11:29:37.366  7310  7310 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 11:29:37.366  7310  7310 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-31 11:29:37.366  7310  7310 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 11:29:37.366  7310  7310 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-31 11:29:37.366  7310  7310 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-31 11:29:37.366  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:29:37.366  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:37.366  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:29:37.376  7316  7316 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:37.376  7316  7316 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:37.386  7316  7316 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:29:37.386  7316  7316 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-31 11:29:37.386  7316  7316 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 11:29:37.406  7316  7316 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:29:37.406  7316  7316 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-31 11:29:37.406  7316  7316 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-31 11:29:37.406  1018  1322 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
08-31 11:29:37.406  1018  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:37.406  1018  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:37.406  1018  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:37.406  1018  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-31 11:29:37.416  7310  7310 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-31 11:29:37.426  7334  7334 E Zygote  : MountEmulatedStorage()
08-31 11:29:37.426  7334  7334 E Zygote  : v2
08-31 11:29:37.426  7334  7334 I libpersona: KNOX_SDCARD checking this for 10141
08-31 11:29:37.426  7334  7334 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:37.426  7334  7334 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:29:37.426  1018  1322 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7334 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-31 11:29:37.426  1018  1322 I ActivityManager: Killing 6817:com.android.calendar/u0a131 (adj 15): empty #21
,08-31 11:29:37.426  7334  7334 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:37.426  7334  7334 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:37.446  7334  7334 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:37.446  7334  7334 D ActivityThread: Added TimaKeyStore provider,
,08-31 11:29:37.466  7334  7334 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-31 11:29:37.466  7334  7334 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 11:29:37.466  7334  7334 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-31 11:29:37.466  7334  7334 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-31 11:29:37.516  1018  1496 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 11:29:37.526  1018  1218 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 11:29:37.556  1018  1490 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 11:29:37.566  1018  1030 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 11:29:37.616  1018  1720 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-31 11:29:37.616  1018  1720 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:37.616  1018  1720 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:37.616  1018  1720 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:37.616  1018  1720 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:37.616  1018  3255 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 11:29:37.626  7357  7357 E Zygote  : MountEmulatedStorage()
08-31 11:29:37.626  7357  7357 E Zygote  : v2
08-31 11:29:37.626  7357  7357 I libpersona: KNOX_SDCARD checking this for 10068
08-31 11:29:37.626  7357  7357 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:37.626  7357  7357 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:37.636  1018  1720 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7357 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-31 11:29:37.636  1018  1320 D RCPManagerService: exchangeData() failure , invalid userId
08-31 11:29:37.636  7357  7357 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:37.636  7357  7357 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-31 11:29:37.646  1018  1218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-31 11:29:37.646  1018  1218 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4243, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-31 11:29:37.646  1018  1218 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-31 11:29:37.646  1018  1218 D BatteryService: stay LED for charging
,08-31 11:29:37.646  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 11:29:37.646  1018  1018 I MotionRecognitionService: Plugged
08-31 11:29:37.646  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 11:29:37.656  1190  1190 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-31 11:29:37.656  1190  1190 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 11:29:37.656  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-31 11:29:37.656  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-31 11:29:37.656  7310  7310 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-31 11:29:37.656  7310  7310 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-31 11:29:37.676  7310  7310 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-31 11:29:37.676   396   396 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7310
08-31 11:29:37.676   396   396 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-31 11:29:37.676  7310  7310 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-31 11:29:37.676  7310  7310 I wpa_supplicant: ssSupport state is = 1
,08-31 11:29:37.676  7310  7310 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-31 11:29:37.676  7310  7310 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-31 11:29:37.676  7357  7357 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 11:29:37.686  7357  7357 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:37.686  7310  7310 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-31 11:29:37.686  1190  1190 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-31 11:29:37.686  1190  1190 D SViewCoverView: level :100 plugged : 2,
,08-31 11:29:37.686   396   396 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7310,
08-31 11:29:37.686   396   396 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-31 11:29:37.686  7310  7310 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-31 11:29:37.686  7310  7310 I wpa_supplicant: ssSupport state is = 1
,08-31 11:29:37.686  7310  7310 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 11:29:37.686  7310  7310 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-31 11:29:37.686  7310  7310 E wpa_supplicant: SIM READ ERROR
08-31 11:29:37.686  1190  1190 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
08-31 11:29:37.686  1190  1190 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-31 11:29:37.696  7310  7310 I wpa_supplicant: wpa_default_ap_write_once
08-31 11:29:37.696  1190  1190 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-31 11:29:37.696  7310  7310 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,08-31 11:29:37.696  7310  7310 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 11:29:37.696  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-31 11:29:37.696  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 11:29:37.696  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-31 11:29:37.696  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-31 11:29:37.696  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
,08-31 11:29:37.696  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-31 11:29:37.706  1018  3255 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 11:29:37.706  1018  3256 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-31 11:29:37.706   325   325 I ServiceManager: Waiting for service AtCmdFwd...
08-31 11:29:37.716  1018  3256 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:37.716  1018  3256 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:37.716  1018  3256 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:37.716  1018  3256 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:37.716   287   287 E SMD     : DCD OFF
,08-31 11:29:37.716  7357  7357 D BadgeProvider: onCreate
08-31 11:29:37.716  7357  7357 D BadgeProvider: DatabaseHelper
,08-31 11:29:37.726  7375  7375 E Zygote  : MountEmulatedStorage(),
08-31 11:29:37.726  7375  7375 E Zygote  : v2
,08-31 11:29:37.726  7375  7375 I libpersona: KNOX_SDCARD checking this for 10009
08-31 11:29:37.726  7375  7375 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:37.726  7375  7375 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:37.726  1018  3256 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7375 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,08-31 11:29:37.726  1018  3256 I ActivityManager: Killing 6915:com.android.vending/u0a26 (adj 15): empty #21
08-31 11:29:37.736  1018  3256 I ActivityManager: Killing 6605:com.android.defcontainer/u0a3 (adj 15): empty #22
08-31 11:29:37.736  7375  7375 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:37.736  7375  7375 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-31 11:29:37.746  1018  2890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 11:29:37.756  7375  7375 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:37.756  7375  7375 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:37.776  7310  7310 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-31 11:29:37.776  7310  7310 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-31 11:29:37.836  1018  3255 I ActivityManager: Killing 7058:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-31 11:29:37.846  7310  7310 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-31 11:29:37.846  7310  7310 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-31 11:29:37.846  7310  7310 I wpa_supplicant: Skip scan - bUseNetwork false
,08-31 11:29:37.846  1018  1322 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 11:29:37.856  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
08-31 11:29:37.856  1018  1322 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 11:29:37.856  1018  1322 W ActivityManager: userId = 0, bbcId = -10000,
08-31 11:29:37.856  1018  1322 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:37.856  1018  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 11:29:37.856  1018  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-31 11:29:37.856  7310  7310 I wpa_supplicant: HOTSPOT20_ENABLE called
08-31 11:29:37.856  7310  7310 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-31 11:29:37.856  7310  7310 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 11:29:37.856  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-31 11:29:37.856  7310  7310 E wpa_supplicant: SIM READ ERROR
08-31 11:29:37.856  7310  7310 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 11:29:37.856  6849  6849 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 11:29:37.856  6849  6849 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 11:29:37.856  1018  1490 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
08-31 11:29:37.856  6849  6849 D SecurityLogAgent: StateMachine : Current State = 1
08-31 11:29:37.856  6849  6849 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-31 11:29:37.856  1631  1631 I Hs20UtilService: Starting #12
,08-31 11:29:37.866  1631  1655 I Hs20UtilService: Message received 5011
,08-31 11:29:37.866  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-31 11:29:37.866  1018  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-31 11:29:37.876  7310  7310 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-31 11:29:37.886  7310  7310 I wpa_supplicant: Skip scan - bUseNetwork false
,08-31 11:29:37.896  1018  1128 D WifiConfigStore: Loading config and enabling all networks ,
,08-31 11:29:37.896  1190  1190 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:29:37.896  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:37.896  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:29:37.896  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:37.896  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:37.896  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:37.896  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:37.896  1190  1190 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:29:37.896  1190  1190 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-31 11:29:37.896  1190  1190 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:29:37.896  1190  1716 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 11:29:37.896  1190  1190 D HotspotTile: onReceive : 3, 0
,08-31 11:29:37.896  4482  4482 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:29:37.906  6662  6662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:37.906  1018  1128 E WifiConfigStore: Not a HS20
,08-31 11:29:37.906  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:37.906  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:37.906  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:37.906  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:37.906  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:37.906  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:37.906  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:37.906  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:37.906  6662  6662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:29:37.906  6662  6662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:37.906  1018  1128 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-31 11:29:37.906  1018  1322 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 11:29:37.906  1018  1322 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:29:37.906  1018  1322 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:37.906  1018  1322 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:37.906  1018  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:29:37.916  1018  1128 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-31 11:29:37.916  7310  7310 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-31 11:29:37.916  7310  7310 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-31 11:29:37.916  7310  7310 I wpa_supplicant: reset timer : RESET_TIMER 0
08-31 11:29:37.916  7310  7310 I wpa_supplicant: P2P: Current p2p state = IDLE
08-31 11:29:37.916  7310  7310 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-31 11:29:37.916  7310  7310 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-31 11:29:37.916  7310  7310 I wpa_supplicant: First Scan Start
,08-31 11:29:37.916  7310  7310 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-31 11:29:37.916  6662  6662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:37.916  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:37.916  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:37.916  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:37.916  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:37.916  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:37.916  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:37.916  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:37.916  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:37.916  6662  6662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:37.916  6662  6662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:37.916  1631  1631 I Hs20UtilService: Starting #13
08-31 11:29:37.916  1631  1655 I Hs20UtilService: Message received 5011
,08-31 11:29:37.916  1018  1720 I art     : Explicit concurrent mark sweep GC freed 59425(3MB) AllocSpace objects, 12(240KB) LOS objects, 33% free, 23MB/34MB, paused 2.597ms total 182.081ms
,08-31 11:29:37.916  1018  1128 D WifiNative-wlan0: Setting external_sim to 1
,08-31 11:29:37.916  1018  1128 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 11:29:37.916  1018  1128 I WifiNative-HAL: startHal
,08-31 11:29:37.916  1018  1128 E wifi    : getStaticLongField sWifiHalHandle 0x9f26588c
08-31 11:29:37.916  7032  7032 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:29:37.916  1018  1128 I WifiNative-HAL: Could not start hal
,08-31 11:29:37.926  1018  1128 E WifiNative-wlan0: do suspend true
,08-31 11:29:37.926  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-31 11:29:37.926  1018  1127 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-31 11:29:37.926  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 3
,08-31 11:29:37.926  1018  1018 D RttService: SCAN_AVAILABLE : 3
,08-31 11:29:37.926  6849  6849 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 11:29:37.926  1018  1152 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:29:37.926  1018  1152 I WifiNative-HAL: startHal
08-31 11:29:37.926  1018  1152 E wifi    : getStaticLongField sWifiHalHandle 0x9e1279bc
08-31 11:29:37.926  1018  1152 I WifiNative-HAL: Could not start hal
08-31 11:29:37.926  1018  1152 E WifiScanningService: could not start HAL
08-31 11:29:37.926  1018  1153 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 11:29:37.926   277   967 D CommandListener: Setting iface cfg
08-31 11:29:37.926   277   967 D CommandListener: Trying to bring up p2p0
,08-31 11:29:37.926  1018  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 11:29:37.926  6849  6849 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 11:29:37.926  6849  6849 D SecurityLogAgent: StateMachine : Current State = 1
08-31 11:29:37.926  6849  6849 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-31 11:29:37.936  1018  1127 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 11:29:37.936  1018  1127 D WifiP2pService: P2pEnablingState
08-31 11:29:37.936  1018  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 11:29:37.936  1018  1128 E WifiNative-wlan0: invaild command id : 215
,08-31 11:29:37.936  1018  1127 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-31 11:29:37.936  7310  7310 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 11:29:37.936  7310  7310 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 11:29:37.936  1018  1127 D WifiP2pService: P2p socket connection successful
,08-31 11:29:37.936  7357  7371 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
08-31 11:29:37.936  1018  1127 D WifiP2pService: P2pEnabledState
,08-31 11:29:37.946  1018  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-31 11:29:37.946  1018  1130 E ConnectivityService: updateNetworkInfo()
08-31 11:29:37.946  7310  7310 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-31 11:29:37.946  1018  1128 E WifiStateMachine: Failed to set frequency band 0
,08-31 11:29:37.946  1018  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 11:29:37.946  1018  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 11:29:37.946  1018  1128 E WifiNative-wlan0: invaild command id : 215
,08-31 11:29:37.946  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:29:37.946  1018  1128 D SecContentProvider2: mCursor = null
,08-31 11:29:37.946  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-31 11:29:37.946  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-31 11:29:37.946  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 11:29:37.946  1018  1048 D WifiDisplayController: disconnect
08-31 11:29:37.946  1018  1048 D WifiDisplayController: updateConnection
08-31 11:29:37.946  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 11:29:37.946  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 11:29:37.946  1018  1127 D WifiNative-p2p0: p2pGetDeviceAddress
08-31 11:29:37.946  1018  1127 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-31 11:29:37.956  4482  4482 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-31 11:29:37.956  4482  4482 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 11:29:37.956  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:29:37.956  1018  1128 D SecContentProvider2: mCursor = null
08-31 11:29:37.956  1018  1127 D WifiP2pService: DeviceAddress: 0a:75:42
,08-31 11:29:37.956  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 11:29:37.956  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:29:37.956  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-31 11:29:37.956  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 11:29:37.956  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
08-31 11:29:37.956  1018  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-31 11:29:37.956  1018  1048 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-31 11:29:37.956  1018  1048 D WifiDisplayController:  primary type: 10-0050F204-5
08-31 11:29:37.956  1018  1048 D WifiDisplayController:  secondary type: null
08-31 11:29:37.956  1018  1048 D WifiDisplayController:  wps: 0
08-31 11:29:37.956  1018  1048 D WifiDisplayController:  grpcapab: 0
08-31 11:29:37.956  1018  1048 D WifiDisplayController:  devcapab: 0
08-31 11:29:37.956  1018  1048 D WifiDisplayController:  status: 3
08-31 11:29:37.956  1018  1048 D WifiDisplayController:  wfdInfo: null
08-31 11:29:37.956  1018  1048 D WifiDisplayController:  groupownerAddress: null
08-31 11:29:37.956  1018  1048 D WifiDisplayController:  GOdeviceName: null
08-31 11:29:37.956  1018  1048 D WifiDisplayController:  interfaceAddress: 
08-31 11:29:37.956  1018  1048 D WifiDisplayController:  SConnectInfo : null
,08-31 11:29:37.956  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 11:29:37.956  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 11:29:37.956  4482  4482 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 11:29:37.956  4482  4521 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 11:29:37.966  1190  1190 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-31 11:29:37.966  1018  1490 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
08-31 11:29:37.966  1190  1190 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-31 11:29:37.966  1018  1322 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-31 11:29:37.966  1018  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:37.966  1018  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:37.966  1018  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:37.966  1018  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:37.976  7357  7373 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-31 11:29:37.976  7357  7373 D BadgeProvider: sendNotify, [notify] : null
08-31 11:29:37.976  7357  7373 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
,08-31 11:29:37.976  7357  7373 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-31 11:29:37.976  7357  7373 D BadgeProvider: update, [UpdateCount] : 1
,08-31 11:29:37.976  7397  7397 E Zygote  : MountEmulatedStorage()
,08-31 11:29:37.976  7397  7397 I libpersona: KNOX_SDCARD checking this for 10064
08-31 11:29:37.976  7397  7397 E Zygote  : v2
08-31 11:29:37.976  7397  7397 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:37.976  7397  7397 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:29:37.986  1018  1322 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7397 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 11:29:37.976  7397  7397 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:37.986  1018  1127 D WifiP2pService: sending p2p persistent groups changed broadcast
08-31 11:29:37.986  1491  1491 D Launcher.Model: reloadBadges entered.
,08-31 11:29:37.986  1018  1127 D WifiP2pService: InactiveState
08-31 11:29:37.986  1018  1127 D WifiP2pService: InactiveState{ what=143376 }
08-31 11:29:37.986  1018  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
08-31 11:29:37.986  7397  7397 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:37.986  7310  7310 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 11:29:37.986  1018  1127 D WifiP2pService: InactiveState{ what=143376 }
,08-31 11:29:37.986  1018  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 11:29:38.006  7397  7397 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 11:29:38.006  7397  7397 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:38.006   309   309 I art     : Explicit concurrent mark sweep GC freed 8656(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 608us total 29.859ms
,08-31 11:29:38.016  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 11:29:38.016  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 11:29:38.016  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-31 11:29:38.016  7397  7397 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-31 11:29:38.026   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 565us total 16.704ms
,08-31 11:29:38.026  7397  7397 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 11:29:38.036  7397  7397 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-31 11:29:38.046   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 568us total 16.258ms,
,08-31 11:29:38.056  7397  7397 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 11:29:38.066  7073  7073 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 11:29:38.066  1018  1494 I ActivityManager: Killing 6968:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-31 11:29:38.716   325   325 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 11:29:39.076  5932  5932 D FactoryTest: Not factory mode,
08-31 11:29:39.076  5932  5932 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-31 11:29:39.076  5932  5932 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-31 11:29:39.076  5932  5932 D MTPRx   : still no open session command from host, so toast,
,08-31 11:29:39.076  5932  5932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
08-31 11:29:39.076  5932  5932 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-31 11:29:39.086  5932  5932 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:117421,
08-31 11:29:39.086  1018  3256 E PersonaManagerService: inState():  stateMachine is null !!
08-31 11:29:39.086  1018  3256 I PersonaManagerService: PersonaId don't exist
08-31 11:29:39.086  1018  3256 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-31 11:29:39.086  1018  3256 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,08-31 11:29:39.086  1018  3256 W ActivityManager: userId = 0, bbcId = -10000,
08-31 11:29:39.086  1018  3256 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:39.086  1018  3256 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-31 11:29:39.096  1018  3256 W ActivityManager: mDVFSHelper.acquire(),
,08-31 11:29:39.106  1018  3256 D PersonaManager: isKioskContainerExistOnDevice
,08-31 11:29:39.116  1018  3256 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-31 11:29:39.116  1018  3256 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
08-31 11:29:39.116  1018  3256 D InputDispatcher: Focused application set to: xxxx,
08-31 11:29:39.116  1018  3256 D InputDispatcher: Focus left window: 6662,
08-31 11:29:39.116  5932  5932 E MTPRx   : started activity for popup
,08-31 11:29:39.126  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-31 11:29:39.126  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-31 11:29:39.136  5932  5932 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-31 11:29:39.146  5932  5932 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-31 11:29:39.146  5932  5932 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-31 11:29:39.146  5932  5932 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 11:29:39.146  5932  5932 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-31 11:29:39.146  7310  7310 I wpa_supplicant: nl80211: Received scan results (26 BSSes),
08-31 11:29:39.146  5932  5932 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 11:29:39.146  7310  7310 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-31 11:29:39.146  7310  7310 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-31 11:29:39.146  7310  7310 I wpa_supplicant: Trying to associate with  'G700'
,08-31 11:29:39.146  7310  7310 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-31 11:29:39.146  7310  7310 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-31 11:29:39.146  1018  7392 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-31 11:29:39.156  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 11:29:39.166  1018  1128 D SecContentProvider2: mCursor = null
,08-31 11:29:39.176  5932  5932 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-31 11:29:39.186  1018  1730 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-31 11:29:39.186  1018  1730 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-31 11:29:39.186  1018  1730 D InputDispatcher: Focused application set to: xxxx
,08-31 11:29:39.186  1018  1730 D InputDispatcher: Focus entered window: 6662
,08-31 11:29:39.186  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-31 11:29:39.186  1018  1494 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-31 11:29:39.186  1018  1494 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@238a6568 attribute=null, token = android.os.BinderProxy@dada6cd
,08-31 11:29:39.186  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-31 11:29:39.226  5932  5932 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-31 11:29:39.226  5932  5932 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-31 11:29:39.226  5932  5932 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-31 11:29:39.256  6662  6662 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-31 11:29:39.256  6662  6662 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-31 11:29:39.256  6662  6662 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-31 11:29:39.256  6662  6662 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-31 11:29:39.256  1018  1490 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-31 11:29:39.256  1018  1490 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-31 11:29:39.256  1018  1490 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-31 11:29:39.256  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-31 11:29:39.256  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,08-31 11:29:39.266  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
08-31 11:29:39.266  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:39.266  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-31 11:29:39.266  7310  7310 E wpa_supplicant: Cmd 35605 not handled
08-31 11:29:39.266  7310  7310 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-31 11:29:39.266  7310  7310 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,08-31 11:29:39.266  7310  7310 I wpa_supplicant: Associated with F4.99.3E
08-31 11:29:39.266  7310  7310 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 11:29:39.266  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:39.266  7310  7310 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-31 11:29:39.266  7310  7310 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-31 11:29:39.266  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,08-31 11:29:39.266  1018  1045 D Tethering: interfaceStatusChanged wlan0, false,
08-31 11:29:39.266  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:29:39.266  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:39.266  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:29:39.266  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 11:29:39.266  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true,
08-31 11:29:39.266  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
08-31 11:29:39.266  1018  1131 E Tethering: No numeric data
,08-31 11:29:39.266  1018  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 11:29:39.266  1018  1131 D Tethering: clearTetheredNotification()
,08-31 11:29:39.266  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
,08-31 11:29:39.266  1018  1128 D SecContentProvider2: mCursor = null
08-31 11:29:39.276  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
08-31 11:29:39.276  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:39.276  1190  1190 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 11:29:39.276  7310  7310 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 11:29:39.276  1190  1190 D HotspotTile: updateTetherState():false, false
08-31 11:29:39.276  7310  7310 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-31 11:29:39.276  7310  7310 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-31 11:29:39.276  7310  7310 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-31 11:29:39.276  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:29:39.276  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 11:29:39.276  7310  7310 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 11:29:39.276  7310  7310 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,08-31 11:29:39.276  7310  7310 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-31 11:29:39.276  1018  1125 V NetworkStats: performPollLocked() took 4ms
08-31 11:29:39.276  7310  7310 I wpa_supplicant: Blacklist: Clear (temp) 
08-31 11:29:39.276  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-31 11:29:39.276  7310  7310 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-31 11:29:39.276  6662  6662 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-31 11:29:39.276  6662  6662 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
08-31 11:29:39.276  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:39.276  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:29:39.276  1018  1128 D SecContentProvider2: mCursor = null
08-31 11:29:39.276  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 11:29:39.276  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
08-31 11:29:39.276  6662  6662 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@372a5862 time:117616
,08-31 11:29:39.276  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:39.276  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:39.286  6662  6662 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1d3a33fe Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@1206ce0c, 16908290=android.view.AbsSavedState$1@1206ce0c}, android:focusedViewId=100}]}]
08-31 11:29:39.286  6662  6662 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-31 11:29:39.286  6662  6662 V ActivityThread: updateVisibility : ActivityRecord{28b69d29 token=android.os.BinderProxy@372a5862 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-31 11:29:39.286  6662  6662 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-31 11:29:39.286  6662  6662 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-31 11:29:39.286  1018  1128 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-31 11:29:39.296  1018  1720 D PersonaManager: isKioskContainerExistOnDevice
,08-31 11:29:39.296  1018  1128 E WifiConfigStore: setLastSelectedConfiguration -1,
,08-31 11:29:39.306  1018  1128 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-31 11:29:39.306  1018  1130 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-31 11:29:39.306  1018  1130 E ConnectivityService: updateNetworkInfo()
08-31 11:29:39.306  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-31 11:29:39.306  1018  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:29:39.306  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 11:29:39.306  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 11:29:39.306  1190  1190 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:29:39.306  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:39.306  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:39.306  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 11:29:39.306  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:39.306  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:29:39.306  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:39.306  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:39.306  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:39.306  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:39.306  4482  4482 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 11:29:39.316  4482  4482 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 11:29:39.316  1631  1631 I Hs20UtilService: Starting #14
08-31 11:29:39.316  1018  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:29:39.316  1631  1655 I Hs20UtilService: Message received 5007
,08-31 11:29:39.316  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 11:29:39.316  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 11:29:39.316  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 11:29:39.316  4482  4482 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 11:29:39.316  4482  4521 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 11:29:39.326   277   967 D CommandListener: Setting iface cfg
,08-31 11:29:39.326  1018  1128 E WifiStateMachine: Start Dhcp Watchdog 2
,08-31 11:29:39.326  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 11:29:39.326  1018  1128 D SecContentProvider2: mCursor = null
,08-31 11:29:39.336  1190  1190 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:29:39.336  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 11:29:39.336  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:29:39.336  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:29:39.336  1018  1128 D SecContentProvider2: mCursor = null
,08-31 11:29:39.336  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:39.346  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:39.346  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:39.346  1018  1128 E WifiNative-wlan0: do suspend false
08-31 11:29:39.346  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:39.346  1018  1127 D WifiP2pService: InactiveState{ what=143375 }
,08-31 11:29:39.346  1018  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 11:29:39.516  1018  1096 V AlarmManager: waitForAlarm result :4
,08-31 11:29:39.516   277   963 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 11:29:39.516   277   963 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-31 11:29:39.526  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:39.526  1018  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:39.526  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-31 11:29:39.556  7419  7419 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-31 11:29:39.556  7419  7419 I dhcpcd  : version 5.5.6 starting,
,08-31 11:29:39.566  7419  7419 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-31 11:29:39.606  7419  7419 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-31 11:29:39.606  7419  7419 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-31 11:29:39.606  7419  7419 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
08-31 11:29:39.606  7419  7419 I dhcpcd  : bssid match
,08-31 11:29:39.606  7419  7419 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-31 11:29:39.656  7419  7419 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,08-31 11:29:39.666  1018  1030 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-31 11:29:39.666  1018  1030 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-31 11:29:39.666  1018  1030 D SecContentProvider2: mCursor = null
,08-31 11:29:39.666  1018  1030 D WifiService: setWifiEnabled: false pid=6662, uid=10170
,08-31 11:29:39.666  1018  1030 D SettingsProvider: name = wifi_on
,08-31 11:29:39.676  1018  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:29:39.686  1018  1128 E WifiNative-wlan0: do suspend true,
,08-31 11:29:39.706  1018  1127 D WifiP2pService: InactiveState{ what=143375 },
08-31 11:29:39.706  1018  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
08-31 11:29:39.716   277   967 D CommandListener: Clearing all IP addresses on wlan0
08-31 11:29:39.716  7419  7419 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,08-31 11:29:39.716   325   325 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 11:29:39.716  1018  1130 E ConnectivityService: updateNetworkInfo(),
08-31 11:29:39.716  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps],
08-31 11:29:39.716   277   967 E Netd    : no such netId 503
08-31 11:29:39.716  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0,
08-31 11:29:39.716  1190  1190 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:29:39.716  1018  1130 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
08-31 11:29:39.716  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:39.716  1018  1130 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null,
08-31 11:29:39.716  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:29:39.716  1018  1130 V NetworkStats: updateIfacesLocked()
08-31 11:29:39.716  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-31 11:29:39.716  1018  1130 V NetworkStats: performPollLocked(flags=0x1)
08-31 11:29:39.716  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:39.716  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:29:39.716  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 11:29:39.726  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:39.726  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:39.726  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:39.726  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:39.726  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:39.726  1018  1130 V NetworkStats: performPollLocked() took 6ms
,08-31 11:29:39.736  1018  1127 D WifiP2pService: InactiveState{ what=131204 }
08-31 11:29:39.736  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 1
08-31 11:29:39.736  1018  1127 D WifiP2pService: P2pEnabledState{ what=131204 }
08-31 11:29:39.736  1018  1152 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 11:29:39.736  1018  1018 D RttService: SCAN_AVAILABLE : 1
08-31 11:29:39.736  1018  1128 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 11:29:39.736  1018  1153 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:29:39.736  1018  1127 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-31 11:29:39.736  1018  1130 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-31 11:29:39.736  1018  1130 D ConnectivityService: nai.networkMonitor.doQuit()
08-31 11:29:39.736  1018  1130 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-31 11:29:39.736  1018  7415 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:29:39.736  1018  1130 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-31 11:29:39.736  1018  1130 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
,08-31 11:29:39.736  1018  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-31 11:29:39.736  1018  7415 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-31 11:29:39.736  1018  1130 E ConnectivityService: updateNetworkInfo()
08-31 11:29:39.736  1018  1130 E ConnectivityService: updateNetworkInfo()
08-31 11:29:39.736  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:39.736  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:39.736  1190  1190 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-31 11:29:39.736  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:29:39.736  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-31 11:29:39.736  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 11:29:39.736  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-31 11:29:39.736  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:39.736  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:29:39.736  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:39.736  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:39.736  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:39.736  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:39.736  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-31 11:29:39.736  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-31 11:29:39.736  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 11:29:39.736  1018  1048 D WifiDisplayController: disconnect
08-31 11:29:39.736  1018  1048 D WifiDisplayController: updateConnection,
,08-31 11:29:39.736  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 11:29:39.736  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 11:29:39.746  1190  1190 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED,
08-31 11:29:39.746  1018  1730 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 11:29:39.746  1018  1496 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 11:29:39.746  1018  1496 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:29:39.746  1018  1127 D WifiP2pService: P2pDisablingState
08-31 11:29:39.746  1018  1496 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:39.746  1018  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:39.746  1018  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 11:29:39.746  1018  1127 D WifiP2pService: P2pDisablingState{ what=147458 }
08-31 11:29:39.746  1018  1127 D WifiP2pService: p2p socket connection lost,
08-31 11:29:39.746  1018  1127 D WifiP2pService: P2pDisabledState
08-31 11:29:39.756  1631  1631 I Hs20UtilService: Starting #15
08-31 11:29:39.756  1190  1190 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-31 11:29:39.756  1018  1128 E WifiNative-wlan0: do suspend true
,08-31 11:29:39.756  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-31 11:29:39.756  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
,08-31 11:29:39.756  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 11:29:39.756  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-31 11:29:39.756  1631  1655 I Hs20UtilService: Message received 5007
08-31 11:29:39.756  4482  4482 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 11:29:39.756  4482  4482 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-31 11:29:39.756  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 11:29:39.756  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 11:29:39.756  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 11:29:39.756  4482  4482 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 11:29:39.756  4482  4521 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 11:29:39.766  4482  4482 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-31 11:29:39.766  4482  4482 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 11:29:39.766  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 11:29:39.766  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 11:29:39.766  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 11:29:39.766  4482  4482 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 11:29:39.766  4482  4521 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 11:29:39.776  7397  7397 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-31 11:29:39.776  7397  7397 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected,
08-31 11:29:39.776  7397  7397 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 11:29:39.776  7073  7073 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-31 11:29:39.776  1018  1127 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-31 11:29:39.776  1018  1127 D WifiP2pService: DefaultState{ what=143375 }
,08-31 11:29:39.786  1190  1190 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-31 11:29:39.786  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:39.786  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:29:39.786  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:39.786  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:39.786  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:39.786  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:39.796   277   967 D CommandListener: Clearing all IP addresses on wlan0
,08-31 11:29:39.796  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-31 11:29:39.796  7310  7310 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED,
,08-31 11:29:39.806  1190  1190 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-31 11:29:39.806  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-31 11:29:39.806  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:29:39.806  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:39.806  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:39.806  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-31 11:29:39.816  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:39.816  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:29:39.816  1018  1128 D SecContentProvider2: mCursor = null
,08-31 11:29:39.816  4482  4482 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:29:39.816  1018  1031 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 11:29:39.816  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:29:39.826  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:39.826  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:39.826  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:29:39.826  6662  6662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:39.826  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:39.826  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:39.826  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:39.826  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:39.826  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:39.826  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:39.826  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:39.826  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:39.826  6662  6662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:39.826  6662  6662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:39.826  1190  1190 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:29:39.826  1190  1190 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:29:39.826  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:39.826  1190  1716 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 11:29:39.826  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null,
08-31 11:29:39.826  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:39.826  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:39.836  1190  1190 D HotspotTile: onReceive : 0, 0
08-31 11:29:39.826  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:39.826  6662  6662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:39.826  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:39.826  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:39.826  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:39.826  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:39.826  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:39.826  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:39.826  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:39.826  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:39.826  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:39.826  1190  1190 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:29:39.826  1190  1190 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-31 11:29:39.826  6662  6662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 11:29:39.826  6662  6662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:39.836  4482  4482 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 11:29:39.836  4482  4482 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-31 11:29:39.836  1631  1631 I Hs20UtilService: Starting #16
08-31 11:29:39.836  1631  1655 I Hs20UtilService: Message received 5007
08-31 11:29:39.836  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 11:29:39.836  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 11:29:39.836  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-31 11:29:39.836  4482  4482 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 11:29:39.836  4482  4521 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 11:29:39.856  1018  1730 W ActivityManager: userId = 0, bbcId = -10000,
08-31 11:29:39.856  1018  1730 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 11:29:39.856  1018  1730 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-31 11:29:39.856  1018  1730 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
08-31 11:29:39.856  1018  1730 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 11:29:39.856  1631  1631 I Hs20UtilService: Starting #17
,08-31 11:29:39.856  6849  6849 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 11:29:39.856  6849  6849 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 11:29:39.856  6849  6849 D SecurityLogAgent: StateMachine : Current State = 1
08-31 11:29:39.856  6849  6849 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-31 11:29:39.856  1631  1655 I Hs20UtilService: Message received 5011
,08-31 11:29:39.896  7310  7310 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 11:29:39.976  7310  7310 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-31 11:29:39.976  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 11:29:39.976  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
08-31 11:29:39.976  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-31 11:29:39.996  7310  7310 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
08-31 11:29:39.996  7310  7310 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
,08-31 11:29:39.996  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:29:39.996  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:39.996  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-31 11:29:39.996  1018  1131 D Tethering: InitialState.processMessage what=4
,08-31 11:29:40.006  1018  1131 E Tethering: No numeric data
08-31 11:29:40.006  1018  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-31 11:29:40.006  1018  1131 D Tethering: clearTetheredNotification()
08-31 11:29:40.006  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:40.006  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-31 11:29:40.006  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:29:40.006  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:29:40.006  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:29:40.006  1190  1190 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
,08-31 11:29:40.006  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:29:40.006  1190  1190 D HotspotTile: updateTetherState():false, false
08-31 11:29:40.006  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:40.006  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:40.006  7310  7310 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-31 11:29:40.006  1018  1125 V NetworkStats: performPollLocked() took 2ms
08-31 11:29:40.006  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:40.006  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 11:29:40.006  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:40.006  7310  7310 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-31 11:29:40.006  7310  7310 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-31 11:29:40.006  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:29:40.006  1018  1045 D Tethering: interfaceStatusChanged wlan0, false,
,08-31 11:29:40.206  7310  7310 I wpa_supplicant: Blacklist: Clear (all) ,
,08-31 11:29:40.256  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
08-31 11:29:40.256  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:40.256  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:29:40.296  7310  7310 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,08-31 11:29:40.296  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:29:40.296  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:40.296  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:29:40.406  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-31 11:29:40.406  1018  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-31 11:29:40.406  1190  1190 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:29:40.406  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 11:29:40.406  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-31 11:29:40.406  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:40.406  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:40.416  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:40.416  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:40.416  1190  1190 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:29:40.416  1190  1190 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 11:29:40.416  1190  1190 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-31 11:29:40.416  1190  1716 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 11:29:40.416  7032  7032 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:29:40.416  1190  1190 D HotspotTile: onReceive : 1, 0
,08-31 11:29:40.416  4482  4482 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:29:40.416  1739  2188 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 11:29:40.416  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:40.416  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:40.426  1018  1031 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 11:29:40.426  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:29:40.426  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:40.426  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:40.426  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:29:40.426  1631  1631 I Hs20UtilService: Starting #18
,08-31 11:29:40.426  6849  6849 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 11:29:40.426  6849  6849 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 11:29:40.426  6849  6849 D SecurityLogAgent: StateMachine : Current State = 1
08-31 11:29:40.426  6849  6849 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 11:29:40.436  1631  1655 I Hs20UtilService: Message received 5011
,08-31 11:29:40.726   325   325 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
08-31 11:29:40.726   287   287 E SMD     : DCD OFF
,08-31 11:29:41.126  1018  1045 D Tethering: interfaceRemoved wlan0
,08-31 11:29:41.126  1018  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-31 11:29:41.346  1018  1045 D Tethering: interfaceRemoved p2p0,
08-31 11:29:41.346  1018  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-31 11:29:42.106  1018  1043 W ActivityManager: mDVFSHelper.release()
,08-31 11:29:42.116  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-31 11:29:42.666  6662  6834 D BluetoothAdapter: enable()
,08-31 11:29:42.676  1018  1218 W ActivityManager: Permission Denial: getCurrentUser() from pid=6662, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-31 11:29:42.686  1018  1218 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-31 11:29:42.686  1018  1218 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6662, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-31 11:29:42.686  1018  1218 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 11:29:42.686  1018  1218 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-31 11:29:42.686  1018  1218 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-31 11:29:42.686  1018  1218 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-31 11:29:42.686  1018  1218 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-31 11:29:42.686  1018  1218 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 11:29:42.686  1018  1218 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
,08-31 11:29:42.686  1018  1218 D SettingsProvider: name = bluetooth_on,
,08-31 11:29:42.696  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 11:29:42.706  1018  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
08-31 11:29:42.696  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 11:29:42.706  2788  2845 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-31 11:29:42.706  2788  2845 D BluetoothAdapterProperties: Setting state to 11
08-31 11:29:42.716  1018  1136 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:42.706  2788  2845 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-31 11:29:42.716  1018  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-31 11:29:42.706  2788  2845 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 11:29:42.706  2788  2845 D BluetoothAdapterService: updateAdapterState state is 11
,08-31 11:29:42.706  2788  2845 D BluetoothAdapterService: Autoconnection is available 
08-31 11:29:42.706  2788  2845 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-31 11:29:42.706  2788  2845 D BtConfig.SecureMode: isSecureModeOn:false
08-31 11:29:42.706  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-31 11:29:42.706  2788  2845 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-31 11:29:42.706  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 11:29:42.706  2788  2845 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-31 11:29:42.706  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 11:29:42.706  2788  2845 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-31 11:29:42.706  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 11:29:42.706  2788  2845 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-31 11:29:42.706  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 11:29:42.706  2788  2845 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-31 11:29:42.706  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 11:29:42.706  2788  2845 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-31 11:29:42.706  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:42.706  2788  2845 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-31 11:29:42.706  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 11:29:42.706  2788  2845 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-31 11:29:42.706  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:29:42.706  2788  2845 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:29:42.706  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:42.706  2788  2845 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:42.706  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 11:29:42.706  2788  2845 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
,08-31 11:29:42.706  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 11:29:42.706  2788  2845 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-31 11:29:42.706  2788  2845 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
,08-31 11:29:42.706  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-31 11:29:42.706  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 11:29:42.706  2788  2845 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-31 11:29:42.716  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:42.716  1018  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.716  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:42.726  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-31 11:29:42.726  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 11:29:42.726  2788  2845 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-31 11:29:42.726  2788  2788 D HeadsetService: Received start request. Starting profile...
08-31 11:29:42.726  2788  2788 D HeadsetService: start()
08-31 11:29:42.726  2788  2788 D HeadsetStateMachine: make
,08-31 11:29:42.726  1018  1320 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:29:42.726  1018  1320 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 11:29:42.726  2788  2788 E HeadsetStateMachine: # of Max HF connection is 2
08-31 11:29:42.726  1018  1320 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:42.726  1018  1320 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.726  1018  1320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:42.736  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-31 11:29:42.736  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 11:29:42.736  2788  2845 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-31 11:29:42.736  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:42.736  1018  1018 I InputMethodManagerService: [BT Setting State] State =11
,08-31 11:29:42.746  1973  1973 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-31 11:29:42.746  1190  1190 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:42.746  1190  1190 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 11:29:42.746  1190  1190 D BluetoothTile:  getBluetoothState : 11
,08-31 11:29:42.746  4482  4482 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:42.756  1018  1720 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 11:29:42.756  1018  1496 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 11:29:42.756  1190  1190 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 11:29:42.756  1190  1716 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 11:29:42.756  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:42.756  1190  1716 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-31 11:29:42.766  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:42.766  1018  1494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:29:42.766  1018  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 11:29:42.766  1018  1494 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:42.766  1018  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:42.766  1018  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:42.766  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-31 11:29:42.766  1018  3255 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-31 11:29:42.766  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 11:29:42.766  1018  3255 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
08-31 11:29:42.766  2788  2845 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-31 11:29:42.766  1018  3255 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:42.766  1018  3255 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.766  1018  3255 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-31 11:29:42.776  1018  1218 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:42.776  1018  1218 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-31 11:29:42.776  1018  1218 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:42.776  1018  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.776  1018  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:42.776  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-31 11:29:42.776  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 11:29:42.776  2788  2845 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-31 11:29:42.776  1018  1322 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-31 11:29:42.776  1018  1322 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-31 11:29:42.776  1018  1322 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:42.776  1018  1322 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.776  1018  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-31 11:29:42.776  1018  1320 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:42.776  1018  1320 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 11:29:42.776  2788  2788 I bluedroid: get_profile_interface handsfree
,08-31 11:29:42.786  1018  1320 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:42.786  1018  1320 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.786  1018  1320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:42.786  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,08-31 11:29:42.786  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-31 11:29:42.786  2788  2845 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-31 11:29:42.796  1681  1681 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:29:42.796  1018  3256 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:29:42.796  1018  3256 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 11:29:42.796  1018  3256 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:42.806  1018  3256 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.806  1018  3256 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:42.806  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService,
08-31 11:29:42.806  1018  1730 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:42.806  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-31 11:29:42.806  1018  1730 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-31 11:29:42.806  2788  2845 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-31 11:29:42.806  1018  1730 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:42.806  1018  1730 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.806  1018  1730 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:42.816  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 11:29:42.816  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 11:29:42.816  2788  2845 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:29:42.816  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-31 11:29:42.816  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:42.816  2788  2845 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:42.816  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
,08-31 11:29:42.816  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 11:29:42.816  2788  2845 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-31 11:29:42.816  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-31 11:29:42.816  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 11:29:42.816  2788  2845 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-31 11:29:42.816  2788  2845 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-31 11:29:42.816  2788  2788 E DualScoManager: Dual Sco Manager already instantiated
,08-31 11:29:42.816  2788  2788 I DualScoManager: Set HeadsetServiceHelper
08-31 11:29:42.816  2788  2788 D BluetoothAtMessage: createCMTIContentObservers
,08-31 11:29:42.826  4482  4482 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 11:29:42.826  1018  1494 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-31 11:29:42.826  1018  1494 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:42.826  1018  1494 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:42.826  1018  1494 D SettingsProvider: selectionArgs: false
,08-31 11:29:42.826  1018  1494 D SettingsProvider: selectionArgs: 1002
08-31 11:29:42.826  1018  1494 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 11:29:42.826  1018  1494 D SettingsProvider: ret = -1
,08-31 11:29:42.826  2788  7451 D HeadsetStateMachine: Enter Disconnected: -2
,08-31 11:29:42.826  2788  2788 D HeadsetService: mStartError = false
,08-31 11:29:42.826  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
,08-31 11:29:42.836  2788  2788 D A2dpService: Received start request. Starting profile...
08-31 11:29:42.836  2788  2788 D A2dpService: start()
08-31 11:29:42.836  2788  2788 I bluedroid: get_profile_interface avrcp
,08-31 11:29:42.836  2788  7451 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-31 11:29:42.836  2788  7451 D HeadsetStateMachine: map size, before remove : 0
08-31 11:29:42.836  2788  7451 D HeadsetStateMachine: map size, after remove: 0
,08-31 11:29:42.836  2788  2788 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-31 11:29:42.836  2788  2788 D Avrcp   : Initialize Media Controller
08-31 11:29:42.836  2788  2788 D Avrcp   : Get the Context Package Name: com.android.bluetooth
08-31 11:29:42.836  1190  1190 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:42.836  1190  1190 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-31 11:29:42.836  2788  2788 E Avrcp   : getActiveSessions
08-31 11:29:42.836  1018  1720 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-31 11:29:42.836  2788  2788 D Avrcp   : pick active media Controller
08-31 11:29:42.836  2788  2788 D Avrcp   : Get the active Media Controller 
08-31 11:29:42.836  1018  1720 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:42.836  1018  1720 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:42.836  1018  1720 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:42.836  1018  1720 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:42.856  7453  7453 E Zygote  : MountEmulatedStorage(),
08-31 11:29:42.856  1018  1720 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7453 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-31 11:29:42.856  7453  7453 E Zygote  : v2
08-31 11:29:42.856  7453  7453 I libpersona: KNOX_SDCARD checking this for 10055
,08-31 11:29:42.856  7453  7453 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-31 11:29:42.856  7453  7453 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:42.856  7453  7453 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:42.866  7453  7453 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 11:29:42.866  2788  2788 I Avrcp   :  Updating now playing list upon AVRCP Start
08-31 11:29:42.866  2788  2788 D A2dpStateMachine: make
08-31 11:29:42.866  2788  7452 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-31 11:29:42.866  2788  2788 I bluedroid: get_profile_interface a2dp
08-31 11:29:42.866  2788  7460 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 11:29:42.866  2788  2788 E bt-btif : warning : media task started media_task_refcnt 1 
,08-31 11:29:42.866  2788  2788 D A2dpService: mStartError = false
08-31 11:29:42.866  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
,08-31 11:29:42.866  2788  7459 D A2dpStateMachine: Enter Disconnected: -2
08-31 11:29:42.866  2788  2788 D HidService: Received start request. Starting profile...
08-31 11:29:42.866  2788  2788 D HidService: start()
08-31 11:29:42.866  2788  2788 I bluedroid: get_profile_interface hidhost
08-31 11:29:42.866  2788  2788 D HidService: setHidService(): set to: null
08-31 11:29:42.866  2788  2788 D HidService: mStartError = false
08-31 11:29:42.866  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
,08-31 11:29:42.866  2788  2788 D HeadsetStateMachine: Try to query the phonestate on bind
08-31 11:29:42.866  1440  1468 I Telecom : BluetoothPhoneService: queryPhoneState
,08-31 11:29:42.876  1440  1440 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-31 11:29:42.876  1440  1440 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-31 11:29:42.876  1440  1468 I Telecom : BluetoothPhoneService: Result of Message : true
,08-31 11:29:42.876  2788  2788 D HealthService: Received start request. Starting profile...
08-31 11:29:42.876  2788  2788 D HealthService: start()
,08-31 11:29:42.876  2788  2788 I bluedroid: get_profile_interface health,
08-31 11:29:42.876  2788  2788 D HealthService: mStartError = false
08-31 11:29:42.876  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
,08-31 11:29:42.876  2788  2788 D HeadsetStateMachine: Proxy object connected
08-31 11:29:42.876  2788  2788 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-31 11:29:42.876  2788  7451 D HeadsetStateMachine: Disconnected process message: 11
,08-31 11:29:42.876  2788  2788 D PanService: Received start request. Starting profile...
08-31 11:29:42.876  2788  2788 D PanService: start()
08-31 11:29:42.876  2788  2788 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 11:29:42.876  2788  2788 I bluedroid: get_profile_interface pan
08-31 11:29:42.876  2788  2788 D PanService: mStartError = false
08-31 11:29:42.876  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
,08-31 11:29:42.876  2788  2788 D BluetoothMapService: Received start request. Starting profile...
08-31 11:29:42.876  2788  2788 D BluetoothMapService: start()
,08-31 11:29:42.876  2788  2788 D BluetoothMapService: mStartError = false
08-31 11:29:42.876  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
08-31 11:29:42.876  2788  2788 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-31 11:29:42.876  2788  2788 D HeadsetPhoneState: Signal level : previous=0 curr=4
08-31 11:29:42.876  2788  7451 D HeadsetStateMachine: Disconnected process message: 18
,08-31 11:29:42.886  2788  2788 D SapService: Received start request. Starting profile...
08-31 11:29:42.886  2788  2788 D SapService: start()
08-31 11:29:42.886  2788  2788 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-31 11:29:42.886  2788  2788 I bluedroid: get_profile_interface sap
08-31 11:29:42.886  2788  2788 D SapService: mStartError = false
08-31 11:29:42.886  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
08-31 11:29:42.886  2788  2788 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 11:29:42.886  2788  2788 E BluetoothAdapterService(777348176): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-31 11:29:42.886  2788  2788 E BluetoothAdapterService(777348176): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-31 11:29:42.886  2788  2788 E BluetoothAdapterService(777348176): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-31 11:29:42.886  2788  2788 E BluetoothAdapterService(777348176): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-31 11:29:42.886  2788  2788 E BluetoothAdapterService(777348176): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
08-31 11:29:42.886  2788  7451 D HeadsetStateMachine: Disconnected process message: 10
08-31 11:29:42.886  2788  7451 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 11:29:42.886  2788  7451 D HeadsetStateMachine: Disconnected process message: 11
,08-31 11:29:42.886  2788  7452 D BluetoothMediaBrowser: no now playing list
08-31 11:29:42.886  2788  7452 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-31 11:29:42.906  7453  7453 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:42.906  7453  7453 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:42.906  2788  2788 E BluetoothAdapterService(777348176): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-31 11:29:42.906  2788  2788 E BluetoothAdapterService(777348176): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-31 11:29:42.906  2788  2845 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-31 11:29:42.906  2788  2845 I bluedroid: enable
,08-31 11:29:42.916  2788  2848 E bt-btif : Calling BTA_HhEnable
08-31 11:29:42.916  2788  2848 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-31 11:29:42.916  2788  2848 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-31 11:29:42.916  2788  2848 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
08-31 11:29:42.916  2788  2848 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-31 11:29:42.916  2788  2848 E BluetoothServiceJni: populateRssiValuesNative
08-31 11:29:42.916  2788  2848 I bluedroid: getModelRssiValues
08-31 11:29:42.916  2788  2848 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-31 11:29:42.916  2788  2848 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-31 11:29:42.916  2788  2848 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-31 11:29:42.926  1018  1018 D SettingsProvider: name = bluetooth_name
,08-31 11:29:42.926  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:42.926  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:42.926  2788  2848 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-31 11:29:42.926  2788  2848 D BluetoothAdapterProperties: Scan Mode:20
08-31 11:29:42.926  2788  2848 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 11:29:42.926  2788  2848 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-31 11:29:42.926  2788  2848 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-31 11:29:42.926  2788  2848 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-31 11:29:42.936  2788  2848 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-31 11:29:42.936  2788  2848 E bt-btif : JVenable fails
,08-31 11:29:42.936  2788  2848 D bte_conf: Device ID record 1 : primary
,08-31 11:29:42.936  2788  2848 D bte_conf:   vendorId            = 0075
08-31 11:29:42.936  2788  2848 D bte_conf:   vendorIdSource      = 0001
,08-31 11:29:42.936  2788  2848 D bte_conf:   product             = 0100
08-31 11:29:42.936  2788  2848 D bte_conf:   version             = 0200
08-31 11:29:42.936  2788  2848 D bte_conf:   clientExecutableURL = 
,08-31 11:29:42.936  2788  2848 D bte_conf:   serviceDescription  = 
08-31 11:29:42.936  2788  2848 D bte_conf:   documentationURL    = 
,08-31 11:29:42.936  2788  2848 D bte_conf: bte_load_did_conf no section named DID2.
,08-31 11:29:42.936  2788  2845 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-31 11:29:42.936  2788  2845 D BluetoothAdapterProperties: ScanMode =  20
08-31 11:29:42.936  2788  2845 D BluetoothAdapterProperties: State =  11
,08-31 11:29:42.936  7453  7453 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-31 11:29:42.936  1018  1489 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-31 11:29:42.936  2788  2845 D BluetoothAdapterProperties: Setting state to 12
08-31 11:29:42.936  2788  2845 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-31 11:29:42.936  2788  2848 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-31 11:29:42.936  2788  2848 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 11:29:42.946  2788  2848 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 11:29:42.946  2788  2848 D BluetoothAdapterProperties: Scan Mode:21
08-31 11:29:42.946  2788  2848 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 11:29:42.946  1018  1730 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-31 11:29:42.946  1018  1730 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:42.946  1018  1730 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:42.946  1018  1730 D SettingsProvider: selectionArgs: false
08-31 11:29:42.946  1018  1730 D SettingsProvider: selectionArgs: 1002
,08-31 11:29:42.946  1018  1730 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:42.946  1018  1730 D SettingsProvider: ret = -1
,08-31 11:29:42.946  2788  2845 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 11:29:42.946  2788  2845 D BluetoothAdapterService: updateAdapterState state is 12
08-31 11:29:42.946  1018  1136 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:29:42.946  1018  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 11:29:42.946  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:42.946  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:42.946  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:42.946  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:42.946  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:42.946  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:42.946  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:42.946  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:42.956  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:42.956  6662  6662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:42.956  1018  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.956  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:42.956  6662  7396 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 11:29:42.956  2788  2845 D BluetoothAdapterService: Autoconnection is available 
,08-31 11:29:42.956  2788  2845 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-31 11:29:42.956  2788  2845 D BluetoothAdapterService: starting service from this receiver
,08-31 11:29:42.956  6662  7396 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:29:42.956  2788  2788 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-31 11:29:42.966  2788  2788 I BluetoothPbapService: Handler(): got msg=1
08-31 11:29:42.966  2788  2849 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 11:29:42.966  1018  1136 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:42.966  1018  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-31 11:29:42.966  1018  1320 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 11:29:42.966  2788  2849 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-31 11:29:42.966  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:42.966  1018  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.966  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:42.966  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:42.966  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:42.966  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:42.966  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:42.966  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:42.966  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:42.966  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:42.966  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:42.966  2788  2845 I BluetoothAdapterState: Entering On State from state = 11
,08-31 11:29:42.966  1018  1047 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-31 11:29:42.966  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 11:29:42.966  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:42.966  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.966  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:42.976  1448  1478 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 11:29:42.976  1448  1478 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:29:42.976  6662  6662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:42.976  4482  4491 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:29:42.976  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-31 11:29:42.976  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:29:42.976  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:42.976  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.976  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:42.976  4482  4491 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:29:42.976  7453  7453 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-31 11:29:42.976  1440  1454 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:29:42.976  7453  7453 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-31 11:29:42.976  7453  7453 D UserAnalysis: Create SecureDbHelper
,08-31 11:29:42.976  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-31 11:29:42.976  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:29:42.986  2788  7474 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-31 11:29:42.986  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:42.986  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.986  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:42.986  1440  1454 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:29:42.986  4482  4490 D BluetoothPan: Binding service...
,08-31 11:29:42.986  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-31 11:29:42.986  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 11:29:42.986  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:42.986  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:42.986  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:42.986  2788  7474 D BluetoothSocket: bindListen(): myUserId = 0
08-31 11:29:42.986  2788  7474 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:29:42.986  1018  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-31 11:29:42.986  7453  7453 D IntelligenceServiceApplication: onCreate()
,08-31 11:29:42.986  2788  7474 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-31 11:29:42.986  2788  7474 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 11:29:42.986  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 11:29:42.986  2788  7474 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 11:29:42.986  2788  7474 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@be292cc
08-31 11:29:42.986  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-31 11:29:42.986  1018  1047 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:29:42.986  2788  7474 D BluetoothSocket: channel: 19
08-31 11:29:42.986  2788  7474 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-31 11:29:42.986  4482  4491 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 11:29:42.996  4482  4482 D HeadsetProfile: Bluetooth service connected
08-31 11:29:42.996  1018  3255 I ActivityManager: Killing 6988:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-31 11:29:42.996  2788  2788 D BluetoothA2dp: Proxy object connected
,08-31 11:29:42.996  2788  2788 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-31 11:29:42.996  7453  7453 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-31 11:29:43.006  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-31 11:29:43.006  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 11:29:43.006  4482  4482 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 11:29:43.006  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:43.006  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:43.006  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:43.006  4482  4482 D PanProfile: Bluetooth service connected
,08-31 11:29:43.006  1458  2039 D BluetoothAdapter: onBluetoothStateChange: up=true,
08-31 11:29:43.006  1458  2039 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 11:29:43.006  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-31 11:29:43.006  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 11:29:43.006  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-31 11:29:43.006  1018  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:29:43.006  1018  1018 D BluetoothA2dp: Proxy object connected
,08-31 11:29:43.006  1458  1479 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:29:43.016  1018  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 11:29:43.016  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:29:43.016  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:43.016  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:43.016  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:43.016  1458  1479 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:29:43.016  1018  1322 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-31 11:29:43.016  1440  1454 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-31 11:29:43.016  7453  7453 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-31 11:29:43.026  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 11:29:43.026  4482  4482 D BluetoothMap: Proxy object connected
08-31 11:29:43.026  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-31 11:29:43.026  4482  4482 D MapProfile: Bluetooth service connected
08-31 11:29:43.026  4482  4482 D BluetoothMap: getConnectedDevices()
,08-31 11:29:43.026  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:43.026  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
,08-31 11:29:43.026  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-31 11:29:43.026  1440  1454 E BluetoothHeadset: BluetoothHeadset service is binded
08-31 11:29:43.026  4482  7475 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 11:29:43.026  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-31 11:29:43.026  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 11:29:43.026  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:43.026  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:43.026  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:43.026  1739  1756 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:29:43.026  1739  1756 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:29:43.026  1681  1769 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:29:43.026  1681  1769 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 11:29:43.026  1018  1047 D BluetoothPan: Binding service...
,08-31 11:29:43.026  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-31 11:29:43.026  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-31 11:29:43.026  1018  1018 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 11:29:43.026  4482  7475 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 11:29:43.026  4482  4482 D BluetoothPbap: Proxy object connected
08-31 11:29:43.026  4482  4482 D PbapServerProfile: Bluetooth service connected
,08-31 11:29:43.026  4482  7475 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:29:43.036  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-31 11:29:43.036  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 11:29:43.036  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:43.036  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:43.036  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:43.036  4482  7475 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:29:43.036  4482  7475 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 11:29:43.036  4482  4482 D BluetoothA2dp: Proxy object connected
08-31 11:29:43.036  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:29:43.036  1018  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:29:43.036  4482  4482 D A2dpProfile: Bluetooth service connected
,08-31 11:29:43.036  1440  1454 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:29:43.036  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 11:29:43.036  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:29:43.036  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:43.036  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:43.036  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-31 11:29:43.036  1440  1454 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:29:43.036  4482  4490 D Bluetoothsap: onBluetoothStateChange: up=true
,08-31 11:29:43.036  4482  4490 D Bluetoothsap: Binding service...
08-31 11:29:43.036  7453  7453 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-31 11:29:43.046  4482  4490 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-31 11:29:43.046  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-31 11:29:43.046  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 11:29:43.046  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:43.046  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:43.046  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:43.046  4482  4490 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-31 11:29:43.046  4482  4482 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-31 11:29:43.046  1190  2205 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:29:43.046  1190  2205 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 11:29:43.046  4482  4482 D SapProfile: Bluetooth service connected
08-31 11:29:43.046  4482  4482 D Bluetoothsap: getConnectedDevices()
,08-31 11:29:43.056  1018  1047 E BluetoothManagerService: Unable to call onBluetoothStateChange() on callback #22
08-31 11:29:43.056  1018  1047 E BluetoothManagerService: android.os.DeadObjectException
08-31 11:29:43.056  1018  1047 E BluetoothManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 11:29:43.056  1018  1047 E BluetoothManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
08-31 11:29:43.056  1018  1047 E BluetoothManagerService: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub$Proxy.onBluetoothStateChange(IBluetoothStateChangeCallback.java:84)
08-31 11:29:43.056  1018  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.sendBluetoothStateCallback(BluetoothManagerService.java:1053)
08-31 11:29:43.056  1018  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:2007)
08-31 11:29:43.056  1018  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.access$3900(BluetoothManagerService.java:105)
08-31 11:29:43.056  1018  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1576)
08-31 11:29:43.056  1018  1047 E BluetoothManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:43.056  1018  1047 E BluetoothManagerService: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:43.056  1018  1047 E BluetoothManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 11:29:43.056  1018  1047 E BluetoothManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-31 11:29:43.056  2788  2803 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:29:43.056  2788  2803 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:29:43.056  4482  7475 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 11:29:43.056  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-31 11:29:43.056  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 11:29:43.056  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:43.056  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:43.056  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:43.056  4482  4482 D BluetoothInputDevice: Proxy object connected
08-31 11:29:43.056  1440  7477 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:29:43.056  1440  7477 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:29:43.066  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-31 11:29:43.066  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-31 11:29:43.066  4482  4482 D HidProfile: Bluetooth service connected
,08-31 11:29:43.066  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:43.066  1018  1018 I InputMethodManagerService: [BT Setting State] State =12
08-31 11:29:43.066  1018  1018 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-31 11:29:43.066  1190  1190 D BluetoothTile:  onBluetoothStateChange:
,08-31 11:29:43.066  1190  1190 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 11:29:43.076  1190  1190 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:43.076  1190  1190 D BluetoothTile:  getBluetoothState : 12
08-31 11:29:43.076  1440  1440 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2fc5a047, true
,08-31 11:29:43.076  1973  1973 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
08-31 11:29:43.076  1440  1440 D BluetoothHeadset: registerMessageListener
,08-31 11:29:43.076  1190  1190 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ),
08-31 11:29:43.076  1190  1716 D BluetoothTile:  handleUpdatestate:false name:null
08-31 11:29:43.076  1190  1716 D BluetoothTile:  handleUpdatestate:false name:null
08-31 11:29:43.076  1190  1716 D BluetoothTile:  handleUpdatestate:false name:null,
,08-31 11:29:43.076  1018  1490 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-31 11:29:43.076  1018  1489 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-31 11:29:43.086  2788  2849 D HeadsetService: registerMessageListener
,08-31 11:29:43.086  2788  2849 D HeadsetService: registerMessageListener
,08-31 11:29:43.086  2788  7451 D HeadsetStateMachine: Disconnected process message: 70
08-31 11:29:43.086  2788  7451 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2dfad915
08-31 11:29:43.086  1440  1440 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-31 11:29:43.086  4482  4482 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:43.086  1440  1440 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-31 11:29:43.086  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:43.096  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:43.096  1440  1440 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-31 11:29:43.096  1440  1440 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-31 11:29:43.096  1440  1440 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-31 11:29:43.096  2788  7478 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-31 11:29:43.096  4482  4482 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-31 11:29:43.096  4482  4482 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-31 11:29:43.096  4482  4482 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-31 11:29:43.096  4482  4482 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-31 11:29:43.096  2788  7451 D HeadsetStateMachine: Disconnected process message: 9
08-31 11:29:43.096  2788  7451 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-31 11:29:43.096   282   674 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-31 11:29:43.106   282   674 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-31 11:29:43.106   282   674 V voice   : voice_set_parameters: exit with code(-2)
08-31 11:29:43.106   282   674 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-31 11:29:43.106   282   674 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-31 11:29:43.106   282   674 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-31 11:29:43.106   282   674 V audio_hw_primary: adev_set_parameters: exit
,08-31 11:29:43.106  2788  7478 D BluetoothSocket: bindListen(): myUserId = 0
08-31 11:29:43.106  2788  7478 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 11:29:43.106  2788  7451 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-31 11:29:43.106  2788  7478 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-31 11:29:43.106  2788  7478 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 11:29:43.106  2788  7478 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 11:29:43.106  2788  7478 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d31042a
08-31 11:29:43.106  2788  7478 D BluetoothSocket: channel: 5
,08-31 11:29:43.106  4482  4482 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:29:43.106  1018  1218 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-31 11:29:43.106  1018  1218 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 11:29:43.106  1018  1218 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:43.106  1018  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:43.106  1018  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 11:29:43.116  1681  1681 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:29:43.116  4482  4482 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:29:43.126  4482  4482 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 11:29:43.126  1190  1190 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:43.126  1190  1190 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-31 11:29:43.136  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
,08-31 11:29:43.136  2788  2788 D BtConfig.SecureMode: isSecureModeOn:false
,08-31 11:29:43.136  1018  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:29:43.136  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-31 11:29:43.136  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:43.136  1018  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:43.136  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:43.136  1018  1322 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-31 11:29:43.146  1018  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:43.146  1018  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:43.146  1018  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:43.146  1018  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:43.156  7481  7481 E Zygote  : MountEmulatedStorage()
08-31 11:29:43.156  7481  7481 E Zygote  : v2
08-31 11:29:43.156  7481  7481 I libpersona: KNOX_SDCARD checking this for 10105
,08-31 11:29:43.156  7481  7481 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:43.156  1018  1322 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7481 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-31 11:29:43.156  7481  7481 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-31 11:29:43.166  1018  1030 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy,
,08-31 11:29:43.166  7481  7481 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-31 11:29:43.166  7481  7481 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 11:29:43.176  2788  7492 D BluetoothSocket: bindListen(): myUserId = 0
08-31 11:29:43.176  2788  7492 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:29:43.176  2788  7492 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,08-31 11:29:43.176  2788  7492 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 11:29:43.176  2788  7492 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 11:29:43.176  2788  7492 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1cb338f6
08-31 11:29:43.176  2788  7492 D BluetoothSocket: channel: 12
08-31 11:29:43.176  2788  7492 I BtOppRfcommListener: Accept thread started.
,08-31 11:29:43.186  7481  7481 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:43.186  7481  7481 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:43.296   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-31 11:29:43.296   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 11:29:43.296  7481  7502 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-31 11:29:43.306   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-31 11:29:43.306   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 11:29:43.306  7481  7502 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-31 11:29:43.436  7481  7481 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:43.436  7481  7481 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:43.436  7481  7481 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:43.436  7481  7481 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.q.e.b(PG:170)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:43.436  7481  7481 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.q.k.d(PG:583)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.q.e.b(PG:170)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:43.436  7481  7481 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:43.436  1018  1320 I ActivityManager: Killing 7090:com.sec.pcw.device/1000 (adj 15): empty #21
08-31 11:29:43.436  7481  7481 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 11:29:43.436  7481  7481 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 11:29:43.436  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-31 11:29:43.496  7481  7502 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-31 11:29:43.526  1018  1218 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 11:29:43.526  1018  1218 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:43.526  1018  1218 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:43.526  1018  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-31 11:29:43.726   287   287 E SMD     : DCD OFF
,08-31 11:29:44.696  1018  2869 D SSRM:n  : SIOP:: AP = 360
,08-31 11:29:45.696  6662  6834 D BluetoothAdapter: disable()
,08-31 11:29:45.696  1018  1494 D SettingsProvider: name = bluetooth_on
,08-31 11:29:45.706  2788  2845 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-31 11:29:45.716  2788  2845 D BluetoothAdapterProperties: Setting state to 13
08-31 11:29:45.716  2788  2845 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13,
08-31 11:29:45.716  2788  2845 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 11:29:45.716  1018  1320 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:45.716  2788  2845 D BluetoothAdapterService: updateAdapterState state is 13,
,08-31 11:29:45.716  1018  1320 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-31 11:29:45.716  1018  1320 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:45.716  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-31 11:29:45.716  1018  1320 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:45.716  1018  1320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:45.716  2788  2788 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-31 11:29:45.716  2788  2788 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@17ee64f7, channel: 19, state: LISTENING
08-31 11:29:45.716  2788  2788 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@17ee64f7, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@be292cc, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@214e6f64mSocket: android.net.LocalSocket@1fae15cd impl:android.net.LocalSocketImpl@3151ee82 fd:FileDescriptor[74]
08-31 11:29:45.716  2788  2788 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1fae15cd impl:android.net.LocalSocketImpl@3151ee82 fd:FileDescriptor[74]
,08-31 11:29:45.716  2788  2845 D BluetoothAdapterService: Autoconnection is available 
08-31 11:29:45.716  2788  2845 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-31 11:29:45.716  2788  2845 D BluetoothAdapterService: terminating service from this receiver
08-31 11:29:45.716  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:45.716  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:45.716  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 11:29:45.716   325   325 I ServiceManager: Waiting for service AtCmdFwd...
08-31 11:29:45.716  2788  2845 D BluetoothAdapterProperties: onBluetoothDisable()
,08-31 11:29:45.716  2788  2845 D BluetoothAdapterProperties: mDiscovering is false
08-31 11:29:45.726  1018  1031 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-31 11:29:45.726  2788  2845 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-31 11:29:45.726  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:45.726  1018  1018 I InputMethodManagerService: [BT Setting State] State =13
,08-31 11:29:45.736  1190  1190 D BluetoothTile:  onBluetoothStateChange:
,08-31 11:29:45.736  1190  1190 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 11:29:45.736  1190  1716 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 11:29:45.736  1190  1716 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 11:29:45.746  1190  1190 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:45.746  1190  1190 D BluetoothTile:  getBluetoothState : 13
,08-31 11:29:45.746  1973  1973 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
08-31 11:29:45.746  1190  1716 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-31 11:29:45.746  1018  1496 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 11:29:45.746  1018  1031 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 11:29:45.746  4482  4482 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:45.746  1190  1190 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 11:29:45.756  6662  6662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:29:45.756  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:45.756  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:45.756  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:45.756  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:45.756  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:45.756  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:45.756  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:45.756  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:45.756  6662  6662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:29:45.756  6662  6662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:45.756  6662  6662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:29:45.756  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:45.756  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:45.756  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:45.756  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:45.756  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 11:29:45.756  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:45.756  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:45.756  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:45.766  6662  6662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 11:29:45.766  6662  6662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:45.766  2788  2848 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-31 11:29:45.766  2788  2848 D BluetoothAdapterProperties: Scan Mode:20
,08-31 11:29:45.776  2788  2845 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-31 11:29:45.776  2788  2845 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-31 11:29:45.776  2788  2845 E bt-btif : cmd socket is not created
,08-31 11:29:45.776  2788  2845 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 11:29:45.776  2788  7492 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 11:29:45.776  2788  2852 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-31 11:29:45.776  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:45.776  2788  2788 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@311a5993, channel: 5, state: LISTENING
,08-31 11:29:45.776  2788  2788 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@311a5993, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d31042a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@a351dd0mSocket: android.net.LocalSocket@269341c9 impl:android.net.LocalSocketImpl@353470ce fd:FileDescriptor[76]
,08-31 11:29:45.776  2788  2788 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@269341c9 impl:android.net.LocalSocketImpl@353470ce fd:FileDescriptor[76]
08-31 11:29:45.776  2788  2788 I BtOppRfcommListener: stopping Accept Thread
08-31 11:29:45.776  2788  2788 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2f06fbef, channel: 12, state: LISTENING
08-31 11:29:45.776  2788  2788 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2f06fbef, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1cb338f6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@309646fcmSocket: android.net.LocalSocket@1c853185 impl:android.net.LocalSocketImpl@baacbda fd:FileDescriptor[80]
08-31 11:29:45.776  2788  2788 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1c853185 impl:android.net.LocalSocketImpl@baacbda fd:FileDescriptor[80]
,08-31 11:29:45.776  2788  7492 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-31 11:29:45.786  2788  2788 V BluetoothOppManager: cleanUp...
,08-31 11:29:45.786  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:45.786  2788  2852 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:29:45.786  2788  2852 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:29:45.786  2788  2852 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 11:29:45.786  2788  2852 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 11:29:45.786  2788  2852 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 11:29:45.786  2788  2852 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-31 11:29:45.786  4482  4482 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:29:45.786  1018  1322 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-31 11:29:45.786  1018  1322 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 11:29:45.796  1018  1322 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:45.796  1018  1322 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:45.796  1018  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 11:29:45.796  4482  4482 D BluetoothPbap: Proxy object disconnected
08-31 11:29:45.796  4482  4482 D PbapServerProfile: Bluetooth service disconnected
,08-31 11:29:45.796  1681  1681 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:29:45.796  4482  4482 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:29:45.806  4482  4482 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 11:29:45.806  1190  1190 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:45.806  1190  1190 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-31 11:29:45.986  2788  2845 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-31 11:29:45.986  2788  2845 D BtConfig.SecureMode: isSecureModeOn:false
,08-31 11:29:45.986  2788  2845 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-31 11:29:45.986  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
,08-31 11:29:45.986  2788  2845 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-31 11:29:45.986  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,08-31 11:29:45.986  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 11:29:45.986  2788  2845 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-31 11:29:45.986  1018  1496 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:29:45.986  1018  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-31 11:29:45.986  1018  1496 W ActivityManager: userId = 0, bbcId = -10000,
,08-31 11:29:45.986  1018  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:45.986  1018  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:45.986  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService,
,08-31 11:29:45.986  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 11:29:45.986  2788  2845 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-31 11:29:45.986  1018  3256 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:45.986  1018  3256 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0,
,08-31 11:29:45.986  1018  3256 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:45.986  1018  3256 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
,08-31 11:29:45.986  1018  3256 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 11:29:45.996  2788  2788 D HeadsetService: Received stop request...Stopping profile...
,08-31 11:29:45.996  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
08-31 11:29:45.996  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-31 11:29:45.996  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 11:29:45.996  2788  2845 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-31 11:29:45.996  1018  1730 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:29:45.996  1018  1730 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 11:29:45.996  1018  1730 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:45.996  1018  1730 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:45.996  1018  1730 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:45.996  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-31 11:29:45.996  1018  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:45.996  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 11:29:45.996  1018  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-31 11:29:45.996  2788  2845 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-31 11:29:46.006  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:46.006  1018  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:46.006  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 11:29:46.006  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-31 11:29:46.006  4482  4482 D HeadsetProfile: Bluetooth service disconnected
08-31 11:29:46.006  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-31 11:29:46.006  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 11:29:46.006  2788  2845 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-31 11:29:46.006  1018  1320 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:46.006  1018  1320 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 11:29:46.006  1018  1320 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:46.006  1018  1320 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:46.006  1018  1320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:46.006  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,08-31 11:29:46.006  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:46.006  2788  2845 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-31 11:29:46.006  1018  3255 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:46.006  1018  3255 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 11:29:46.006  1018  3255 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:46.006  1018  3255 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:46.006  1018  3255 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:46.006  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-31 11:29:46.006  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 11:29:46.006  2788  2845 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-31 11:29:46.006  1018  1496 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:46.006  1018  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 11:29:46.016  1018  1496 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:46.016  1018  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:46.016  1018  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:46.016  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 11:29:46.016  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:29:46.016  2788  2845 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:29:46.016  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:46.016  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:46.016  2788  2845 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-31 11:29:46.016  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-31 11:29:46.016  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 11:29:46.016  2788  2845 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-31 11:29:46.016  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-31 11:29:46.016  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-31 11:29:46.016  2788  2845 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-31 11:29:46.016  2788  2845 D BluetoothAdapterState: Stopping profile services that were post enabled
08-31 11:29:46.016  2788  2788 E BluetoothAdapterService(777348176): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-31 11:29:46.016  2788  2788 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 11:29:46.016  2788  2788 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-31 11:29:46.016  2788  2788 D A2dpService: Received stop request...Stopping profile...
08-31 11:29:46.016  2788  7459 D A2dpStateMachine: Exit Disconnected: -1
,08-31 11:29:46.016  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
,08-31 11:29:46.026  1018  1018 D BluetoothA2dp: Proxy object disconnected
,08-31 11:29:46.026  4482  4482 D BluetoothA2dp: Proxy object disconnected
08-31 11:29:46.026  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-31 11:29:46.026  4482  4482 D A2dpProfile: Bluetooth service disconnected
08-31 11:29:46.026  2788  2788 D HidService: Received stop request...Stopping profile...
08-31 11:29:46.026  2788  2788 D HidService: Stopping Bluetooth HidService
08-31 11:29:46.026  2788  2788 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 11:29:46.026  2788  2788 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-31 11:29:46.026  2788  2788 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 11:29:46.026  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
,08-31 11:29:46.026  4482  4482 D BluetoothInputDevice: Proxy object disconnected
,08-31 11:29:46.026  4482  4482 D HidProfile: Bluetooth service disconnected
,08-31 11:29:46.026  2788  2788 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 11:29:46.026  2788  2788 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-31 11:29:46.026  2788  2788 D HealthService: Received stop request...Stopping profile...
08-31 11:29:46.026  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
,08-31 11:29:46.026  2788  2788 D PanService: Received stop request...Stopping profile...
,08-31 11:29:46.026  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
,08-31 11:29:46.026  2788  2788 D BluetoothMapService: Received stop request...Stopping profile...
,08-31 11:29:46.036  1018  1018 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 11:29:46.036  4482  4482 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-31 11:29:46.036  4482  4482 D PanProfile: Bluetooth service disconnected
,08-31 11:29:46.036  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
,08-31 11:29:46.036  2788  2788 D SapService: Received stop request...Stopping profile...
,08-31 11:29:46.036  2788  2788 D SapService: Stopping Bluetooth SapService
08-31 11:29:46.036  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
,08-31 11:29:46.036  2788  2788 E BluetoothAdapterService(777348176): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-31 11:29:46.036  2788  2788 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 11:29:46.036  2788  2788 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-31 11:29:46.036  2788  2788 D BluetoothA2dp: Proxy object disconnected
08-31 11:29:46.036  2788  2788 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-31 11:29:46.036  2788  7460 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-31 11:29:46.036  2788  2788 I GKI_LINUX: GKI_exit_task 2 done
,08-31 11:29:46.036  2788  2788 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-31 11:29:46.036  2788  2788 E BluetoothAdapterService(777348176): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-31 11:29:46.036  2788  2788 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-31 11:29:46.036  2788  2788 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:46.036  2788  2788 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:46.036  2788  2788 E BluetoothAdapterService(777348176): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
,08-31 11:29:46.046  2788  2788 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-31 11:29:46.046  2788  2788 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:46.046  2788  2788 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:46.046  2788  2788 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 11:29:46.046  2788  2788 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-31 11:29:46.046  2788  2788 E BluetoothAdapterService(777348176): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-31 11:29:46.046  2788  2788 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-31 11:29:46.046  2788  2788 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:46.046  2788  2788 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:46.046  2788  2788 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 11:29:46.046  2788  2788 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-31 11:29:46.046  2788  2788 E BluetoothAdapterService(777348176): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-31 11:29:46.046  2788  2788 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-31 11:29:46.046  2788  2788 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 11:29:46.046  2788  2788 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-31 11:29:46.046  2788  2788 E BluetoothAdapterService(777348176): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-31 11:29:46.046  2788  2788 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,08-31 11:29:46.046  2788  2788 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-31 11:29:46.046  2788  2788 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-31 11:29:46.046  4482  4482 D BluetoothMap: Proxy object disconnected
08-31 11:29:46.046  4482  4482 D MapProfile: Bluetooth service disconnected
,08-31 11:29:46.046  4482  4482 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-31 11:29:46.046  4482  4482 D SapProfile: Bluetooth service disconnected
,08-31 11:29:46.046  2788  2845 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-31 11:29:46.046  2788  2845 D BluetoothAdapterProperties: Setting state to 10
08-31 11:29:46.046  2788  2845 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-31 11:29:46.046  2788  2845 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 11:29:46.046  2788  2845 D BluetoothAdapterService: updateAdapterState state is 10
,08-31 11:29:46.046  2788  2845 D BluetoothAdapterService: Autoconnection is available 
08-31 11:29:46.046  6662  6670 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 11:29:46.046  2788  2845 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-31 11:29:46.046  2788  2845 I BluetoothAdapterState: Entering OffState
08-31 11:29:46.046  6662  6670 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 11:29:46.046  6662  6670 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-31 11:29:46.046  6662  6670 D BluetoothLeAdvertiser: Exit stop advertising
08-31 11:29:46.046  6662  6670 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-31 11:29:46.046  6662  6670 D BluetoothLeScanner: Exiting stopAllScan
08-31 11:29:46.046  2788  2798 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 11:29:46.046  1448  1459 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 11:29:46.046  1448  1459 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:29:46.056  7481  7498 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 11:29:46.056  7481  7498 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:29:46.056  4482  4491 D BluetoothMap: onBluetoothStateChange: up=false
,08-31 11:29:46.056  1458  2676 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 11:29:46.056  1458  2676 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:29:46.056  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 11:29:46.056  4482  4490 D BluetoothPbap: onBluetoothStateChange: up=false
,08-31 11:29:46.056  1739  1748 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 11:29:46.056  1739  1748 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:29:46.056  1681  2211 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 11:29:46.056  1681  2211 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:29:46.056  4482  7475 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 11:29:46.056  4482  4491 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 11:29:46.056  4482  4491 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:29:46.056  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 11:29:46.066  1018  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:29:46.066  4482  4490 D Bluetoothsap: onBluetoothStateChange: up=false
,08-31 11:29:46.066  4482  4490 D Bluetoothsap: Unbinding service...
,08-31 11:29:46.066  1190  1205 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 11:29:46.066  1190  1205 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:29:46.066  2788  2803 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 11:29:46.066  2788  2803 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:29:46.066  4482  7475 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-31 11:29:46.066  1440  7519 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 11:29:46.066  1440  7519 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 11:29:46.066  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:46.066  1018  1018 I InputMethodManagerService: [BT Setting State] State =10
08-31 11:29:46.066  1018  1018 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-31 11:29:46.076  1190  1190 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 11:29:46.076  1190  1190 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:46.076  1190  1190 D BluetoothTile:  getBluetoothState : 10
,08-31 11:29:46.076  1018  1030 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 11:29:46.086  1018  1489 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 11:29:46.086  1973  1973 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0,
08-31 11:29:46.086  1190  1190 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ),
,08-31 11:29:46.086  4482  4482 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:46.086  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:46.086  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:46.086  4482  4482 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:29:46.086  1018  3256 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-31 11:29:46.096  1018  3256 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 11:29:46.096  1018  3256 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:46.096  1018  3256 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:46.096  1018  3256 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 11:29:46.096  1681  1681 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:29:46.106  4482  4482 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:29:46.106  4482  4482 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 11:29:46.106  1190  1190 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:46.106  1190  1190 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-31 11:29:46.726   287   287 E SMD     : DCD OFF
,08-31 11:29:46.726   325   325 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 11:29:47.696  1018  1320 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-31 11:29:47.696  1018  1320 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4278, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-31 11:29:47.696  1018  1320 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-31 11:29:47.696  1018  1320 D BatteryService: stay LED for charging,
08-31 11:29:47.696  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 11:29:47.696  1018  1018 I MotionRecognitionService: Plugged,
08-31 11:29:47.696  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 11:29:47.706  1190  1190 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,08-31 11:29:47.706  1190  1190 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 11:29:47.706  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-31 11:29:47.706  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-31 11:29:47.716  1190  1190 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-31 11:29:47.716  1190  1190 D SViewCoverView: level :100 plugged : 2
,08-31 11:29:47.716  1190  1190 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 11:29:47.716  1190  1190 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 11:29:47.716  1190  1190 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 11:29:47.726   325   325 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 11:29:48.726  6662  6834 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 11:29:48.726  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:48.726   325   325 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 11:29:49.726   287   287 E SMD     : DCD OFF,
,08-31 11:29:49.726   325   325 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 11:29:50.726   325   325 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-31 11:29:51.086  1018  1096 V AlarmManager: waitForAlarm result :4,
,08-31 11:29:51.096   277   963 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 11:29:51.096   277   963 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-31 11:29:51.116  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:51.116  1018  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:51.116  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-31 11:29:51.726  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:29:51.726  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@28f59355 added. We now have 6 listener(s)
,08-31 11:29:51.726  6662  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:51.726  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:29:51.726  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c31d16a added. We now have 7 listener(s),
08-31 11:29:51.726  6662  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:51.726  6662  6834 I System.out: IsBluetoothEnabled
08-31 11:29:51.726  6662  6834 D BluetoothAdapter: disable()
08-31 11:29:51.726  1018  1320 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-31 11:29:51.736  6662  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-31 11:29:51.736  6662  6834 D BluetoothAdapter: enable()
,08-31 11:29:51.736  1018  3256 W ActivityManager: Permission Denial: getCurrentUser() from pid=6662, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-31 11:29:51.736  1018  3256 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-31 11:29:51.736  1018  3256 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6662, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-31 11:29:51.736  1018  3256 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 11:29:51.736  1018  3256 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-31 11:29:51.736  1018  3256 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-31 11:29:51.736  1018  3256 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-31 11:29:51.736  1018  3256 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-31 11:29:51.736  1018  3256 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 11:29:51.736  1018  3256 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 11:29:51.736  1018  3256 D SettingsProvider: name = bluetooth_on,
,08-31 11:29:51.746  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 11:29:51.746  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 11:29:51.756  1018  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-31 11:29:51.756  2788  2845 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-31 11:29:51.756  2788  2845 D BluetoothAdapterProperties: Setting state to 11
,08-31 11:29:51.756  2788  2845 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-31 11:29:51.756  2788  2845 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-31 11:29:51.756  2788  2845 D BluetoothAdapterService: updateAdapterState state is 11
,08-31 11:29:51.756  2788  2845 D BluetoothAdapterService: Autoconnection is available 
,08-31 11:29:51.756  2788  2845 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-31 11:29:51.756  2788  2845 D BtConfig.SecureMode: isSecureModeOn:false
08-31 11:29:51.756  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-31 11:29:51.756  2788  2845 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-31 11:29:51.766  1018  1136 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:51.756  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 11:29:51.766  1018  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-31 11:29:51.756  2788  2845 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-31 11:29:51.756  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 11:29:51.756  2788  2845 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10,
08-31 11:29:51.756  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 11:29:51.756  2788  2845 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-31 11:29:51.756  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 11:29:51.756  2788  2845 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-31 11:29:51.756  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 11:29:51.756  2788  2845 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-31 11:29:51.756  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:51.756  2788  2845 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-31 11:29:51.756  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 11:29:51.756  2788  2845 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-31 11:29:51.756  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:29:51.756  2788  2845 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:29:51.756  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:51.756  2788  2845 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:51.756  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 11:29:51.756  2788  2845 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-31 11:29:51.756  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 11:29:51.756  2788  2845 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-31 11:29:51.756  2788  2845 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-31 11:29:51.756  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-31 11:29:51.756  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 11:29:51.756  2788  2845 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-31 11:29:51.766  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:51.766  1018  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:51.766  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 11:29:51.766  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-31 11:29:51.766  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 11:29:51.766  2788  2845 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-31 11:29:51.766  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:51.766  1018  1018 I InputMethodManagerService: [BT Setting State] State =11
,08-31 11:29:51.766  2788  2788 D HeadsetService: Received start request. Starting profile...
,08-31 11:29:51.766  2788  2788 D HeadsetService: start()
08-31 11:29:51.766  2788  2788 D HeadsetStateMachine: make
,08-31 11:29:51.776  2788  2788 E HeadsetStateMachine: # of Max HF connection is 2
,08-31 11:29:51.786  1973  1973 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 11:29:51.786  4482  4482 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:51.786  1190  1190 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 11:29:51.796  1190  1190 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:51.796  1190  1190 D BluetoothTile:  getBluetoothState : 11
08-31 11:29:51.796  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:51.796  1018  1720 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:51.796  1018  1720 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 11:29:51.796  1018  1720 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:51.796  1018  1720 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:51.796  1018  1720 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 11:29:51.796  1018  1496 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-31 11:29:51.796  1018  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
08-31 11:29:51.796  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,08-31 11:29:51.796  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 11:29:51.796  1018  3255 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-31 11:29:51.796  2788  2845 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-31 11:29:51.796  1018  1496 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:51.806  1018  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:51.806  1018  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-31 11:29:51.806  1190  1716 D BluetoothTile:  handleUpdatestate:false name:null
08-31 11:29:51.806  1190  1716 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-31 11:29:51.806  1018  1730 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:51.806  1018  1730 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-31 11:29:51.806  1018  1489 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 11:29:51.806  1018  1730 W ActivityManager: userId = 0, bbcId = -10000,
08-31 11:29:51.806  1018  1730 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:51.806  1018  1730 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:51.806  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,08-31 11:29:51.806  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-31 11:29:51.806  2788  2845 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-31 11:29:51.816  1190  1190 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 11:29:51.816  1681  1681 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 11:29:51.816  1018  1320 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-31 11:29:51.816  1018  1320 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-31 11:29:51.816  1018  1320 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:51.816  1018  1320 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:51.816  1018  1320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-31 11:29:51.816  1018  1494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:29:51.816  1018  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-31 11:29:51.826  2788  2788 I bluedroid: get_profile_interface handsfree
08-31 11:29:51.826  1018  1494 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:51.826  1018  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:51.826  1018  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:51.826  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,08-31 11:29:51.826  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 11:29:51.826  2788  2845 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-31 11:29:51.826  1018  3255 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:51.826  1018  3255 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:51.826  1018  3255 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:51.826  1018  3255 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0,
08-31 11:29:51.826  1018  3255 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 11:29:51.826  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,08-31 11:29:51.826  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:51.826  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 11:29:51.826  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-31 11:29:51.826  2788  2845 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-31 11:29:51.836  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:51.836  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:51.836  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:51.836  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-31 11:29:51.836  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 11:29:51.836  2788  2845 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-31 11:29:51.836  4482  4482 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 11:29:51.836  1018  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:51.836  1018  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-31 11:29:51.836  2788  2788 E DualScoManager: Dual Sco Manager already instantiated
08-31 11:29:51.836  2788  2788 I DualScoManager: Set HeadsetServiceHelper
08-31 11:29:51.836  2788  2788 D BluetoothAtMessage: createCMTIContentObservers
08-31 11:29:51.836  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:51.836  1018  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:51.836  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:51.846  1018  3256 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-31 11:29:51.846  1018  3256 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 11:29:51.846  1018  3256 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:51.846  1018  3256 D SettingsProvider: selectionArgs: false
08-31 11:29:51.846  1018  3256 D SettingsProvider: selectionArgs: 1002
08-31 11:29:51.846  1018  3256 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 11:29:51.846  1018  3256 D SettingsProvider: ret = -1
,08-31 11:29:51.846  2788  7529 D HeadsetStateMachine: Enter Disconnected: -2
,08-31 11:29:51.846  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:29:51.846  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:29:51.846  2788  2845 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 11:29:51.846  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:51.846  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:51.846  2788  2845 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-31 11:29:51.846  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-31 11:29:51.846  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 11:29:51.846  2788  2845 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-31 11:29:51.846  2788  2845 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-31 11:29:51.846  2788  2845 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 11:29:51.846  2788  2845 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-31 11:29:51.846  2788  2845 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-31 11:29:51.846  2788  2788 D HeadsetService: mStartError = false
08-31 11:29:51.846  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
,08-31 11:29:51.846  2788  2788 D A2dpService: Received start request. Starting profile...
,08-31 11:29:51.846  2788  2788 D A2dpService: start()
08-31 11:29:51.846  2788  2788 I bluedroid: get_profile_interface avrcp
,08-31 11:29:51.856  1190  1190 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:51.856  1190  1190 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-31 11:29:51.856  2788  7529 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-31 11:29:51.856  2788  7529 D HeadsetStateMachine: map size, before remove : 0
,08-31 11:29:51.856  2788  7529 D HeadsetStateMachine: map size, after remove: 0
,08-31 11:29:51.856  2788  2788 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 11:29:51.856  2788  2788 D Avrcp   : Initialize Media Controller
08-31 11:29:51.856  2788  2788 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-31 11:29:51.856  2788  2788 E Avrcp   : getActiveSessions
,08-31 11:29:51.856  2788  2788 D Avrcp   : pick active media Controller
08-31 11:29:51.866  2788  2788 D Avrcp   : Get the active Media Controller 
,08-31 11:29:51.866  2788  2788 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-31 11:29:51.866  2788  7530 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
08-31 11:29:51.866  2788  2788 D A2dpStateMachine: make
,08-31 11:29:51.866  2788  2788 I bluedroid: get_profile_interface a2dp
,08-31 11:29:51.866  2788  7532 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 11:29:51.866  2788  2788 E bt-btif : warning : media task started media_task_refcnt 1 
,08-31 11:29:51.876  2788  2788 D A2dpService: mStartError = false
08-31 11:29:51.876  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
08-31 11:29:51.876  2788  2788 D HeadsetStateMachine: Try to query the phonestate on bind
,08-31 11:29:51.876  1440  1454 I Telecom : BluetoothPhoneService: queryPhoneState
,08-31 11:29:51.876  2788  7531 D A2dpStateMachine: Enter Disconnected: -2
,08-31 11:29:51.876  1440  1440 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-31 11:29:51.876  1440  1440 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-31 11:29:51.876  1440  1454 I Telecom : BluetoothPhoneService: Result of Message : true
,08-31 11:29:51.876  2788  2788 D HidService: Received start request. Starting profile...
08-31 11:29:51.876  2788  2788 D HidService: start()
08-31 11:29:51.876  2788  2788 I bluedroid: get_profile_interface hidhost
08-31 11:29:51.876  2788  2788 D HidService: setHidService(): set to: null
08-31 11:29:51.876  2788  2788 D HidService: mStartError = false
08-31 11:29:51.876  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
08-31 11:29:51.876  2788  2788 D HeadsetStateMachine: Proxy object connected
08-31 11:29:51.876  2788  2788 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-31 11:29:51.876  2788  7529 D HeadsetStateMachine: Disconnected process message: 11
,08-31 11:29:51.876  2788  2788 D HealthService: Received start request. Starting profile...
08-31 11:29:51.876  2788  2788 D HealthService: start()
,08-31 11:29:51.876  2788  7530 D BluetoothMediaBrowser: no now playing list
08-31 11:29:51.876  2788  7530 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-31 11:29:51.876  2788  2788 I bluedroid: get_profile_interface health
08-31 11:29:51.876  2788  2788 D HealthService: mStartError = false
08-31 11:29:51.876  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
,08-31 11:29:51.876  2788  2788 D PanService: Received start request. Starting profile...
08-31 11:29:51.876  2788  2788 D PanService: start()
08-31 11:29:51.876  2788  2788 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 11:29:51.876  2788  2788 I bluedroid: get_profile_interface pan
08-31 11:29:51.876  2788  2788 D PanService: mStartError = false
08-31 11:29:51.876  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
,08-31 11:29:51.886  2788  2788 D BluetoothMapService: Received start request. Starting profile...
,08-31 11:29:51.886  2788  2788 D BluetoothMapService: start()
,08-31 11:29:51.886  2788  2788 D BluetoothMapService: mStartError = false
,08-31 11:29:51.886  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
,08-31 11:29:51.886  2788  2788 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-31 11:29:51.886  2788  2788 D HeadsetPhoneState: Signal level : previous=0 curr=4
08-31 11:29:51.886  2788  7529 D HeadsetStateMachine: Disconnected process message: 18
,08-31 11:29:51.886  2788  2788 D SapService: Received start request. Starting profile...
,08-31 11:29:51.886  2788  2788 D SapService: start()
08-31 11:29:51.886  2788  2788 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-31 11:29:51.886  2788  2788 I bluedroid: get_profile_interface sap
08-31 11:29:51.886  2788  2788 D SapService: mStartError = false
08-31 11:29:51.886  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
08-31 11:29:51.886  2788  2788 E BluetoothAdapterService(777348176): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-31 11:29:51.886  2788  2788 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 11:29:51.886  2788  2788 E BluetoothAdapterService(777348176): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-31 11:29:51.886  2788  2788 E BluetoothAdapterService(777348176): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-31 11:29:51.886  2788  7529 D HeadsetStateMachine: Disconnected process message: 10
08-31 11:29:51.886  2788  7529 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 11:29:51.886  2788  7529 D HeadsetStateMachine: Disconnected process message: 11
,08-31 11:29:51.896  2788  2788 E BluetoothAdapterService(777348176): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-31 11:29:51.896  2788  2788 E BluetoothAdapterService(777348176): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-31 11:29:51.906  2788  2788 E BluetoothAdapterService(777348176): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-31 11:29:51.906  2788  2788 E BluetoothAdapterService(777348176): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-31 11:29:51.906  2788  2845 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-31 11:29:51.906  2788  2845 I bluedroid: enable
,08-31 11:29:51.916  2788  2848 E bt-btif : Calling BTA_HhEnable
,08-31 11:29:51.916  2788  2848 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-31 11:29:51.916  2788  2848 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-31 11:29:51.916  2788  2848 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-31 11:29:51.916  2788  2848 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
,08-31 11:29:51.916  2788  2848 E BluetoothServiceJni: populateRssiValuesNative
08-31 11:29:51.916  2788  2848 I bluedroid: getModelRssiValues
,08-31 11:29:51.916  2788  2848 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-31 11:29:51.916  2788  2848 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-31 11:29:51.916  1018  1018 D SettingsProvider: name = bluetooth_name
,08-31 11:29:51.916  2788  2848 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-31 11:29:51.926  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:51.926  2788  2848 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-31 11:29:51.926  2788  2848 D BluetoothAdapterProperties: Scan Mode:20
,08-31 11:29:51.926  2788  2848 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 11:29:51.926  2788  2848 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
,08-31 11:29:51.926  2788  2848 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-31 11:29:51.926  2788  2848 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-31 11:29:51.926  2788  2848 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-31 11:29:51.926  2788  2848 E bt-btif : JVenable fails
,08-31 11:29:51.936  2788  2848 D bte_conf: Device ID record 1 : primary
,08-31 11:29:51.936  2788  2848 D bte_conf:   vendorId            = 0075
08-31 11:29:51.936  2788  2848 D bte_conf:   vendorIdSource      = 0001
,08-31 11:29:51.936  2788  2848 D bte_conf:   product             = 0100
08-31 11:29:51.936  2788  2848 D bte_conf:   version             = 0200
08-31 11:29:51.936  2788  2848 D bte_conf:   clientExecutableURL = 
,08-31 11:29:51.936  2788  2848 D bte_conf:   serviceDescription  = 
,08-31 11:29:51.936  2788  2848 D bte_conf:   documentationURL    = 
,08-31 11:29:51.936  2788  2848 D bte_conf: bte_load_did_conf no section named DID2.
,08-31 11:29:51.936  2788  2845 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-31 11:29:51.936  2788  2845 D BluetoothAdapterProperties: ScanMode =  20
08-31 11:29:51.936  2788  2845 D BluetoothAdapterProperties: State =  11
,08-31 11:29:51.936  2788  2848 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-31 11:29:51.936  2788  2848 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 11:29:51.936  1018  1031 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-31 11:29:51.936  2788  2845 D BluetoothAdapterProperties: Setting state to 12
08-31 11:29:51.936  2788  2845 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-31 11:29:51.936  2788  2848 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 11:29:51.936  2788  2848 D BluetoothAdapterProperties: Scan Mode:21
08-31 11:29:51.936  2788  2848 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 11:29:51.946  1018  1322 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-31 11:29:51.946  1018  1322 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 11:29:51.946  1018  1322 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 11:29:51.946  1018  1322 D SettingsProvider: selectionArgs: false
,08-31 11:29:51.946  1018  1322 D SettingsProvider: selectionArgs: 1002
,08-31 11:29:51.946  1018  1322 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 11:29:51.946  1018  1322 D SettingsProvider: ret = -1
,08-31 11:29:51.946  2788  2845 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 11:29:51.946  2788  2845 D BluetoothAdapterService: updateAdapterState state is 12
,08-31 11:29:51.946  1018  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:29:51.946  1018  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 11:29:51.946  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:51.946  1018  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:51.946  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:51.956  6662  7396 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 11:29:51.956  2788  2788 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-31 11:29:51.956  2788  2788 I BluetoothPbapService: Handler(): got msg=1
,08-31 11:29:51.956  2788  2845 D BluetoothAdapterService: Autoconnection is available 
08-31 11:29:51.956  6662  7396 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 11:29:51.956  2788  2845 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
,08-31 11:29:51.956  2788  2845 D BluetoothAdapterService: starting service from this receiver
,08-31 11:29:51.956  1018  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 11:29:51.956  2788  2798 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 11:29:51.956  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:51.956  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:51.956  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:51.956  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:51.956  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:51.956  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:51.956  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:51.956  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:51.956  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-31 11:29:51.956  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:51.956  1018  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:51.956  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:51.966  2788  2798 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:29:51.966  1018  1496 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-31 11:29:51.966  6662  6662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:51.966  2788  2845 I BluetoothAdapterState: Entering On State from state = 11
,08-31 11:29:51.966  1018  1047 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-31 11:29:51.966  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 11:29:51.966  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:51.966  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:51.966  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:51.976  1448  1459 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 11:29:51.976  1448  1459 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:29:51.976  2788  7538 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-31 11:29:51.976  4482  7475 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:29:51.976  2788  2788 D BluetoothA2dp: Proxy object connected
08-31 11:29:51.976  2788  2788 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-31 11:29:51.996  2788  7538 D BluetoothSocket: bindListen(): myUserId = 0
,08-31 11:29:51.996  2788  7538 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:29:51.996  2788  7538 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
,08-31 11:29:51.996  2788  7538 D BluetoothSocket: bindListen(), new LocalSocket 
,08-31 11:29:51.996  2788  7538 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-31 11:29:51.996  2788  7538 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3074963
,08-31 11:29:51.996  2788  7538 D BluetoothSocket: channel: 19
,08-31 11:29:51.996  2788  7538 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-31 11:29:52.116  1018  1047 I art     : Explicit concurrent mark sweep GC freed 63511(3MB) AllocSpace objects, 6(97KB) LOS objects, 33% free, 22MB/34MB, paused 2.382ms total 144.835ms
08-31 11:29:52.116  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 11:29:52.116  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:29:52.126  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:52.126  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:52.126  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:52.126  4482  7475 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:29:52.126  1440  1468 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:29:52.126  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 11:29:52.126  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:29:52.126  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:52.126  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:52.126  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:52.126  4482  4482 D HeadsetProfile: Bluetooth service connected
08-31 11:29:52.126  1440  1468 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:29:52.126  7481  7495 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 11:29:52.126  7481  7495 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:29:52.126  4482  4490 D BluetoothPan: Binding service...
,08-31 11:29:52.126  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-31 11:29:52.126  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 11:29:52.136  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:52.136  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:52.136  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:52.136  1018  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-31 11:29:52.136  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 11:29:52.136  4482  4482 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 11:29:52.136  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-31 11:29:52.136  4482  4482 D PanProfile: Bluetooth service connected
08-31 11:29:52.136  1018  1047 E BluetoothHeadset: BluetoothHeadset service is binded
08-31 11:29:52.136  4482  7475 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 11:29:52.136  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-31 11:29:52.136  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 11:29:52.136  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:52.136  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:52.136  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:52.136  1458  2484 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:29:52.136  1458  2484 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 11:29:52.136  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 11:29:52.136  1018  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:29:52.136  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-31 11:29:52.136  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 11:29:52.136  1458  2039 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:29:52.136  1018  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 11:29:52.136  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:29:52.136  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:52.136  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:52.136  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:52.146  4482  4482 D BluetoothMap: Proxy object connected
,08-31 11:29:52.146  1458  2039 E BluetoothHeadset: BluetoothHeadset service is binded
08-31 11:29:52.146  4482  4482 D MapProfile: Bluetooth service connected
08-31 11:29:52.146  4482  4482 D BluetoothMap: getConnectedDevices()
,08-31 11:29:52.146  1440  1468 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:29:52.146  1018  1018 D BluetoothA2dp: Proxy object connected
,08-31 11:29:52.146  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 11:29:52.146  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:29:52.146  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:52.146  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:52.146  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:52.146  1440  1468 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:29:52.146  4482  4490 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 11:29:52.146  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-31 11:29:52.146  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 11:29:52.156  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:52.156  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:52.156  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:52.156  4482  4482 D BluetoothPbap: Proxy object connected
,08-31 11:29:52.156  1739  1756 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:29:52.156  1739  1756 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 11:29:52.156  4482  4482 D PbapServerProfile: Bluetooth service connected
,08-31 11:29:52.156  1681  1769 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:29:52.156  1681  1769 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 11:29:52.156  1018  1047 D BluetoothPan: Binding service...
,08-31 11:29:52.156  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-31 11:29:52.156  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 11:29:52.156  4482  7540 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 11:29:52.156  1018  1018 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 11:29:52.156  4482  7540 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:29:52.156  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-31 11:29:52.156  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 11:29:52.166  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:52.166  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:52.166  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:52.166  4482  4491 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:29:52.166  4482  4482 D BluetoothA2dp: Proxy object connected
08-31 11:29:52.166  4482  4482 D A2dpProfile: Bluetooth service connected
,08-31 11:29:52.166  4482  4491 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:29:52.166  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:29:52.166  1018  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:29:52.166  1440  7477 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 11:29:52.166  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-31 11:29:52.166  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 11:29:52.166  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:52.166  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:52.166  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:52.176  1440  7477 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 11:29:52.176  4482  7475 D Bluetoothsap: onBluetoothStateChange: up=true
,08-31 11:29:52.176  4482  7475 D Bluetoothsap: Binding service...
,08-31 11:29:52.176  4482  7475 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-31 11:29:52.176  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-31 11:29:52.176  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 11:29:52.176  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:52.176  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:52.176  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:52.176  4482  4482 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-31 11:29:52.186  4482  7475 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-31 11:29:52.186  4482  4482 D SapProfile: Bluetooth service connected
08-31 11:29:52.186  4482  4482 D Bluetoothsap: getConnectedDevices()
,08-31 11:29:52.186  1190  2205 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 11:29:52.186  1190  2205 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 11:29:52.186  2788  6963 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 11:29:52.186  2788  6963 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 11:29:52.186  4482  7540 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 11:29:52.186  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-31 11:29:52.186  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 11:29:52.186  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:52.186  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:52.186  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:52.186  1440  7519 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 11:29:52.186  1440  7519 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 11:29:52.186  4482  4482 D BluetoothInputDevice: Proxy object connected
08-31 11:29:52.186  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-31 11:29:52.186  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-31 11:29:52.186  4482  4482 D HidProfile: Bluetooth service connected
,08-31 11:29:52.196  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:52.196  1018  1018 I InputMethodManagerService: [BT Setting State] State =12
08-31 11:29:52.196  1018  1018 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-31 11:29:52.196  1440  1440 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@be51074, true
,08-31 11:29:52.196  1440  1440 D BluetoothHeadset: registerMessageListener
,08-31 11:29:52.196  1190  1190 D BluetoothTile:  onBluetoothStateChange:
,08-31 11:29:52.196  1973  1973 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 11:29:52.206  4482  4482 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:52.206  1190  1190 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 11:29:52.206  1190  1190 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 11:29:52.206  1190  1190 D BluetoothTile:  getBluetoothState : 12
,08-31 11:29:52.206  1190  1716 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 11:29:52.206  2788  2803 D HeadsetService: registerMessageListener
,08-31 11:29:52.206  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:52.206  2788  2803 D HeadsetService: registerMessageListener
08-31 11:29:52.206  2788  7529 D HeadsetStateMachine: Disconnected process message: 70
08-31 11:29:52.206  2788  7529 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@28089960
08-31 11:29:52.206  4482  4482 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-31 11:29:52.206  4482  4482 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-31 11:29:52.206  4482  4482 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-31 11:29:52.206  4482  4482 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-31 11:29:52.206  1440  1440 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-31 11:29:52.206  1440  1440 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-31 11:29:52.216  1190  1716 D BluetoothTile:  handleUpdatestate:false name:null
08-31 11:29:52.216  1440  1440 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-31 11:29:52.216  1440  1440 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-31 11:29:52.216  1440  1440 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-31 11:29:52.216  2788  7541 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-31 11:29:52.216  2788  7529 D HeadsetStateMachine: Disconnected process message: 9
08-31 11:29:52.216  2788  7529 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-31 11:29:52.216  1018  1496 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 11:29:52.216  1018  1720 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-31 11:29:52.216  1190  1190 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-31 11:29:52.216   282  1014 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-31 11:29:52.216   282  1014 V voice   : voice_set_parameters: enter: A2dpSuspended=false
,08-31 11:29:52.216   282  1014 V voice   : voice_set_parameters: exit with code(-2)
08-31 11:29:52.216   282  1014 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-31 11:29:52.216   282  1014 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-31 11:29:52.216   282  1014 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-31 11:29:52.216   282  1014 V audio_hw_primary: adev_set_parameters: exit,
08-31 11:29:52.216  1190  1716 D BluetoothTile:  handleUpdatestate:false name:null
08-31 11:29:52.216  2788  7529 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-31 11:29:52.216  4482  4482 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 11:29:52.216  1018  1136 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-31 11:29:52.216  1018  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 11:29:52.216  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:52.226  1018  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:52.226  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 11:29:52.226  2788  7541 D BluetoothSocket: bindListen(): myUserId = 0
08-31 11:29:52.226  2788  7541 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:29:52.226  2788  7541 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-31 11:29:52.226  2788  7541 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 11:29:52.226  2788  7541 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 11:29:52.226  2788  7541 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2aa4be19
,08-31 11:29:52.226  1681  1681 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 11:29:52.226  2788  7541 D BluetoothSocket: channel: 5
,08-31 11:29:52.236  4482  4482 D DockEventReceiver: finishStartingService: stopping service
,08-31 11:29:52.236  4482  4482 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 11:29:52.236  1190  1190 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 11:29:52.236  1190  1190 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-31 11:29:52.246  2788  2788 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e556450
,08-31 11:29:52.246  2788  2788 D BtConfig.SecureMode: isSecureModeOn:false
,08-31 11:29:52.246  1018  1218 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 11:29:52.246  1018  1218 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-31 11:29:52.246  1018  1218 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:52.246  1018  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 11:29:52.246  1018  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 11:29:52.256  1018  1031 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 11:29:52.266  2788  7546 D BluetoothSocket: bindListen(): myUserId = 0
,08-31 11:29:52.266  2788  7546 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 11:29:52.276  2788  7546 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-31 11:29:52.276  2788  7546 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 11:29:52.276  2788  7546 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 11:29:52.276  2788  7546 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@183a22d5
,08-31 11:29:52.276  2788  7546 D BluetoothSocket: channel: 12
08-31 11:29:52.276  2788  7546 I BtOppRfcommListener: Accept thread started.
,08-31 11:29:52.726   287   287 E SMD     : DCD OFF
,08-31 11:29:52.756  6662  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:52.756  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:52.756  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:52.756  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 11:29:52.756  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:52.756  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,08-31 11:29:52.756  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:52.756  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 11:29:52.756  6662  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:52.766  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:29:52.766  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@100a65b added. We now have 8 listener(s)
08-31 11:29:52.766  6662  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:52.766  1018  1496 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-31 11:29:52.766  1018  1496 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-31 11:29:52.766  1018  1496 D SecContentProvider2: mCursor = null
,08-31 11:29:52.776  1018  1496 D WifiService: setWifiEnabled: false pid=6662, uid=10170
,08-31 11:29:52.776  1018  1496 D SettingsProvider: name = wifi_on
,08-31 11:29:52.776  6662  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:52.776  1018  3256 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-31 11:29:52.776  1018  3256 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-31 11:29:52.776  1018  3256 D SecContentProvider2: mCursor = null
,08-31 11:29:52.786  1018  3256 D WifiService: setWifiEnabled: true pid=6662, uid=10170
,08-31 11:29:52.786  1018  3256 W ActivityManager: Permission Denial: getCurrentUser() from pid=6662, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-31 11:29:52.786  1018  3256 W WifiService: Failed getting userId using ActivityManagerNative
08-31 11:29:52.786  1018  3256 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6662, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-31 11:29:52.786  1018  3256 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-31 11:29:52.786  1018  3256 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-31 11:29:52.786  1018  3256 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-31 11:29:52.786  1018  3256 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-31 11:29:52.786  1018  3256 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-31 11:29:52.786  1018  3256 D SettingsProvider: name = wifi_on
,08-31 11:29:52.796  1018  1128 E WifiHW  : ##################### set firmware type 0 #####################
,08-31 11:29:53.116  1018  1045 D Tethering: interfaceAdded wlan0
,08-31 11:29:53.116  1018  1131 E Tethering: No numeric data
,08-31 11:29:53.126  1018  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 11:29:53.126  1018  1131 D Tethering: clearTetheredNotification()
,08-31 11:29:53.126  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-31 11:29:53.126  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:53.126  1190  1190 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
,08-31 11:29:53.126  1190  1190 D HotspotTile: updateTetherState():false, false
,08-31 11:29:53.136  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:29:53.136  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:29:53.136  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:53.136  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-31 11:29:53.136  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:29:53.136  1018  1131 D Tethering: InitialState.processMessage what=4
08-31 11:29:53.136  1018  1131 E Tethering: No numeric data
08-31 11:29:53.136  1018  1125 V NetworkStats: performPollLocked() took 13ms
08-31 11:29:53.136  1018  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 11:29:53.136  1018  1131 D Tethering: clearTetheredNotification()
,08-31 11:29:53.136  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:53.146  1190  1190 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 11:29:53.146  1190  1190 D HotspotTile: updateTetherState():false, false
,08-31 11:29:53.146  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:53.146  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:53.146  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:53.146  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-31 11:29:53.146  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:29:53.146  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:29:53.146  1018  1045 D Tethering: interfaceAdded p2p0
,08-31 11:29:53.156  1018  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-31 11:29:53.156  1018  1125 V NetworkStats: performPollLocked() took 6ms
08-31 11:29:53.156  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:53.156  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:53.156  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:53.156  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 11:29:53.156  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 11:29:53.156  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-31 11:29:53.166   277   967 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-31 11:29:53.166   277   967 D SoftapController: Softap fwReload - Ok
,08-31 11:29:53.166   277   967 D CommandListener: Setting iface cfg
08-31 11:29:53.166   277   967 D CommandListener: Trying to bring down wlan0,
08-31 11:29:53.166   277   967 D CommandListener: Clearing all IP addresses on wlan0,
,08-31 11:29:53.176  1018  1128 E WifiHW  : supplicant_name : p2p_supplicant
,08-31 11:29:53.176  1018  1128 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-31 11:29:53.196  1190  1190 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:29:53.196  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 11:29:53.196  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-31 11:29:53.196  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:53.196  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:53.196  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-31 11:29:53.196  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:53.196  1190  1190 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:29:53.196  1190  1190 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:29:53.196  1190  1190 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-31 11:29:53.196  1190  1716 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 11:29:53.196  1190  1190 D HotspotTile: onReceive : 2, 0
08-31 11:29:53.206  4482  4482 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:29:53.206  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-31 11:29:53.216  1018  1322 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-31 11:29:53.216  1018  1322 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:53.216  1018  1322 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 11:29:53.216  1018  1322 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:53.216  1018  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 11:29:53.216  1631  1631 I Hs20UtilService: Starting #19
,08-31 11:29:53.216  1631  1655 I Hs20UtilService: Message received 5011
,08-31 11:29:53.216  6849  6849 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 11:29:53.226  6849  6849 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-31 11:29:53.226  6849  6849 D SecurityLogAgent: StateMachine : Current State = 1
,08-31 11:29:53.226  6849  6849 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 11:29:53.236  7558  7558 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-31 11:29:53.236  7558  7558 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-31 11:29:53.236  7558  7558 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-31 11:29:53.256  7558  7558 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-31 11:29:53.256   396   396 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7558
,08-31 11:29:53.256   396   396 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-31 11:29:53.256  7558  7558 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running,
08-31 11:29:53.256  7558  7558 I wpa_supplicant: ssSupport state is = 1
,08-31 11:29:53.266  7558  7558 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-31 11:29:53.266  7558  7558 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-31 11:29:53.266   396   396 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7558
,08-31 11:29:53.266   396   396 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-31 11:29:53.426   396   396 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-31 11:29:53.436  7558  7558 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-31 11:29:53.476  7558  7558 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-31 11:29:53.476  7558  7558 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-31 11:29:53.486  7558  7558 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-31 11:29:53.486   396   396 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7558,
08-31 11:29:53.486   396   396 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-31 11:29:53.486  7558  7558 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-31 11:29:53.486  7558  7558 I wpa_supplicant: ssSupport state is = 1
08-31 11:29:53.486  7558  7558 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-31 11:29:53.486  7558  7558 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 11:29:53.486  7558  7558 E wpa_supplicant: SIM READ ERROR
08-31 11:29:53.486  7558  7558 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 11:29:53.486  7558  7558 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 11:29:53.486  7558  7558 E wpa_supplicant: SIM READ ERROR
,08-31 11:29:53.486  7558  7558 I wpa_supplicant: Blacklist: Clear (all) 
08-31 11:29:53.486  7558  7558 I wpa_supplicant: wpa_default_ap_write_once
08-31 11:29:53.486  7558  7558 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 11:29:53.486  7558  7558 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 11:29:53.486  7558  7558 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
08-31 11:29:53.486  7558  7558 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 11:29:53.486  7558  7558 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-31 11:29:53.496  7558  7558 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-31 11:29:53.496  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
08-31 11:29:53.496  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:53.496  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:29:53.546  7558  7558 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-31 11:29:53.786  7558  7558 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-31 11:29:53.786  7558  7558 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-31 11:29:53.796  7558  7558 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-31 11:29:53.796   396   396 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7558
08-31 11:29:53.796   396   396 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-31 11:29:53.806  7558  7558 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-31 11:29:53.806  7558  7558 I wpa_supplicant: ssSupport state is = 1
,08-31 11:29:53.806  7558  7558 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-31 11:29:53.806  7558  7558 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-31 11:29:53.816  7558  7558 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-31 11:29:53.816   396   396 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7558
08-31 11:29:53.816   396   396 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-31 11:29:53.816  7558  7558 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-31 11:29:53.816  7558  7558 I wpa_supplicant: ssSupport state is = 1
08-31 11:29:53.816  7558  7558 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 11:29:53.816  7558  7558 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-31 11:29:53.816  7558  7558 E wpa_supplicant: SIM READ ERROR
08-31 11:29:53.816  7558  7558 I wpa_supplicant: wpa_default_ap_write_once
08-31 11:29:53.816  7558  7558 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,08-31 11:29:53.816  7558  7558 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 11:29:53.826  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false,
08-31 11:29:53.826  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-31 11:29:53.826  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-31 11:29:53.826  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false,
08-31 11:29:53.826  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
08-31 11:29:53.826  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-31 11:29:53.866  7558  7558 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-31 11:29:53.866  7558  7558 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-31 11:29:53.926  7558  7558 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-31 11:29:53.926  7558  7558 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=,
08-31 11:29:53.926  7558  7558 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-31 11:29:53.936  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-31 11:29:53.936  1018  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-31 11:29:53.936  7558  7558 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-31 11:29:53.936  7558  7558 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-31 11:29:53.946  7558  7558 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 11:29:53.946  7558  7558 E wpa_supplicant: SIM READ ERROR
08-31 11:29:53.946  7558  7558 I wpa_supplicant: Blacklist: Clear (all) ,
,08-31 11:29:53.966  7558  7558 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-31 11:29:53.976  7558  7558 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-31 11:29:53.986  1018  1128 D WifiConfigStore: Loading config and enabling all networks ,
,08-31 11:29:53.986  1190  1190 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:29:53.986  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:53.986  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:29:53.986  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:53.986  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:53.986  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:53.986  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:53.986  1190  1190 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-31 11:29:53.996  4482  4482 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:29:53.996  1190  1190 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-31 11:29:53.996  1190  1190 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 11:29:53.996  1190  1716 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 11:29:53.996  1018  1320 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 11:29:53.996  1018  1320 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:29:53.996  1018  1320 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:53.996  1018  1320 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:53.996  1018  1320 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:29:53.996  1190  1190 D HotspotTile: onReceive : 3, 0
,08-31 11:29:54.006  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:54.006  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:54.006  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:54.006  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:54.006  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:54.006  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:54.006  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:54.006  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:54.006  1631  1631 I Hs20UtilService: Starting #20
,08-31 11:29:54.006  1631  1655 I Hs20UtilService: Message received 5011
08-31 11:29:54.006  6662  6662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:29:54.006  1018  1128 E WifiConfigStore: Not a HS20
08-31 11:29:54.006  1018  1128 D WifiNative-wlan0: callSECApiInt - ID [65]
08-31 11:29:54.016  6849  6849 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 11:29:54.016  6849  6849 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 11:29:54.016  6849  6849 D SecurityLogAgent: StateMachine : Current State = 1
08-31 11:29:54.016  1018  1128 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-31 11:29:54.016  7558  7558 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-31 11:29:54.016  7558  7558 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-31 11:29:54.016  7558  7558 I wpa_supplicant: reset timer : RESET_TIMER 0
08-31 11:29:54.016  7558  7558 I wpa_supplicant: P2P: Current p2p state = IDLE
08-31 11:29:54.016  7558  7558 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-31 11:29:54.016  7558  7558 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-31 11:29:54.016  7558  7558 I wpa_supplicant: First Scan Start
08-31 11:29:54.016  7558  7558 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-31 11:29:54.016  1018  1128 D WifiNative-wlan0: Setting external_sim to 1
08-31 11:29:54.016  1018  1128 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 11:29:54.016  1018  1128 I WifiNative-HAL: startHal
08-31 11:29:54.016  1018  1128 E wifi    : getStaticLongField sWifiHalHandle 0x9f26588c
08-31 11:29:54.016  1018  1128 I WifiNative-HAL: Could not start hal
08-31 11:29:54.016  7032  7032 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 11:29:54.016  6849  6849 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-31 11:29:54.016  1018  1128 E WifiNative-wlan0: do suspend true
08-31 11:29:54.016  1018  1127 D WifiP2pService: P2pDisabledState{ what=131203 }
08-31 11:29:54.026   277   967 D CommandListener: Setting iface cfg
08-31 11:29:54.026   277   967 D CommandListener: Trying to bring up p2p0
08-31 11:29:54.026  1018  1127 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-31 11:29:54.026  1018  1127 D WifiP2pService: P2pEnablingState
08-31 11:29:54.026  1018  1127 D WifiP2pService: P2pEnablingState{ what=147457 }
08-31 11:29:54.026  1018  1127 D WifiP2pService: P2p socket connection successful
08-31 11:29:54.026  1018  1127 D WifiP2pService: P2pEnabledState
08-31 11:29:54.026  1018  1130 E ConnectivityService: updateNetworkInfo()
08-31 11:29:54.026  1018  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-31 11:29:54.026  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-31 11:29:54.026  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-31 11:29:54.026  1018  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 11:29:54.026  1018  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 11:29:54.026  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-31 11:29:54.026  1018  1128 E WifiNative-wlan0: invaild command id : 215
08-31 11:29:54.026  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 11:29:54.026  1018  1048 D WifiDisplayController: disconnect
08-31 11:29:54.026  1018  1048 D WifiDisplayController: updateConnection
08-31 11:29:54.026  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 11:29:54.026  1018  1127 D WifiNative-p2p0: p2pGetDeviceAddress
08-31 11:29:54.026  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-31 11:29:54.026  1018  1127 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
08-31 11:29:54.036  1018  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 11:29:54.036  1018  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 11:29:54.036  1018  1128 E WifiNative-wlan0: invaild command id : 215
08-31 11:29:54.036  7558  7558 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-31 11:29:54.036  7558  7558 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-31 11:29:54.036  7558  7558 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-31 11:29:54.036  1018  1128 E WifiStateMachine: Failed to set frequency band 0
08-31 11:29:54.036  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 3
08-31 11:29:54.036  1018  1152 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:29:54.036  1018  1152 I WifiNative-HAL: startHal
08-31 11:29:54.036  1018  1152 E wifi    : getStaticLongField sWifiHalHandle 0x9e1279bc
08-31 11:29:54.036  1018  1152 I WifiNative-HAL: Could not start hal
08-31 11:29:54.036  1018  1152 E WifiScanningService: could not start HAL
08-31 11:29:54.036  1018  1018 D RttService: SCAN_AVAILABLE : 3
08-31 11:29:54.036  1018  1153 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:29:54.046  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:29:54.046  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 11:29:54.046  1018  1128 D SecContentProvider2: mCursor = null
08-31 11:29:54.046  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-31 11:29:54.046  4482  4482 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-31 11:29:54.046  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 11:29:54.046  4482  4482 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-31 11:29:54.046  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
08-31 11:29:54.046  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-31 11:29:54.046  1190  1190 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-31 11:29:54.046  1018  1320 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-31 11:29:54.046  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:29:54.046  1190  1190 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-31 11:29:54.046  1018  1128 D SecContentProvider2: mCursor = null
08-31 11:29:54.046  1018  1127 D WifiP2pService: DeviceAddress: 0a:75:42
08-31 11:29:54.046  1018  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-31 11:29:54.046  1018  1048 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-31 11:29:54.046  1018  1048 D WifiDisplayController:  primary type: 10-0050F204-5
08-31 11:29:54.046  1018  1048 D WifiDisplayController:  secondary type: null
08-31 11:29:54.046  1018  1048 D WifiDisplayController:  wps: 0
08-31 11:29:54.046  1018  1048 D WifiDisplayController:  grpcapab: 0
08-31 11:29:54.046  1018  1048 D WifiDisplayController:  devcapab: 0
08-31 11:29:54.046  1018  1048 D WifiDisplayController:  status: 3
08-31 11:29:54.046  1018  1048 D WifiDisplayController:  wfdInfo: null
08-31 11:29:54.046  1018  1048 D WifiDisplayController:  groupownerAddress: null
08-31 11:29:54.046  1018  1048 D WifiDisplayController:  GOdeviceName: null
08-31 11:29:54.046  1018  1048 D WifiDisplayController:  interfaceAddress: 
08-31 11:29:54.046  1018  1048 D WifiDisplayController:  SConnectInfo : null
08-31 11:29:54.046  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 11:29:54.046  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 11:29:54.046  4482  4482 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 11:29:54.046  4482  4521 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 11:29:54.056  7397  7397 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 11:29:54.056  7397  7397 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-31 11:29:54.056  7397  7397 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 11:29:54.066  1018  1127 D WifiP2pService: sending p2p persistent groups changed broadcast
08-31 11:29:54.066  7073  7073 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 11:29:54.066  1018  1127 D WifiP2pService: InactiveState
08-31 11:29:54.066  1018  1127 D WifiP2pService: InactiveState{ what=143376 }
,08-31 11:29:54.066  1018  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 11:29:54.066  7558  7558 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 11:29:54.066  1018  1127 D WifiP2pService: InactiveState{ what=143376 }
,08-31 11:29:54.066  1018  1127 D WifiP2pService: P2pEnabledState{ what=143376 },
,08-31 11:29:54.126  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 11:29:54.126  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 11:29:54.126  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-31 11:29:54.716  1018  2869 D SSRM:n  : SIOP:: AP = 330,
,08-31 11:29:54.816  6662  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:54.816  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:54.816  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:54.816  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:54.816  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:54.816  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:54.816  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:54.816  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:54.816  6662  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-31 11:29:54.826  6662  6834 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-31 11:29:54.826  6662  6834 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-31 11:29:54.826  6662  6834 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1d3a33fe Bundle[{}]
,08-31 11:29:54.826  6662  6834 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 11:29:54.826  6662  6834 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-31 11:29:54.826  6662  6834 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-31 11:29:54.826  6662  6834 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-31 11:29:54.826  6662  6834 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-31 11:29:54.826  6662  6834 D io.jxcore.node.LifeCycleMonitor: onActivityPaused,
,08-31 11:29:54.836  6662  6834 I System.out: Running OutgoingSocketThread
,08-31 11:29:54.846  6662  7567 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1340)
,08-31 11:29:54.846  6662  7567 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 33339
,08-31 11:29:54.846  6662  7567 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-31 11:29:55.226  7558  7558 I wpa_supplicant: nl80211: Received scan results (25 BSSes),
08-31 11:29:55.226  7558  7558 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
08-31 11:29:55.226  7558  7558 I wpa_supplicant: Trying to associate with SSID '4E47373030',
08-31 11:29:55.226  7558  7558 I wpa_supplicant: Trying to associate with  'G700'
08-31 11:29:55.226  7558  7558 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-31 11:29:55.226  7558  7558 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-31 11:29:55.226  1018  7564 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-31 11:29:55.236  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:29:55.236  1018  1128 D SecContentProvider2: mCursor = null
,08-31 11:29:55.336  7558  7558 E wpa_supplicant: Cmd 35605 not handled
,08-31 11:29:55.336  7558  7558 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 11:29:55.336  7558  7558 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-31 11:29:55.336  7558  7558 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-31 11:29:55.336  7558  7558 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-31 11:29:55.336  7558  7558 I wpa_supplicant: Associated with F4.99.3E
08-31 11:29:55.336  7558  7558 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 11:29:55.336  7558  7558 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-31 11:29:55.336  7558  7558 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-31 11:29:55.336  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,08-31 11:29:55.336  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 11:29:55.336  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-31 11:29:55.336  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 11:29:55.336  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:29:55.336  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:29:55.336  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 11:29:55.336  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 11:29:55.336  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-31 11:29:55.336  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-31 11:29:55.336  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
,08-31 11:29:55.336  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
,08-31 11:29:55.336  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:29:55.336  1018  1128 D SecContentProvider2: mCursor = null
,08-31 11:29:55.336  7558  7558 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e,
08-31 11:29:55.336  7558  7558 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-31 11:29:55.336  7558  7558 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-31 11:29:55.336  7558  7558 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-31 11:29:55.336  7558  7558 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-31 11:29:55.336  7558  7558 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-31 11:29:55.336  7558  7558 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-31 11:29:55.336  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 11:29:55.336  7558  7558 I wpa_supplicant: Blacklist: Clear (temp) 
08-31 11:29:55.336  1018  1128 D SecContentProvider2: mCursor = null
08-31 11:29:55.336  7558  7558 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-31 11:29:55.346  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-31 11:29:55.346  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 11:29:55.346  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
,08-31 11:29:55.346  1018  1131 E Tethering: No numeric data
,08-31 11:29:55.346  1018  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 11:29:55.346  1018  1131 D Tethering: clearTetheredNotification()
,08-31 11:29:55.356  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
08-31 11:29:55.356  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:55.356  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-31 11:29:55.356  1190  1190 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-31 11:29:55.356  1190  1190 D HotspotTile: updateTetherState():false, false
08-31 11:29:55.356  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:29:55.356  1018  1128 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-31 11:29:55.356  1018  1128 E WifiConfigStore: setLastSelectedConfiguration -1
,08-31 11:29:55.356  1018  1125 V NetworkStats: performPollLocked() took 9ms
08-31 11:29:55.356  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:55.366  1190  1190 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-31 11:29:55.366  1018  1128 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-31 11:29:55.366  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:55.366  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:29:55.366  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:29:55.366  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:55.366  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:55.366  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:55.366  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:55.366  1018  1130 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-31 11:29:55.366  1018  1130 E ConnectivityService: updateNetworkInfo()
,08-31 11:29:55.376  1018  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 11:29:55.376  1018  1496 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 11:29:55.376  1018  1496 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 11:29:55.376  1018  1496 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:55.386  1018  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
,08-31 11:29:55.386  1018  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:29:55.386  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-31 11:29:55.386  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:55.386  1018  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 11:29:55.396  1631  1631 I Hs20UtilService: Starting #21
,08-31 11:29:55.396  1631  1655 I Hs20UtilService: Message received 5007
,08-31 11:29:55.396  4482  4482 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 11:29:55.396  4482  4482 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 11:29:55.396  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 11:29:55.396  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 11:29:55.396  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false,
08-31 11:29:55.406  4482  4482 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 11:29:55.406  4482  4521 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 11:29:55.406   277   967 D CommandListener: Setting iface cfg,
,08-31 11:29:55.406  1018  1128 E WifiStateMachine: Start Dhcp Watchdog 3
,08-31 11:29:55.416  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 11:29:55.416  1018  1128 D SecContentProvider2: mCursor = null
,08-31 11:29:55.426  1190  1190 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:29:55.426  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 11:29:55.426  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-31 11:29:55.426  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:55.426  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:55.426  1018  1128 E WifiNative-wlan0: do suspend false
08-31 11:29:55.426  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:55.426  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:55.426  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 11:29:55.426  1018  1128 D SecContentProvider2: mCursor = null
,08-31 11:29:55.436  1018  1127 D WifiP2pService: InactiveState{ what=143375 }
,08-31 11:29:55.436  1018  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 11:29:55.646  7570  7570 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-31 11:29:55.656  7570  7570 I dhcpcd  : version 5.5.6 starting,
,08-31 11:29:55.656  7570  7570 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-31 11:29:55.716  7570  7570 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-31 11:29:55.716  7570  7570 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-31 11:29:55.716  7570  7570 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,08-31 11:29:55.716  7570  7570 I dhcpcd  : bssid match
08-31 11:29:55.716  7570  7570 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-31 11:29:55.726   287   287 E SMD     : DCD OFF,
,08-31 11:29:55.766  7570  7570 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,08-31 11:29:55.846  7570  7570 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds,
08-31 11:29:55.846  6662  6834 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1341)
08-31 11:29:55.846  6662  6834 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1341)
,08-31 11:29:55.846  6662  6834 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1346)
08-31 11:29:55.846  6662  6834 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-31 11:29:55.846  6662  6834 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1347)
,08-31 11:29:55.846  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:29:55.846  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2558bef8 added. We now have 2 listener(s)
08-31 11:29:55.856  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-31 11:29:55.856  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 11:29:55.856  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:29:55.856  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:55.856  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cc90fd1 added. We now have 9 listener(s)
08-31 11:29:55.856  6662  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:55.856  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 11:29:55.866  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:29:55.866  6662  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:55.866  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:55.866  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:55.866  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:55.866  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:55.866  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:55.866  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:55.866  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:55.876  6662  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:29:55.876  6662  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:29:55.886  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:29:55.886  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a194d37 added. We now have 3 listener(s)
08-31 11:29:55.886  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:55.886  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:55.886  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-31 11:29:55.886  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:55.886  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:29:55.886  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-31 11:29:55.886  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21d6d2a4 added. We now have 10 listener(s)
08-31 11:29:55.886  6662  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:29:55.886  6662  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:55.886  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:55.886  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:55.886  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:55.886  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:55.886  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:29:55.886  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:55.886  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2558bef8 removed from the list
08-31 11:29:55.886  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:55.886  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cc90fd1 removed from the list
,08-31 11:29:55.886  6662  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:55.886  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:55.886  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-31 11:29:55.886  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:55.886  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 11:29:55.886  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:55.886  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:55.886  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cc90fd1 not in the list
08-31 11:29:55.886  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:29:55.886  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:55.886  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:55.886  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:55.886  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:55.886  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21d6d2a4 removed from the list
08-31 11:29:55.886  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:55.886  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:55.886  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:55.886  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:55.886  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a194d37 removed from the list
08-31 11:29:55.886  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:29:55.886  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7dd80d added. We now have 2 listener(s)
,08-31 11:29:55.896  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-31 11:29:55.896  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:55.896  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:29:55.896  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 11:29:55.896  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37723c2 added. We now have 9 listener(s)
08-31 11:29:55.896  6662  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:55.906  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 11:29:55.906  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:29:55.906  6662  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-31 11:29:55.906  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:55.906  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:55.906  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:55.906  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:55.906  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:55.906  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:55.906  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:55.916  6662  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 11:29:55.916  6662  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:29:55.916  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:29:55.916  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10007510 added. We now have 3 listener(s)
,08-31 11:29:55.916  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:55.916  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 11:29:55.916  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-31 11:29:55.916  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:55.916  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:29:55.916  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:55.916  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3ce809 added. We now have 10 listener(s)
,08-31 11:29:55.916  6662  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:29:55.916  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:29:55.916  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:29:55.916  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-31 11:29:55.916  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:55.916  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 11:29:55.926  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 11:29:55.936  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 11:29:55.936  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 11:29:55.946  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 11:29:55.946  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 11:29:55.946  6662  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 11:29:55.956  2788  6963 D BtGatt.GattService: registerClient() - UUID=3baf510a-0086-427c-b9e9-c46f5b4f6c4e
,08-31 11:29:55.996  2788  2848 D BtGatt.GattService: onClientRegistered() - UUID=3baf510a-0086-427c-b9e9-c46f5b4f6c4e, clientIf=6
,08-31 11:29:55.996  6662  6670 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-31 11:29:55.996  2788  2803 D BtGatt.GattService: start scan with filters
,08-31 11:29:55.996  2788  2905 D BtGatt.ScanManager: handling starting scan
08-31 11:29:55.996  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 11:29:55.996  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 11:29:55.996  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 11:29:55.996  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 11:29:56.006  2788  2848 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
08-31 11:29:56.006  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:56.006  2788  2905 D BtGatt.ScanManager: allow scan with filters
08-31 11:29:56.006  2788  2905 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-31 11:29:56.006  2788  2905 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
,08-31 11:29:56.006  2788  2848 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-31 11:29:56.006  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-31 11:29:56.006  2788  2905 D BtGatt.ScanManager: Starting BLE batch scan
08-31 11:29:56.006  2788  2905 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 11:29:56.006  2788  2848 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-31 11:29:56.006  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:56.006  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:29:56.016  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 11:29:56.016  6662  6662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:29:56.016  2788  2848 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-31 11:29:56.016  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:56.016  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 11:29:56.016  6662  6834 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-31 11:29:56.016  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:56.016  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 11:29:56.016  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:56.016  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:29:56.016  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 11:29:56.016  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:29:56.016  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:29:56.016  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:29:56.016  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:29:56.016  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 11:29:56.026  2788  2798 D BtGatt.GattService: stopScan() - queue size =1,
,08-31 11:29:56.026  2788  6962 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 11:29:56.026  2788  2905 D BtGatt.ScanManager: filter size is 1
08-31 11:29:56.026  2788  2905 D BtGatt.ScanManager: delete FilterIndex - 6
08-31 11:29:56.026  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 11:29:56.026  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 11:29:56.026  2788  2848 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-31 11:29:56.026  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 11:29:56.026  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:56.026  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 11:29:56.026  2788  2905 D BtGatt.ScanManager: stopping BLe Batch
08-31 11:29:56.026  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 11:29:56.026  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:29:56.026  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 11:29:56.026  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
,08-31 11:29:56.036  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 11:29:56.036  2788  2848 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-31 11:29:56.036  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:56.036  2788  2905 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-31 11:29:56.036  2788  2848 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
08-31 11:29:56.036  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:56.036  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:29:56.046  6662  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-31 11:29:56.046  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-31 11:29:56.046  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:56.046  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:29:56.046  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:56.046  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:29:56.046  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-31 11:29:56.046  6662  6662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:56.046  6662  6662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-31 11:29:56.046  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7dd80d removed from the list
08-31 11:29:56.046  6662  6662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:29:56.046  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:56.046  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37723c2 removed from the list
08-31 11:29:56.046  6662  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:56.046  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:56.046  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:56.046  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:56.046  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:56.046  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:56.046  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:56.046  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37723c2 not in the list
08-31 11:29:56.046  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:56.046  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:56.046  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 11:29:56.046  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:56.046  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:56.046  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3ce809 removed from the list
08-31 11:29:56.046  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:29:56.046  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:56.046  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:56.046  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:56.046  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10007510 removed from the list
08-31 11:29:56.056  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:29:56.056  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc2fbc5 added. We now have 2 listener(s)
,08-31 11:29:56.056  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-31 11:29:56.056  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:56.056  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:29:56.056  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:56.056  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@419691a added. We now have 9 listener(s)
08-31 11:29:56.056  6662  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:56.056  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 11:29:56.066  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-31 11:29:56.066  6662  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:56.066  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:56.066  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:56.066  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:56.066  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:56.066  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:56.066  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false,
08-31 11:29:56.066  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:56.076  6662  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:56.076  6662  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:29:56.076  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 11:29:56.076  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f5d628 added. We now have 3 listener(s)
,08-31 11:29:56.086  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:56.086  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:56.086  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-31 11:29:56.086  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:56.086  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:29:56.086  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:56.086  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7dc8f41 added. We now have 10 listener(s)
08-31 11:29:56.086  6662  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:29:56.086  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:29:56.086  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:29:56.086  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:29:56.086  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:29:56.086  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:56.086  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 11:29:56.096  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,08-31 11:29:56.096  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 11:29:56.106  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 11:29:56.116  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 11:29:56.116  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 11:29:56.116  6662  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 11:29:56.116  2788  6962 D BtGatt.GattService: registerClient() - UUID=c2d0b6aa-ae0c-4934-be93-fef9df7cfd6a
,08-31 11:29:56.136  1018  1043 W ProcessCpuTracker: Skipping unknown process pid 7577,
,08-31 11:29:56.156  2788  2848 D BtGatt.GattService: onClientRegistered() - UUID=c2d0b6aa-ae0c-4934-be93-fef9df7cfd6a, clientIf=6
,08-31 11:29:56.156  6662  6670 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-31 11:29:56.156  2788  7539 D BtGatt.GattService: start scan with filters
,08-31 11:29:56.156  2788  2905 D BtGatt.ScanManager: handling starting scan
,08-31 11:29:56.156  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 11:29:56.156  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 11:29:56.156  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 11:29:56.156  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 11:29:56.156  2788  2848 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-31 11:29:56.156  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:56.156  2788  2905 D BtGatt.ScanManager: allow scan with filters
08-31 11:29:56.156  2788  2905 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-31 11:29:56.156  2788  2905 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,08-31 11:29:56.166  2788  2848 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-31 11:29:56.166  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:56.166  2788  2905 D BtGatt.ScanManager: Starting BLE batch scan
08-31 11:29:56.166  2788  2905 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 11:29:56.166  2788  2848 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-31 11:29:56.166  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:56.166  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:29:56.166  6662  6662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:29:56.166  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 11:29:56.166  2788  2848 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
08-31 11:29:56.166  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:56.176  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 11:29:56.176  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 11:29:56.176  6662  6834 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-31 11:29:56.176  6662  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:29:56.176  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:56.176  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 11:29:56.176  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 11:29:56.176  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:56.176  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:29:56.176  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-31 11:29:56.176  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc2fbc5 removed from the list
08-31 11:29:56.176  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:29:56.176  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@419691a removed from the list
08-31 11:29:56.176  6662  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:56.176  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:29:56.186  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:56.186  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-31 11:29:56.186  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:56.186  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:29:56.186  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 11:29:56.186  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:56.186  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 11:29:56.186  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@419691a not in the list
08-31 11:29:56.186  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:29:56.186  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-31 11:29:56.186  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:29:56.186  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-31 11:29:56.186  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 11:29:56.186  2788  2849 D BtGatt.GattService: stopScan() - queue size =1
,08-31 11:29:56.186  2788  2905 D BtGatt.ScanManager: filter size is 1,
08-31 11:29:56.186  2788  2905 D BtGatt.ScanManager: delete FilterIndex - 7
,08-31 11:29:56.186  2788  2798 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 11:29:56.186  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:29:56.186  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 11:29:56.186  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 11:29:56.186  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 11:29:56.186  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 11:29:56.186  2788  2848 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-31 11:29:56.186  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:56.186  2788  2905 D BtGatt.ScanManager: stopping BLe Batch
,08-31 11:29:56.186  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 11:29:56.196  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 11:29:56.196  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:29:56.196  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 11:29:56.196  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:56.196  6662  6662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-31 11:29:56.196  6662  6662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:56.196  6662  6662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:29:56.196  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:56.196  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 11:29:56.196  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:56.196  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7dc8f41 removed from the list
08-31 11:29:56.196  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:56.196  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:29:56.196  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:56.196  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:56.196  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f5d628 removed from the list,
08-31 11:29:56.196  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:29:56.196  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a1de7d added. We now have 2 listener(s)
,08-31 11:29:56.196  2788  2848 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-31 11:29:56.196  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:56.196  2788  2905 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-31 11:29:56.196  2788  2848 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-31 11:29:56.196  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:56.196  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-31 11:29:56.196  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:56.196  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:29:56.196  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:56.196  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38640172 added. We now have 9 listener(s)
08-31 11:29:56.196  6662  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 11:29:56.196  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 11:29:56.206  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:29:56.206  6662  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:56.206  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:56.206  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:56.206  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:56.206  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:56.206  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 11:29:56.206  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 11:29:56.206  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 11:29:56.206  6662  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 11:29:56.206  6662  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:29:56.206  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:29:56.206  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2be34240 added. We now have 3 listener(s)
,08-31 11:29:56.206  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:56.206  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:56.216  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-31 11:29:56.216  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:56.216  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:29:56.216  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:56.216  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b72e579 added. We now have 10 listener(s)
08-31 11:29:56.216  6662  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:29:56.216  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:29:56.216  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 11:29:56.216  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 11:29:56.216  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 11:29:56.216  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 11:29:56.216  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 11:29:56.216  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 11:29:56.216  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 11:29:56.226  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 11:29:56.226  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-31 11:29:56.226  6662  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 11:29:56.226  2788  6962 D BtGatt.GattService: registerClient() - UUID=2113df4b-d2c9-4f55-81b8-16d2079c828e
,08-31 11:29:56.256  1018  1128 E WifiNative-wlan0: do suspend true
,08-31 11:29:56.276  2788  2848 D BtGatt.GattService: onClientRegistered() - UUID=2113df4b-d2c9-4f55-81b8-16d2079c828e, clientIf=6
,08-31 11:29:56.276  6662  7396 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-31 11:29:56.276  2788  7539 D BtGatt.GattService: start scan with filters
,08-31 11:29:56.276  2788  2905 D BtGatt.ScanManager: handling starting scan
,08-31 11:29:56.276  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 11:29:56.276  2788  2848 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-31 11:29:56.276  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:56.276  2788  2905 D BtGatt.ScanManager: allow scan with filters
,08-31 11:29:56.276  2788  2905 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-31 11:29:56.276  2788  2905 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
,08-31 11:29:56.276  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-31 11:29:56.276  1018  1127 D WifiP2pService: InactiveState{ what=143375 }
,08-31 11:29:56.276  1018  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 11:29:56.276  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 11:29:56.276  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 11:29:56.276  2788  2848 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-31 11:29:56.276  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:56.286  2788  2905 D BtGatt.ScanManager: Starting BLE batch scan
08-31 11:29:56.286  2788  2905 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-31 11:29:56.286  1018  1128 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-31 11:29:56.286  1018  1128 E WifiStateMachine: VerifyingLinkState enter
,08-31 11:29:56.286  1018  1130 E ConnectivityService: updateNetworkInfo()
,08-31 11:29:56.286  2788  2848 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-31 11:29:56.296  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 11:29:56.296  1018  1130 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-31 11:29:56.296  1018  1130 D ConnectivityService: Adding iface wlan0 to network 504
,08-31 11:29:56.296  1190  1190 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-31 11:29:56.296  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:56.296  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:29:56.296  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:56.296  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:56.296  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:56.296  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:56.306  1018  1146 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-31 11:29:56.306  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 11:29:56.306  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 11:29:56.306  6662  6662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 11:29:56.306  2788  2848 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
08-31 11:29:56.306  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,08-31 11:29:56.306  1018  1146 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
08-31 11:29:56.306  1018  1146 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-31 11:29:56.306  1018  1146 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-31 11:29:56.306  1018  1146 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-31 11:29:56.326  1190  1190 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:29:56.326  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 11:29:56.326  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-31 11:29:56.326  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:56.326  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:56.326  1018  1490 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 11:29:56.326  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:56.326  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 11:29:56.326  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:56.336  1018  1128 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-31 11:29:56.336  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:56.336  1018  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:56.336  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:29:56.336  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
08-31 11:29:56.336  1631  1631 I Hs20UtilService: Starting #22
08-31 11:29:56.346  1631  1655 I Hs20UtilService: Message received 5007
08-31 11:29:56.346  4482  4482 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 11:29:56.346  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-31 11:29:56.356  1018  1130 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-31 11:29:56.356  1018  1130 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-31 11:29:56.356  1018  1130 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-31 11:29:56.356  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-31 11:29:56.356  1018  1128 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-31 11:29:56.356  1018  1018 I WifiTrafficPoller: mBoosterFLAG : 0
08-31 11:29:56.356  1018  1128 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-31 11:29:56.356  1018  1018 I WifiTrafficPoller: current booster mode : FullMode
08-31 11:29:56.356  1018  1130 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 11:29:56.356  4482  4482 I NearbySettings: MountReceiver.onReceive - Keep current state
08-31 11:29:56.356  1018  1130 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-31 11:29:56.356  1018  1130 D ConnectivityService: LTETest block dns file not exists
,08-31 11:29:56.366  1190  1190 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:29:56.366  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:56.366  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 11:29:56.366  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:56.366  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:56.366  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:56.366  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:56.366  1190  1190 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 11:29:56.366  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-31 11:29:56.366  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:56.366  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:56.366  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:56.366  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:56.376  6662  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 11:29:56.376  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:56.376  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:56.376  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:56.376  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:56.376  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 11:29:56.376  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:56.376  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a1de7d removed from the list
08-31 11:29:56.376  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:56.376  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38640172 removed from the list
08-31 11:29:56.376  6662  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:56.376  1018  1130 V NetworkStats: updateIfacesLocked()
08-31 11:29:56.376  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:29:56.376  1018  1130 V NetworkStats: performPollLocked(flags=0x1)
08-31 11:29:56.376  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:56.376  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:56.376  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-31 11:29:56.376  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:56.386  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 11:29:56.386  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:29:56.386  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:29:56.386  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:56.386  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:56.386  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:56.386  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38640172 not in the list
08-31 11:29:56.386  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 11:29:56.386  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 11:29:56.386  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 11:29:56.386  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 11:29:56.386  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 11:29:56.386  1018  1130 V NetworkStats: performPollLocked() took 9ms
08-31 11:29:56.386  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:56.396  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:56.396  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:56.396  1018  1130 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-31 11:29:56.396  1018  1130 E ConnectivityService: updateNetworkInfo()
08-31 11:29:56.396  1018  1130 E ConnectivityService: updateNetworkInfo()
08-31 11:29:56.396  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 11:29:56.396  1018  1130 V NetworkStats: updateIfacesLocked()
08-31 11:29:56.396  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:56.396  1018  1130 V NetworkStats: performPollLocked(flags=0x1)
,08-31 11:29:56.396  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:29:56.396  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:29:56.396  2788  6963 D BtGatt.GattService: stopScan() - queue size =1
08-31 11:29:56.396  2788  2905 D BtGatt.ScanManager: filter size is 1
08-31 11:29:56.396  2788  2905 D BtGatt.ScanManager: delete FilterIndex - 8
,08-31 11:29:56.396  2788  2849 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 11:29:56.396  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 11:29:56.396  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 11:29:56.396  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 11:29:56.396  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 11:29:56.396  1018  1130 V NetworkStats: performPollLocked() took 5ms
08-31 11:29:56.396  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-31 11:29:56.396  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:56.396  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:29:56.396  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:56.396  1018  1130 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-31 11:29:56.396  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:56.396  1018  1322 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 11:29:56.396  1018  7568 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:29:56.396  1018  1322 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 11:29:56.396  1018  7568 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-31 11:29:56.396  1018  1130 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-31 11:29:56.396  1018  7568 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 11:29:56.396  1018  7568 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-31 11:29:56.396  1018  1322 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:56.396  1018  1322 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:56.396  1018  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 11:29:56.406  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 11:29:56.406  6662  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 11:29:56.406  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 11:29:56.406  2788  2848 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-31 11:29:56.406  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:56.406  2788  2905 D BtGatt.ScanManager: stopping BLe Batch
08-31 11:29:56.406  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:56.406  1018  7568 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-31 11:29:56.406  1631  1631 I Hs20UtilService: Starting #23
08-31 11:29:56.406  1018  1130 D ConnectivityService:    accepting network in place of null
08-31 11:29:56.406  1018  1128 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-31 11:29:56.406  1018  1127 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-31 11:29:56.406  1458  1458 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-31 11:29:56.406  1458  1458 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 11:29:56.406   277   963 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 11:29:56.406   277   963 D Netd    : getNetworkForDns: using netid 504 for uid 1000
08-31 11:29:56.406  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:56.406  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:56.406  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:56.406  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b72e579 removed from the list
08-31 11:29:56.406  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:56.406  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:56.406  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:56.406  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:56.406  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2be34240 removed from the list
08-31 11:29:56.406  6662  6662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:56.406  6662  6662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 11:29:56.406  6662  6662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 11:29:56.406  2788  2848 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-31 11:29:56.406  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:56.406  2788  2905 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-31 11:29:56.406  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:29:56.406  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17b36035 added. We now have 2 listener(s)
08-31 11:29:56.406  1018  1130 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-31 11:29:56.406  1018  1130 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-31 11:29:56.406  2788  2848 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-31 11:29:56.406  1018  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 11:29:56.406  2788  2848 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 11:29:56.406  1631  1655 I Hs20UtilService: Message received 5007
08-31 11:29:56.416  1018  1130 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-31 11:29:56.416  1018  1018 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-31 11:29:56.416  1018  1131 D Tethering: MasterInitialState.processMessage what=3
08-31 11:29:56.416  4482  4482 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 11:29:56.416  4482  4482 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-31 11:29:56.416  1018  1125 V NetworkStats: updateIfacesLocked()
08-31 11:29:56.416  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:56.416  1018  1130 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-31 11:29:56.416  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
08-31 11:29:56.416  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
08-31 11:29:56.416  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:29:56.416  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 11:29:56.416  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:56.416  1018  1125 V NetworkStats: performPollLocked() took 3ms
08-31 11:29:56.416  1018  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-31 11:29:56.416  1190  1190 D StatusBar.NetworkController: EthernetConnected: false
08-31 11:29:56.416  1190  1190 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-31 11:29:56.416  1190  1190 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-31 11:29:56.416  1190  1190 D StatusBar.NetworkController: updateDataNetType()
08-31 11:29:56.416  1190  1680 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 11:29:56.426  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:56.426  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-31 11:29:56.426  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:56.426  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:29:56.426  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:56.426  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cae4cca added. We now have 9 listener(s)
08-31 11:29:56.426  6662  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:29:56.426  1190  1190 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-31 11:29:56.426  1190  1190 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-31 11:29:56.426  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:56.426  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 11:29:56.426  1018  1126 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-31 11:29:56.426  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:56.426  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:56.426  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:56.426  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:56.426  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 11:29:56.426  4482  4482 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-31 11:29:56.426  4482  4482 I NearbySettings: MountReceiver.onReceive - Keep current state
08-31 11:29:56.436  1190  1190 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-31 11:29:56.436  1190  1190 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 24 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,08-31 11:29:56.436  1190  1190 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-31 11:29:56.436  1190  1190 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-31 11:29:56.436  1190  1190 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 11:29:56.436  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-31 11:29:56.436  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:56.436  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:56.436  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:56.436  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:56.436  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 11:29:56.436  6662  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 11:29:56.436  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 11:29:56.436  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:56.436  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:56.436  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:56.436  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:56.436  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:56.436  6662  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 11:29:56.446  1018  3255 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 11:29:56.446  6662  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:56.446  1018  3255 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 11:29:56.446  6662  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 11:29:56.446  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 11:29:56.446  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d5f1958 added. We now have 3 listener(s)
,08-31 11:29:56.446  1018  3255 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:56.446  1018  3255 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:56.446  1018  3255 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 11:29:56.446  1631  1631 I Hs20UtilService: Starting #24
,08-31 11:29:56.446  1631  1655 I Hs20UtilService: Message received 5007
,08-31 11:29:56.446  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:56.446  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 11:29:56.456  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-31 11:29:56.456  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 11:29:56.456  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 11:29:56.456  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 11:29:56.456  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d46cab1 added. We now have 10 listener(s)
08-31 11:29:56.456  6662  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 11:29:56.456  6662  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 11:29:56.456  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 11:29:56.456  6662  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 11:29:56.456  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:56.456  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:56.456  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 11:29:56.456  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:56.456  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17b36035 removed from the list
08-31 11:29:56.456  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:56.456  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cae4cca removed from the list
08-31 11:29:56.456  6662  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-31 11:29:56.456  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:56.456  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:56.456  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 11:29:56.456  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-31 11:29:56.456  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:56.456  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:56.456  6662  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cae4cca not in the list
08-31 11:29:56.456  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 11:29:56.456  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:56.456  4482  4482 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 11:29:56.456  4482  4482 I NearbySettings: MountReceiver.onReceive - Keep current state
08-31 11:29:56.456  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 11:29:56.456  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 11:29:56.456  6662  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 11:29:56.456  6662  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d46cab1 removed from the list
08-31 11:29:56.456  6662  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 11:29:56.456  6662  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 11:29:56.456  6662  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 11:29:56.456  6662  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 11:29:56.456  6662  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d5f1958 removed from the list
08-31 11:29:56.456  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-31 11:29:56.456  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-31 11:29:56.456  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-31 11:29:56.456  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 11:29:56.456  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-31 11:29:56.456  6662  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-31 11:29:56.466  1018  1720 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-31 11:29:56.466  6662  7606 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1354, name: My test thread name)
,08-31 11:29:56.466  1018  1218 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,08-31 11:29:56.466  1018  1218 D SecContentProvider2: mCursor = null
08-31 11:29:56.466  6662  7606 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1354, thread name: My test thread name)
08-31 11:29:56.466  6662  7606 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1354, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-31 11:29:56.466  1018  1496 D SecContentProvider2: uri = 15 selection = getToastGravity
08-31 11:29:56.466  1018  1496 D SecContentProvider2: mCursor = null
,08-31 11:29:56.466  1018  1490 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,08-31 11:29:56.466  1018  1490 D SecContentProvider2: mCursor = null
08-31 11:29:56.466  6662  7607 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1356, name: My test thread name)
08-31 11:29:56.466  6662  7607 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1356, thread name: My test thread name)
08-31 11:29:56.466  6662  7607 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1356, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-31 11:29:56.466  1018  1030 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,08-31 11:29:56.466  1018  1030 D SecContentProvider2: mCursor = null
,08-31 11:29:56.476  6662  6834 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-31 11:29:56.476  6662  6834 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-31 11:29:56.476  6662  6834 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-31 11:29:56.476  6662  6834 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-31 11:29:56.476  6662  6834 D com.test.thalitest.ThaliTestRunner: Total duration: 23376 ms
,08-31 11:29:56.476  6662  6834 I jxcore-log: Total number of executed tests:  80
08-31 11:29:56.476  6662  6834 I jxcore-log: 
,08-31 11:29:56.476  6662  6834 I jxcore-log: Number of passed tests:  80
08-31 11:29:56.476  6662  6834 I jxcore-log: 
08-31 11:29:56.476  6662  6834 I jxcore-log: Number of failed tests:  0
08-31 11:29:56.476  6662  6834 I jxcore-log: 
,08-31 11:29:56.476  6662  6834 I jxcore-log: Number of ignored tests:  0
08-31 11:29:56.476  6662  6834 I jxcore-log: 
08-31 11:29:56.476  6662  6834 I jxcore-log: Total duration:  23376
08-31 11:29:56.476  6662  6834 I jxcore-log: 
08-31 11:29:56.476  6662  6834 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-31 11:29:56.476  6662  6834 I jxcore-log: 
08-31 11:29:56.476  1018  3255 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-31 11:29:56.476  1018  3255 D SecContentProvider2: mCursor = null
08-31 11:29:56.476  6662  6834 I jxcore-log: My device name is: samsung-SM-A300FU
08-31 11:29:56.476  6662  6834 I jxcore-log: 
08-31 11:29:56.476  1018  1494 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-31 11:29:56.476  1018  1494 D SecContentProvider2: mCursor = null
08-31 11:29:56.476  6662  6834 I jxcore-log: WARN testUtils: myNameCallback not set!
08-31 11:29:56.476  6662  6834 I jxcore-log: 
,08-31 11:29:56.486  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:56.486  6662  6834 I jxcore-log: 
08-31 11:29:56.486  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:56.486  6662  6834 I jxcore-log: 
08-31 11:29:56.486  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:56.486  6662  6834 I jxcore-log: 
08-31 11:29:56.486  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:56.486  6662  6834 I jxcore-log: 
08-31 11:29:56.486  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:56.486  6662  6834 I jxcore-log: 
,08-31 11:29:56.496  1018  7568 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-31 11:29:56.496  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:56.496  6662  6834 I jxcore-log: 
,08-31 11:29:56.496  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:29:56.496  6662  6834 I jxcore-log: 
08-31 11:29:56.496  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:29:56.496  6662  6834 I jxcore-log: 
08-31 11:29:56.496  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 11:29:56.496  6662  6834 I jxcore-log: 
08-31 11:29:56.496  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:29:56.496  6662  6834 I jxcore-log: 
08-31 11:29:56.496  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 11:29:56.496  6662  6834 I jxcore-log: 
08-31 11:29:56.496  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:29:56.496  6662  6834 I jxcore-log: 
08-31 11:29:56.496  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:29:56.496  6662  6834 I jxcore-log: 
08-31 11:29:56.496  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:29:56.496  6662  6834 I jxcore-log: 
,08-31 11:29:56.496  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:29:56.496  6662  6834 I jxcore-log: 
08-31 11:29:56.496  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:29:56.496  6662  6834 I jxcore-log: 
08-31 11:29:56.506  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 11:29:56.506  6662  6834 I jxcore-log: 
08-31 11:29:56.506  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:29:56.506  6662  6834 I jxcore-log: 
,08-31 11:29:56.506  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 11:29:56.506  6662  6834 I jxcore-log: 
08-31 11:29:56.506  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 11:29:56.506  6662  6834 I jxcore-log: 
08-31 11:29:56.506  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 11:29:56.506  6662  6834 I jxcore-log: 
,08-31 11:29:56.506  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 11:29:56.506  6662  6834 I jxcore-log: 
08-31 11:29:56.506  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-31 11:29:56.506  6662  6834 I jxcore-log: 
08-31 11:29:56.506  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 11:29:56.506  6662  6834 I jxcore-log: 
08-31 11:29:56.506  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 11:29:56.506  6662  6834 I jxcore-log: 
,08-31 11:29:56.506  6662  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 11:29:56.506  6662  6834 I jxcore-log: 
,08-31 11:29:56.506   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast,
,08-31 11:29:56.516  1018  1720 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018
,08-31 11:29:56.526  1190  1190 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-31 11:29:56.546  6662  6662 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 11:29:56.566  1018  7568 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 09:29:56 GMT], X-Android-Received-Millis=[1472635796575], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472635796546]}
,08-31 11:29:56.566  1018  7568 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,08-31 11:29:56.566  1018  7568 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-31 11:29:56.566  1018  1130 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-31 11:29:56.566  1018  1130 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-31 11:29:56.566  1018  1130 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-31 11:29:56.566  1018  1130 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-31 11:29:56.566  1018  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-31 11:29:56.566  1190  1680 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-31 11:29:56.576  1190  1190 D StatusBar.NetworkController: EthernetConnected: false
,08-31 11:29:56.576  1190  1190 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-31 11:29:56.576  1190  1190 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
,08-31 11:29:56.576  1190  1190 D StatusBar.NetworkController: updateDataNetType()
,08-31 11:29:56.576  1190  1190 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-31 11:29:56.576  1190  1190 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-31 11:29:56.576  1190  1190 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-31 11:29:56.576  1190  1190 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 24 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,08-31 11:29:56.576  1190  1190 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
,08-31 11:29:56.576  1190  1190 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-31 11:29:56.576  1190  1190 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 11:29:56.576  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-31 11:29:56.586  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:56.586  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:56.586  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 11:29:56.586  1190  1190 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 11:29:56.696  6662  6662 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,08-31 11:29:56.756  7609  7609 D AndroidRuntime: ,
08-31 11:29:56.756  7609  7609 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-31 11:29:56.766  7609  7609 D AndroidRuntime: CheckJNI is OFF,
08-31 11:29:56.766  7609  7609 D AndroidRuntime: readGMSProperty: start
08-31 11:29:56.766  7609  7609 D AndroidRuntime: readGMSProperty: already setted!!
08-31 11:29:56.766  7609  7609 D AndroidRuntime: propertySet: couldn't set property (it is from app)
,08-31 11:29:56.766  7609  7609 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 11:29:56.766  7609  7609 D AndroidRuntime: readGMSProperty: end
08-31 11:29:56.766  7609  7609 D AndroidRuntime: addProductProperty: start
,08-31 11:29:56.886  7609  7609 E AffinityControl: AffinityControl: registerfunction enter,
,08-31 11:29:56.906  6662  6662 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 11:29:56.916  1018  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,08-31 11:29:56.926  7609  7609 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-31 11:29:56.926  1018  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:29:56.936  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-31 11:29:56.946  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:56.946  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:56.946  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:56.946  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:56.946  1018  1218 D PackageManager: START PACKAGE DELETE: observer{468740455}
08-31 11:29:56.946  1018  1218 D PackageManager: pkg{<packageName>}
08-31 11:29:56.946  1018  1218 D PackageManager: user{0}
08-31 11:29:56.946  1018  1218 D PackageManager: caller{2000}
08-31 11:29:56.946  1018  1218 D PackageManager: flags{2}
,08-31 11:29:56.946  1018  1218 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,08-31 11:29:56.956  1018  1218 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-31 11:29:56.956  6662  6662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 11:29:56.956  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-31 11:29:56.956  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 11:29:56.956  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 11:29:56.956  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 11:29:56.956  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 11:29:56.956  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 11:29:56.956  6662  6662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 11:29:56.956  1018  1218 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-31 11:29:56.956  1018  1218 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-31 11:29:56.956  1018  1218 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-31 11:29:56.956  1018  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-31 11:29:56.956  1018  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-31 11:29:56.956  1018  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-31 11:29:56.956  1018  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
08-31 11:29:56.956  1018  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-31 11:29:56.956  6662  6662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 11:29:56.966  7620  7620 E Zygote  : MountEmulatedStorage(),
08-31 11:29:56.966  7620  7620 E Zygote  : v2
,08-31 11:29:56.966  7620  7620 I libpersona: KNOX_SDCARD checking this for 1000
08-31 11:29:56.966  7620  7620 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:56.966  1018  1056 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,08-31 11:29:56.966  7620  7620 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:56.966  1018  1043 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7620 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,08-31 11:29:56.966  1018  1043 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,08-31 11:29:56.976  1018  1043 I ActivityManager: Killing 6662:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-31 11:29:56.976  1018  1043 I ActivityManager:   Force finishing activity ActivityRecord{2602a496 u0 com.test.thalitest/.MainActivity t163}
08-31 11:29:56.976  7620  7620 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:56.976  7620  7620 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 11:29:56.976  1018  1043 D InputDispatcher: Focus left window: 6662
08-31 11:29:56.986   257   454 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
08-31 11:29:56.986   257   452 I SurfaceFlinger: id=13 Removed NainActivit (-2/9),
,08-31 11:29:56.996  1018  1043 D InputDispatcher: Focused application released
,08-31 11:29:56.996  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 11:29:56.996  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-31 11:29:57.006  7620  7620 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:57.006  7620  7620 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:57.096  1018  1056 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,08-31 11:29:57.116  1018  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-31 11:29:57.136  1018  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 11:29:57.146  6073  6073 I art     : Explicit concurrent mark sweep GC freed 2081(119KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 642us total 31.611ms
,08-31 11:29:57.146  7620  7620 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-31 11:29:57.146  7620  7620 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-31 11:29:57.146  7620  7620 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-31 11:29:57.156  1973  1973 E SamsungIME: mOCRHelper is null
,08-31 11:29:57.156  1739  1939 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-31 11:29:57.166  7620  7620 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-31 11:29:57.166  7620  7620 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-31 11:29:57.166  7620  7620 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-31 11:29:57.166  7620  7620 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:29:57.176  1018  1125 V NetworkStats: removeUidsLocked() for UIDs [10170]
08-31 11:29:57.176  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:57.176  1018  1125 V NetworkStats: performPollLocked(flags=0x3)
,08-31 11:29:57.186  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:29:57.186  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:29:57.186  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:57.186  1018  1125 V NetworkStats: performPollLocked() took 5ms
08-31 11:29:57.186  1018  1018 D RCPManagerService: PackageReceiver onReceive()
,08-31 11:29:57.186  1018  1218 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
08-31 11:29:57.186  1018  1218 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
,08-31 11:29:57.186  1018  1218 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver,
,08-31 11:29:57.186  1018  1218 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
08-31 11:29:57.196  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-31 11:29:57.196  1448  1448 D PersonaManager: isKioskContainerExistOnDevice
,08-31 11:29:57.206  1018  1218 I ActivityManager: Killing 7107:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-31 11:29:57.206  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-31 11:29:57.206  1018  1018 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-31 11:29:57.206  1018  1018 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-31 11:29:57.206  1448  1448 D RegisteredServicesCache: empty dynamic service
,08-31 11:29:57.216  1018  1018 I OTPFW   : ProvisionData::getAllEntries Enter
,08-31 11:29:57.226  1018  1018 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-31 11:29:57.226  1018  1030 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-31 11:29:57.226  1018  1030 D SecContentProvider2: mCursor = null
,08-31 11:29:57.236  1448  1448 D RegisteredComponentCache: Collect Tech packages for Knox
,08-31 11:29:57.246  1448  1448 D PersonaManager: isKioskContainerExistOnDevice
,08-31 11:29:57.266  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:57.266  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:57.276  1018  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
,08-31 11:29:57.276  1018  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-31 11:29:57.276  1018  1042 W TextServicesManagerService: no available spell checker services found
,08-31 11:29:57.286  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:29:57.296  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:29:57.296  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:29:57.306  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:29:57.346  1018  1056 I art     : Explicit concurrent mark sweep GC freed 71038(4MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 23MB/34MB, paused 3.121ms total 186.528ms
,08-31 11:29:57.396  1018  1130 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-31 11:29:57.396  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:57.396  1018  1130 V NetworkStats: updateIfacesLocked()
08-31 11:29:57.396  1018  1130 V NetworkStats: performPollLocked(flags=0x1)
,08-31 11:29:57.396  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 11:29:57.396  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 11:29:57.396  1018  1130 V NetworkStats: performPollLocked() took 4ms
08-31 11:29:57.396  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:57.406  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 11:29:57.406  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 11:29:57.406  1018  1130 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-31 11:29:57.406  1018  1130 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-31 11:29:57.406  1190  1680 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-31 11:29:57.406  1018  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
08-31 11:29:57.406  1190  1680 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-31 11:29:57.416  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-31 11:29:57.416  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:29:57.416  1018  1130 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-31 11:29:57.416  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-31 11:29:57.416  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-31 11:29:57.416  1018  1018 V EnterpriseBillingPolicy: uID is 10170
08-31 11:29:57.416  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
08-31 11:29:57.416  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-31 11:29:57.416  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,08-31 11:29:57.426  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
,08-31 11:29:57.426  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 11:29:57.426  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
,08-31 11:29:57.426  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-31 11:29:57.426  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-31 11:29:57.426  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-31 11:29:57.426  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-31 11:29:57.426  1018  1018 V EnterpriseBillingPolicy: uID is 10170
08-31 11:29:57.426  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
08-31 11:29:57.426  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-31 11:29:57.426  1018  2869 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-31 11:29:57.426  1018  1163 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,08-31 11:29:57.426  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-31 11:29:57.426  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-31 11:29:57.426  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-31 11:29:57.426  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-31 11:29:57.426  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-31 11:29:57.426  1018  1018 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,08-31 11:29:57.436  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:29:57.446  1018  1056 D PackageManager: delete codoeFile: 
,08-31 11:29:57.446  1018  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-31 11:29:57.446  1018  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 11:29:57.446  1018  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-31 11:29:57.456  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:29:57.456  1018  1056 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
,08-31 11:29:57.456  1018  1056 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,08-31 11:29:57.456  1018  1056 D PackageManager: result of delete: 1{468740455}
08-31 11:29:57.466  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:29:57.466  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:29:57.466  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 11:29:57.466  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-31 11:29:57.476  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
08-31 11:29:57.476  7609  7609 D AndroidRuntime: Shutting down VM
,08-31 11:29:57.476  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 11:29:57.476  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-31 11:29:57.476  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
08-31 11:29:57.476  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-31 11:29:57.476  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 11:29:57.486  1018  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-31 11:29:57.486  1018  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-31 11:29:57.506  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-31 11:29:57.506  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:57.506  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:57.506  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:57.506  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:57.516  1018  1018 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7637 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-31 11:29:57.526  7637  7637 E Zygote  : MountEmulatedStorage()
08-31 11:29:57.526  7637  7637 I libpersona: KNOX_SDCARD checking this for 10001
08-31 11:29:57.526  7637  7637 E Zygote  : v2
,08-31 11:29:57.526  7637  7637 I libpersona: KNOX_SDCARD not a persona
08-31 11:29:57.526  7637  7637 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:57.526  7637  7637 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-31 11:29:57.526  7637  7637 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:57.546  7637  7637 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:57.546  7637  7637 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:57.596  7125  7125 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-31 11:29:57.596  7125  7125 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-31 11:29:57.596  7125  7125 I DIAGMON_AGENT: ./extraInfo: "NG700"
,08-31 11:29:57.596  7125  7125 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-31 11:29:57.686  7609  7609 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-31 11:29:57.706  7140  7140 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-31 11:29:57.706  7140  7140 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
08-31 11:29:57.716  1018  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-31 11:29:57.716  1018  1056 D PackageManager: userId{-1}
08-31 11:29:57.716  1018  1056 D PackageManager: andCode{true}
08-31 11:29:57.716  7140  7140 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,08-31 11:29:57.716  1018  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-31 11:29:57.716  1018  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:57.716  1018  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:57.716  1018  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 11:29:57.716  1018  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 11:29:57.716  7140  7140 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,08-31 11:29:57.726  7657  7657 E Zygote  : MountEmulatedStorage()
08-31 11:29:57.726  7657  7657 E Zygote  : v2
08-31 11:29:57.726  7657  7657 I libpersona: KNOX_SDCARD checking this for 10003
08-31 11:29:57.726  7657  7657 I libpersona: KNOX_SDCARD not a persona
,08-31 11:29:57.736  7657  7657 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-31 11:29:57.736  7657  7657 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-31 11:29:57.736  1018  1056 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7657 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-31 11:29:57.736  7657  7657 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 11:29:57.746  1018  2890 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 11:29:57.756  1018  3256 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-31 11:29:57.756  1018  1720 I ActivityManager: Killing 7157:com.sec.android.soagent/u0a31 (adj 15): empty #21
08-31 11:29:57.756  1018  3256 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4240, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-31 11:29:57.756  1018  3256 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-31 11:29:57.756  1018  3256 D BatteryService: stay LED for charging
08-31 11:29:57.756  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 11:29:57.766  1018  1018 I MotionRecognitionService: Plugged
08-31 11:29:57.766  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 11:29:57.766  7657  7657 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 11:29:57.766  7657  7657 D ActivityThread: Added TimaKeyStore provider
,08-31 11:29:57.776  1190  1190 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-31 11:29:57.776  1190  1190 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 11:29:57.786  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-31 11:29:57.786  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-31 11:29:57.796  2788  2788 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-31 11:29:57.806  2788  7529 D HeadsetStateMachine: Disconnected process message: 10
08-31 11:29:57.806  1018  1322 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-31 11:29:57.806  1018  1322 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-31 11:29:57.806  1018  1322 W ActivityManager: userId = 0, bbcId = -10000,
08-31 11:29:57.806  1018  1322 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 11:29:57.806  1018  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-31 11:29:57.806  1190  1190 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-31 11:29:57.806  1190  1190 D SViewCoverView: level :100 plugged : 2
,08-31 11:29:57.816  1190  1190 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 11:29:57.816  1190  1190 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 11:29:57.816  1190  1190 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-31 11:29:57.826   277   963 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-31 11:29:57.826   277   963 D Netd    : getNetworkForDns: using netid 504 for uid 10011
,08-31 11:29:57.826  1847  1847 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-31 11:29:57.836  1847  4752 I iu.UploadsManager: num queued entries: 0
,08-31 11:29:57.836  1847  4752 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,08-31 11:29:57.836  1847  4752 E SQLiteLog: (3850) statement aborts at 61: [UPDATE media_record SET upload_state=? WHERE upload_account_id != -1 AND upload_state = 200] disk I/O error
,08-31 11:29:57.836  1018  1490 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 11:29:57.836  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
08-31 11:29:57.836  1847  4752 E AndroidRuntime: FATAL EXCEPTION: iu-sync-manager
08-31 11:29:57.836  1847  4752 E AndroidRuntime: Process: com.google.android.gms, PID: 1847
08-31 11:29:57.836  1847  4752 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 11:29:57.836  1847  4752 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 11:29:57.836  1847  4752 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
08-31 11:29:57.836  1847  4752 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 11:29:57.836  1847  4752 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 11:29:57.836  1847  4752 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1714)
08-31 11:29:57.836  1847  4752 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1660)
08-31 11:29:57.836  1847  4752 E AndroidRuntime: 	at com.google.android.libraries.social.autobackup.ae.a(SourceFile:403)
08-31 11:29:57.836  1847  4752 E AndroidRuntime: 	at com.google.android.libraries.social.autobackup.j.a(SourceFile:307)
08-31 11:29:57.836  1847  4752 E AndroidRuntime: 	at com.google.android.libraries.social.autobackup.j.b(SourceFile:43)
08-31 11:29:57.836  1847  4752 E AndroidRuntime: 	at com.google.android.libraries.social.autobackup.l.handleMessage(SourceFile:218)
08-31 11:29:57.836  1847  4752 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 11:29:57.836  1847  4752 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-31 11:29:57.836  1847  4752 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 11:29:57.836  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-31 11:29:57.836  1018  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 11:29:57.836  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 11:29:57.846  1018  1720 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,08-31 11:29:57.846  1847  1847 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 11:29:57.856  1847  1847 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,08-31 11:29:57.856  1018  7675 E DropBoxManagerService: Can't write: system_app_crash
08-31 11:29:57.856  1018  7675 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop192.tmp: open failed: EROFS (Read-only file system)
08-31 11:29:57.856  1018  7675 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-31 11:29:57.856  1018  7675 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 11:29:57.856  1018  7675 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 11:29:57.856  1018  7675 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 11:29:57.856  1018  7675 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-31 11:29:57.856  1018  7675 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
08-31 11:29:57.856  1018  7675 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 11:29:57.856  1018  7675 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 11:29:57.856  1018  7675 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 11:29:57.856  1018  7675 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 11:29:57.856  1018  7675 E DropBoxManagerService: 	... 5 more
,08-31 11:29:57.876  2928  2928 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 31 11:29:57 GMT+02:00 2016
,08-31 11:29:57.876  1018  1031 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-31 11:29:57.876  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-31 11:29:57.876  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-31 11:29:57.876  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 11:29:57.876  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-31 11:29:57.876  1847  4752 I Process : Sending signal. PID: 1847 SIG: 9
,08-31 11:29:57.876   254   254 E lowmemorykiller: Error writing /proc/1847/oom_score_adj; errno=22
,08-31 11:29:57.886  1018  1489 I ActivityManager: Killing 7174:com.sec.spp.push/u0a32 (adj 15): empty #21

```
